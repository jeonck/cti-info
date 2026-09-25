---
title: "우크라이나 웹사이트 해킹 후 가짜 Cloudflare 페이지로 Psychedelic Stealer 유포하는 ClickFix 캠페인"
date: 2026-09-25T00:21:06.217708+00:00
verdict: "학습"
tags: ["clickfix-ttp", "infostealer-analysis", "malware-campaign"]
source: "https://thehackernews.com/2026/09/hacked-ukrainian-sites-serve-fake.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 악성코드(Psychedelic Stealer) 캠페인 분석 — ClickFix 기법과 TTP 패턴이 ATT&CK 매핑 및 위협 행위자 동향 연구에 해당
- **액션:** Psychedelic Stealer의 전달 체인(ClickFix→msiexec 클립보드 인젝션)을 MITRE ATT&CK T1204.002(User Execution: Malicious File), T1566(Phishing) 등으로 매핑하고 STIX Malware/Attack-Pattern 객체로 초안 작성
