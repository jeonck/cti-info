---
title: "Rust arrayref 크레이트 공급망 침해 — 빌드타임 인포스틸러 삽입"
date: 2026-08-20T22:30:51.298620+00:00
verdict: "학습"
tags: ["supply-chain-attack", "ttp-analysis", "infostealer"]
source: "https://www.bleepingcomputer.com/news/security/hackers-poison-arrayref-rust-crate-to-push-infostealer-malware/"
source_name: "BleepingComputer"
status: "완료"
---
- **근거:** 소프트웨어 공급망 공격(빌드타임 악성코드 삽입) 사례로, TTP 분석 및 위협 행위자 캠페인 리포트 관심 분야에 해당
- **액션:** arrayref 공급망 공격을 MITRE ATT&CK T1195.001(Compromise Software Dependencies)에 매핑하고, 관련 IOC(악성 crate 버전, C2 주소)를 STIX Malware/Indicator 객체로 구조화 연습
