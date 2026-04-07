<p align="center">
  ![QLMD-001](https://github.com/user-attachments/assets/4b2c4d2b-97e0-434c-a0ba-ca6973651d71)
</p>

<h1 align="center">QLMD</h1>

<p align="center">
  <strong>QuickLook Markdown Viewer for macOS</strong><br>
  스페이스바로 마크다운 파일을 미리보세요
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14%2B-blue">
  <img src="https://img.shields.io/badge/Swift-5.9-orange">
  <img src="https://img.shields.io/badge/license-Proprietary-red">
</p>

---

## 📥 설치

1. [**Latest Release**](https://github.com/haseo-ai/qlmd-releases/releases/latest)에서 `QLMD.dmg` 다운로드
2. DMG를 열고 `QLMD.app`을 **Applications** 폴더로 드래그
3. 앱을 **한 번 실행** (QuickLook 확장 등록)

## ✨ 기능

- 🚀 **GitHub 스타일 렌더링** — cmark-gfm, 100KB 파일 < 20ms
- 📖 **자동 목차 (TOC)** — 헤딩 기반 사이드바
- 🔍 **코드 하이라이팅** — 180+ 언어 지원
- 🎨 **다크/라이트 테마** — 시스템 설정 자동 감지
- 🔤 **실시간 번역** — 12개 언어, 오프라인 (macOS 26+)
- 📐 **수식 렌더링** — KaTeX
- 📊 **다이어그램** — Mermaid
- 🔍 **줌** — 50% ~ 200%
- 📄 **원본 보기** — Raw Markdown 토글

## 📋 시스템 요구사항

- macOS 14.0+ (기본 기능)
- macOS 26.0+ (번역 기능)
- Apple Silicon / Intel

## 🚀 사용법

Finder에서 마크다운 파일 (`.md`, `.markdown`, `.mdown`) 선택 후 **스페이스바**를 누르세요.

## 🔧 QuickLook 확장 수동 등록

설치 후 미리보기가 작동하지 않으면 터미널에서:

```bash
/System/Library/Frameworks/CoreServices.framework/Frameworks/LaunchServices.framework/Support/lsregister -f /Applications/QLMD.app
qlmanage -r cache
killall Finder
```

## 📜 라이선스

Proprietary. All rights reserved.
