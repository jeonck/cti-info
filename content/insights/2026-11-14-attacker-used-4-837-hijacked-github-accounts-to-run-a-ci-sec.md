---
title: "4,837개 탈취 GitHub 계정으로 1,806개 리포지터리 CI 시크릿 탈취 캠페인"
date: 2026-11-14T02:02:16.957889+00:00
verdict: "학습"
tags: ["supply-chain-attack", "ci-cd-compromise", "ttp-mapping"]
source: "https://thehackernews.com/2026/11/4837-hijacked-github-accounts-ran-ci.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** GitHub CI 환경을 대상으로 한 공급망 공격 캠페인으로, TTP(자격증명 탈취→리포지터리 쓰기→CI 시크릿 수집) 분석 및 위협 행위자 동향에 해당
- **액션:** MITRE ATT&CK T1552.001(Credentials In Files) 및 T1195(Supply Chain Compromise) 프레임으로 TTP 매핑 후 STIX 2.1 Campaign/Attack-Pattern 객체로 모델링
