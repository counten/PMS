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
1. 创建数据库 pms
1. 修改pom.xml 去掉下面一段的注释，并修改对应的URL，账户，密码
    ```xml
    <systemProperty>
        <name>datasource.dialect</name>
        <value>MYSQL</value>
    </systemProperty>
    <systemProperty>
        <name>datasource.url</name>
        <value>jdbc:mysql://localhost:3306/pms</value>
    </systemProperty>
    <systemProperty>
        <name>datasource.username</name>
        <value>root</value>
    </systemProperty>
    <systemProperty>
        <name>datasource.password</name>
        <value>160415</value>
    </systemProperty>
    ```
1. 运行以下命令，初次运行时会自动初始化数据库。
	```bash
	mvn jetty:run
	```

## Team member
1. [Xiaodong Lian](https://github.com/donnelian)
1. [Bowie](https://github.com/Carbine416)
1. [printlnCout](https://github.com/printlnCout)