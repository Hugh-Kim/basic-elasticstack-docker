# basic-elasticstack-docker
docker-compose for basic elastic stack(logstash, elasticsearch, kibana)

elasticsearch 와 kibana는 public docker hub의 latest image를 그대로 사용합니다.
logstash 는 config를 넣어준 상태로 docker image를 만듭니다.

docker-logstash directory 하위에서 아래 명령어로 docker image를 생성합니다.
"docker build -t <user docker image name> ."

logstash 에 대한 docker image 를 생성했다면 docker-compose.yml 이 있는 경로에서 아래 명령어로 elastic stack 을 실행합니다.
"docker-compose up"
