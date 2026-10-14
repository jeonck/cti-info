---
title: "Ghostscript 힙 버퍼 오버플로우로 PDF 업로드 통한 원격 코드 실행 가능"
date: 2026-10-14T00:57:50.887815+00:00
verdict: "학습"
tags: ["cve-rce", "ghostscript", "exploit-public-facing-application"]
source: "https://www.bleepingcomputer.com/news/security/ghostscript-flaw-lets-hackers-hijack-servers-via-pdf-uploads/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** 운영 중인 인프라에 Ghostscript를 사용하지 않으나, 원격 코드 실행을 허용하는 Critical CVE로 CVE/익스플로잇 관심 분야에 해당
- **액션:** CVE-2026-39919를 STIX 2.1 Vulnerability 객체로 모델링하고 관련 TTP(T1190 Exploit Public-Facing Application) 매핑 작성
