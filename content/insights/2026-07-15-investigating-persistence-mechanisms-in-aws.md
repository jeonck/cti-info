---
title: "AWS 지속성 유지 기법 심층 분석 — IAM·Lambda·페더레이션 세션 탐지 워크플로"
date: 2026-07-15T23:02:50.675029+00:00
verdict: "학습"
tags: ["cloud-persistence", "iam-ttp", "mitre-attack-cloud"]
source: "https://www.rapid7.com/blog/post/dr-investigating-aws-persistence-mechanisms"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** AWS 환경의 IAM·Lambda·페더레이션 세션을 이용한 지속성 유지 TTP(T1136, T1078 계열)를 실전 탐지·대응 관점에서 정리한 분석 리포트로, CTI 지식그래프의 클라우드 환경 TTP 노드 모델링에 참고 가능
- **액션:** 본문의 지속성 기법(IAM CreateUser, Lambda 백도어, 페더레이션 세션 남용)을 MITRE ATT&CK Cloud 매트릭스 서브테크닉(T1136.003, T1078.004 등)에 매핑하고 STIX Relationship 오브젝트로 초안 작성
