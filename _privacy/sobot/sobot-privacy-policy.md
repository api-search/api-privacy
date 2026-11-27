---
api_specs:
- filename: sobot-agent-api-openapi.yml
  format: yaml
  label: Sobot Agent API
  slug: sobot-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-agent-api-openapi.yml
- filename: sobot-basic-public-service-api-openapi.yml
  format: yaml
  label: Sobot basic-public/service/坐席信息管理 API
  slug: sobot-basic-public-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-basic-public-service-api-openapi.yml
- filename: sobot-exts-api-openapi.yml
  format: yaml
  label: Sobot Exts API
  slug: sobot-exts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-exts-api-openapi.yml
- filename: sobot-user-api-openapi.yml
  format: yaml
  label: Sobot User API
  slug: sobot-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-user-api-openapi.yml
- filename: sobot-openapi-plant-store-api-openapi.yml
  format: yaml
  label: Sobot OpenAPI Plant Store API
  slug: sobot-openapi-plant-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sobot/openapi/sobot-openapi-plant-store-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: you will need to provide your contact name, mobile phone number and email address, as well as your company name
  - category: identifying
    text: real name and mobile phone number
  - category: device
    text: device identifier, Android ID, operating system type, system version, App package name, App version, device type, device manufacturer, device model, screen size, network type
  - category: behavioral
    text: the date and time of access, source URL, browsing history, search query, click to view, follow, browser and version
  - category: communication
    text: Records of your communications, including correspondence, calls, and related content
  deletion:
    route: Written request to dpo@sobot.io or Online Inquiry in the Admin Center; agent self-deletion in Sobot app
    text: You can also send a written request to dpo@sobot.io.
  dpa:
    available: true
    text: we will require our partners to sign a data processing agreement or include provisions on data protection in the cooperation agreement
    url: null
  purposes:
  - purpose: Account registration and service provision
    text: To register an account with our services, you will need to provide your contact name, mobile phone number and email address
  - purpose: Security and fraud prevention
    text: to protect you or the public from infringement of personal property, to better prevent phishing sites, fraud, network vulnerabilities, computer viruses, network attacks, network intrusion and other security risks
  - purpose: Algorithm training for chatbot
    text: we may carry out algorithm training, such as optimizing the functions of Chatbot and emotion analysis, and enrich the internal knowledge base for Chatbot.
  residency:
  - region: Singapore and United States
    text: stored our proprietary servers in Singapore or the United States
  retention:
  - period: 3 months after deletion
    scope: Company account data
    text: company data is deleted 3 months after deletion and cannot be recovered
  - period: null
    scope: Identity and account information
    text: We store your identity and account information for as long as your account is active and a reasonable period thereafter
  rights:
  - right: Access
    text: You have the right to access your personal data.
  - right: Correction
    text: When you wish to change your personal data, you can do it directly in the intelligent customer service system
  - right: Copy of personal data
    text: You have the right to obtain a copy of your personal information
  - right: Erasure or rectification (EEA)
    text: To request the rectification or erasure of your personal data held by us
  - right: Object to marketing and profiling (EEA)
    text: To object to the further processing of your personal data, including the right to object to marketing and profiling
  - right: Withdraw consent
    text: You may withdraw consent and request us to stop using and/or disclosing your personal data
  role:
    text: Sobot Technologies PTE. LTD ( "Sobot", "we", "us", or "our") may collect, use, disclose or otherwise process personal data through our products and services in accordance with the Personal Data Protection Act of Singapore ("PDPA")
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We utilize standard contractual clauses approved by the European Commission for data transfers from the EEA to other regions or countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sobot
provenance_date: '2026-11-10'
provider_name: Sobot
provider_slug: sobot
slug: sobot-privacy-policy
source_date: '2026-11-10'
source_filename: sobot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sobot.io/privacy-protection-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sobot\naid: sobot\nurl: https://www.sobot.io/privacy-protection-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Sobot Technologies PTE. LTD ( \"Sobot\", \"we\", \"us\", or \"our\") may collect, use, disclose or otherwise process\n    personal data through our products and services in accordance with the Personal Data Protection Act of Singapore\n    (\"PDPA\")\ndata_categories:\n- category: contact\n  text: you will need to provide your contact name, mobile phone number and email address, as well as your company\n    name\n- category: identifying\n  text: real name and mobile phone\
  \ number\n- category: device\n  text: device identifier, Android ID, operating system type, system version, App package name, App version, device\n    type, device manufacturer, device model, screen size, network type\n- category: behavioral\n  text: the date and time of access, source URL, browsing history, search query, click to view, follow, browser\n    and version\n- category: communication\n  text: Records of your communications, including correspondence, calls, and related content\npurposes:\n- purpose: Account registration and service provision\n  text: To register an account with our services, you will need to provide your contact name, mobile phone number\n    and email address\n- purpose: Security and fraud prevention\n  text: to protect you or the public from infringement of personal property, to better prevent phishing sites, fraud,\n    network vulnerabilities, computer viruses, network attacks, network intrusion and other security risks\n- purpose: Algorithm training for\
  \ chatbot\n  text: we may carry out algorithm training, such as optimizing the functions of Chatbot and emotion analysis, and\n    enrich the internal knowledge base for Chatbot.\nretention:\n- scope: Company account data\n  period: 3 months after deletion\n  text: company data is deleted 3 months after deletion and cannot be recovered\n- scope: Identity and account information\n  period: null\n  text: We store your identity and account information for as long as your account is active and a reasonable period\n    thereafter\nresidency:\n- region: Singapore and United States\n  text: stored our proprietary servers in Singapore or the United States\ntransfers:\n- mechanism: SCC\n  text: We utilize standard contractual clauses approved by the European Commission for data transfers from the\n    EEA to other regions or countries.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we will require our partners to sign a data processing agreement or include\
  \ provisions on data protection\n    in the cooperation agreement\ndeletion:\n  route: Written request to dpo@sobot.io or Online Inquiry in the Admin Center; agent self-deletion in Sobot app\n  text: You can also send a written request to dpo@sobot.io.\nrights:\n- right: Access\n  text: You have the right to access your personal data.\n- right: Correction\n  text: When you wish to change your personal data, you can do it directly in the intelligent customer service system\n- right: Copy of personal data\n  text: You have the right to obtain a copy of your personal information\n- right: Erasure or rectification (EEA)\n  text: To request the rectification or erasure of your personal data held by us\n- right: Object to marketing and profiling (EEA)\n  text: To object to the further processing of your personal data, including the right to object to marketing and\n    profiling\n- right: Withdraw consent\n  text: You may withdraw consent and request us to stop using and/or disclosing your personal\
  \ data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sobot/privacy/sobot-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 21 quoted statements, read from Sobot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Contact Center
- Customer Service
- Live Chat
- Chatbots
- Voice
- Ticketing
- WhatsApp
- Omnichannel
- Communications
- Artificial Intelligence
---
