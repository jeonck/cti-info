---
title: "Cloudflare Workers Spectre 공격으로 동일 노드 JWT 초당 12비트 유출"
date: 2026-08-19T22:27:32.532511+00:00
verdict: "학습"
tags: ["side-channel-attack", "ttp-analysis", "credential-access"]
source: "https://thehackernews.com/2026/08/cloudflare-workers-spectre-attack-leaks.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** Spectre 계열 사이드채널 공격을 통한 크로스-테넌트 정보 유출 기법 — TTP 분석 및 공격 시나리오 구조화 관점에서 유의미한 사례
- **액션:** 해당 연구 리포트를 읽고 MITRE ATT&CK T1212(Exploitation for Credential Access) 및 T1056 계열과 매핑해 STIX Course of Action 객체 초안 작성
