---
title: "BPFDoor 신규 변종 및 AVERAT 리눅스 임플란트 캠페인 TTP 분석"
date: 2026-10-03T01:01:08.256745+00:00
verdict: "학습"
tags: ["bpfdoor-variant", "linux-implant-ttp", "apt-campaign-analysis"]
source: "https://www.rapid7.com/blog/post/tr-smtp-is-the-key-bpfdoor-averat-hitting-the-network-edge"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** BPFDoor·AVERAT 신규 변종의 TTP(드로퍼 체인, BPF 필터 기반 백도어, 지역화 위장 기법) 분석 리포트로, MITRE ATT&CK 매핑 및 위협 행위자 캠페인 구조화 연구에 직접 활용 가능
- **액션:** 리포트의 드로퍼→watchdog 체인(T1027/T1036)·BPF 소켓 필터(T1205.002) TTPs를 STIX 2.1 Attack Pattern·Malware 오브젝트로 모델링하고 기존 BPFDoor 캠페인 노드와 관계 엣지 연결
