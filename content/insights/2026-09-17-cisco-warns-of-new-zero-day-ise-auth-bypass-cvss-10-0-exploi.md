---
title: "Cisco ISE 인증 우회 제로데이 (CVE-2026-76460, CVSS 10.0) 야생 악용 확인"
date: 2026-09-17T23:59:49.648128+00:00
verdict: "즉시조치"
tags: ["cvss-10-critical", "zero-day-exploited", "auth-bypass"]
source: "https://thehackernews.com/2026/09/cisco-warns-of-new-zero-day-ise-auth.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 10.0 + 야생 활발 익스플로잇 중인 Critical CVE — CTI 파이프라인 우선순위 1순위 기준(활발히 익스플로잇 중인 Critical CVE)에 직접 해당, 즉시 STIX 구조화 대상
- **액션:** CVE-2026-76460을 STIX 2.1 Vulnerability 객체로 정규화하고, 미인증 원격 API 인증 우회 TTP를 ATT&CK T1190(Exploit Public-Facing Application)에 매핑하여 지식그래프에 등록
