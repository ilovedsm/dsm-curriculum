
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

### **버전 관리**

GIT

GIT Flow (git branch 전략)

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

### 실시간

- Polling
- SSE(Server Sent Event)
- Streaming
- WebSocket

### **Test Tool**

- Postman
- Insomnia

### **API Docs**

필요성 이해

- Swagger
- Redoc
- Slate

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

### CI (Continuous Integration)

- Travis-CI
- Jenkins
- Circle-CI

### **클라이언트와의 연동**

- CORS (Cross-Origin Resource Sharing) 개념
- 도메인과 호스팅

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

### 캐싱

- Redis
- memcached

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

Heroku

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

### **Agenda**

- CRUD가 가능한 게시판 구현 (4단계 수행)
- Compute Engine 결정과 hello world 서버 배포

# Anything Else?

### **크롤링 Crawling (anything Else)**

- 크롤링의 개념 (데이터 수집과 대용량 데이터 처리)
- 라이브러리를 이용할 크롤링
- selenium 을 이용한 고수준의 크롤링

- [44bits.io](notion://www.notion.so/applebox/44bits.io) : 백엔드 및 클라우드쪽의 편향적인 지식을 얻을 수 있는 블로그. 트렌디한 기술 스택을 소개해준다.
- [roadmap.sh](http://roadmap.sh/) or [[Github] 2019년 웹 개발자가 되기 위한 로드맵](https://github.com/devJang/developer-roadmap)
: 백엔드 및 프론트엔드, 데브옵스가 되는 과정을 담은 로드맵
