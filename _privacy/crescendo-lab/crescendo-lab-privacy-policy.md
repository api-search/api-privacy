---
api_specs:
- filename: crescendo-lab-broadcast-api-openapi.yml
  format: yaml
  label: Crescendo Lab Broadcast API
  slug: crescendo-lab-broadcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-broadcast-api-openapi.yml
- filename: crescendo-lab-contacts-api-openapi.yml
  format: yaml
  label: Crescendo Lab Contacts API
  slug: crescendo-lab-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-contacts-api-openapi.yml
- filename: crescendo-lab-sms-api-openapi.yml
  format: yaml
  label: Crescendo Lab SMS API
  slug: crescendo-lab-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-sms-api-openapi.yml
- filename: crescendo-lab-teams-api-openapi.yml
  format: yaml
  label: Crescendo Lab Teams API
  slug: crescendo-lab-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-teams-api-openapi.yml
- filename: crescendo-lab-maac-go-api-api-openapi.yml
  format: yaml
  label: Crescendo Lab MAAC Go API
  slug: crescendo-lab-maac-go-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-maac-go-api-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: 帳號資料 Email、手機、品牌名稱、時區
  - category: financial
    text: 信用卡後 4 碼、發票開立資料（統編 / 抬頭）
  - category: device
    text: IP、User-Agent、Cookie
  - category: identifying
    text: 公司登記證明、負責人或本人身分證明文件
  deletion:
    route: email legal@cresclab.com
    text: 請求刪除（法令另有保存規定或為履行契約、防詐調查所必要者除外）
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 提供 SMS 發送服務與帳號管理
    text: 提供 SMS 發送服務與帳號管理
  - purpose: 計費、發票開立、金流處理
    text: 計費、發票開立、金流處理
  - purpose: 身分驗證、反詐騙偵測及電信合規審查
    text: 身分驗證、反詐騙偵測及電信合規審查
  - purpose: 服務改善與分析（匿名化 / 去識別化後）
    text: 服務改善與分析（匿名化 / 去識別化後）
  residency:
  - region: Taiwan (asia-east1)
    text: 帳號資料、發送紀錄及身分驗證文件主要儲存於 Google Cloud 台灣區域（asia-east1）。
  retention:
  - period: 180 天
    scope: 使用紀錄 收件號碼、訊息內容及發送來源 IP
    text: 保存 180 天，屆期自動刪除（號碼僅保留前 4 碼供統計）
  - period: 7 日內輪替
    scope: 系統備份
    text: 系統備份於 7 日內輪替
  rights:
  - right: 查詢或請求閱覽
    text: 查詢或請求閱覽
  - right: 請求製給複製本
    text: 請求製給複製本
  - right: 請求補充或更正
    text: 請求補充或更正（帳號資料可於後台設定中直接修改）
  - right: 請求停止蒐集、處理或利用
    text: 請求停止蒐集、處理或利用
  - right: 請求刪除
    text: 請求刪除（法令另有保存規定或為履行契約、防詐調查所必要者除外）
  role:
    text: 本公司依中華民國《個人資料保護法》及相關法令蒐集、處理及利用您的個人資料。
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: 我們不會將您的資料販售給廣告商或第三方行銷公司。
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 為完成簡訊傳送、付款處理及電子郵件寄送，收件號碼、訊息內容、付款及聯絡資料可能傳輸至境外之服務供應商處理
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Crescendo Lab
provenance_date: '2026-11-09'
provider_name: Crescendo Lab
provider_slug: crescendo-lab
slug: crescendo-lab-privacy-policy
source_date: '2026-11-09'
source_filename: crescendo-lab-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sms.cresclab.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crescendo Lab\naid: crescendo-lab\nurl: https://sms.cresclab.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 本公司依中華民國《個人資料保護法》及相關法令蒐集、處理及利用您的個人資料。\ndata_categories:\n- category: contact\n  text: 帳號資料 Email、手機、品牌名稱、時區\n- category: financial\n  text: 信用卡後 4 碼、發票開立資料（統編 / 抬頭）\n- category: device\n  text: IP、User-Agent、Cookie\n- category: identifying\n  text: 公司登記證明、負責人或本人身分證明文件\npurposes:\n- purpose: 提供 SMS 發送服務與帳號管理\n  text: 提供 SMS 發送服務與帳號管理\n- purpose: 計費、發票開立、金流處理\n  text: 計費、發票開立、金流處理\n- purpose: 身分驗證、反詐騙偵測及電信合規審查\n  text: 身分驗證、反詐騙偵測及電信合規審查\n- purpose: 服務改善與分析（匿名化 / 去識別化後）\n\
  \  text: 服務改善與分析（匿名化 / 去識別化後）\nretention:\n- scope: 使用紀錄 收件號碼、訊息內容及發送來源 IP\n  period: 180 天\n  text: 保存 180 天，屆期自動刪除（號碼僅保留前 4 碼供統計）\n- scope: 系統備份\n  period: 7 日內輪替\n  text: 系統備份於 7 日內輪替\nresidency:\n- region: Taiwan (asia-east1)\n  text: 帳號資料、發送紀錄及身分驗證文件主要儲存於 Google Cloud 台灣區域（asia-east1）。\ntransfers:\n- mechanism: other\n  text: 為完成簡訊傳送、付款處理及電子郵件寄送，收件號碼、訊息內容、付款及聯絡資料可能傳輸至境外之服務供應商處理\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email legal@cresclab.com\n  text: 請求刪除（法令另有保存規定或為履行契約、防詐調查所必要者除外）\nrights:\n- right: 查詢或請求閱覽\n  text: 查詢或請求閱覽\n- right: 請求製給複製本\n  text: 請求製給複製本\n- right: 請求補充或更正\n  text: 請求補充或更正（帳號資料可於後台設定中直接修改）\n- right: 請求停止蒐集、處理或利用\n  text: 請求停止蒐集、處理或利用\n- right: 請求刪除\n  text: 請求刪除（法令另有保存規定或為履行契約、防詐調查所必要者除外）\nsale_or_sharing:\n  stance: prohibited\n  text: 我們不會將您的資料販售給廣告商或第三方行銷公司。\n"
source_yaml_url: https://artifacts.apis.io/crescendo-lab/privacy/crescendo-lab-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Crescendo Lab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- Messaging
- Marketing Automation
- Customer Engagement
- Taiwan
- Omnichannel
- MCP
---
