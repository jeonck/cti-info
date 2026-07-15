---
title: "방치된 UEFI 심(Shim) 부트로더 11종, Secure Boot 우회 허용"
date: 2026-07-15T23:02:50.675029+00:00
verdict: "학습"
tags: ["uefi-secure-boot", "firmware-vulnerability", "ttp-analysis"]
source: "https://www.welivesecurity.com/en/eset-research/forgotten-uefi-shims-undermining-secure-boot/"
source_name: "WeLiveSecurity (ESET)"
status: "대기"
---
- **근거:** UEFI 부트킷·Secure Boot 우회 기법은 APT/펌웨어 위협 TTP 분석 및 MITRE ATT&CK(T1542.003) 매핑 연구에 해당
- **액션:** CVE 번호 및 영향받는 shim 목록 확인 후 STIX Vulnerability/Course-of-Action 객체로 모델링하고, T1542.003(Bootkit) TTP와 연결
