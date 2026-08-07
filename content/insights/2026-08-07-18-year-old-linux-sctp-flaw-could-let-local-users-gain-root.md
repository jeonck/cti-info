---
title: "18년 된 Linux SCTP Use-After-Free, 로컬 루트 탈취·컨테이너 탈출 PoC 공개"
date: 2026-08-07T22:39:48.624149+00:00
verdict: "즉시조치"
tags: ["linux-kernel", "privilege-escalation", "container-escape"]
source: "https://thehackernews.com/2026/08/18-year-old-linux-sctp-flaw-could-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Tencent 연구진이 컨테이너 탈출까지 시연한 PoC 공개 직후의 고위험 Linux 커널 취약점으로, CTI 구조화 관점에서 즉시 수집·분석 대상
- **액션:** CVE 번호 확인 후 STIX Vulnerability 객체로 정규화하고, MITRE ATT&CK T1611(Container Escape) 및 T1068(Privilege Escalation) TTP와 매핑하여 파이프라인에 등록
