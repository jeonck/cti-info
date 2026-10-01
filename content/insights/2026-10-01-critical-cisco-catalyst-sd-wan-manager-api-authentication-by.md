---
title: "Cisco Catalyst SD-WAN Manager API 인증 우회(CVE-2026-76504) 야생 익스플로잇 확인"
date: 2026-10-01T01:08:57.076039+00:00
verdict: "즉시조치"
tags: ["active-exploitation", "critical-cve", "authentication-bypass"]
source: "https://www.rapid7.com/blog/post/etr-critical-cisco-catalyst-sd-wan-manager-api-authentication-bypass-exploited-in-the-wild-cve-2026-76504"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** CVSS 9.8 + 야생 익스플로잇 확인된 Critical CVE — CTI 파이프라인 우선순위 1순위(활발히 익스플로잇 중인 Critical CVE)에 직접 해당, CISA KEV 등재 가능성 높아 즉시 수집·구조화 필요
- **액션:** CVE-2026-76504를 STIX 2.1 Vulnerability 객체로 모델링하고 CWE-177(URL 인코딩 부적절 처리) 연결, ATT&CK T1190(Exploit Public-Facing Application)에 매핑 후 지식그래프에 ingestion — CISA KEV 등재 여부 주기적 폴링 설정
