# 보안했던 개발자
보안 분야에서 출발해 의약품 이커머스까지 다양한 서비스 개발을 해왔고 
스타트업 서비스 초기 부터 성장 단계까지 경험한 백엔드 개발자입니다.
Python/Django 기반 서비스 아키텍처 설계와 운영 경험을 보유하고 있습니다.

비즈니스 요구사항의 변화에 유연하게 대응하며 그에 대한 트레이드 오프를 대비합니다.

신기술에 대한 리서치는 좋아하지만 실제 업무에 도입하는것은 신중하게 접근합니다.

문제 해결을 위해 사람들 간의 커뮤니케이션을 좋아하고, 대화의 목적이 승리인 사람과의 협업을 즐거워 하지 않습니다. 
팀원은 경쟁 상대가 아니라 함께 문제를 해결해 나가는 동료라고 생각합니다


## Contact Me 
- Email : ben3787@gmail.com





## 이력
----
### 바로팜
주요업무
- 주문, 결제, 취반품, 정산, 제약사 대상 SaaS 백엔드 서비스 설계 및 개발
- Python3/Django 기반 백엔드 API 개발,  내부 운영자/파트너 용 CMS(Frontend) 개발

성과
- 파트너별 브랜드관, 잔고결제 기능을 2달 만에 개발, 연 30억 규모 계약 확보 및 이후 제약사 대상 사업 확장 기반 마련에 기여
- 서비스별 결제 대상 사업자 이원화 구조를 설계,구현하여 매출 분산 처리 및 연간 결제 수수료 절감 
- 결제 DB 구조를 고도화하여 단일 PG 구조를 다중 PG 지원 가능 구조로 개선하여 기술문제 해결
- python에서 호출 가능한 Seed 128 (pkcs5 / pkcs7) 암복호화 모듈을 개발하여 기술문제 해결
- DRF-spectacular 도입 및 관련 유틸리티 도구 개발, 팀내 가이드라인 제공을 통해 팀 전체의 문서 작성 생산성 향상
- Django-Filter 기반 API 표준화 및 재사용 구조 마련, 문서화 자동화, 보안 강화, 개발 생산성에 기여


기술스택

Backend: python3/Django, Celery

DB : PostgreSQL, ElasticSearch

Infrastructure : AWS (EC2, lambda, RDS, ECR, ECS, Redis)

Monitoring : DataDog, Grafana


----
### 비바리퍼블리카(토스)
주요업무 
- slack&웹 기반 내부 취약점 발생 현황 및 취약점 보고서 관리 서비스 설계 및 개발

기술 스택

BackEnd : Python3/Django, Container 기반 서비스, slack bot

DB : Postgresql

----
### 쏘마
Threat Hunting 서비스(Monster) 개발
주요업무
- 윈도우 주요 행위 이벤트 정보 수집 ETL 파이프라인 개발 
- Django, FastAPI를 이용한 외부 서비스와의 연동 기능 설계 및 개발

성과
- 트래픽 1000배 증가 이벤트 핸들링


재택근무 보안 서비스(Any Office) 개발
주요업무
- 윈도우 프로세스/네트워크 대용량 이벤트 정보 수집 ETL 파이프라인 개발 
- Django, FastAPI를 이용한 인증과 정책 담당 백엔드 서비스 설계 및 개발

성과
- pytest 도입 및 테스트 자동화를 통한 서비스 장애 발생율 감소
- 캐싱용 redis 도입으로 인한 전체 서비스 응답속도 개선
- 모니터링 도구 도입 및 장애 대응 프로세스 고도화로 서비스 신뢰도 개선

기술스택

BackEnd : Python3 (Django, FastAPI), Celery, Container 기반 서비스

DB : Postgresql, ElasticSearch

Cache : Redis

Message Queue : Kafka

Infrastructure : nCloud

Monitoring : DataDog

----
### 차세대 보안리더 양성 프로그램(Best Of the Best)

버그바운티 프로그램 도입 가이드라인 제시 및 플랫폼 프로토타입 및 시제품 개발

국내 버그바운티 문화 활성화를 위해 국내 해커와 기업들의 수요와 요구사항을 조사하여 버그바운티 운영 가이드라인 및 버그바운티 활성화에 관련한 논문을 발표하였습니다.
([화이트해커와 기업 분석을 통한 국내 버그바운티 활성화 방안 제시](https://kiisc.or.kr/society/kiisc/homepage/bbs/1077/2237))
이를 바탕으로 플랫폼 구축 및 사업화를 목표로 진행한 프로젝트에서 팀내 메인 개발자로 
서비스 아키텍쳐 설계 및 백엔드&프론트 개발을 담당하였습니다.


논문
- 화이트 해커와 기업분석을 통한 국내 버그바운티 활성화 방안 제시 (한국정보보호학회 동계학술대회 2019 - 2019.11.16)

기술 스택

BackEnd : python/Django

DB : MariaDB

Infrastructure : AWS(EC2, Lambda,RDB)

CTF(해킹대회) 문제출제
- ChristMas CTF 2020 DOBBY_IS_FREE! 문제 출제 [https://dreamhack.io/ctf/4](https://dreamhack.io/ctf/4))
- [DOBBY_IS_FREE! 문제](https://github.com/Tempuss/CTF_CVE-2020-7471)



----
### 세인트 시큐리티
악성코드 분석 서비스 개발 및 운영

주요업무
- 악성코드 인텔리전스 서비스 개발
- 유저 관리 및 인증 기능 개발
- 분석 정보 조회 서비스 설계 및 개발

성과
- CI/CD 도입으로 인한 테스트&배포 시간 감축
- 코드 문서화 도입으로 인한 팀내 생산성에 기여
- API 사용량 측정 방식 고도화로 응답 속도 향상 및 로그 손실률 감소(과금 정확도 향상으로 매출에 기여)
- IDC 네트워크 장애로 Couchbase 이중화 오류 및 Elasticsearch 데이터 불일치 문제를 2주간의 복구 작업으로 해결, 서비스 정상화에 기여

기술 스택

FrontEnd : jQuery

BackEnd : C#.NET, PHP(Laravel, Slim)

DB : CouchBase, ElasticSearch, MariaDB, AWS aurora DB, MongoDB



APT 대응 솔루션(MNX) 개발
주요업무
- APT 대응 솔루션 기능 설계 및 개발(백엔드&프론트)
- 취약점 분석 및 보완

성과
- GS, CC(EAL3) 인증 통과
- Legacy PHP(5.x)를 Laravel(PHP7.x)로 마이그레이션

기술스택
BackEnd : PHP5, PHP7(Laravel)

DB : MariaDB


빅데이터 기반 악성코드 분석 시스템 개발
주요업무
- 정부기관과의 비밀유지계약으로 인한 업무내용 기재 불가


모바일 악성앱 분석 시스템 개발
주요업무
- 모바일 악성앱 분석 시스템의 백엔드&프론트엔드 개발
- 악성앱 분석 시스템과의 연동 기능 개발
- 분석결과 시각화 개발

기술 스택

BackEnd : PHP(5.x)

DB : MariaDB



----
### SeedGen
보안 교육 서비스(islearning.kr) 개발 및 유지보수

주요업무
- 서비스 유지보수를 위한 Front & Backend 개발

기술 스택

BackEnd : PHP(5.x)

DB : MariaDB



## 학력
한국산업기술대학교 중퇴
한세사이버보안고등학교 졸업


