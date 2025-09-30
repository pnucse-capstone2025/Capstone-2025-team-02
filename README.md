### 1. 프로젝트 배경
#### 1.1. 국내외 시장 현황 및 문제점
<img width="7680" height="4320" alt="1" src="https://github.com/user-attachments/assets/8777e327-739c-4c03-a7ab-22820d2f39cd" />

현대 사회의 고령화, 만성질환의 증가, 건강에 대한 관심 증가는 개인의 복약 관리 수요를 급격히 높이고 있습니다. 그러나 의료 시스템은 하기한 구조적 한계를 지닙니다.

- 다약제 복용의 증가: 고령층의 약 82.4%가 5종 이상의 약을 복용하며, 본인의 복약 내용을 인지하기 어려운 경우가 많습니다.
  
- 기존 복약 시스템의 비효율성: 종이 처방전, 약 봉투 등에 의존한 정보 제공은 가독성이 떨어지고, 이해하기 어려운 경우가 많습니다.
 
- 약물 사고의 빈도 증가: 2023년 전체 환자 안전사고의 52.8%가 약물 관련 사고로, DUR(의약품안전사용서비스) 시스템이 아직 완전히 도입되지 않았고, 법적인 안전장치도 부족해서 처방전 간의 상호 검증에도 한계가 있습니다.
  
- 민감정보의 체계화된 관리 시스템 부족: 처방전이나 문진표같은 민감한 정보는 체계화된 관리 시스템이 부족하여 개인정보 유출 사고가 자주 발생합니다.
  - 이러한 예로 지난 2022년 개인정보가 담긴 처방전을 제대로 파기하지 않고 그대로 쓰레기 수거장에 버리는 바람에 개인정보가 유출된 사건
  - 종이 처방전을 둘 곳이 없어 사용자들이 이용하는 계단에 처방전을 보관하는 등의 문제가 있었습니다
    
- 개인정보 주도권 부재: 환자가 자신의 복약 이력과 정보를 능동적으로 관리하기 어려우며, 정보의 흐름을 통제하기 어렵습니다.

이러한 문제들은 사용자가 **스스로 약물 정보를 통합 관리하고, 약물 상호작용 및 부작용을 사전에 인지할 수 있는 새로운 디지털 솔루션**의 필요성을 시사합니다.

<img width="7680" height="4320" alt="4" src="https://github.com/user-attachments/assets/1ddfb222-2b4a-49bc-9409-68eda49d8325" />
<img width="7680" height="4320" alt="5" src="https://github.com/user-attachments/assets/fa8b5b33-b54d-462c-8342-7b07ecfd6fe7" />
<img width="7680" height="4320" alt="5 (1)" src="https://github.com/user-attachments/assets/39991f19-9ecf-4d1e-900f-67a3902fc390" />

#### 1.2. 페르소나
<img width="7680" height="4320" alt="5" src="https://github.com/user-attachments/assets/9862861d-66cb-42a9-ab60-6ab1f6e7647f" />

#### 1.3. 필요성과 기대효과
<img width="7680" height="4320" alt="29" src="https://github.com/user-attachments/assets/87112244-0318-4806-bceb-856ef34a58d6" />
<img width="7680" height="4320" alt="31" src="https://github.com/user-attachments/assets/5010a665-26d7-440c-8e67-2b00d6f7a624" />
<img width="7680" height="4320" alt="32" src="https://github.com/user-attachments/assets/3ad38c1f-14ed-463a-a209-98f0252a6f94" />

### 2. 개발 목표
#### 2.1. 목표 및 사회적 가치
<img width="7680" height="4320" alt="6" src="https://github.com/user-attachments/assets/32d46260-b51c-426a-b706-10e6e107094d" />
<img width="7680" height="4320" alt="33" src="https://github.com/user-attachments/assets/8e874969-a82a-48c2-9fe5-4188104d600a" />

#### 2.2. 기존 서비스 대비 차별성 
<img width="7680" height="4320" alt="4" src="https://github.com/user-attachments/assets/621b49c4-35e8-4deb-91e7-2451ae14f95c" />
<img width="7680" height="4320" alt="11" src="https://github.com/user-attachments/assets/88a1fdbf-ccea-4b67-9af5-53a75cca8b9b" />
<img width="7680" height="4320" alt="20" src="https://github.com/user-attachments/assets/1c0d29e9-d55d-4cfe-844c-ecc514b7fe67" />

