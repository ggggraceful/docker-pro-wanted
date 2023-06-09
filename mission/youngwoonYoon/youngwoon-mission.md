## 사전 미션

1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

```text
컨테이너란 호스트 OS상에 논리적인 구획(컨테이너)을 만들고, 어플리케이션을 작동시키기 위해 필요한 라이브러리나 어플리케이션 등을 하나로 모아, 마치 별도의 서버인 것처럼 사용할 수 있게 만든 것입니다. 호스트 OS의 리소스를 논리적으로 분리시키고, 여러 개의 컨테이너가 공유하여 사용합니다. 컨테이너는 오버헤드가 적기 때문에 가볍고 고속으로 작동하는 것이 특징입니다.
비슷한 기술로 가상머신이 있지만 가상머신은 논리적으로 나눈 각 구획들 마다 os를 각각 설치해주고 하드웨어도 독립적으로 가지는 방식이기에 무겁고 비효율적이다.
```

2. 도커란 무엇입니까? (100자 이내로 요약)

```text
리눅스 컨테이너에 리눅스 어플리케이션을 프로세스 격리기술을 사용하여 더 쉽게 컨테이너로 실행하고 관리할 수 있게 해주는 오픈소스 프로젝트이다.
```

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계일까?

**도커파일**

```text
도커파일(Dockerfile) 이란? 도커파일은 docker 에서 이미지를 생성하기 위한 용도로 작성하는 파일이다. 만들 이미지에 대한 정보를 기술해 둔 템플릿(template) 이라고 보면 된다.
도커파일을 사용하면 이미지의 기능을 파악하기 쉽다는 장점이 있으며, 버전 관리에 용이하다.
```

**도커 이미지**

```text
Docker image는 파일로 어플리케이션 실행에 필요한 독립적인 환경을 포함하며, 런타임 환경을 위한 일종의 템플릿이다.
특정 시점의 어플리케이션과 가상 환경을 종합하며, 컨테이너를 통해 구동할 수 있다.
```

**도커 컨테이너**

```text
도커 컨테이너(Docner Container)는 이미지란 템플릿에서 생성된 배포된 인스턴스(Deployed Instances)입니다.
하나의 이미지로 여러 개의 컨테이너를 만들 수 있다.
```
