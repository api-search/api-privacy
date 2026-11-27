---
api_specs:
- filename: boltena-com-default-api-openapi.yml
  format: yaml
  label: 볼테나 기본 API
  slug: boltena-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-default-api-openapi.yml
- filename: boltena-com-eqp-api-openapi.yml
  format: yaml
  label: 볼테나 EQP 모듈 필요 API
  slug: boltena-com-eqp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-eqp-api-openapi.yml
- filename: boltena-com-hr-api-openapi.yml
  format: yaml
  label: 볼테나 HR 모듈 필요 API
  slug: boltena-com-hr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltena-com/openapi/boltena-com-hr-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 이용자가 직접 입력하는 항목 — 회사명(필수), 담당자명, 전화, 이메일, 인원 규모, 관심 모듈, 도입 형태, 문의 내용.
  - category: contact
    text: 연락처는 전화 또는 이메일 중 하나만 있으면 됩니다.
  - category: device
    text: 접수 시점의 IP 주소
  - category: behavioral
    text: 문의 폼에 오기 직전에 본 이 사이트 안의 페이지 주소
  - category: device
    text: 브라우저·기기 종류, 대략의 지역
  deletion:
    route: request to the provider
    text: 이용자가 삭제를 요청하면 파기 합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: inquiry response and quotes
    text: 접수된 문의에 대한 응대와 견적 안내
  - purpose: optional product news
    text: 문의 폼에서 별도의 선택 동의 를 하신 경우에만, 입력하신 이메일로 기능·가격 변경 등 제품 소식을 보냅니다.
  - purpose: analytics
    text: 어떤 안내가 도움이 되었는지 파악하기 위한 내부 확인에 사용합니다.
  residency:
  - region: 미국
    text: 수집된 통계 데이터는 Google LLC(미국)의 서버로 전송·보관됩니다.
  - region: unstated
    text: 보관 위치는 당사가 운영하는 데이터베이스이고
  retention:
  - period: null
    scope: inquiry data
    text: 문의 응대 목적이 유지되는 동안 보관하며, 이용자가 삭제를 요청하면 파기 합니다.
  - period: 최대 2년
    scope: blog notification consent
    text: 보유 기간은 수신거부 시까지(최대 2년)이고
  - period: 최대 24개월
    scope: email hash for free trial
    text: 최대 24개월 보관합니다
  - period: 14개월
    scope: Google Analytics data
    text: 보관 기간은 당사의 애널리틱스 보존 설정(14개월)을 따릅니다.
  rights:
  - right: access, correction, deletion, restriction
    text: 본인의 문의 내용에 대해 열람·정정·삭제·처리정지 를 요청할 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 볼테나
provenance_date: '2026-11-09'
provider_name: 볼테나
provider_slug: boltena-com
slug: boltena-com-privacy-policy
source_date: '2026-11-09'
source_filename: boltena-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://boltena.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 볼테나\naid: boltena-com\nurl: https://boltena.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 이용자가 직접 입력하는 항목 — 회사명(필수), 담당자명, 전화, 이메일, 인원 규모, 관심 모듈, 도입 형태, 문의 내용.\n- category: contact\n  text: 연락처는 전화 또는 이메일 중 하나만 있으면 됩니다.\n- category: device\n  text: 접수 시점의 IP 주소\n- category: behavioral\n  text: 문의 폼에 오기 직전에 본 이 사이트 안의 페이지 주소\n- category: device\n  text: 브라우저·기기 종류, 대략의 지역\npurposes:\n- purpose: inquiry response and quotes\n  text: 접수된 문의에 대한 응대와 견적 안내\n- purpose: optional product news\n  text: 문의 폼에서 별도의 선택 동의 를 하신 경우에만, 입력하신\
  \ 이메일로 기능·가격 변경 등 제품 소식을 보냅니다.\n- purpose: analytics\n  text: 어떤 안내가 도움이 되었는지 파악하기 위한 내부 확인에 사용합니다.\nretention:\n- scope: inquiry data\n  period: null\n  text: 문의 응대 목적이 유지되는 동안 보관하며, 이용자가 삭제를 요청하면 파기 합니다.\n- scope: blog notification consent\n  period: 최대 2년\n  text: 보유 기간은 수신거부 시까지(최대 2년)이고\n- scope: email hash for free trial\n  period: 최대 24개월\n  text: 최대 24개월 보관합니다\n- scope: Google Analytics data\n  period: 14개월\n  text: 보관 기간은 당사의 애널리틱스 보존 설정(14개월)을 따릅니다.\nresidency:\n- region: 미국\n  text: 수집된 통계 데이터는 Google LLC(미국)의 서버로 전송·보관됩니다.\n- region: unstated\n  text: 보관 위치는 당사가 운영하는 데이터베이스이고\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to the provider\n  text: 이용자가 삭제를 요청하면 파기 합니다.\nrights:\n- right: access, correction, deletion, restriction\n  text: 본인의 문의 내용에 대해 열람·정정·삭제·처리정지 를 요청할 수 있습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boltena-com/privacy/boltena-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 16 quoted statements, read from 볼테나's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Human Resources
- MES
- Business Intelligence
---
