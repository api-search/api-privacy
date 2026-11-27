---
api_specs:
- filename: domob-reporting-api-openapi.yml
  format: yaml
  label: domob Reporting API
  slug: domob-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/domob/openapi/domob-reporting-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: location
    text: 粗略位置信息 【仅 Android】基站、附近的WIFI、连接的WIFI
  - category: device
    text: 设备制造商、品牌、设备型号、操作系统版本、屏幕分辨率、屏幕方向、屏幕DPI、IP地址、时区、网络类型、运营商
  - category: identifying
    text: 【仅Android】OAID
  - category: behavioral
    text: 【双端】如产品交互数据、广告数据（如展示、点击、转化广告数据）
  - category: device
    text: 【双端】宿主应用的包名、版本号
  deletion:
    route: deleted or anonymised after retention period or on developer instruction
    text: 超出与开发者约定的存储期限后，或者接到开发者的相应指令后，我们将对您的个人信息进行删除或匿名化处理，但法律法规另有规定的除外。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: advertising delivery
    text: 多盟广告SDK的基本业务功能为在开发者应用中进行广告投放活动，包括广告展示、监测、归因及投放效果分析与优化。
  - purpose: anti-fraud
    text: 设备制造商、品牌、设备型号、操作系统版本、屏幕分辨率、屏幕方向、屏幕DPI、IP地址、时区、网络类型、运营商
  - purpose: crash and performance diagnostics
    text: 最大程度减少App崩溃、确保服务器正常运行、提升可扩展性和性能
  residency:
  - region: China mainland
    text: 我们依照法律法规的规定，将在中华人民共和国境内运营过程中收集和产生的个人信息存储于境内。
  retention:
  - period: null
    scope: personal information provided for service purposes
    text: 我们仅在为开发者提供服务之目的所必需的期间内保留您的信息。
  rights:
  - right: access, copy, correct, supplement, delete, withdraw consent
    text: 包括查阅、复制、更正、补充、删除、撤回授权同意等权利
  role:
    text: 我们仅按照开发者的委托和指示处理您的个人信息，并接受开发者与您对个人信息使用活动的监督。
    value: processor
  sale_or_sharing:
    stance: conditional
    text: 我们可能与委托我们进行推广和广告投放的合作伙伴和其他合作伙伴如广告主、代理商、广告监测服务商、进行广告投放与优化合作的关联方等（合称"广告合作方"）共享分析去标识化或匿名化处理的设备信息、统计信息、标签信息或其他由多盟广告SDK所采集的必要信息。
  subprocessors:
    text: 多盟接入的合作方及其个人信息处理情况请详细查阅多盟广告SDK第三方信息共享清单。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: domob
provenance_date: '2026-11-09'
provider_name: domob
provider_slug: domob
slug: domob-privacy-policy
source_date: '2026-11-09'
source_filename: domob-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.domob.cn/article?id=advertiserPlatformPrivacyPolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: domob\naid: domob\nurl: https://www.domob.cn/article?id=advertiserPlatformPrivacyPolicy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: 我们仅按照开发者的委托和指示处理您的个人信息，并接受开发者与您对个人信息使用活动的监督。\ndata_categories:\n- category: location\n  text: 粗略位置信息 【仅 Android】基站、附近的WIFI、连接的WIFI\n- category: device\n  text: 设备制造商、品牌、设备型号、操作系统版本、屏幕分辨率、屏幕方向、屏幕DPI、IP地址、时区、网络类型、运营商\n- category: identifying\n  text: 【仅Android】OAID\n- category: behavioral\n  text: 【双端】如产品交互数据、广告数据（如展示、点击、转化广告数据）\n- category: device\n  text: 【双端】宿主应用的包名、版本号\npurposes:\n- purpose: advertising delivery\n  text: 多盟广告SDK的基本业务功能为在开发者应用中进行广告投放活动，包括广告展示、监测、归因及投放效果分析与优化。\n\
  - purpose: anti-fraud\n  text: 设备制造商、品牌、设备型号、操作系统版本、屏幕分辨率、屏幕方向、屏幕DPI、IP地址、时区、网络类型、运营商\n- purpose: crash and performance diagnostics\n  text: 最大程度减少App崩溃、确保服务器正常运行、提升可扩展性和性能\nretention:\n- scope: personal information provided for service purposes\n  period: null\n  text: 我们仅在为开发者提供服务之目的所必需的期间内保留您的信息。\nresidency:\n- region: China mainland\n  text: 我们依照法律法规的规定，将在中华人民共和国境内运营过程中收集和产生的个人信息存储于境内。\ntransfers: []\nsubprocessors:\n  url: null\n  text: 多盟接入的合作方及其个人信息处理情况请详细查阅多盟广告SDK第三方信息共享清单。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: deleted or anonymised after retention period or on developer instruction\n  text: 超出与开发者约定的存储期限后，或者接到开发者的相应指令后，我们将对您的个人信息进行删除或匿名化处理，但法律法规另有规定的除外。\nrights:\n- right: access, copy, correct, supplement, delete, withdraw consent\n  text: 包括查阅、复制、更正、补充、删除、撤回授权同意等权利\nsale_or_sharing:\n  stance: conditional\n  text: 我们可能与委托我们进行推广和广告投放的合作伙伴和其他合作伙伴如广告主、代理商、广告监测服务商、进行广告投放与优化合作的关联方等（合称\"广告合作方\"）共享分析去标识化或匿名化处理的设备信息、统计信息、标签信息或其他由多盟广告SDK所采集的必要信息。\n"
source_yaml_url: https://artifacts.apis.io/domob/privacy/domob-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from domob's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Mobile
- AdTech
- Marketing
- SDK
- DSP
- Monetization
- Reporting
- China
---
