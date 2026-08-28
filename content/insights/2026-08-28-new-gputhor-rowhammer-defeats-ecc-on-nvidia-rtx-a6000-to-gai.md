---
title: "GPUThor: ECC 우회 GPU Rowhammer로 NVIDIA RTX A6000 호스트 루트 탈취"
date: 2026-08-28T06:01:12.270545+00:00
verdict: "학습"
tags: ["rowhammer", "gpu-security", "privilege-escalation"]
source: "https://thehackernews.com/2026/08/gputhor-rowhammer-defeats-ecc-on-nvidia.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 운영 중인 인프라에 NVIDIA RTX A6000이 없어 즉시 패치 대상은 아니지만, GPU DRAM Rowhammer를 통한 권한 상승 신규 공격 기법(TTP)으로 CTI 관심 분야에 해당
- **액션:** GPUThor 논문 원문 확인 후 Rowhammer 기반 권한 상승 TTP를 MITRE ATT&CK T1068(Exploitation for Privilege Escalation)에 매핑해 CTI 지식그래프에 노드 추가 검토
