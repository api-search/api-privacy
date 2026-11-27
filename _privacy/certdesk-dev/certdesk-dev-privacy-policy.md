---
api_specs:
- filename: certdesk-dev-certificate-api-openapi.yml
  format: yaml
  label: certdesk-dev Certificate API
  slug: certdesk-dev-certificate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-certificate-api-openapi.yml
- filename: certdesk-dev-dns-api-openapi.yml
  format: yaml
  label: certdesk-dev Dns API
  slug: certdesk-dev-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-dns-api-openapi.yml
- filename: certdesk-dev-dns-info-api-openapi.yml
  format: yaml
  label: certdesk-dev Dns Info API
  slug: certdesk-dev-dns-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-dns-info-api-openapi.yml
- filename: certdesk-dev-expiry-api-openapi.yml
  format: yaml
  label: certdesk-dev Expiry API
  slug: certdesk-dev-expiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-expiry-api-openapi.yml
- filename: certdesk-dev-explain-api-openapi.yml
  format: yaml
  label: certdesk-dev Explain API
  slug: certdesk-dev-explain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-explain-api-openapi.yml
- filename: certdesk-dev-security-api-openapi.yml
  format: yaml
  label: certdesk-dev Security API
  slug: certdesk-dev-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-security-api-openapi.yml
- filename: certdesk-dev-watch-api-openapi.yml
  format: yaml
  label: certdesk-dev Watch API
  slug: certdesk-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certdesk-dev/openapi/certdesk-dev-watch-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: 이메일 주소(구독, 대기자, 피드백 회신, 문의, 소유권 확인과 보안 진단)
  - category: other
    text: 감시·진단할 도메인과 알림 설정
  - category: device
    text: 접속 정보(IP 주소 등)
  - category: behavioral
    text: 이용 경로(웹·API·MCP·배지·캘린더), 기능 이름
  deletion:
    route: 수신 거부 링크 또는 hello@certdesk.dev
    text: '구독 해지(삭제) : 모든 감시 메일 아래의 ''수신 거부'' 링크를 열고 확인 버튼을 누르면 구독 기록(이메일·도메인·알림 설정)을 즉시 삭제합니다.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 신청 확인 메일 발송
    text: 신청 확인 메일 발송, 등록한 도메인의 인증서·도메인 등록 만료·보안 등급 매일 점검
  - purpose: 서비스 제공·남용 대응·개선
    text: 서비스 제공, 남용·장애 대응, 이용 현황 파악과 개선 근거
  residency:
  - region: 미국·유럽경제지역 (Cloudflare)
    text: 미국 등 (주로 미국·유럽경제지역에 저장)
  retention:
  - period: '메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 구독을 해지할 때까지(해지하면 즉시 삭제)'
    scope: 만료 감시 구독
    text: '보유 기간 메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 구독을 해지할 때까지(해지하면 즉시 삭제)'
  - period: '메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 1년(지나면 자동 삭제)'
    scope: 팀용 버전 대기자 명단
    text: '보유 기간 메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 1년(지나면 자동 삭제)'
  - period: 접수 후 1년(지나면 자동 삭제)
    scope: 피드백
    text: 보유 기간 접수 후 1년(지나면 자동 삭제)
  - period: 답변·처리를 마친 뒤 1년 안에 삭제
    scope: 메일 문의
    text: 답변·처리를 마친 뒤 1년 안에 삭제
  - period: 90일
    scope: 보안 진단 보고서
    text: 진단 보고서는 생성 후 90일 동안 보관하고 지나면 자동 삭제합니다
  - period: 3개월
    scope: 이용 통계
    text: 3개월 뒤 자동 삭제됩니다(Cloudflare Workers Analytics Engine 보관 기간)
  - period: 3일
    scope: 실행 기록
    text: 3일 뒤 자동 삭제됩니다(현재 요금제 기준, 유료 요금제는 7일)
  rights:
  - right: 열람·정정·삭제·처리정지
    text: 이용자(정보주체)는 언제든 자기 개인정보의 열람·정정·삭제·처리정지를 요구할 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 「개인정보 보호법」 제28조의8 제1항 제3호(계약 이행을 위한 처리위탁·보관)에 따라 이 방침으로 알립니다.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: certdesk-dev
provenance_date: '2026-11-09'
provider_name: certdesk-dev
provider_slug: certdesk-dev
slug: certdesk-dev-privacy-policy
source_date: '2026-11-09'
source_filename: certdesk-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://certdesk.dev/ko/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: certdesk-dev\naid: certdesk-dev\nurl: https://certdesk.dev/ko/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 이메일 주소(구독, 대기자, 피드백 회신, 문의, 소유권 확인과 보안 진단)\n- category: other\n  text: 감시·진단할 도메인과 알림 설정\n- category: device\n  text: 접속 정보(IP 주소 등)\n- category: behavioral\n  text: 이용 경로(웹·API·MCP·배지·캘린더), 기능 이름\npurposes:\n- purpose: 신청 확인 메일 발송\n  text: 신청 확인 메일 발송, 등록한 도메인의 인증서·도메인 등록 만료·보안 등급 매일 점검\n- purpose: 서비스 제공·남용 대응·개선\n  text: 서비스 제공, 남용·장애 대응, 이용 현황 파악과 개선 근거\nretention:\n- scope: 만료 감시 구독\n  period: '메일 확인 전: 7일(지나면 자동 삭제) ·\
  \ 확인 후: 구독을 해지할 때까지(해지하면 즉시 삭제)'\n  text: '보유 기간 메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 구독을 해지할 때까지(해지하면 즉시 삭제)'\n- scope: 팀용 버전 대기자 명단\n  period: '메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 1년(지나면 자동 삭제)'\n  text: '보유 기간 메일 확인 전: 7일(지나면 자동 삭제) · 확인 후: 1년(지나면 자동 삭제)'\n- scope: 피드백\n  period: 접수 후 1년(지나면 자동 삭제)\n  text: 보유 기간 접수 후 1년(지나면 자동 삭제)\n- scope: 메일 문의\n  period: 답변·처리를 마친 뒤 1년 안에 삭제\n  text: 답변·처리를 마친 뒤 1년 안에 삭제\n- scope: 보안 진단 보고서\n  period: 90일\n  text: 진단 보고서는 생성 후 90일 동안 보관하고 지나면 자동 삭제합니다\n- scope: 이용 통계\n  period: 3개월\n  text: 3개월 뒤 자동 삭제됩니다(Cloudflare Workers Analytics Engine 보관 기간)\n- scope: 실행 기록\n  period: 3일\n  text: 3일 뒤 자동 삭제됩니다(현재 요금제 기준, 유료 요금제는 7일)\nresidency:\n- region: 미국·유럽경제지역 (Cloudflare)\n  text: 미국 등 (주로 미국·유럽경제지역에 저장)\ntransfers:\n- mechanism: other\n  text: 「개인정보 보호법」 제28조의8 제1항 제3호(계약 이행을 위한 처리위탁·보관)에 따라 이 방침으로 알립니다.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 수신 거부 링크 또는 hello@certdesk.dev\n  text: '구독\
  \ 해지(삭제) : 모든 감시 메일 아래의 ''수신 거부'' 링크를 열고 확인 버튼을 누르면 구독 기록(이메일·도메인·알림 설정)을 즉시 삭제합니다.'\nrights:\n- right: 열람·정정·삭제·처리정지\n  text: 이용자(정보주체)는 언제든 자기 개인정보의 열람·정정·삭제·처리정지를 요구할 수 있습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/certdesk-dev/privacy/certdesk-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from certdesk-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
