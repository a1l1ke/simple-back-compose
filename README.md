# simple-back
Spring Boot 4 기반의 간단한 사용자 조회 REST API 실습 프로젝트입니다.
## 기술 스택
![Java 17](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white) ![Spring Boot 4](https://img.shields.io/badge/Spring_Boot-4.1.1-6DB33F?logo=springboot&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-Wrapper-02303A?logo=gradle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![Lombok](https://img.shields.io/badge/Lombok-BC4521?logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
`ui`, `app`, `domain`, `infra` 계층으로 구성된 클린 아키텍처를 적용합니다.
설정은 12-Factor 원칙에 따라 환경변수를 사용하며 `local`, `prod`, `test` 프로필로 분리합니다.
`GET /`은 애플리케이션 상태를, `GET /users`는 JPA 기반 사용자 목록을 반환합니다.
MockMvc 슬라이스 테스트와 Gradle Wrapper 기반 실행 가능한 fat JAR 빌드를 지원합니다.
