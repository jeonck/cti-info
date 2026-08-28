---
title: "Next.js 인증 없는 RCE 취약점 2건 패치 — AVIF 파싱 및 Windows 경로 순회"
date: 2026-08-28T06:01:12.270545+00:00
verdict: "학습"
tags: ["cve-rce", "nextjs", "exploit-analysis"]
source: "https://thehackernews.com/2026/08/nextjs-patches-critical-avif-and.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Next.js 인프라를 운영하지 않으므로 직접 패치 대상은 아니나, Critical RCE CVE 및 익스플로잇 경로 분석은 CTI 취약점 구조화 관심 분야에 해당
- **액션:** CVE-2026-75604(Windows 경로 순회)와 AVIF 파싱 RCE를 STIX Vulnerability 객체로 모델링하고, 익스플로잇 체인을 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 샘플 STIX 번들 작성
