# DSM Backend Curriculum

백엔드 개발자를 목표로 하고 있는 친구들, 그리고 서버 개발을 배우고 싶은 친구들이 백엔드 분야에 도전하는 것을 도와주기 위해 이 커리큘럼을 작성하게 되었습니다.



체계적이고 단계적인 학습을 위해 단계를 나누었습니다. 단계에 적힌 순서를 무조건 따라야 하는 것은 아니며 유동적으로 판단하여 학습하시길 바랍니다. 또한 단계 별로 챌린지를 설정해두었습니다. 공부를 하기 전 목표를 세우고 그것을 이루어내었을 때의 `성취감`을 얻길 바랍니다.



마지막으로 학습의 재미는 자신만의 커리큘럼과 공부법을 찾아가는 것에 있다고 생각합니다. 이 커리큘럼을 참고하되 맹목적으로 따르지 말고 `왜 이것을 배워야 하는가?` 를 스스로에게 끊임없이 질문하세요.



## STEP 1

> Challenge #1: 자신만의 언어를 정하고 그 언어로 간단한 미니 프로젝트 하나를 완성시켜보자.

### 서버-클라이언트 구조 이해

1. 네트워크의 등장
2. 클라이언트-클라이언트(Peer to Peer)
3. 서버-클라이언트

