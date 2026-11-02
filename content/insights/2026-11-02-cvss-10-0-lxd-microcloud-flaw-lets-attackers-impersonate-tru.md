---
title: "CVSS 10.0 LXD/MicroCloud 신뢰 클라이언트 사칭 취약점"
date: 2026-11-02T01:21:15.764487+00:00
verdict: "학습"
tags: ["cve-critical", "authentication-bypass", "stix-modeling"]
source: "https://thehackernews.com/2026/11/critical-lxd-and-microcloud-flaw-cvss.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** LXD/MicroCloud 인프라를 운영하지 않으나, CVSS 10.0 취약점으로 익스플로잇 메커니즘(인증 우회·공개 인증서 악용)이 CTI TTP 분석 및 CVE 구조화 연구에 해당
- **액션:** CVE 식별자 확인 후 STIX Vulnerability 객체로 모델링하고, MITRE ATT&CK T1550(Use Alternate Authentication Material) 또는 T1078에 매핑하여 온톨로지에 추가
