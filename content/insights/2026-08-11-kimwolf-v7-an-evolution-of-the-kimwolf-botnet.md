---
title: "Kimwolf v7 봇넷: Ethereum ENS C2 및 Tor 백업 라우팅을 활용한 Android IoT 공격"
date: 2026-08-11T22:46:54.111389+00:00
verdict: "학습"
tags: ["botnet-ttp", "c2-infrastructure", "malware-analysis"]
source: "https://unit42.paloaltonetworks.com/kimwolf-v7-botnet-malware/"
source_name: "Unit42 (Palo Alto)"
status: "완료"
---
- **근거:** Kimwolf v7 봇넷의 악성코드 구조·행위 패턴(HTTP/2 DDoS 핑거프린팅, Ethereum ENS C2 리졸루션, Tor 백업 라우팅) 분석은 TTP·악성코드 분석 관심 분야에 해당
- **액션:** Kimwolf v7 리포트에서 ENS 기반 C2 리졸루션 TTP를 MITRE ATT&CK T1568(Dynamic Resolution) 하위 기법으로 매핑하고 STIX Course of Action 객체로 모델링
