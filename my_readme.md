新增两个运行配置文件
> assembly.run.xml 
> 
> portal.run.xml

修改了apollo-assembly/src/main/resources/application.yml 
可能的原因: eureka 启动时，无法及时注册，又因超时时间较短，所以抛错终止了

具体原因，待了解eureka之后
