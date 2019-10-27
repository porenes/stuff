# Setup WP on mac

1. Install php `brew install php`
2. Edit httpd.conf `sudo subl /etc/apache2/httpd.conf`
   Uncomment `LoadModule php7_module libexec/apache2/libphp7.so`
3. add
```    <FilesMatch \.php$>
        SetHandler application/x-httpd-php
    </FilesMatch>```
    
