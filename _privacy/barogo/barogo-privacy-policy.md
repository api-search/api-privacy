---
api_specs:
- filename: barogo-areas-api-openapi.yml
  format: yaml
  label: Barogo Areas API
  slug: barogo-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-areas-api-openapi.yml
- filename: barogo-delivery-api-openapi.yml
  format: yaml
  label: Barogo Delivery API
  slug: barogo-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-delivery-api-openapi.yml
- filename: barogo-deposits-api-openapi.yml
  format: yaml
  label: Barogo Deposits API
  slug: barogo-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-deposits-api-openapi.yml
- filename: barogo-orders-api-openapi.yml
  format: yaml
  label: Barogo Orders API
  slug: barogo-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-orders-api-openapi.yml
- filename: barogo-stores-api-openapi.yml
  format: yaml
  label: Barogo Stores API
  slug: barogo-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-stores-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 이름, 연락처(전화, 휴대전화번호), 이메일, 문의사항
  - category: identifying
    text: 이름, 생년월일, 연락처(전화, 휴대전화번호), 배달경험, 희망 근무 시간, 바이크 보유 여부, 희망 근무 지역
  - category: identifying
    text: 사업주(대표자)의 주민등록번호
  - category: financial
    text: 예금주명, 은행명, 계좌번호, 가상 계좌번호, 가장계좌 예금주
  - category: device
    text: 라이더 앱 이름, 휴대폰번호, 생년월일,닉네임, CI, 아이디, 비밀번호
  - category: communication
    text: 상담내용(상담원, 정보주체 녹취음성 및 내용)
  - category: behavioral
    text: Google Analytics를 통하여 당사 서비스 이용자의 행태정보를 수집하게 되며
  deletion:
    route: null
    text: 회사는 원칙적으로 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 서비스 가입 의사확인, 문의사항처리
    text: 서비스 가입 의사확인, 문의사항처리
  - purpose: 고용 알선 / 채용 절차
    text: 지원 의사 확인, 고용 알선
  - purpose: 배달대행 업무의 수행 및 정산
    text: 배달대행 업무의 수행 및 정산
  - purpose: 고객 서비스 이용 및 상담
    text: 고객 서비스 이용 및 상담
  - purpose: 이벤트 및 마케팅
    text: 이벤트 및 마케팅 (필수)
  - purpose: 서비스 이용 통계 분석
    text: 회사는 서비스 이용 통계 분석을 목적으로 구글(Google)에서 제공하는 로그 분석 툴인 Google Analytics를 사용하고 있습니다.
  retention:
  - period: 문의 종료일로부터 1년간
    scope: 일반 문의
    text: 문의 종료일로부터 1년간
  - period: 종료일로부터 1년간 또는 동의 철회 시
    scope: 채용 절차 (라이더 지원)
    text: 종료일로부터 1년간 또는 동의 철회 시
  - period: 3년
    scope: 고객 센터 상담
    text: 고객 서비스 이용 및 상담 3년(전자상거래법 제6조)
  - period: 로그아웃(퇴근) 후 즉시 파기
    scope: 위치정보 처리
    text: 로그아웃(퇴근) 후 즉시 파기.
  - period: 3개월
    scope: 서비스 이용에 관한 로그기록
    text: 통신비밀보호법 서비스 이용에 관한 로그기록 3개월
  rights:
  - right: 열람·정정·삭제·처리정지
    text: 이용자는 회사에 대하여 언제든지 자신의 개인정보를 열람·정정·삭제·처리정지 요구 등의 권리를 행사할 수 있습니다.
  - right: 대리인을 통한 권리 행사
    text: 권리 행사는 이용자의 법정대리인이나 위임을 받은 자 등 대리인을 통하여 하실 수도 있습니다.
  - right: 쿠키 거부
    text: 웹브라우저에서 옵션을 설정함으로써 모든 쿠키를 허용하거나, 쿠키가 저장될 때마다 확인을 거치거나, 아니면 모든 쿠키의 저장을 거부할 수도 있습니다.
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
name: Barogo
provenance_date: '2026-11-09'
provider_name: Barogo
provider_slug: barogo
slug: barogo-privacy-policy
source_date: '2026-11-09'
source_filename: barogo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.barogo.com/policy/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Barogo\naid: barogo\nurl: https://www.barogo.com/policy/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 이름, 연락처(전화, 휴대전화번호), 이메일, 문의사항\n- category: identifying\n  text: 이름, 생년월일, 연락처(전화, 휴대전화번호), 배달경험, 희망 근무 시간, 바이크 보유 여부, 희망 근무 지역\n- category: identifying\n  text: 사업주(대표자)의 주민등록번호\n- category: financial\n  text: 예금주명, 은행명, 계좌번호, 가상 계좌번호, 가장계좌 예금주\n- category: device\n  text: 라이더 앱 이름, 휴대폰번호, 생년월일,닉네임, CI, 아이디, 비밀번호\n- category: communication\n  text: 상담내용(상담원, 정보주체 녹취음성 및 내용)\n- category: behavioral\n  text: Google Analytics를 통하여 당사\
  \ 서비스 이용자의 행태정보를 수집하게 되며\npurposes:\n- purpose: 서비스 가입 의사확인, 문의사항처리\n  text: 서비스 가입 의사확인, 문의사항처리\n- purpose: 고용 알선 / 채용 절차\n  text: 지원 의사 확인, 고용 알선\n- purpose: 배달대행 업무의 수행 및 정산\n  text: 배달대행 업무의 수행 및 정산\n- purpose: 고객 서비스 이용 및 상담\n  text: 고객 서비스 이용 및 상담\n- purpose: 이벤트 및 마케팅\n  text: 이벤트 및 마케팅 (필수)\n- purpose: 서비스 이용 통계 분석\n  text: 회사는 서비스 이용 통계 분석을 목적으로 구글(Google)에서 제공하는 로그 분석 툴인 Google Analytics를 사용하고 있습니다.\nretention:\n- scope: 일반 문의\n  period: 문의 종료일로부터 1년간\n  text: 문의 종료일로부터 1년간\n- scope: 채용 절차 (라이더 지원)\n  period: 종료일로부터 1년간 또는 동의 철회 시\n  text: 종료일로부터 1년간 또는 동의 철회 시\n- scope: 고객 센터 상담\n  period: 3년\n  text: 고객 서비스 이용 및 상담 3년(전자상거래법 제6조)\n- scope: 위치정보 처리\n  period: 로그아웃(퇴근) 후 즉시 파기\n  text: 로그아웃(퇴근) 후 즉시 파기.\n- scope: 서비스 이용에 관한 로그기록\n  period: 3개월\n  text: 통신비밀보호법 서비스 이용에 관한 로그기록 3개월\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: 회사는 원칙적으로 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가\
  \ 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.\nrights:\n- right: 열람·정정·삭제·처리정지\n  text: 이용자는 회사에 대하여 언제든지 자신의 개인정보를 열람·정정·삭제·처리정지 요구 등의 권리를 행사할 수 있습니다.\n- right: 대리인을 통한 권리 행사\n  text: 권리 행사는 이용자의 법정대리인이나 위임을 받은 자 등 대리인을 통하여 하실 수도 있습니다.\n- right: 쿠키 거부\n  text: 웹브라우저에서 옵션을 설정함으로써 모든 쿠키를 허용하거나, 쿠키가 저장될 때마다 확인을 거치거나, 아니면 모든 쿠키의 저장을 거부할 수도 있습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/barogo/privacy/barogo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 22 quoted statements, read from Barogo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Delivery
- Logistics
- Last Mile Delivery
- Food Delivery
- Couriers
- Fulfillment
- Order
- Webhook
- South Korea
- Transportation
- Marketplace
---
