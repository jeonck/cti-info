---
title: "Docker Sandboxes 치명적 결함 — 게스트 코드가 macOS 호스트 파일 읽기·수정 가능"
date: 2026-09-18T23:59:08.275851+00:00
verdict: "학습"
tags: ["container-escape", "cve-2026-77179", "ttp-analysis"]
source: "https://thehackernews.com/2026/09/critical-docker-sandboxes-flaw-lets.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 컨테이너 탈출 취약점(CVE-2026-77179)으로 CTI 연구 인프라와 직접 관련은 없으나, 샌드박스 이스케이프 기법은 TTP 분석 및 공격 시나리오 모델링 관심 분야에 해당
- **액션:** CVE-2026-77179를 STIX Course of Action/Vulnerability 객체로 모델링하고, 컨테이너 탈출 TTP(T1611)와 연결하는 샘플 STIX 번들 작성
