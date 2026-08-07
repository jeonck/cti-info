---
title: "npm 악성 패키지 800개 캠페인 — 크로스플랫폼 RAT·인포스틸러 배포"
date: 2026-08-07T22:39:48.624149+00:00
verdict: "학습"
tags: ["supply-chain-attack", "malware-ttp", "ioc-collection"]
source: "https://thehackernews.com/2026/08/nearly-800-malicious-npm-packages.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** npm 공급망을 통한 멀웨어 캠페인으로, TTP(타이포스쿼팅, AI 생성 패키지명) 및 멀웨어 행위 패턴이 CTI 구조화 연구 관심 분야에 해당
- **액션:** 보고서의 악성 패키지 목록·IOC(패키지명, 해시, C2)를 수집해 STIX 2.1 Malware/Campaign 객체로 모델링하고 공급망 공격 TTP(T1195.001)와 매핑
