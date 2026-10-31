---
title: "BeyondTrust Remote Support 인증 없는 파일 업로드→RCE (CVE-2026-102764), Metasploit 모듈 공개"
date: 2026-10-31T01:27:30.111110+00:00
verdict: "즉시조치"
tags: ["unauthenticated-rce", "exploit-public", "cve"]
source: "https://www.rapid7.com/blog/post/ra-rapid7-analysis-unauthenticated-file-upload-to-rce-in-beyondtrust-remote-support-cve-2026-102764"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** 인증 불필요 RCE에 공개 Metasploit 모듈이 존재하는 'PoC 공개 직후 고위험 취약점' — CTI 파이프라인 관점에서 CVE·TTP 즉시 구조화 대상
- **액션:** CVE-2026-102764를 STIX2 Vulnerability 객체로 생성하고, T1190(Exploit Public-Facing Application) 및 T1505.003(Web Shell) Attack Pattern과 관계 연결 후 BeyondTrust Remote Support 소프트웨어 엔티티에 매핑
