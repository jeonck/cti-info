---
title: "Akira 랜섬웨어 암호화 취약점을 이용한 GPU 기반 파일 복호화 기법 분석"
date: 2026-10-11T00:44:45.257006+00:00
verdict: "학습"
tags: ["ransomware-ttp", "akira", "malware-analysis"]
source: "https://tinyhack.com/2025/03/13/decrypting-encrypted-files-from-akira-ransomware-linux-esxi-variant-2024-using-a-bunch-of-gpus/"
source_name: "HN (ransomware)"
status: "대기"
---
- **근거:** Akira 랜섬웨어의 암호화 구현 취약점(타임스탬프 기반 시드)을 역이용한 복호화 기법 — 랜섬웨어 그룹 TTP 분석 및 악성코드 행위 패턴 연구에 직접 해당
- **액션:** Akira 랜섬웨어의 암호화 스킴(chacha8+RSA, 타임스탬프 시드 취약점)을 MITRE ATT&CK T1486(Data Encrypted for Impact)에 매핑하고 STIX Malware 객체로 구조화 초안 작성
