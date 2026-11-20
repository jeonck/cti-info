---
title: "NGINX2Root: 원격 코드 실행 + 커널 권한 상승 체이닝 취약점"
date: 2026-11-20T02:53:16.905409+00:00
verdict: "학습"
tags: ["cve-rce", "exploit-chain", "ttp-mapping"]
source: "https://www.bleepingcomputer.com/news/security/critical-nginx-nginx2root-bugs-let-attackers-hijack-servers/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** 운영 중인 NGINX 인프라는 없으나, RCE 취약점 체이닝(NGINX + 커널 LPE) 사례는 TTP 분석 및 CVE 구조화 연구 관심 범위에 해당
- **액션:** CVE 번호 확인 후 STIX Vulnerability 객체로 정규화하고 MITRE ATT&CK T1190(Exploit Public-Facing Application) 및 T1068(Exploitation for Privilege Escalation)과 매핑
