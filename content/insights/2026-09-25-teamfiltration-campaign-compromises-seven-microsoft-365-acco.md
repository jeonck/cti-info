---
title: "TeamFiltration 캠페인, Microsoft 365 계정 7개 침해 — 패스워드 스프레이 TTP 분석"
date: 2026-09-25T00:21:06.217708+00:00
verdict: "학습"
tags: ["credential-stuffing", "campaign-analysis", "microsoft-365"]
source: "https://thehackernews.com/2026/09/teamfiltration-compromises-seven.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** M365 인프라 운영 환경 없으나, TeamFiltration 도구 기반 캠페인(UNK_CondorFiltration)의 TTP(패스워드 스프레이, T1110.003)·위협 행위자 분석이 CTI 구조화 관심 분야에 해당
- **액션:** Proofpoint 보고서 기반으로 UNK_CondorFiltration 캠페인을 STIX 2.1 Campaign/ThreatActor/AttackPattern 오브젝트로 모델링하고, AWS EC2 소스 IP 활용 패턴을 ATT&CK T1110.003에 매핑
