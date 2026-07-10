---
title: ".NET CLR 네이티브 후킹으로 반사 어셈블리 덤프 및 AMSI/ETW 무결성 검사 도구"
date: 2026-07-10T23:01:22.107325+00:00
verdict: "학습"
tags: ["reflective-loading", "amsi-etw-bypass", "dotnet-ttp"]
source: "https://github.com/Zypherion-Technologies/Nemesis"
source_name: "GitHub Trending"
status: "대기"
---
- **근거:** 반사 어셈블리 로딩·AMSI/ETW 무결성 검증은 .NET 기반 악성코드가 활용하는 방어 회피 TTP로, 악성코드 행위 패턴 분석 및 ATT&CK 매핑 관점에서 참고 가치 있음
- **액션:** MITRE ATT&CK T1620(Reflective Code Loading)·T1562.001(Disable AMSI/ETW) 항목과 이 도구의 탐지 로직을 대조해 TTP 구조화 사례로 메모
