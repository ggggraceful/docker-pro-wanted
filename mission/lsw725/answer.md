# 프리온보딩 백엔드 챌린지 4월

> ## Docker: 나만의 도커 이미지 만들기 부터, 클라우드 배포까지

## 문제

### 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

- 외부의 작업환경과 격리된 작업환경을 만드는 기술입니다. 중요한 것은 의존성으로 작업환경에서 사용할 프로세스에 대한 모든 의존성을 가진 공간을 의미합니다.

### 2. 도커란 무엇입니까? (100자 이내로 요약)

- 컨테이너 기술을 기반으로 프로세스 수준에서 가상화된 작업환경을 손쉽게 구축하고 관리할 수 있게 해주는 도구입니다.

### 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- 도커 파일은 도커 이미지를 만들기 위한 스크립트를 의미합니다. 도커 이미지가 갖는 환경에 대한 명세를 적습니다.

- 도커 이미지는 프로세스가 실행될 환경(필요한 파일들이나 프로세스)이 설정된 묶음입니다. 컨테이너를 실행할 일종의 틀이라고 할 수 있습니다.

- 도커 컨테이너는 실제로 이미지가 빌드되어 동작하는 컨테이너 환경을 말합니다.
