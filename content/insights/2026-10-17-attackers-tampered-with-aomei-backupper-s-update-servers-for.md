---
title: "AOMEI Backupper 업데이트 서버 단기 변조를 통한 백도어 배포 공급망 공격 캠페인"
date: 2026-10-17T00:12:48.020439+00:00
verdict: "학습"
tags: ["supply-chain-attack", "ttp-analysis", "apt-campaign"]
source: "https://thehackernews.com/2026/10/attackers-tampered-with-aomei.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** 업데이트 서버 단기 변조(5~10분 윈도우) 방식의 소프트웨어 공급망 침해 캠페인으로, MITRE ATT&CK T1195(Supply Chain Compromise)/T1072 매핑 및 위협 행위자 TTP 분석 관심 분야에 해당
- **액션:** MITRE ATT&CK T1195.002(Compromise Software Supply Chain) 서브테크닉으로 이 캠페인을 STIX Course of Action/Attack Pattern 객체로 모델링하고, 단기 타임윈도우 변조 특성을 kill-chain 단계별 속성으로 정규화
