---
api_specs:
- filename: zhiyong-dev-agent-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent API
  slug: zhiyong-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-api-openapi.yml
- filename: zhiyong-dev-agent-discovery-json-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent Discovery.json API
  slug: zhiyong-dev-agent-discovery-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-discovery-json-api-openapi.yml
- filename: zhiyong-dev-agent-feedback-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent Feedback API
  slug: zhiyong-dev-agent-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-feedback-api-openapi.yml
- filename: zhiyong-dev-agent-observation-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent Observation API
  slug: zhiyong-dev-agent-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-observation-api-openapi.yml
- filename: zhiyong-dev-agent-task-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent Task API
  slug: zhiyong-dev-agent-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-task-api-openapi.yml
- filename: zhiyong-dev-agent-topic-api-openapi.yml
  format: yaml
  label: zhiyong-dev Agent Topic API
  slug: zhiyong-dev-agent-topic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-agent-topic-api-openapi.yml
- filename: zhiyong-dev-community-api-openapi.yml
  format: yaml
  label: zhiyong-dev Community API
  slug: zhiyong-dev-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-community-api-openapi.yml
- filename: zhiyong-dev-entity-feedback-api-openapi.yml
  format: yaml
  label: zhiyong-dev Entity Feedback API
  slug: zhiyong-dev-entity-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-entity-feedback-api-openapi.yml
- filename: zhiyong-dev-health-api-openapi.yml
  format: yaml
  label: zhiyong-dev Health API
  slug: zhiyong-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-health-api-openapi.yml
- filename: zhiyong-dev-search-api-openapi.yml
  format: yaml
  label: zhiyong-dev Search API
  slug: zhiyong-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zhiyong-dev/openapi/zhiyong-dev-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 如果你自愿提交联系表单，我们会收集你选择的产品、具体工作问题、联系方式，以及你主动填写的称呼或团队名称
  - category: communication
    text: 你主动向 A2A 服务发送消息时，服务会调用 OpenAI 生成回复
  - category: behavioral
    text: 网站会记录页面路径、访问时间、来源、国家/地区及匿名访客标识
  - category: identifying
    text: 服务会使用随机生成的 zhiyong_vid 标识（HttpOnly Cookie，最长保留一年）限制滥用和防止重复点赞
  deletion:
    route: email to hello@zhiyong.dev
    text: 如需查阅、更正或申请删除，请发送邮件至 hello@zhiyong.dev ，由管理员人工处理
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: A2A session continuity
    text: 为支持同一 A2A 会话的后续交流
  - purpose: service quality and intent audit
    text: 另为服务质量与意图处理审计
  - purpose: reply to contact inquiry
    text: 用于回复这次咨询
  - purpose: visit and article statistics
    text: 为统计访问和文章阅读
  - purpose: ad serving via Google AdSense
    text: 根据用户的同意状态、设备和访问上下文提供、衡量或个性化广告
  retention:
  - period: 12 小时
    scope: A2A session messages
    text: 最长 12 小时后自动删除
  - period: 30 天
    scope: A2A audit records
    text: 会话标识以单向哈希保存，记录在 30 天后自动删除
  - period: null
    scope: contact inquiries
    text: 目前咨询收件箱没有自动清理的固定期限
  - period: 一年
    scope: zhiyong_vid cookie
    text: 最长保留一年
  rights:
  - right: access, correction, deletion
    text: 如需查阅、更正或申请删除，请发送邮件至 hello@zhiyong.dev ，由管理员人工处理
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 语义检索可能将查询文本发送至 OpenAI Embeddings 与 Qdrant
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: zhiyong-dev
provenance_date: '2026-11-10'
provider_name: zhiyong-dev
provider_slug: zhiyong-dev
slug: zhiyong-dev-privacy-policy
source_date: '2026-11-10'
source_filename: zhiyong-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zhiyong.dev/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: zhiyong-dev\naid: zhiyong-dev\nurl: https://zhiyong.dev/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 如果你自愿提交联系表单，我们会收集你选择的产品、具体工作问题、联系方式，以及你主动填写的称呼或团队名称\n- category: communication\n  text: 你主动向 A2A 服务发送消息时，服务会调用 OpenAI 生成回复\n- category: behavioral\n  text: 网站会记录页面路径、访问时间、来源、国家/地区及匿名访客标识\n- category: identifying\n  text: 服务会使用随机生成的 zhiyong_vid 标识（HttpOnly Cookie，最长保留一年）限制滥用和防止重复点赞\npurposes:\n- purpose: A2A session continuity\n  text: 为支持同一 A2A 会话的后续交流\n- purpose: service quality and intent audit\n  text: 另为服务质量与意图处理审计\n- purpose:\
  \ reply to contact inquiry\n  text: 用于回复这次咨询\n- purpose: visit and article statistics\n  text: 为统计访问和文章阅读\n- purpose: ad serving via Google AdSense\n  text: 根据用户的同意状态、设备和访问上下文提供、衡量或个性化广告\nretention:\n- scope: A2A session messages\n  period: 12 小时\n  text: 最长 12 小时后自动删除\n- scope: A2A audit records\n  period: 30 天\n  text: 会话标识以单向哈希保存，记录在 30 天后自动删除\n- scope: contact inquiries\n  period: null\n  text: 目前咨询收件箱没有自动清理的固定期限\n- scope: zhiyong_vid cookie\n  period: 一年\n  text: 最长保留一年\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 语义检索可能将查询文本发送至 OpenAI Embeddings 与 Qdrant\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to hello@zhiyong.dev\n  text: 如需查阅、更正或申请删除，请发送邮件至 hello@zhiyong.dev ，由管理员人工处理\nrights:\n- right: access, correction, deletion\n  text: 如需查阅、更正或申请删除，请发送邮件至 hello@zhiyong.dev ，由管理员人工处理\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zhiyong-dev/privacy/zhiyong-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from zhiyong-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software
- Developer Tools
- Integration
---
