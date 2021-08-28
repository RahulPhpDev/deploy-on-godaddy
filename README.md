# deploy-on-godaddy

Upload laravel project on c-panel is easy 


### here is the step we need to do 

**Deploy your app in c-panel**


> now go to the inside project


> Reame server.php to **index.php**


```
copy or create a new ***.htaccess*** file in root directory 

and put following code in this .htacess
it will remove public after the url 

```

```
 
<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteRule ^(.*)$ public/$1 [L]
</IfModule>



 ***


> Happy Coding

***
