---
api_specs:
- filename: ecommercedataapi-com-amazon-keywords-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Keywords API
  slug: ecommercedataapi-com-amazon-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-keywords-api-openapi.yml
- filename: ecommercedataapi-com-amazon-markets-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Markets API
  slug: ecommercedataapi-com-amazon-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-markets-api-openapi.yml
- filename: ecommercedataapi-com-amazon-products-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Products API
  slug: ecommercedataapi-com-amazon-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-products-api-openapi.yml
- filename: ecommercedataapi-com-amazon-traffic-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Traffic API
  slug: ecommercedataapi-com-amazon-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-traffic-api-openapi.yml
- filename: ecommercedataapi-com-global-trademarks-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Global Trademarks API
  slug: ecommercedataapi-com-global-trademarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-global-trademarks-api-openapi.yml
- filename: ecommercedataapi-com-tools-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Tools API
  slug: ecommercedataapi-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-tools-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 我们会处理账户标识、姓名、电子邮件地址、头像、IP 地址
  - category: device
    text: 浏览器信息
  - category: financial
    text: 套餐、金额、币种和计费周期
  - category: other
    text: 响应中可能包含在电商平台或商标登记中公开的个人信息
  deletion:
    route: account request
    text: 您可以请求访问、更正或删除账户信息
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: user authentication, quota control, abuse prevention, operations
    text: 我们使用这些信息进行用户鉴权、额度控制、防止滥用、故障诊断、服务运营与改进
  - purpose: support requests and legal obligations
    text: 响应支持请求，以及履行法律义务
  retention:
  - period: 180 天
    scope: full API request and response records
    text: 完整的请求和响应记录保留 180 天
  - period: null
    scope: account, payment, usage and security records
    text: 账户、支付、用量和安全记录仅在提供服务、解决争议、防止滥用和满足法律义务所需的
  rights:
  - right: access, correction, deletion
    text: 您可以请求访问、更正或删除账户信息
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 我们不会出售个人信息。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ecommercedataapi-com
provenance_date: '2026-11-09'
provider_name: ecommercedataapi-com
provider_slug: ecommercedataapi-com
slug: ecommercedataapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: ecommercedataapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ecommercedataapi.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ecommercedataapi-com\naid: ecommercedataapi-com\nurl: https://ecommercedataapi.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 我们会处理账户标识、姓名、电子邮件地址、头像、IP 地址\n- category: device\n  text: 浏览器信息\n- category: financial\n  text: 套餐、金额、币种和计费周期\n- category: other\n  text: 响应中可能包含在电商平台或商标登记中公开的个人信息\npurposes:\n- purpose: user authentication, quota control, abuse prevention, operations\n  text: 我们使用这些信息进行用户鉴权、额度控制、防止滥用、故障诊断、服务运营与改进\n- purpose: support requests and legal obligations\n  text: 响应支持请求，以及履行法律义务\nretention:\n- scope:\
  \ full API request and response records\n  period: 180 天\n  text: 完整的请求和响应记录保留 180 天\n- scope: account, payment, usage and security records\n  period: null\n  text: 账户、支付、用量和安全记录仅在提供服务、解决争议、防止滥用和满足法律义务所需的\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account request\n  text: 您可以请求访问、更正或删除账户信息\nrights:\n- right: access, correction, deletion\n  text: 您可以请求访问、更正或删除账户信息\nsale_or_sharing:\n  stance: prohibited\n  text: 我们不会出售个人信息。\n"
source_yaml_url: https://artifacts.apis.io/ecommercedataapi-com/privacy/ecommercedataapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from ecommercedataapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Data
- Amazon
- Market Research
---
