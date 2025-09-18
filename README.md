# Vibe App

안드로이드 기반의 Vibe 앱입니다.

## 📱 앱 소개

Vibe App은 사용자에게 환영 메시지를 보여주는 간단하고 깔끔한 안드로이드 애플리케이션입니다.

## ✨ 주요 기능

- **환영 화면**: "Hello Vibe" 메시지와 함께 사용자를 환영
- **모던한 UI**: Material Design을 활용한 깔끔한 인터페이스
- **ViewBinding**: 안전한 뷰 바인딩을 통한 UI 관리

## 🛠️ 기술 스택

- **언어**: Kotlin
- **플랫폼**: Android
- **최소 SDK**: API 24 (Android 7.0)
- **타겟 SDK**: API 36
- **아키텍처**: MVVM (Model-View-ViewModel)
- **UI**: Material Design Components
- **바인딩**: ViewBinding

## 📋 요구사항

- Android 7.0 (API 24) 이상
- Android Studio Arctic Fox 이상
- Kotlin 1.8.0 이상

## 🚀 설치 및 실행

1. 프로젝트 클론
```bash
git clone https://github.com/[사용자명]/2509172.git
cd 2509172
```

2. Android Studio에서 프로젝트 열기

3. Gradle 동기화

4. 앱 빌드 및 실행
```bash
./gradlew assembleDebug
```

## 📁 프로젝트 구조

```
app/
├── src/main/
│   ├── java/com/example/a2509172/
│   │   ├── MainActivity.kt
│   │   └── ui/
│   │       ├── dashboard/
│   │       ├── home/
│   │       └── notifications/
│   ├── res/
│   │   ├── layout/
│   │   ├── values/
│   │   └── ...
│   └── AndroidManifest.xml
├── build.gradle.kts
└── proguard-rules.pro
```

## 🎨 스크린샷

앱의 주요 화면들:
- 환영 화면: "Hello Vibe" 메시지 표시
- 메인 화면: 깔끔한 UI와 함께 사용자 인터페이스 제공

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

프로젝트에 대한 문의사항이 있으시면 이슈를 생성해 주세요.

---

**Vibe App** - 간단하고 아름다운 안드로이드 앱
