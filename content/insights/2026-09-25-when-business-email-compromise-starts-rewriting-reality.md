---
title: "Zimbra 50개 이상 취약점 악용 BEC 캠페인 — 인증 없는 RCE·저장형 XSS로 이메일 환경 재구성"
date: 2026-09-25T00:21:06.217708+00:00
verdict: "학습"
tags: ["bec-attack", "zimbra-cve", "cisa-kev"]
source: "https://www.rapid7.com/blog/post/ve-business-email-compromise-rewriting-reality-zimbra-cve"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** Zimbra BEC 캠페인 분석 리포트로, CISA KEV 등재 CVE(CVE-2024-45519, CVE-2025-27915) 및 공격자 TTP가 CTI 관심 분야(APT 캠페인 분석, 취약점 동향)에 해당
- **액션:** CVE-2024-45519·CVE-2025-27915를 STIX 2.1 Vulnerability/Indicator 객체로 정규화하고, BEC 관련 TTP(T1566 Phishing, T1078 Valid Accounts, T1114 Email Collection)를 MITRE ATT&CK에 매핑해 지식그래프에 추가
