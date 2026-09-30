---
title: "Storm-3068: 소스코드 침해를 넘어 클라우드 자격증명 탈취로 이어지는 공격 체인 분석"
date: 2026-09-30T01:09:26.980305+00:00
verdict: "학습"
tags: ["apt-campaign-analysis", "cloud-credential-theft", "mitre-attack-ttp"]
source: "https://www.microsoft.com/en-us/security/blog/2026/09/29/beyond-source-code-a-path-to-the-keys-to-the-kingdom/"
source_name: "Microsoft Security Blog"
status: "대기"
---
- **근거:** Storm-3068 APT 그룹의 클라우드 환경 내 자격증명 탈취 및 피벗 캠페인 분석으로, 위협 행위자 TTP 및 공격 시나리오 모델링 관심 분야에 해당
- **액션:** Storm-3068의 초기 접근 → 자격증명 탈취 → 클라우드 피벗 체인을 MITRE ATT&CK(T1078, T1552, T1550 등)으로 매핑해 STIX Campaign/TTP 객체로 구조화
