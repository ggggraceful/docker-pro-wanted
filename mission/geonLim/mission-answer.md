### 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
- 컨테이너 기술은 애플리케이션을 실행하는 데 필요한 종속성 및 모든 구성 요소가 포함된 경량의 독립 실행형 패키지에 소프트웨어를 패키징하는 방법입니다.

### 2. 도커란 무엇입니까? (100자 이내로 요약)
- 도커는 컨테이너에서 분산 애플리케이션을 구축, 배송 및 실행하기 위한 일종의 플랫폼 및 도구의 세트입니다. 도커를 사용하면 개발자는 로컬 및 프로덕션 서버까지 다양한 환경에서 일관되게 실행할 수 있는 단일 컨테이너에 애플리케이션과 종속성을 패키징할 수 있습니다.

### 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
- 도커파일 : 도커파일은 애플리케이션의 구성 요소와 구성을 정의(종속성 설치 등)하는 선언전 스크립트입니다. 이후 도커이미지를 빌드하는데 사용됩니다.
- 도커 이미지 : 도커이미지는 변경할 수 없으며 다양한 환경에서 배포 및 재사용할 수 있습니다.
- 도커 컨테이너 : 도커 이미지에서 실행되며 애플리케이션 실행을 위한 가볍고 격리된 환경을 제공합니다.