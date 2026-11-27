---
api_specs:
- filename: futureinfra-ai-openapi-generated.yml
  format: yaml
  label: FutureInfra API
  slug: futureinfra-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/futureinfra-ai/openapi/_ae-authored/futureinfra-ai-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 이메일 주소, 비밀번호(암호화 저장), 이름 또는 조직명
  - category: device
    text: 접속 기록 IP 주소, 브라우저 정보(User-Agent), 접속 일시
  - category: financial
    text: 결제 승인 번호, 결제 수단 종류, 결제 일시
  deletion:
    route: Console or email request
    text: 콘솔에서 직접 조회·수정·탈퇴하실 수 있으며, privacy@futureinfra.ai 로 요청하셔도 지체 없이 처리합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account identification and login
    text: 회원 식별 및 로그인, 2단계 인증 등 계정 보호 서비스 제공
  - purpose: Fee calculation and billing
    text: 이용요금 산정 및 정산, 결제 처리
  - purpose: Fraud prevention and security
    text: 부정 이용 방지 및 보안 사고 대응
  residency:
  - region: Korea
    text: 클라우드 서버·도메인 등 그 밖의 기능은 국내에서만 처리되며 국외로 이전되지 않습니다.
  retention:
  - period: 회원 탈퇴 시까지
    scope: Member information
    text: 회원 정보 회원 탈퇴 시까지 서비스 제공
  - period: 3개월
    scope: Usage and access logs
    text: 서비스 이용 기록·접속 로그 3개월 통신비밀보호법
  - period: 5년
    scope: Contract or withdrawal records
    text: 계약 또는 청약철회 기록 5년 전자상거래법
  rights:
  - right: Access
    text: 개인정보 열람 요구
  - right: Correction
    text: 오류가 있을 경우 정정 요구
  - right: Deletion
    text: 삭제 요구
  - right: Restriction of processing
    text: 처리 정지 요구
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 회사는 이용자의 개인정보를 제3자에게 제공하지 않습니다. 다만 다음의 경우는 예외로 합니다.
  subprocessors:
    text: 하이온넷 서버 설비(IDC) 운영 위탁 계약 종료 시까지
    url: null
  transfers:
  - mechanism: other
    text: AI 기능을 이용하실 때, 입력하신 내용은 미국에 있는 AI 모델 제공사로 전송됩니다.
  - mechanism: other
    text: 이전 방법은 서비스 이용 시점의 네트워크 전송(HTTPS 암호화)이며
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FutureInfra
provenance_date: '2026-11-09'
provider_name: FutureInfra
provider_slug: futureinfra-ai
slug: futureinfra-ai-privacy-policy
source_date: '2026-11-09'
source_filename: futureinfra-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://futureinfra.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FutureInfra\naid: futureinfra-ai\nurl: https://futureinfra.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 이메일 주소, 비밀번호(암호화 저장), 이름 또는 조직명\n- category: device\n  text: 접속 기록 IP 주소, 브라우저 정보(User-Agent), 접속 일시\n- category: financial\n  text: 결제 승인 번호, 결제 수단 종류, 결제 일시\npurposes:\n- purpose: Account identification and login\n  text: 회원 식별 및 로그인, 2단계 인증 등 계정 보호 서비스 제공\n- purpose: Fee calculation and billing\n  text: 이용요금 산정 및 정산, 결제 처리\n- purpose: Fraud prevention and security\n  text: 부정 이용 방지 및 보안 사고 대응\nretention:\n- scope: Member\
  \ information\n  period: 회원 탈퇴 시까지\n  text: 회원 정보 회원 탈퇴 시까지 서비스 제공\n- scope: Usage and access logs\n  period: 3개월\n  text: 서비스 이용 기록·접속 로그 3개월 통신비밀보호법\n- scope: Contract or withdrawal records\n  period: 5년\n  text: 계약 또는 청약철회 기록 5년 전자상거래법\nresidency:\n- region: Korea\n  text: 클라우드 서버·도메인 등 그 밖의 기능은 국내에서만 처리되며 국외로 이전되지 않습니다.\ntransfers:\n- mechanism: other\n  text: AI 기능을 이용하실 때, 입력하신 내용은 미국에 있는 AI 모델 제공사로 전송됩니다.\n- mechanism: other\n  text: 이전 방법은 서비스 이용 시점의 네트워크 전송(HTTPS 암호화)이며\nsubprocessors:\n  url: null\n  text: 하이온넷 서버 설비(IDC) 운영 위탁 계약 종료 시까지\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Console or email request\n  text: 콘솔에서 직접 조회·수정·탈퇴하실 수 있으며, privacy@futureinfra.ai 로 요청하셔도 지체 없이 처리합니다.\nrights:\n- right: Access\n  text: 개인정보 열람 요구\n- right: Correction\n  text: 오류가 있을 경우 정정 요구\n- right: Deletion\n  text: 삭제 요구\n- right: Restriction of processing\n  text: 처리 정지 요구\nsale_or_sharing:\n  stance: conditional\n  text: 회사는 이용자의 개인정보를 제3자에게 제공하지 않습니다. 다만 다음의\
  \ 경우는 예외로 합니다.\n"
source_yaml_url: https://artifacts.apis.io/futureinfra-ai/privacy/futureinfra-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from FutureInfra's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- Infrastructure
- Artificial Intelligence
- Korean
- Platform
---
