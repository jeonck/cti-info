---
title: "n8n 샌드박스 탈출 취약점 — 인증된 워크플로 편집자의 서버 OS 명령 실행 가능"
date: 2026-07-27T23:05:26.762607+00:00
verdict: "학습"
tags: ["sandbox-escape", "rce", "workflow-automation"]
source: "https://thehackernews.com/2026/07/n8n-sandbox-escape-lets-workflow.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** n8n은 내 CTI 파이프라인 스택에 포함되지 않으나, 인증된 사용자의 샌드박스 탈출을 통한 RCE 취약점 사례로 CVE/익스플로잇 관심 분야에 해당
- **액션:** CVE 번호 및 CVSS 점수 확인 후 STIX Vulnerability 객체로 모델링 실습 (affects 버전 범위, patch 버전, exploit_refs 포함)
