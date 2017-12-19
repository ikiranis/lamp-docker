## Create Docker with Apache/PHP and Mysql

* Edit **.env** file with your settings

* Run **docker-compose up -d**

* Put your application files in /www folder

You can create your apache image instead of **apps4net/apache** with the command:

**docker build -t apache docker/apache**