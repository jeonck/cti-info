---
title: "jscrambler 8.14.0 npm 패키지 공급망 침해 — 설치 시 Rust 인포스틸러 실행"
date: 2026-07-11T22:53:29.112612+00:00
verdict: "학습"
tags: ["supply-chain-attack", "malicious-npm", "infostealer"]
source: "https://thehackernews.com/2026/07/compromised-jscrambler-8140-npm-release.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** npm 공급망 공격(악성 preinstall 훅 + infostealer) 사례로, TTP 분석 및 위협 행위자 캠페인 연구에 해당
- **액션:** 해당 캠페인을 MITRE ATT&CK T1195.001(공급망 소프트웨어 타협)에 매핑하고, STIX Bundle로 TTP·IOC 정규화 초안 작성
