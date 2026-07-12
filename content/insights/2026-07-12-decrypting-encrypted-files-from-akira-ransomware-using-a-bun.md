---
title: "Akira 랜섬웨어 암호화 취약점: GPU로 복호화 성공한 기법 분석"
date: 2026-07-12T22:54:02.402958+00:00
verdict: "학습"
tags: ["ransomware-ttp", "akira", "crypto-weakness"]
source: "https://tinyhack.com/2025/03/13/decrypting-encrypted-files-from-akira-ransomware-linux-esxi-variant-2024-using-a-bunch-of-gpus/"
source_name: "HN (ransomware)"
status: "대기"
---
- **근거:** Akira 랜섬웨어의 암호화 구현 취약점(타임스탬프 기반 시드)을 GPU 병렬 연산으로 역산한 사례 — 랜섬웨어 TTP 및 암호화 메커니즘 분석 관심 분야에 해당
- **액션:** Akira Linux/ESXi 변종의 암호화 스킴(chacha8 + ECDH 시드 취약점)을 ATT&CK T1486(Data Encrypted for Impact) 및 T1027 하위 기법으로 매핑해 STIX Course of Action 노드 초안 작성
