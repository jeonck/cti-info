---
title: "LiteLLM 릴리즈 파이프라인 침해 — PyPI·Docker Hub에 자격증명 탈취 악성 패키지 배포"
date: 2026-10-23T00:27:49.578517+00:00
verdict: "학습"
tags: ["supply-chain-attack", "malware-analysis", "ttp-mapping"]
source: "https://thehackernews.com/2026/10/litellm-suspects-github-token-leak-in.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** AI 게이트웨이 릴리즈 파이프라인 공급망 공격 — 자격증명 탈취형 악성코드 삽입 TTP 및 위협행위자 캠페인 분석 사례에 해당
- **액션:** 공격 흐름(GitHub 토큰 유출 → PyPI/Docker Hub 악성 패키지 배포 → 백도어)을 MITRE ATT&CK T1195.001(공급망 타협)·T1528(토큰 탈취) 매핑하여 STIX Campaign 오브젝트로 구조화
