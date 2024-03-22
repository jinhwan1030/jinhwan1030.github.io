---
title: "React Native 입문 가이드: 설치부터 프로젝트 만들기까지"
date: 2024-03-16 10:20:00 +0900
categories: [Programming, React Native]
tags: [react native, installation, project, debugging, tutorial]
---

## React Native란?

React Native는 Facebook에서 개발한 오픈 소스 모바일 애플리케이션 프레임워크로, JavaScript와 React를 사용하여 iOS와 Android 양쪽 모두에서 실행될 수 있는 네이티브 모바일 앱을 개발할 수 있게 해줍니다.

## React Native 시작하기

### 1. React Native 설치하기

React Native 개발을 시작하기 전에 Node.js와 npm이 설치되어 있어야 합니다. React Native CLI를 글로벌하게 설치하기 위해 다음 명령어를 사용하세요.

```bash
npm install -g react-native-cli
```

### 2. 새 프로젝트 생성하기

React Native CLI를 사용하여 새로운 프로젝트를 생성하려면, 원하는 디렉토리에서 다음 명령어를 실행하세요.

```bash
react-native init MyFirstReactNativeApp
```

### 3. 프로젝트 실행하기
프로젝트 폴더로 이동한 다음, iOS 또는 Android 시뮬레이터/디바이스에서 앱을 실행할 수 있습니다.

- iOS에서 실행하기
```bash
cd MyFirstReactNativeApp
npx react-native run-ios
```

- Android에서 실행하기
```bash
cd MyFirstReactNativeApp
npx react-native run-android
```

### 4. 기본 코드 이해와 디버깅
React Native 프로젝트를 생성하면 App.js 파일에 기본 코드가 자동으로 생성됩니다. 이 파일은 앱의 시작점이며, 간단한 UI 구성 요소를 수정하여 앱의 외관을 변경할 수 있습니다.