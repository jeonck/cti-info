---
title: "ARM64 KVM 게스트가 호스트 메모리 읽기·쓰기 가능한 리눅스 커널 신규 취약점"
date: 2026-09-23T00:08:22.582821+00:00
verdict: "학습"
tags: ["cve-2026-89775", "vm-escape", "linux-kernel"]
source: "https://thehackernews.com/2026/09/new-linux-kernel-flaw-gives-arm64-kvm.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** ARM64 KVM 게스트 탈출 CVE-2026-89775로, 운영 인프라는 없으나 신규 CVE 트래킹 관심 분야에 해당
- **액션:** CVE-2026-89775를 STIX Vulnerability 객체로 모델링하고 CVSS 점수·영향 범위(nested virt 조건) 메타데이터 정규화
