---
title: "ClickFix 공격으로 배포되는 macOS 기반 암호화폐 탈취 스틸러"
date: 2026-08-07T22:39:48.624149+00:00
verdict: "학습"
tags: ["clickfix", "macos-malware", "ttp-analysis"]
source: "https://thehackernews.com/2026/08/clickfix-attacks-deliver-macos-stealer.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** ClickFix 기법을 활용한 macOS 스틸러 캠페인으로, TTP 분석 및 공격자 행위 패턴 연구 관심 분야에 해당
- **액션:** ClickFix 감염 체인(shell script → 아키텍처별 페이로드 fetch)을 MITRE ATT&CK T1059.004(Unix Shell), T1566(Phishing)으로 매핑하고 STIX Campaign/Malware 객체로 모델링 초안 작성
