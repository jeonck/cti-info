---
title: "GitLab CVSS 10.0 파일 읽기 취약점(CVE-2026-85706), 공개 직후 야생 악용 탐지"
date: 2026-09-11T23:58:13.841113+00:00
verdict: "학습"
tags: ["cve-critical", "path-traversal", "cisa-kev-candidate"]
source: "https://thehackernews.com/2026/09/gitlab-cvss-10-file-read-flaw-draws-in.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CVE-2026-85706은 CVSS 10.0의 야생 익스플로잇 확인 취약점으로, 직접 운영하는 GitLab 인프라는 없으나 CISA KEV 등재 가능성이 높은 고위험 CVE로서 CTI 구조화·TTP 분석 관심 분야에 해당
- **액션:** CVE-2026-85706을 STIX 2.1 Vulnerability 오브젝트로 모델링하고, path traversal TTP(T1083/T1552)와 연계한 공격 시나리오 지식그래프 노드 추가
