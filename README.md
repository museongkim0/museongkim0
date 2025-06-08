# 김무성 (Museong Kim) 👋

> **효율적인 데이터 처리와 전략적 인사이트로 비즈니스를 혁신하는 엔지니어**

[![Blog](https://img.shields.io/badge/Blog-jobdahan--tech.tistory.com-blue)](https://jobdahan-tech.tistory.com)
[![Velog](https://img.shields.io/badge/Velog-@mstar228-green)](https://velog.io/@mstar228)
[![Email](https://img.shields.io/badge/Email-mstar0228@gmail.com-red)](mailto:mstar0228@gmail.com)

## 🧑‍💻 About Me

개발부터 데이터 파이프라인 구축, 분석까지 **데이터의 수집·처리·분석 전 과정**에서 전문성을 발휘하는 엔지니어입니다.

- 🎓 **한양대학교 ERICA 산업경영공학과** 졸업
- 💼 **비트나인** 데이터 분석팀 (2022.01 ~ 2024.05)
- 🏕️ **한화시스템 BEYOND SW캠프** 수료 (2024.11 ~ 2025.05)
- 📊 **빅데이터 분석기사**, **SQLD**, **AdsP** 보유

[**포트폴리오 보기**](https://docs.google.com/presentation/d/1rYxNtYQYZnVZ0FOOQCtHjlA91Q38L_kB/edit?slide=id.p6#slide=id.p6)

### 🚀 핵심 역량
- **도전적인 엔지니어**: 새로운 기술 트렌드에 민감하게 반응하며 지속적 학습을 통한 역량 확장
- **기업 중심 사고**: 개인 성취보다 기업 목표 우선, 데이터 기반 의사결정으로 비즈니스 가치 극대화
- **다재다능한 전문가**: 안정적인 데이터 파이프라인 구축부터 비즈니스 인사이트 도출까지

## 🛠️ Tech Stack

### Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat&logo=gnu-bash&logoColor=white)

### Data & Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Cypher](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)

### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)

### Frameworks & Tools
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)

## 🏆 주요 프로젝트

### 🎵 Techup - 데스크톱 부품 추천 플랫폼 [[Github Link]](https://github.com/museongkim0/Techup)
> **2025.03 ~ 2025.05** | 팀 프로젝트 / 팀장 역할

**사용자 맞춤형 데스크톱 부품 추천 플랫폼**

- **핵심 성과**:
  - Kafka 이용 **실시간 데이터 업데이트**
  - ElasticSearch 도입으로 **응답시간 67% 개선** (1.2s → 0.4s)
  - pySpark 이용 분산 처리를 통해 데이터 **처리시간 31%개선** (49.6s → 34.05s)
- **기술적 도전**: 
  - Kafka를 활용한 실시간 추천시스템 구현
  - TruncatedSVD 차원 축소 + HNSW 알고리즘으로 유사도 계산 소요 시간 개선
  - Elastic Search를 활용한 확장성 개선
  - pySpark를 이용한 데이터 파이프라인 최적화

**Tech Stack**: `FastAPI` `Spring Boot` `Kafka` `ElasticSearch` `pySpark` `Vue.js`

---

### 📚 GCMC 기반 도서 추천시스템 [[Github Link]](https://github.com/museongkim0/GCMC_recommendation)
> **2021.10 ~ 2021.12** | 인턴 R&D

**Graph Convolutional Matrix Completion을 활용한 추천시스템**

- **핵심 성과**: Feature Engineering + 하이퍼파라미터 튜닝으로 **RMSE 16.5% 개선** (2.0 → 1.67)
- **기술적 도전**:
  - Multimodal 데이터(텍스트, 이미지, 범주형) 통합 처리
  - 차원 불일치 문제 해결 (유저 3차원 ↔ 도서 1042차원)
  - Graph Embedding을 통한 특징 벡터 생성

**Tech Stack**: `Python` `PyTorch` `GCMC` `Node2Vec` `SBERT` `Docker`

---

### 🏫 EduLink - 부트캠프 학습 관리 플랫폼 [[Github Link]](https://github.com/museongkim0/edulink)
> **2025.02 ~ 2025.03** | 팀장 역할

**기존 LMS의 한계를 보완한 부트캠프 전용 학습 관리 플랫폼**

- **핵심 성과**: JPA saveAll() 메서드 활용으로 **응답시간 70% 개선** (8.5s → 2.6s)
- **기술적 도전**:
  - JPQL을 이용한 N+1 문제 해결
  - CI/CD 파이프라인 구축 (Jenkins + Docker + Kubernetes)
  - 반응형 UI 구현 및 컴포넌트 재사용성 최적화

**Tech Stack**: `Spring Boot` `Vue.js` `Tailwind CSS` `Jenkins` `Kubernetes`

## 💼 Professional Experience

### 🏢 비트나인 - 데이터 분석팀
> **2022.01 ~ 2024.05** (정규직, 2년 5개월)<br>
> **2021.07 ~ 2021.12** (인턴, 6개월)

#### 주요 프로젝트

**🎵 음악 플랫폼 노래 추천 시스템** (2022.01 ~ 2022.03)
- Word2Vec을 응용한 Song2Vec 모델 개발
- RDB to GraphDB ETL 파이프라인 구축 및 테이블 단위 적재, Connection Pool 활용 성능 최적화

**🏢 기업 신용도 지표 탐색 프로젝트** (2022.04 ~ 2022.06)
- 그래프 데이터베이스 활용으로 **기업간 거래 관계 6depth까지 조회** 성능 개선
- 기업간 거래 데이터 전처리 및 적재 파이프라인 개발

**📊 Graphizer - 그래프 시각화 및 분석 툴** (2023.01 ~ 2023.11)
- **노코드 그래프 데이터베이스** 적재 및 조회 시각화 분석 툴 기획
- UI/UX를 활용한 RDB to GraphDB 적재 기능 설계

**🔍 금융 사기 Graph FDS** (2024.01 ~ 2024.05)
- 룰 기반 Cypher 쿼리 개발로 **사기 의심 계좌 탐지 자동화**
- 인력 검토 대상 계좌 수 대폭 감소로 업무 효율성 향상

---

## 📋 기타 프로젝트

### 🔍 반도체 분류 프로젝트 [[Github Link]](https://github.com/museongkim0/semiconductor_classification)
> **2021.03 ~ 2021.06** | 대학교 팀프로젝트 / 팀장 역할

반도체 제조 공정의 센서 및 공정 데이터를 통한 반도체 양품/불량품 분류

- **핵심 성과**: 임베디드 특징선택 + 앙상블 + 하이퍼파라미터 튜닝으로 **AUC-Score 19% 개선** (0.57 → 0.68)
- **Tech Stack**: `Python` `Scikit-learn` `Feature Selection` `Ensemble`

### 📰 가짜 뉴스 탐지 프로젝트 [[Github Link]](https://github.com/museongkim0/fakenews-classification)
> **2021.07** | 인턴 프로젝트

뉴스 정보와 SNS 확산 양상을 바탕으로 가짜/진짜 뉴스 분류

- **핵심 성과**: Feature Engineering으로 생성한 변수들의 **특성 중요도 93% 이상** 달성
- **Tech Stack**: `Python` `NLP` `Graph Analysis` `Feature Engineering`

### 🐾 펫 플랫폼 추천 PoC
> **2021.09** | 인턴 프로젝트

사용자와 펫의 관계 정보를 그래프로 구성한 유사도 기반 추천시스템

- **핵심 성과**: 아다믹 아다르 유사도 탐색 및 적용으로 추천시스템 성능 개선
- **Tech Stack**: `Python` `Graph Theory` `Similarity Algorithm`

<!--
## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=museongkim0&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=museongkim0&layout=compact&theme=radical)
-->

## 📫 Contact & Links

- 📧 **Email**: mstar0228@gmail.com
- 📝 **Tech Blog**: [jobdahan-tech.tistory.com](https://jobdahan-tech.tistory.com)
- ✍️ **Velog**: [velog.io/@mstar228](https://velog.io/@mstar228)

---

> **"기술과 데이터로 새로운 가치를 창출합니다"**
