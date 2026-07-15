---
title: "SonicWall SMA1000 제로데이 2종(CVE-2026-15409/15410) 야생 악용 확인 및 CISA KEV 등재"
date: 2026-07-15T23:02:50.675029+00:00
verdict: "학습"
tags: ["cisa-kev", "zero-day", "cve-ssrf-lpe"]
source: "https://www.rapid7.com/blog/post/etr-rapid7-mdr-team-discovers-new-sonicwall-sma1000-zero-days-being-actively-exploited-cve-2026-15409-cve-2026-15410"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** SonicWall SMA1000 제로데이(CVE-2026-15409/15410)는 내 인프라와 무관하나, CISA KEV 신규 등재 + CVSS 10.0 + PoC 공개된 활발히 악용 중인 취약점으로 CTI 구조화·분석 연구 대상
- **액션:** 두 CVE를 STIX 2.1 Vulnerability/Indicator 오브젝트로 정규화하고, SSRF→LPE 체인 TTP를 ATT&CK T1190(Exploit Public-Facing Application)·T1068(Privilege Escalation) 매핑 후 지식그래프에 추가
