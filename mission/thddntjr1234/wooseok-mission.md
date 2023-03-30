
## 사전 미션
### 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
->컨테이너 기술이란 개별 소프트웨어의 실행환경을 운영체제에 종속되지 않고 독립적으로 운용할 수 있도록 컨테이너 단위로 격리하여 독립성을 확보해 주는 기술을 말합니다.

<br>

### 2. 도커란 무엇입니까? (100자 이내로 요약)
도커란 서버에 독립된 환경을 만들어서 소프트웨어를 구동할 수 있도록 하는 컨테이너 기반의 오픈소스 가상화 플랫폼입니다.

<br>

### 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
도커 파일이란 도커 이미지를 생성하기 위한 용도로 작성하는 설정 파일입니다.

도커 이미지는 소프트웨어를 실행하기 위한 실행 환경과 소스코드, 의존성, 라이브러리 등을 포함한 파일입니다.

도커 컨테이너란 도커 이미지를 기반으로 생성하며 프로그램을 실행하는 데 필요한 모든 설정, 의존성, 라이브러리 등을 컨테이너라는 공간 안에 구성한 것으로 서버 운영체제와 독립된 실행 환경을 가집니다.

따라서 서로간의 관계는 다음과 같습니다.

도커 파일 -> 도커 이미지 -> 도커 컨테이너