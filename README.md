## 프로젝트 - Glemoa

---
<img width="1852" height="1181" alt="Glemoa 아키텍처 drawio" src="https://github.com/user-attachments/assets/f3089424-d14a-44ee-a756-41894fd399a4" />


### 소개

- 여러 커뮤니티의 인기 글들을 한눈에 보는 서비스

### 기간 / 인원

- 2025.09.19 ~ 2025.10.25
- FE/BE 개인 프로젝트

### 인프라

- MSA
- NHN CLOUD
- Filebeat + (ELK)
- Github Actions를 이용한 CI / CD

### 핵심 기능

- 즐겨찾기
- JWT / Oauth 2.0 로그인
- 크롤러를 통한 실시간 데이터 수집 및 처리
- redis를 이용한 조회수 관리 및 실시간 랭킹

### 기술 경험 / 개선 사항

- Filebeat와 ELK를 이용한 로그 수집
- Oauth를 이용한 로그인
- 커버링 인덱스를 통한 조회 쿼리와 페이지네이션 성능 개선
- ElasticSearch를 통한 검색 쿼리 성능 개선
