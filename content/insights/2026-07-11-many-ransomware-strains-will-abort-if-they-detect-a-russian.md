---
title: "랜섬웨어의 러시아 키보드 레이아웃 감지 기반 실행 중단 패턴 (2021)"
date: 2026-07-11T22:53:29.112612+00:00
verdict: "학습"
tags: ["ransomware-ttp", "evasion-technique", "threat-actor-behavior"]
source: "https://krebsonsecurity.com/2021/05/try-this-one-weird-trick-russian-hackers-hate/"
source_name: "HN (ransomware)"
status: "대기"
---
- **근거:** 랜섬웨어 그룹의 운영 패턴(러시아어권 타겟 회피 로직)은 위협 행위자 TTP 분석 및 ATT&CK 매핑 관심 분야에 해당
- **액션:** 해당 회피 기법(keyboard layout 검사)을 MITRE ATT&CK T1614.001(System Location Discovery) 또는 Defense Evasion 카테고리로 매핑하고 STIX Malware 객체에 kill-switch 패턴으로 모델링 검토
