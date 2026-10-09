---
title: "UAT-11985: AI 기반 이벤트 루어 활용 실시간 Google AitM 피싱 캠페인"
date: 2026-10-09T01:49:44.556170+00:00
verdict: "학습"
tags: ["apt-campaign", "aitm-phishing", "ttp-analysis"]
source: "https://blog.talosintelligence.com/uat-11985/"
source_name: "Talos Intelligence"
status: "대기"
---
- **근거:** 대만 연구기관 대상 APT 스피어피싱 캠페인 분석 리포트로, AI 보조 루어·AitM 기법 등 MITRE ATT&CK 매핑 가능한 신규 TTP 포함
- **액션:** Talos 리포트에서 UAT-11985의 TTP를 추출해 STIX 2.1 Campaign/TTP 객체로 모델링하고 MITRE ATT&CK 기법(T1566, AitM 관련)과 관계 엣지 추가
