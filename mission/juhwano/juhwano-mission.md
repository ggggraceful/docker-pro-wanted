1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

- 소프트웨어 개발에서 컨테이너는 표준화된 소프트웨어 유닛입니다. 기본적으로 코드 패키지이며 해당 코드를 실행하는데 필요한 종속성과 도구가 포함되어있습니다.
  <br/>
  <br/>

2. 도커란 무엇입니까? (100자 이내로 요약)

- 도커는 컨테이너 기술을 사용하여 애플리케이션의 배포, 확장 및 관리를 자동화하는 오픈 소스 플랫폼입니다. 컨테이너 내에서 프로세스를 간소화하여 다양한 환경에서 이식성, 리소스 효율성 개선 및 일관성을 유지합니다.
  <br/>
  <br/>

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- 도커파일: 도커 이미지를 빌드하기 위한 지침이 포함된 텍스트 파일입니다. 이 파일은 기본 이미지, 애플리케이션 종속성, 구성 및 기타 필수 구성 요소를 정의합니다.
- 도커 이미지: 도커 파일에서 생성된 컨테이너의 스냅샷입니다. 앱, 종속성 및 필수 런타임 환경이 포함된 가볍고 이식 가능한 실행 가능한 패키지입니다.
- 도커 컨테이너: 실행 중인 도커 이미지의 인스턴스입니다. 컨테이너는 애플리케이션을 격리하여 여러 환경에서 일관된 동작을 보장합니다.
- 관계: 도커 파일 -> 빌드 -> 도커 이미지 -> 실행 -> 도커 컨테이너.


---
[실행 화면] <br/>

- docker build
<img width="810" alt="스크린샷 2023-03-20 오후 10 10 31" src="https://user-images.githubusercontent.com/77667889/226349009-d646391c-906f-43e1-87aa-d12bdc1f14a0.png">


- docker run
<img width="620" alt="스크린샷 2023-03-20 오후 10 11 08" src="https://user-images.githubusercontent.com/77667889/226349608-9d3f1fda-11f6-4102-8152-0aea333af46f.png">
