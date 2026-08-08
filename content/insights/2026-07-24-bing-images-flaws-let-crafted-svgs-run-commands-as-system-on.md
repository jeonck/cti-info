---
title: "Bing 이미지 처리 서버에서 조작된 SVG로 SYSTEM 권한 RCE 달성 — Critical CVE-2026-32194 공개"
date: 2026-07-24T23:06:46.309981+00:00
verdict: "학습"
tags: ["critical-cve", "rce-ttp", "svg-exploit"]
source: "https://thehackernews.com/2026/07/bing-images-flaws-let-crafted-svgs-run.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** Microsoft Bing 서버 측 SVG 처리 파이프라인의 RCE 취약점(CVE-2026-32194)으로, 사용자 운영 인프라와 무관하나 SVG를 매개로 한 RCE TTP 및 신규 Critical CVE로서 CTI 분석 관심 범위에 해당
- **액션:** CVE-2026-32194 STIX Vulnerability 객체 생성 후 공격 기법(SVG 파일 파싱 → SYSTEM 권한 RCE) 을 ATT&CK T1203(Exploitation for Client Execution) 또는 T1190에 매핑해 지식그래프에 추가
