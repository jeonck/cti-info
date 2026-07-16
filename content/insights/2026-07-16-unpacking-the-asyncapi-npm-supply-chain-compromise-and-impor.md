---
title: "AsyncAPI npm 공급망 침해: import-time 페이로드 전달 전술 분석"
date: 2026-07-16T22:59:51.636392+00:00
verdict: "학습"
tags: ["supply-chain-attack", "npm-threat", "ttp-analysis"]
source: "https://www.microsoft.com/en-us/security/blog/2026/07/15/unpacking-asyncapi-npm-supply-chain-compromise-import-time-payload-delivery/"
source_name: "Microsoft Security Blog"
status: "대기"
---
- **근거:** npm 공급망 공격 사례는 직접 운영 인프라는 없으나 TTP 분석·공격 체인 구조화 관점에서 CTI 연구 관심 분야에 해당
- **액션:** AsyncAPI 공급망 공격의 전술 체인(CI/CD 악용 → import-time payload)을 MITRE ATT&CK(T1195.001, T1059 등)로 매핑해 STIX Bundle 초안 작성
