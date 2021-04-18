SpringBoot+Maven+Mybatis+Redis+RabbitMQ 

## development environment				

| JDK |Maven | Mysql |SpringBoot | redis |RabbitMQ|
|--|--|--|--|--|--|
|1.8 | 3.2.2 | 5.5 | 1.5.9.RELEASE | 3.2 |3.7.14| 



## instructions


1. Download code by git clone to idea

2. Run the SQL file in the SQL folder

3. Go to Src / main / resources application.properties Modify your database link user name and password

4. Install redis, mysql, rabbitmq, Maven and other environments

5. Check the configuration before starting application.properties Address of redis, MySQL and rabbitmq in

6. Set reasonable start time and end time in the database seckill commodity table

7. Login address: http://localhost :8080/login/to_ login

8. Commodity second kill list address: http://localhost :8080/goods/to_ list

##Other instructions

1. There are about 1000 users in the database (mobile phone number: 15200000000 ~ 15200000997, password: 123456), which are prepared for pressure measurement.

2. The mailbox only implements the front-end format verification, and only needs to input a correct mailbox format (for example: xxx@qq.com ）

##Project description

1. Use distributed seesion to enable multiple servers to respond.

2. Use redis as cache to improve access speed and concurrency and reduce database pressure.

3. Use page static, cache page to browser, separate front and back end, reduce server pressure.

4. Use message queue to complete asynchronous order, improve user experience, reduce peak and flow.

5. Security optimization: Double MD5 password verification, seckill interface address hiding, interface current limiting and anti brushing, mathematical formula verification code.
