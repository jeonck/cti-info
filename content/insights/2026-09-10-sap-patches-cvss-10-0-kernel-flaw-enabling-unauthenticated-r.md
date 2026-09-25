---
title: "SAP Extended Passport 처리 모듈에서 CVSS 10.0 메모리 커럽션 취약점(CVE-2026-44756) 패치 공개"
date: 2026-09-10T23:50:46.911653+00:00
verdict: "학습"
tags: ["cvss-10", "sap-rce", "memory-corruption"]
source: "https://thehackernews.com/2026/09/sap-patches-cvss-100-kernel-flaw.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** SAP 인프라를 운영하지 않아 직접 패치 대상은 아니나, CVSS 10.0 최고등급 CVE(인증 없이 RCE 가능한 메모리 커럽션)로 CTI 취약점 구조화 관심 분야에 해당
- **액션:** CVE-2026-44756을 STIX 2.1 Vulnerability/Indicator 객체로 정규화하고, memory-corruption → unauthenticated-RCE 공격 체인을 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 지식그래프에 추가
