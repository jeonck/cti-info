---
title: "Cursor 에디터 취약점: 악성 저장소 클론 시 git.exe 위장 바이너리 자동 실행"
date: 2026-07-15T23:02:50.675029+00:00
verdict: "학습"
tags: ["supply-chain-attack", "path-hijacking", "windows-execution"]
source: "https://thehackernews.com/2026/07/cursor-flaw-lets-malicious-cloned.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Cursor 에디터의 git.exe 경로 하이재킹 취약점 — 악성 저장소 클론 시 자동 코드 실행으로 이어지는 공급망/실행 기법(TTP)이며 CTI 공격 시나리오 모델링에 참조 가치 있음
- **액션:** MITRE ATT&CK T1574.007(Path Interception by PATH Environment Variable) 또는 T1195(Supply Chain Compromise)로 매핑하고, '악성 저장소 내 위장 바이너리 자동 실행' 패턴을 TTP 온톨로지에 신규 노드로 추가
