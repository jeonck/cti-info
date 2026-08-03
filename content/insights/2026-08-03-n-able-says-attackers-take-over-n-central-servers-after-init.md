---
title: "N-able N-central 인증 우회(CVE-2026-18577) 실제 악용 — 첫 패치 불완전, 공격자 서버 장악 확인"
date: 2026-08-03T23:04:48.142797+00:00
verdict: "즉시조치"
tags: ["cve-2026-18577", "rmm-exploitation", "auth-bypass"]
source: "https://thehackernews.com/2026/08/n-able-says-attackers-take-over-n.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 활발히 익스플로잇 중인 RMM 플랫폼 인증 우회(CVE-2026-18577) — 공격자가 N-central 서버를 탈취해 관리 대상 고객 시스템까지 도달한 공급망 유형 캠페인으로, CTI 구조화·시나리오 분석 관점에서 즉시 데이터 수집 대상
- **액션:** CVE-2026-18577을 STIX Vulnerability 객체로 생성하고, auth-bypass → RMM 서버 장악 → 관리 고객 침투 경로를 Attack Pattern(T1190 Exploit Public-Facing Application + T1021 Remote Services)으로 매핑해 파이프라인에 인제스트
