---
title: "ClickLock macOS 인포스틸러: 앱 강제 종료 루프로 패스워드 탈취"
date: 2026-07-16T22:59:51.636392+00:00
verdict: "학습"
tags: ["macos-malware", "ttp-analysis", "persistence"]
source: "https://thehackernews.com/2026/07/new-clicklock-macos-stealer-kills-apps.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** macOS 신규 인포스틸러(ClickLock)의 행위 패턴·지속성 기법(LaunchAgent 남용, 앱 킬 루프)은 TTP 분석 및 악성코드 행위 패턴 구조화 관심 분야에 해당
- **액션:** ClickLock의 LaunchAgent 기반 지속성 기법을 MITRE ATT&CK T1543.001(Launch Agent)에 매핑하고, 앱 킬 루프를 통한 패스워드 탈취 흐름을 STIX Course of Action 객체로 초안 작성
