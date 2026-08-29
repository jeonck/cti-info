---
title: "PaperCut NG/MF 두 취약점 체이닝으로 비인증 원격 코드 실행 공격 진행 중"
date: 2026-08-29T03:34:47.726285+00:00
verdict: "학습"
tags: ["exploit-chaining", "rce", "cve-analysis"]
source: "https://thehackernews.com/2026/08/attackers-chain-two-papercut-flaws-to.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 활발히 익스플로잇 중인 인증 우회+RCE 취약점 체인으로, 내 인프라에 PaperCut이 없어 즉시조치 대상은 아니나 TTP 분석·CVE 구조화 관심 분야에 해당
- **액션:** PaperCut CVE 두 건을 STIX 2.1 Vulnerability + ExploitTarget 객체로 모델링하고 MITRE ATT&CK T1190(Exploit Public-Facing Application) 매핑 추가
