---
api_specs:
- filename: yutori-browsing-api-openapi.yml
  format: yaml
  label: Yutori Browsing API
  slug: yutori-browsing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-browsing-api-openapi.yml
- filename: yutori-chat-completions-api-openapi.yml
  format: yaml
  label: Yutori Chat Completions API
  slug: yutori-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-chat-completions-api-openapi.yml
- filename: yutori-health-api-openapi.yml
  format: yaml
  label: Yutori Health API
  slug: yutori-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-health-api-openapi.yml
- filename: yutori-research-api-openapi.yml
  format: yaml
  label: Yutori Research API
  slug: yutori-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-research-api-openapi.yml
- filename: yutori-scouting-api-openapi.yml
  format: yaml
  label: Yutori Scouting API
  slug: yutori-scouting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-scouting-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: names email addresses contact preferences phone numbers contact or authentication data
  - category: device
    text: device and usage information, such as your IP address, browser and device characteristics, operating system, language preferences, referring URLs, device name, country, location
  - category: location
    text: We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about how and when you use our Services
  - category: other
    text: If you include personal data or reference external content in your Inputs, we will collect that information
  deletion:
    route: data subject access request
    text: To request to review, update, or delete your personal information, please fill out and submit a data subject access request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, improve, and administer Services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: marketing communications
    text: To send you marketing and promotional communications.
  - purpose: identify usage trends
    text: To identify usage trends.
  retention:
  - period: As long as the user has an account with us
    scope: Category A (identifiers)
    text: Category A - As long as the user has an account with us
  - period: period of time in which users have an account with us
    scope: personal information generally
    text: No purpose in this notice will require us keeping your personal information for longer than the period of time in which users have an account with us
  rights:
  - right: access
    text: Right to access your personal data
  - right: deletion
    text: Right to request the deletion of your personal data
  - right: correction
    text: Right to correct inaccuracies in your personal data
  - right: opt out of targeted advertising and sale
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yutori
provenance_date: '2026-11-10'
provider_name: Yutori
provider_slug: yutori
slug: yutori-privacy-policy
source_date: '2026-11-10'
source_filename: yutori-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://yutori.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yutori\naid: yutori\nurl: https://yutori.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: contact\n  text: names email addresses contact preferences phone numbers contact or authentication data\n- category: device\n  text: device and usage information, such as your IP address, browser and device characteristics, operating system,\n    language preferences, referring URLs, device name, country, location\n- category: location\n  text: We collect location data such\
  \ as information about your device's location, which can be either precise or\n    imprecise.\n- category: behavioral\n  text: information about how and when you use our Services\n- category: other\n  text: If you include personal data or reference external content in your Inputs, we will collect that information\npurposes:\n- purpose: provide, improve, and administer Services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: marketing communications\n  text: To send you marketing and promotional communications.\n- purpose: identify usage trends\n  text: To identify usage trends.\nretention:\n- scope: Category A (identifiers)\n  period: As long as the user has an account with us\n  text: Category A - As long as the user has an account with us\n- scope: personal information generally\n  period: period of time in which users have an account with us\n  text:\
  \ No purpose in this notice will require us keeping your personal information for longer than the period of\n    time in which users have an account with us\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: data subject access request\n  text: To request to review, update, or delete your personal information, please fill out and submit a data subject\n    access request\nrights:\n- right: access\n  text: Right to access your personal data\n- right: deletion\n  text: Right to request the deletion of your personal data\n- right: correction\n  text: Right to correct inaccuracies in your personal data\n- right: opt out of targeted advertising and sale\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell or share personal information in the future belonging to website visitors, users,\
  \ and other\n    consumers.\n"
source_yaml_url: https://artifacts.apis.io/yutori/privacy/yutori-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Yutori's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Browser Automation
- Web Monitoring
- Research
- MCP
- LLM
- Foundation Models
---
