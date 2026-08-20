---
title: "Poison Claude: 할인 Claude 접근권 판매 중 운영자가 모든 고객 프롬프트 열람"
date: 2026-08-05T23:03:18.805981+00:00
verdict: "학습"
tags: ["llm-abuse", "threat-actor", "supply-chain-ttp"]
source: "https://thehackernews.com/2026/08/poison-claude-sells-discounted-claude.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** LLM API 불법 재판매 서비스가 사용자 프롬프트를 탈취하는 공급망 위협 — 위협 행위자 동향 및 신규 TTP 분석 관심 분야에 해당
- **액션:** Poison Claude 캠페인을 STIX 2.1로 모델링: ThreatActor, Infrastructure(피싱 프록시), TTP(T1199 Trusted Relationship 또는 AiTM) 객체 작성 후 OpenCTI에 임포트 테스트
