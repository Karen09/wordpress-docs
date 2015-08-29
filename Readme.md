#Docs

##How to install wordpress in directadmin

###Mysql

* Enter the URL http://domain.com:2222/ ( this is the default port for DirectAdmin access ).

* If you are Administrator, you could see the User Level in your right panel, if you are normal user, you could see the MySQL Databases icon there.

* Click on MySQL Management, If you are Administrator.

* Click Create a Database.

###wordpress

* cd /home/DAuser/domains/domain.com/public_html

* wget http://wordpress.org/latest.tar.gz

* tar -zvxf latest.tar.gz

* mv ./wordpress/* ./

* rmdir wordpress

* cp wp-config-sample.php wp-config.php

* vi wp-config.php


###End

Enter http://domain.com/ in your browser then the step will bring you install to finish.

###publick_html page?

* cd /home/DAuser/domains/domain.com/public_html/

* mv public.html public.htmlback


