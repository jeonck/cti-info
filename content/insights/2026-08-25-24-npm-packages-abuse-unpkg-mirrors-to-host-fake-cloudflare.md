---
title: "npm 패키지 24개, unpkg CDN 악용해 가짜 Cloudflare CAPTCHA 피싱 인프라로 사용"
date: 2026-08-25T22:33:22.661858+00:00
verdict: "학습"
tags: ["clickfix-ttp", "npm-abuse", "phishing-infrastructure"]
source: "https://thehackernews.com/2026/08/24-npm-packages-abuse-unpkg-mirrors-to.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** npm/unpkg를 피싱 인프라로 악용하는 ClickFix 캠페인 TTP — 합법 CDN을 C2/호스팅 대용으로 쓰는 공격 패턴으로 ATT&CK 매핑 및 위협행위자 캠페인 분석 관심 분야에 해당
- **액션:** MITRE ATT&CK T1583.001(인프라 획득: 도메인)·T1608.001(스테이징: 악성 링크) 관점에서 npm/unpkg 악용 TTP를 STIX Campaign 오브젝트로 모델링하고 ClickFix 패턴과 연결
