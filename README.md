# ActiveMQ Knowledge
## Queue
## Topic
## Producer features
## Consumer features
<details>
<summary>Durable subscribers</summary>
</details>
<details>
<summary>Virtual Topic</summary>
</details>

## Spring Integration with Active MQ

<details>
<summary>Setup</summary>
<br/>
  Add dependencies:
  
  ```
  <dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-jms</artifactId>
  </dependency>

  <dependency>
    <groupId>org.apache.activemq</groupId>
    <artifactId>activemq-all</artifactId>
  </dependency>
   ``` 

To configure a integration between Active MQ and Spring Integration, you need to define beans as follows: 
+ **@EnableJms** : Enable JMS auto-configuration in Spring.
+ **ActiveMQConnectionFactory** :
+ **JmsTemplate** :
+ **DefaultJmsListenerContainerFactory** :

</details>
