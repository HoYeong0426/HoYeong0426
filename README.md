
# Introduce.

"항상 고민하는 3년차 백엔드 개발자 천호영"입니다.

- 단순히 ‘동작하는 것’에 그치지 않고, ‘효율적으로 동작하는 구조’를 설계하기 위해 끊임없이 고민합니다.
- 레거시 ERP 시스템을 Spring Boot 기반 MSA 아키텍처로 전환하며 안정성과 개발 효율성을 높였습니다.
- 비용 제약으로 도입하지 못했던 Kafka·Redis의 필요성을 사이드 프로젝트에서 직접 구현해 데이터 정합성과 성능 개선 방안을 검증했습니다.

현실적인 제약 속에서도 대안을 찾고, 스스로 성장하는 개발자로서 비즈니스와 기술의 균형 잡힌 발전을 추구하고 있습니다.

---

### Contact & Channel.

Email : [cjsghdud426@gmail.com](mailto:cjsghdud426@gmail.com)

Blog: https://rich-yuna-daddy.tistory.com/

---

# Work Experiences

### [하이록코리아](https://www.hy-lok.com/Index.hylok)

2023.10. ~

- 프로젝트
    - 레거시 ERP 시스템 웹 전환 및 MSA 아키텍처 도입

- 기존 시스템 한계
    - VB6.0 기반 ERP 및 Struts 시스템의 노후화로 유지보수성과 확장성 한계
    - CS 구조 특성상 외부 시스템 연동 불가, 자동화/확장 제약
    - Legacy Oracle 쿼리와 비효율적 로직으로 성능 저하 지속

- 기술스택
    - Java 17 · Spring Boot · MyBatis · Spring Security · JWT · Oracle · Vanilla JS · jQuery · Thymeleaf

- 역할 및 기여
- MSA 아키텍처 설계 및 구축 (기여도 30%)
    - 각 부서별 서버 분리 및 Eureka·Feign 기반 서비스 통신 도입
    - 중복 코드 70% 감축, 장애 시 서비스 격리로 안정성 확보
- JWT 기반 중앙 인증/인가 시스템 구축
    - Spring Security + Filter/Interceptor로 통합 인증 처리
    - RBAC(Role-Based Access Control) 체계 확립으로 보안 강화
- 공통 모듈화 및 파일 서버 구축
    - 파일 등록·삭제·복제 로직 통합 → 중복 코드 90% 이상 제거
- 전역 예외 처리 및 로깅 시스템 구축
    - @RestControllerAdvice 기반 표준 예외 응답 구조 설계
    - 비즈니스 로직 오류 추적 효율 향상
- 쿼리 리팩토링 및 성능 최적화
    - 배치 인서트·MERGE 도입 → 대량 데이터 처리 속도 5배 향상
 
---

# Personal Project

### [마이크로서비스 게시판 시스템](https://github.com/HoYeong0426/msa-board)

2025.10. ~ 11. | 백엔드 개발

- 프로젝트
    - 6개의 마이크로서비스로 구성된 CQRS 기반 게시판 시스템, Outbox Pattern과 Redis 샤딩을 통해 데이터 일관성과 확장성 확보

- 기술스택
    - Java 21 · Spring Boot 3.3.2 · Kafka · Redis · MySQL

- 주요 성과
    - Outbox Pattern 적용으로 데이터 정합성 100% 보장, Kafka 이벤트 손실 0건
    - Redis 하트비트 기반 자동 샤딩 시스템 구현, 중복 처리 0건
    - CQRS + Kafka 이벤트 스트리밍으로 서비스 결합도 제거, 실시간 동기화 구현
    - Redis 캐싱 및 랭킹 시스템 도입, 조회 응답 속도 80% 단축
 
---


# Other Experiences

## 부산아이티윌

- 2022.12.22 ~ 2023.06.19

## 정보처리기사

- 2023.09.01.

- K-디지털 교육과정
    - 팀프로젝트 최우수상
    

---

# Skill

- Backend: Java, Spring Boot, MyBatis, JPA
- Infra: Kafka, Redis, Docker, AWS
- Frontend: jQuery, Thymeleaf, Wijmo, Bootstrap
- Database: Oracle, MySQL
- Tools: GitHub, VS Code, IntelliJ, Notion
