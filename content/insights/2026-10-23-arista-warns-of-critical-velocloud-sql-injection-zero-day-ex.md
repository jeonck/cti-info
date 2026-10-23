---
title: "Arista VeloCloud Orchestrator 제로데이 SQL 인젝션 — 실제 공격 활용 중"
date: 2026-10-23T00:27:49.578517+00:00
verdict: "학습"
tags: ["active-exploitation", "sql-injection", "sd-wan-vulnerability"]
source: "https://thehackernews.com/2026/10/arista-warns-of-critical-velocloud-sql.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** VeloCloud VCO 인프라를 운영하지 않아 직접 패치 대상은 아니나, 활발히 익스플로잇 중인 Critical 제로데이로 CISA KEV 등재 가능성이 높고, SQL 인젝션 → 권한 상승 TTP 패턴이 CTI 구조화 연구 자료로 유의미함
- **액션:** CVE 번호 확인 후 STIX Course of Action + Vulnerability 객체로 모델링하고, MITRE ATT&CK T1190(Exploit Public-Facing Application) 매핑 추가; CISA KEV 등재 여부 주 중 재확인
