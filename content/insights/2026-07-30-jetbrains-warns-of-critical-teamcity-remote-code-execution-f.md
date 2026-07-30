---
title: "JetBrains TeamCity On-Premises 인증 우회 통한 원격 코드 실행 취약점 경고"
date: 2026-07-30T23:11:01.083639+00:00
verdict: "백로그"
tags: ["critical-rce", "teamcity", "authentication-bypass"]
source: "https://www.bleepingcomputer.com/news/security/jetbrains-warns-of-critical-teamcity-remote-code-execution-flaw/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** TeamCity는 과거 DPRK 등 APT 그룹의 주요 타깃이었던 CI/CD 플랫폼으로, 인증 우회 + RCE 조합의 크리티컬 취약점은 CVE 트래킹·익스플로잇 공개 여부 모니터링 대상
- **액션:** CVE 번호 확인 후 CISA KEV 등재 및 PoC 공개 여부를 주시하고, STIX CourseOfAction·Vulnerability 객체로 초안 구조화
