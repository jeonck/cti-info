---
title: "keyv 연계 npm 웜, 868개 패키지 오염 — Claude Code·VS Code 훅 심기 TTP 확인"
date: 2026-08-04T23:06:05.653692+00:00
verdict: "학습"
tags: ["supply-chain-attack", "npm-worm", "ide-hook-persistence"]
source: "https://thehackernews.com/2026/08/keyv-linked-npm-worm-poisons-hundreds.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** npm 웜을 통한 공급망 공격 + Claude Code/VS Code 훅 심기라는 신규 TTP — MITRE T1195(공급망 침해) 및 T1546(이벤트 기반 지속성) 매핑 사례로 CTI 구조화 연구에 직접 활용 가능
- **액션:** keyv@6.0.0 웜의 확산 경로(353→868 패키지)를 STIX Campaign/Malware 오브젝트로 모델링하고, IDE 훅 심기를 T1546 서브테크닉으로 ATT&CK 매핑 초안 작성
