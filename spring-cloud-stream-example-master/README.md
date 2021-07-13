# spring-cloud-stream-example
install docker desktop

go to the directory where you have the below yml file and run (spring-cloud-stream-example-master/apacheConfluent.yml)

docker-compose -f apacheConfluent.yml up -d

open http://localhost:8082


create new topic "testTopic"

then run the application both spring-cloud-stream/spring-cloud-stream-example-master/spring-cloud-stream-consumer and spring-cloud-stream/spring-cloud-stream-example-master/spring-cloud-stream-publisher


