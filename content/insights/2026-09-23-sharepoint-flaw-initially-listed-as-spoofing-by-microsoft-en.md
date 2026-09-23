---
title: "SharePoint CVE-2026-65660: Microsoft의 스푸핑 오분류, 실제론 인증된 RCE"
date: 2026-09-23T00:08:22.582821+00:00
verdict: "학습"
tags: ["cve-rce", "cvss-misclassification", "sharepoint"]
source: "https://thehackernews.com/2026/09/sharepoint-flaw-initially-listed-as.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** SharePoint를 운영하지 않아 직접 패치 대상은 아니나, CVSS 오분류(스푸핑→인증된 RCE) 사례로 CVE 심각도 평가 및 취약점 구조화 연구에 해당
- **액션:** CVE-2026-65660 기술 분석 리포트(Viettel Cyber Security)를 읽고 STIX Vulnerability 객체로 정규화 — severity_reclassification 커스텀 속성 추가 검토
