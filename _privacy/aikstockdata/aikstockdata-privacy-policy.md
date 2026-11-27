---
api_specs:
- filename: aikstockdata-data-api-openapi.yml
  format: yaml
  label: 한국주식데이터 (aikstockdata) Data API
  slug: aikstockdata-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aikstockdata/openapi/aikstockdata-data-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 닉네임(선택, 미입력 시 '익명')
  - category: identifying
    text: PBKDF2-SHA256 해시(글마다 다른 salt·20,000회 반복)로만 저장하며 복원할 수 없습니다
  - category: device
    text: 접속 IP 주소(도배·악용 방지 목적)
  - category: communication
    text: 작성 내용
  deletion:
    route: author deletes own post/comment with password; otherwise request via contact channels
    text: 글·댓글은 작성 시 설정한 비밀번호로 언제든 직접 수정·삭제할 수 있습니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 도배·악용 방지
    text: 도배·악용 방지(속도 제한)
  - purpose: 방문자 수 집계
    text: 방문자 수 중복 집계 방지를 위해 접속 IP가 1시간 동안 임시 저장됩니다.
  - purpose: 방문 통계 측정
    text: 방문 통계 측정을 위해 Google Analytics 4 (Google LLC)를 사용하며
  residency:
  - region: outside Korea (US and Cloudflare/Google server locations)
    text: 국외(미국 등 Cloudflare 서버 소재지)에서 저장·처리됩니다.
  retention:
  - period: null
    scope: 글·댓글 (함께 저장된 IP 포함)
    text: 글·댓글(함께 저장된 IP 포함)은 작성자가 비밀번호로 직접 삭제하거나 관리자가 삭제할 때까지 보유하며
  - period: 1시간
    scope: 방문 집계 IP
    text: 접속 IP가 1시간 동안 임시 저장됩니다.
  - period: 1년
    scope: 속도 제한 IP 키
    text: 방문 집계·속도 제한용 IP 키는 위에 적은 기간(1시간~1년)이 지나면 자동 파기됩니다.
  - period: 최대 2년
    scope: Google Analytics 쿠키
    text: 이 도구가 방문자 구분용 쿠키(_ga 등, 최대 2년)를 이용자 브라우저에 저장합니다.
  rights:
  - right: edit or delete own posts
    text: 글·댓글은 작성 시 설정한 비밀번호로 언제든 직접 수정·삭제할 수 있습니다.
  - right: deletion request without password
    text: 비밀번호를 설정하지 않았거나 잊은 경우, 아래 문의 채널로 삭제를 요청할 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 수집한 개인정보를 제3자에게 제공하지 않습니다(법령에 따른 적법한 요청 제외).
  subprocessors:
    text: 사이트 호스팅과 데이터 저장은 Cloudflare, Inc. (미국)에 위탁되어 있습니다
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 한국주식데이터 (aikstockdata)
provenance_date: '2026-11-09'
provider_name: 한국주식데이터 (aikstockdata)
provider_slug: aikstockdata
slug: aikstockdata-privacy-policy
source_date: '2026-11-09'
source_filename: aikstockdata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aikstockdata.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 한국주식데이터 (aikstockdata)\naid: aikstockdata\nurl: https://aikstockdata.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 닉네임(선택, 미입력 시 '익명')\n- category: identifying\n  text: PBKDF2-SHA256 해시(글마다 다른 salt·20,000회 반복)로만 저장하며 복원할 수 없습니다\n- category: device\n  text: 접속 IP 주소(도배·악용 방지 목적)\n- category: communication\n  text: 작성 내용\npurposes:\n- purpose: 도배·악용 방지\n  text: 도배·악용 방지(속도 제한)\n- purpose: 방문자 수 집계\n  text: 방문자 수 중복 집계 방지를 위해 접속 IP가 1시간 동안 임시 저장됩니다.\n- purpose: 방문 통계 측정\n  text: 방문 통계 측정을 위해 Google Analytics 4 (Google LLC)를 사용하며\n\
  retention:\n- scope: 글·댓글 (함께 저장된 IP 포함)\n  period: null\n  text: 글·댓글(함께 저장된 IP 포함)은 작성자가 비밀번호로 직접 삭제하거나 관리자가 삭제할 때까지 보유하며\n- scope: 방문 집계 IP\n  period: 1시간\n  text: 접속 IP가 1시간 동안 임시 저장됩니다.\n- scope: 속도 제한 IP 키\n  period: 1년\n  text: 방문 집계·속도 제한용 IP 키는 위에 적은 기간(1시간~1년)이 지나면 자동 파기됩니다.\n- scope: Google Analytics 쿠키\n  period: 최대 2년\n  text: 이 도구가 방문자 구분용 쿠키(_ga 등, 최대 2년)를 이용자 브라우저에 저장합니다.\nresidency:\n- region: outside Korea (US and Cloudflare/Google server locations)\n  text: 국외(미국 등 Cloudflare 서버 소재지)에서 저장·처리됩니다.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 사이트 호스팅과 데이터 저장은 Cloudflare, Inc. (미국)에 위탁되어 있습니다\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: author deletes own post/comment with password; otherwise request via contact channels\n  text: 글·댓글은 작성 시 설정한 비밀번호로 언제든 직접 수정·삭제할 수 있습니다.\nrights:\n- right: edit or delete own posts\n  text: 글·댓글은 작성 시 설정한 비밀번호로 언제든 직접 수정·삭제할 수 있습니다.\n- right: deletion request without password\n  text: 비밀번호를 설정하지 않았거나 잊은\
  \ 경우, 아래 문의 채널로 삭제를 요청할 수 있습니다.\nsale_or_sharing:\n  stance: prohibited\n  text: 수집한 개인정보를 제3자에게 제공하지 않습니다(법령에 따른 적법한 요청 제외).\n"
source_yaml_url: https://artifacts.apis.io/aikstockdata/privacy/aikstockdata-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from 한국주식데이터 (aikstockdata)'s own page on 2026-11-09.
synthetic: false
tags:
- South Korea
- Stock Market
- Financial Data
- Open Data
- Dart
- kospi
- kosdaq
- konex
- Filings
- Stocks
- MCP
- Llms.txt
- OpenAPI
---
