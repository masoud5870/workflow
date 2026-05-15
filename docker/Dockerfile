FROM wordpress:latest

# Hardening: حذف فایل‌های پیش‌فرض برای کاهش سطح حمله
RUN rm /var/www/html/readme.html /var/www/html/license.txt

# تغییر کاربر به غیر ریشه (Non-root user) طبق اهداف پروژه
USER www-data
