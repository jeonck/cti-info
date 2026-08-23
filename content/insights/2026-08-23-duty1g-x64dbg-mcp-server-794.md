---
title: "x64dbg MCP 서버 — AI 어시스턴트로 디버거 제어하는 네이티브 플러그인"
date: 2026-08-23T22:25:48.580749+00:00
verdict: "학습"
tags: ["malware-analysis", "dynamic-analysis", "mcp"]
source: "https://github.com/duty1g/x64dbg-mcp-server"
source_name: "GitHub Trending"
status: "대기"
---
- **근거:** 악성코드 분석 리포트(구조·행위 패턴) 관심 분야에 해당 — x64dbg는 악성코드 동적 분석 핵심 도구이며, MCP로 AI 연동 시 TTP 추출 파이프라인 자동화에 활용 가능
- **액션:** x64dbg-mcp-server 레포 클론 후 MCP API 엔드포인트 목록 확인, 악성코드 행위 추출(레지스터 덤프·메모리 읽기) 자동화 가능성을 CTI 파이프라인 설계 문서에 메모
