---
title: "Artifactory 취약점 체이닝으로 Rust 백도어 배포 공격 캠페인 분석"
date: 2026-09-11T23:58:13.841113+00:00
verdict: "학습"
tags: ["ttp-analysis", "backdoor-malware", "exploit-chaining"]
source: "https://www.bleepingcomputer.com/news/security/artifactory-flaws-chained-in-attacks-deploying-backdoor-malware/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** JFrog Artifactory 취약점 체이닝을 통한 백도어 배포 캠페인으로, TTP 분석 및 공격자 행위 패턴 연구에 해당
- **액션:** 공격 체인(인증 우회 → 권한 상승 → Rust 백도어 배포)을 MITRE ATT&CK TTP로 매핑하고 STIX Bundle로 구조화
