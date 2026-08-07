---
title: "JetBrains TeamCity 미인증 RCE(CVE-2026-63077), CISA KEV 등재 및 PoC 공개"
date: 2026-08-07T22:39:48.624149+00:00
verdict: "학습"
tags: ["cve-rce", "cisa-kev", "deserialization"]
source: "https://www.rapid7.com/blog/post/ra-unauthenticated-rce-in-jetbrains-teamcity-cve-2026-63077"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** 내 인프라에 TeamCity를 운영하지 않으나, CISA KEV 등재 및 PoC 공개된 인증 불필요 RCE로 위협 인텔리전스 구조화·TTP 분석 관심 분야에 해당
- **액션:** CVE-2026-63077의 익스플로잇 체인(XStream 역직렬화 → 허용 목록 우회 → RCE)을 MITRE ATT&CK T1059(Command Execution) 및 T1190(Exploit Public-Facing Application)으로 매핑해 STIX Course of Action 객체 초안 작성
