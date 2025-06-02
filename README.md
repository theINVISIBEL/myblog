# 📰 Django Blog - مدونة احترافية باستخدام Django

مشروع مدونة شخصية مبني باستخدام إطار العمل Django، يتيح للمستخدمين تصفح المقالات، إنشاء محتوى جديد، والتفاعل من خلال التعليقات. تم تطوير هذا المشروع كجزء من بورتفوليودي الشخصي لعرض مهاراتي في تطوير تطبيقات الويب باستخدام Python وDjango.

---

## 🚀 الميزات الأساسية:

- 📝 إنشاء وتعديل وحذف المقالات
- 🔎 نظام بحث متقدم عن المقالات
- 🗂️ تصنيفات ووسوم (Categories & Tags)
- 💬 نظام تعليقات للمستخدمين
- 🧑‍💻 لوحة تحكم للمشرف (Admin Panel)
- 🔐 تسجيل دخول وخروج للمستخدمين
- 🌙 تصميم متجاوب (Responsive)

---

## 🛠️ التقنيات المستخدمة:

- Python 3.x
- Django 4.x
- HTML5, CSS3, JavaScript
- Bootstrap 5
- SQLite (أو PostgreSQL)

---

## ⚙️ خطوات التشغيل:

```bash
# 1. استنساخ المشروع
git clone https://github.com/username/django-blog.git
cd django-blog

# 2. إنشاء بيئة افتراضية
python -m venv env
source env/bin/activate  # أو env\Scripts\activate على ويندوز

# 3. تثبيت الحزم
pip install -r requirements.txt

# 4. تنفيذ الترحيلات
python manage.py migrate

# 5. إنشاء مستخدم مشرف
python manage.py createsuperuser

# 6. تشغيل الخادم المحلي
python manage.py runserver

