---
title: "Microsoft 8월 패치화요일: Windows 커널 드라이버 권한상승 제로데이(CVE-2026-68820) 포함 398개 취약점 수정"
date: 2026-08-11T22:46:54.111389+00:00
verdict: "학습"
tags: ["cve-exploit", "privilege-escalation", "ttp-mapping"]
source: "https://thehackernews.com/2026/08/microsoft-patches-398-flaws-including.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** 활발히 악용 중인 Windows 커널 드라이버 권한상승 제로데이(CVE-2026-68820)로, 직접 운영 인프라는 없으나 CISA KEV 등재 가능성 높은 고위험 TTP 사례로 구조화 가치 있음
- **액션:** CVE-2026-68820을 STIX Vulnerability + Indicator 객체로 모델링하고 MITRE ATT&CK T1068(Exploitation for Privilege Escalation)에 매핑하여 파이프라인에 수집
