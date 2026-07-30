---
title: "SSH 봇의 하드웨어 정찰 후 마이너 배포 TTP 분석"
date: 2026-07-30T23:11:01.083639+00:00
verdict: "학습"
tags: ["ttp-analysis", "cryptomining", "ssh-botnet"]
source: "https://isc.sans.edu/diary/rss/33198"
source_name: "SANS Internet Storm Center"
status: "대기"
---
- **근거:** SSH 봇이 하드웨어 정보를 수집 후 마이너를 배포하는 TTP 분석 사례로, 공격 행위 패턴(정찰→페이로드 배포) 연구에 해당
- **액션:** 해당 SSH 봇의 정찰·배포 행위를 MITRE ATT&CK T1592(정보 수집), T1496(리소스 탈취)에 매핑하고 STIX Bundle로 구조화 초안 작성
