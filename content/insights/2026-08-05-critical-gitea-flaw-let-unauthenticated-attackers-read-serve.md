---
title: "Gitea 비인증 파일 읽기 취약점 CVE-2026-59774 (CVSS 9.8) — 1.27.1로 패치"
date: 2026-08-05T23:03:18.805981+00:00
verdict: "학습"
tags: ["cve-critical", "file-read", "supply-chain-adjacent"]
source: "https://thehackernews.com/2026/08/critical-gitea-flaw-let-unauthenticated.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Gitea가 명시된 CTI 파이프라인 스택(OpenCTI, MISP 등)에 포함되지 않으나, CVSS 9.8 Critical CVE로서 관심 분야인 '취약점·익스플로잇' 항목에 해당
- **액션:** CVE-2026-59774를 STIX Vulnerability 객체로 모델링하고, 'unauthenticated file read via markup rendering' 패턴을 TTP 매핑(T1005 등)과 연결해 샘플 그래프에 추가
