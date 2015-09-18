Step # 1: Backup existing database and wordpress directory

Type the following commands at shell prompt:

$ mkdir /backup/wp/28nov2006
$ mysqldump -u user -p WP-DATABASENAME > /backup/wp/28nov2006/blog.db.sql
$ tar -zcvf /backup/wp/28nov2006.tar.gz /var/www/html/blog


Step # 2: Download latest wordpress CMS

$ cd /tmp
$ wget http://wordpress.org/latest.zip
$ unzip latest.zip


$ cd /var/www/html/blog
$ yes | cp -fr /tmp/wordpress/* .
$ rm -rf /tmp/wordpress /tmp/latest.zip
