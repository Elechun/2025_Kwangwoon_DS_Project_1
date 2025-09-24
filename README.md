# 2025_Kwangwoon_Univ_DS_Project_1

Please read Update Notes regularly before proceeding with the task and check for any updates before proceeding.  

---

## Update Notes  

**2025-09-15 :**  
- initial upload  

**2025-09-24 :**
- VMWare 설치 과정 문제 관련 설명 추가
- 아래 이미지와 같은 오류가 지속될 시 조교에게 메일로 문의바랍니다.
<img width="745" height="248" alt="image" src="https://github.com/user-attachments/assets/f80e3b8f-bdc3-467d-99ec-d9b494f38e3c" />

---

## Due Date  

- **2025-10-12 23:59:59** 까지가 최종 제출 마감일입니다.  
- **추가 제출 기간**은 **2025-10-13 00:59:59** 까지이며, 이 경우 제출은 인정되지만 **득점 점수에서 10% 감점**이 적용됩니다.  
- 제출 전에 반드시 제안서를 꼼꼼히 읽어보시고, 요구사항을 모두 충족했는지 확인하시기 바랍니다.  
- 프로젝트 진행 중 궁금한 사항은 GitHub 저장소의 **Issues** 탭을 통해 질문해 주시기 바랍니다.
- 설계, 실습 모두 듣는 학생들은 실습 수업에 제출 후, 설계 제출란엔 텍스트 파일 제목을 "실습 수업에 제출"로 제출하기

---

## How to Clone Repository  

```bash
sudo apt-get install git
git clone https://github.com/Elechun/2025_Kwangwoon_DS_Project_1.git
```

---

## NEED TO DOWNLOAD!!!!
```bash
sudo apt install make
sudo apt install gcc
sudo apt install g++
```

## Install VSCode
- 우분투에서 아래 링크 접속 후 .deb 파일 다운로드
- https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64
- 반드시 deb파일이 위치한 디렉토리 내에서 수행해야 함.
```bash
sudo apt install code_1.104.0-1757488003_amd64.deb
```

## How to Run  
- 반드시 Makefile이 위치한 디렉토리 내에서 수행해야 함. cd(change directory)로 변경하기
```bash
cd DS_Project1_25
make
./run
```

---

## 구현 고려사항  

- 제공된 스켈레톤 코드는 참고용이며, 본인이 원하는 방식으로 함수를 자유롭게 추가하거나 수정하여 구현할 수 있다.  
- 단, **과제 제안서에 명시된 요구사항**을 반드시 충족해야 한다.  
- **Queue 자료구조 구현 시 STL Queue 사용은 불가**하며, 직접 구현해야 한다.  
- 함수명, 데이터 형식, 클래스 구조는 자유롭게 변경 가능하지만, 전체 프로그램의 실행 흐름과 명령어 처리 방식은 과제 명세를 따라야 한다.  
- 스켈레톤 코드는 빌드 성공을 보장하지 않으며, 학생이 직접 수정 및 보완하여 완성해야 한다.  
- 추가적으로 **`log_조교.txt`** 와 **`command_조교.txt`** 파일을 함께 제공하였다. `log_조교.txt`에는 각 명령어 결과에 대한 설명이 포함되어 있으므로 구현 시 참고.
- 반드시 **`command.txt`**와 **`Music_List.txt`** 파일은 소스코드 파일과 같이 있어야 한다.  
- 본 프로젝트는 **데이터구조 수업에서 다루는 기본 자료구조의 동작 확인**을 목적으로 하는 과제이다. 따라서 극단적인 예외 상황까지 고려할 필요는 없다. (예: 가수와 노래 제목이 모두 같은 경우, 실제로 존재하는 노래인지 검증하는 과정 등은 구현 대상에서 제외된다.)
  
- MAEKPL 명려어 : ARTIST, TITLE 옵션으로 하나의 데이터가 아닌 여러개의 데이터를 한번에 넣는 과정에서, 넣고자 하는 여러 데이터 중 하나라도 PlayList에 존재한다면, Error code로 처리해 주시면 되겠습니다. **`log_조교.txt`**에 해당 예시가 있으니 참고바랍니다.
- LOAD 명령어의 경우 한번만 LOAD 하는 경우로 구현 하시면 되겠습니다. 
---
