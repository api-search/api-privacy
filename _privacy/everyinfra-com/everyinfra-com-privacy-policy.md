---
api_specs:
- filename: everyinfra-com-account-api-openapi.yml
  format: yaml
  label: EveryInfra Account API
  slug: everyinfra-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-account-api-openapi.yml
- filename: everyinfra-com-ai-api-openapi.yml
  format: yaml
  label: EveryInfra AI API
  slug: everyinfra-com-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-ai-api-openapi.yml
- filename: everyinfra-com-availability-api-openapi.yml
  format: yaml
  label: EveryInfra Availability API
  slug: everyinfra-com-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-availability-api-openapi.yml
- filename: everyinfra-com-captcha-api-openapi.yml
  format: yaml
  label: EveryInfra Captcha API
  slug: everyinfra-com-captcha-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-captcha-api-openapi.yml
- filename: everyinfra-com-discovery-api-openapi.yml
  format: yaml
  label: EveryInfra Discovery API
  slug: everyinfra-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-discovery-api-openapi.yml
- filename: everyinfra-com-email-api-openapi.yml
  format: yaml
  label: EveryInfra Email API
  slug: everyinfra-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-email-api-openapi.yml
- filename: everyinfra-com-marketplace-api-openapi.yml
  format: yaml
  label: EveryInfra Marketplace API
  slug: everyinfra-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-marketplace-api-openapi.yml
- filename: everyinfra-com-proxy-api-openapi.yml
  format: yaml
  label: EveryInfra Proxy API
  slug: everyinfra-com-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-proxy-api-openapi.yml
- filename: everyinfra-com-search-api-openapi.yml
  format: yaml
  label: EveryInfra Search API
  slug: everyinfra-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-search-api-openapi.yml
- filename: everyinfra-com-sms-api-openapi.yml
  format: yaml
  label: EveryInfra SMS API
  slug: everyinfra-com-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-sms-api-openapi.yml
- filename: everyinfra-com-social-api-openapi.yml
  format: yaml
  label: EveryInfra Social API
  slug: everyinfra-com-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-social-api-openapi.yml
- filename: everyinfra-com-support-api-openapi.yml
  format: yaml
  label: EveryInfra Support API
  slug: everyinfra-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyinfra-com/openapi/everyinfra-com-support-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 你注册时提供的邮箱地址
  - category: identifying
    text: 经加密存储(pbkdf2)的密码，不以明文保存。
  - category: device
    text: 来源 IP、User-Agent、语言偏好(Accept-Language)、来源页(Referer/Origin)
  - category: location
    text: 经 CDN 判定的来源国家与边缘节点
  - category: behavioral
    text: 我们自己的统计会记录官网和控制台的页面访问与点击
  - category: financial
    text: 每次 API 调用的时间、调用的能力(平台/动作)、状态码、耗时与扣费金额，用于计费、排障与防滥用。
  deletion:
    route: account cancellation or contact
    text: 你有权访问、更正或删除你的账户信息，或注销账户。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 提供与维护服务、计量与计费
    text: 提供与维护服务、计量与计费、施加速率限制与防止滥用、排查故障与保障安全
  - purpose: Google Ads conversion measurement
    text: 用来统计广告带来的注册和付费
  retention:
  - period: null
    scope: account after cancellation
    text: 账户注销后，我们会在合理期限内删除或匿名化你的账户资料，但上述日志与记录以及法律要求保留的信息除外。
  - period: 400 天
    scope: first-party visit cookie
    text: 保存 400 天，只在 everyinfra.com 下使用，不用于广告
  rights:
  - right: access, correction, deletion
    text: 你有权访问、更正或删除你的账户信息，或注销账户。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 我们不会将你的账户信息出售给第三方。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EveryInfra
provenance_date: '2026-11-09'
provider_name: EveryInfra
provider_slug: everyinfra-com
slug: everyinfra-com-privacy-policy
source_date: '2026-11-09'
source_filename: everyinfra-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://everyinfra.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EveryInfra\naid: everyinfra-com\nurl: https://everyinfra.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 你注册时提供的邮箱地址\n- category: identifying\n  text: 经加密存储(pbkdf2)的密码，不以明文保存。\n- category: device\n  text: 来源 IP、User-Agent、语言偏好(Accept-Language)、来源页(Referer/Origin)\n- category: location\n  text: 经 CDN 判定的来源国家与边缘节点\n- category: behavioral\n  text: 我们自己的统计会记录官网和控制台的页面访问与点击\n- category: financial\n  text: 每次 API 调用的时间、调用的能力(平台/动作)、状态码、耗时与扣费金额，用于计费、排障与防滥用。\npurposes:\n- purpose: 提供与维护服务、计量与计费\n  text: 提供与维护服务、计量与计费、施加速率限制与防止滥用、排查故障与保障安全\n\
  - purpose: Google Ads conversion measurement\n  text: 用来统计广告带来的注册和付费\nretention:\n- scope: account after cancellation\n  period: null\n  text: 账户注销后，我们会在合理期限内删除或匿名化你的账户资料，但上述日志与记录以及法律要求保留的信息除外。\n- scope: first-party visit cookie\n  period: 400 天\n  text: 保存 400 天，只在 everyinfra.com 下使用，不用于广告\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account cancellation or contact\n  text: 你有权访问、更正或删除你的账户信息，或注销账户。\nrights:\n- right: access, correction, deletion\n  text: 你有权访问、更正或删除你的账户信息，或注销账户。\nsale_or_sharing:\n  stance: prohibited\n  text: 我们不会将你的账户信息出售给第三方。\n"
source_yaml_url: https://artifacts.apis.io/everyinfra-com/privacy/everyinfra-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from EveryInfra's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Infrastructure
- Data
- Platform
---
