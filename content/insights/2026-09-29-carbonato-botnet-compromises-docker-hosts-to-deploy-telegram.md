---
title: "Carbonato 봇넷, Docker 호스트 침해 후 텔레그램 제어 AI 에이전트 배포"
date: 2026-09-29T01:35:48.660073+00:00
verdict: "학습"
tags: ["botnet-ttp", "docker-exploitation", "ai-agent-c2"]
source: "https://thehackernews.com/2026/09/carbonato-botnet-compromises-docker.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Docker 데몬 노출 익스플로잇 및 AI 에이전트 프레임워크를 C2로 활용하는 신규 악성코드 패밀리 — 신규 TTP 분석 및 악성코드 행위 패턴 분류 관심 분야에 해당
- **액션:** Carbonato의 주요 TTP(T1610 Docker daemon abuse, T1102 Telegram C2 등)를 MITRE ATT&CK에 매핑하고 STIX Bundle로 초안 작성
