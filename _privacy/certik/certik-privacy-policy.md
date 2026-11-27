---
api_specs:
- filename: certik-security-score-api-openapi.yml
  format: yaml
  label: CertiK Security Score API
  slug: certik-security-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certik/openapi/certik-security-score-api-openapi.yml
- filename: certik-token-scan-api-openapi.yml
  format: yaml
  label: CertiK Token Scan API
  slug: certik-token-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certik/openapi/certik-token-scan-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses usernames passwords contact or authentication data
  - category: financial
    text: payment details (for requested services only)
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about your activity in the Services (such as the date/time stamps associated with your usage, pages and files viewed, searches, and other actions you take
  - category: communication
    text: contact preferences
  deletion:
    route: Account termination request or data subject access request
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, improve, and administer services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: fraud monitoring and prevention
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: identify usage trends
    text: To identify usage trends. We may process information about how you use our Services to better understand how they are being used so we can improve them.
  retention:
  - period: null
    scope: personal information generally
    text: We will only keep your personal information for as long as it is necessary for the purposes set out in this Privacy Notice, unless a longer retention period is required or permitted by law (such as tax, accounting, or other legal requirements).
  - period: As long as the user has an account with us
    scope: category A, B, F, G data
    text: Category A - As long as the user has an account with us
  rights:
  - right: access
    text: right (i) to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: (ii) to request rectification or erasure
  - right: restrict processing
    text: (iii) to restrict the processing of your personal information
  - right: data portability
    text: (iv) if applicable, to data portability
  - right: object to processing
    text: In certain circumstances, you may also have the right to object to the processing of your personal information.
  - right: withdraw consent
    text: You have the right to withdraw your consent at any time.
  - right: opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CertiK
provenance_date: '2026-11-09'
provider_name: CertiK
provider_slug: certik
slug: certik-privacy-policy
source_date: '2026-11-09'
source_filename: certik-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.certik.com/company/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CertiK\naid: certik\nurl: https://www.certik.com/company/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names email addresses usernames passwords contact or authentication data\n- category: financial\n  text: payment details (for requested services only)\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category:\
  \ location\n  text: Location Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: information about your activity in the Services (such as the date/time stamps associated with your usage,\n    pages and files viewed, searches, and other actions you take\n- category: communication\n  text: contact preferences\npurposes:\n- purpose: provide, improve, and administer services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: fraud monitoring and prevention\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: identify usage trends\n  text: To identify usage trends. We may process information about how you use our Services\
  \ to better understand\n    how they are being used so we can improve them.\nretention:\n- scope: personal information generally\n  period: null\n  text: We will only keep your personal information for as long as it is necessary for the purposes set out in this\n    Privacy Notice, unless a longer retention period is required or permitted by law (such as tax, accounting, or\n    other legal requirements).\n- scope: category A, B, F, G data\n  period: As long as the user has an account with us\n  text: Category A - As long as the user has an account with us\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account termination request or data subject access request\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: access\n  text: right (i) to request access and obtain a copy of your\
  \ personal information\n- right: rectification or erasure\n  text: (ii) to request rectification or erasure\n- right: restrict processing\n  text: (iii) to restrict the processing of your personal information\n- right: data portability\n  text: (iv) if applicable, to data portability\n- right: object to processing\n  text: In certain circumstances, you may also have the right to object to the processing of your personal information.\n- right: withdraw consent\n  text: You have the right to withdraw your consent at any time.\n- right: opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold or shared any personal information to third\
  \ parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/certik/privacy/certik-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 20 quoted statements, read from CertiK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Web3
- Blockchain
- Smart Contract Security
- Security Auditing
- Threat Intelligence
---
