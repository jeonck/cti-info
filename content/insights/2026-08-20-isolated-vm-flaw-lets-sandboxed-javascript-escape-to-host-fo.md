---
title: "isolated-vm 취약점: 샌드박스 JS가 호스트로 탈출해 RCE 가능"
date: 2026-08-20T22:30:51.298620+00:00
verdict: "학습"
tags: ["sandbox-escape", "javascript-rce", "isolated-vm"]
source: "https://thehackernews.com/2026/08/isolated-vm-flaw-lets-sandboxed.html"
source_name: "The Hacker News"
status: "완료"
---
- **근거:** 신규 Critical 취약점(샌드박스 이스케이프→RCE)으로 CVE 관심 분야에 해당하나, 사용자 인프라에 isolated-vm이 포함되어 있지 않아 즉시조치 불필요
- **액션:** GHSA-864f-rcv7-6rh4를 STIX Vulnerability 객체로 모델링하고 7.0.0 이하 버전 영향 범위를 affected_versions 필드에 기록
