---
api_specs:
- filename: typesafe-ai-models-api-openapi.yml
  format: yaml
  label: TypeSafe AI Models API
  slug: typesafe-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesafe-ai/openapi/typesafe-ai-models-api-openapi.yml
- filename: typesafe-ai-systemone-api-openapi.yml
  format: yaml
  label: TypeSafe AI Systemone API
  slug: typesafe-ai-systemone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesafe-ai/openapi/typesafe-ai-systemone-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Information. We collect the personal data you provide to create, update, or manage your Services account, including, for example, your name and email address.
  - category: contact
    text: Contact Information. We may collect your personal data when you inquire about us, the Services, or when you otherwise interact with us.
  - category: communication
    text: If you contact us directly, we may receive personal data about you, such as your name, email address, the contents of a message or attachments that you may send to us.
  - category: financial
    text: Payment Information. If you make a payment to us, your payment-related information, such as credit card or other financial information, may be collected by our third-party payment processor on our behalf.
  - category: location
    text: Location Information. We may collect and infer your general location information, including, for example, by collecting and using your internet protocol (IP) address.
  - category: device
    text: Device Information. We may receive information about your device and software, including IP address, device type, device identifiers, web browser type and version, and operating system version.
  - category: behavioral
    text: Usage Information. We automatically receive data about your interactions with the Services, such as the dates and times of your use of the Services
  - category: professional
    text: We will collect the information you choose to provide on your resume, such as your education and employment experience.
  deletion:
    route: Request to TypeSafe
    text: When you request that we do so, we take measures to delete your personal data or keep it in a form that does not permit identifying you when this personal data is no longer reasonably necessary for the purposes for which we process it, unless we are required by law to keep this data for a longer period.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve Services
    text: To provide, maintain, improve, debug, administer, and enhance the Services;
  - purpose: Marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials that may be relevant, valuable or otherwise of interest to you;
  - purpose: Customer support and communications
    text: To communicate with you, provide you with relevant updates and other information, provide information that you request, respond to comments and questions, and otherwise provide customer support;
  - purpose: Fraud and abuse prevention
    text: To find and prevent fraud and abuse, resolve disputes, or respond to trust and safety issues;
  - purpose: Live request hosting
    source: https://trust.typesafe.ai/subprocessors
    text: Customer information for live requests is stored and processed on databases, caches and compute nodes within AWS
  - purpose: AI prompt processing
    source: https://trust.typesafe.ai/subprocessors
    text: Customer AI prompts are processed, but not stored, on compute nodes managed by Modal
  - purpose: Support collaboration
    source: https://trust.typesafe.ai/subprocessors
    text: Information about customers may be surfaced by through our collaboration tool, Slack, in the process of collaboration.
  - purpose: Email and document exchange
    source: https://trust.typesafe.ai/subprocessors
    text: Customer information and their data may be exchanged through our email and document provider, Google, at their request, e.g., in emails to our service inbox.
  - purpose: Customer support
    source: https://trust.typesafe.ai/subprocessors
    text: Customer contact information and support communications, including data customers submit in support requests, are stored and processed in Pylon to manage and respond to customer inquiries.
  residency:
  - region: USA
    source: https://trust.typesafe.ai/subprocessors
    text: Cloud provider USA Customer information for live requests is stored and processed on databases, caches and compute nodes within AWS
  - region: Worldwide
    source: https://trust.typesafe.ai/subprocessors
    text: Microsoft Azure Cloud infrastructure Worldwide azure.com
  retention:
  - period: null
    scope: Personal data
    text: We retain personal data about you for as long as reasonably necessary to provide you with the Services, or otherwise in support of our business or commercial purposes.
  - period: null
    scope: AI prompts on Modal, Nebius, CoreWeave
    source: https://trust.typesafe.ai/subprocessors
    text: Customer AI prompts are processed, but not stored
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not “sell” personal data nor “share” personal data for cross-contextual behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you choose to use the Services from the EEA, the UK or other regions of the world with laws governing data collection and use that may differ from U.S. law, then please note that you are transferring your personal data outside of those regions to the U.S. for storage and processing.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TypeSafe AI
provenance_date: '2026-11-10'
provider_name: TypeSafe AI
provider_slug: typesafe-ai
slug: typesafe-ai-privacy-policy
source_date: '2026-11-10'
source_filename: typesafe-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://typesafe.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TypeSafe AI\naid: typesafe-ai\nurl: https://typesafe.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.typesafe.ai/subprocessors\n  - https://typesafe.ai/legal/privacy-policy\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account Information. We collect the personal data you provide to create, update, or manage your Services\n    account, including, for example, your name and email address.\n- category: contact\n  text: Contact Information. We may collect your personal data when you inquire about us, the Services, or when\n    you\
  \ otherwise interact with us.\n- category: communication\n  text: If you contact us directly, we may receive personal data about you, such as your name, email address, the\n    contents of a message or attachments that you may send to us.\n- category: financial\n  text: Payment Information. If you make a payment to us, your payment-related information, such as credit card\n    or other financial information, may be collected by our third-party payment processor on our behalf.\n- category: location\n  text: Location Information. We may collect and infer your general location information, including, for example,\n    by collecting and using your internet protocol (IP) address.\n- category: device\n  text: Device Information. We may receive information about your device and software, including IP address, device\n    type, device identifiers, web browser type and version, and operating system version.\n- category: behavioral\n  text: Usage Information. We automatically receive data about\
  \ your interactions with the Services, such as the\n    dates and times of your use of the Services\n- category: professional\n  text: We will collect the information you choose to provide on your resume, such as your education and employment\n    experience.\npurposes:\n- purpose: Provide and improve Services\n  text: To provide, maintain, improve, debug, administer, and enhance the Services;\n- purpose: Marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n    that may be relevant, valuable or otherwise of interest to you;\n- purpose: Customer support and communications\n  text: To communicate with you, provide you with relevant updates and other information, provide information that\n    you request, respond to comments and questions, and otherwise provide customer support;\n- purpose: Fraud and abuse prevention\n  text: To find and prevent fraud and abuse, resolve disputes, or respond to trust\
  \ and safety issues;\n- purpose: Live request hosting\n  text: Customer information for live requests is stored and processed on databases, caches and compute nodes within\n    AWS\n  source: https://trust.typesafe.ai/subprocessors\n- purpose: AI prompt processing\n  text: Customer AI prompts are processed, but not stored, on compute nodes managed by Modal\n  source: https://trust.typesafe.ai/subprocessors\n- purpose: Support collaboration\n  text: Information about customers may be surfaced by through our collaboration tool, Slack, in the process of\n    collaboration.\n  source: https://trust.typesafe.ai/subprocessors\n- purpose: Email and document exchange\n  text: Customer information and their data may be exchanged through our email and document provider, Google, at\n    their request, e.g., in emails to our service inbox.\n  source: https://trust.typesafe.ai/subprocessors\n- purpose: Customer support\n  text: Customer contact information and support communications, including data\
  \ customers submit in support requests,\n    are stored and processed in Pylon to manage and respond to customer inquiries.\n  source: https://trust.typesafe.ai/subprocessors\nretention:\n- scope: Personal data\n  period: null\n  text: We retain personal data about you for as long as reasonably necessary to provide you with the Services,\n    or otherwise in support of our business or commercial purposes.\n- scope: AI prompts on Modal, Nebius, CoreWeave\n  period: null\n  text: Customer AI prompts are processed, but not stored\n  source: https://trust.typesafe.ai/subprocessors\nresidency:\n- region: USA\n  text: Cloud provider USA Customer information for live requests is stored and processed on databases, caches and\n    compute nodes within AWS\n  source: https://trust.typesafe.ai/subprocessors\n- region: Worldwide\n  text: Microsoft Azure Cloud infrastructure Worldwide azure.com\n  source: https://trust.typesafe.ai/subprocessors\ntransfers:\n- mechanism: other\n  text: If you choose\
  \ to use the Services from the EEA, the UK or other regions of the world with laws governing\n    data collection and use that may differ from U.S. law, then please note that you are transferring your personal\n    data outside of those regions to the U.S. for storage and processing.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to TypeSafe\n  text: When you request that we do so, we take measures to delete your personal data or keep it in a form that\n    does not permit identifying you when this personal data is no longer reasonably necessary for the purposes for\n    which we process it, unless we are required by law to keep this data for a longer period.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not “sell” personal data nor “share” personal data for cross-contextual behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/typesafe-ai/privacy/typesafe-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- sale_or_sharing
summary_line: 24 quoted statements, read from TypeSafe AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Classification
- Content Moderation
- Decision Support
- Structured Outputs
- Inference
- LLM Alternative
- Agent Skills
- MCP
- Agent-Native
- Developer Tools
- A2A
---
