---
title: "캘린더 초대 미끼와 실시간 프록시를 활용한 Google 세션 하이재킹 캠페인 분석"
date: 2026-11-13T02:28:54.605959+00:00
verdict: "학습"
tags: ["aitm-phishing", "session-hijacking", "ttp-mapping"]
source: "https://thehackernews.com/2026/11/calendar-invites-and-live-proxies.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Google 세션 하이재킹 캠페인의 TTP(캘린더 초대 미끼, 실시간 프록시 AiTM)가 MITRE ATT&CK 매핑 및 위협 행위자 캠페인 분석 연구 대상에 해당
- **액션:** 캠페인 TTPs(T1566 Phishing, T1557 AiTM, T1539 Web Session Cookie Theft)를 STIX 2.1 Campaign/Attack-Pattern 객체로 모델링하고 Operation CloudFire 관련 도메인 IOC를 수집해 지식그래프에 추가
