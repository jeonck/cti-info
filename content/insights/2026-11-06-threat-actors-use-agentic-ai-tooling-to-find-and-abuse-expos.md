---
title: "위협 행위자, 에이전틱 AI 프레임워크 ARTEX로 GitHub 노출 OAuth 시크릿 탐색·악용"
date: 2026-11-06T02:04:19.270601+00:00
verdict: "학습"
tags: ["agentic-ai-ttp", "oauth-secret-abuse", "credential-access"]
source: "https://www.microsoft.com/en-us/security/blog/2026/11/05/threat-actors-use-agentic-ai-tooling-to-find-and-abuse-exposed-secrets/"
source_name: "Microsoft Security Blog"
status: "대기"
---
- **근거:** 위협 행위자의 신규 TTP(에이전틱 AI 기반 자격증명 탐색·악용)로, MITRE ATT&CK 매핑 및 CTI 지식그래프 모델링 대상
- **액션:** ARTEX 프레임워크를 T1552.001(Credentials in Files) 및 T1550.001(Application Access Token) TTP에 매핑하고, OAuth secret 탈취 공격 체인을 STIX Campaign/Attack-Pattern 객체로 초안 모델링
