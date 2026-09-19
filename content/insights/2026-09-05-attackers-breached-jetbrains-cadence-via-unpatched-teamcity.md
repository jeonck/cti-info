---
title: "TeamCity 미패치 취약점으로 JetBrains Cadence 침해 — AWS 자격증명 탈취"
date: 2026-09-05T23:38:09.326828+00:00
verdict: "학습"
tags: ["ttp-credential-access", "supply-chain-compromise", "cve-exploit"]
source: "https://thehackernews.com/2026/09/attackers-breached-jetbrains-cadence.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** TeamCity 취약점을 통한 실제 침해 사례로, TTP(초기 접근→자격증명 탈취) 분석 및 CVE 구조화 관점에서 참조 가치 있음
- **액션:** 이번 사고에 사용된 TeamCity CVE를 식별해 STIX Course of Action 및 Attack Pattern 오브젝트로 모델링하고, MITRE ATT&CK T1078(Valid Accounts)/T1552(Unsecured Credentials)에 매핑