### 3. 시스템 설계
#### 3.1. 시스템 구성도
<img width="6206" height="2061" alt="Group 1707482187" src="https://github.com/user-attachments/assets/183c6c4b-53ef-46b8-b518-60c371f75dee" />

#### 3.2. 사용 기술
**기술 스택**
- **Frontend**: Kotlin, Android, Jetpack Compose, Hilt-Dagger, Coroutine, OAuth2.0, Retrofit, Okhttp, MVVM, Flow 
- **Backend**: Java, Spring Boot, elasticsearch, redis, NGiNX, Next.js, FastAPI, TypeScript, RAG, AI orchestration, Docker, MySQL, Weaviate, React, OpenAI API, YOLO v8, FCM
- **Design**: Figma, Adobe Illustrator, Adobe Photoshop
  
**사용된 API 및 서비스**
<img width="1130" height="401" alt="image" src="https://github.com/user-attachments/assets/cb49bc4a-9f89-4127-9b37-e5f58b56346d" />
- Kakao API(OAuth2.0)
- Google Firebase Cloud Messaging
- Open AI API (GPT-4o mini))
<img width="1517" height="546" alt="image" src="https://github.com/user-attachments/assets/c7b8115a-2da6-4618-9777-437c3b233ca3" />
<img width="1520" height="247" alt="image" src="https://github.com/user-attachments/assets/ce3c154e-70c3-49ad-9df7-a14546163f7f" />
<img width="1525" height="330" alt="image" src="https://github.com/user-attachments/assets/e0bcb492-9034-49b4-a957-ead162af95e6" />
<img width="1521" height="337" alt="image" src="https://github.com/user-attachments/assets/2f759db2-6c29-424b-89a1-cb40dd25da56" />
<img width="1517" height="370" alt="image" src="https://github.com/user-attachments/assets/d3aec173-68a7-46cc-8c09-8328933a792b" />
<img width="1520" height="332" alt="image" src="https://github.com/user-attachments/assets/779c5063-0567-4a99-9d81-b954cdceb67e" />
<img width="1516" height="860" alt="image" src="https://github.com/user-attachments/assets/c5723b1b-3a80-48a0-a85e-542dfa9125ad" />
<img width="1521" height="369" alt="image" src="https://github.com/user-attachments/assets/38649867-972b-4484-8677-5e0ebe376ffd" />
<img width="1522" height="471" alt="image" src="https://github.com/user-attachments/assets/1d677b65-718f-49a6-a063-f7ca89a05e75" />
<img width="1517" height="329" alt="image" src="https://github.com/user-attachments/assets/bc33143d-b646-4f99-8c8a-778eb6d890d4" />
<img width="1518" height="326" alt="image" src="https://github.com/user-attachments/assets/6d1029a3-bc0f-4c16-980c-37a1238513fb" />
<img width="1520" height="1182" alt="image" src="https://github.com/user-attachments/assets/91034a7c-f476-412a-98ee-f23ea7788791" />
<img width="1520" height="432" alt="image" src="https://github.com/user-attachments/assets/1045ab95-e203-4787-8df9-f43b0e0a0113" />
<img width="1518" height="498" alt="image" src="https://github.com/user-attachments/assets/70b734a2-9f4c-4683-8732-f20cb5abb1a7" />
<img width="1517" height="791" alt="image" src="https://github.com/user-attachments/assets/4bdd4e87-bb01-4b13-9775-7b88ebbb0638" />

### 4. 개발 결과
#### 4.1. 전체 시스템 흐름도
- 전체 데이터베이스 ERD  
<img width="649" height="556" alt="image" src="https://github.com/user-attachments/assets/d7377c9d-a9a5-4ef4-a722-0b8eb5932350" />

- 사용자 데이터베이스 ERD
<img width="528" height="412" alt="image" src="https://github.com/user-attachments/assets/83e9b596-d3d4-4edc-9e90-86c77b0b1a01" />

- 의약품 데이터베이스 ERD
<img width="260" height="371" alt="image" src="https://github.com/user-attachments/assets/6df3a996-f1d0-44cd-8dde-a6057c244029" />

- 건강기능식품 데이터베이스 ERD
<img width="490" height="449" alt="image" src="https://github.com/user-attachments/assets/ac54536a-c237-45b8-9276-41ff944a7b4d" />

