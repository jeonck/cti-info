---
title: "HollowByte: 11바이트 페이로드로 OpenSSL 서버 메모리를 마비시키는 DoS 취약점"
date: 2026-07-17T22:53:18.508334+00:00
verdict: "학습"
tags: ["openssl", "denial-of-service", "cve"]
source: "https://www.bleepingcomputer.com/news/security/hollowbyte-ddos-flaw-bloats-openssl-server-memory-with-11-byte-payload/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** 신규 공개 OpenSSL DoS 취약점(CVE)으로, 운영 인프라는 없으나 CVE 심각도·익스플로잇 특성 분석 및 STIX 취약점 오브젝트 모델링 사례로 활용 가능
- **액션:** HollowByte CVE 번호 확인 후 STIX 2.1 Vulnerability 오브젝트로 정규화하고, 11바이트 트리거 메커니즘을 TTP(T1499 계열) 매핑과 함께 기록
