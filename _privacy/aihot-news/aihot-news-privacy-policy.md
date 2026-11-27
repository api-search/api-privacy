---
api_specs:
- filename: aihot-news-agent-api-openapi.yml
  format: yaml
  label: AIHOT Agent API
  slug: aihot-news-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-agent-api-openapi.yml
- filename: aihot-news-dailies-api-openapi.yml
  format: yaml
  label: AIHOT Dailies API
  slug: aihot-news-dailies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-dailies-api-openapi.yml
- filename: aihot-news-hot-topics-api-openapi.yml
  format: yaml
  label: AIHOT Hot Topics API
  slug: aihot-news-hot-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-hot-topics-api-openapi.yml
- filename: aihot-news-items-api-openapi.yml
  format: yaml
  label: AIHOT Items API
  slug: aihot-news-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-items-api-openapi.yml
- filename: aihot-news-monthlies-api-openapi.yml
  format: yaml
  label: AIHOT Monthlies API
  slug: aihot-news-monthlies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-monthlies-api-openapi.yml
- filename: aihot-news-selected-api-openapi.yml
  format: yaml
  label: AIHOT Selected API
  slug: aihot-news-selected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-selected-api-openapi.yml
- filename: aihot-news-stories-api-openapi.yml
  format: yaml
  label: AIHOT Stories API
  slug: aihot-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-stories-api-openapi.yml
- filename: aihot-news-weeklies-api-openapi.yml
  format: yaml
  label: AIHOT Weeklies API
  slug: aihot-news-weeklies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihot-news/openapi/aihot-news-weeklies-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 浏览器会在本地生成随机访客标识
  - category: contact
    text: 我们会处理反馈内容、选填邮箱、当时页面 URL、User-Agent
  - category: device
    text: 源站会记录 IP 地址、访问时间、请求方法、URL 路径（不含查询参数）、协议、响应状态和大小、来源页面、User-Agent
  - category: behavioral
    text: 页面停留时间、有限的点击信息
  deletion:
    route: contact the operator
    text: 你可以随时申请删除。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide content and core functions
    text: 向你返回网页、RSS、API、MCP 和其他公开内容，并维持基本功能。
  - purpose: security and abuse prevention
    text: 识别故障、攻击、滥用、异常请求、缓存问题和容量需求，保护网站及使用者安全。
  - purpose: analytics and product improvement
    text: 统计访问趋势、新访客与回访、设备适配、页面速度、来源渠道和功能使用情况，以改进产品。
  - purpose: feedback handling
    text: 接收、去重、回复和跟进反馈，核验问题并处理相关争议。
  retention:
  - period: ３０ 天
    scope: browser analytics raw events
    text: 浏览器分析原始事件（含随机访客标识）保存 ３０ 天，随后删除；
  - period: ３６５ 天
    scope: origin access logs
    text: 源站原始访问日志在服务器本地归档最长保存 ３６５ 天，用于安全取证、滥用回溯和运行审计；到期清理。
  - period: １２０ 天
    scope: AAC receipts and rolling state
    text: AAC 的成功回执、Actor 日内去重集合、覆盖率和由这些明细重建的滚动状态最多保存 １２０ 天；
  - period: null
    scope: feedback materials
    text: 反馈资料按处理、回访、安全和争议需要保存，在目的完成且不再有法定或合理保留需要后删除或匿名化；
  rights:
  - right: access, correction, supplement or deletion
    text: 如果你希望查询、更正、补充或删除与自己有关的信息，也可以直接联系我们。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 不出售个人信息
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIHOT
provenance_date: '2026-11-09'
provider_name: AIHOT
provider_slug: aihot-news
slug: aihot-news-privacy-policy
source_date: '2026-11-09'
source_filename: aihot-news-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aihot.news/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIHOT\naid: aihot-news\nurl: https://aihot.news/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 浏览器会在本地生成随机访客标识\n- category: contact\n  text: 我们会处理反馈内容、选填邮箱、当时页面 URL、User-Agent\n- category: device\n  text: 源站会记录 IP 地址、访问时间、请求方法、URL 路径（不含查询参数）、协议、响应状态和大小、来源页面、User-Agent\n- category: behavioral\n  text: 页面停留时间、有限的点击信息\npurposes:\n- purpose: provide content and core functions\n  text: 向你返回网页、RSS、API、MCP 和其他公开内容，并维持基本功能。\n- purpose: security and abuse prevention\n  text: 识别故障、攻击、滥用、异常请求、缓存问题和容量需求，保护网站及使用者安全。\n- purpose: analytics and\
  \ product improvement\n  text: 统计访问趋势、新访客与回访、设备适配、页面速度、来源渠道和功能使用情况，以改进产品。\n- purpose: feedback handling\n  text: 接收、去重、回复和跟进反馈，核验问题并处理相关争议。\nretention:\n- scope: browser analytics raw events\n  period: ３０ 天\n  text: 浏览器分析原始事件（含随机访客标识）保存 ３０ 天，随后删除；\n- scope: origin access logs\n  period: ３６５ 天\n  text: 源站原始访问日志在服务器本地归档最长保存 ３６５ 天，用于安全取证、滥用回溯和运行审计；到期清理。\n- scope: AAC receipts and rolling state\n  period: １２０ 天\n  text: AAC 的成功回执、Actor 日内去重集合、覆盖率和由这些明细重建的滚动状态最多保存 １２０ 天；\n- scope: feedback materials\n  period: null\n  text: 反馈资料按处理、回访、安全和争议需要保存，在目的完成且不再有法定或合理保留需要后删除或匿名化；\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the operator\n  text: 你可以随时申请删除。\nrights:\n- right: access, correction, supplement or deletion\n  text: 如果你希望查询、更正、补充或删除与自己有关的信息，也可以直接联系我们。\nsale_or_sharing:\n  stance: prohibited\n  text: 不出售个人信息\n"
source_yaml_url: https://artifacts.apis.io/aihot-news/privacy/aihot-news-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from AIHOT's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
