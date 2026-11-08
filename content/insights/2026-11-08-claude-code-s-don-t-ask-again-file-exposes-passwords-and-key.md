---
title: "Claude Code 설정 파일에 저장된 비밀번호·API키, GitHub 공개 저장소 1,122개에서 노출"
date: 2026-11-08T01:12:05.656869+00:00
verdict: "학습"
tags: ["credential-exposure", "ttp-mapping", "supply-chain"]
source: "https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html"
source_name: "The Hacker News"
status: "대기"
---
- **근거:** CTI 관점에서 AI 코딩 도구의 비밀정보 노출은 공격자의 초기 접근(TA0001) 벡터 및 자격증명 수집(T1552) TTP에 해당하며, 위협행위자 캠페인 분석 시 참조 가능한 공격 기법 사례
- **액션:** MITRE ATT&CK T1552.001(Credentials In Files) 및 T1213(Data from Information Repositories) 항목과 연계해 'AI tool credential leakage' TTP 패턴을 STIX Course of Action 오브젝트로 모델링 검토
