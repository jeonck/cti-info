---
title: "PHP Windows 패키지, Brotli 라이브러리 RCE 취약점(CVE-2026-111497) 긴급 재빌드"
date: 2026-10-27T01:17:17.810075+00:00
verdict: "학습"
tags: ["cve-2026-111497", "rce-vulnerability", "supply-chain-dependency"]
source: "https://thehackernews.com/2026/10/php-issues-second-windows-security.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVE/취약점 관심 분야에 해당하는 신규 Critical CVE(PHP Windows Brotli RCE)이나, 운영 중인 PHP 인프라 없음 — 구조화·분석 대상 취약점 레코드로 수집
- **액션:** CVE-2026-111497을 STIX Vulnerability 객체로 정규화: affected_versions(PHP 8.2–8.5 Windows), attack_vector(cURL/Brotli 자동 압축해제), impact(memory corruption→RCE) 필드 채워 지식그래프에 추가
