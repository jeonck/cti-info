---
title: "Candiru 광고 기반 스파이웨어 캠페인 IOC 로컬 스캐너 zero-breach 공개"
date: 2026-10-18T23:59:39.670048+00:00
verdict: "학습"
tags: ["ioc-collection", "spyware-campaign", "threat-actor"]
source: "https://github.com/interplains/zero-breach"
source_name: "GitHub Trending"
status: "대기"
---
- **근거:** Candiru 스파이웨어 캠페인 IOC를 스캔하는 도구로, APT/상업용 스파이웨어 그룹의 캠페인 분석 및 IOC 수집·구조화 관점에서 관심 분야에 해당
- **액션:** zero-breach 저장소의 IOC 목록(해시, 도메인, 경로 패턴 등)을 추출해 STIX Indicator 객체로 정규화하고 AdFection/Candiru 위협행위자 노드와 연결
