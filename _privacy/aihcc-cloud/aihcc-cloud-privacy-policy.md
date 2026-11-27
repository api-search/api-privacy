---
api_specs:
- filename: aihcc-cloud-openapi-generated.yml
  format: yaml
  label: AIHCC API
  slug: aihcc-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aihcc-cloud/openapi/_ae-authored/aihcc-cloud-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: 账号信息：注册时提供的邮箱或手机号、加密存储的密码（PBKDF2 加盐哈希，不可逆）。
  - category: behavioral
    text: 使用数据：调用次数、额度消耗、延迟等服务运行指标，用于计费与服务质量改进。
  - category: other
    text: 检测内容：您提交检测的文本仅用于实时检测，检测完成后原始原文不落库。
  - category: other
    text: 浏览器扩展：API Key 仅保存在您浏览器本地（chrome.storage.local），不上传服务器、不进入页面上下文。
  deletion:
    route: request via contact email
    text: 删除：可申请删除账号及关联数据。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 提供核心服务
    text: 提供核心服务：声明提取、搜索验证、置信度评估、修正建议。
  - purpose: 改进检测效果
    text: 改进检测效果：仅使用脱敏后的样本进入评测集与反馈闭环。
  - purpose: 账号与计费
    text: 账号与计费：额度计数、套餐管理、API Key 签发与轮换。
  - purpose: 安全与反滥用
    text: 安全与反滥用：登录锁定、限流、异常调用检测。
  retention:
  - period: 检测完成即弃
    scope: 检测原文
    text: 检测原文：检测完成即弃，不持久化。
  - period: 保留至您注销账号或提出删除请求
    scope: 脱敏样本
    text: 脱敏样本：用于评测与优化，保留至您注销账号或提出删除请求。
  - period: 账号存续期间
    scope: 账号数据
    text: 账号数据：账号存续期间保留；注销后按法律法规要求的最短期限保留必要日志。
  rights:
  - right: access and correction
    text: 查询与更正：在个人资料页查看与修改账号信息。
  - right: deletion
    text: 删除：可申请删除账号及关联数据。
  - right: withdraw consent
    text: 撤回授权：停止使用即视为撤回；浏览器扩展可随时卸载并清除本地 Key。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 不会出售您的个人信息。
  subprocessors:
    text: 检测过程中，您提交的文本会发送至大模型服务方（DeepSeek / OpenAI / GLM / 通义等）与搜索服务方（百度千帆 / Bing）以完成验证，受其各自隐私政策约束。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIHCC
provenance_date: '2026-11-09'
provider_name: AIHCC
provider_slug: aihcc-cloud
slug: aihcc-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: aihcc-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aihcc.cloud/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIHCC\naid: aihcc-cloud\nurl: https://aihcc.cloud/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 账号信息：注册时提供的邮箱或手机号、加密存储的密码（PBKDF2 加盐哈希，不可逆）。\n- category: behavioral\n  text: 使用数据：调用次数、额度消耗、延迟等服务运行指标，用于计费与服务质量改进。\n- category: other\n  text: 检测内容：您提交检测的文本仅用于实时检测，检测完成后原始原文不落库。\n- category: other\n  text: 浏览器扩展：API Key 仅保存在您浏览器本地（chrome.storage.local），不上传服务器、不进入页面上下文。\npurposes:\n- purpose: 提供核心服务\n  text: 提供核心服务：声明提取、搜索验证、置信度评估、修正建议。\n- purpose: 改进检测效果\n  text: 改进检测效果：仅使用脱敏后的样本进入评测集与反馈闭环。\n- purpose: 账号与计费\n  text: 账号与计费：额度计数、套餐管理、API\
  \ Key 签发与轮换。\n- purpose: 安全与反滥用\n  text: 安全与反滥用：登录锁定、限流、异常调用检测。\nretention:\n- scope: 检测原文\n  period: 检测完成即弃\n  text: 检测原文：检测完成即弃，不持久化。\n- scope: 脱敏样本\n  period: 保留至您注销账号或提出删除请求\n  text: 脱敏样本：用于评测与优化，保留至您注销账号或提出删除请求。\n- scope: 账号数据\n  period: 账号存续期间\n  text: 账号数据：账号存续期间保留；注销后按法律法规要求的最短期限保留必要日志。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 检测过程中，您提交的文本会发送至大模型服务方（DeepSeek / OpenAI / GLM / 通义等）与搜索服务方（百度千帆 / Bing）以完成验证，受其各自隐私政策约束。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via contact email\n  text: 删除：可申请删除账号及关联数据。\nrights:\n- right: access and correction\n  text: 查询与更正：在个人资料页查看与修改账号信息。\n- right: deletion\n  text: 删除：可申请删除账号及关联数据。\n- right: withdraw consent\n  text: 撤回授权：停止使用即视为撤回；浏览器扩展可随时卸载并清除本地 Key。\nsale_or_sharing:\n  stance: prohibited\n  text: 不会出售您的个人信息。\n"
source_yaml_url: https://artifacts.apis.io/aihcc-cloud/privacy/aihcc-cloud-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AIHCC's own page on 2026-11-09.
synthetic: false
tags:
- AI Safety
- Agent Tools
- Hallucination Detection
- Prompt Injection
- Chinese
---
