---
title: "OpenPLC Runtime 레이스 컨디션으로 비인증 관리자 계정 생성 가능 (CVE-2026-126088)"
date: 2026-11-20T02:53:16.905409+00:00
verdict: "학습"
tags: ["ics-ot", "race-condition", "cve-modeling"]
source: "https://www.cisa.gov/news-events/ics-advisories/icsa-26-323-01"
source_name: "CISA Cybersecurity Advisories"
status: "대기"
---
- **근거:** ICS/OT 환경의 PLC 런타임 취약점으로, 직접 운영 인프라는 없으나 CVE 구조화·CISA KEV 추적 관심 분야에 해당
- **액션:** CVE-2026-126088을 STIX Vulnerability 오브젝트로 모델링하고 CWE-362(Race Condition), CVSS 4.0 점수, ICS 섹터 컨텍스트를 포함해 지식그래프에 추가
