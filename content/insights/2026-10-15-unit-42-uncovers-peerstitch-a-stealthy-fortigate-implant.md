---
title: "Unit 42, FortiGate 대상 메모리 상주 임플란트 PEERSTITCH 분석 (CVE-2024-47575 악용)"
date: 2026-10-15T00:20:56.708433+00:00
verdict: "학습"
tags: ["ttp-analysis", "apt-campaign", "malware-behavior"]
source: "https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/"
source_name: "Unit42 (Palo Alto)"
status: "대기"
---
- **근거:** APT 캠페인 분석 리포트로, CVE-2024-47575 악용 및 메모리 상주 임플란트(PEERSTITCH)의 행위 패턴이 TTP 구조화·ATT&CK 매핑 연구에 해당
- **액션:** PEERSTITCH의 실행 체인(FortiManager 초기 접근 → 메모리 상주 ARM64 임플란트 배포)을 MITRE ATT&CK TTP로 매핑하고 STIX 2.1 Campaign/Malware 오브젝트로 모델링
