---
title: "Unbound DNSSEC 검증기 힙 오버플로우(CVE-2026-81642) — RCE 가능 Critical 취약점"
date: 2026-09-17T23:59:49.648128+00:00
verdict: "학습"
tags: ["cve-analysis", "dns-security", "rce"]
source: "https://thehackernews.com/2026/09/critical-unbound-dnssec-validator-flaw.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Unbound DNS 취약점(CVE-2026-81642)은 내 인프라에 직접 해당하지 않으나, 신규 Critical CVE·PoC 공개 패턴으로 CTI 구조화 연구의 취약점 데이터 수집 대상
- **액션:** CVE-2026-81642를 STIX 2.1 Vulnerability 객체로 모델링하고 CVSS 점수·익스플로잇 조건(악성 DNS 존 제어 필요)을 관계 속성으로 정규화
