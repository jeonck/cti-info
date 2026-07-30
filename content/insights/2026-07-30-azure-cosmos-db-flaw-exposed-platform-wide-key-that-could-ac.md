---
title: "Azure Cosmos DB 취약점, 플랫폼 전역 키 노출로 전체 테넌트 DB 접근 가능"
date: 2026-07-30T23:11:01.083639+00:00
verdict: "학습"
tags: ["cloud-vulnerability", "tenant-isolation-escape", "ttp-analysis"]
source: "https://thehackernews.com/2026/07/azure-cosmos-db-flaw-exposed-platform.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** 클라우드 서비스 테넌트 격리 탈출 및 플랫폼 전역 키 노출은 CTI 관점에서 공격 기법(TTP) 및 취약점 분석 대상
- **액션:** CosmosEscape 익스플로잇 체인(Gremlin 샌드박스 탈출 → 코드 실행 → 플랫폼 키 획득)을 MITRE ATT&CK T1610/T1548 등으로 매핑하고 STIX Course of Action 오브젝트로 정리
