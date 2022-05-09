# kafka-study

## commands
1. daemon형태로 zookeeper실행, 정지  
    `bin/zookeeper-server-start.sh -daemon config/zookeeper.properties`  
    `bin/zookeeper-server-stop.sh`
2. kafka 실행, 정지  
    `bin/kafka-server-start.sh -daemon config/server.properties`  
   `bin/kafka-server-stop.sh`
3. 실행확인  
    `netstat -an | grep 2181`
4. 토픽생성  
    `bin/kafka-topics.sh --create --topic quickstart-events --bootstrap-server localhost:9092 --partitions 1 --replication-factor 1`

## refs
1. quickstart `kafka/config/kraft/README.md`
2. https://somjang.tistory.com/entry/Kafka-Mac%EC%97%90-%EC%B9%B4%ED%94%84%EC%B9%B4-%EC%84%A4%EC%B9%98%ED%95%98%EA%B3%A0-%EC%8B%A4%ED%96%89%ED%95%B4%EB%B3%B4%EA%B8%B0
3. 

