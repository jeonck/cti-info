---
title: "RefluXFS 9년 된 리눅스 커널 결함(CVE-2026-64600): RHEL 기본 설치에서 로컬 루트 권한 탈취"
date: 2026-07-23T23:00:45.696578+00:00
verdict: "학습"
tags: ["local-privilege-escalation", "linux-kernel", "cve-2026-64600"]
source: "https://thehackernews.com/2026/07/nine-year-old-refluxfs-linux-flaw-gives.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CTI 관심 분야인 신규 CVE·PoC 공개 항목이며, 운영 중인 RHEL/Linux 인프라가 없어 즉시 패치 대상은 아님
- **액션:** CVE-2026-64600을 STIX Vulnerability 객체로 모델링하고 Qualys PoC 기반 익스플로잇 조건(XFS 마운트, 로컬 접근)을 attack-pattern으로 연결해 스키마 적용 사례로 기록
