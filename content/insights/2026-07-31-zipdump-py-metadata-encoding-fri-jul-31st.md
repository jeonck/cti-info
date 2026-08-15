---
title: "zipdump.py를 활용한 ZIP 파일 메타데이터 인코딩 분석 기법"
date: 2026-07-31T23:05:02.340672+00:00
verdict: "학습"
tags: ["malware-analysis", "zip-forensics", "file-metadata"]
source: "https://isc.sans.edu/diary/rss/33202"
source_name: "SANS Internet Storm Center"
status: "완료"
---
- **근거:** ZIP 파일 메타데이터 인코딩 분석 기법은 악성코드 분석(구조·행위 패턴) 관심 분야에 해당하며, zipdump.py는 CTI 파이프라인에서 악성 ZIP 샘플 파싱 시 활용 가능
- **액션:** zipdump.py의 메타데이터 인코딩 옵션(-M 등)을 실제 악성 ZIP 샘플에 적용해 보고, 추출된 메타데이터 필드를 STIX Artifact 오브젝트에 매핑하는 방식 검토
