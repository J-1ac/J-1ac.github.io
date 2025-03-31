---
layout: resume
title: 이상준 | Developer
author: 이상준
tags: resume
---

# 안녕하세요. 이상준입니다.
<p style="text-align: right;">Github: <a href="https://github.com/J-1ac">@J-1ac</a></p>
<p style="text-align: right;">Email: tkdwns26@naver.com</p>
<p style="text-align: right;">Contact: 010-6752-2436</p>

<h3 style="text-align: center;">
  <img src="https://avatars.githubusercontent.com/u/55781137?v=4" alt="프로필 사진" style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%;"><br><br>
  <p style="bold">사용자에게 더 나은 경험을 제공하는 개발자를 꿈꿉니다.</p>
</h3>


<h2 style="text-align: center;">
  <b>Experience</b><br>
</h2>

- **한국남부발전 인턴 재직중(디지털인프라실 AI혁신부)**
  - 폐쇄망환경에서 PDF 자동 변환 도구를 개발하며 한글과컴퓨터에서 제공하는 보안 모듈을 내부망으로 반입하기 위해 정보보안실의 타당성 검토를 진행했습니다.
  - 비전공자도 쉽게 따라 할 수 있도록 환경 설정과 실행 방법을 이미지와 함께 단계별로 정리한 매뉴얼을 작성했습니다.

---

