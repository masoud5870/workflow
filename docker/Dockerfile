FROM wordpress:latest

# حذف فایل‌های غیرضروری برای کاهش سطح حمله
RUN rm /var/www/html/readme.html /var/www/html/license.txt

# تنظیم اجرای کانتینر با کاربر غیر ریشه (Non-root user)
USER www-data

EXPOSE 80
