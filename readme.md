# The Training for WordPress implementation"

But, you know, they are just a containers php-apache and mysql.
Let's try to install WordPress.
<br>

## Hint
<br>

### download wp in the server
Where is the DocumentRoot of httpd?<br>
Maybe, you can find it to check compose.yml.<br>

If you want to download WordPress in current directory.
```console
wget https://ja.wordpress.org/latest-ja.tar.gz
```
After you dl and unzip WP, check expanded files and directories.<br>
<br>
### install wp
To understand roles of each files and directories, let's read scripts and opretate WP.<br>

Access http://localhost:8080 <br>
running start script of wp, you can input your DB name,user,host,and password.<br>
What are DB infomations? read compose.yml!<br>
Or, you can create wp-config.php. I prefer it.<br>
After you set up WP, create some posts and pages in wp-admin.<br>

