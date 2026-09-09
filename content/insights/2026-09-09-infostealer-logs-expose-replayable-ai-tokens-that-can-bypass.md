---
title: "인포스틸러 로그로 MFA 우회 가능한 AI 서비스 토큰 탈취 TTP 분석"
date: 2026-09-09T23:54:39.878153+00:00
verdict: "학습"
tags: ["infostealer", "credential-theft", "ttp-analysis"]
source: "https://thehackernews.com/2026/09/infostealer-logs-expose-replayable-ai.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 인포스틸러(Lumma, Vidar)의 AI 서비스 세션 토큰 탈취 TTP — 악성코드 행위 패턴 및 신규 공격 기법 분석 관심 분야에 해당
- **액션:** Lumma Stealer / Vidar의 AI 토큰 수집 행위를 MITRE ATT&CK T1528(Application Access Token) 및 T1539(Steal Web Session Cookie)에 매핑하고, 관련 IOC(인포스틸러 C2, 로그 마켓플레이스)를 STIX Indicator 객체로 정규화하는 모델링 초안 작성
