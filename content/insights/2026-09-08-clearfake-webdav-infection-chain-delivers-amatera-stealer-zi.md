---
title: "ClearFake WebDAV 감염 체인: Amatera 스틸러·ZigCryptoStealer·NetSupport Manager 배포 캠페인 분석"
date: 2026-09-08T23:55:56.108437+00:00
verdict: "학습"
tags: ["clearfake", "stealer-malware", "ttp-analysis"]
source: "https://blog.talosintelligence.com/clearfake-webdav-infection-chain/"
source_name: "Talos Intelligence"
status: "완료"
---
- **근거:** ClearFake 캠페인의 감염 체인(WebDAV), 스틸러 악성코드(Amatera, ZigCryptoStealer), RAT(NetSupport Manager) 등 TTP 및 악성코드 행위 패턴 분석 자료로 MITRE ATT&CK 매핑 및 위협 행위자 동향 파악에 활용 가능
- **액션:** Talos 리포트에서 Amatera stealer·ZigCryptoStealer의 IOC(해시·C2·도메인) 추출 후 STIX 2.1 Malware·Indicator 객체로 정규화하고 ClearFake 캠페인 Intrusion Set에 연결
