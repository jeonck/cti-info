---
title: "HTTP/3 QPACK 결함으로 서버 충돌 및 최대 4,000배 메모리 증폭 가능 — PoC 공개"
date: 2026-10-23T00:27:49.578517+00:00
verdict: "학습"
tags: ["http3-qpack", "memory-amplification", "dos-ttp"]
source: "https://thehackernews.com/2026/10/new-qpack-flaws-can-crash-http3-servers.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 취약점 PoC 공개 항목으로 관심 분야에 해당하며, QPACK 헤더 압축을 이용한 메모리 증폭 기법은 DoS TTP 분석 및 ATT&CK 매핑 자료로 활용 가능
- **액션:** CVE 번호 확인 후 STIX Vulnerability 객체 초안 작성, MITRE ATT&CK T1499(Endpoint Denial of Service) 하위 기법으로 매핑 검토
