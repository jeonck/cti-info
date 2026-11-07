---
title: "OpenSSH SSHole(CVE-2026-123158) 공개 수 시간 내 실제 익스플로잇 시도 — 허니팟 root 탈취 확인"
date: 2026-11-07T01:43:06.270073+00:00
verdict: "즉시조치"
tags: ["cve-openssh", "exploit-in-wild", "cisa-kev-watch"]
source: "https://thehackernews.com/2026/11/hackers-exploited-openssh-sshole-flaw.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 8.1의 OpenSSH 신규 CVE로 공개 직후 익스플로잇 시도 및 허니팟 root 획득 확인 — PoC 공개 직후 고위험 취약점 즉시조치 기준에 해당
- **액션:** CVE-2026-123158 영향 조건(musl libc + PAM disabled) 확인 후 STIX 2.1 Vulnerability/Indicator 객체로 정규화, CISA KEV 등재 여부 모니터링
