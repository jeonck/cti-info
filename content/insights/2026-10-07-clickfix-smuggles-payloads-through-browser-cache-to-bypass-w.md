---
title: "ClickFix, 브라우저 캐시에 페이로드를 은닉해 Windows 실행 제한 우회"
date: 2026-10-07T01:16:11.173390+00:00
verdict: "학습"
tags: ["clickfix", "browser-cache-smuggling", "ttp-analysis"]
source: "https://thehackernews.com/2026/10/clickfix-smuggles-payloads-through.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 브라우저 캐시를 악용한 페이로드 은닉이라는 신규 TTP 패턴으로, MITRE ATT&CK 매핑 및 CTI 구조화 연구에 직접 활용 가능
- **액션:** ClickFix 브라우저 캐시 기법을 T1027(Obfuscated Files) 또는 T1105(Ingress Tool Transfer) 서브테크닉으로 매핑하고 STIX Course of Action 오브젝트로 모델링
