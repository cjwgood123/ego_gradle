1. jenkins가 리소스에 접근하는데 필요한 credentials 등록
2. 깃허브 레포지토리 webhook 설정
3. pipeline Item생성
4. 파이프라인 코드 작성


1.github repository credential 등록
깃허브 레포지토리에 접근하기 위한 credential을 등록
깃허브 계정의 액세스 토큰을 발급 
Jenkins Credencials에 대상 레포지토리에 대한 토큰 등록.


2. Github repository Webhook 설정 
웹훅은 깃허브 레포지토리에 변화가 발생한다면 깃허브에서 젠킨스로 이벤트가 생겼다고 알림을 
그 경로를 설정 ->   깃허브 레포지토리

![image](https://github.com/cjwgood123/ego_gradle/assets/47588727/3d5048ad-18f3-4ded-9c55-41570825be7d)


3 파이프라인 등록 

![image](https://github.com/cjwgood123/ego_gradle/assets/47588727/1c93064a-1e2a-42a6-84ee-fd0f6291c096)

Build Trigger를 Github hook trigger for GitScm Polling 으로 체크



# ego_new
전자정부 프레임워크 작업 이력 안내 

1. 기존 CentOs 설치된 docker 에 젠킨스 설치.
3. 전자정부 프레임워크 4.2v  공통컴포넌트 설치 
4. 전자정부 프레임워크 4.2v  gradle로 변환 및 필요 라이브러리 변환
6. 전자정부 프레임워크 프로젝트 githook 설정
7. 젠킨스 pipeLine 작성


![image](https://github.com/cjwgood123/ego_gradle/assets/47588727/3ac055f0-2efb-4ef0-bb9a-e847c8ea3ecb)

