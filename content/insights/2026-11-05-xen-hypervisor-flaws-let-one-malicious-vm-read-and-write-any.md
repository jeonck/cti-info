---
title: "Xen 하이퍼바이저 결함, 악성 VM이 동일 호스트의 타 VM 메모리 읽기·쓰기 가능"
date: 2026-11-05T02:02:27.797665+00:00
verdict: "학습"
tags: ["xen-hypervisor", "vm-escape", "cve-analysis"]
source: "https://thehackernews.com/2026/11/xen-hypervisor-flaws-let-one-malicious.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 운영 중인 Xen 인프라 없음 — 직접 패치 대상은 아니지만 신규 CVE 공개(VM 간 메모리 R/W) 항목으로 관심 분야에 해당
- **액션:** Xen Project 공식 어드바이저리에서 CVE 번호·CVSS 점수 확인 후 STIX Vulnerability 객체로 정규화하고 관련 TTP(T1611 Escape to Host) 매핑
