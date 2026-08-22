---
title: "AI 코딩 에이전트(Claude Code·Gemini CLI) 취약점으로 GitHub Issue → CI 시크릿 탈취 가능"
date: 2026-08-07T22:39:48.624149+00:00
verdict: "학습"
tags: ["prompt-injection", "ai-agent-ttp", "ci-cd-attack"]
source: "https://thehackernews.com/2026/08/claude-code-and-gemini-cli-flaws-let.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** AI 코딩 에이전트의 프롬프트 인젝션 → CI 시크릿 탈취라는 신규 TTP로, 공격 기법 동향 및 공급망 공격 체인 관점에서 CTI 구조화 연구에 관련
- **액션:** 해당 공격 체인을 MITRE ATT&CK T1195(공급망 침해) + T1059(명령 실행) 조합으로 매핑하고, AI 에이전트 관련 TTP 노드를 온톨로지에 신규 추가 검토
