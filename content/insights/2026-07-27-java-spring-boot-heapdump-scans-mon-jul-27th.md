---
title: "Spring Boot /actuator/heapdump 엔드포인트 스캔 및 자격증명 탈취 TTP 분석"
date: 2026-07-27T23:05:26.762607+00:00
verdict: "학습"
tags: ["ttp-credential-access", "spring-boot-actuator", "mitre-attack"]
source: "https://isc.sans.edu/diary/rss/33188"
source_name: "SANS Internet Storm Center"
status: "완료"
---
- **근거:** Spring Boot actuator 노출 취약점은 직접 운영 인프라는 없으나, 공격자가 메모리 덤프로 자격증명을 탈취하는 TTP(T1552 등) 패턴으로 CTI 구조화 연구에 관련
- **액션:** MITRE ATT&CK T1552.001(Credentials In Files) 및 T1005(Data from Local System)에 heapdump 악용 패턴 매핑하여 STIX Course of Action 오브젝트 초안 작성
