---
title: "Azure DevOps MCP 서버 결함으로 숨겨진 PR 댓글이 AI 리뷰 에이전트 탈취 가능"
date: 2026-07-22T23:08:11.311655+00:00
verdict: "학습"
tags: ["prompt-injection", "ai-agent-hijack", "mcp-vulnerability"]
source: "https://thehackernews.com/2026/07/microsoft-azure-devops-mcp-flaw-lets.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** MCP 서버의 프롬프트 인젝션을 통한 AI 에이전트 하이재킹 — CTI 관점에서 AI 파이프라인 공격 TTP에 해당
- **액션:** Azure DevOps MCP 취약점을 MITRE ATT&CK T1055(Process Injection) 또는 신규 AI-specific TTP로 매핑하고 STIX Course of Action 객체로 모델링 검토
