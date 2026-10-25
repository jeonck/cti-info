---
title: "Brotli 디코더 메모리 손상(CVE-2026-111497) — Python brotli/brotlicffi 패키지 RCE 영향"
date: 2026-10-25T00:05:41.127914+00:00
verdict: "즉시조치"
tags: ["cve-rce", "python-dependency", "memory-corruption"]
source: "https://thehackernews.com/2026/10/brotli-decoder-flaw-behind-nodejs-rce.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CTI 파이프라인이 Python 기반일 가능성이 높고, 영향 받는 Python brotli/brotlicffi 패키지가 설치되어 있으면 RCE 노출 — PoC 연계 실증 사례(Node.js RCE) 이미 공개된 상태
- **액션:** pip show brotli brotlicffi 로 설치 여부 및 버전 확인 후 취약 버전이면 pip install --upgrade brotli brotlicffi 실행, 없으면 무시
