---
title: "Kaltura mwEmbed 미패치 취약점: 원격 파일 읽기 및 코드 실행 가능"
date: 2026-08-27T03:01:01.000790+00:00
verdict: "학습"
tags: ["cve", "deserialization", "ttp-mapping"]
source: "https://thehackernews.com/2026/08/unpatched-kaltura-mwembed-flaws-could.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 CVE(익스플로잇 미확인)로 CVE/취약점 관심 분야에 해당하며, unsafe deserialization 기반 RCE·파일 읽기 취약점은 TTP 분석 자료로 활용 가능
- **액션:** CVE-2026-19913/19912를 STIX Vulnerability 객체로 모델링하고, T1059(Command Execution) 및 T1083(File Discovery) ATT&CK 기법과 관계 매핑 추가
