---
title: "MikroTik 라우터 비인증 완전 장악 허용하는 CVE 체인 'MikroTrick' 공개"
date: 2026-09-24T00:18:42.741390+00:00
verdict: "학습"
tags: ["chained-exploit", "ssh-vulnerability", "ttp-analysis"]
source: "https://thehackernews.com/2026/09/mikrotrick-chain-let-attackers-take.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** MikroTik 인프라 미운영으로 즉시 패치 대상 없으나, 두 CVE를 체인으로 연결한 비인증 RCE 사례는 CVE·익스플로잇 동향 및 TTP 분석 관심 분야에 해당
- **액션:** CVE-2026-67279(SSH 상태머신 결함)·CVE-2026-86060(인수 인젝션) 두 노드를 STIX Vulnerability·Attack Pattern 객체로 모델링하고 체인 관계(uses/exploits)를 표현하는 샘플 번들 작성
