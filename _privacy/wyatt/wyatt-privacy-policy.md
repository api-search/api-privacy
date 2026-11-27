---
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 이름, 성별, 생년월일, 비밀번호, 이메일, 휴대전화
  - category: contact
    text: 주문자 정보(주문자, 이메일, 휴대전화 번호)
  - category: financial
    text: 결제 정보
  - category: behavioral
    text: 구매내역, 웹사이트 내 회원 행동데이터
  - category: device
    text: 서비스이용기록(행태정보), 접속로그, 쿠키, 접속 IP
  deletion:
    route: Company deletes data when retention period ends or purpose is achieved
    text: 회사는 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 회원 서비스 운영
    text: 회원 서비스 운영
  - purpose: 구매 주문 및 결제처리, 상품 배송
    text: 구매 주문 및 결제처리, 상품 배송
  - purpose: 맞춤형 광고 제공 및 광고 성과 측정
    text: 웹사이트 이용현황 및 구매 행동 분석, 사용자 경험 개선, 맞춤형 광고 제공 및 광고 성과 측정
  residency:
  - region: Korea (Seoul AWS region)
    text: Amazon Web Service 인프라 관리 및 데이터 보관(서울리전)
  - region: Japan (AWS Tokyo region)
    text: 일본(AWS 도쿄리전)
  retention:
  - period: 회원 탈퇴 시까지
    scope: 회원 정보
    text: 회원 탈퇴 시까지
  - period: 5년
    scope: 거래기록
    text: 거래기록이 없을 경우, 회원 탈퇴 후 30일까지 거래기록이 없을 경우 거래기록 발생 후 5년까지
  - period: 3개월
    scope: 통신비밀 보호법 로그기록
    text: 컴퓨터통신, 인터넷 로그기록자료, 접속지 추적자료 3개월
  rights:
  - right: Access, correction, deletion, restriction, withdrawal
    text: 정보주체는 회사에 대해 언제든지 개인정보 열람・정정・삭제・처리정지 및 철회 요구, 자동화된 결정에 대한 거부 또는 설명 요구 등의 권리를 행사
  - right: Withdrawal of consent via membership withdrawal
    text: 정보주체는 언제든지 ‘회원탈퇴’를 통해 개인정보의 수집 및 이용 동의 철회가 가능합니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: ② 개인정보 처리 재위탁을 받는 재수탁자와 그 업무는 아래와 같습니다.
    url: null
  transfers:
  - mechanism: other
    text: 와이어트는 「개인정보 보호법」제26조의8제1항제3호(처리 위탁 ·보관)에 따라 다음과 같이 개인정보를 국외에 이전하여 처리를 위탁하고 있습니다.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Wyatt
provenance_date: '2026-11-10'
provider_name: Wyatt
provider_slug: wyatt
slug: wyatt-privacy-policy
source_date: '2026-11-10'
source_filename: wyatt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://drforhair.co.kr/member/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Wyatt\naid: wyatt\nurl: https://drforhair.co.kr/member/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 이름, 성별, 생년월일, 비밀번호, 이메일, 휴대전화\n- category: contact\n  text: 주문자 정보(주문자, 이메일, 휴대전화 번호)\n- category: financial\n  text: 결제 정보\n- category: behavioral\n  text: 구매내역, 웹사이트 내 회원 행동데이터\n- category: device\n  text: 서비스이용기록(행태정보), 접속로그, 쿠키, 접속 IP\npurposes:\n- purpose: 회원 서비스 운영\n  text: 회원 서비스 운영\n- purpose: 구매 주문 및 결제처리, 상품 배송\n  text: 구매 주문 및 결제처리, 상품 배송\n- purpose: 맞춤형 광고 제공 및 광고 성과 측정\n  text: 웹사이트 이용현황 및 구매 행동 분석, 사용자 경험 개선,\
  \ 맞춤형 광고 제공 및 광고 성과 측정\nretention:\n- scope: 회원 정보\n  period: 회원 탈퇴 시까지\n  text: 회원 탈퇴 시까지\n- scope: 거래기록\n  period: 5년\n  text: 거래기록이 없을 경우, 회원 탈퇴 후 30일까지 거래기록이 없을 경우 거래기록 발생 후 5년까지\n- scope: 통신비밀 보호법 로그기록\n  period: 3개월\n  text: 컴퓨터통신, 인터넷 로그기록자료, 접속지 추적자료 3개월\nresidency:\n- region: Korea (Seoul AWS region)\n  text: Amazon Web Service 인프라 관리 및 데이터 보관(서울리전)\n- region: Japan (AWS Tokyo region)\n  text: 일본(AWS 도쿄리전)\ntransfers:\n- mechanism: other\n  text: 와이어트는 「개인정보 보호법」제26조의8제1항제3호(처리 위탁 ·보관)에 따라 다음과 같이 개인정보를 국외에 이전하여 처리를 위탁하고 있습니다.\nsubprocessors:\n  url: null\n  text: ② 개인정보 처리 재위탁을 받는 재수탁자와 그 업무는 아래와 같습니다.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Company deletes data when retention period ends or purpose is achieved\n  text: 회사는 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.\nrights:\n- right: Access, correction, deletion, restriction, withdrawal\n  text: 정보주체는 회사에 대해 언제든지 개인정보 열람・정정・삭제・처리정지 및 철회 요구, 자동화된 결정에 대한 거부 또는 설명 요구 등의 권리를\
  \ 행사\n- right: Withdrawal of consent via membership withdrawal\n  text: 정보주체는 언제든지 ‘회원탈퇴’를 통해 개인정보의 수집 및 이용 동의 철회가 가능합니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wyatt/privacy/wyatt-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from Wyatt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Beauty
- Personal Care
- Hair Care
- Consumer Products
- E-Commerce
- Retail
- Agentic Commerce
- MCP
- South Korea
---
