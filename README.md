## AI 챗봇을 이용한 건강 자가진단 및 주변 병원 온라인 예약 서비스
-  ### Health self-diagnosis using AI chatbot and online reservation service for nearby hospital

### Production
https://tukdoctor.shop

### 연구 개발 배경
- 주기적인 병원 방문
    - 병원을 주기적으로 방문하여 진료를 받는다면 예약을 통해 대기없이 진료를 받고 싶음
- 예기치 못한 병원 방문
    - 갑작스럽게 몸이 아플때 예약을 하지 못할 가능성이 크므로 현재 병원의 영업유무를 알고싶음
- 혼란스러운 상황
    - 어떤 병원을 가야할지 혼란스러운 상황에서 간단한 설문을 통해 진단이나 진료과 추천을 받고싶음


### 커밋 컨벤션
- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `docs`: 문서 수정
- `style`: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- `refactor`: 코드 리펙토링
- `test`: 테스트 코드, 리펙토링 테스트 코드 추가
- `chore`: 빌드 업무 수정, 패키지 매니저 수정
- ex) feat: 로그인 기능 구현
    - : 뒤의 메시지는 알아보기 쉽게만 작성, 따로 컨벤션을 두진 않음
 
### 깃 전략 (git flow)

- `main` : 제품으로 출시될 수 있는 브랜치
- `develop` : 다음 출시 버전을 개발하는 브랜치
- `feature` : 기능을 개발하는 브랜치

### 아키텍처
<img width="939" alt="스크린샷 2023-06-08 오후 8 22 05" src="https://github.com/KPUHeyDoctor/.github/assets/99026631/b3017b02-2ae0-4fbf-83f1-e8ae14a02cc7">

### 시스템 모듈 상세 설계 - 챗봇
<img width="996" alt="스크린샷 2023-04-25 오후 11 57 17" src="https://user-images.githubusercontent.com/99026631/234317761-18156706-79ce-4ef9-a55b-7e545ea80e1d.png">

