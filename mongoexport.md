##mongoexport 导出
##mongoimport 导入

-h:指明数据库宿主机的IP

-u:指明数据库的用户名

-p:指明数据库的密码

-d:指明数据库的名字

-c:指明collection的名字

-f:指明要导出那些列

-o:指明到要导出的文件名

-q:指明导出数据的过滤条件

mongoimport --host mongo-adpro-ssp-rs-1 --port 1301 -d account -c main --upsert /hdd1/ssp-basic-dump-0707/account.json

*--upsert* 已存在数据直接覆盖