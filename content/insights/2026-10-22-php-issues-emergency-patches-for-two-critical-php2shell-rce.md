---
title: "PHP 긴급 패치: PHP2Shell 치명적 RCE 2건, 익스플로잇 시도 포착"
date: 2026-10-22T00:30:02.001225+00:00
verdict: "즉시조치"
tags: ["critical-rce", "active-exploitation", "php-vulnerability"]
source: "https://thehackernews.com/2026/10/php-issues-emergency-patches-for-two.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 활발한 익스플로잇 시도가 확인된 Critical RCE(PHP2Shell), CISA KEV 등재 가능성 높음 — CTI 파이프라인에서 즉시 IOC·TTP 구조화 대상
- **액션:** CVE-2026-109618/109619를 STIX 2.1 Vulnerability/Indicator 객체로 정규화하고, 관련 PoC·exploit attempt IOC를 수집해 ATT&CK T1190(Exploit Public-Facing Application)에 매핑
