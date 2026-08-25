---
title: "IP 주소를 호스트명으로 난독화하는 SSRF 우회 기법 분석"
date: 2026-08-25T22:33:22.661858+00:00
verdict: "학습"
tags: ["ssrf", "ip-obfuscation", "ttp-analysis"]
source: "https://isc.sans.edu/diary/rss/33280"
source_name: "SANS Internet Storm Center"
status: "대기"
---
- **근거:** SSRF 공격 기법(TTP) 및 IP 난독화 우회 패턴은 ATT&CK 매핑·위협 행위자 분석 파이프라인에 유용한 기술 맥락
- **액션:** SSRF TTP를 MITRE ATT&CK T1090/T1071 등과 매핑하고, 클라우드 메타데이터 서비스 대상 IOC(169.254.169.254 우회 변형 패턴) 를 STIX Indicator 객체로 모델링 검토
