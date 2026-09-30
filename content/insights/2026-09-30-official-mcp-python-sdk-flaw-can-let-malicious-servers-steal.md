---
title: "공식 MCP Python SDK 취약점 — 악성 서버가 OAuth 자격증명 탈취 가능 (v1.30.0에서 패치)"
date: 2026-09-30T01:09:26.980305+00:00
verdict: "학습"
tags: ["oauth-credential-theft", "mcp-sdk", "supply-chain-vulnerability"]
source: "https://thehackernews.com/2026/09/official-mcp-python-sdk-flaw-can-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** MCP Python SDK의 OAuth 자격증명 탈취 취약점으로, CVE/소프트웨어 취약점 관심 분야에 해당하나 내 CTI 파이프라인 스택에 직접 사용 중인 컴포넌트는 아님
- **액션:** MCP Python SDK 사용 여부 확인 후, 사용 중이라면 1.30.0 이상으로 업그레이드 (`pip show mcp` → 버전 확인)
