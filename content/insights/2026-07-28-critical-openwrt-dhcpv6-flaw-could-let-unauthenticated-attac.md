---
title: "OpenWrt DHCPv6 스택 오버플로우(CVE-2026-53921) — 비인증 원격 루트 실행 가능"
date: 2026-07-28T23:03:06.606637+00:00
verdict: "학습"
tags: ["cve-critical", "network-device", "remote-code-execution"]
source: "https://thehackernews.com/2026/07/critical-openwrt-dhcpv6-flaw-could-let.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVSS 9.8 신규 CVE(CVE-2026-53921)로 스택 오버플로우 기반 비인증 RCE 사례 — 운영 인프라는 없으나 취약점 구조화·TTP 분석 대상으로 적합
- **액션:** CVE-2026-53921을 STIX Vulnerability 객체로 정규화하고, odhcpd DHCPv6 파싱 결함을 T1190(Exploit Public-Facing Application)에 매핑해 온톨로지에 추가