- **2025 지역문제 해결 연합 해커톤 [Emergency_911](https://github.com/Diving-Seagull/Emergency_911)**
  - 2025 지역문제 해결 연합 해커톤에 참가하여 **소방 업무 효율화를 위한 인공지능 통합 신고 처리 시스템 Emergency_911**을 개발했습니다.
  - 사용자의 음성 신고를 Whisper API를 통해 텍스트로 변환한 뒤, GPT-3.5 Turbo로 내용을 분석해 분류했습니다. 대분류(화재, 구급 등)는 Enum 기반으로, 소분류는 유형별로 구성한 프롬프트를 GPT에 전달해 자동 분류의 정확도를 높였습니다. 예를 들어 ‘구급’의 경우 MedicalCategory Enum에 각 단계와 세부 증상을 정리해 구조화된 형태로 제공했습니다. 
  - 이후 분류된 신고에 대해 '30분 이내, 반경 50m 이내, 동일 소분류'라는 기준으로 ElasticSearch의 GeoPoint 기반 위치 필터링을 적용해 중복 여부를 빠르게 판별했습니다.

---

- **디지랩 챌린지: 기술로 바꾸는 세상 - 제주와 함께하는 힐링산책 [간당](https://github.com/Diving-Seagull/gandang)**
  - 2024 [디지랩 챌린지](https://digilab-hackathon.com/)에 참가하여 제주 해안도로를 따라 여행하는 관광객을 위한 드라이브 코스 추천 내비게이션 서비스를 개발했습니다.
  - 제주데이터허브의 서귀포시 자전거 보관소 공공데이터를 활용해 경로 내 보관소 위치를 안내하고, 제주관광공사의 마을 관광지 정보 데이터를 기반으로 2km 이내 관광 명소를 표시하는 해안도로 내비게이션 알고리즘을 설계했습니다. 
  - 이 과정에서 Python OSMnx를 활용해 해안선과 인접한 서귀포시 도로망의 교차점 993개를 추출하고, 해당 지점을 경유하는 경로 탐색 알고리즘을 구현했습니다.

---

- **카카오테크캠퍼스 - 전세 사기 대처 웹 플랫폼[Boomerang](https://github.com/kakao-tech-campus-2nd-step3/Team11_BE)**
    - 전세 사기 피해 후 복잡한 절차와 방대한 서류 제출로 어려움을 겪는 문제를 해결하기 위해 아이디어톤에서 As-Is -> To-Be 분석, 마켓 리서치, Crazy 8 기법, 페르소나 및 저니 맵 작성 등 다양한 기획 기법을 활용해 사용자 관점에서 문제를 정의하고 기획했습니다.
    - Step 3에서는 실제 개발을 진행하며, 피해자 오픈채팅방에서 확인한 복잡한 서류 제출 과정과 오픈 채팅의 낮은 신뢰도 문제를 해결하기 위해 PDFBox AcroForm을 활용한 서류 자동 완성 기능과 Redis, SMTP를 활용한 멘토 인증을 위한 이메일 인증 기능을 담당하여 개발했습니다.
    - 서류 자동화 과정에서는 일부 뷰어에서 텍스트가 비정상적으로 출력되는 문제가 발생해 PDF를 이미지로 변환한 후 다시 PDF로 생성하는 방식으로 렌더링 환경에 상관없이 일관된 사용자 경험을 제공했습니다.
    - 이메일 인증 시스템 초기 구현 시 이메일 전송으로 인해 API 응답 시간이 7~10초까지 지연지만, 비동기 처리로 응답 속도를 10ms 수준까지 단축해 사용자 체감 성능을 크게 개선할 수 있었습니다.

---

- **졸업과제 - 실시간 시선 추적 기반 시간 관리 플랫폼 [SeagullsRoom](https://github.com/new3seagull/SeagullsRoom)**
  - 집중에 어려움을 겪는 학생들을 위해 기존 타이머의 강제성 부족 문제를 개선한 실시간 시선 추적 기반 시간 관리 플랫폼 'SeagullsRoom'을 기획 및 개발했습니다.
  - 웹캠 기반 Eye Tracking을 자체 구현해 사용자의 클릭 위치와 눈 이미지 벡터를 선형 회귀로 분석하여 실시간 시선 위치를 추정했습니다. 
  - 이후 해당 위치의 화면 캡처 이미지를 OpenAI의 GPT-4o API로 분석해 유튜브, 게임 등 방해 요소를 분류하고 타이머를 자동화했습니다. 
  - 마지막으로 사용자 정의 학습 카테고리와 연동해 스크린 타임을 시각화함으로써 사용자가 자신의 집중 패턴을 인식하고 개선할 수 있도록 개발했습니다.

---

- **2024 DIVE2024 해커톤 - [With-u](https://github.com/Diving-Seagull/With-u)**
  - 부산광역시 공공데이터 활용 해커톤 [DIVE2024](https://www.dxchallenge.co.kr/about-1)에서 삼정KPMG의 발제를 받아 WYD2027 행사를 위한 팀 관리 애플리케이션 With-u를 개발했습니다.
  - BE개발을 담당하여 FCM을 활용한 공지사항 푸시 알림, 부산시 공공데이터를 활용한 관광지도 서비스, Google Cloud Translation API를 통한 다국어 번역 서비스 등을 담당하여 개발했습니다.

---

- **대리 출석 방지를 위한 안면 인식 기반 출석 시스템 [NoDaechul](https://github.com/hunsy9/NoDaechul)**
  - 2024 1학기 클라우드컴퓨팅 과목을 수강하며 대리출석 방지를 위해 AWS Rekognition을 통해 수업에 참여중인 학생들의 얼굴 특징 벡터를 추출한 후 DB에 저장된 학생의 사진과 비교함으로써 학생이 출석했는지 확인할 수 있는 출석 체크 시스템을 제공하는 **NoDaechul**를 개발했습니다. 
  - DB 스키마 설계 및 웹 서버 어플리케이션 개발을 담당해 백엔드 개발을 진행했습니다.

---

- **2023 DX Living Solution 공모전 - 세탁기 시뮬레이터의 알고리즘 구현 및 결함 분석 도구 개발 [DXLivingSol](https://github.com/J-1ac/DXLivingSol)**
  - LG전자 리빙솔루션제어QE팀 멘토님과 산학 공모전을 진행하여 실제 세탁기의 PCBA를 Arduino와 Serial 통신을 이용해 부하 없이 가상으로 사이클을 동작하여 제작 전 미리 결함을 예방하는 시스템을 구축하는 과정에서 Serial 통신과 각 부하의 알고리즘의 구현을 담당했습니다. 
  - 주어진 요구사항을 넘어 LCD와 LED를 활용해 현재 동작 단계와 변숫값을 실시간으로 시각화했습니다.
  - 급수 밸브의 물 높이를 0.5초당 4만큼 선형 증가시키라는 요구사항이 있었지만, 실제 구조를 반영하기 위해 이를 세탁기 내부를 눕혀진 원기둥 형태로 가정하고 삼각함수를 적용해 보다 정밀하게 구현했습니다.

---

- **2023 부산 연합 IT 동아리 PROJECT - MemeStore 개발 (BE) [MemeStore](https://github.com/WebPHub/MemeStore)** 
  - 부산 연합 개발 동아리인 PROJECT에서 **Meme Store**라는 밈 제작 웹사이트를 다양한 배경, 전공을 가진 팀원들과 협업하여 개발했습니다. Spring boot 프레임워크를 활용하여 사용자 CRUD, 밈 생성 및 삭제, 좋아요 기능의 백엔드를 담당해 개발 과정 전반을 경험했습니다.

---

- **2020 컴퓨터기초실험 프로젝트 - 마스크 자동 살균기 제작**
  - 당시 코로나19와 마스크 대란으로 인해 비말 차단용 마스크를 구하기 어려워지자, 이를 해결하기 위해 Arduino를 활용하여 일회용 마스크를 알코올과 자외선을 이용해 자동으로 소독하는 시스템을 구축하여 다회 사용할 수 있는 해결책을 제안하였습니다.

<h2 style="text-align: center;">
  <b>Awards</b><br>
</h2>

- 2025 지역문제 해결 연합 해커톤 경진대회 금상 (부경대학교 소프트웨어융합혁신원장상)
- 부산대학교 정보컴퓨터공학부 2024 전기 졸업과제 소프트웨어·인공지능 분과 금상 (부산대학교 정보의생명공학대학장상)
- 부산광역시 글로벌 해커톤 DIVE2024 삼정KPMG 발제사 3등 (부산테크노파크원장상)
- 카카오테크캠퍼스 2기 아이디어톤 최우수상
- PNU Tiny ML Challenge 2023 금상 (부산대학교 정보의생명공학대학장상)
- 2023 DX Living Solution 공모전 우수상 (부산대학교 공과대학장상)
- 2020 부산대학교 컴퓨터기초실험 프로젝트 우수상 (부산대학교 정보컴퓨터공학전공주임상)

<h2 style="text-align: center;">
  <b>Skills</b><br>
</h2>

- Languages: Java, C++, Python, SQL, JS..
- Frameworks: Spring Boot
- Database: RDMS(MySQL, H2, PostgreSQL), Elasticsearch
- ETC: Docker, AWS, Azure..

<h2 style="text-align: center;">
  <b>Education</b><br>
</h2>

- B.S. in Computer Science and Engineering, Pusan National University. Mar 2019 - Feb 2025
- [카카오테크캠퍼스 2기 BE](https://www.kakaotechcampus.com/kakaotech/about/list.do). Mar 2024 - Nov 2024 