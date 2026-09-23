---
title: "F5 BIG-IP APM 장비 대상 Linux 루트킷 배포 캠페인 — 파일리스 웹셸 기법 분석"
date: 2026-09-08T23:55:56.108437+00:00
verdict: "학습"
tags: ["rootkit", "fileless-attack", "ttp-analysis"]
source: "https://www.bleepingcomputer.com/news/security/hackers-breach-f5-big-ip-apm-devices-to-deploy-linux-rootkit/"
source_name: "BleepingComputer"
status: "완료"
---
- **근거:** F5 BIG-IP APM 대상 Linux 루트킷 캠페인은 직접 운영 인프라는 없으나, 공격 기법(메모리 내 파일리스 웹셸, PHP 인터셉션) 분석이 TTP·악성코드 행위 패턴 연구에 해당
- **액션:** 해당 루트킷의 TTP를 MITRE ATT&CK 매핑(T1014 Rootkit, T1505.003 Web Shell, T1027.011 Fileless Storage)으로 정리하고 STIX Malware/Attack-Pattern 객체로 초안 작성
