FROM WordPress: latest

# حذف فایل‌های حساس برای کاهش سطح حمله
RUN rm /var/www/html/readme.html /var/www/html/license.txt

# تنظیم اجرای کانتینر با کاربر غیر ریشه برای امنیت بیشتر (Hardening)
USER www-data

EXPOSE 80
