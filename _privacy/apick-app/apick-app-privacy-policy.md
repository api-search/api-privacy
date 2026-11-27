---
api_specs:
- filename: apick-app-openapi-generated.yml
  format: yaml
  label: apick-app API
  slug: apick-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apick-app/openapi/_ae-authored/apick-app-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: '1. 홈페이지 회원가입 및 관리 - 필수항목: 이름, 휴대폰번호, 이메일주소, 본인확인정보(CI, DI), 신용카드결제정보, 은행계좌정보, 서비스 이용 기록, 접속 로그, 쿠키, 접속 IP 정보, 결제기록'
  - category: device
    text: 접속 로그, 쿠키, 접속 IP 정보
  - category: behavioral
    text: '서비스 개선을 위한 이용 행태 정보: 방문한 화면, 선택한 기능(버튼·링크), 화면 체류 시간, 오류 발생 여부, 접속 환경(화면 크기)'
  deletion:
    route: membership withdrawal, consent withdrawal, or purpose end
    text: 회사는 회원이 회원 탈퇴를 요청하거나, 개인정보의 수집 및 이용에 대한 동의를 철회하는 경우, 수집 및 이용목적이 달성되거나, 또는 보유 기간이 종료한 경우에 해당 개인정보를 지체 없이 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: member identification
    text: 1. 회원제 서비스 제공을 위한 본인 식별 및 인증
  - purpose: payment and settlement
    text: 4. 유료 서비스 이용 시 콘텐츠 등의 요금 결제 및 정산
  - purpose: usage statistics
    text: 6. 서비스 이용현황 통계분석 및 활용
  - purpose: marketing and personalization
    text: 10. 신규 서비스 개발 및 맞춤 서비스 제공, 기능개선, 인구통계학적 특성에 따른 서비스 제공, 각종 이벤트나 광고성 정보의 제공, 서비스의 유효성 확인, 접속 빈도 파악 또는 회원의 서비스 이용에 대한 통계 목적
  retention:
  - period: null
    scope: payment arrears or disputes
    text: '가) 해지, 탈퇴 등으로 서비스가 종료되었거나 상품 또는 서비스의 미납이 존재하는 경우 : 요금 완납 시까지'
  - period: 5년
    scope: contract and payment records
    text: 계약 또는 청약철회 등에 관한 기록/대금 결제 및 재화 등의 공급에 관한 기록 전자상거래 등에서의 소비자보호에 관한 법률 5년
  - period: 3개월
    scope: service access records
    text: 서비스 이용 관련 개인정보(서비스 접속 기록) 통신비밀보호법 3개월
  rights:
  - right: access
    text: 1. 개인정보 열람 요구
  - right: correction
    text: 2. 오류 등이 있을 경우 정정 요구
  - right: deletion
    text: 3. 삭제 요구
  - right: restriction of processing
    text: 4. 처리정지 요구
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 양질의 서비스 제공을 위해 이용자의 개인정보를 협력업체와 공유할 필요가 있는 경우에는 제공 받는 자, 제공목적, 제공정보 항목, 이용 및 보유 기간을 회원에게 고지하여 동의를 구합니다.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apick-app
provenance_date: '2026-11-09'
provider_name: apick-app
provider_slug: apick-app
slug: apick-app-privacy-policy
source_date: '2026-11-09'
source_filename: apick-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apick.app/personal_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apick-app\naid: apick-app\nurl: https://apick.app/personal_policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: '1. 홈페이지 회원가입 및 관리 - 필수항목: 이름, 휴대폰번호, 이메일주소, 본인확인정보(CI, DI), 신용카드결제정보, 은행계좌정보, 서비스 이용 기록, 접속 로그, 쿠키, 접속\n    IP 정보, 결제기록'\n- category: device\n  text: 접속 로그, 쿠키, 접속 IP 정보\n- category: behavioral\n  text: '서비스 개선을 위한 이용 행태 정보: 방문한 화면, 선택한 기능(버튼·링크), 화면 체류 시간, 오류 발생 여부, 접속 환경(화면 크기)'\npurposes:\n- purpose: member identification\n  text: 1. 회원제 서비스 제공을 위한 본인 식별 및 인증\n- purpose: payment and settlement\n  text: 4. 유료 서비스 이용 시 콘텐츠\
  \ 등의 요금 결제 및 정산\n- purpose: usage statistics\n  text: 6. 서비스 이용현황 통계분석 및 활용\n- purpose: marketing and personalization\n  text: 10. 신규 서비스 개발 및 맞춤 서비스 제공, 기능개선, 인구통계학적 특성에 따른 서비스 제공, 각종 이벤트나 광고성 정보의 제공, 서비스의 유효성 확인, 접속 빈도 파악 또는 회원의\n    서비스 이용에 대한 통계 목적\nretention:\n- scope: payment arrears or disputes\n  period: null\n  text: '가) 해지, 탈퇴 등으로 서비스가 종료되었거나 상품 또는 서비스의 미납이 존재하는 경우 : 요금 완납 시까지'\n- scope: contract and payment records\n  period: 5년\n  text: 계약 또는 청약철회 등에 관한 기록/대금 결제 및 재화 등의 공급에 관한 기록 전자상거래 등에서의 소비자보호에 관한 법률 5년\n- scope: service access records\n  period: 3개월\n  text: 서비스 이용 관련 개인정보(서비스 접속 기록) 통신비밀보호법 3개월\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: membership withdrawal, consent withdrawal, or purpose end\n  text: 회사는 회원이 회원 탈퇴를 요청하거나, 개인정보의 수집 및 이용에 대한 동의를 철회하는 경우, 수집 및 이용목적이 달성되거나, 또는 보유 기간이 종료한 경우에 해당 개인정보를 지체 없이\n    파기합니다.\nrights:\n- right: access\n  text: 1. 개인정보 열람 요구\n-\
  \ right: correction\n  text: 2. 오류 등이 있을 경우 정정 요구\n- right: deletion\n  text: 3. 삭제 요구\n- right: restriction of processing\n  text: 4. 처리정지 요구\nsale_or_sharing:\n  stance: conditional\n  text: 양질의 서비스 제공을 위해 이용자의 개인정보를 협력업체와 공유할 필요가 있는 경우에는 제공 받는 자, 제공목적, 제공정보 항목, 이용 및 보유 기간을 회원에게 고지하여 동의를 구합니다.\n"
source_yaml_url: https://artifacts.apis.io/apick-app/privacy/apick-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from apick-app's own page on 2026-11-09.
synthetic: false
tags:
- Korean
- Platform
- Data
- Services
---
