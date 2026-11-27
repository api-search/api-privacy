---
api_specs:
- filename: twtapi-com-admin-api-openapi.yml
  format: yaml
  label: twtapi-com Admin API
  slug: twtapi-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-admin-api-openapi.yml
- filename: twtapi-com-agent-api-openapi.yml
  format: yaml
  label: twtapi-com Agent API
  slug: twtapi-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-agent-api-openapi.yml
- filename: twtapi-com-auth-api-openapi.yml
  format: yaml
  label: twtapi-com Auth API
  slug: twtapi-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-auth-api-openapi.yml
- filename: twtapi-com-captcha-api-openapi.yml
  format: yaml
  label: twtapi-com Captcha API
  slug: twtapi-com-captcha-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-captcha-api-openapi.yml
- filename: twtapi-com-myapi-api-openapi.yml
  format: yaml
  label: twtapi-com Myapi API
  slug: twtapi-com-myapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-myapi-api-openapi.yml
- filename: twtapi-com-payment-api-openapi.yml
  format: yaml
  label: twtapi-com Payment API
  slug: twtapi-com-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-payment-api-openapi.yml
- filename: twtapi-com-twitter-api-openapi.yml
  format: yaml
  label: twtapi-com Twitter API
  slug: twtapi-com-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-twitter-api-openapi.yml
- filename: twtapi-com-twtapi-backend-api-openapi.yml
  format: yaml
  label: twtapi-com TwtAPI Backend API
  slug: twtapi-com-twtapi-backend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twtapi-com/openapi/twtapi-com-twtapi-backend-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: 账户信息：如邮箱地址、密码（加密存储）、昵称（若您填写）
  - category: device
    text: 使用与设备信息：如 IP 地址、浏览器类型、访问时间、API 调用记录与用量
  - category: financial
    text: 支付相关：通过支付渠道（如 Stripe）处理时，我们可能获得订单号、金额、支付状态，但不存储您的完整银行卡号
  - category: communication
    text: 您主动提供的信息：如联系表单、客服沟通中的内容
  deletion:
    route: Request deletion or anonymization by contacting us
    text: 您也可要求我们删除或匿名化您的个人数据（法律要求保留的除外）
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: 提供与维护本服务、身份验证、计费与防欺诈、用量统计与限流、改进产品与文档
  - purpose: Respond to inquiries
    text: 回复您的咨询与投诉，以及遵守适用法律法规
  retention:
  - period: null
    scope: Personal data after account closure
    text: 账户注销后，我们将在合理期限内删除或匿名化您的个人数据
  rights:
  - right: Access and correction
    text: 您有权查询、更正您的账户信息
  - right: Deletion or anonymization
    text: 您也可要求我们删除或匿名化您的个人数据（法律要求保留的除外）
  - right: Withdraw consent
    text: 或撤回同意——可通过联系我们来行使上述权利
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 我们不会出售您的个人信息。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: twtapi-com
provenance_date: '2026-11-10'
provider_name: twtapi-com
provider_slug: twtapi-com
slug: twtapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: twtapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://twtapi.com/zh/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: twtapi-com\naid: twtapi-com\nurl: https://twtapi.com/zh/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 账户信息：如邮箱地址、密码（加密存储）、昵称（若您填写）\n- category: device\n  text: 使用与设备信息：如 IP 地址、浏览器类型、访问时间、API 调用记录与用量\n- category: financial\n  text: 支付相关：通过支付渠道（如 Stripe）处理时，我们可能获得订单号、金额、支付状态，但不存储您的完整银行卡号\n- category: communication\n  text: 您主动提供的信息：如联系表单、客服沟通中的内容\npurposes:\n- purpose: Provide and maintain service\n  text: 提供与维护本服务、身份验证、计费与防欺诈、用量统计与限流、改进产品与文档\n- purpose: Respond to inquiries\n  text: 回复您的咨询与投诉，以及遵守适用法律法规\nretention:\n- scope: Personal\
  \ data after account closure\n  period: null\n  text: 账户注销后，我们将在合理期限内删除或匿名化您的个人数据\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion or anonymization by contacting us\n  text: 您也可要求我们删除或匿名化您的个人数据（法律要求保留的除外）\nrights:\n- right: Access and correction\n  text: 您有权查询、更正您的账户信息\n- right: Deletion or anonymization\n  text: 您也可要求我们删除或匿名化您的个人数据（法律要求保留的除外）\n- right: Withdraw consent\n  text: 或撤回同意——可通过联系我们来行使上述权利\nsale_or_sharing:\n  stance: prohibited\n  text: 我们不会出售您的个人信息。\n"
source_yaml_url: https://artifacts.apis.io/twtapi-com/privacy/twtapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from twtapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Twitter
- X
- Data
- Search
- Monitoring
- Artificial Intelligence
---