#### 4.2. 기능 설명 및 주요 기능 명세서
<img width="7680" height="4320" alt="23" src="https://github.com/user-attachments/assets/25714580-e13b-4286-8fda-6641827701cc" />
<img width="7680" height="4320" alt="24" src="https://github.com/user-attachments/assets/7ef300c2-51f5-4ac1-8e13-94c8533dcb2c" />
<img width="7680" height="4320" alt="25" src="https://github.com/user-attachments/assets/11a1faf7-99be-438b-8b04-c5f61e9730ae" />
<img width="7680" height="4320" alt="12" src="https://github.com/user-attachments/assets/a609e765-50b4-4072-a09d-b340314b2b2b" />
<img width="7680" height="4320" alt="9" src="https://github.com/user-attachments/assets/a3a1d0d8-c1b9-42c3-90f1-7f65792277ed" />
<img width="7680" height="4320" alt="10" src="https://github.com/user-attachments/assets/bc4e86c2-a201-4a34-ae3d-0792f7ca545d" />

#### 4.3. 산업체 멘토링 의견 및 반영 사항
- 멘토의 의견 1 : 철저한 개인정보 보호가 필요하다.
    - 해결 : 사용자 민감정보가 저장되는 모든 DB 암호화(AES-GCM) 및 비식별화

### 5. 설치 및 실행 방법
#### 5.1. 설치절차 및 실행 방법
Android 앱을 내려받아 설치할 수 있습니다.
서버 문의는 따로 부탁드립니다.
k_bright_st@pusan.ac.kr

#### 5.2. 오류 발생 시 해결 방법
- Chatbot은 베타서비스로써, 네트워크 상황 등으로 인한 실행 오류, 잘못된 답변이 제공될 수 있습니다.

