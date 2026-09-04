---
title: "Elementor Pro 미인증 PHP 파일 업로드 → RCE 취약점 (CVE-2026-32475, CVSS 9.0)"
date: 2026-08-21T22:28:27.344954+00:00
verdict: "학습"
tags: ["cve-2026-32475", "wordpress-plugin", "rce"]
source: "https://thehackernews.com/2026/08/elementor-pro-flaw-could-let.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** CVSS 9.0 고위험 CVE이나 운영 중인 WordPress/Elementor Pro 인프라가 없으며, 현재 활발한 익스플로잇·CISA KEV 등재 미확인 — CVE 관심 분야로 학습 판정
- **액션:** CVE-2026-32475를 STIX Vulnerability 객체로 모델링하고, 'unrestricted file upload → RCE' TTP 패턴을 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 지식그래프에 추가
