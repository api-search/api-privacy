---
api_specs:
- filename: overshoot-billing-api-openapi.yml
  format: yaml
  label: Overshoot Billing API
  slug: overshoot-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-billing-api-openapi.yml
- filename: overshoot-healthz-api-openapi.yml
  format: yaml
  label: Overshoot Healthz API
  slug: overshoot-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-healthz-api-openapi.yml
- filename: overshoot-metrics-api-openapi.yml
  format: yaml
  label: Overshoot Metrics API
  slug: overshoot-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-metrics-api-openapi.yml
- filename: overshoot-models-api-openapi.yml
  format: yaml
  label: Overshoot Models API
  slug: overshoot-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-models-api-openapi.yml
- filename: overshoot-readyz-api-openapi.yml
  format: yaml
  label: Overshoot Readyz API
  slug: overshoot-readyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-readyz-api-openapi.yml
- filename: overshoot-streams-api-openapi.yml
  format: yaml
  label: Overshoot Streams API
  slug: overshoot-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-streams-api-openapi.yml
- filename: overshoot-v1beta-api-openapi.yml
  format: yaml
  label: Overshoot V1beta API
  slug: overshoot-v1beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-v1beta-api-openapi.yml
- filename: overshoot-chat-completions-api-openapi.yml
  format: yaml
  label: Overshoot Chat Completions API
  slug: overshoot-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overshoot/openapi/overshoot-chat-completions-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: email addresses
  - category: financial
    text: Payment Data. We may collect data necessary to process your payment if you choose to make purchases, such as your payment instrument number, and the security code associated with your payment instrument.
  - category: identifying
    text: Social Media Login Data. We may provide you with the option to register with us using your existing social media account details
  - category: communication
    text: Images and audio, video or call recordings created in connection with our business activities
  - category: behavioral
    text: Analyze how our Services are used so we can improve them to engage and retain users
  deletion:
    route: Contact us; account termination request
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: We may disclose your personal information with our service providers pursuant to a written contract between us and each service provider.
    url: null
  purposes:
  - purpose: account management
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: AI product delivery
    text: To process user-submitted content through third-party AI services (if requested by the user) in order to deliver the core functionality of our API .
  - purpose: security and fraud prevention
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  retention:
  - period: twelve (12) months
    scope: account termination
    text: No purpose in this notice will require us keeping your personal information for longer than twelve (12) months past the termination of the user's account .
  rights:
  - right: access
    text: Right to access your personal data
  - right: deletion
    text: Right to request the deletion of your personal data
  - right: correction
    text: Right to correct inaccuracies in your personal data
  - right: opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law) , the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ( "profiling" )
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not disclosed, sold, or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Overshoot
provenance_date: '2026-11-10'
provider_name: Overshoot
provider_slug: overshoot
slug: overshoot-privacy-policy
source_date: '2026-11-10'
source_filename: overshoot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://platform.overshoot.ai/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Overshoot\naid: overshoot\nurl: https://platform.overshoot.ai/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: contact\n  text: email addresses\n- category: financial\n  text: Payment Data. We may collect data necessary to process your payment if you choose to make purchases, such\n    as your payment instrument number, and the security code associated with your payment instrument.\n- category: identifying\n  text: Social Media Login Data. We may provide you with\
  \ the option to register with us using your existing social\n    media account details\n- category: communication\n  text: Images and audio, video or call recordings created in connection with our business activities\n- category: behavioral\n  text: Analyze how our Services are used so we can improve them to engage and retain users\npurposes:\n- purpose: account management\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: AI product delivery\n  text: To process user-submitted content through third-party AI services (if requested by the user) in order to\n    deliver the core functionality of our API .\n- purpose: security and fraud prevention\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\nretention:\n- scope: account termination\n  period: twelve (12) months\n  text: No purpose in this notice will require\
  \ us keeping your personal information for longer than twelve (12)\n    months past the termination of the user's account .\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We may disclose your personal information with our service providers pursuant to a written contract between\n    us and each service provider.\ndeletion:\n  route: Contact us; account termination request\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: access\n  text: Right to access your personal data\n- right: deletion\n  text: Right to request the deletion of your personal data\n- right: correction\n  text: Right to correct inaccuracies in your personal data\n- right: opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n\
  \    as defined under California’s privacy law) , the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects ( \"profiling\" )\nsale_or_sharing:\n  stance: unstated\n  text: We have not disclosed, sold, or shared any personal information to third parties for a business or commercial\n    purpose in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/overshoot/privacy/overshoot-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
summary_line: 16 quoted statements, read from Overshoot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Computer Vision
- Video
- Video Understanding
- Vision Language Models
- Real-Time
- Streaming
- WebRTC
- Inference
- Multi-Modal
- Machine Learning
---
