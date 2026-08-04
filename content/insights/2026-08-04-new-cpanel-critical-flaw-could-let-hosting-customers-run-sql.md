---
title: "cPanel 치명적 결함 CVE-2026-58048: 호스팅 고객이 DB 루트로 SQL 실행 가능"
date: 2026-08-04T23:06:05.653692+00:00
verdict: "학습"
tags: ["cve", "privilege-escalation", "sql-injection"]
source: "https://thehackernews.com/2026/08/new-cpanel-critical-flaw-could-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 9.4의 신규 CVE로 관심 분야(CVE/취약점 동향)에 해당하나, 내 인프라에 cPanel 없음 — 즉시조치 대상 아님
- **액션:** CVE-2026-58048을 STIX Vulnerability 객체로 모델링하고, privilege-boundary-crossing 패턴(테넌트→DB root)을 ATT&CK T1078/T1611에 매핑해 온톨로지에 추가
