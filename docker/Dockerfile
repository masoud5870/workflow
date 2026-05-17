FROM wordpress:latest

# Hardening: حذف فایل‌های حساس از مسیر اصلی و مسیر موقت برای کاهش سطح حمله
# استفاده از فلگ -f مانع از توقف خط لوله (Pipeline) در صورت عدم وجود فایل می‌شود
RUN rm -f /var/www/html/readme.html /var/www/html/license.txt \
          /usr/src/wordpress/readme.html /usr/src/wordpress/license.txt

# تنظیم اجرای کانتینر با کاربر غیر ریشه برای امنیت بیشتر
USER www-data
