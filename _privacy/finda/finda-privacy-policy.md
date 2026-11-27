---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 성명, 휴대전화번호, 생년월일, 내외국인정보, 통신사정보, 성별, CI, DI, PIN번호
  - category: financial
    text: 고객 신용정보 내역(신용점수, 대출현황, 연체현황, 채무불이행 현황)
  - category: financial
    text: 국민건강보험공단 정보(건강보험자격확인(통보)서, 건강보험자격득실확인서, 건강보험료납부확인서)
  - category: device
    text: 유저 아이디, 암호화 CI[복호화가 불가능한 일방향 암호화(해시)하여 보관], 모바일기기OS 정보, 디바이스 정보, 핀다앱 버전 정보, IP, 부정이용기록
  - category: contact
    text: 고객 문의 성명, 휴대전화번호, userid, 문의 및 상담내용
  - category: professional
    text: 연소득, 소득구분, 고용형태, 가입의료보험 종류, 근무입사일/개업일
  - category: location
    text: 주거형태, 거주정보, 소유차량정보, 개인회생여부 주택담보정보, 전세계약정보
  deletion:
    route: 핀다앱 내 전체(≡) > 설정 > 회원탈퇴
    text: '회원 탈퇴 : 핀다앱 내 전체(≡) > 설정 > 회원탈퇴를 통해 탈퇴 가능합니다.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 회원 가입 및 핀다서비스 제공
    text: 회원 가입 및 핀다서비스 제공
  - purpose: 대출모집서비스
    text: 비교대출서비스 제공 및 수수료 정산
  - purpose: 홍보 및 마케팅
    text: 핀다 및 제휴사의 서비스에 대한 앱푸시, 문자, 메세지 등 광고 발송
  - purpose: AI 대출예측
    text: 고객정보 분석을 통한 대출 조건 예측 및 맞춤형 대출 상품 추천 서비스
  retention:
  - period: 1년간
    scope: 회원 가입 및 핀다서비스 제공 (부정이용기록 등)
    text: 부정사용행위 확인 및 방지를 위해 회원탈퇴 후 1년간 보관
  - period: 회원탈퇴 시까지
    scope: 신용관리서비스
    text: 신용관리서비스 회원탈퇴 시까지
  - period: 5년
    scope: 전자상거래 계약 또는 청약철회 기록
    text: 계약 또는 청약철회 등에 관한 기록 소비자의 불만 또는 분쟁처리에 관한 기록 대금 결제 및 재화 등의 공급에 관한 기록 5년 3년 5년
  - period: 3개월
    scope: 로그인 기록(통신비밀 보호법)
    text: 로그인 기록(로그기록 자료, 접속자의 추적 자료) 3개월
  - period: 경품 지급 완료일로부터 30일까지
    scope: 이벤트 경품 제세공과금 처리
    text: 경품 지급 완료일로부터 30일까지 (단, 관련 법령상 보관 의무가 있는 경우 해당 기간까지)
  rights:
  - right: 열람, 삭제, 처리정지 요구
    text: '개인(신용)정보의 열람, 삭제, 처리 정지 요구 : 핀다앱 내 전체(≡) > 1:1 채팅 문의를 통해 청구를 하실 수 있습니다.'
  - right: 수정
    text: '개인(신용)정보의 수정 : 핀다앱 내 전체(≡) > 설정 > 내 정보를 통해 수정 하실 수 있습니다.'
  - right: 마이데이터 연결 해지
    text: '마이데이터 서비스 연결 해지 : 핀다앱 내 전체(≡) > 설정 > 마이데이터 연결 내역 관리 > 연결 해지 및 데이터 삭제를 통해 연결 해지 및 데이터 삭제가 가능합니다.'
  - right: 이용·제공 사실 조회
    text: '개인(신용)정보 이용·제공 사실 조회 : 핀다앱 내 전체(≡) > 설정 > 개인신용정보 이용/제공 내역 조회를 통해 조회할 수 있습니다.'
  role:
    text: 주식회사 핀다(이하 "회사" 또는 "핀다"라 함)는 이용자의 신용정보를 포함한 개인정보
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
name: Finda
provenance_date: '2026-11-09'
provider_name: Finda
provider_slug: finda
slug: finda-privacy-policy
source_date: '2026-11-09'
source_filename: finda-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://finda.co.kr/terms/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Finda\naid: finda\nurl: https://finda.co.kr/terms/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 주식회사 핀다(이하 \"회사\" 또는 \"핀다\"라 함)는 이용자의 신용정보를 포함한 개인정보\ndata_categories:\n- category: identifying\n  text: 성명, 휴대전화번호, 생년월일, 내외국인정보, 통신사정보, 성별, CI, DI, PIN번호\n- category: financial\n  text: 고객 신용정보 내역(신용점수, 대출현황, 연체현황, 채무불이행 현황)\n- category: financial\n  text: 국민건강보험공단 정보(건강보험자격확인(통보)서, 건강보험자격득실확인서, 건강보험료납부확인서)\n- category: device\n  text: 유저 아이디, 암호화 CI[복호화가 불가능한 일방향 암호화(해시)하여 보관], 모바일기기OS 정보, 디바이스 정보, 핀다앱 버전 정보, IP, 부정이용기록\n- category: contact\n  text: 고객 문의 성명, 휴대전화번호, userid, 문의 및 상담내용\n\
  - category: professional\n  text: 연소득, 소득구분, 고용형태, 가입의료보험 종류, 근무입사일/개업일\n- category: location\n  text: 주거형태, 거주정보, 소유차량정보, 개인회생여부 주택담보정보, 전세계약정보\npurposes:\n- purpose: 회원 가입 및 핀다서비스 제공\n  text: 회원 가입 및 핀다서비스 제공\n- purpose: 대출모집서비스\n  text: 비교대출서비스 제공 및 수수료 정산\n- purpose: 홍보 및 마케팅\n  text: 핀다 및 제휴사의 서비스에 대한 앱푸시, 문자, 메세지 등 광고 발송\n- purpose: AI 대출예측\n  text: 고객정보 분석을 통한 대출 조건 예측 및 맞춤형 대출 상품 추천 서비스\nretention:\n- scope: 회원 가입 및 핀다서비스 제공 (부정이용기록 등)\n  period: 1년간\n  text: 부정사용행위 확인 및 방지를 위해 회원탈퇴 후 1년간 보관\n- scope: 신용관리서비스\n  period: 회원탈퇴 시까지\n  text: 신용관리서비스 회원탈퇴 시까지\n- scope: 전자상거래 계약 또는 청약철회 기록\n  period: 5년\n  text: 계약 또는 청약철회 등에 관한 기록 소비자의 불만 또는 분쟁처리에 관한 기록 대금 결제 및 재화 등의 공급에 관한 기록 5년 3년 5년\n- scope: 로그인 기록(통신비밀 보호법)\n  period: 3개월\n  text: 로그인 기록(로그기록 자료, 접속자의 추적 자료) 3개월\n- scope: 이벤트 경품 제세공과금 처리\n  period: 경품 지급 완료일로부터 30일까지\n  text: 경품 지급 완료일로부터 30일까지 (단, 관련 법령상 보관 의무가 있는 경우 해당 기간까지)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: 핀다앱 내 전체(≡) > 설정 > 회원탈퇴\n  text: '회원 탈퇴 : 핀다앱 내 전체(≡) > 설정 > 회원탈퇴를 통해 탈퇴 가능합니다.'\nrights:\n- right: 열람, 삭제, 처리정지 요구\n  text: '개인(신용)정보의 열람, 삭제, 처리 정지 요구 : 핀다앱 내 전체(≡) > 1:1 채팅 문의를 통해 청구를 하실 수 있습니다.'\n- right: 수정\n  text: '개인(신용)정보의 수정 : 핀다앱 내 전체(≡) > 설정 > 내 정보를 통해 수정 하실 수 있습니다.'\n- right: 마이데이터 연결 해지\n  text: '마이데이터 서비스 연결 해지 : 핀다앱 내 전체(≡) > 설정 > 마이데이터 연결 내역 관리 > 연결 해지 및 데이터 삭제를 통해 연결 해지 및 데이터 삭제가 가능합니다.'\n- right: 이용·제공 사실 조회\n  text: '개인(신용)정보 이용·제공 사실 조회 : 핀다앱 내 전체(≡) > 설정 > 개인신용정보 이용/제공 내역 조회를 통해 조회할 수 있습니다.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finda/privacy/finda-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 22 quoted statements, read from Finda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Loans
- Lending
- Loan Comparison
- Personal Finance
- Credit
- South Korea
---
