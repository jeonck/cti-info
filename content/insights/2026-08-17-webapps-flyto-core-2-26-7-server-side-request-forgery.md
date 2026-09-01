---
title: "flyto_core 2.26.7 SSRF 취약점 PoC Exploit-DB 공개"
date: 2026-08-17T22:28:11.755941+00:00
verdict: "학습"
tags: ["ssrf", "exploit-db", "ttp-mapping"]
source: "https://www.exploit-db.com/exploits/52651"
source_name: "Exploit-DB"
status: "완료"
---
- **근거:** Exploit-DB에 공개된 SSRF PoC로, 익스플로잇 공개 여부 추적 관심 분야에 해당하며 SSRF는 MITRE ATT&CK TTP(T1090 계열) 분석에 참조 가능
- **액션:** flyto_core SSRF 익스플로잇 코드를 분석해 MITRE ATT&CK T1602/Server-Side Request Forgery 패턴으로 매핑하고 CTI 파이프라인의 TTP 샘플로 수집
