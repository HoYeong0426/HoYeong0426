
# Introduce.

"항상 고민하는 3년차 백엔드 개발자 천호영"입니다.

- 단순히 기능이 '동작하는 것'을 넘어, '효율적으로 동작하는 것'에 대한 깊은 고민을 멈추지 않습니다.
- 레거시 시스템 마이그레이션을 통해서, MSA 아키텍처를 도입하고 깊이 있는 기술적 고민을 바탕으로 안정적인 시스템 구축에 기여했습니다.
- 당시 Kafka, Redis 도입은 비용 제약으로 불가능 했지만, 기술적 필요성을 느껴 사이드프로젝트에서 직접 Message Queue와 캐싱 시스템을 구현하며 데이터 정합성과 성능 개선 방안을 검증했습니다.

현실적인 제약 속에서도 대안을 찾고, 스스로 성장하는 개발자로서 비즈니스와 기술의 균형 잡힌 발전을 추구하고 있습니다.

---

### Contact & Channel.

Email : [cjsghdud426@gmail.com](mailto:cjsghdud426@gmail.com)

Blog: https://rich-yuna-daddy.tistory.com/

---

# Work Experiences

### [하이록코리아](https://www.hy-lok.com/Index.hylok)

2023.10 ~

기존 모놀리식 **ERP 시스템**의 확장성 및 유지보수성 한계를 극복하기 위해 **마이크로서비스 아키텍처**를 도입하고, 동적 서비스 통신 및 인증 시스템을 구축했습니다.

- 기간 : 2023.10 ~

- **동적 서비스 디스커버리 및 통신 효율화**
    - 하드코딩된 URL 의존성 문제를 해결하고, **Spring Cloud OpenFeign**과 **Eureka**를 활용해 동적 서비스 디스커버리 시스템을 구축했습니다. 이를 통해 **서비스 간 통신 코드 중복을 70%** 줄였고, 새로운 백엔드 서비스 추가 시 코드 수정이 불필요해져 개발 생산성을 크게 높였습니다.
- **JWT 기반 인증 및 권한 관리 시스템 구축**
    - 마이크로서비스 환경에서 발생하는 세션 불일치 문제를 해결하고자 **JWT 기반 인증 시스템**으로 전환했습니다. **인터셉터**를 활용해 모든 API 요청에 대해 **중앙 집중식 권한 검증 시스템**을 구축하고, **Role-based Access Control**을 도입하여 권한 관리의 효율성을 높였습니다.
- **통합 API 관리 시스템 구현**
    - **FeignClientBuilder**를 이용한 동적 서비스 라우팅 시스템과 공통에러 처리 및 로깅 시스템을 구축하여 **API 호출 코드 재사용성을 90%** 향상시켰습니다.
- **비지니스 로직 리팩토링 및 성능 개선**
    - 노후화된 **레거시 코드 리팩토링**을 통해 시스템 유지보수성을 개선했습니다. 비효율적인 쿼리를 최적화하고 공통 모듈화 작업을 진행하여 **코드 중복을 70%** 줄였으며, 비즈니스 로직을 자동화하여 **데이터 오류율을 80% 감소**시켰습니다.
    - **대용량 쓰기**로 일괄 삽입(Batch Insert)과 **MERGE 기반의 upsert**를 도입해 DB 왕복 횟수를 줄여 대용량 데이터 처리 성능을 향상시켰습니다.

- 관련 기술
    - Backend : Java, Spring Boot, Spring Security, MyBatis, JWT
    - Frontend : Vanilla JS, jQuery, Thymeleaf, BootStrap
    - Database: Oracle

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

- Backend: Java 17, Spring Boot, MyBatis, JPA
- Frontend: jQuery, Thymeleaf, Wijmo, Bootstrap
- Database: Oracle (PL/SQL), MySQL, Redis (학습 중)
- Infra: Docker, Kfaka(학습 중), AWS(학습 중)
- Tooling: GitHub, VS Code, IntelliJ, Notion
