---
title: "기존 방어 우회하는 신규 Spectre-v2 BTR 변종, Linux 메모리 유출 가능"
date: 2026-09-30T01:09:26.980305+00:00
verdict: "학습"
tags: ["spectre-v2", "side-channel-attack", "cpu-vulnerability"]
source: "https://thehackernews.com/2026/09/new-spectre-v2-btr-attack-leaks-linux.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 CPU 부채널 공격 기법(Spectre-v2 BTR) 연구 공개 — 활발한 익스플로잇 미확인, CISA KEV 미등재이나 TTP 분석 관점에서 新공격기법 패턴으로 기록 가치 있음
- **액션:** BTR(Branch Target Reuse) 기법을 MITRE ATT&CK T1212(취약점 익스플로잇) 또는 하드웨어 사이드채널 관련 TTP 노드로 지식그래프에 추가하고, CVE 번호 확정 시 STIX Vulnerability 객체 생성 준비
