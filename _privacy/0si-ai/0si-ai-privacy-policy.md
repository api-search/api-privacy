---
api_specs:
- filename: 0si-ai-companies-api-openapi.yml
  format: yaml
  label: 공시.ai Companies API
  slug: 0si-ai-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-companies-api-openapi.yml
- filename: 0si-ai-disclosures-api-openapi.yml
  format: yaml
  label: 공시.ai Disclosures API
  slug: 0si-ai-disclosures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-disclosures-api-openapi.yml
- filename: 0si-ai-sec-api-openapi.yml
  format: yaml
  label: 공시.ai Sec API
  slug: 0si-ai-sec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-sec-api-openapi.yml
- filename: 0si-ai-status-api-openapi.yml
  format: yaml
  label: 공시.ai Status API
  slug: 0si-ai-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-status-api-openapi.yml
- filename: 0si-ai-stream-api-openapi.yml
  format: yaml
  label: 공시.ai Stream API
  slug: 0si-ai-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-stream-api-openapi.yml
- filename: 0si-ai-usage-api-openapi.yml
  format: yaml
  label: 공시.ai Usage API
  slug: 0si-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-usage-api-openapi.yml
- filename: 0si-ai-webhooks-api-openapi.yml
  format: yaml
  label: 공시.ai Webhooks API
  slug: 0si-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0si-ai/openapi/0si-ai-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: '소셜 로그인 정보: provider, provider user ID, email, nickname, profile image'
  - category: contact
    text: '이메일: ops@0si.ai'
  - category: financial
    text: '결제 관련 정보: 인앱 결제 상품, 구독 상태, 만료 예정일, 영수증 검증 결과.'
  - category: device
    text: '기기 및 알림 정보: push token, notification permission status, device platform'
  - category: behavioral
    text: '서비스 이용 통계: 페이지 경로, 기능 상호작용, 브라우저·기기 정보, 대략적 지역, Analytics client ID'
  - category: communication
    text: '사용자 생성 정보: 댓글, 좋아요, 공유, 문의 및 문의 답변 내역'
  - category: other
    text: '운영 로그: 접속 시각, 요청 URL, IP address, user agent, 오류 로그, 보안 이벤트'
  deletion:
    route: In-app account deletion menu (내 정보 > 계정 삭제)
    text: 계정과 연결된 데이터의 삭제는 앱 내 내 정보의 계정 삭제 메뉴에서 직접 시작할 수 있습니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 회원 식별, 로그인 유지, 계정 보호
    text: 회원 식별, 로그인 유지, 계정 보호
  - purpose: 푸시 알림 및 공지
    text: 푸시 알림, 서비스 공지, 문의 답변 제공
  - purpose: 구독 및 결제 검증
    text: 구독 플랜 적용, 결제 검증, 부정 결제 방지
  - purpose: 서비스 안정성 및 보안
    text: 서비스 안정성 확보, 장애 분석, 보안 위협 및 비정상 이용 대응
  - purpose: 이용 현황 분석
    text: 서비스 화면과 기능 이용 현황 분석 및 사용성 개선
  - purpose: 마케팅 안내(동의 시)
    text: 이용자 동의가 있는 경우 기능 업데이트, 이벤트, 혜택 안내
  retention:
  - period: null
    scope: general personal data
    text: 회사는 개인정보를 처리 목적 달성에 필요한 기간 동안 보관합니다.
  - period: null
    scope: on withdrawal or purpose completion
    text: 이용자가 탈퇴하거나 처리 목적이 달성되면 지체 없이 파기하거나 복구할 수 없는 방식으로 분리 보관합니다.
  - period: null
    scope: legal/security retention
    text: 관계 법령 준수, 분쟁 대응, 부정 이용 방지를 위해 필요한 정보는 법령 또는 내부 보안 기준에 따라 필요한 기간 동안 보관할 수 있습니다.
  rights:
  - right: access
    text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.
  - right: rectification
    text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.
  - right: erasure
    text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.
  - right: restriction of processing
    text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.
  - right: withdraw consent
    text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 회사는 원칙적으로 이용자의 개인정보를 외부에 판매하지 않습니다.
  subprocessors:
    text: 'Apple, Google, Kakao: 소셜 로그인 인증'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 공시.ai
