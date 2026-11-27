---
api_specs:
- filename: hanyang-oai-pmh-api-openapi.yml
  format: yaml
  label: Hanyang University OAI PMH API
  slug: hanyang-oai-pmh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hanyang/openapi/hanyang-oai-pmh-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: 계좌번호, 아이디, 사진, 전화번호, 휴대전화번호, 비상연락처, 주소, 이메일
  - category: device
    text: 이용자의 IP(Internet Protocol) 주소, 브라우저 종류 및 OS, 쿠키
  - category: behavioral
    text: 이용자의 접속 일시
  - category: financial
    text: 계좌번호, 납부금액, 대학등록금
  deletion:
    route: 개인정보 파기 절차
    text: 한양대학교는 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체 없이 해당 개인정보를 파기합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 학사업무 처리
    text: 한양대학교는 고등교육법 및 고등교육법 시행령에 따라 학사업무를 수행하기 위하여 개인정보를 처리합니다.
  - purpose: 행정업무 처리
    text: 한양대학교는 고등교육법 및 사립학교법에 따라 행정업무를 수행하기 위하여 개인정보를 처리합니다.
  - purpose: 민원사무 처리
    text: 민원인의 신원 확인, 민원사항 확인, 사실조사를 위한 연락·통지, 처리결과 통보 등의 목적으로 개인정보를 처리합니다.
  - purpose: 회원가입 및 관리
    text: 회원 유지ㆍ관리, 불량회원의 부정 이용 방지와 비인가 사용 방지
  retention:
  - period: 1년
    scope: 포털 회원 정보 (일반회원)
    text: 일반회원:1년
  - period: 준영구
    scope: 포털 회원 정보 (교직원 및 학생회원)
    text: 교직원 및 학생회원:준영구
  - period: 10년
    scope: 장학관리
    text: 10년 등록관리
  rights:
  - right: 열람
    text: 개인정보 열람요구
  - right: 정정
    text: 오류 등이 있을 경우 정정 요구
  - right: 삭제
    text: 삭제요구
  - right: 처리정지
    text: 처리정지 요구
  role:
    text: 한양대학교는 개인정보 보호법 제30조에 따라 정보주체의 개인정보를 보호하고
    value: controller
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
name: Hanyang University
provenance_date: '2026-11-09'
provider_name: Hanyang University
provider_slug: hanyang
slug: hanyang-privacy-policy
source_date: '2026-11-09'
source_filename: hanyang-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://portal.hanyang.ac.kr/PiopAct/piopMainDaepyoWeb.do
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hanyang University\naid: hanyang\nurl: https://portal.hanyang.ac.kr/PiopAct/piopMainDaepyoWeb.do\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 한양대학교는 개인정보 보호법 제30조에 따라 정보주체의 개인정보를 보호하고\ndata_categories:\n- category: contact\n  text: 계좌번호, 아이디, 사진, 전화번호, 휴대전화번호, 비상연락처, 주소, 이메일\n- category: device\n  text: 이용자의 IP(Internet Protocol) 주소, 브라우저 종류 및 OS, 쿠키\n- category: behavioral\n  text: 이용자의 접속 일시\n- category: financial\n  text: 계좌번호, 납부금액, 대학등록금\npurposes:\n- purpose: 학사업무 처리\n  text: 한양대학교는 고등교육법 및 고등교육법 시행령에 따라 학사업무를 수행하기 위하여 개인정보를 처리합니다.\n- purpose: 행정업무 처리\n  text: 한양대학교는 고등교육법 및 사립학교법에\
  \ 따라 행정업무를 수행하기 위하여 개인정보를 처리합니다.\n- purpose: 민원사무 처리\n  text: 민원인의 신원 확인, 민원사항 확인, 사실조사를 위한 연락·통지, 처리결과 통보 등의 목적으로 개인정보를 처리합니다.\n- purpose: 회원가입 및 관리\n  text: 회원 유지ㆍ관리, 불량회원의 부정 이용 방지와 비인가 사용 방지\nretention:\n- scope: 포털 회원 정보 (일반회원)\n  period: 1년\n  text: 일반회원:1년\n- scope: 포털 회원 정보 (교직원 및 학생회원)\n  period: 준영구\n  text: 교직원 및 학생회원:준영구\n- scope: 장학관리\n  period: 10년\n  text: 10년 등록관리\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 개인정보 파기 절차\n  text: 한양대학교는 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체 없이 해당 개인정보를 파기합니다.\nrights:\n- right: 열람\n  text: 개인정보 열람요구\n- right: 정정\n  text: 오류 등이 있을 경우 정정 요구\n- right: 삭제\n  text: 삭제요구\n- right: 처리정지\n  text: 처리정지 요구\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hanyang/privacy/hanyang-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from Hanyang University's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Higher Education
- University
- South Korea
- Seoul
- Research Repository
- OAI-PMH
- OAuth
- OpenAPI
- Identity Federation
- Authentication
---
