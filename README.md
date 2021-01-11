# 记录一些自己感兴趣的技术


### 技术栈
 - 后端: 
    - [Spring boot 2.3.1.RELEASE](https://spring.io/projects/spring-boot)  
    - [Apache Dubbo 2.7.7](https://dubbo.apache.org/en-us/)  
    - [HttpComponents 4.4.13](http://hc.apache.org/)  
    - .......
    
 - 中间件: 
    - [Mongodb 4.2](https://docs.mongodb.com/)  
    - [Zookeeper 3.6](https://zookeeper.apache.org/) 

![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
张飞|骂|三弟
张飞|骂|三弟
张飞|骂|三弟


```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```

```flow 
graph LR 
    start[开始] --> input[输入A,B,C]
    input --> conditionA{A是否大于B}
    conditionA -- YES --> conditionC{A是否大于C}
    conditionA -- NO --> conditionB{B是否大于C}
    conditionC -- YES --> printA[输出A]
    conditionC -- NO --> printC[输出C]
    conditionB -- YES --> printB[输出B]
    conditionB -- NO --> printC[输出C]
    printA --> stop[结束]
    printC --> stop
    printB --> stop
```
