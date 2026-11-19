---
title: "공개 블록체인을 C2 dead-drop으로 활용하는 악성코드 방어의 어려움"
date: 2026-11-19T02:59:00.953572+00:00
verdict: "학습"
tags: ["c2-infrastructure", "ttp-analysis", "blockchain-dead-drop"]
source: "https://blog.talosintelligence.com/the-challenge-of-defending-against-bulletproof-dead-drops-on-public-blockchains/"
source_name: "Talos Intelligence"
status: "대기"
---
- **근거:** 블록체인 기반 C2 인프라 기법은 MITRE ATT&CK T1102(Web Service) 계열 TTP로 분류 가능하며, 악성코드 행위 패턴 분석 및 CTI 구조화 연구에 직접 활용 가능
- **액션:** MITRE ATT&CK T1102/T1568(Dynamic Resolution) 매핑 후, 블록체인 dead-drop resolver 기법을 STIX Course of Action 및 Indicator 오브젝트로 모델링 초안 작성
