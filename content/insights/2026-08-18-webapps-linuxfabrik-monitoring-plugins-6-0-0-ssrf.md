---
title: "Linuxfabrik 모니터링 플러그인 6.0.0 SSRF 취약점 — Exploit-DB PoC 공개"
date: 2026-08-18T22:27:10.065346+00:00
verdict: "학습"
tags: ["ssrf", "exploit-db", "ttp-mapping"]
source: "https://www.exploit-db.com/exploits/52653"
source_name: "Exploit-DB"
status: "대기"
---
- **근거:** Exploit-DB에 SSRF PoC가 공개된 케이스로, CTI 관심 분야인 익스플로잇 공개 여부 추적 및 SSRF TTP(T1090/T1602 계열) 분석 자료로 활용 가능
- **액션:** Exploit-DB 52653 PoC를 검토해 SSRF 공격 패턴을 MITRE ATT&CK T1090(Proxy) 또는 관련 기법으로 매핑하고 STIX Course of Action 오브젝트 초안 작성