### 6. 시연 영상
#### 6.1. 시연 영상
[![Pilltip 소개 영상](http://img.youtube.com/vi/hAz6OM7bPMQ/0.jpg)](https://www.youtube.com/watch?v=hAz6OM7bPMQ)

#### 6.2. 수상 이력
- 2025 SW중심대학 디지털 경진대회 : SW부문
  - 부산대학교 대표팀 선발 및 본선 진출
  - 서울 중구 대한상공회의소 발표 및 딥노이드 상 수상
- 2025 K-ICT in Busan
  - Pilltip 출품 및 BEXCO 부스 전시
- SK AI SUMMIT 2025
  - 우수사례 선정 및 전시부스 운영
  - 코엑스 (그랜드볼룸, 아셈볼룸, 오디토리움) 전시
- Busan Dataweek 2025 데이터활용 우수사례 공모전
  - 우수사례 선정 및 최우수상(1등상, 부산광역시장상)
  - 벡스코 제2전시장 4A홀 전시
- Google.org AI 커리어스쿨 창업톤 L:AUNCH
  - 장려(3등상, 100만 원)

### 7. 팀 구성
#### 7.1. 팀원별 소개 및 역할 분담
<img width="7680" height="4320" alt="19" src="https://github.com/user-attachments/assets/26c26406-3ba9-4a52-82b6-11dfea08c1dd" />
- 디자이너와의 협업으로 Pilltip을 성공적으로 개발했습니다.

### 8. 참고 문헌 및 출처
- [1] Google. Jetpack Compose [Online]. Available: https://developer.android.com/jetpack/compose (accessed Sep. 18, 2025).
- [2] Google. LiveData overview [Online]. Available: https://developer.android.com/topic/libraries/architecture/livedata (accessed Sep. 18, 2025).
- [3] Google. ViewModel overview [Online]. Available: https://developer.android.com/topic/libraries/architecture/viewmodel (accessed Sep. 18, 2025).
- [4] M. Fowler and D. Rice. Patterns of Enterprise Application Architecture: MVVM. Addison-Wesley, 2009.
- [5] Kotlin Foundation. Coroutines Guide [Online]. Available: https://kotlinlang.org/docs/coroutines-overview.html (accessed Sep. 18, 2025).
- [6] Google. Hilt dependency injection [Online]. Available: https://dagger.dev/hilt (accessed Sep. 18, 2025).
- [7] Square. OkHttp [Online]. Available: https://square.github.io/okhttp/ (accessed Sep. 18, 2025).
- [8] Elastic. Elasticsearch documentation [Online]. Available: https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html (accessed Sep. 18, 2025).
- [9] Redis Ltd. Redis documentation [Online]. Available: https://redis.io/docs/ (accessed Sep. 18, 2025).
- [10] Weaviate. Weaviate vector database [Online]. Available: https://weaviate.io/developers/weaviate (accessed Sep. 18, 2025).
- [11] Docker Inc. Docker overview [Online]. Available: https://docs.docker.com/get-started/overview/ (accessed Sep. 18, 2025).
- [12] OpenAI. GPT API reference [Online]. Available: https://platform.openai.com/docs/ (accessed Sep. 18, 2025).
- [13] Google. Firebase Cloud Messaging (FCM) [Online]. Available: https://firebase.google.com/docs/cloud-messaging (accessed Sep. 18, 2025).
- [14] Pivotal Software. Spring Boot reference documentation [Online]. Available: https://docs.spring.io/spring-boot/docs/current/reference/html/ (accessed Sep. 18, 2025).
- [15] Oracle. MySQL 8.0 reference manual [Online]. Available: https://dev.mysql.com/doc/refman/8.0/en/ (accessed Sep. 18, 2025).
- [16] National Institute of Standards and Technology (NIST). Recommendation for Block Cipher Modes of Operation: Galois/Counter Mode (GCM) and GMAC. NIST Special Publication 800-38D, 2001 [Online]. Available: - https://csrc.nist.gov/publications/detail/sp/800-38d/final (accessed Sep. 18, 2025).
- [17] Internet Engineering Task Force (IETF). The Transport Layer Security (TLS) Protocol Version 1.2. RFC 5246, 2008 [Online]. Available: https://datatracker.ietf.org/doc/html/rfc5246 (accessed Sep. 18, 2025).
- [18] Internet Engineering Task Force (IETF). The OAuth 2.0 Authorization Framework. RFC 6749, 2012 [Online]. Available: https://datatracker.ietf.org/doc/html/rfc6749 (accessed Sep. 18, 2025).
- [19] NGINX Inc. NGINX documentation [Online]. Available: https://nginx.org/en/docs/ (accessed Sep. 18, 2025).
- [20] Meta. React documentation [Online]. Available: https://react.dev/ (accessed Sep. 18, 2025).
- [21] Vercel. Next.js documentation [Online]. Available: https://nextjs.org/docs (accessed Sep. 18, 2025).
- [22] Ministry of Health and Welfare. Drug Utilization Review (DUR) system information and inspection statistics. Policy page, 2023–2025 [Online]. Available: https://www.mohw.go.kr (in Korean).
- [23] H. S. Jeon. Legislative direction for activation of DUR. Health Insurance Review and Assessment Service (HIRA) OAK Repository, Policy Research Report, 2019 [Online]. Available: https://repository.hira.or.kr (in Korean).
- [24] Health Insurance Review and Assessment Service (HIRA). DUR operation guidelines, including portal conditions and prescription/dispensing support software. Ministry of Health and Welfare Notice No. 2010-84, 2010 [Online]. Available: https://www.hira.or.kr (in Korean).
- [25] Ministry of Health and Welfare. Overview, history, and performance of the DUR system (2008 pilot onwards). 2023–2025 [Online]. Available: https://www.mohw.go.kr (in Korean).
- [26] KPANews. “Drug expenses increase 28% in 5 years, management of polypharmacy patients needed.” Seoul: KPANews; 2024 [Online]. Available: https://www.kpanews.co.kr/article/show.asp?idx=253715&category=C (in Korean).
- [27] Y. H. Moon. “47% get drug information from pharmacists vs 42% from the Internet.” NewsTheVoice Healthcare; Apr. 13, 2023 [Online]. Available: https://www.newsthevoice.com/news/articleView.html?idxno=32184(in Korean).
- [28] H. R. Bang. “1.36 million patients take 10+ drugs for over 60 days.” HitNews; Nov. 28, 2024 [Online]. Available: https://www.hitnews.co.kr/news/articleView.html?idxno=59503 (in Korean).
- [29] Yonhap News. “53% of patient safety accidents are drug-related: mandatory DUR needed.” Apr. 19, 2024 [Online]. Available: https://www.yna.co.kr/view/AKR20240419071800530 (in Korean).
- [30] D. Y. Kim. “Prescription papers discarded as trash, mass personal data leakage.” DealSite Economy TV; Apr. 19, 2022 [Online]. Available: https://news.dealsitetv.com/articles/78278 (in Korean).
- [31] J. H. Hong. “[Reader complaints] Prescriptions abandoned in pharmacies, personal data exposed.” Jemin Ilbo; Mar. 22, 2023 [Online]. Available: https://www.jemin.com/news/articleView.html?idxno=752278 (in Korean).
- [32] J. H. Lee. “Ignored DUR for narcotics, 21.9 million duplicate prescriptions in 5 years.” DailyPharm; Oct. 18, 2023 [Online]. Available: https://www.dailypharm.com/Users/News/NewsView.html?ID=304930 (in Korean).

Copyright 2025 Pilltip All Rights Reserved.

