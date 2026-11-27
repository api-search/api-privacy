---
api_specs:
- filename: addshuffle-com-credits-api-openapi.yml
  format: yaml
  label: Shuffle Credits API
  slug: addshuffle-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-credits-api-openapi.yml
- filename: addshuffle-com-l402-api-openapi.yml
  format: yaml
  label: Shuffle L402 API
  slug: addshuffle-com-l402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-l402-api-openapi.yml
- filename: addshuffle-com-manual-mode-api-openapi.yml
  format: yaml
  label: Shuffle Manual Mode API
  slug: addshuffle-com-manual-mode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-manual-mode-api-openapi.yml
- filename: addshuffle-com-utilities-api-openapi.yml
  format: yaml
  label: Shuffle Utilities API
  slug: addshuffle-com-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-utilities-api-openapi.yml
- filename: addshuffle-com-video-chain-api-openapi.yml
  format: yaml
  label: Shuffle Video Chain API
  slug: addshuffle-com-video-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-video-chain-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Phone number (required for SMS/iMessage service)
  - category: contact
    text: Email address (if provided)
  - category: financial
    text: we only retain a payment token and the last four digits of your card for reference
  - category: communication
    text: Text messages you send to the Service
  - category: location
    text: Mobile carrier information
  - category: device
    text: Device type and operating system
  - category: behavioral
    text: Features you use and how you interact with them
  deletion:
    route: Email privacy@dnftinc.com
    text: 'You may request deletion of your data by contacting privacy@dnftinc.com . We will delete your data within 30 days, except where we are required or permitted to retain it for: Legal compliance'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Process your messages and generate AI responses
  - purpose: Train AI models
    text: Your content (messages, images, inputs) may be used to train, fine-tune, and improve AI models operated by DNFT.
  - purpose: Advertising measurement and retargeting
    text: We may share certain identifiers (such as device IDs and usage data) with advertising partners for measurement or retargeting purposes
  - purpose: Safety and security
    text: Detect and prevent fraud, abuse, and security threats
  residency:
  - region: United States
    text: Your data is processed in the United States.
  retention:
  - period: Duration of your account, plus up to 90 days after deletion
    scope: Message content
    text: Message content Duration of your account, plus up to 90 days after deletion
  - period: Duration of your account, plus up to 2 years for legal compliance
    scope: Account information
    text: Account information Duration of your account, plus up to 2 years for legal compliance
  - period: 7 years (legal/tax requirements)
    scope: Billing records
    text: Billing records 7 years (legal/tax requirements)
  - period: Only as long as the task needs them, then deleted
    scope: Verification codes and credentials
    text: Verification codes and credentials provided during a task Only as long as the task needs them, then deleted.
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correction
    text: Request correction of inaccurate information
  - right: Deletion
    text: Request deletion of your information (subject to legal exceptions)
  - right: Opt out of AI model training
    text: Opt out of the use of your content for AI model training (Section 2)
  - right: Opt out of sale/sharing (California)
    text: You have the right to opt out of the sale or sharing of your personal information.
  - right: Non-discrimination (California)
    text: We will not discriminate against you for exercising your privacy rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for money. We may share certain identifiers (such as device IDs and usage data) with advertising partners for measurement or retargeting purposes, which may be considered a "sale" or "sharing" under California law
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By using the Service, you consent to the transfer of your data to the United States, which may have different data protection laws than your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shuffle
provenance_date: '2026-11-09'
provider_name: Shuffle
provider_slug: addshuffle-com
slug: addshuffle-com-privacy-policy
source_date: '2026-11-09'
source_filename: addshuffle-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.textshuffle.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shuffle\naid: addshuffle-com\nurl: https://www.textshuffle.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Phone number (required for SMS/iMessage service)\n- category: contact\n  text: Email address (if provided)\n- category: financial\n  text: we only retain a payment token and the last four digits of your card for reference\n- category: communication\n  text: Text messages you send to the Service\n- category: location\n  text: Mobile carrier information\n- category: device\n  text: Device type and operating system\n\
  - category: behavioral\n  text: Features you use and how you interact with them\npurposes:\n- purpose: Provide and operate the Service\n  text: Process your messages and generate AI responses\n- purpose: Train AI models\n  text: Your content (messages, images, inputs) may be used to train, fine-tune, and improve AI models operated\n    by DNFT.\n- purpose: Advertising measurement and retargeting\n  text: We may share certain identifiers (such as device IDs and usage data) with advertising partners for measurement\n    or retargeting purposes\n- purpose: Safety and security\n  text: Detect and prevent fraud, abuse, and security threats\nretention:\n- scope: Message content\n  period: Duration of your account, plus up to 90 days after deletion\n  text: Message content Duration of your account, plus up to 90 days after deletion\n- scope: Account information\n  period: Duration of your account, plus up to 2 years for legal compliance\n  text: Account information Duration of your account, plus\
  \ up to 2 years for legal compliance\n- scope: Billing records\n  period: 7 years (legal/tax requirements)\n  text: Billing records 7 years (legal/tax requirements)\n- scope: Verification codes and credentials\n  period: Only as long as the task needs them, then deleted\n  text: Verification codes and credentials provided during a task Only as long as the task needs them, then deleted.\nresidency:\n- region: United States\n  text: Your data is processed in the United States.\ntransfers:\n- mechanism: other\n  text: By using the Service, you consent to the transfer of your data to the United States, which may have different\n    data protection laws than your country.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@dnftinc.com\n  text: 'You may request deletion of your data by contacting privacy@dnftinc.com . We will delete your data within\n    30 days, except where we are required or permitted to retain\
  \ it for: Legal compliance'\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correction\n  text: Request correction of inaccurate information\n- right: Deletion\n  text: Request deletion of your information (subject to legal exceptions)\n- right: Opt out of AI model training\n  text: Opt out of the use of your content for AI model training (Section 2)\n- right: Opt out of sale/sharing (California)\n  text: You have the right to opt out of the sale or sharing of your personal information.\n- right: Non-discrimination (California)\n  text: We will not discriminate against you for exercising your privacy rights.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information for money. We may share certain identifiers (such as device IDs and\n    usage data) with advertising partners for measurement or retargeting purposes, which may be considered a \"sale\"\n    or \"sharing\" under California law\n"
source_yaml_url: https://artifacts.apis.io/addshuffle-com/privacy/addshuffle-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Shuffle's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social Media
- Automation
- Marketing
- Software-as-a-Service
---
