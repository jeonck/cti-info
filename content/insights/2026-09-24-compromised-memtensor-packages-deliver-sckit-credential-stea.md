---
title: "npm·PyPI MemTensor 패키지 공급망 침해 — Go 기반 sckit 자격증명 탈취 임플란트 배포"
date: 2026-09-24T00:18:42.741390+00:00
verdict: "학습"
tags: ["supply-chain-attack", "credential-stealer", "ttp-mapping"]
source: "https://thehackernews.com/2026/09/compromised-memtensor-packages-deliver.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** npm/PyPI 공급망 타협을 통한 자격증명 탈취 캠페인으로, MITRE ATT&CK T1195.001(소프트웨어 공급망 침해) TTP 분석 및 Go 기반 임플란트 행위 패턴이 CTI 구조화 연구 대상에 해당
- **액션:** sckit 임플란트를 STIX 2.1 Malware + Attack Pattern 객체로 모델링하고, T1195.001 및 T1555(자격증명 탈취) relationship 매핑 초안 작성
