---
api_specs:
- filename: bithot-news-agent-api-openapi.yml
  format: yaml
  label: BITHOT Agent API
  slug: bithot-news-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-agent-api-openapi.yml
- filename: bithot-news-dailies-api-openapi.yml
  format: yaml
  label: BITHOT Dailies API
  slug: bithot-news-dailies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-dailies-api-openapi.yml
- filename: bithot-news-hot-topics-api-openapi.yml
  format: yaml
  label: BITHOT Hot Topics API
  slug: bithot-news-hot-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-hot-topics-api-openapi.yml
- filename: bithot-news-items-api-openapi.yml
  format: yaml
  label: BITHOT Items API
  slug: bithot-news-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-items-api-openapi.yml
- filename: bithot-news-monthlies-api-openapi.yml
  format: yaml
  label: BITHOT Monthlies API
  slug: bithot-news-monthlies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-monthlies-api-openapi.yml
- filename: bithot-news-selected-api-openapi.yml
  format: yaml
  label: BITHOT Selected API
  slug: bithot-news-selected-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-selected-api-openapi.yml
- filename: bithot-news-stories-api-openapi.yml
  format: yaml
  label: BITHOT Stories API
  slug: bithot-news-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-stories-api-openapi.yml
- filename: bithot-news-weeklies-api-openapi.yml
  format: yaml
  label: BITHOT Weeklies API
  slug: bithot-news-weeklies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithot-news/openapi/bithot-news-weeklies-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: 你在反馈页提交的内容、选填的邮箱、提交时所在页面的地址，以及你选择附上的截图，会保存在服务器上
  - category: device
    text: 服务器会保存一个由网络地址和浏览器类别计算出的、无法还原的标识
  - category: other
    text: 收藏、已读记录、深浅色设置、最近搜索（你搜过的词，最多 10 条）
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: feedback handling
    text: 用于处理你的反馈
  - purpose: abuse prevention
    text: 用于限流和封禁滥用来源
  - purpose: analytics
    text: 本站使用 Google Analytics（衡量 ID：G-TLM9KBW5XV）统计页面访问
  retention:
  - period: null
    scope: browser local data
    text: 清除浏览器数据后它们会消失
  - period: null
    scope: screenshots forwarded to Feishu
    text: 截图上传到飞书后服务器上不再保留
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
name: BITHOT
provenance_date: '2026-11-09'
provider_name: BITHOT
provider_slug: bithot-news
slug: bithot-news-privacy-policy
source_date: '2026-11-09'
source_filename: bithot-news-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bithot.news/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BITHOT\naid: bithot-news\nurl: https://bithot.news/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 你在反馈页提交的内容、选填的邮箱、提交时所在页面的地址，以及你选择附上的截图，会保存在服务器上\n- category: device\n  text: 服务器会保存一个由网络地址和浏览器类别计算出的、无法还原的标识\n- category: other\n  text: 收藏、已读记录、深浅色设置、最近搜索（你搜过的词，最多 10 条）\npurposes:\n- purpose: feedback handling\n  text: 用于处理你的反馈\n- purpose: abuse prevention\n  text: 用于限流和封禁滥用来源\n- purpose: analytics\n  text: 本站使用 Google Analytics（衡量 ID：G-TLM9KBW5XV）统计页面访问\nretention:\n- scope: browser local data\n  period: null\n  text: 清除浏览器数据后它们会消失\n\
  - scope: screenshots forwarded to Feishu\n  period: null\n  text: 截图上传到飞书后服务器上不再保留\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: 不出售个人信息\n"
source_yaml_url: https://artifacts.apis.io/bithot-news/privacy/bithot-news-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 9 quoted statements, read from BITHOT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Cryptocurrency
- Web3
- Memecoin
- News
---
