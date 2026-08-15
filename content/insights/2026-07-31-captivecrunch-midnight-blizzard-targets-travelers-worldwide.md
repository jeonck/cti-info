---
title: "CaptiveCrunch: Midnight Blizzard의 여행객 대상 악성코드 배포 및 자격증명 탈취 캠페인"
date: 2026-07-31T23:05:02.340672+00:00
verdict: "학습"
tags: ["apt-midnight-blizzard", "campaign-analysis", "ttp-mapping"]
source: "https://www.microsoft.com/en-us/security/blog/2026/07/31/captivecrunch-midnight-blizzard-targets-travelers-worldwide-for-malware-delivery-and-credential-theft/"
source_name: "Microsoft Security Blog"
status: "완료"
---
- **근거:** 러시아 APT(Midnight Blizzard/Storm-2945)의 신규 캠페인 분석으로, TTP 및 위협 행위자 동향 관심 분야에 해당
- **액션:** CaptiveCrunch 캠페인 리포트를 STIX 2.1로 모델링: Midnight Blizzard ThreatActor 객체에 Storm-2945 서브클러스터 관계 추가, 호텔 로그인 포털 침해→악성코드 배포→자격증명 탈취 TTP를 ATT&CK(T1566/T1056 등) 매핑하여 Campaign 객체로 구조화
