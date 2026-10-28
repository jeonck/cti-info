---
title: "Microsoft Authenticator Android 취약점(CVE-2026-80097): 권한 없는 앱의 업무 계정 토큰 탈취"
date: 2026-10-28T01:03:11.628072+00:00
verdict: "학습"
tags: ["cve", "token-theft", "credential-access"]
source: "https://thehackernews.com/2026/10/microsoft-authenticator-flaw-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 신규 CVE(CVE-2026-80097) 공개·패치로 '관심 분야: CVE/취약점' 범주에 해당; 권한 없는 앱이 MFA 앱을 사칭해 OAuth 토큰을 탈취하는 기법은 MITRE ATT&CK T1528 매핑 가치 있음
- **액션:** CVE-2026-80097을 STIX Vulnerability 객체로 정규화하고, T1528(Steal Application Access Token) TTP 노드와 '이용(exploits)' 관계로 연결하는 온톨로지 모델링 수행
