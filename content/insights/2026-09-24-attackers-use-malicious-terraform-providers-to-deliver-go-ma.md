---
title: "HashiCorp 레지스트리를 배포 벡터로 악용한 Go 기반 악성코드 공급망 공격"
date: 2026-09-24T00:18:42.741390+00:00
verdict: "학습"
tags: ["supply-chain-attack", "malware-ttp", "go-ecosystem"]
source: "https://thehackernews.com/2026/09/attackers-use-malicious-terraform.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 공급망 공격을 통한 악성코드 배포 기법(TTP)으로, CTI 구조화 및 위협 행위자 동향 관심 분야에 해당
- **액션:** 해당 캠페인의 IOC(악성 모듈 해시, C2 주소)와 MITRE ATT&CK 매핑(T1195.001 공급망 타협)을 STIX 2.1 Bundle로 모델링하고 OpenCTI에 수동 인제스트 테스트
