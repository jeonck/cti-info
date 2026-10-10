---
title: "Citrix NetScaler Critical RCE 취약점(CVE-2026-107406) 패치 공개"
date: 2026-10-10T01:34:45.908355+00:00
verdict: "학습"
tags: ["cve-critical", "rce", "netscaler"]
source: "https://thehackernews.com/2026/10/citrix-patches-critical-netscaler-flaw.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** NetScaler의 Critical RCE CVE로 CISA KEV 등재 또는 PoC 공개 여부는 미확인이나, 신규 Critical CVE 공개 및 벤더 보안 권고로 관심 분야(CVE/취약점) 해당
- **액션:** CVE-2026-107406을 STIX 2.1 Vulnerability/Indicator 객체로 모델링하고, SAML 배포 환경에서의 익스플로잇 조건(memory overflow → RCE 경로)을 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 지식그래프에 추가
