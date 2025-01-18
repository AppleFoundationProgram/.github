# CrumpDump

CrumpDump는 감정을 기록하고 해소하는 데 도움을 주는 iOS 앱입니다.  
사용자는 감정을 선택하고 종이 쪽지에 그 감정을 적은 후, 이를 가상으로 구기고 던지는 행위를 통해 감정을 표현하고 정화할 수 있습니다.  
던진 쪽지는 귀여운 개구리 인형이 먹어 치우며 감정을 없애주는 상징적인 역할을 합니다.  
이 앱은 심리적 표현을 통해 작은 트라우마와 부정적인 감정을 긍정적인 방식으로 다룰 수 있도록 돕습니다.  

CrumpDump is an iOS app designed to help users express and release emotions.  
Users can select emotions, write them down on a virtual note, crumple it up, and throw it to symbolically process and release their feelings.  
The thrown note is "eaten" by a cute frog doll, symbolically erasing the emotions.  
This app helps users deal with small traumas and negative emotions in a positive way through psychological expression.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/e090b517-a12c-4839-a67a-ba8d166a6bb5" width="15%">
  <img src="https://github.com/user-attachments/assets/bee86fab-9a92-46da-a8f6-49dc112bf68c" width="15%">
  <img src="https://github.com/user-attachments/assets/9c309923-8287-4c96-a25d-8e52a6ccb377" width="15%">
  <img src="https://github.com/user-attachments/assets/81c411dc-bf3a-4964-93c8-d5e3d4d62f36" width="15%">
  <img src="https://github.com/user-attachments/assets/a0962735-36df-42c9-9eee-f0e6ef929ebc" width="15%">
  <img src="https://github.com/user-attachments/assets/03d29035-4916-4261-b421-e075713f8f24" width="15%">
</p>

---

## 📖 목차 | Table of Contents

- [주요 기능](#주요-기능) | Key Features  
- [기술 스택](#기술-스택) | Tech Stack  
- [주의사항](#주의사항) | Cautions  
- [프로젝트 배경](#프로젝트-배경) | Project Background  
- [앱 스토어 링크](#앱-스토어-링크) | App Store Link  
- [문의](#문의) | Contact  

---

## 주요 기능 | Key Features

### 1. 감정 기록 | Emotion Recording
- 사용자는 현재 느끼고 있는 감정이나 상황을 자유롭게 기록할 수 있습니다.  
  작성된 감정은 이후 종이에 적혀 구겨지며, 던지기 애니메이션을 통해 감정을 해소할 수 있습니다.  
- Users can freely record their current emotions or situations.  
  The recorded emotion is written on a piece of paper, crumpled, and thrown to help release emotions.

### 2. 감정 선택 | Emotion Selection
- 사용자는 버리고 싶은 감정을 선택할 수 있습니다.  
  여러 감정 카테고리에서 원하는 감정을 최대 3개까지 선택하여 감정의 본질을 구체화할 수 있습니다.  
- Users can select emotions they want to discard.  
  Up to three emotions can be chosen from various categories to clarify their essence.

### 3. 종이 구기기 | Crumpling the Note
- 사용자는 화면에서 종이를 길게 눌러 가상으로 종이를 구기면서 진동 및 오디오 효과를 경험할 수 있습니다.  
  이 행위는 감정을 물리적으로 분리하는 느낌을 제공합니다.  
- Users can virtually crumple the note by pressing and holding it on the screen, experiencing vibration and sound effects.  
  This action helps users feel as if they are physically separating from their emotions.

### 4. 던지기 | Throwing the Note
- 사용자는 구긴 종이를 목표물(인형)에 던지는 동작을 통해 감정을 해소할 수 있습니다.  
  던지기 동작은 CoreMotion을 활용해 사용자의 모션 데이터를 분석하여 정확히 감지합니다.  
- Users can throw the crumpled note towards a target (the frog doll) as a way to release their emotions.  
  Throwing is accurately detected by analyzing user motion data using CoreMotion.

---

## 기술 스택 | Tech Stack

- **SwiftUI**: 직관적이고 심플한 UI 구성.  
- **CoreMotion**: 던지기 동작을 감지하고 모션 데이터를 기록.  
- **AVFoundation**: 구기기 및 던지기 시의 사운드 효과 제공.  
- **UIKit Dynamics & CAAnimation**: 종이 던지기의 현실적 애니메이션 구현.  

---

## 주의사항 | Cautions

- **안전한 사용**: 던지기 동작은 가상입니다. 실제로 핸드폰을 던지지 마세요.  
  넉넉한 공간에서 사용하세요.  
- Safe Usage: The throwing action is virtual.  
  Do not physically throw your phone. Use the app in a spacious area.

---

## 프로젝트 배경 | Project Background

- 이 프로젝트는 **Apple Developer Academy @POSTECH**의 **Foundation Program 4기** 결과물입니다.  
- This project was developed during the Apple Developer Academy @POSTECH as part of Foundation Program 4th Cohort.

---

## 앱 스토어 링크 | App Store Link

- CrumpDump는 [앱 스토어](https://apps.apple.com/kr/app/crumpdump/id6737130375)에서 다운로드할 수 있습니다.  
- CrumpDump is available on the [App Store](https://apps.apple.com/kr/app/crumpdump/id6737130375).

---

## 문의 | Contact

- 질문이나 제안 사항이 있으시면 **andrewkimswe@gmail.com**로 연락해주세요.  
- For questions or suggestions, please contact **andrewkimswe@gmail.com**.
