---
title: "CWP 서버에 숨겨진 Linux 백도어 — 웹 요청으로 로그 없이 명령 실행"
date: 2026-11-07T01:43:06.270073+00:00
verdict: "학습"
tags: ["linux-backdoor", "log-evasion", "ttp-mapping"]
source: "https://thehackernews.com/2026/11/hackers-hide-linux-backdoor-in-control.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CWP 웹 서버 백도어의 로그 회피 기법은 MITRE ATT&CK T1505(서버 소프트웨어 컴포넌트)/T1562(방어 회피) TTP 분석·모델링 사례로 CTI 구조화 연구에 활용 가능
- **액션:** 백도어 행위 패턴을 MITRE ATT&CK T1505.003(웹 셸)/T1562.006(로그 회피)으로 매핑하고 STIX 2.1 Attack-Pattern + Indicator 객체 초안 작성
