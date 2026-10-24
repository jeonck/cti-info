---
title: "Ruby Onigmo 정규식 엔진 3개 버그로 GitLab Critical RCE 4건 유발 — Ruby 패치 릴리스"
date: 2026-10-24T00:22:48.349283+00:00
verdict: "학습"
tags: ["cve-exploit", "rce", "supply-chain"]
source: "https://thehackernews.com/2026/10/ruby-fixes-three-regex-engine-bugs.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** GitLab RCE 취약점의 근본 원인(Onigmo 정규식 엔진 메모리 손상)은 CVE/익스플로잇 분석 및 TTP 구조화 관심 분야에 해당
- **액션:** 관련 CVE 번호 확인 후 STIX Vulnerability 객체로 모델링하고 Onigmo 버그→GitLab RCE 연결 관계(exploit-target) 그래프에 추가
