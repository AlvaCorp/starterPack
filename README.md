###################
Starter Pack
###################
1. Helper 
2. Data tables
3. boostrap 
4. font awesome
5. select2
6. JS 
7. datepicker
8. form js

####################
.htaccess
####################
<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteBase /nama_project
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteRule ^(.*)$ index.php?/$1 [L]
</IfModule>
