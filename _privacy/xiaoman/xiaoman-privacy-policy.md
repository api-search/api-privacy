---
api_specs:
- filename: xiaoman-companies-api-openapi.yml
  format: yaml
  label: OKKI Go Companies API
  slug: xiaoman-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-companies-api-openapi.yml
- filename: xiaoman-contacts-api-openapi.yml
  format: yaml
  label: OKKI Go Contacts API
  slug: xiaoman-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-contacts-api-openapi.yml
- filename: xiaoman-credits-api-openapi.yml
  format: yaml
  label: OKKI Go Credits API
  slug: xiaoman-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-credits-api-openapi.yml
- filename: xiaoman-default-api-openapi.yml
  format: yaml
  label: Xiaoman (OKKI CRM) 产品 API
  slug: xiaoman-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-default-api-openapi.yml
- filename: xiaoman-emails-api-openapi.yml
  format: yaml
  label: OKKI Go Emails API
  slug: xiaoman-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-emails-api-openapi.yml
- filename: xiaoman-s7-1-api-openapi.yml
  format: yaml
  label: Xiaoman (OKKI CRM) s7.1 API
  slug: xiaoman-s7-1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-s7-1-api-openapi.yml
- filename: xiaoman-dev-ops-api-openapi.yml
  format: yaml
  label: Xiaoman (OKKI) Dev Ops API
  slug: xiaoman-dev-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xiaoman/openapi/xiaoman-dev-ops-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: 当您创建OKKI账户（即小满账户）时，提供的姓名、所在公司、电子邮件及/或手机号码。
  - category: identifying
    text: 我们会从微信等第三方身份验证中收集您的微信昵称和OpenID。
  - category: location
    text: 按照用户的授权范围所收集的移动设备的位置
  - category: communication
    text: 用户确认使用小满SaaS软件中的邮件等沟通功能时
  - category: other
    text: 用户在小满SaaS软件中录入或存储的潜在客户、买家等个人信息。
  deletion:
    route: In-app self-service or request to enterprise admin
    text: 您可以通过上述“1.查询、更正或补充您的信息”中列明的方式删除您的部分信息。
  dpa:
    available: true
    text: 数据处理协议
    url: null
  purposes:
  - purpose: Create and log in to OKKI account
    text: 创建及登录OKKI账户
  - purpose: Provide lead generation service
    text: 向用户提供获客服务
  - purpose: Analyse, develop and improve products
    text: 分析、开发和提升产品及功能
  residency:
  - region: China mainland
    text: 我们会将按照本隐私政策收集到的您的个人信息存储在中华人民共和国境内。
  retention:
  - period: 不少于六个月
    scope: Network logs after enterprise user stops using service
    text: 就您使用小满SaaS软件服务留存相关的网络日志不少于六个月
  rights:
  - right: Access, correct or supplement information
    text: 查询、更正或补充您的信息
  - right: Delete information
    text: 删除您的信息
  - right: Change scope of consent
    text: 改变您授权同意的范围
  - right: Cancel OKKI account
    text: 注销OKKI账户
  role:
    text: 我们作为个人信息受托处理者将按照企业用户的委托范围
    value: both
  sale_or_sharing:
    stance: conditional
    text: 我们在获取您的明确同意后，与其他方共享您的个人信息。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Xiaoman (OKKI)
provenance_date: '2026-11-10'
provider_name: Xiaoman (OKKI)
provider_slug: xiaoman
slug: xiaoman-privacy-policy
source_date: '2026-11-10'
source_filename: xiaoman-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.xiaoman.cn/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Xiaoman (OKKI)\naid: xiaoman\nurl: https://www.xiaoman.cn/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 我们作为个人信息受托处理者将按照企业用户的委托范围\ndata_categories:\n- category: contact\n  text: 当您创建OKKI账户（即小满账户）时，提供的姓名、所在公司、电子邮件及/或手机号码。\n- category: identifying\n  text: 我们会从微信等第三方身份验证中收集您的微信昵称和OpenID。\n- category: location\n  text: 按照用户的授权范围所收集的移动设备的位置\n- category: communication\n  text: 用户确认使用小满SaaS软件中的邮件等沟通功能时\n- category: other\n  text: 用户在小满SaaS软件中录入或存储的潜在客户、买家等个人信息。\npurposes:\n- purpose: Create and log in to OKKI account\n  text: 创建及登录OKKI账户\n- purpose: Provide lead generation service\n  text:\
  \ 向用户提供获客服务\n- purpose: Analyse, develop and improve products\n  text: 分析、开发和提升产品及功能\nretention:\n- scope: Network logs after enterprise user stops using service\n  period: 不少于六个月\n  text: 就您使用小满SaaS软件服务留存相关的网络日志不少于六个月\nresidency:\n- region: China mainland\n  text: 我们会将按照本隐私政策收集到的您的个人信息存储在中华人民共和国境内。\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: 数据处理协议\ndeletion:\n  route: In-app self-service or request to enterprise admin\n  text: 您可以通过上述“1.查询、更正或补充您的信息”中列明的方式删除您的部分信息。\nrights:\n- right: Access, correct or supplement information\n  text: 查询、更正或补充您的信息\n- right: Delete information\n  text: 删除您的信息\n- right: Change scope of consent\n  text: 改变您授权同意的范围\n- right: Cancel OKKI account\n  text: 注销OKKI账户\nsale_or_sharing:\n  stance: conditional\n  text: 我们在获取您的明确同意后，与其他方共享您的个人信息。\n"
source_yaml_url: https://artifacts.apis.io/xiaoman/privacy/xiaoman-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Xiaoman (OKKI)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- CRM
- Foreign Trade
- B2B
- Sales
- Prospecting
- Email Marketing
- AI Agents
- China
- Alibaba
---
