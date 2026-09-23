---
title: "Bifrost AI 게이트웨이 인증 없이 임의 명령 실행 허용 치명적 취약점 (CVE-2026-90898, CVSS 9.8)"
date: 2026-09-23T00:08:22.582821+00:00
verdict: "학습"
tags: ["critical-cve", "ai-gateway", "rce-unauthenticated"]
source: "https://thehackernews.com/2026/09/critical-bifrost-ai-gateway-flaw-lets.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 운영 중인 스택에 Bifrost AI Gateway가 없어 직접 패치 대상은 아니나, CVSS 9.8 신규 CVE로 CVE/익스플로잇 관심 분야에 해당
- **액션:** CVE-2026-90898을 STIX Vulnerability 객체로 모델링하고, 인증 우회→RCE 패턴을 ATT&CK T1190(Exploit Public-Facing Application)에 매핑해 파이프라인 샘플 데이터로 추가
