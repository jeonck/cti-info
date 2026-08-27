---
title: "SLEEPWALKER 백도어: 특수 패킷 수신 후 자체 바이트코드 실행하는 신규 Windows 악성코드"
date: 2026-08-27T03:01:01.000790+00:00
verdict: "학습"
tags: ["malware-analysis", "ttp-mapping", "backdoor"]
source: "https://thehackernews.com/2026/08/newly-sleepwalker-backdoor-waits-for.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 악성코드 분석 리포트로, 독자적 바이트코드 실행 구조 및 대기형 백도어 행위 패턴이 CTI TTP 분석·모델링 관심 분야에 해당
- **액션:** SLEEPWALKER의 트리거 메커니즘(crafted packet → 바이트코드 실행)을 MITRE ATT&CK T1205(Traffic Signaling) 및 T1620(Reflective Code Loading)에 매핑하고 STIX Malware 객체 초안 작성
