---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 주인과 화자 user_id , speaker_id
  - category: contact
    text: 수집 항목 이메일 주소, 동의 여부와 시각, 신청한 페이지 언어, 유입 출처(링크에 붙은 표시가 있을 때)
  - category: location
    text: '국가 코드(예: KR)'
  - category: behavioral
    text: '가입 뒤 대시보드에서 직접 고른 답(예: X·검색·지인 소개)'
  - category: communication
    text: 의견 종류(버그·제안·제휴 문의), 내용
  - category: other
    text: 기억 원문 content_raw
  deletion:
    route: dashboard account tab 계정 지우기
    text: 대시보드 계정 탭의 계정 지우기 에서 직접 탈퇴합니다.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: search and classification
    text: 검색·분류·관련 기억 연결
  - purpose: invitation and waitlist
    text: 창립 회원 초대 순서 안내와 초대 메일 발송
  - purpose: feedback reply and improvement
    text: 답장, 버그 수정과 서비스 개선, 제휴 검토
  residency:
  - region: Seoul (Supabase)
    text: 프로젝트는 서울 리전(ap-northeast-2)에서 운영됩니다.
  - region: Finland (Hetzner)
    text: 핀란드(헬싱키 데이터센터)
  - region: Australia (CipherStash)
    text: 호주(AWS 시드니 리전, ap-southeast-2)
  retention:
  - period: 무기한
    scope: default memory data
    text: 기본은 무기한 보존하고, 삭제는 요청에 따라 처리합니다.
  - period: 1년
    scope: feedback
    text: 처리를 마친 뒤 1년 동안 보관하고 지웁니다.
  - period: null
    scope: founding member application
    text: 가입해 계정이 만들어지거나 신청을 철회하면 지웁니다
  rights:
  - right: access
    text: 열람 memory_search , memory_card , memory_stats 로 확인합니다.
  - right: correction
    text: 정정 분류가 틀리면 memory_retag 로 태그를 고칩니다.
  - right: portability
    text: memory_export 로 본인 기억을 JSON Lines로 받습니다.
  role:
    text: 개인정보처리자는 ASR 서비스 운영자 (주)아이디오입니다.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 「개인정보 보호법」 제28조의8에 따라 알립니다.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ASR Memory
provenance_date: '2026-11-09'
provider_name: ASR Memory
provider_slug: asrmemory-com
slug: asrmemory-com-privacy-policy
source_date: '2026-11-09'
source_filename: asrmemory-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asrmemory.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ASR Memory\naid: asrmemory-com\nurl: https://asrmemory.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 개인정보처리자는 ASR 서비스 운영자 (주)아이디오입니다.\ndata_categories:\n- category: identifying\n  text: 주인과 화자 user_id , speaker_id\n- category: contact\n  text: 수집 항목 이메일 주소, 동의 여부와 시각, 신청한 페이지 언어, 유입 출처(링크에 붙은 표시가 있을 때)\n- category: location\n  text: '국가 코드(예: KR)'\n- category: behavioral\n  text: '가입 뒤 대시보드에서 직접 고른 답(예: X·검색·지인 소개)'\n- category: communication\n  text: 의견 종류(버그·제안·제휴 문의), 내용\n- category: other\n  text: 기억 원문 content_raw\npurposes:\n- purpose: search and classification\n  text:\
  \ 검색·분류·관련 기억 연결\n- purpose: invitation and waitlist\n  text: 창립 회원 초대 순서 안내와 초대 메일 발송\n- purpose: feedback reply and improvement\n  text: 답장, 버그 수정과 서비스 개선, 제휴 검토\nretention:\n- scope: default memory data\n  period: 무기한\n  text: 기본은 무기한 보존하고, 삭제는 요청에 따라 처리합니다.\n- scope: feedback\n  period: 1년\n  text: 처리를 마친 뒤 1년 동안 보관하고 지웁니다.\n- scope: founding member application\n  period: null\n  text: 가입해 계정이 만들어지거나 신청을 철회하면 지웁니다\nresidency:\n- region: Seoul (Supabase)\n  text: 프로젝트는 서울 리전(ap-northeast-2)에서 운영됩니다.\n- region: Finland (Hetzner)\n  text: 핀란드(헬싱키 데이터센터)\n- region: Australia (CipherStash)\n  text: 호주(AWS 시드니 리전, ap-southeast-2)\ntransfers:\n- mechanism: other\n  text: 「개인정보 보호법」 제28조의8에 따라 알립니다.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard account tab 계정 지우기\n  text: 대시보드 계정 탭의 계정 지우기 에서 직접 탈퇴합니다.\nrights:\n- right: access\n  text: 열람 memory_search , memory_card , memory_stats 로 확인합니다.\n- right: correction\n\
  \  text: 정정 분류가 틀리면 memory_retag 로 태그를 고칩니다.\n- right: portability\n  text: memory_export 로 본인 기억을 JSON Lines로 받습니다.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asrmemory-com/privacy/asrmemory-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from ASR Memory's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- MCP
- Servers
- Collaboration
---
