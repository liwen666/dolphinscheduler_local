#主页
API  localhost:12345/dolphinscheduler/swagger-ui.html#/
 
 用户加密
        String md5 = EncryptionUtils.getMd5(password);



localhost:8888

localhost:8888
admin/dolphinscheduler123

    MasterServer         ----- master服务
    WorkerServer         ----- worker服务
    LoggerServer         ----- logger服务
    ApiApplicationServer ----- api服务
    AlertServer          ----- alert服务

mysql> CREATE DATABASE dolphinscheduler DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;
mysql> GRANT ALL PRIVILEGES ON dolphinscheduler.* TO '{user}'@'%' IDENTIFIED BY '{password}';
mysql> GRANT ALL PRIVILEGES ON dolphinscheduler.* TO '{user}'@'localhost' IDENTIFIED BY '{password}';
mysql> flush privileges;