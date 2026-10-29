# 화면 번역기 Android

안드로이드 화면의 영어·일본어를 읽어, 글자가 있던 자리 위에 한국어 번역을
겹쳐 보여 주는 앱입니다. OCR과 번역은 모두 기기 안에서 처리합니다.

이 저장소에는 APK만 올립니다.

## 내려받기

**[최신 APK 받기](https://github.com/reezex0-ux/screen-translator-android-releases/releases/latest/download/ScreenTranslator-Android.apk)**
· [모든 버전](https://github.com/reezex0-ux/screen-translator-android-releases/releases)

- Android 10 이상. 고품질 영어 번역(QuickMT)은 64비트 기기에서만 됩니다.
- Play 스토어 앱이 아니어서 설치할 때 '출처를 알 수 없는 앱' 허용을 묻습니다.
- 모든 APK는 같은 키로 서명합니다. 인증서 SHA-256:
  `02:B0:46:C8:E8:6E:4B:08:3A:87:D5:CD:52:57:25:16:52:9C:1B:D8:2E:70:16:47:DA:46:15:94:A9:D7:C1:64`

## 쓰는 법

1. 앱 아이콘을 누르고, 처음 한 번 '다른 앱 위에 표시'를 허용합니다.
2. 화면 녹화 동의 창에서 **시작**을 누르면 떠 있는 **번역** 버튼이 나옵니다.
3. 버튼을 누르면 지금 화면을 번역해 원문 위에 겹쳐 보여 주고, 아무 곳이나 누르면
   사라집니다. 버튼을 길게 누르면 꺼집니다.
4. 아이콘을 길게 눌러 나오는 **설정**에서 고품질 영어 번역 모델을 받거나
   **업데이트 확인**으로 새 버전을 설치합니다.

## 포함된 구성 요소

- Google ML Kit (글자 인식, 기기 내 번역)
- [CTranslate2](https://github.com/OpenNMT/CTranslate2) (MIT),
  [SentencePiece](https://github.com/google/sentencepiece) (Apache 2.0)
- QuickMT 영한 모델은 앱에 들어 있지 않고, 사용자가 받기를 누를 때 내려받습니다
  (CC BY 4.0).
