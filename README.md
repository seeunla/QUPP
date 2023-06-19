# QUPP

### 김세은 맡은 부분
- **Spring Security** 기반의 회원 도메인에 **MVC 패턴** 적용
- **CI/CD** **자동 배포**를 위한 **docker + spring + mariadb + jenkins + ncloud** 기반의 인프라 구성
- 팀내 인프라 구성, [배포 가이드](https://www.notion.so/613a77f4b7ee46578f1c8f96458d17ce)
- **EC2, NCP**으로 서버 구축 및 배포
- **Rest API**를 이용한 사용자 도메인의 회원가입, 로그인, 비밀번호 수정, **jwt** 구현 및 사용자 도메인의 닉네임 중복, 이메일 중복, 닉네임 수정 리팩토링
- Git commit 규칙, 노션 페이지 진행 상황 캘린더, 주 1회 CS공부, 깃허브 풀 리퀘스트 규칙을 정립해 코드 리뷰 작성 등 적극적으로 커뮤니케이션하며 프로젝트 진행
  - 노션 진행 상황 캘린더 [`노션 페이지`](https://www.notion.so/328abb459b894647b1ad8cc35d7ad4da) 
- 기존 프로젝트의 Pull Requests
  - [QUPP.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ec5beb23-0206-44ce-b5f8-273c6f667179/QUPP.pdf)
### 시연영상
https://user-images.githubusercontent.com/107592967/211485482-b7218bd5-5764-4101-b0fd-70f2ed5689a6.mp4


## 🔥 QUPP란?

QUPP는 기존 질의응답 서비스들의 타겟이 되지 못했던 이들을 위해 기획된 서비스입니다.

QUPP는 Question University Problem Platform의 약어로, 대학생들의 학업상 궁금증을 해소해주겠다는 의미를 담고 있습니다.

[QUPP 소개 PDF 확인 가능](https://github.com/seeunla/QUPP/blob/master/QUPP.pdf)


### 기존 서비스의 한계점
- 연령층
  - 콴다: 고등학생 이하를 대상으로 한다.
- 영역
  - Chegg: 공학
  - StackOverFlow: 개발

### 개선안
- (연령층) 학부 수준에 관심이 있는 누구나
- (영역) 모든 전공을 커버

## 😎 프로젝트 세부 사항

### 로드맵 및 진행상황

[노션 페이지](https://www.notion.so/qupp/328abb459b894647b1ad8cc35d7ad4da) 를 통해 확인 가능

## ⭐️️ Git 규칙

### ❗️ Branch

#### main
  - 배포
#### feature
  - 기능 개발
  - ex. User의 login 관련 기능을 개발하는 경우: feature-user-login
####  hotfix
  - 버그 수정
  - ex. User의 login 관련 버그를 수정하는 경우: hotfix-user-login
#### others
  - 그 외의 것
  - 리팩토링, 문서작성, 설정변경 등

### ❗️ Commit

- commit 규칙은 [다음](https://jason-api.tistory.com/89) 을 참조하되, 완화시켜 진행

- 예시
> 타입(Type): 제목(Title)
> 
> 본문

#### 타입(Type)

- FEAT: 기능개발
- FIX: 버그수정
- DOCS: 문서수정
- STYLE: 스타일수정 (들여쓰기, 세미콜론 등)
- REFACTOR: 리팩토링
- TEST: 테스트코드
- CHORE: 빌드, 패키지매니저 수정 (gitignore 등)

#### 제목(Title)

- 첫글자는 대문자
- 마침표(.) 없이 종결

#### 본문

- 제목과 본문 사이에는 한 줄 공백
- 본문에는 '어떻게'가 아닌 '무엇'을 '왜' 했는지 기입

## 팀회고

### 💡테크톡처럼 해보기

- 현재의 수업 스타일에서 어떠한 개념을 구체적으로 복습하기란 어렵다.
- 테크톡처럼 주제를 한 가지 정하여, 어느정도 깊이 있게 공부를 해보자.
- 면접 질문에도 대비하고 포토폴리오도 될 수 있는, 두 마리의 토끼를 잡아보자.
- 주제 선정은 '해당 주차에 발표하는 사람끼리 주제가 겹치지 않으면서 & 전 주에 다뤘던 내용 중 하나'
- ex. 8/18 발표: 8/8 ~ 8/12의 수업 내용 중 하나를 선택

|회차|날짜|주제|담당자| 진행사항 |
|---|---|---|---|:----:|
|1|22.08.18|Restful API<br>쿠키/세션/토큰|김세은<br>민찬기|✅<br>✅|
|2|22.08.25|Bean<br>Maven&Gradle|송용호<br>임소망|✅<br>✅|
|3|22.09.01|Transaction<br>Properties|정영환<br>김세은|✅<br>✅|
|4|22.09.08|Singleton<br>Stream|민찬기<br>송용호|✅<br>✅|
|5|22.09.15|HTTP&HTTPS<br>Interface|임소망<br>정영환|✅<br>✅|
|6|22.09.22|OAuth<br>CORS|김세은<br>민찬기|✅<br>✅|
