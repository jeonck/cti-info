---
title: "GoAhead 웹서버 TLS 결함 — 폐기된 클라이언트 인증서 허용 및 세션 복호화 가능"
date: 2026-10-28T01:03:11.628072+00:00
verdict: "학습"
tags: ["tls-vulnerability", "certificate-revocation", "embedded-web-server"]
source: "https://thehackernews.com/2026/10/goahead-tls-flaws-allow-revoked-client.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** GoAhead 임베디드 웹서버의 신규 TLS CVE — CISA KEV 미등재·PoC 미공개 단계로 관심 분야 'CVE 공개' 항목에 해당
- **액션:** CVE 번호 확인 후 STIX Vulnerability 객체로 정규화하고 mutual-TLS 우회 TTP(인증서 검증 실패)를 ATT&CK T1552 계열에 매핑 메모 작성
