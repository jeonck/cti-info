---
title: "curl HTTP/2 업로드 결함 패치 — PoC로 클라이언트 측 코드 실행 확인"
date: 2026-10-15T00:20:56.708433+00:00
verdict: "학습"
tags: ["cve-exploit", "memory-corruption", "http2"]
source: "https://thehackernews.com/2026/10/curl-patches-http2-upload-flaw-after.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 CVE + PoC 공개로 관심 분야인 CVE/익스플로잇 카테고리에 해당하나, 악용 난이도가 높고(메모리 레이아웃 사전 파악 필요) 운영 중인 방어 인프라가 없어 즉시조치·백로그 대상 외
- **액션:** curl 8.23.0 릴리스 노트 및 연구자 PoC 분석 후 CVE 항목을 STIX Vulnerability 객체로 구조화(CVSS, 익스플로잇 성숙도, 영향 컴포넌트 포함)하여 지식그래프에 등재
