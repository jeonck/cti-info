---
title: "Fireworks AI 키 탈취로 인한 Claude Code 확장 프로그램 공급망 침해 사건 분석"
date: 2026-11-16T01:39:17.732849+00:00
verdict: "학습"
tags: ["supply-chain-attack", "credential-theft", "ttp-analysis"]
source: "https://thehackernews.com/2026/11/stolen-fireworks-ai-key-led-to-cursor.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 공급망 공격(API 키 탈취 → 확장 프로그램 트로이목마화) 사례로, TTPs 분석 및 ATT&CK 매핑(T1195 Supply Chain Compromise, T1552 Unsecured Credentials) 관점에서 연구 가치 있음
- **액션:** 해당 사건을 STIX Bundle로 모델링: ThreatActor → Campaign → AttackPattern(T1195.001) + Credential 탈취 경로(Fireworks AI 침해 → Cursor 키 노출 → 악성 확장 배포) 관계 그래프 초안 작성
