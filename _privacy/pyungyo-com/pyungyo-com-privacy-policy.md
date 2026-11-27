---
api_specs:
- filename: pyungyo-com-carriers-api-openapi.yml
  format: yaml
  label: pyungyo-com Carriers API
  slug: pyungyo-com-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-carriers-api-openapi.yml
- filename: pyungyo-com-changes-api-openapi.yml
  format: yaml
  label: pyungyo-com Changes API
  slug: pyungyo-com-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-changes-api-openapi.yml
- filename: pyungyo-com-cheapest-api-openapi.yml
  format: yaml
  label: pyungyo-com Cheapest API
  slug: pyungyo-com-cheapest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-cheapest-api-openapi.yml
- filename: pyungyo-com-index-api-openapi.yml
  format: yaml
  label: pyungyo-com Index API
  slug: pyungyo-com-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-index-api-openapi.yml
- filename: pyungyo-com-meta-api-openapi.yml
  format: yaml
  label: pyungyo-com Meta API
  slug: pyungyo-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-meta-api-openapi.yml
- filename: pyungyo-com-plans-api-openapi.yml
  format: yaml
  label: pyungyo-com Plans API
  slug: pyungyo-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-plans-api-openapi.yml
- filename: pyungyo-com-search-api-openapi.yml
  format: yaml
  label: pyungyo-com Search API
  slug: pyungyo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-search-api-openapi.yml
- filename: pyungyo-com-ssal-api-openapi.yml
  format: yaml
  label: pyungyo-com Ssal API
  slug: pyungyo-com-ssal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-ssal-api-openapi.yml
- filename: pyungyo-com-stats-api-openapi.yml
  format: yaml
  label: pyungyo-com Stats API
  slug: pyungyo-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyungyo-com/openapi/pyungyo-com-stats-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: '토스 이용자 식별값(userKey): 토스 로그인 후 토스가 이 서비스에만 발급하는 숫자로, 이 값으로 알림을 보냅니다.'
  - category: behavioral
    text: '알림 신청 내용: 알림을 건 요금제 이름·통신사, 이용자가 달력에서 고른 날짜, 알림 발송 결과(보낸 시각·실패 사유).'
  - category: device
    text: '접속 기록: 요금제 자료를 받아 갈 때 IP 주소, 접속 시각, 요청한 주소, 브라우저·기기 종류가 서버 기록에 남습니다.'
  - category: other
    text: '요금제 질문 게시판(웹 pyungyo.com/qna, 선택): 이용자가 직접 쓴 제목·내용·닉네임, 글에 단 요금제 카드(요금제 번호·그때 월 요금), 쓴 시각, 지울 때 쓸 비밀번호(되돌릴 수 없게 바꾼 값)만 저장합니다.'
  deletion:
    route: Email the operator at wmask@naver.com to request access or deletion of stored notification information
    text: 보관 중인 내 알림 정보의 열람·삭제를 원하시면 wmask@naver.com로 알려 주세요.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 요금제 정보 제공과 화면 표시, 알림 발송, 장애 대응, 차단, 이용 통계
    text: 요금제 정보 제공과 화면 표시, 이용자가 신청한 날짜에 토스 알림 보내기(7일 전·3일 전·당일), 장애 대응, 비정상 접근·과도한 요청 차단, 이용 통계.
  residency:
  - region: South Korea
    text: '클라우드 서버 호스팅 사업자(대한민국): 서버 운영, 알림 신청 내용 보관'
  retention:
  - period: 7일
    scope: 알림 신청 내용과 토스 이용자 식별값
    text: 고른 날짜의 당일 알림을 보낸 뒤 7일이 지나면 지웁니다.
  - period: 14일
    scope: 접속 기록
    text: 접속 기록은 14일이 지나면 자동으로 지워집니다.
  - period: 30일
    scope: 요금제 질문 게시판 글
    text: 신고·분쟁 처리를 위해 30일 뒤 제목·내용·닉네임·비밀번호 값까지 지웁니다.
  - period: 3개월
    scope: 포인트 이벤트 참여 기록
    text: 이벤트 종료 후 3개월 뒤 파기
  rights:
  - right: Access and deletion of stored notification information
    text: 보관 중인 내 알림 정보의 열람·삭제를 원하시면 wmask@naver.com로 알려 주세요.
  - right: Change or cancel notification date
    text: 알림은 상세 화면에서 언제든 날짜를 바꾸거나 취소할 수 있습니다.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 수집한 정보를 다른 사람이나 회사에 제공하거나 판매하지 않습니다.
  subprocessors:
    text: 서비스 운영을 위해 아래 사업자의 설비를 이용합니다.
    url: null
  transfers:
  - mechanism: other
    text: 'Google LLC(미국): 안드로이드 앱에서 한정 요금제 알림을 켠 경우 그 알림 전달(Firebase 클라우드 메시징).'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pyungyo-com
