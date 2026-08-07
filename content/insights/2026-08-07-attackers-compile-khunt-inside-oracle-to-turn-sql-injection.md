---
title: "공격자, Oracle DB 내부에서 Java 코드 컴파일해 SQL 인젝션을 Windows SYSTEM 권한으로 전환"
date: 2026-08-07T01:30:55.590713+00:00
verdict: "학습"
tags: ["ttp-analysis", "sql-injection", "privilege-escalation"]
source: "https://thehackernews.com/2026/08/attackers-compile-khunt-inside-oracle.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** SQL 인젝션→DB 내부 코드 실행→SYSTEM 권한 상승으로 이어지는 신규 공격 기법(TTP)으로, ATT&CK 매핑 및 공격 체인 분석 관점에서 연구 가치 있음
- **액션:** khunt 툴킷의 공격 체인을 MITRE ATT&CK TTP로 매핑(T1190 SQL Injection → T1059 Java 실행 → T1068 권한 상승)하고 STIX Course of Action 객체로 구조화
