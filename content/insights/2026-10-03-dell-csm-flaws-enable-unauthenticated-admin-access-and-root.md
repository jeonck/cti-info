---
title: "Dell CSM 인증 우회 취약점(CVSS 10.0) — Kubernetes 노드 루트 권한 탈취 가능"
date: 2026-10-03T01:01:08.256745+00:00
verdict: "학습"
tags: ["critical-cve", "kubernetes", "authentication-bypass"]
source: "https://thehackernews.com/2026/10/dell-csm-flaws-enable-unauthenticated.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 10.0 신규 Critical CVE로 CVE 심각도 추적 관심 분야에 해당하나, 운영 중인 Dell CSM/Kubernetes 인프라 없음
- **액션:** CVE-2026-63688을 STIX 2.1 Vulnerability 객체로 모델링하고, 인증 우회(T1078) TTP와 매핑해 ATT&CK 관계 노드 추가
