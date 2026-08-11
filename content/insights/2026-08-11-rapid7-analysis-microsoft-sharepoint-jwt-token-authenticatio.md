---
title: "Microsoft SharePoint JWT 인증 우회 CVE-2026-55040 — Rapid7 PoC 공개"
date: 2026-08-11T22:46:54.111389+00:00
verdict: "즉시조치"
tags: ["cve-exploit", "authentication-bypass", "sharepoint"]
source: "https://www.rapid7.com/blog/post/ra-microsoft-sharepoint-jwt-token-authentication-bypass-cve-2026-55040"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** PoC 공개 직후의 Critical 인증 우회 취약점으로, CTI 파이프라인에서 TTP·익스플로잇 체인 구조화 우선 수집 대상
- **액션:** Rapid7 PoC 및 기술 분석을 기반으로 CVE-2026-55040의 STIX 2.1 Vulnerability + Attack Pattern 객체 작성 (JWT 위조 체인 4단계를 kill chain 단계로 매핑, MITRE ATT&CK T1550.004 Valid Accounts: Cloud Accounts 연계)
