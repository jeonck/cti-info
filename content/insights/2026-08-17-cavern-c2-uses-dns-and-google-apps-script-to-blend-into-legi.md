---
title: "이란 APT의 Cavern C2 프레임워크: DNS·Google Apps Script를 활용한 정상 트래픽 위장 기법 분석"
date: 2026-08-17T22:28:11.755941+00:00
verdict: "학습"
tags: ["apt-c2", "dns-tunneling", "ttp-mapping"]
source: "https://thehackernews.com/2026/08/cavern-c2-uses-dns-and-google-apps.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** 이란 국가 연계 위협 행위자의 신규 C2 프레임워크 TTP(DNS 터널링, Google Apps Script 악용) 분석으로 APT 캠페인 동향 파악에 해당
- **액션:** Cavern C2의 DNS/GAS 기반 C2 통신 패턴을 MITRE ATT&CK T1071(Application Layer Protocol), T1568(Dynamic Resolution)에 매핑하고 STIX Campaign/TTP 객체로 모델링 초안 작성
