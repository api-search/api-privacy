---
api_specs:
- filename: openhands-add-git-providers-api-openapi.yml
  format: yaml
  label: OpenHands Add Git Providers API
  slug: openhands-add-git-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-add-git-providers-api-openapi.yml
- filename: openhands-alive-api-openapi.yml
  format: yaml
  label: OpenHands Alive API
  slug: openhands-alive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-alive-api-openapi.yml
- filename: openhands-conversations-api-openapi.yml
  format: yaml
  label: OpenHands Conversations API
  slug: openhands-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-conversations-api-openapi.yml
- filename: openhands-health-api-openapi.yml
  format: yaml
  label: OpenHands Health API
  slug: openhands-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-health-api-openapi.yml
- filename: openhands-options-api-openapi.yml
  format: yaml
  label: OpenHands Options API
  slug: openhands-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-options-api-openapi.yml
- filename: openhands-reset-settings-api-openapi.yml
  format: yaml
  label: OpenHands Reset Settings API
  slug: openhands-reset-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-reset-settings-api-openapi.yml
- filename: openhands-secrets-api-openapi.yml
  format: yaml
  label: OpenHands Secrets API
  slug: openhands-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-secrets-api-openapi.yml
- filename: openhands-settings-api-openapi.yml
  format: yaml
  label: OpenHands Settings API
  slug: openhands-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-settings-api-openapi.yml
- filename: openhands-unset-provider-tokens-api-openapi.yml
  format: yaml
  label: OpenHands Unset Provider Tokens API
  slug: openhands-unset-provider-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-unset-provider-tokens-api-openapi.yml
- filename: openhands-user-api-openapi.yml
  format: yaml
  label: OpenHands User API
  slug: openhands-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhands/openapi/openhands-user-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact information and credentials, such as your name, email address, phone number, address, and the username and password you use to access our Services.
  - category: financial
    text: Transactions and payment information including your purchases, transactions, and billing information.
  - category: device
    text: Device data, such as your computer’s or mobile device’s operating system type and version, manufacturer and model, browser type, screen resolution, RAM and disk size, CPU usage, device type (e.g., phone, tablet), IP address, unique identifiers, language settings, mobile device carrier, radio/network information (e.g., WiFi, LTE, 4G), and general location information such as city, state or geographic area.
  - category: behavioral
    text: Usage data, such as pages or screens you viewed, how long you spent on a page or screen, browsing history, navigation paths between pages or screens, information about your activity on a page or screen, access times, duration of access, and whether you have opened our emails or clicked links within them.
  - category: communication
    text: Feedback or correspondence, such as information you provide when you contact us with questions, feedback, or otherwise correspond with us online.
  - category: other
    text: Content. This includes any information you submit to the Services or permit the Services to access (including through GitHub), where such content contains personal information, such as any prompts, inputs, text, code or other information you upload or provide to the Services or that you generate using the Services.
  deletion:
    route: email contact@all-hands.dev
    text: If you require your data to be deleted, please email contact@all-hands.dev.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and provide the Services
    text: We use personal information to provide, operate, maintain, secure and improve our Site and Services.
  - purpose: Develop and improve Services, including AI model training
    text: we may use content and feedback from your use of the Services to train and tune our AI models to improve the capabilities of our Services.
  - purpose: Direct marketing and interest-based advertising
    text: We engage advertising partners to display ads about the Services on other online platforms and services.
  - purpose: Analytics and usage measurement
    text: We use third-party analytics providers (such as Posthog, Google Analytics or similar tools) to help us understand how users interact with our Site and Services, measure engagement, and improve performance.
  - purpose: Compliance and protection
    text: Compliance and protection, including to comply with applicable laws, lawful requests, and legal process
  retention:
  - period: as long as reasonably necessary
    scope: Personal information generally
    text: We keep personal information for as long as reasonably necessary for the purposes described in this Privacy Policy, while we have a business need to do so, or as required by law (e.g. for tax, legal, accounting, or other purposes), whichever is longer.
  rights:
  - right: Update and delete account content
    text: You may be able to update information within your account, including managing and deleting the content you store on the Services.
  - right: Opt out of marketing emails
    text: You can opt out of receiving marketing emails at any time by clicking “unsubscribe” within the email footer.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenHands
provenance_date: '2026-11-10'
provider_name: OpenHands
provider_slug: openhands
slug: openhands-privacy-policy
source_date: '2026-11-10'
source_filename: openhands-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.openhands.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenHands\naid: openhands\nurl: https://www.openhands.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact information and credentials, such as your name, email address, phone number, address, and the username\n    and password you use to access our Services.\n- category: financial\n  text: Transactions and payment information including your purchases, transactions, and billing information.\n- category: device\n  text: Device data, such as your computer’s or mobile device’s operating system type and version, manufacturer\n\
  \    and model, browser type, screen resolution, RAM and disk size, CPU usage, device type (e.g., phone, tablet),\n    IP address, unique identifiers, language settings, mobile device carrier, radio/network information (e.g., WiFi,\n    LTE, 4G), and general location information such as city, state or geographic area.\n- category: behavioral\n  text: Usage data, such as pages or screens you viewed, how long you spent on a page or screen, browsing history,\n    navigation paths between pages or screens, information about your activity on a page or screen, access times,\n    duration of access, and whether you have opened our emails or clicked links within them.\n- category: communication\n  text: Feedback or correspondence, such as information you provide when you contact us with questions, feedback,\n    or otherwise correspond with us online.\n- category: other\n  text: Content. This includes any information you submit to the Services or permit the Services to access (including\n    through\
  \ GitHub), where such content contains personal information, such as any prompts, inputs, text, code or\n    other information you upload or provide to the Services or that you generate using the Services.\npurposes:\n- purpose: Operate and provide the Services\n  text: We use personal information to provide, operate, maintain, secure and improve our Site and Services.\n- purpose: Develop and improve Services, including AI model training\n  text: we may use content and feedback from your use of the Services to train and tune our AI models to improve\n    the capabilities of our Services.\n- purpose: Direct marketing and interest-based advertising\n  text: We engage advertising partners to display ads about the Services on other online platforms and services.\n- purpose: Analytics and usage measurement\n  text: We use third-party analytics providers (such as Posthog, Google Analytics or similar tools) to help us understand\n    how users interact with our Site and Services, measure engagement,\
  \ and improve performance.\n- purpose: Compliance and protection\n  text: Compliance and protection, including to comply with applicable laws, lawful requests, and legal process\nretention:\n- scope: Personal information generally\n  period: as long as reasonably necessary\n  text: We keep personal information for as long as reasonably necessary for the purposes described in this Privacy\n    Policy, while we have a business need to do so, or as required by law (e.g. for tax, legal, accounting, or other\n    purposes), whichever is longer.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email contact@all-hands.dev\n  text: If you require your data to be deleted, please email contact@all-hands.dev.\nrights:\n- right: Update and delete account content\n  text: You may be able to update information within your account, including managing and deleting the content you\n    store on the Services.\n\
  - right: Opt out of marketing emails\n  text: You can opt out of receiving marketing emails at any time by clicking “unsubscribe” within the email footer.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openhands/privacy/openhands-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 15 quoted statements, read from OpenHands's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Autonomous
- Open Source
- Developer Tools
- Software Engineering
- Code Generation
---