provenance_date: '2026-11-09'
provider_name: 공시.ai
provider_slug: 0si-ai
slug: 0si-ai-privacy-policy
source_date: '2026-11-09'
source_filename: 0si-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0si.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 공시.ai\naid: 0si-ai\nurl: https://0si.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: '소셜 로그인 정보: provider, provider user ID, email, nickname, profile image'\n- category: contact\n  text: '이메일: ops@0si.ai'\n- category: financial\n  text: '결제 관련 정보: 인앱 결제 상품, 구독 상태, 만료 예정일, 영수증 검증 결과.'\n- category: device\n  text: '기기 및 알림 정보: push token, notification permission status, device platform'\n- category: behavioral\n  text: '서비스 이용 통계: 페이지 경로, 기능 상호작용, 브라우저·기기 정보, 대략적 지역, Analytics client ID'\n- category: communication\n  text: '사용자\
  \ 생성 정보: 댓글, 좋아요, 공유, 문의 및 문의 답변 내역'\n- category: other\n  text: '운영 로그: 접속 시각, 요청 URL, IP address, user agent, 오류 로그, 보안 이벤트'\npurposes:\n- purpose: 회원 식별, 로그인 유지, 계정 보호\n  text: 회원 식별, 로그인 유지, 계정 보호\n- purpose: 푸시 알림 및 공지\n  text: 푸시 알림, 서비스 공지, 문의 답변 제공\n- purpose: 구독 및 결제 검증\n  text: 구독 플랜 적용, 결제 검증, 부정 결제 방지\n- purpose: 서비스 안정성 및 보안\n  text: 서비스 안정성 확보, 장애 분석, 보안 위협 및 비정상 이용 대응\n- purpose: 이용 현황 분석\n  text: 서비스 화면과 기능 이용 현황 분석 및 사용성 개선\n- purpose: 마케팅 안내(동의 시)\n  text: 이용자 동의가 있는 경우 기능 업데이트, 이벤트, 혜택 안내\nretention:\n- scope: general personal data\n  period: null\n  text: 회사는 개인정보를 처리 목적 달성에 필요한 기간 동안 보관합니다.\n- scope: on withdrawal or purpose completion\n  period: null\n  text: 이용자가 탈퇴하거나 처리 목적이 달성되면 지체 없이 파기하거나 복구할 수 없는 방식으로 분리 보관합니다.\n- scope: legal/security retention\n  period: null\n  text: 관계 법령 준수, 분쟁 대응, 부정 이용 방지를 위해 필요한 정보는 법령 또는 내부 보안 기준에 따라 필요한 기간 동안 보관할 수 있습니다.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Apple, Google, Kakao: 소셜 로그인 인증'\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion menu (내 정보 > 계정 삭제)\n  text: 계정과 연결된 데이터의 삭제는 앱 내 내 정보의 계정 삭제 메뉴에서 직접 시작할 수 있습니다.\nrights:\n- right: access\n  text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.\n- right: rectification\n  text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.\n- right: erasure\n  text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.\n- right: restriction of processing\n  text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.\n- right: withdraw consent\n  text: 이용자는 본인의 개인정보 열람, 정정, 삭제, 처리 정지, 동의 철회를 요청할 수 있습니다.\nsale_or_sharing:\n  stance: prohibited\n  text: 회사는 원칙적으로 이용자의 개인정보를 외부에 판매하지 않습니다.\n"
source_yaml_url: https://artifacts.apis.io/0si-ai/privacy/0si-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from 공시.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Filings
- South Korea
- USA
---
