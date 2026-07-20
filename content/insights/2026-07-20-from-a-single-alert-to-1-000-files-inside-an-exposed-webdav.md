---
title: "노출된 WebDAV 멀웨어 배포 랩 분석: 생성형 AI 활용 공격자 운영 체계 내부 공개"
date: 2026-07-20T23:03:37.157174+00:00
verdict: "학습"
tags: ["ttp-analysis", "webdav-delivery", "ai-assisted-attacks"]
source: "https://www.rapid7.com/blog/post/tr-exposed-webdav-malware-delivery-lab-analysis"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** WebDAV 기반 멀웨어 전달 인프라의 TTP·행위 패턴 분석 리포트로, MITRE ATT&CK 매핑 및 위협 행위자 운영 방식 구조화에 직접 활용 가능
- **액션:** 보고서에서 추출한 WebDAV 전달 체인(WebClient 서비스 기동 → davclnt.dll → rundll32 실행)을 MITRE ATT&CK T1021.002(SMB/WebDAV), T1218.011(Rundll32)로 매핑하고 STIX Campaign/TTP 객체 초안 작성
