---
title: "Gitea 치명적 RCE(CVE-2026-60004): 저장소 쓰기 권한으로 Git Hook 통해 셸 명령 실행 가능"
date: 2026-07-29T23:01:48.690478+00:00
verdict: "학습"
tags: ["cve-tracking", "rce", "supply-chain-ttp"]
source: "https://thehackernews.com/2026/07/new-gitea-rce-lets-repository-writers.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** CVE-2026-60004(CVSS 9.8) 신규 공개 — 사용자 스택에 Gitea는 없으나 Git hook 악용 RCE 기법은 TTP 분석·CVE 모니터링 관심 분야에 해당
- **액션:** CVE-2026-60004를 STIX Vulnerability 객체로 모델링하고, T1059(Command and Scripting Interpreter) 및 T1505.004(Server Software Component: IIS Components 대신 Git Hook)에 매핑해 ATT&CK 연계 레코드 생성
