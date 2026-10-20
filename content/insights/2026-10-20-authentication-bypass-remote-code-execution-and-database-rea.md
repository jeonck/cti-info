---
title: "Eptura Archibus 인증 우회·RCE·DB 읽기 취약점 3종 공개 (패치 완료)"
date: 2026-10-20T00:58:41.930313+00:00
verdict: "학습"
tags: ["authentication-bypass", "rce", "cve-analysis"]
source: "https://www.rapid7.com/blog/post/ve-authentication-bypass-remote-code-execution-and-database-read-in-eptura-archibus-fixed"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** Eptura Archibus는 운영 스택과 무관하나, 인증 우회→파일 업로드→RCE로 이어지는 취약점 체인(CVSS 9.6)은 TTP 패턴 및 CVE 구조화 분석 관심 분야에 해당
- **액션:** CVE-2026-107186 STIX Vulnerability 객체 생성 후 ATT&CK T1190(Exploit Public-Facing Application) 및 T1059(Command and Scripting Interpreter)와 매핑하여 auth-bypass→RCE 체인을 관계 그래프로 모델링