[Peer to Peer (P2P) 방식과 Client/Server (CS)](http://www.gameserverlab.com/archives/312)



### 언어 결정

다른 직군과는 달리, 프로그래밍 언어 선택지가 많은 편입니다.

그만큼 언어 당 백엔드 프레임워크도 많고, 무조건 따라하기 보다는 직접 프레임워크를 선택하세요.

1. [[Github] web-frameworks](https://github.com/the-benchmarker/web-frameworks) : 웹 프레임워크들의 벤치마킹 보고서.

   

### Package Manager

Package Manager의 필요성에 대한 고민하기.

예를들어 , **PHP**는 composer, **Node.js** 는 npm과 yarn **Python**은 pip, **Ruby**는 gems



### 풀 스택 프레임워크와 마이크로 프레임워크의 차이



### 프로토콜

OSI 7계층에 대해 알아보기.

- TCP/IP
- HTTP
- HTTP over SSL
- WS



### 버전 관리

GIT

GIT Flow (git branch 전략)



## STEP 2

> Challenge #2 : 인증과 DB 연동 기능이 있는 간단한 게시판을 만들어보자.

### 데이터베이스

- 파일 시스템의 문제점에 대한 이해.
- 데이터베이스 설계와 모델링
- SQL
- DBMS
    - 각 RDBMS 마다의 특징, 각 NoSQL만의 특징 이해하기.
    - MySQL, PostgreSQL, Oracle
    - MongoDB, Redis, Memcached, Aerospike, Neo4j, InfluxDB
- ORM

### 인증

- Cookie
- Session
- Token
    - request header
    - 사용자 지정 헤더 ( ex: X-AccessToken )
    - JWT AccessToken & RefreshToken
- OAuth

### **Test Tool**

- Postman
- Insomnia



## STEP 3

> Challenge #3 : 내 서버를 클라이언트와 연동해보자. 실시간 통신을 배워 클라이언트와 함께 실시간 채팅 서비스를 개발해보자. 혼자 하는 것 보다는 클라이언트를 공부하는 다른 친구와 함께 하는 것을 추천함. 

### **클라이언트와의 연동**

- CORS (Cross-Origin Resource Sharing) 개념
- 도메인과 호스팅

### 실시간

- Polling
- SSE(Server Sent Event)
- Streaming
- WebSocket

### **API Docs**

필요성 이해

- Swagger
- Redoc
- Slate

### PaaS 클라우드

서버를 클라우드에 올려보자

* Heroku

## STEP 4

> Challenge #4 : 그동안 배운 것들을 최대한 활용하여 SNS 서비스 (페이스북, 트위터, 인스타그램) 을 클론 코딩 해보자. 클라이언트 친구와 협업하는 것을 추천함. 그리고  내 서버의 질을 높이기 위한 다양한 시도를 해보자.

### 아키텍쳐/패턴

* RESTful API
* Monolitic Architecture
* MSA (MicroService Architecture)
* Serverless Architecture
* MVC pattern (Model-View-Controller)

### 테스트

- API 개발 입장에서 TDD의 필요성 이해
- 테스트 코드 작성
- TDD의 원칙
- DDD, BDD
- 유닛테스트 라이브러리
- mocking

### 웹 서버

- 아파치
- 톰캣
- nginx

### 캐싱

- Redis
- memcached

### docker

* 컨테이너 , 이미지, 레지스트리 개념
* docker로 서버 배포하기
* docker compose

## STEP 5

> 이제 자신만의 Challenge 를 세우고 수행하자. 더 나은 코드 더 나은 서버 구축을 목표로 하자.

### CI (Continuous Integration)

- Travis-CI
- Jenkins
- Circle-CI

### 배포 자동화

- Ansible
- Chef
- Capistrano
- Puppet
- Fabric

### 로그, 데이터 분석

log 로 남기는 정보들에 대해 알아야 함

log level ( debug:0 > info:1 > notice:2 > warning:3 > error:4 > crit:5 > alert:6 > emerg:7 )

logging 라이브러리 , 자신의 서비스에 맞게 커스텀 해보기

- ELK Stack
- Hadoop
- HDFS
- Spark
- Zeppelin

### 모니터링

- Zabbix
- New Relic
- Grafana, Graphite, Prometheus

### 메시지 큐

- Kafka
- RabbitMQ
- ZeroMQ
- Celery
- Beanstalkd
- Amazon SQS

### **보안**

서버의 취약점에 대해 알고있어야함

- XSS
- CSRF
- SQL injection
- 보안 지원 라이브러리

### **협업**

- Agile 개발론
- 협업 툴 사용 (notion, slack, Jira, 잔디)

### **클라우드 서비스**

Iaas / PaaS / SaaS 의 개념

### AWS 서비스

- 컴퓨팅 : EC2, Elastic Container Service, Lambda, API Gateway
- 스토리지 : S3, EBS, EFS
- 데이터베이스 : Aurora(MySQL 호환 RDB), DynamoDB(Key-value NoSQL 데이터베이스)
- 데이터베이스 관리 : RDS(RDB 관리), ElastiCache(NoSQL 관리), Redshift(데이터 웨어하우스)
- CDN : CloudFront
- 배포 자동화 : CodeDeploy

### GCP 서비스

- 컴퓨팅 : Compute Engine, App Engine, Kubernetes Engine, Container Registry, Cloud Function
- 스토리지 : Cloud Storage
- 데이터베이스 : Cloud Bigtable(대규모 분석 및 운영 작업을 위한 NoSQL 빅데이터 데이터베이스), Cloud Datastore(확장성 높은 NoSQL 데이터베이스)
- 데이터베이스 관리 : Cloud SQL(RDB 관리)
- CDN : Cloud CDN
- 배포 자동화 : Deployment Manager

# Anything Else?

### **크롤링 Crawling (anything Else)**

- 크롤링의 개념 (데이터 수집과 대용량 데이터 처리)
- 라이브러리를 이용할 크롤링
- selenium 을 이용한 고수준의 크롤링

- [44bits.io](notion://www.notion.so/applebox/44bits.io) : 백엔드 및 클라우드쪽의 편향적인 지식을 얻을 수 있는 블로그. 트렌디한 기술 스택을 소개해준다.
- [roadmap.sh](http://roadmap.sh/) or [[Github] 2019년 웹 개발자가 되기 위한 로드맵](https://github.com/devJang/developer-roadmap)
: 백엔드 및 프론트엔드, 데브옵스가 되는 과정을 담은 로드맵
