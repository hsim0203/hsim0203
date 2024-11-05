# 안녕하세요 👋, 개발자를 희망하는 임현수 입니다!

게임을 좋아하고, 대화하는것을 좋아하는 개발자 임현수입니다..

---

## 👨‍💻 About Me:
학점은행제를 통해 컴퓨터공학을 전공<br> 현재는 폴리텍대학 하이테크과정 인공지능소프트웨어 학과에서 웹 프로그래밍을 배우고 있습니다.
<!--
- 🔭 I’m currently working on **[Project Name](Link to Project)**
- 🌱 I’m currently learning **[Technology or Tool]**
- 👯 I’m looking to collaborate on **[Type of Projects or Technologies]**
- 💬 Ask me about **[Your Skills or Topics You Are Good At]**
- 📫 How to reach me: **[Your Email]**
- ⚡ Fun fact: **[Interesting Fact About You]**
-->
---

## 🛠️ My Tech Stack:

- **Languages**: 
  - ![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![C](https://img.shields.io/badge/C-000000?style=flat&logo=C&logoColor=white)

- **Frontend**:
  - ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white)

- **Backend**:
  - ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white) ![JSP](https://img.shields.io/badge/-JSP-323330?style=flat&logo=java&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

- **Databases**:
  - ![Oracle](https://img.shields.io/badge/-Oracle-F80000?style=flat&logo=oracle&logoColor=white)

- **Libraries & Framework**:
  - ![JQuery](https://img.shields.io/badge/-JQuery-0769AD?style=flat&logo=jquery&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat&logo=mybatis&logoColor=white)

- **Tools & Platforms**:
  - ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![Eclipse](https://img.shields.io/badge/-Eclipse-2C2255?style=flat&logo=eclipse&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white) ![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat&logo=pycharm&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)


---

## 🚀 My Projects:

### **[접근성 완화를 위한 손동작 및 음성인식 배리어프리 키오스크](https://github.com/hsim0203/kiosk_project)**
프로젝트 기간 : 2024.10.01 ~ 2024.11.08
- **프로젝트 인원 :** 2명
- **GitHub Repository :** [https://github.com/hsim0203/kiosk_project](https://github.com/hsim0203/kiosk_project)

`Python`, `Tensorflow`, `Whisper`, `KNN`, `Sequence-to-Sequence`, `Mediapipe`, `Flask` ,`Unity`,~~`LSTM`~~

- 편리한 키오스크 사용을 위한 손동작 인식, 음성인식 키오스크
- **개요 및 목적**
    - 키오스크 사용이 힘들거나 불편한 사람들을 위한 배리어 프리 키오스크 제작
    - 딥러닝 모델에 대한 학습 및 이해도 향상
    - 백앤드, 프론트앤드를 확실히 구분해 개발하는 방법 학습
- **세부기능**
  - **음성인식**
    - Unity로부터 음성파일을 전송받은 후 Whisper를 사용해 text로 변경
    - Whisper를 통해 변환된 text를 seq2seq모델에 입력 시퀀스로 사용해 출력 시퀀스 출력
    - 출력 시퀀스를 답변으로 하여 Unity로 넘겨주고 tts처리를 통해 대화형 키오스크 구현
  - **손동작 인식**
    - 손동작 이미지를 전송 받아 학습된 KNN 알고리즘을 통해 손동작을 판별
    - ~~손동작 이미지를 전송 받아 학습된 LSTM 모델을 통해 손동작을 판별~~(판별을 하기위해 프레임이 많이 필요하고, 응답시간이 길어 KNN으로 대체)
    - 판별된 손동작의 결과(손동작, 정확도)를 JSON형태로 Unity로 전송
    - Unity에서 Flask로부터 전송받은 JSON 객체를 통해 동작
- **보완할점**
    - Seq2Seq 모델 학습을 위한 데이터셋 부족(소상공인 질의-응답 데이터를 사용)
    - Seq2Seq모델 학습시 mecab과 같은 형태소분석을 추가, attention이나 transformor 모델을 사용하여 성능 향상 가능
            
<hr>

### **[Mydog 애견 쇼핑몰](https://github.com/hsim0203/ShoppingMall)**
프로젝트 기간 : 2024.06.26 ~ 2024.07.04
- **프로젝트 인원 :** 개인 프로젝트
- **GitHub Repository :** [https://github.com/hsim0203/ShoppingMall](https://github.com/hsim0203/ShoppingMall)

`JAVA`, `Oracle`, `JavaScript`, `Html`, `CSS3`, `Jquery`, `MyBatis`, `jsp`

- 상품 카테고리별 검색 및 장바구니, 주문등의 기능을 갖춘 쇼핑몰 프로젝트
- **개요 및 목적**
    - JSP, HTML 등의 웹페이지 코딩 기술능력 향상
    - MVC 모델에 대한 지식 및 이해도 향상
    - OPEN API(DAUM 주소) 활용방법 익히기
    - AJAX를 통한 비동기 통신방법 익히기
- **세부기능**
    - 회원가입 및 로그인 : 회원가입시 다음주소api를 통한 주소 조회 및 등록, AJAX를 통한 중복아이디 체크기능
    - 메인페이지(신규 등록상품 추천) 및 제품 카테고리별 페이지
    - 상품 상세페이지 : 상품 상세정보,선택한 수량만큼 장바구니 담기 기능
    - 장바구니 페이지 : 장바구니에 담긴 품목 및 수량, 가격 확인, 담긴 항목 삭제, 선택한 항목 주문
    - 결제 페이지 : 결제시 주소 변경(기존 주소 or 새로운 주소 등록)
    - 관리자 상품 추가
- **보완할점**
    - 상품 이름일부 검색등의 직접 검색 기능
    - 카테고리별 상품창의 페이징 기능
    - 상품 삭제 등의 관리자 기능 추가 및 관리자페이지 추가
            
<hr>

### **[DogWorld](https://github.com/JungmiP/dogWorld)**
프로젝트 기간 : 2024.07.08 ~ 2024.07.12
- **프로젝트 인원 :** 3명
- **담당 업무 :** 스프링부트 통합페이지 코딩
- **GitHub Repository :** [https://github.com/JungmiP/dogWorld](https://github.com/JungmiP/dogWorld)
  
`Spring Boot`, `Oracle`, `JAVA`, `Html`, `CSS3`
  
- 각자 개인프로젝트로 진행하였던 애견용품 쇼핑몰, 애견유치원, 동물병원의 통합페이지
- **개요 및 목적**
    - 개인프로젝트들을 통합하는 프로젝트
    - 사이트 통합로그인 기능 구현
    - DBLink등을 사용한 DB테이블 공유
- **세부기능**
    - DBLink를 통한 회원, 애견정보 테이블 통합
    - 통합페이지로서 통합로그인 기능(접속했던 사이트 url 저장 및 로그인 후 돌아감)
    - 마이페이지 : 회원정보 조회 및 수정, 수정시 비밀번호 재확인
    - 애견정보 : 애견정보 조회, 등록, 수정
- **보완할점**
    - 통합로그인 기능 : 현제 구현된 방식(쿠키, 파라미터)방식의 보안성 문제
    - 통합페이지 자체의 기능 부족

<hr>

### **[자바 콘솔환경 이메일시스템](https://github.com/hsim0203/Email-Con-Work)**
프로젝트 기간 : 2024.04.18 ~ 2024.04.25
- **프로젝트 인원 :** 개인 프로젝트
- **GitHub Repository :** [https://github.com/hsim0203/Email-Con-Work](https://github.com/hsim0203/Email-Con-Work)
  
`Java`, `Oracle`
  
- 이클립스 자바 콘솔환경에서의 이메일 시스템 구축 프로젝트
- **개요 및 목적**
    - 프로젝트의 진행과정 파악
    - JAVA 프로그래밍 실력 향상
    - DB설계 및 제작 실력 향상
- **세부기능**
    - 로그인 및 회원가입, 아이디 중복 시 회원가입 재시도
    - 메일함 : 전체 메일함, 수신 메일함, 송신 메일함 분류
    - 휴지통 : 휴지통 메일 조회, 상세보기, 영구삭제
    - 메일 수신 또는 송신날자 최신순으로 조회 및 넘버링
    - 메일 작성 및 전송
    - 메일 삭제 시 휴지통 이동
- **보완할점**
    - 자바 콘솔환경의 한계점(기능이나 메일 선택시 기능번호를 일일히 입력 등)
    - 회원가입중 아이디 중복시 중복체크시점이 뒤에있어 실패시 회원정보를 다시 작성해야함
    - ORACLE 페이징기능을 통한 메일 페이징

<hr>

### **[스프링부트 수어탐지 웹사이트](https://github.com/hsim0203/Spring-Boot-Sign-Language-Recognition)**
프로젝트 기간 : 2024.07.15 ~ 2024.07.29
- **프로젝트 인원 :** 개인 프로젝트
- **GitHub Repository :** [https://github.com/hsim0203/Spring-Boot-Sign-Language-Recognition](https://github.com/hsim0203/Spring-Boot-Sign-Language-Recognition)
  
`Spring Boot`, `Python`, `mediapipe`, `Flask`, `OpenCV`, `LSTM`  

- FLASK 및 LSTM 모델을 사용해 수어탐지 RestServer를 만들고 이를 통해 스프링 웹 페이지 캠화면에서 수어탐지를 하는 프로젝트입니다
- **개요 및 목적**
    - Flask를 활용한 RestServer 구현방법 학습
    - LSTM, YOLO 등의 머신러닝 학습
    - Spring Boot와 RestServer 간의 통신 방법 학습
- **세부기능**
    - 스프링 웹페이지 화면에서 캠을 통한 이미지 저장
    - RestServer로 이미지 데이터를 JSON 객채로 변환 후 전송
    - 전송받은 JSON객체를 이미지 변환 후 LSTM모델을 통해 수어 정확도 예측
    - Spring Boot로 정확도 반환 및 캠화면에 표시
![수어탐지](https://github.com/user-attachments/assets/1898f4b7-d46a-428d-a7de-2aa1e8d224f1)

- **보완할점**
    - M동작의 정확도가 낮게 측정

<hr>
