---
title: "TerminalFix: 가짜 Cloudflare CAPTCHA로 역방향 터널 백도어 배포하는 ClickFix 변종"
date: 2026-08-31T00:17:19.131619+00:00
verdict: "학습"
tags: ["ttp-analysis", "clickfix-variant", "reverse-tunnel"]
source: "https://thehackernews.com/2026/08/terminalfix-uses-fake-cloudflare.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** ClickFix 변종 TerminalFix는 신규 TTP(사회공학 기반 명령 실행 + 역방향 터널 백도어)로 MITRE ATT&CK 매핑 및 캠페인 분석 관심 분야에 해당
- **액션:** TerminalFix TTP를 MITRE ATT&CK T1204.002(User Execution: Malicious File) 및 T1572(Protocol Tunneling)에 매핑하고 STIX Campaign/Attack-Pattern 객체로 초안 모델링
