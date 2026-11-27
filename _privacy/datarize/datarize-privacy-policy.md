---
api_specs:
- filename: datarize-openapi-generated.yml
  format: yaml
  label: Datarize API
  slug: datarize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarize/openapi/_ae-authored/datarize-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 성명, 아이디, 비밀번호, 전화번호, 이메일 주소
  - category: financial
    text: 신용카드번호, 은행계좌정보
  - category: device
    text: IP주소, 쿠키, 광고 식별자(ADID/IDFA), MAC주소, 서비스 이용기록, 방문기록
  - category: behavioral
    text: 쿠키, 광고 식별자(ADID/IDFA) 등 온라인 식별자에 기반한 웹사이트 방문 및 탐색 이력, 콘텐츠 조회 이력
  - category: identifying
    text: 본인확인식별값(CI), 본인확인 일시. 다만, 중복가입확인정보(DI)는 수집하지 아니합니다.
  deletion:
    route: 보유기간 경과 또는 처리목적 달성 시 지체없이 파기; 개인정보보호책임자에게 문의
    text: 회사는 개인정보 보유기간의 경과, 처리목적의 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 회원 가입 및 관리
    text: 홈페이지 회원 가입 및 관리
  - purpose: 서비스 제공
    text: 서비스 제공, 계약서·청구서 발송, 콘텐츠 제공, 맞춤서비스 제공, 본인인증, 연령인증, 요금결제·정산, 채권추심을 목적으로 개인정보를 처리합니다.
  - purpose: 마케팅 및 광고
    text: 광고 및 마케팅 목적의 활용, 고객 분석, 설문조사 등 서비스 개선을 위한 활용
  - purpose: 맞춤형 광고 및 행태정보 분석
    text: 이용자의 관심에 기반한 맞춤형 서비스 제공, 광고 집행 및 성과 분석
  residency:
  - region: 대한민국 (서울 리전)
    text: 데이터 저장·처리 및 분석 Snowflake Computing Netherlands B.V. 데이터의 저장·처리 및 분석 (대한민국 서울 리전)
  retention:
  - period: 사업자/단체 홈페이지 탈퇴 시까지
    scope: 회원 가입 및 관리
    text: '홈페이지 회원 가입 및 관리: 사업자/단체 홈페이지 탈퇴 시까지.'
  - period: 동의일로부터 3년까지
    scope: 마케팅 목적 활용, 광고성 메시지 발송
    text: '마케팅 목적의 활용, 광고성 메시지 발송: 동의일로부터 3년까지, 또는 개인정보 수집 시 정보주체로부터 동의를 받은 기간 동안'
  - period: null
    scope: 행태정보
    text: 수집·이용 목적 달성 시 지체 없이 파기 (법령에서 정하는 경우 해당 기간까지 보유)
  - period: 30일 이내
    scope: 국외이전 자료(Anthropic)
    text: 이전받는 자가 수신 또는 생성 후 30일 이내 파기(법령상 보존이 요구되는 경우 등은 예외).
  rights:
  - right: 열람·정정·삭제·처리정지
    text: 정보주체는 회사에 대해 언제든지 개인정보 열람·정정·삭제·처리정지 요구 등의 권리를 행사할 수 있습니다.
  - right: 국외이전 거부
    text: 정보주체는 제1항 제②호의 개인정보 국외이전에 대하여 거부할 수 있습니다.
  - right: 쿠키 및 행태정보 거부
    text: 웹 브라우저 또는 모바일 브라우저의 설정을 통하여 쿠키에 저장된 정보를 삭제하거나 쿠키의 저장을 차단할 수 있습니다.
  role:
    text: 회사는 회원(고객사)으로부터 개인정보 처리업무를 위탁 받아 수탁자의 지위에서 이를 처리할 수 있습니다.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: '미합중국 서비스 이용 시 네트워크를 통해 이전 이메일, 고객 DB 이전 목적: 광고 집행'
  - mechanism: other
    text: 미합중국 발신번호 사전등록 증빙서류 처리 시 네트워크를 통해 이전
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Datarize
provenance_date: '2026-11-09'
provider_name: Datarize
provider_slug: datarize
slug: datarize-privacy-policy
source_date: '2026-11-09'
source_filename: datarize-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policy.datarize.ai/ko/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Datarize\naid: datarize\nurl: https://policy.datarize.ai/ko/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 회사는 회원(고객사)으로부터 개인정보 처리업무를 위탁 받아 수탁자의 지위에서 이를 처리할 수 있습니다.\ndata_categories:\n- category: identifying\n  text: 성명, 아이디, 비밀번호, 전화번호, 이메일 주소\n- category: financial\n  text: 신용카드번호, 은행계좌정보\n- category: device\n  text: IP주소, 쿠키, 광고 식별자(ADID/IDFA), MAC주소, 서비스 이용기록, 방문기록\n- category: behavioral\n  text: 쿠키, 광고 식별자(ADID/IDFA) 등 온라인 식별자에 기반한 웹사이트 방문 및 탐색 이력, 콘텐츠 조회 이력\n- category: identifying\n  text: 본인확인식별값(CI), 본인확인 일시. 다만, 중복가입확인정보(DI)는 수집하지 아니합니다.\npurposes:\n- purpose: 회원 가입 및 관리\n  text:\
  \ 홈페이지 회원 가입 및 관리\n- purpose: 서비스 제공\n  text: 서비스 제공, 계약서·청구서 발송, 콘텐츠 제공, 맞춤서비스 제공, 본인인증, 연령인증, 요금결제·정산, 채권추심을 목적으로 개인정보를 처리합니다.\n- purpose: 마케팅 및 광고\n  text: 광고 및 마케팅 목적의 활용, 고객 분석, 설문조사 등 서비스 개선을 위한 활용\n- purpose: 맞춤형 광고 및 행태정보 분석\n  text: 이용자의 관심에 기반한 맞춤형 서비스 제공, 광고 집행 및 성과 분석\nretention:\n- scope: 회원 가입 및 관리\n  period: 사업자/단체 홈페이지 탈퇴 시까지\n  text: '홈페이지 회원 가입 및 관리: 사업자/단체 홈페이지 탈퇴 시까지.'\n- scope: 마케팅 목적 활용, 광고성 메시지 발송\n  period: 동의일로부터 3년까지\n  text: '마케팅 목적의 활용, 광고성 메시지 발송: 동의일로부터 3년까지, 또는 개인정보 수집 시 정보주체로부터 동의를 받은 기간 동안'\n- scope: 행태정보\n  period: null\n  text: 수집·이용 목적 달성 시 지체 없이 파기 (법령에서 정하는 경우 해당 기간까지 보유)\n- scope: 국외이전 자료(Anthropic)\n  period: 30일 이내\n  text: 이전받는 자가 수신 또는 생성 후 30일 이내 파기(법령상 보존이 요구되는 경우 등은 예외).\nresidency:\n- region: 대한민국 (서울 리전)\n  text: 데이터 저장·처리 및 분석 Snowflake Computing Netherlands B.V. 데이터의 저장·처리 및 분석 (대한민국 서울 리전)\ntransfers:\n- mechanism: other\n  text: '미합중국 서비스 이용 시 네트워크를 통해 이전 이메일, 고객 DB 이전 목적: 광고 집행'\n- mechanism: other\n  text: 미합중국 발신번호 사전등록 증빙서류 처리 시 네트워크를\
  \ 통해 이전\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 보유기간 경과 또는 처리목적 달성 시 지체없이 파기; 개인정보보호책임자에게 문의\n  text: 회사는 개인정보 보유기간의 경과, 처리목적의 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.\nrights:\n- right: 열람·정정·삭제·처리정지\n  text: 정보주체는 회사에 대해 언제든지 개인정보 열람·정정·삭제·처리정지 요구 등의 권리를 행사할 수 있습니다.\n- right: 국외이전 거부\n  text: 정보주체는 제1항 제②호의 개인정보 국외이전에 대하여 거부할 수 있습니다.\n- right: 쿠키 및 행태정보 거부\n  text: 웹 브라우저 또는 모바일 브라우저의 설정을 통하여 쿠키에 저장된 정보를 삭제하거나 쿠키의 저장을 차단할 수 있습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datarize/privacy/datarize-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from Datarize's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Analytics
- API Platform
- Enterprise
---
