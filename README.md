# kafka-zookeper

Run the following two commands:
  - docker-compose -f mul-zk-mul-kafka.yml up

To scale the services use
  - docker-compose -f mul-zk-mul-kafka.yml scale kafka1=3 zoo1=3

To bring down the services
  - docker-compose -f mul-zk-mul-kafka.yml down
