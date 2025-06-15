< 앱 소개 >
- BodyCareApp은 사용자 회원가입, 로그인, 운동 루틴 생성 및 관리, 운동 루틴 공유, 식단 관리 등의 기능을 제공하는 헬스케어 Android 애플리케이션입니다.

< 개발 환경 >
- Android Studio
- Kotlin 버전: 1.8.21 이상
- Android SDK 버전: API Level 35 (Android 15.0 VanillaIceCream) 이상

< 테스트 환경 >
- Android Emulator (Pixel 5 Android 15.0 "VanillaIceCream")

< 실행 방법 >
1. Android Studio 설치

2. 프로젝트 열기
- BodyCareApp 폴더를 Android Studio에서 열기

3. Gradle 버전 수정
- gradle-wrapper.properties 파일에서 다음처럼 설정:
distributionUrl=https\://services.gradle.org/distributions/gradle-8.12-bin.zip

4. 필요 라이브러리 동기화
- Android Studio 상단 메뉴에서 File > Sync Project with Gradle Files 실행

5. Device Manager에서 (Pixel 5 Android 15.0 "VanillaIceCream") 실행

6. 최상단 바에서 Run > Run 'app' 클릭