##mongodump
**Export MongoDB data to BSON files.**

-h:指明数据库宿主机的IP\n
-u:指明数据库的用户名
-p:指明数据库的密码
-d:指明数据库的名字
-c:指明collection的名字
-o:指明到要导出的文件名
-q:指明导出数据的过滤条件

`./bin/mongodump -d test -o /tmp`

##mongostore
-h:指明数据库宿主机的IP
-u:指明数据库的用户名
-p:指明数据库的密码
-d:指明数据库的名字
-c:指明collection的名字
-o:指明到要备份的文件名
-q:指明备份数据的过滤条件

`./bin/mongorestore -d test --drop data/backup/test/`