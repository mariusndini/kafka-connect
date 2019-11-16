### Start Kafka
```
sudo systemctl start kafka
```

### Start Kafka
```
sudo systemctl stop kafka
```

### Consumer
```
./bin/kafka-console-consumer.sh --bootstrap-server 35.225.38.201:9092 --topic TutorialTopic
```

### Producer
```
echo "Hello, World2" | ./bin/kafka-console-producer.sh --broker-list 35.125.38.201:9092 --topic Tuto
rialTopic > /dev/null
```

### Topics
```
./bin/kafka-topics.sh --list --zookeeper localhost:2181
```

### Connector Attempt
```
  547  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariu
sndini/kafka/config/snowflakeconnect.properties
  548  vim config//snowflakeconnect.properties 
  549  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariu
sndini/kafka/config/snowflakeconnect.properties
  550  clear
  551  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariu
sndini/kafka/config/snowflakeconnect.properties
  552  vim config/connect-standalone.properties 
  553  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariu
sndini/kafka/config/snowflakeconnect.properties
  554  vim config/connect-standalone.properties 
  555  vim config/snowflakeconnect.properties 
  556  vim config/connect-standalone.properties 
  557  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariu
sndini/kafka/config/snowflakeconnect.properties
  558  jclear
  559  clear
  560  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties
  561  cd vim
  562  cd config/
  563  ls
  564  clear
  565  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties /home/mariusn
dini/kafka/config/snowflakeconnect.properties
  566  cd ..
  567  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties /home/mariusn
dini/kafka/config/snowflakeconnect.properties
  568  vim config/snowflakeconnect.properties 
  569  clear
  570  ./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties /home/mariusn
dini/kafka/config/snowflakeconnect.properties
  571  ./bin/connect-standalone.sh 
  572  ./bin/connect-standalone.sh config/snowflakeconnect.properties 
  573  ./bin/connect-standalone.sh -daemon config/snowflakeconnect.properties 
  574  ./bin/connect-standalone.sh config/snowflakeconnect.properties 
```










./bin/connect-standalone.sh /home/mariusndini/kafka/config/connect-standalone.properties /home/mariusndini/kafka/config/snowflakeconnect.properties
./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties /home/mariusndini/kafka/config/snowflakeconnect.properties
./bin/connect-standalone.sh /home/mariusndini/kafka/config/snowflakeconnect.properties /home/mariusndini/kafka/config/snowflakeconnect.properties



./bin/kafka-console-consumer.sh --zookeeper localhost:2181 --topic TutorialTopic
./bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic TutorialTopic --from-beginning
./bin/kafka-console-consumer.sh --bootstrap-server 35.125.38.201:9092 --topic TutorialTopic

./bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic TutorialTopic
./bin/kafka-topics.sh --list --zookeeper localhost:2181





./bin/kafka-console-consumer.sh --bootstrap-server 35.225.38.201:9092 --topic TutorialTopic
