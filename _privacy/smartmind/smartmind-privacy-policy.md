---
api_specs:
- filename: smartmind-file-api-openapi.yml
  format: yaml
  label: SmartMind File API
  slug: smartmind-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-file-api-openapi.yml
- filename: smartmind-health-api-openapi.yml
  format: yaml
  label: SmartMind Health API
  slug: smartmind-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-health-api-openapi.yml
- filename: smartmind-metric-api-openapi.yml
  format: yaml
  label: SmartMind Metric API
  slug: smartmind-metric-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-metric-api-openapi.yml
- filename: smartmind-query-api-openapi.yml
  format: yaml
  label: SmartMind Query API
  slug: smartmind-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-query-api-openapi.yml
- filename: smartmind-schema-api-openapi.yml
  format: yaml
  label: SmartMind Schema API
  slug: smartmind-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-schema-api-openapi.yml
- filename: smartmind-table-api-openapi.yml
  format: yaml
  label: SmartMind Table API
  slug: smartmind-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-table-api-openapi.yml
- filename: smartmind-table-template-api-openapi.yml
  format: yaml
  label: SmartMind Table Template API
  slug: smartmind-table-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-table-template-api-openapi.yml
- filename: smartmind-view-api-openapi.yml
  format: yaml
  label: SmartMind View API
  slug: smartmind-view-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartmind/openapi/smartmind-view-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 회사명, 이름, 직책, 이메일, 연락처, 문의 내용
  - category: device
    text: 방문 일시, IP 주소, 브라우저 종류, OS, 방문 페이지, 쿠키
  - category: professional
    text: 이름, 이메일, 연락처, 이력서 파일, 포트폴리오 URL, 자기소개
  deletion:
    route: Destroy once purpose is fulfilled; electronic files permanently deleted
    text: 회사는 개인정보 수집·이용 목적이 달성된 후에는 해당 정보를 지체 없이 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sales inquiry handling
    text: '도입 문의: 솔루션 도입 상담, 견적 제공, PoC 진행, 후속 연락'
  - purpose: Service provision
    text: '서비스 이용: 본인 확인, 서비스 제공 및 운영, 이용 통계 분석, 고객 지원'
  retention:
  - period: 1년
    scope: Sales inquiry information
    text: 도입 문의 정보 문의 처리 완료 후 1년
  - period: 5년
    scope: Contract and payment records
    text: 계약·결제 기록 5년 전자상거래법 제6조
  - period: 3개월
    scope: Website access logs
    text: 홈페이지 방문 기록(접속 로그) 3개월
  rights:
  - right: Access request
    text: 개인정보 열람 요구
  - right: Correction request
    text: 오류 등이 있을 경우 정정 요구
  - right: Deletion request
    text: 삭제 요구
  - right: Processing suspension request
    text: 처리 정지 요구
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 원칙적으로 정보주체의 사전 동의 없이 제3자에게 제공하지 않습니다.
  subprocessors:
    text: Naver Cloud Platform 클라우드 인프라 운영 및 데이터 저장 위탁
    url: null
  transfers:
  - mechanism: other
    text: 이 과정에서 쿠키, 방문 페이지, 브라우저 정보 등이 Google의 서버(국외)로 전송될 수 있습니다.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SmartMind
provenance_date: '2026-11-10'
provider_name: SmartMind
provider_slug: smartmind
slug: smartmind-privacy-policy
source_date: '2026-11-10'
source_filename: smartmind-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.smartmind-ai.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SmartMind\naid: smartmind\nurl: https://www.smartmind-ai.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 회사명, 이름, 직책, 이메일, 연락처, 문의 내용\n- category: device\n  text: 방문 일시, IP 주소, 브라우저 종류, OS, 방문 페이지, 쿠키\n- category: professional\n  text: 이름, 이메일, 연락처, 이력서 파일, 포트폴리오 URL, 자기소개\npurposes:\n- purpose: Sales inquiry handling\n  text: '도입 문의: 솔루션 도입 상담, 견적 제공, PoC 진행, 후속 연락'\n- purpose: Service provision\n  text: '서비스 이용: 본인 확인, 서비스 제공 및 운영, 이용 통계 분석, 고객 지원'\nretention:\n- scope: Sales inquiry information\n  period: 1년\n  text: 도입 문의 정보\
  \ 문의 처리 완료 후 1년\n- scope: Contract and payment records\n  period: 5년\n  text: 계약·결제 기록 5년 전자상거래법 제6조\n- scope: Website access logs\n  period: 3개월\n  text: 홈페이지 방문 기록(접속 로그) 3개월\nresidency: []\ntransfers:\n- mechanism: other\n  text: 이 과정에서 쿠키, 방문 페이지, 브라우저 정보 등이 Google의 서버(국외)로 전송될 수 있습니다.\nsubprocessors:\n  url: null\n  text: Naver Cloud Platform 클라우드 인프라 운영 및 데이터 저장 위탁\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Destroy once purpose is fulfilled; electronic files permanently deleted\n  text: 회사는 개인정보 수집·이용 목적이 달성된 후에는 해당 정보를 지체 없이 파기합니다.\nrights:\n- right: Access request\n  text: 개인정보 열람 요구\n- right: Correction request\n  text: 오류 등이 있을 경우 정정 요구\n- right: Deletion request\n  text: 삭제 요구\n- right: Processing suspension request\n  text: 처리 정지 요구\nsale_or_sharing:\n  stance: conditional\n  text: 원칙적으로 정보주체의 사전 동의 없이 제3자에게 제공하지 않습니다.\n"
source_yaml_url: https://artifacts.apis.io/smartmind/privacy/smartmind-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from SmartMind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Database
- Analytics
- Data
- SQL
- Ontology
- RAG
- Enterprise AI
- Mental Health
- Wellness
- Platform
---
