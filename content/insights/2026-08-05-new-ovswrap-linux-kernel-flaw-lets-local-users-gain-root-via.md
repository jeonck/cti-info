---
title: "OVSwrap: Open vSwitch 메모리 손상으로 로컬 루트 권한 획득 — 공개 익스플로잇 포함 (CVE-2026-64531)"
date: 2026-08-05T23:03:18.805981+00:00
verdict: "즉시조치"
tags: ["linux-kernel-lpe", "public-exploit", "cve"]
source: "https://thehackernews.com/2026/08/new-ovswrap-linux-kernel-flaw-lets.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 공개 익스플로잇(~800개 커널 빌드 대응) 동반 Linux 커널 LPE 취약점으로, CTI 파이프라인의 취약점 구조화·분석 대상이며 PoC 공개 직후 고위험 케이스에 해당
- **액션:** CVE-2026-64531을 STIX Vulnerability 오브젝트로 정규화(CVSS 7.8, affected-product: linux-kernel + openvswitch, exploit-available: true) 후 KEV 등재 여부 모니터링 태그 부착
