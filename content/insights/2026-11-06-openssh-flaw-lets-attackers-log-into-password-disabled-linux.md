---
title: "OpenSSH 취약점: 비밀번호 비활성화 계정에 초대형 패스워드로 로그인 가능"
date: 2026-11-06T02:04:19.270601+00:00
verdict: "학습"
tags: ["openssh-cve", "authentication-bypass", "linux-vuln"]
source: "https://www.bleepingcomputer.com/news/security/openssh-flaw-lets-attackers-log-into-password-disabled-linux-accounts/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** OpenSSH 신규 취약점(CVE)으로 관심 분야인 CVE/취약점 카테고리에 해당하며, 직접 운영하는 인프라는 없으나 CTI 구조화 연구 맥락에서 익스플로잇 패턴 분석 가치 있음
- **액션:** CVE 번호 확인 후 STIX Vulnerability 객체로 정규화 — affected_systems(musl-based Alpine Linux), attack_pattern(oversized password bypass), mitigation(OpenSSH 긴급 패치 버전) 필드 매핑