provenance_date: '2026-11-10'
provider_name: pyungyo-com
provider_slug: pyungyo-com
slug: pyungyo-com-privacy-policy
source_date: '2026-11-10'
source_filename: pyungyo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pyungyo.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pyungyo-com\naid: pyungyo-com\nurl: https://pyungyo.com/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: '토스 이용자 식별값(userKey): 토스 로그인 후 토스가 이 서비스에만 발급하는 숫자로, 이 값으로 알림을 보냅니다.'\n- category: behavioral\n  text: '알림 신청 내용: 알림을 건 요금제 이름·통신사, 이용자가 달력에서 고른 날짜, 알림 발송 결과(보낸 시각·실패 사유).'\n- category: device\n  text: '접속 기록: 요금제 자료를 받아 갈 때 IP 주소, 접속 시각, 요청한 주소, 브라우저·기기 종류가 서버 기록에 남습니다.'\n- category: other\n  text: '요금제 질문 게시판(웹 pyungyo.com/qna, 선택): 이용자가 직접 쓴 제목·내용·닉네임, 글에 단 요금제 카드(요금제 번호·그때 월 요금), 쓴 시각, 지울 때 쓸 비밀번호(되돌릴\n    수 없게 바꾼 값)만\
  \ 저장합니다.'\npurposes:\n- purpose: 요금제 정보 제공과 화면 표시, 알림 발송, 장애 대응, 차단, 이용 통계\n  text: 요금제 정보 제공과 화면 표시, 이용자가 신청한 날짜에 토스 알림 보내기(7일 전·3일 전·당일), 장애 대응, 비정상 접근·과도한 요청 차단, 이용 통계.\nretention:\n- scope: 알림 신청 내용과 토스 이용자 식별값\n  period: 7일\n  text: 고른 날짜의 당일 알림을 보낸 뒤 7일이 지나면 지웁니다.\n- scope: 접속 기록\n  period: 14일\n  text: 접속 기록은 14일이 지나면 자동으로 지워집니다.\n- scope: 요금제 질문 게시판 글\n  period: 30일\n  text: 신고·분쟁 처리를 위해 30일 뒤 제목·내용·닉네임·비밀번호 값까지 지웁니다.\n- scope: 포인트 이벤트 참여 기록\n  period: 3개월\n  text: 이벤트 종료 후 3개월 뒤 파기\nresidency:\n- region: South Korea\n  text: '클라우드 서버 호스팅 사업자(대한민국): 서버 운영, 알림 신청 내용 보관'\ntransfers:\n- mechanism: other\n  text: 'Google LLC(미국): 안드로이드 앱에서 한정 요금제 알림을 켠 경우 그 알림 전달(Firebase 클라우드 메시징).'\nsubprocessors:\n  url: null\n  text: 서비스 운영을 위해 아래 사업자의 설비를 이용합니다.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the operator at wmask@naver.com to request access or deletion of stored notification information\n  text: 보관 중인 내 알림 정보의 열람·삭제를 원하시면 wmask@naver.com로 알려 주세요.\n\
  rights:\n- right: Access and deletion of stored notification information\n  text: 보관 중인 내 알림 정보의 열람·삭제를 원하시면 wmask@naver.com로 알려 주세요.\n- right: Change or cancel notification date\n  text: 알림은 상세 화면에서 언제든 날짜를 바꾸거나 취소할 수 있습니다.\nsale_or_sharing:\n  stance: prohibited\n  text: 수집한 정보를 다른 사람이나 회사에 제공하거나 판매하지 않습니다.\n"
source_yaml_url: https://artifacts.apis.io/pyungyo-com/privacy/pyungyo-com-privacy-policy.yml
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
summary_line: 16 quoted statements, read from pyungyo-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- Mobile
- South Korea
- Price Comparison
- OpenAPI
---
