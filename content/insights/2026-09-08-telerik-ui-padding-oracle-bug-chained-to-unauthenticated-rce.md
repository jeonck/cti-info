---
title: "Telerik UI ASP.NET AJAX 패딩 오라클→비인증 RCE 체인, 공개 익스플로잇 등장"
date: 2026-09-08T00:04:06.245835+00:00
verdict: "학습"
tags: ["padding-oracle", "unauthenticated-rce", "public-exploit"]
source: "https://thehackernews.com/2026/09/telerik-ui-padding-oracle-bug-chained.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** 공개 익스플로잇이 방금 나온 Unauthenticated RCE 취약점으로 CVE/익스플로잇 관심 분야에 해당하나, 야생 익스플로잇 미확인·비기본 설정 한정·7월 패치 완료로 즉시조치 요건(KEV 등재, 활발한 익스플로잇) 미충족
- **액션:** TantoSec PoC 분석하여 padding-oracle→RCE 공격 체인을 MITRE ATT&CK(T1190 Exploit Public-Facing Application) 매핑 후 STIX Course of Action 오브젝트로 구조화
