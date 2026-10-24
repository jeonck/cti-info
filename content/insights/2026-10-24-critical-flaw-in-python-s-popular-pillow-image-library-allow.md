---
title: "Python Pillow EPS 처리 RCE 취약점(CVE-2026-112900): Ghostscript 인자 미검증"
date: 2026-10-24T00:22:48.349283+00:00
verdict: "학습"
tags: ["critical-cve", "rce", "python-library"]
source: "https://thehackernews.com/2026/10/critical-flaw-in-pythons-popular-pillow.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** Python 생태계 Critical RCE CVE로 관심 분야(신규 CVE, 익스플로잇 가능성)에 해당하나, CTI 파이프라인에서 Pillow 이미지 처리를 직접 사용하는 스택은 아님
- **액션:** CVE-2026-112900 CVSS 점수·PoC 공개 여부 확인 후 STIX Vulnerability 객체로 기록, Ghostscript 경유 인자 주입 패턴을 TTP(T1059 계열) 매핑 검토
