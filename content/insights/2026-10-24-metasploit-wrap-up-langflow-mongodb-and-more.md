---
title: "Metasploit, OpenCTI 인증 전 원격 코드 실행(pre-auth RCE) 체인 모듈 공개"
date: 2026-10-24T00:22:48.349283+00:00
verdict: "즉시조치"
tags: ["opencti-rce", "pre-auth-rce", "metasploit-module"]
source: "https://www.rapid7.com/blog/post/pt-metasploit-wrap-up-langflow-mongodb-and-more"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** 운영 중인 CTI 파이프라인 도구인 OpenCTI에 대한 pre-auth RCE 체인이 Metasploit 모듈로 공개되어 즉각적인 버전 확인 및 패치가 필요
- **액션:** 운영 중인 OpenCTI 인스턴스 버전 확인 후 취약 버전 여부 점검(CVE 번호 미기재이나 Metasploit PR #21831 참조), 최신 버전으로 업그레이드 또는 네트워크 접근 제한 적용
