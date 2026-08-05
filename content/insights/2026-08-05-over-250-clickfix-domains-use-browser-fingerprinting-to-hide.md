---
title: "250개 이상 도메인 활용 ClickFix 캠페인, 브라우저 핑거프린팅으로 macOS 악성코드 전달"
date: 2026-08-05T23:03:18.805981+00:00
verdict: "학습"
tags: ["clickfix", "browser-fingerprinting", "ttp-analysis"]
source: "https://thehackernews.com/2026/08/over-250-clickfix-domains-use-browser.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** ClickFix 캠페인의 브라우저 핑거프린팅 기반 타겟팅 기법은 TTP 분석 및 위협 행위자 인프라 패턴 연구에 해당
- **액션:** 250개 이상의 ClickFix 프론트엔드 도메인 IOC를 STIX Domain-Name/Infrastructure 객체로 정규화하고, 핑거프린팅→페이로드 전달 체인을 ATT&CK T1592(Gather Victim Host Information) 및 T1204(User Execution)에 매핑
