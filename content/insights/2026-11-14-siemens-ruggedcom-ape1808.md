---
title: "Siemens RUGGEDCOM APE1808 PAN-OS PHP UAF 취약점 — CVSS 9.8 원격코드실행"
date: 2026-11-14T02:02:16.957889+00:00
verdict: "학습"
tags: ["critical-cve", "ics-ot", "rce"]
source: "https://www.cisa.gov/news-events/ics-advisories/icsa-26-316-05"
source_name: "CISA Cybersecurity Advisories"
status: "대기"
---
- **근거:** 운영 중인 Siemens/PAN-OS 인프라 없음 — 단, CVSS 9.8 PHP Use-After-Free → RCE 취약점(ICS/OT 환경)으로 TTP 및 취약점 구조화 연구 대상
- **액션:** CVE-2026-109618 PHP longjmp OOM 조건 → UAF → RCE 체인을 STIX CourseOfAction·Vulnerability 객체로 모델링하고, RUGGEDCOM APE1808(ICS) + PAN-OS(IT) 교차점을 ATT&CK ICS 매트릭스에 매핑
