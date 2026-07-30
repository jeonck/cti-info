---
title: "VMware vCenter 인증 우회·RCE 취약점 CVE-2026-59309/59310 (CVSS 9.8)"
date: 2026-07-30T23:11:01.083639+00:00
verdict: "백로그"
tags: ["critical-cve", "vmware-vcenter", "authentication-bypass"]
source: "https://www.rapid7.com/blog/post/etr-critical-vmware-vcenter-vulnerabilities-allow-authentication-bypass-and-remote-code-execution-cve-2026-59309-cve-2026-59310"
source_name: "Rapid7 Blog"
status: "대기"
---
- **근거:** CVSS 9.8 Critical 신규 CVE이나 CISA KEV 등재·PoC 공개·활발한 악용 증거가 없어 긴급 분석 대상은 아님; CTI 파이프라인의 고위험 취약점 레코드로 수집·구조화 가치 있음
- **액션:** CVE-2026-59309/59310을 STIX 2.1 Vulnerability 객체로 모델링하고, VMware vCenter를 대상으로 한 기존 APT 캠페인 TTP(T1078 Valid Accounts, T1190 Exploit Public-Facing Application)와 Relationship 엣지 추가
