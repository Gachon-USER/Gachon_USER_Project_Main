# Gachon_USER

---

![Untitled](https://github.com/Gachon-USER/Project_Main/blob/main/img_data/main_0.png)

가천대 AI 소프트웨어 학과 졸업작품 프로젝트 인 USER 프로젝트 위키 페이지 입니다.

# Project Goal

- 프로젝트 목적 :
    - 1인가구 시대가 도래하고 코로나 시대를 넘어 고물가 시대에 접어들면서 점차 집밥 수요가 증가하고 있는 현 상황에 맞추어 사용자가 간편하게 사용할수 있는 요리 레시피 서비스를 제공하고자 함.

# **Key Features**

- 음성으로 조작 가능한 레시피 시스템.
    - 기능구현 :
        - 사용자 음성을 인식가능한 ChatBot 모델을 제작 및 학습하여 사용자가 음성을 통해 ChatBot과 대화하며 레시피 조작이 가능하도록 구현함.
- 사용자가 직접 자신만의 레시피를 등록하고 이를 다른이가 사용 가능한 시스템.
    - 기능구현 :
        - 기존에 작성되어 있는 레시피 데이터 외에 별도로 사용자가 레시피를 작성할수 있는 UI 시스템과 이와 연동되는 어플리케이션 서버 시스템을 제작.
- 사용자별 맞춤 레시피 추천 시스템.
    - 기능구현 :
        - 별도의 추천 시스템을 제작하여 API 형태로 제공, 이를 UI를 통해 접근하여 사용가능한 방식으로 제작됨.

# **Key Implementation Units**

Define Implementation Units of this project. 

프로젝트 구현을 위해 제작된 세부 유닛 기능 리스트 (별도 페이지 설명)

### GUI

- 안드로이드 어플리케이션으로 제작된 UI 시스템 :
    - UI 구현 내용 :
    
    ![Untitled](https://github.com/Gachon-USER/Project_Main/blob/main/img_data/main_1.png)
    
    - 세부 구현 내용 : [https://github.com/Gachon-USER/Project_Main/wiki/GUI](https://github.com/Gachon-USER/Project_Main/wiki/GUI)

### DataBase

- 레시피 추천을 위한 레시피 데이터 및 사용자 정보 (사용자 이용기록, 검색기록 등) 를 관리하는 관계형 데이터 베이스 (SQL Light) 구현.
    - 세부 구현 내용 : [https://github.com/Gachon-USER/Project_Main/wiki/DataBase](https://github.com/Gachon-USER/Project_Main/wiki/DataBase)

### ChatBot

- 음성 레시피 조작을 위한 ChatBot 시스템.
    - 작동 방식 설명 :
        - 사용자 음성 → STT → ChatBot(음성 분석 및 명령 파악) → UI (명령에 따른 반응) → TTS
    
    ![Untitled](https://github.com/Gachon-USER/Project_Main/blob/main/img_data/main_2.png)
    
    - 세부 구현 내용 : [https://github.com/Gachon-USER/Project_Main/wiki/AI-ChatBot](https://github.com/Gachon-USER/Project_Main/wiki/AI-ChatBot)

### Server

- UI 시스템이 데이터 베이스 및 ChatBot 시스템과 연동하여 동작할수 있도록 API 기능을 제공하는것을 목적으로 제작된  Java Spring boot 서버 프로젝트.
    - 구현내용 이미지 :
        
        ![Untitled](https://github.com/Gachon-USER/Project_Main/blob/main/img_data/main_3.png)
        
    - 세부 구현 내용 : [https://github.com/Gachon-USER/Project_Main/wiki/Server](https://github.com/Gachon-USER/Project_Main/wiki/Server)

### API

- 프로젝트 내에서 제작된 ChatBot, Server 유닛에서 제공하는 전체 API 목록 및 상세 설명 페이지
    - 세부 내용 :  [https://github.com/Gachon-USER/Project_Main/wiki/API_LIST](https://github.com/Gachon-USER/Project_Main/wiki/API_LIST)
