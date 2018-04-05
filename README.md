# 하나달 - 달이 돌아올 때까지

## 개요

- 하나달은 30일 도전을 성취할 수 있도록 관리하고, 기록해주는 앱이다.
- 하나달은 한달을 의미하고 부제목은 달이 공전을 통하여 제자리로 돌아오는 시간이 1달인 점을 의미한다.

## 기능

### 하나의 도전 (Repository)

한 Repository는 어떤 목표를 설정하고 30일동안 그 일일 목표를 달성하고 기록할 때 이용한다. 주제를 나타내기 위해서 여러 해시태그를 가지고 Public / Private으로 구분 할 수 있다.

#### Commit
- 도전의 하루 목표로 삼은 것을 완료하였을 때에 확인, 인증하는 기능

#### Star
- 관심이 일치하고 목표가 신선하거나 성실히 도전에 임하고 있으면 응원, 관심을 보이는 기능

#### Pull Request or Issues
- 목표에 조언, 충고 혹은 더 나은 방법을 다른 유저가 제공함으로써 도전에 도움을 줌

#### TODO List
- 목표를 도전할 때 할 일을 저장, 알려주는 기능

#### Diary
- 목표를 도전하고 했던 일을 기록, 후에 다른 사람들이 참고 할 수 있거나 자신의 도전을 회고할 수 있음

#### Widget / Lock Screen / Push Notification
- 위젯, 잠금화면과 알림을 통해 진행상황 등을 보여주면 유저가 이를 보고 까먹지 않고 도전을 이어나갈 수 있도록 도움

#### 후기
- 후기를 추가함으로써 후에 비슷한 도전을 하고자 하는 사람들에게 추천 및 조언 할 수 있음

---

### 포인트

포인트는 사람들의 참여를 유도하고 도전을 좀 더 수월하게 할 수 있도록 포인트를 제공한다. 더 많은 포인트 사용처를 만들어야 한다.

#### 얻는 방법
- Commit, Pull Request or Issue, Q&A에서 Answer 등

#### 사용처
- 스킨, 훈장, 질문, 랜덤박스

---

### 유저 

#### 관심분야
- 유저는 자기가 관심있는 분야를 설정 할 수 있다

#### Following
- 같은 관심사의 도전을 주로 하는 유저를 Following함으로써 그 유저의 활동을 볼 수 있는 액티비티 제공

---

### Q&A
현재 도전중인 도전에 대해서 조언받고 싶은 부분, 물어보고 싶은 부분을 포인트를 통해 질문하고 답변을 해준 사람에게는 포인트를 지급받는 형식

#### Question
- 질문을 하기 위해서는 일정한 포인트를 필요로 하며 질문에 관련 해시태그를 달아줘야 한다

#### Answer
- 답변을 해주면 그에 따른 보상 포인트를 얻을 수 있다

---

### Trending

Treding은 현재 많은 Star를 받은 Repository를 태그에 구애받지 않고 띄워주는 액티비티를 제공한다

---

### 해시태그(#)을 이용한 검색

해시태그를 이용하여 다른 사람의 도전, 이전에 했던 나의 도전, Q&A등 을 검색 할 수 있다

---

### 부가기능

- 이후 추가

---

## 구현사항

- 화이팅

----

## UI/UX

### 참고사항 
- 구글플레이 메인처럼 Navigation Drawer와 페이스북의 Tab View 사용

### 들어갈 내용
- 네비게이션에 글쓴거, 도전한거, 프로필 등
- 탭뷰로 설정, 메인, 트렌딩, 프로필
- 검색했을때에 종류별로 보여줌 ex) 운동 검색하면 운동에 관련된 도전, 운동과 관련된 Q&A 등 페이스북 검색화면처럼(사람, 페이지, 그룹 등)
- 메인에 트렌딩, 내도전, 달력 등 보여줌 간단히
- 슬랙 참조


스용이는 바보래도 깃도 깨지래요