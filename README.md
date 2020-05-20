composer self-update // Fix Trying to access array offset on value of type null

Khi chạy php artisan serve, thay đổi thông tin .env thì phải restart service để đọc lại file .env

<VirtualHost *:80> 
    DocumentRoot "D:\PROGRAM\laragon\www\LARAVEL-PROJECT\laragis\public"
    ServerName laragis.local 
    ServerAlias *.laragis.local 
    <Directory "D:\PROGRAM\laragon\www\LARAVEL-PROJECT\laragis\public">
        AllowOverride All
        Require all granted
    </Directory>	
</VirtualHost>
