---
title: "Kubernetes YAML 파일 하나로 GCP 조직 전체 장악 가능한 권한 상승 기법"
date: 2026-09-24T00:18:42.741390+00:00
verdict: "학습"
tags: ["privilege-escalation", "cloud-ttp", "kubernetes"]
source: "https://www.bleepingcomputer.com/news/security/how-one-kubernetes-yaml-can-hand-over-a-gcp-organization/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** Kubernetes/GCP 환경 직접 운영 없으나, 클라우드 환경 권한 상승 TTP(confused deputy, misconfiguration 기반 privilege escalation)는 MITRE ATT&CK 매핑 및 위협 시나리오 분석 관심 분야에 해당
- **액션:** 해당 TTP를 ATT&CK T1548(Abuse Elevation Control Mechanism) 또는 T1078(Valid Accounts) 계열로 매핑하고, GCP Config Connector 관련 STIX Course of Action 객체 초안 작성
