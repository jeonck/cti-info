---
title: "PostgreSQL 52개 취약점 패치 — 22년 된 인증된 RCE 버그(CVE-2026-6460, CVSS 8.8) 포함"
date: 2026-11-14T02:02:16.957889+00:00
verdict: "학습"
tags: ["cve-rce", "postgresql", "vendor-patch"]
source: "https://thehackernews.com/2026/11/postgresql-patches-52-flaws-including.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 8.8 인증된 RCE CVE(CVE-2026-6460)로 관심 분야인 신규 CVE·취약점 항목에 해당하나, 운영 중인 PostgreSQL 인프라가 없어 즉시조치·백로그 대상은 아님
- **액션:** CVE-2026-6460을 STIX Vulnerability 객체로 모델링하고, 'authenticated RCE via type confusion' TTP를 ATT&CK T1059(Command Execution) 또는 T1203과 매핑해 지식그래프에 추가
