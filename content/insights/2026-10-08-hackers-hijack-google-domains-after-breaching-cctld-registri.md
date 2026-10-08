---
title: "해커, ccTLD 레지스트리 침해 후 구글 도메인 하이재킹 및 HTTPS 인증서 탈취"
date: 2026-10-08T01:40:42.328696+00:00
verdict: "학습"
tags: ["dns-hijacking", "supply-chain-attack", "ttp-analysis"]
source: "https://www.bleepingcomputer.com/news/security/hackers-hijack-google-domains-after-breaching-cctld-registries/"
source_name: "BleepingComputer"
status: "대기"
---
- **근거:** DNS 하이재킹 및 인증서 탈취를 통한 공급망 침해 사례로, TTP 및 위협 행위자 캠페인 분석 관심 분야에 해당
- **액션:** STIX 2.1로 해당 공격 체인(ccTLD 레지스트리 침해 → DNS 레코드 변조 → 인증서 발급)을 Attack Pattern 및 Campaign 오브젝트로 모델링 초안 작성
