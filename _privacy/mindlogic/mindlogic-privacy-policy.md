---
api_specs:
- filename: mindlogic-audio-api-openapi.yml
  format: yaml
  label: Mindlogic Audio API
  slug: mindlogic-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-audio-api-openapi.yml
- filename: mindlogic-credits-api-openapi.yml
  format: yaml
  label: Mindlogic Credits API
  slug: mindlogic-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-credits-api-openapi.yml
- filename: mindlogic-gateway-api-openapi.yml
  format: yaml
  label: Mindlogic Gateway API
  slug: mindlogic-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-gateway-api-openapi.yml
- filename: mindlogic-images-api-openapi.yml
  format: yaml
  label: Mindlogic Images API
  slug: mindlogic-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-images-api-openapi.yml
- filename: mindlogic-models-api-openapi.yml
  format: yaml
  label: Mindlogic Models API
  slug: mindlogic-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-models-api-openapi.yml
- filename: mindlogic-video-api-openapi.yml
  format: yaml
  label: Mindlogic Video API
  slug: mindlogic-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-video-api-openapi.yml
- filename: mindlogic-chat-completions-api-openapi.yml
  format: yaml
  label: Mindlogic Chat Completions API
  slug: mindlogic-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mindlogic/openapi/mindlogic-chat-completions-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 이름, 이메일주소, 소속
  - category: device
    text: IP정보, MAC정보, 이용기록, 접속로그, 쿠키
  deletion:
    route: automatic destruction after retention period expires
    text: 개별이용자가 제공한 모든 개인정보는 보유기간이 만료되면 내부방침 및 관련 법령에 따라 자동적으로 파기 대상으로 선정되어 파기됩니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account identification and withdrawal
    text: 가입신청 의사의 확인, 개별이용자 식별, 탈퇴 의사의 확인
  - purpose: service analysis and statistics
    text: 서비스 이용기록과 접속 빈도 분석, 서비스 이용에 대한 통계
  - purpose: generative AI response generation
    text: '이전 목적: 생성형 AI 기반의 응답 생성'
  retention:
  - period: 5년 간
    scope: contract or withdrawal records
    text: 그로부터 5년 간 보존합니다
  - period: 3년 간
    scope: consumer complaint or dispute records
    text: 그로부터 3년 간 보존합니다
  - period: 3개월 간
    scope: communication confirmation records
    text: 기록이 생성된 시점으로부터 3개월 간 보존합니다
  - period: 30일
    scope: cross-border transferred query data
    text: '5. 보유 및 이용 기간: 30일'
  rights:
  - right: withdraw consent
    text: 개별이용자가 개인정보 수집 및 이용에 관한 동의를 철회하면 즉시 만료됩니다.
  - right: refuse cross-border transfer
    text: 정보주체는 다음과 같은 방법으로 개인정보의 국외이전에 대한 동의를 거부하실 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 개별이용자의 사전 동의 없이는 그 범위를 초과하여 이용하거나 제3자에게 공개/제공하지 않습니다.
  subprocessors:
    text: '2. 위탁을 받는 자: [해당사항 없음]'
    url: null
  transfers:
  - mechanism: other
    text: 공급자는 원활한 AI응답 생성 서비스 제공을 위해 다음과 같이 개별이용자의 데이터를 국외로 이전할 수 있습니다.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mindlogic
provenance_date: '2026-11-10'
provider_name: Mindlogic
provider_slug: mindlogic
slug: mindlogic-privacy-policy
source_date: '2026-11-10'
source_filename: mindlogic-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://factchat-public.s3.ap-northeast-2.amazonaws.com/public/pdf/ko_privacy_policy.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mindlogic\naid: mindlogic\nurl: https://factchat-public.s3.ap-northeast-2.amazonaws.com/public/pdf/ko_privacy_policy.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 이름, 이메일주소, 소속\n- category: device\n  text: IP정보, MAC정보, 이용기록, 접속로그, 쿠키\npurposes:\n- purpose: account identification and withdrawal\n  text: 가입신청 의사의 확인, 개별이용자 식별, 탈퇴 의사의 확인\n- purpose: service analysis and statistics\n  text: 서비스 이용기록과 접속 빈도 분석, 서비스 이용에 대한 통계\n- purpose: generative AI response generation\n  text: '이전 목적: 생성형 AI 기반의 응답 생성'\nretention:\n- scope: contract\
  \ or withdrawal records\n  period: 5년 간\n  text: 그로부터 5년 간 보존합니다\n- scope: consumer complaint or dispute records\n  period: 3년 간\n  text: 그로부터 3년 간 보존합니다\n- scope: communication confirmation records\n  period: 3개월 간\n  text: 기록이 생성된 시점으로부터 3개월 간 보존합니다\n- scope: cross-border transferred query data\n  period: 30일\n  text: '5. 보유 및 이용 기간: 30일'\nresidency: []\ntransfers:\n- mechanism: other\n  text: 공급자는 원활한 AI응답 생성 서비스 제공을 위해 다음과 같이 개별이용자의 데이터를 국외로 이전할 수 있습니다.\nsubprocessors:\n  url: null\n  text: '2. 위탁을 받는 자: [해당사항 없음]'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: automatic destruction after retention period expires\n  text: 개별이용자가 제공한 모든 개인정보는 보유기간이 만료되면 내부방침 및 관련 법령에 따라 자동적으로 파기 대상으로 선정되어 파기됩니다.\nrights:\n- right: withdraw consent\n  text: 개별이용자가 개인정보 수집 및 이용에 관한 동의를 철회하면 즉시 만료됩니다.\n- right: refuse cross-border transfer\n  text: 정보주체는 다음과 같은 방법으로 개인정보의 국외이전에 대한 동의를 거부하실 수 있습니다.\nsale_or_sharing:\n  stance: conditional\n  text: 개별이용자의 사전 동의 없이는 그 범위를 초과하여 이용하거나\
  \ 제3자에게 공개/제공하지 않습니다.\n"
source_yaml_url: https://artifacts.apis.io/mindlogic/privacy/mindlogic-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Mindlogic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Conversational AI
- LLM Gateway
- Chatbots
- API Gateway
- South Korea
---
