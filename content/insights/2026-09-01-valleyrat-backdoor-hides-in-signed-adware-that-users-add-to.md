---
title: "Silver Fox, 서명된 애드웨어로 위장한 ValleyRAT 백도어 배포 캠페인"
date: 2026-09-01T01:05:27.305982+00:00
verdict: "학습"
tags: ["threat-actor", "malware-ttp", "stix-modeling"]
source: "https://thehackernews.com/2026/08/valleyrat-backdoor-hides-in-signed.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Silver Fox 위협 행위자의 ValleyRAT 백도어 캠페인 — 서명된 애드웨어를 위장 벡터로 사용하는 TTP 분석 리포트로, CTI 온톨로지의 위협 행위자·악성코드 노드 모델링에 활용 가능
- **액션:** Silver Fox → ValleyRAT 관계를 STIX Bundle로 정의하고, T1036.001(Masquerading: Invalid Code Signature 역용 변형)·T1562.001(AV 제외 목록 악용) ATT&CK 기법과 매핑 후 지식그래프에 ingestion
