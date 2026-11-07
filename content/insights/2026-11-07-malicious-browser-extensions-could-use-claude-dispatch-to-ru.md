---
title: "악성 브라우저 확장이 Claude Dispatch를 악용해 사용자 PC 코드 실행 가능"
date: 2026-11-07T01:43:06.270073+00:00
verdict: "학습"
tags: ["browser-extension-attack", "ai-tool-exploitation", "ttp-analysis"]
source: "https://thehackernews.com/2026/11/malicious-browser-extensions-could-use.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 브라우저 확장 프로그램을 통한 AI 도구(Claude Dispatch) 악용으로 RCE를 달성하는 신규 공격 체인 — 직접 운영 인프라는 없으나 TTP 분석 관심 분야에 해당
- **액션:** 공격 체인(악성 확장→claude.ai 스크립트 실행→Dispatch→로컬 RCE)을 MITRE ATT&CK T1176(Browser Extensions) 및 T1059(Command and Scripting Interpreter)에 매핑해 CTI 지식그래프에 신규 TTP 노드로 추가
