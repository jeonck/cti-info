---
title: "keyv/cacheable npm 웜: 토큰 폐기가 공격 페이로드를 활성화하는 역발상 공급망 공격 분석"
date: 2026-08-07T01:30:55.590713+00:00
verdict: "학습"
tags: ["supply-chain-attack", "npm-worm", "ttp-analysis"]
source: "https://isc.sans.edu/diary/rss/33218"
source_name: "SANS Internet Storm Center"
status: "대기"
---
- **근거:** npm 공급망 웜의 신규 TTP — 토큰 폐기가 오히려 페이로드를 활성화하는 역발상 트리거 메커니즘으로, MITRE ATT&CK T1195(공급망 침해) 매핑 및 인시던트 대응 패턴 분석에 직접 활용 가능
- **액션:** keyv/cacheable 웜 사례를 STIX Course of Action 객체로 모델링하고, '토큰 폐기 → 페이로드 트리거' 인과 관계를 kill chain 단계별로 정리해 TTP 온톨로지에 추가
