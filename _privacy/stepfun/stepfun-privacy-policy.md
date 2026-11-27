---
api_specs:
- filename: stepfun-realtime-asyncapi.yml
  format: yaml
  label: StepFun Realtime API
  slug: realtime-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/stepfun/asyncapi/stepfun-realtime-asyncapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 您的 姓名、身份证号码信息
  - category: contact
    text: 手机号码
  - category: contact
    text: 您的电子邮箱
  - category: biometric
    text: 您的 人脸信息
  - category: communication
    text: 您主动输入的信息（包括文字、语音、图片、视频、音频、文本、链接等多种形式）以及服务的输出信息
  - category: financial
    text: 您的充值记录、账户资金及其使用情况
  - category: device
    text: 您的硬件型号、操作系统版本号、设备标识符、IP地址
  - category: behavioral
    text: 对话记录
  deletion:
    route: account cancellation via platform or contact email; deletion request via contact methods
    text: 您可以通过本平台自主申请注销账号，您也可以通过本隐私政策中提供的联系方式与我们联系申请注销您的账号
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account registration and login
    text: 我们会通过发送 验证码 的方式来验证您的身份是否有效
  - purpose: real-name authentication
    text: 为保障平台及账号安全、核验用户个人或企业身份，并防止恶意注册
  - purpose: AI conversation and content generation
    text: 为了向您提供智能对话、内容生成及AI助手服务
  - purpose: service operation and security
    text: 为了维护我们服务的正常运行，保护您或其他用户或公众的合法利益免受损失
  residency:
  - region: China
    text: 我们依照法律法规的规定，将在境内运营过程中收集和产生的您的个人信息存储于中华人民共和国境内
  retention:
  - period: null
    scope: personal information generally
    text: 我们仅在为提供本平台相关服务之目的所必需的期间内保留您的个人信息
  - period: null
    scope: account cancellation or deletion
    text: 如果您注销账户、主动删除个人信息或超出必要的期限后，我们将对您的个人信息进行删除或匿名化处理
  rights:
  - right: access
    text: 您可以在本平台页面查看您的账号信息
  - right: copy and portability
    text: 您有权通过本隐私政策中提供的联系方式联系我们要求将您的个人信息转移至您指定的个人信息处理者
  - right: correction
    text: 若您发现我们处理的关于您的个人信息有错误时，您有权对错误或不完整的信息作出更正或更新
  - right: deletion
    text: 您也可以通过本隐私政策中提供的联系方式联系我们提出删除个人信息的请求
  - right: withdraw consent
    text: 您也可以通过本隐私政策中提供的联系方式联系向我们提出撤回同意或改变您授权同意的范围的请求
  role:
    text: 本平台由上海阶跃星辰智能科技股份有限公司提供
    value: controller
  sale_or_sharing:
    stance: conditional
    text: 一般情况下，我们不会向其他任何公司、组织和个人提供您的个人信息，若我们需要向第三方共享您的个人信息的，我们将向您告知接收方的名称或者姓名、联系方式、处理目的、处理方式和个人信息的种类，并事先获得您的单独同意
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: StepFun
provenance_date: '2026-11-10'
provider_name: StepFun
provider_slug: stepfun
slug: stepfun-privacy-policy
source_date: '2026-11-10'
source_filename: stepfun-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://platform.stepfun.com/docs/zh/agreement/userprivacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: StepFun\naid: stepfun\nurl: https://platform.stepfun.com/docs/zh/agreement/userprivacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 本平台由上海阶跃星辰智能科技股份有限公司提供\ndata_categories:\n- category: identifying\n  text: 您的 姓名、身份证号码信息\n- category: contact\n  text: 手机号码\n- category: contact\n  text: 您的电子邮箱\n- category: biometric\n  text: 您的 人脸信息\n- category: communication\n  text: 您主动输入的信息（包括文字、语音、图片、视频、音频、文本、链接等多种形式）以及服务的输出信息\n- category: financial\n  text: 您的充值记录、账户资金及其使用情况\n- category: device\n  text: 您的硬件型号、操作系统版本号、设备标识符、IP地址\n- category: behavioral\n  text: 对话记录\npurposes:\n- purpose: account registration\
  \ and login\n  text: 我们会通过发送 验证码 的方式来验证您的身份是否有效\n- purpose: real-name authentication\n  text: 为保障平台及账号安全、核验用户个人或企业身份，并防止恶意注册\n- purpose: AI conversation and content generation\n  text: 为了向您提供智能对话、内容生成及AI助手服务\n- purpose: service operation and security\n  text: 为了维护我们服务的正常运行，保护您或其他用户或公众的合法利益免受损失\nretention:\n- scope: personal information generally\n  period: null\n  text: 我们仅在为提供本平台相关服务之目的所必需的期间内保留您的个人信息\n- scope: account cancellation or deletion\n  period: null\n  text: 如果您注销账户、主动删除个人信息或超出必要的期限后，我们将对您的个人信息进行删除或匿名化处理\nresidency:\n- region: China\n  text: 我们依照法律法规的规定，将在境内运营过程中收集和产生的您的个人信息存储于中华人民共和国境内\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account cancellation via platform or contact email; deletion request via contact methods\n  text: 您可以通过本平台自主申请注销账号，您也可以通过本隐私政策中提供的联系方式与我们联系申请注销您的账号\nrights:\n- right: access\n  text: 您可以在本平台页面查看您的账号信息\n- right: copy and portability\n  text: 您有权通过本隐私政策中提供的联系方式联系我们要求将您的个人信息转移至您指定的个人信息处理者\n\
  - right: correction\n  text: 若您发现我们处理的关于您的个人信息有错误时，您有权对错误或不完整的信息作出更正或更新\n- right: deletion\n  text: 您也可以通过本隐私政策中提供的联系方式联系我们提出删除个人信息的请求\n- right: withdraw consent\n  text: 您也可以通过本隐私政策中提供的联系方式联系向我们提出撤回同意或改变您授权同意的范围的请求\nsale_or_sharing:\n  stance: conditional\n  text: 一般情况下，我们不会向其他任何公司、组织和个人提供您的个人信息，若我们需要向第三方共享您的个人信息的，我们将向您告知接收方的名称或者姓名、联系方式、处理目的、处理方式和个人信息的种类，并事先获得您的单独同意\n"
source_yaml_url: https://artifacts.apis.io/stepfun/privacy/stepfun-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from StepFun's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Multi-Modal
- Chat Completions
- Audio
- Speech
- Text-to-Speech
- Speech Recognition
- Image
- Real-Time
- Vector Stores
- China
---
