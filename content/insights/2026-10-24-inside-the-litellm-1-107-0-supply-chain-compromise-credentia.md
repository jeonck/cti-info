---
title: "LiteLLM 1.107.0 공급망 침해: Python 시작 훅을 통한 자격증명 탈취 분석"
date: 2026-10-24T00:22:48.349283+00:00
verdict: "학습"
tags: ["supply-chain-compromise", "ttp-analysis", "python-startup-hook"]
source: "https://www.microsoft.com/en-us/security/blog/2026/10/23/inside-the-litellm-1-107-0-supply-chain-compromise-credential-theft-through-python-startup-hooks/"
source_name: "Microsoft Security Blog"
status: "대기"
---
- **근거:** 소프트웨어 공급망 공격(Python 패키지 타협)은 CTI 구조화 연구에서 TTP 분석 및 공격 캠페인 패턴 수집 관심 분야에 해당
- **액션:** LiteLLM 1.107.0 공급망 침해 TTP를 MITRE ATT&CK(T1195.001 Supply Chain Compromise, T1059 Python startup hook 남용)에 매핑하고 STIX Bundle로 정규화
