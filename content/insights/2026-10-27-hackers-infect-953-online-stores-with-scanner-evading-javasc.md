---
title: "953개 온라인 쇼핑몰 감염 — 탐지 우회 JavaScript 스키머 캠페인 분석"
date: 2026-10-27T01:17:17.810075+00:00
verdict: "학습"
tags: ["web-skimming", "magento-campaign", "ttp-analysis"]
source: "https://thehackernews.com/2026/10/hackers-infect-953-online-stores-with.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Magento 대상 스키머 캠페인으로 직접 방어할 인프라는 없으나, 지속적 공급망·웹스키밍 TTP 분석 사례로 ATT&CK 매핑(T1059.007 등) 및 위협행위자 캠페인 구조화 관심 분야에 해당
- **액션:** Sansec 리포트에서 공개된 IOC(도메인/JS 해시)와 TTP를 STIX 2.1 Indicator·Attack-Pattern 객체로 변환해 로컬 CTI 파이프라인에 수집 테스트
