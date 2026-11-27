---
api_specs:
- filename: 86hc-com-openapi.json
  format: json
  label: Hong Kong Company MCP & Corporate Registry API
  slug: hong-kong-company-mcp-corporate-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/86hc-com/openapi/86hc-com-openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 称谓/姓名、联系电话/WhatsApp/微信号、企业电子邮箱地址
  - category: financial
    text: 支付交易凭证号
  - category: device
    text: 系统网络访问日志（包括 IP 地址、浏览器 User-Agent 及时间戳）
  deletion:
    route: Via compliance contact or online correction channel
    text: 若您对本隐私政策有任何疑问，或欲依法行使《个人资料（私隐）条例》或 GDPR 赋予之数据主体权利，欢迎通过以下途径联系我们的个人资料私隐主任
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Delivering requested registry documents and due diligence reports
    text: 核验、处理并向您电子交付所申请调阅的香港法团法定登记档案存档文件及商业尽职调查报告
  - purpose: Compliance consultation and invoicing
    text: 跟进您的合规咨询服务、开立香港法定发票 (Invoice) 与付款收据 (Receipt)
  - purpose: Infrastructure security
    text: 维护本平台数据基础设施安全，防范恶意批量爬取、黑客攻击及落实网络安全审计
  residency:
  - region: Hong Kong
    text: 静态数据采用 AES-256 算法加密存储于香港本地高防云端设施中
  retention:
  - period: null
    scope: Business accounts and accounting records
    text: 业务账目与会计凭据强制保留至少 7 年
  rights:
  - right: Access and correction
    text: 查阅与更正权： 依法申请查阅本平台留存之个人资料副本，并对错漏处申请校准更新
  - right: Removal/blocking of corporate information
    text: 法定屏蔽下架权： 符合法定事由（法团已解散、司法诉讼已结案、个人证件脱敏等）之主体，可通过本平台 【企业信息异议通道】 申请屏蔽下架
  - right: Regulatory complaint
    text: 监管投诉权： 有权向香港个人资料私隐专员公署 (PCPD) 提出合规监管投诉
  role:
    text: 恒诚商务有限公司 （英文全称： HC BUSINESS LIMITED ，香港商业登记证号 BRN： 66820292 ，持牌信托与公司服务提供者 TCSP 牌照编号： TC006431 ，以下简称“恒诚商务”或“我们”）作为 86hc.com 平台的运营主体
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: 恒诚商务绝不会将您的个人资料出售、出租或非法转让给任何第三方。
  subprocessors:
    text: 为提供全球加速与高防服务，本平台采用腾讯云香港数据中心与高防网络设施。
    url: null
  transfers:
  - mechanism: SCC
    text: 相关基础设施合作伙伴均已签署并严格遵循欧盟委员会认可的 标准合同条款 (Standard Contractual Clauses - SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 恒诚
provenance_date: '2026-11-09'
provider_name: 恒诚
provider_slug: 86hc-com
slug: 86hc-com-privacy-policy
source_date: '2026-11-09'
source_filename: 86hc-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.86hc.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 恒诚\naid: 86hc-com\nurl: https://www.86hc.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 恒诚商务有限公司 （英文全称： HC BUSINESS LIMITED ，香港商业登记证号 BRN： 66820292 ，持牌信托与公司服务提供者 TCSP 牌照编号： TC006431 ，以下简称“恒诚商务”或“我们”）作为\n    86hc.com 平台的运营主体\ndata_categories:\n- category: identifying\n  text: 称谓/姓名、联系电话/WhatsApp/微信号、企业电子邮箱地址\n- category: financial\n  text: 支付交易凭证号\n- category: device\n  text: 系统网络访问日志（包括 IP 地址、浏览器 User-Agent 及时间戳）\npurposes:\n- purpose: Delivering requested registry documents and due diligence reports\n  text: 核验、处理并向您电子交付所申请调阅的香港法团法定登记档案存档文件及商业尽职调查报告\n- purpose: Compliance\
  \ consultation and invoicing\n  text: 跟进您的合规咨询服务、开立香港法定发票 (Invoice) 与付款收据 (Receipt)\n- purpose: Infrastructure security\n  text: 维护本平台数据基础设施安全，防范恶意批量爬取、黑客攻击及落实网络安全审计\nretention:\n- scope: Business accounts and accounting records\n  period: null\n  text: 业务账目与会计凭据强制保留至少 7 年\nresidency:\n- region: Hong Kong\n  text: 静态数据采用 AES-256 算法加密存储于香港本地高防云端设施中\ntransfers:\n- mechanism: SCC\n  text: 相关基础设施合作伙伴均已签署并严格遵循欧盟委员会认可的 标准合同条款 (Standard Contractual Clauses - SCCs)\nsubprocessors:\n  url: null\n  text: 为提供全球加速与高防服务，本平台采用腾讯云香港数据中心与高防网络设施。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Via compliance contact or online correction channel\n  text: 若您对本隐私政策有任何疑问，或欲依法行使《个人资料（私隐）条例》或 GDPR 赋予之数据主体权利，欢迎通过以下途径联系我们的个人资料私隐主任\nrights:\n- right: Access and correction\n  text: 查阅与更正权： 依法申请查阅本平台留存之个人资料副本，并对错漏处申请校准更新\n- right: Removal/blocking of corporate information\n  text: 法定屏蔽下架权： 符合法定事由（法团已解散、司法诉讼已结案、个人证件脱敏等）之主体，可通过本平台 【企业信息异议通道】 申请屏蔽下架\n- right: Regulatory complaint\n  text: 监管投诉权：\
  \ 有权向香港个人资料私隐专员公署 (PCPD) 提出合规监管投诉\nsale_or_sharing:\n  stance: prohibited\n  text: 恒诚商务绝不会将您的个人资料出售、出租或非法转让给任何第三方。\n"
source_yaml_url: https://artifacts.apis.io/86hc-com/privacy/86hc-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from 恒诚's own page on 2026-11-09.
synthetic: false
tags:
- Hong Kong
- Business Intelligence
- Due Diligence
- Corporate Services
- Compliance
---
