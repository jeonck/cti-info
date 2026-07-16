---
title: "Shark 로봇청소기 미패치 취약점 — 인증서 탈취로 타 사용자 기기 원격 제어 가능"
date: 2026-07-16T22:59:51.636392+00:00
verdict: "학습"
tags: ["iot-vulnerability", "exploit-poc", "ttp-analysis"]
source: "https://thehackernews.com/2026/07/unpatched-shark-vacuum-flaw-could-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** IoT 기기의 인증서 탈취를 통한 원격 제어 취약점 — CVE/익스플로잇 공개 사례로 TTP 분석 및 IOC 구조화 관점에서 참고 가치 있음
- **액션:** PoC 분석 후 IoT 공격 체인(인증서 추출→API 남용→원격 제어)을 MITRE ATT&CK T1552.004(Private Keys) 및 T1609(Container Administration Command) 등에 매핑하여 CTI 데이터 모델에 추가
