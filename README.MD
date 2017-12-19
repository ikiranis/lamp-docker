## Create Docker with Apache/PHP and Mysql

* Edit **.env** file with your settings

* Run **docker-compose up -d**

* It will create 2 containers (Apache Server and Mysql Server)

* **/www** folder will be created

* Put your application files in **/www** folder

* Mysql data files will be in **/docker/mysql/data** folder

You can create your apache image instead of **apps4net/apache** with the command:

**docker build -t apache docker/apache**