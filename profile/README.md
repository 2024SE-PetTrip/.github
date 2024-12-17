# Pet Trip

<img src="https://github.com/user-attachments/assets/f4ff64b9-0d4c-4365-8438-605806201614" width="500"/>

### 2024-2 소프트웨어공학 프로젝트
> ‘Pet Trip’은 같은 지역 내 반려동물 보호자 커뮤니티를 활성화하기 위한 서비스입니다. 사용자는 나만의 산책 코스를 생성하고 공유하거나, 다른 보호자들과의 산책 모임을 모집할 수 있습니다.
<br>

## :hammer_and_wrench: STACKS
<div> 
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"> 
  <br>
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</div>
<br>

## :rocket: Setup Instructions
### 백엔드(Spring Boot) 실행
#### 1. 데이터베이스 설정
실행을 위해 MySQL을 설치하고, 데이터베이스와 사용자를 설정해야 합니다.
   ```sql
   CREATE DATABASE pettrip;
   ```
   사용자 계정 정보는 다음과 같습니다
   ```java
   spring.datasource.username=pettripAdmin
   spring.datasource.password=pettrip2024
   ```
   MySQL은 `localhost:3306`에서 실행되고 있어야 합니다.
   <br><br>

#### 2-1. Gradle을 통한 빌드 및 실행
 1. PetTrip_spring 디렉터리의 root에서 `./gradlew build -x test` 명령어를 통해 프로젝트를 빌드합니다. <br>
 2. `java -jar build/libs/PetTrip-0.0.1-SNAPSHOT.jar` 명령어를 통해 빌드된 JAR 파일을 실행할 수 있습니다.
 <br><br>
 
#### 2-2. IntelliJ에서 실행
 1. IntelliJ의 Database 창에서 '+' 버튼으로 MySQL을 추가합니다. <br>
 2. 다음과 같이 설정하고 DB 연결을 마칩니다.
   ```java
   Host: localhost
   Port: 3306
   User: pettripAdmin
   Password: pettrip2024
   ```
 3. Run 버튼으로 프로젝트를 실행합니다.

#### API 서버는 기본적으로 `http://localhost:8080`에서 실행됩니다.

<br> 

### 프론트엔드(Flutter) 실행
1. Flutter SDK 설치
2. 프로젝트 의존성 설치: `flutter pub get` 명령어를 통해 의존성을 설치합니다.
3. 실제 안드로이드 모바일 디바이스를 연결하고 Run 버튼으로 프로젝트를 실행합니다.

<br> 

## :information_desk_person: TEAM MEMBER
|Name|Github ID|Role|
|------|-------|------|
|이태환|[HwantaLee](https://github.com/HwantaLee)|Team Leader, Back-end|
|김수민|[angelsusum](https://github.com/angelsusum)|Front-end|
|김건우|[gnvvoo](https://github.com/gnvvoo)|Front-end|
|조서희|[JoeSeoHee](https://github.com/JoeSeoHee)|Back-end|

<br>

## :package: REPOSITORY
- [Frontend Repository](https://github.com/2024SE-PetTrip/PetTrip_flutter.git)
- [Backend Repository](https://github.com/2024SE-PetTrip/PetTrip_spring.git)
