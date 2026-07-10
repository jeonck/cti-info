---
title: "Rust 기반 멀티스레드 TUI 악성코드 분석 도구 hacksguard 공개"
date: 2026-07-10T23:01:22.107325+00:00
verdict: "학습"
tags: ["malware-analysis", "yara", "ttp"]
source: "https://github.com/Rhacknarok/hacksguard"
source_name: "GitHub Trending"
status: "대기"
---
- **근거:** 악성코드 분석 도구(PE 파싱, YARA 스캔, 휴리스틱 위험 스코어링)로, TTP 분석 및 악성코드 행위 패턴 연구 관심 분야에 해당
- **액션:** hacksguard를 로컬에 설치해 샘플 PE 파일에 대해 YARA 스캔 및 휴리스틱 스코어링 결과를 CTI 파이프라인의 악성코드 속성 필드와 매핑 가능한지 확인
