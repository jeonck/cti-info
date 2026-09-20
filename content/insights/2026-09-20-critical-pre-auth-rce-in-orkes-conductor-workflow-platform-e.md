---
title: "Orkes Conductor 인증 전 RCE(CVE-2026-58138) 실환경 악용 확인 — CVSS 9.8"
date: 2026-09-20T23:57:53.938251+00:00
verdict: "즉시조치"
tags: ["critical-cve", "pre-auth-rce", "actively-exploited"]
source: "https://thehackernews.com/2026/09/critical-pre-auth-rce-in-orkes.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 9.8의 인증 전 RCE가 실환경에서 활발히 익스플로잇 중인 Critical CVE로, CTI 파이프라인에서 우선 수집·구조화 대상
- **액션:** CVE-2026-58138을 STIX 2.1 Vulnerability 객체로 정규화하고, Fortinet 보고서 기반 TTP(초기접근→코드실행)를 ATT&CK T1190(공개 취약점 익스플로잇)에 매핑해 지식그래프에 추가
