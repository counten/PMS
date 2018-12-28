## 目录结构
```
/model      	模型文件
/model_img		模型导出图片
/pms 			项目代码
/doc			包含视频，说明文档，PPT，组内评分表
```

## Requirement
1. JDK 1.8+
1. maven 3.3+
1. MySQL/MariaDB
## Just run
1. 运行以下命令，系统会在内存总生成hsqldb数据库。
	```bash
	mvn jetty:run
	```
## Install
```
CREATE DATABASE lavagna CHARACTER SET utf8 COLLATE utf8_general_ci;
create user 'pms123'@'%' identified by 'pms456';
grant all privileges on lavagna.* to "pms123"@"%" identified by "pms456";
flush privileges;
```


## Team member
1. [Xiaodong Lian](https://github.com/donnelian)
1. [Bowie](https://github.com/Carbine416)
1. [printlnCout](https://github.com/printlnCout)