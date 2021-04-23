# nuber-eats-clone

노마드코더 uber-eats 클론 강의를 바탕으로 기능 추가하여 마무리한 토이 프로젝트 입니다.

### 00. Preview
- Socket 통신으로 실시간 연동, Google Map Route
<img width="80%" src="https://user-images.githubusercontent.com/39077714/115924275-793f5c80-a4ba-11eb-81a7-4a3469c2ece0.gif"/>
<br/>

- 로그인, 주소 설정
<img width="80%" src="https://user-images.githubusercontent.com/39077714/115925977-fd92df00-a4bc-11eb-8420-0e058a4cef52.gif"/>

### 01. 개인적으로 추가한 기능
- 유저에게서 주소 입력 받고, 우편번호 검색(daum postcode API)
- 배달원 - 가게 - 고객 간의 경로 라우팅(google map API)
- 배달원 대쉬보드 개선
- 메뉴에 이미지 추가
- 기타 사소한 변경들

### 02. 사용한 것들
- Nest JS
- Typescript
- TypeORM
- GraphQL
- Apollo
- React JS with Typescript
- Jest
- Cypress
- postgres(heroku)
- netlify

### 03. 강의에서 다룬 주제
- User Authentication
- Email Verification(구현은 했지만, 돈 나가서 메일 보내기 설정은 안해둠)
- Photo Upload(AWS S3)
- Nest JS(Modules, Guards, Middlewares, Decorators
- Online Payment(사업자 등록 필요해서 구현하지 않음)
- Google Map
- Unit Testing
- E2E Testing
- Data Visualization(고도화 안해서 빼버림)
- Tailwind CSS
- JWT Autentication

### 04. To-do(라고 적어두고 아마 안할 것)
- 코드 정리(자금처럼 코딩해놓으면 뒤통수 맞을듯)
- 구글맵 -> naver 또는 daum postcode로 변경
- AWS로 이사(세팅하기 귀찮아서 안했는데...)
- 사업자등록증 신청해서 payment 구현
- React Native로 이사
- 

### 05. 참고 사항 및 링크
- 프리티어 서버다보니 서버가 깨는데 30초 정도 걸릴 수 있음.
- 한국에서 google Map API는 routing을 지원하지 않음. 이거 몰라서 왜 안될까 며칠동안 고민함.  
- 그래서 유저가 주소 세팅하거나 배달원 위치가 달라져도 미국으로 변경되게 설정해둠.
- https://nuber-eats-abys.netlify.app/
- id: client@user.com/ pw: 12345
- id: owner@user.com/ pw: 12345
- id: delivery@user.com / pw: 12345
- backend랑 frontend repo는 공개하려 했는데 확인할게 좀 필요해서 아직... 예전에 실수로 api키들을 .gitignore 추가 안한 적이 있는데, 이후에 지웠는데도 commit 이력에 남아서 private으로 돌려둔 상태, 없애는 법 찾아고 없앤 다음에 공개 하든지 하겠음)
