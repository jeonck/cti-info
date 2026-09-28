---
title: "Citrix NetScaler ADC/Gateway RCE 제로데이 2건 야생 익스플로잇 확인"
date: 2026-09-28T00:24:17.611215+00:00
verdict: "학습"
tags: ["zero-day-rce", "cisa-kev-candidate", "mitre-attack-ttp"]
source: "https://thehackernews.com/2026/09/warning-two-unpatched-citrix-netscaler.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Citrix NetScaler는 내 개인 연구 인프라 스택에 없으나, 활발히 익스플로잇 중인 Critical RCE 제로데이로서 CISA KEV 등재 및 TTP 분석 자료로 활용 가능한 위협 인텔리전스 사례
- **액션:** CVE 번호 확인 후 STIX 2.1 Vulnerability/Indicator 객체로 모델링하고, watchTowr 분석 리포트를 기반으로 MITRE ATT&CK T1190(Exploit Public-Facing Application) 매핑 여부 검토
