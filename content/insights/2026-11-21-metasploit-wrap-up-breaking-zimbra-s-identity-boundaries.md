---
title: "Zimbra 신원 경계 우회 CVE 2종, Metasploit 익스플로잇 모듈 공개"
date: 2026-11-21T03:02:14.926626+00:00
verdict: "학습"
tags: ["new-cve-poc", "authorization-bypass", "metasploit-module"]
source: "https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-breaking-zimbra-s-identity-boundaries"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** Zimbra 인프라를 직접 운영하지 않으나, 신규 CVE 2개(CVE-2026-73571, CVE-2026-93637)에 대해 Metasploit 익스플로잇 모듈이 공개된 사례로 'PoC 공개 직후 CVE 추적' 관심 분야에 해당
- **액션:** CVE-2026-73571(인증 우회·이메일 위장)과 CVE-2026-93637(레이트리밋 우회·크리덴셜 스터핑)을 STIX 2.1 Vulnerability/Attack-Pattern 오브젝트로 정규화하고 MITRE ATT&CK T1078(Valid Accounts), T1110(Brute Force) 에 매핑
