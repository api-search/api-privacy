---
api_specs:
- filename: aiworkstation-cn-ai-api-openapi.yml
  format: yaml
  label: AI Workstation AI工作站·会话入口 API
  slug: aiworkstation-cn-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-ai-api-openapi.yml
- filename: aiworkstation-cn-ai-douyin-account-audit-api-openapi.yml
  format: yaml
  label: AI Workstation AI Douyin Account Audit API
  slug: aiworkstation-cn-ai-douyin-account-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-ai-douyin-account-audit-api-openapi.yml
- filename: aiworkstation-cn-ai-growth-guide-api-openapi.yml
  format: yaml
  label: AI Workstation Ai Growth Guide API
  slug: aiworkstation-cn-ai-growth-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-ai-growth-guide-api-openapi.yml
- filename: aiworkstation-cn-ai-topic-radar-api-openapi.yml
  format: yaml
  label: AI Workstation AI Topic Radar API
  slug: aiworkstation-cn-ai-topic-radar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-ai-topic-radar-api-openapi.yml
- filename: aiworkstation-cn-analytics-api-openapi.yml
  format: yaml
  label: AI Workstation Analytics API
  slug: aiworkstation-cn-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-analytics-api-openapi.yml
- filename: aiworkstation-cn-gaokao-api-openapi.yml
  format: yaml
  label: AI Workstation Gaokao API
  slug: aiworkstation-cn-gaokao-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-gaokao-api-openapi.yml
- filename: aiworkstation-cn-system-api-openapi.yml
  format: yaml
  label: AI Workstation System API
  slug: aiworkstation-cn-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-system-api-openapi.yml
- filename: aiworkstation-cn-tts-api-openapi.yml
  format: yaml
  label: AI Workstation Tts API
  slug: aiworkstation-cn-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiworkstation-cn/openapi/aiworkstation-cn-tts-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: device
    text: 我们会记录必要的设备标识、功能事件、语言、来源域名和粗粒度国家代码
  - category: location
    text: 粗粒度国家代码
  - category: other
    text: 只有当你主动提交问题、链接、文档或图片时，服务才会处理这些内容
  deletion:
    route: delete conversations, individual memory entries, or clear long-term memory
    text: 你可以删除会话、逐条删除或清空长期记忆
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: generate answers or complete requested tasks
    text: 只有当你主动提交问题、链接、文档或图片时，服务才会处理这些内容，以生成回答或完成你要求的任务。
  - purpose: service assurance and product improvement
    text: 为保障服务和改进产品
  retention:
  - period: 游客 30 天、会员 180 天
    scope: uploaded files
    text: 上传文件默认保留期：游客 30 天、会员 180 天，之后由清理任务处理。
  rights:
  - right: export conversations
    text: 将会话导出为 Word、PDF、Markdown 或纯文本
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 请求可能由 AI 工作站配置的模型 API、托管和网络服务提供商处理。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Workstation
provenance_date: '2026-11-09'
provider_name: AI Workstation
provider_slug: aiworkstation-cn
slug: aiworkstation-cn-privacy-policy
source_date: '2026-11-09'
source_filename: aiworkstation-cn-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aiworkstation.cn/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Workstation\naid: aiworkstation-cn\nurl: https://aiworkstation.cn/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: 我们会记录必要的设备标识、功能事件、语言、来源域名和粗粒度国家代码\n- category: location\n  text: 粗粒度国家代码\n- category: other\n  text: 只有当你主动提交问题、链接、文档或图片时，服务才会处理这些内容\npurposes:\n- purpose: generate answers or complete requested tasks\n  text: 只有当你主动提交问题、链接、文档或图片时，服务才会处理这些内容，以生成回答或完成你要求的任务。\n- purpose: service assurance and product improvement\n  text: 为保障服务和改进产品\nretention:\n- scope: uploaded files\n  period: 游客 30 天、会员 180 天\n  text: 上传文件默认保留期：游客 30\
  \ 天、会员 180 天，之后由清理任务处理。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 请求可能由 AI 工作站配置的模型 API、托管和网络服务提供商处理。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete conversations, individual memory entries, or clear long-term memory\n  text: 你可以删除会话、逐条删除或清空长期记忆\nrights:\n- right: export conversations\n  text: 将会话导出为 Word、PDF、Markdown 或纯文本\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiworkstation-cn/privacy/aiworkstation-cn-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 9 quoted statements, read from AI Workstation's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Workstation
- Multi-Model
- Conversations
- File Analysis
- Image-Understanding
- Long-Term Memory
- Assistant
---
