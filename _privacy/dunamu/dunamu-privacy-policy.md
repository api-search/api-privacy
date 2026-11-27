---
api_specs:
- filename: dunamu-exchange-api-openapi.yml
  format: yaml
  label: Dunamu Exchange API
  slug: dunamu-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunamu/openapi/dunamu-exchange-api-openapi.yml
- filename: dunamu-quotation-api-openapi.yml
  format: yaml
  label: Dunamu Quotation API
  slug: dunamu-quotation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dunamu/openapi/dunamu-quotation-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 이름, 휴대전화번호, 생년월일, 성별, 내/외국인 정보, 통신사, 본인확인 정보(CI,DI)
  - category: financial
    text: 디지털 자산의 거래일시, 수량, 종류, 자산명, 원화 환산금액, 입출금기록, 디지털 자산・원화 잔고, 입출금 지갑주소를 포함한 디지털 자산 거래 정보
  - category: location
    text: IP주소
  - category: device
    text: 기기정보(OS, 모델명, 통신사, 회사가 부여한 기기관리번호, 언어정보, ADID, IDFA, IDFV)
  - category: behavioral
    text: 서비스 이용기록, 쿠키
  deletion:
    route: 시스템 자동 삭제 또는 개인정보보호 책임자 등의 승인
    text: 개인정보 파기 절차는 개인정보 보유 기간의 경과, 처리목적 달성 등 파기 사유가 발생한 개인정보를 선정하고 시스템 자동 삭제 또는 개인정보보호 책임자 등의 승인을 받아 개인정보를 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 회원가입 및 관리
    text: 이용자 본인확인 및 식별, 고객확인, 이용자 정보 수정 및 관리, 각종 통지 및 고지사항 전달
  - purpose: 재화 또는 서비스 제공
    text: 디지털 자산 거래 관계 확인
  - purpose: 고충 처리
    text: 민원인의 신원 및 민원사항 확인
  - purpose: 이벤트 및 프로모션 제공
    text: 이벤트∙프로모션 정보 및 혜택, 이벤트 참여기회 제공
  retention:
  - period: 5년
    scope: 재화 또는 서비스 제공
    text: 디지털 자산 거래 등 상거래 관계 종료 후 5년.
  - period: null
    scope: 회원 가입 및 관리
    text: 디지털 자산 거래 등 상거래 관계 종료 시 삭제.
  - period: null
    scope: 이벤트 제공
    text: 해당 이벤트 종료 또는 디지털 자산 거래 등 상거래 관계 종료 시까지
  - period: 최대 26개월
    scope: 행태정보
    text: 수집일로부터 최대 26개월
  rights:
  - right: 열람·정정·삭제·처리정지
    text: 이용자는 회사에 대해 언제든지 개인정보 열람·정정·삭제·처리정지 요구 또는 개인정보 처리에 대한 동의 철회 등의 권리를 행사할 수 있습니다.
  - right: 이의신청
    text: 이용자는 열람·정정·삭제·처리정지 요구 또는 동의 철회 등에 대한 회사의 조치에 불복하는 경우 조치일로부터 10일 이내 제2항의 방법으로 이의신청을 제기할 수 있습니다.
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
    text: 회사는 서비스 제공을 위하여 개인정보 보호법 제28조의8 제1항 제3호 가목에 따라 국외업체와의 계약을 통해 개인정보 업무를 처리위탁∙보관하고 있으며
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dunamu
provenance_date: '2026-11-09'
provider_name: Dunamu
provider_slug: dunamu
slug: dunamu-privacy-policy
source_date: '2026-11-09'
source_filename: dunamu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.upbit.com/privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dunamu\naid: dunamu\nurl: https://www.upbit.com/privacy_policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 이름, 휴대전화번호, 생년월일, 성별, 내/외국인 정보, 통신사, 본인확인 정보(CI,DI)\n- category: financial\n  text: 디지털 자산의 거래일시, 수량, 종류, 자산명, 원화 환산금액, 입출금기록, 디지털 자산・원화 잔고, 입출금 지갑주소를 포함한 디지털 자산 거래 정보\n- category: location\n  text: IP주소\n- category: device\n  text: 기기정보(OS, 모델명, 통신사, 회사가 부여한 기기관리번호, 언어정보, ADID, IDFA, IDFV)\n- category: behavioral\n  text: 서비스 이용기록, 쿠키\npurposes:\n- purpose: 회원가입 및 관리\n  text: 이용자 본인확인 및 식별, 고객확인, 이용자 정보 수정 및 관리, 각종 통지 및 고지사항 전달\n\
  - purpose: 재화 또는 서비스 제공\n  text: 디지털 자산 거래 관계 확인\n- purpose: 고충 처리\n  text: 민원인의 신원 및 민원사항 확인\n- purpose: 이벤트 및 프로모션 제공\n  text: 이벤트∙프로모션 정보 및 혜택, 이벤트 참여기회 제공\nretention:\n- scope: 재화 또는 서비스 제공\n  period: 5년\n  text: 디지털 자산 거래 등 상거래 관계 종료 후 5년.\n- scope: 회원 가입 및 관리\n  period: null\n  text: 디지털 자산 거래 등 상거래 관계 종료 시 삭제.\n- scope: 이벤트 제공\n  period: null\n  text: 해당 이벤트 종료 또는 디지털 자산 거래 등 상거래 관계 종료 시까지\n- scope: 행태정보\n  period: 최대 26개월\n  text: 수집일로부터 최대 26개월\nresidency: []\ntransfers:\n- mechanism: other\n  text: 회사는 서비스 제공을 위하여 개인정보 보호법 제28조의8 제1항 제3호 가목에 따라 국외업체와의 계약을 통해 개인정보 업무를 처리위탁∙보관하고 있으며\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 시스템 자동 삭제 또는 개인정보보호 책임자 등의 승인\n  text: 개인정보 파기 절차는 개인정보 보유 기간의 경과, 처리목적 달성 등 파기 사유가 발생한 개인정보를 선정하고 시스템 자동 삭제 또는 개인정보보호 책임자 등의 승인을 받아 개인정보를 파기합니다.\nrights:\n- right: 열람·정정·삭제·처리정지\n  text: 이용자는 회사에 대해 언제든지 개인정보 열람·정정·삭제·처리정지 요구 또는 개인정보 처리에 대한 동의 철회 등의 권리를 행사할 수 있습니다.\n- right: 이의신청\n  text:\
  \ 이용자는 열람·정정·삭제·처리정지 요구 또는 동의 철회 등에 대한 회사의 조치에 불복하는 경우 조치일로부터 10일 이내 제2항의 방법으로 이의신청을 제기할 수 있습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dunamu/privacy/dunamu-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Dunamu's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Cryptocurrency
- Digital Assets
- Exchange
- Securities
- Trading
- Blockchain
- South Korea
- Company
---
