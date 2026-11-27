---
api_specs:
- filename: kook-bot-kook-api-openapi.yml
  format: yaml
  label: KOOK 将Bot连接到 KOOK 服务器 API
  slug: kook-bot-kook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-bot-kook-api-openapi.yml
- filename: kook-default-api-openapi.yml
  format: yaml
  label: KOOK 事件通知介绍 API
  slug: kook-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-default-api-openapi.yml
- filename: kook-gateway-api-openapi.yml
  format: yaml
  label: KOOK Gateway接口 API
  slug: kook-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-gateway-api-openapi.yml
- filename: kook-kmarkdown-api-openapi.yml
  format: yaml
  label: KOOK K Markdown与卡片消息 API
  slug: kook-kmarkdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kook/openapi/kook-kmarkdown-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 您通过手机号注册/登录KOOK账号时，需提供手机号码
  - category: device
    text: 设备唯一标识符（仅用于设备识别，不进行跨平台追踪）
  - category: location
    text: 地理位置信息，用于优化服务体验、广告投放、排查功能故障
  - category: behavioral
    text: 服务器/频道访问记录、功能操作记录
  - category: communication
    text: 您在KOOK中创建服务器/频道、发布语音/文字内容、进行聊天互动
  deletion:
    route: KOOK-我的-账号设置-账号安全-注销账号
    text: 登录KOOK-我的-账号设置-账号安全-注销账号，按照页面提示完成身份验证后即可申请注销
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide core product and basic services
    text: 为您提供产品及基础服务：基于注册信息、设备信息、权限授权信息，为您实现账号登录、语音/文字聊天、服务器/频道管理等核心功能。
  - purpose: account security
    text: 保障您的账号及交易安全：基于IP地址、登录信息、设备信息，进行安全风险识别
  - purpose: product optimization
    text: 所有分析均采用匿名化、聚合化方式，不识别单个用户。
  residency:
  - region: 中华人民共和国境内
    text: 您的所有个人信息均存储于中华人民共和国境内，我们不会将您的个人信息进行跨境传输
  retention:
  - period: 1年
    scope: basic registration information (phone number, account)
    text: 保存至您注销账号后1年，期满后不可逆脱敏处理
  - period: 6个月
    scope: service usage and network security information
    text: 保存至服务结束后6个月，期满后自动删除
  - period: 15个工作日
    scope: user-published content and interaction information
    text: 保存至您主动删除或注销账号后15个工作日，期满后自动删除
  - period: 3年
    scope: customer service records
    text: 保存至问题处理完毕后3年，期满后自动删除
  rights:
  - right: access
    text: 查阅您的注册信息、网络身份标识信息、服务使用记录、权限授权状态
  - right: correction
    text: 更正您的用户名、头像、个人简介等网络身份标识信息
  - right: deletion
    text: 删除您主动发布的文字、图片、语音等内容
  - right: withdraw consent
    text: 通过操作系统撤回对麦克风、摄像头、相册、用户动态等功能的授权
  - right: copy/export
    text: 复制您的注册信息、服务使用记录等个人信息，导出为电子文件
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 我们不会将您的个人信息向任何第三方无偿共享、有偿售卖，仅在以下法定情形下，在必要范围内共享
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: KOOK
provenance_date: '2026-11-09'
provider_name: KOOK
provider_slug: kook
slug: kook-privacy-policy
source_date: '2026-11-09'
source_filename: kook-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kookapp.cn/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KOOK\naid: kook\nurl: https://www.kookapp.cn/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 您通过手机号注册/登录KOOK账号时，需提供手机号码\n- category: device\n  text: 设备唯一标识符（仅用于设备识别，不进行跨平台追踪）\n- category: location\n  text: 地理位置信息，用于优化服务体验、广告投放、排查功能故障\n- category: behavioral\n  text: 服务器/频道访问记录、功能操作记录\n- category: communication\n  text: 您在KOOK中创建服务器/频道、发布语音/文字内容、进行聊天互动\npurposes:\n- purpose: provide core product and basic services\n  text: 为您提供产品及基础服务：基于注册信息、设备信息、权限授权信息，为您实现账号登录、语音/文字聊天、服务器/频道管理等核心功能。\n- purpose: account security\n  text: 保障您的账号及交易安全：基于IP地址、登录信息、设备信息，进行安全风险识别\n\
  - purpose: product optimization\n  text: 所有分析均采用匿名化、聚合化方式，不识别单个用户。\nretention:\n- scope: basic registration information (phone number, account)\n  period: 1年\n  text: 保存至您注销账号后1年，期满后不可逆脱敏处理\n- scope: service usage and network security information\n  period: 6个月\n  text: 保存至服务结束后6个月，期满后自动删除\n- scope: user-published content and interaction information\n  period: 15个工作日\n  text: 保存至您主动删除或注销账号后15个工作日，期满后自动删除\n- scope: customer service records\n  period: 3年\n  text: 保存至问题处理完毕后3年，期满后自动删除\nresidency:\n- region: 中华人民共和国境内\n  text: 您的所有个人信息均存储于中华人民共和国境内，我们不会将您的个人信息进行跨境传输\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: KOOK-我的-账号设置-账号安全-注销账号\n  text: 登录KOOK-我的-账号设置-账号安全-注销账号，按照页面提示完成身份验证后即可申请注销\nrights:\n- right: access\n  text: 查阅您的注册信息、网络身份标识信息、服务使用记录、权限授权状态\n- right: correction\n  text: 更正您的用户名、头像、个人简介等网络身份标识信息\n- right: deletion\n  text: 删除您主动发布的文字、图片、语音等内容\n- right: withdraw consent\n  text: 通过操作系统撤回对麦克风、摄像头、相册、用户动态等功能的授权\n\
  - right: copy/export\n  text: 复制您的注册信息、服务使用记录等个人信息，导出为电子文件\nsale_or_sharing:\n  stance: conditional\n  text: 我们不会将您的个人信息向任何第三方无偿共享、有偿售卖，仅在以下法定情形下，在必要范围内共享\n"
source_yaml_url: https://artifacts.apis.io/kook/privacy/kook-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from KOOK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice Communication
- Gaming
- Community
- Real-Time
---
