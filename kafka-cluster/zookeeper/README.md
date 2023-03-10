# setup kafka cluster

## Setup

### docker-compose
`docker-compose.yml`에서 {external-ip}를 broker의 외부 IP로 설정한다

[ zookeeper를 포함하여 셋업하는 경우 ]  
- `INTERNAL` : 도커 내부적으로 연결할 경우의 설정
- `EXTERNAL` : 외부에서 연결할 경우의 설정
- `LOCAL` : 로컬에서 연결할 경우의 설정


## Reference
- [Guide to Setting Up Apache Kafka Using Docker](https://www.baeldung.com/ops/kafka-docker-setup)
- [Docker Compose로 멀티브로커 Kafka 구성하기](https://devocean.sk.com/blog/techBoardDetail.do?ID=164016)
- [confluentic-cp-all-in-one](https://github.com/confluentinc/cp-all-in-one/blob/master/cp-all-in-one/docker-compose.yml)
- [kafka client connect to broker](https://www.confluent.io/blog/kafka-client-cannot-connect-to-broker-on-aws-on-docker-etc/)
- [Kafka 설정 listeners vs. advertised.listeners](https://parkcheolu.tistory.com/196)
