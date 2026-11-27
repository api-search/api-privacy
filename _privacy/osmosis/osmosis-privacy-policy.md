---
api_specs:
- filename: osmosis-agent-api-openapi.yml
  format: yaml
  label: Osmosis Agent API
  slug: osmosis-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-agent-api-openapi.yml
- filename: osmosis-knowledge-api-openapi.yml
  format: yaml
  label: Osmosis Knowledge API
  slug: osmosis-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-knowledge-api-openapi.yml
- filename: osmosis-osmosis-agent-improvement-api-api-openapi.yml
  format: yaml
  label: Osmosis Agent Improvement API
  slug: osmosis-osmosis-agent-improvement-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-osmosis-agent-improvement-api-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Names Email addresses Job titles Usernames Contact preferences Contact or authentication data
  - category: financial
    text: We may collect data necessary to process your payment if you choose to make purchases, such as your payment instrument number, and the security code associated with your payment instrument.
  - category: location
    text: We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: behavioral
    text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically collect when you access or use our Services
  deletion:
    route: Request via data request page or contact email
    text: 'To request to review, update, or delete your personal information, please visit: https://platform.osmosis.ai/data-request.'
  dpa:
    available: true
    text: 'Our Data Processing Agreements that include Standard Contractual Clauses are available here: https://osmosis.ai/legal/dpa .'
    url: https://osmosis.ai/legal/dpa
  purposes:
  - purpose: Provide and administer services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: Marketing communications
    text: We may process the personal information you send to us for our marketing purposes, if this is in accordance with your marketing preferences.
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: null
    scope: Personal information generally
    text: We will only keep your personal information for as long as it is necessary for the purposes set out in this Privacy Policy, unless a longer retention period is required or permitted by law (such as tax, accounting, or other legal requirements).
  - period: As long as the user has an account with us
    scope: Categories A, B, D, F, G, I, K
    text: Category A - As long as the user has an account with us
  rights:
  - right: Access
    text: Right to access your personal data
  - right: Correction
    text: Right to correct inaccuracies in your personal data
  - right: Deletion
    text: Right to request the deletion of your personal data
  - right: Portability
    text: Right to obtain a copy of the personal data you previously shared with us
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We have implemented measures to protect your personal information, including by using the European Commission's Standard Contractual Clauses for transfers of personal information between our group companies and between us and our third-party providers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Osmosis
provenance_date: '2026-11-10'
provider_name: Osmosis
provider_slug: osmosis
slug: osmosis-privacy-policy
source_date: '2026-11-10'
source_filename: osmosis-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://osmosis.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Osmosis\naid: osmosis\nurl: https://osmosis.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: Names Email addresses Job titles Usernames Contact preferences Contact or authentication data\n- category: financial\n  text: We may collect data necessary to process your payment if you choose to make purchases, such as your payment\n    instrument number, and the security code associated with your payment instrument.\n- category: location\n\
  \  text: We collect location data such as information about your device's location, which can be either precise or\n    imprecise.\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: behavioral\n  text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information\n    our servers automatically collect when you access or use our Services\npurposes:\n- purpose: Provide and administer services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: Marketing communications\n  text: We may process the personal information you send to us for our marketing purposes, if this is in accordance\n    with your marketing preferences.\nretention:\n- scope: Personal information generally\n  period:\
  \ null\n  text: We will only keep your personal information for as long as it is necessary for the purposes set out in this\n    Privacy Policy, unless a longer retention period is required or permitted by law (such as tax, accounting, or\n    other legal requirements).\n- scope: Categories A, B, D, F, G, I, K\n  period: As long as the user has an account with us\n  text: Category A - As long as the user has an account with us\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: SCC\n  text: We have implemented measures to protect your personal information, including by using the European Commission's\n    Standard Contractual Clauses for transfers of personal information between our group companies and between us\n    and our third-party providers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://osmosis.ai/legal/dpa\n  text: 'Our Data Processing Agreements that include Standard Contractual\
  \ Clauses are available here: https://osmosis.ai/legal/dpa\n    .'\ndeletion:\n  route: Request via data request page or contact email\n  text: 'To request to review, update, or delete your personal information, please visit: https://platform.osmosis.ai/data-request.'\nrights:\n- right: Access\n  text: Right to access your personal data\n- right: Correction\n  text: Right to correct inaccuracies in your personal data\n- right: Deletion\n  text: Right to request the deletion of your personal data\n- right: Portability\n  text: Right to obtain a copy of the personal data you previously shared with us\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance:\
  \ unstated\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/osmosis/privacy/osmosis-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Osmosis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Reinforcement Learning
- LLM
- Post-Training
- Model Training
- Agents
- Machine Learning
- Developer Tools
---
