---
title: "Langflow 심각도 9.9 인증 RCE 취약점, 허니팟서 1,423건 익스플로잇 시도 포착"
date: 2026-10-17T00:12:48.020439+00:00
verdict: "학습"
tags: ["critical-rce", "active-exploitation", "ai-platform-vulnerability"]
source: "https://thehackernews.com/2026/10/langflows-critical-authenticated-rce.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** Langflow는 내 CTI 파이프라인 스택에 포함되지 않으나, CVSS 9.9 + 1,423건 허니팟 공격 탐지된 활발한 익스플로잇 사례로 CVE·TTP 분석 관심 분야에 해당
- **액션:** CVE-2026-105740을 STIX Vulnerability 객체로 모델링하고, 허니팟 기반 공격 시도 데이터(공격 벡터, 인증 우회 패턴)를 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 지식그래프에 추가
