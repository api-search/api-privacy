---
api_specs:
- filename: linkagi-model-api-anthropic-style-route-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Anthropic-style route API
  slug: linkagi-model-api-anthropic-style-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-anthropic-style-route-api-openapi.yml
- filename: linkagi-model-api-discovery-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Discovery API
  slug: linkagi-model-api-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-discovery-api-openapi.yml
- filename: linkagi-model-api-gemini-style-route-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Gemini-style route API
  slug: linkagi-model-api-gemini-style-route-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-gemini-style-route-api-openapi.yml
- filename: linkagi-model-api-openai-compatible-api-openapi.yml
  format: yaml
  label: LinkAGI Model API OpenAI compatible API
  slug: linkagi-model-api-openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-openai-compatible-api-openapi.yml
- filename: linkagi-model-api-public-metadata-api-openapi.yml
  format: yaml
  label: LinkAGI Model API Public metadata API
  slug: linkagi-model-api-public-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkagi-model-api/openapi/linkagi-model-api-public-metadata-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: 账号与安全信息：邮箱、验证状态、登录与安全事件、必要的网络与设备信息。
  - category: financial
    text: 订单与计费信息：充值订单状态、余额变动、模型、Token 用量和实际扣费
  - category: behavioral
    text: API 调用元数据：调用时间、所选模型和分组、Token 数量、响应状态、耗时、费用及排错所需的错误信息。
  - category: communication
    text: 支持信息：用户主动提交给客服的故障描述、截图和联系方式。
  - category: other
    text: 请求会被转发到用户选择的模型渠道或上游服务。
  deletion:
    route: Contact LinkAGI
    text: 需要查询、更正或删除账号相关信息时，可联系 LinkAGI
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing account, billing, API, logs and support
    text: 本说明解释我们在提供账号、计费、API 调用、日志查询和技术支持时可能处理的信息。
  - purpose: Troubleshooting, billing, security audit and abuse prevention
    text: 为排查故障、计费、安全审计和防止滥用，系统可能处理必要的请求、响应或错误信息
  retention:
  - period: null
    scope: account, billing, security and fault logs
    text: 账号、计费、安全和故障日志会在提供服务、对账、防滥用及满足适用法律要求所需的期限内保留。
  - period: null
    scope: upstream model channels
    text: 上游模型渠道的保留期限可能不同
  rights:
  - right: Query, correct or delete account information
    text: 需要查询、更正或删除账号相关信息时，可联系 LinkAGI
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: LinkAGI 不会把用户请求内容出售给第三方
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LinkAGI Model API
provenance_date: '2026-11-09'
provider_name: LinkAGI Model API
provider_slug: linkagi-model-api
slug: linkagi-model-api-privacy-policy
source_date: '2026-11-09'
source_filename: linkagi-model-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://api.linktoagi.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LinkAGI Model API\naid: linkagi-model-api\nurl: https://api.linktoagi.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 账号与安全信息：邮箱、验证状态、登录与安全事件、必要的网络与设备信息。\n- category: financial\n  text: 订单与计费信息：充值订单状态、余额变动、模型、Token 用量和实际扣费\n- category: behavioral\n  text: API 调用元数据：调用时间、所选模型和分组、Token 数量、响应状态、耗时、费用及排错所需的错误信息。\n- category: communication\n  text: 支持信息：用户主动提交给客服的故障描述、截图和联系方式。\n- category: other\n  text: 请求会被转发到用户选择的模型渠道或上游服务。\npurposes:\n- purpose: Providing account, billing, API, logs and support\n  text: 本说明解释我们在提供账号、计费、API\
  \ 调用、日志查询和技术支持时可能处理的信息。\n- purpose: Troubleshooting, billing, security audit and abuse prevention\n  text: 为排查故障、计费、安全审计和防止滥用，系统可能处理必要的请求、响应或错误信息\nretention:\n- scope: account, billing, security and fault logs\n  period: null\n  text: 账号、计费、安全和故障日志会在提供服务、对账、防滥用及满足适用法律要求所需的期限内保留。\n- scope: upstream model channels\n  period: null\n  text: 上游模型渠道的保留期限可能不同\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact LinkAGI\n  text: 需要查询、更正或删除账号相关信息时，可联系 LinkAGI\nrights:\n- right: Query, correct or delete account information\n  text: 需要查询、更正或删除账号相关信息时，可联系 LinkAGI\nsale_or_sharing:\n  stance: prohibited\n  text: LinkAGI 不会把用户请求内容出售给第三方\n"
source_yaml_url: https://artifacts.apis.io/linkagi-model-api/privacy/linkagi-model-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from LinkAGI Model API's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- AI API Gateway
- Relay
- OpenAI-Compatible
- Anthropic Compatible
- Gemini-compatible
- Developer Tools
- CLI coding agents
- Model Routing
- China
---
