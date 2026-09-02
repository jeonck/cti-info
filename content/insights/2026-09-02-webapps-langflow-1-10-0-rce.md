---
title: "Langflow 1.10.0 원격 코드 실행 PoC 공개"
date: 2026-09-02T23:55:05.521976+00:00
verdict: "학습"
tags: ["rce", "exploit-db", "ttp-t1190"]
source: "https://www.exploit-db.com/exploits/52675"
source_name: "Exploit-DB"
status: "대기"
---
- **근거:** Langflow RCE PoC 공개 — CTI 파이프라인에서 직접 사용하는 스택은 아니나, 신규 익스플로잇 코드 공개로 CVE/익스플로잇 동향 관심 분야에 해당
- **액션:** Exploit-DB 52675 PoC 분석 후 Langflow CVE 번호 확인, STIX Vulnerability 객체로 정규화 및 관련 TTP(T1190 Exploit Public-Facing Application) 매핑
