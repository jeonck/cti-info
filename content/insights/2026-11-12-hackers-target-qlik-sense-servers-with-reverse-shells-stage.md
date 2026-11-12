---
title: "Qlik Sense 서버 대상 리버스 셸 공격 및 ActiveMQ·Veeam 익스플로잇 스테이징 캠페인 분석"
date: 2026-11-12T02:46:36.810312+00:00
verdict: "학습"
tags: ["ttp-analysis", "exploit-chaining", "threat-actor-campaign"]
source: "https://thehackernews.com/2026/11/hackers-target-qlik-sense-servers-with.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Qlik Sense 취약점 악용, ActiveMQ/Veeam 익스플로잇 스테이징 등 실제 캠페인의 TTP 분석 사례로 ATT&CK 매핑 및 위협 행위자 동향 연구에 해당
- **액션:** 해당 캠페인의 TTP(PowerShell reverse shell, 익스플로잇 체이닝)를 MITRE ATT&CK 기법(T1059.001, T1190 등)으로 매핑하고 STIX 2.1 Campaign/Attack-Pattern 객체로 모델링 초안 작성
