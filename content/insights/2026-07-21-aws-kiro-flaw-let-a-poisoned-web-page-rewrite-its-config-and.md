---
title: "AWS Kiro IDE 프롬프트 인젝션으로 설정 파일 변조 및 원격 코드 실행"
date: 2026-07-21T23:01:02.666657+00:00
verdict: "학습"
tags: ["prompt-injection", "agentic-ai-ttp", "rce"]
source: "https://thehackernews.com/2026/07/aws-kiro-flaw-let-poisoned-web-page.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** AI 코딩 IDE의 프롬프트 인젝션→RCE 사례로, 에이전틱 AI 시스템의 TTP 패턴 분석에 해당
- **액션:** Intezer/Kodem Security 원본 리포트를 찾아 공격 체인(프롬프트 인젝션→설정 파일 덮어쓰기→코드 실행) 단계를 MITRE ATT&CK T1059·T1565 등에 매핑해 정리
