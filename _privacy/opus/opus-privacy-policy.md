---
api_specs:
- filename: opus-brand-templates-api-openapi.yml
  format: yaml
  label: Opus Brand Templates API
  slug: opus-brand-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-brand-templates-api-openapi.yml
- filename: opus-censor-jobs-api-openapi.yml
  format: yaml
  label: Opus Censor Jobs API
  slug: opus-censor-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-censor-jobs-api-openapi.yml
- filename: opus-clip-project-api-openapi.yml
  format: yaml
  label: Opus Clip Project API
  slug: opus-clip-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-clip-project-api-openapi.yml
- filename: opus-collection-api-openapi.yml
  format: yaml
  label: Opus Collection API
  slug: opus-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-collection-api-openapi.yml
- filename: opus-collection-content-api-openapi.yml
  format: yaml
  label: Opus Collection Content API
  slug: opus-collection-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-collection-content-api-openapi.yml
- filename: opus-exportableclip-api-openapi.yml
  format: yaml
  label: Opus ExportableClip API
  slug: opus-exportableclip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-exportableclip-api-openapi.yml
- filename: opus-generative-jobs-api-openapi.yml
  format: yaml
  label: Opus Generative Jobs API
  slug: opus-generative-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-generative-jobs-api-openapi.yml
- filename: opus-social-posting-api-openapi.yml
  format: yaml
  label: Opus Social Posting API
  slug: opus-social-posting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-social-posting-api-openapi.yml
- filename: opus-transcripts-api-openapi.yml
  format: yaml
  label: Opus Transcripts API
  slug: opus-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-transcripts-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Profile or Contact Data: First and last name Email Phone number'
  - category: financial
    text: 'Commercial Data: Purchase history'
  - category: device
    text: 'Device/IP Data: IP address Device ID Type of device/operating system/browser used to access the Services Device fingerprint'
  - category: location
    text: 'Geolocation Data: IP address-based location information Browser time zone'
  - category: behavioral
    text: 'Web analytics: Web page interactions Referring webpage/source through which you accessed the Services'
  - category: communication
    text: 'User-generated content: Videos, images, transcripts'
  deletion:
    route: Email account.deletion@opus.pro or contact@opus.pro
    text: 'please send an email to exercise that right at: account.deletion@opus.pro'
  dpa:
    available: true
    text: We enter into Data Protection Agreements with all of our sub-processors.
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: 'Purpose: Account creation, authentication, customer support'
  - purpose: Service security and troubleshooting
    text: 'Purpose: Service security, troubleshooting, analytics'
  - purpose: Marketing and advertising
    text: Showing you advertisements, including interest-based or online behavioral advertising.
  residency:
  - region: United States
    text: OpusClip runs on secure Google Cloud servers located in the United States.
  retention:
  - period: null
    scope: Profile information and credentials
    text: We retain your profile information and credentials for as long as you have an account with us.
  - period: null
    scope: Payment data
    text: We retain your payment data for as long as we need to process your purchase or subscription.
  - period: null
    scope: Device/IP data
    text: We retain your device/IP data for as long as we need it to ensure that our systems are working appropriately, effectively and efficiently.
  rights:
  - right: Access
    text: 'Access: You may have the right to request confirmation of or access to the Personal Data that we process about you.'
  - right: Deletion
    text: 'Deletion: You may have the right to request that we delete the Personal Data that we have collected about you.'
  - right: Correction
    text: 'Correction: You may have the right to request that we correct any inaccurate Personal Data we have collected about you.'
  - right: Portability
    text: 'Portability: You may have the right to request a copy of your Personal Data in a machine-readable format, to the extent technically feasible.'
  role:
    text: OpusClip is usually the processor of your personal data. We are the controller only if we process data for our own legitimate purposes.
    value: both
  sale_or_sharing:
    stance: conditional
    text: 'We sell or share your Personal Data to the following categories of third parties: Advertising Partners'
  subprocessors:
    text: The current list of sub-processors can be found at Trust Portal .
    url: https://trust.opus.pro
  transfers:
  - mechanism: DPF
    text: OpusClip complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
  - mechanism: SCC
    text: We use standard contractual clauses (SCCs) to ensure adequate protection for personal data transferred outside the EU, UK, and Switzerland.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Opus
provenance_date: '2026-11-10'
provider_name: Opus
provider_slug: opus
slug: opus-privacy-policy
source_date: '2026-11-10'
source_filename: opus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.opus.pro/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Opus\naid: opus\nurl: https://www.opus.pro/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: OpusClip is usually the processor of your personal data. We are the controller only if we process data for\n    our own legitimate purposes.\ndata_categories:\n- category: contact\n  text: 'Profile or Contact Data: First and last name Email Phone number'\n- category: financial\n  text: 'Commercial Data: Purchase history'\n- category: device\n  text: 'Device/IP Data: IP address Device ID Type of device/operating system/browser used to access the Services\n    Device fingerprint'\n- category: location\n\
  \  text: 'Geolocation Data: IP address-based location information Browser time zone'\n- category: behavioral\n  text: 'Web analytics: Web page interactions Referring webpage/source through which you accessed the Services'\n- category: communication\n  text: 'User-generated content: Videos, images, transcripts'\npurposes:\n- purpose: Account creation and authentication\n  text: 'Purpose: Account creation, authentication, customer support'\n- purpose: Service security and troubleshooting\n  text: 'Purpose: Service security, troubleshooting, analytics'\n- purpose: Marketing and advertising\n  text: Showing you advertisements, including interest-based or online behavioral advertising.\nretention:\n- scope: Profile information and credentials\n  period: null\n  text: We retain your profile information and credentials for as long as you have an account with us.\n- scope: Payment data\n  period: null\n  text: We retain your payment data for as long as we need to process your purchase or subscription.\n\
  - scope: Device/IP data\n  period: null\n  text: We retain your device/IP data for as long as we need it to ensure that our systems are working appropriately,\n    effectively and efficiently.\nresidency:\n- region: United States\n  text: OpusClip runs on secure Google Cloud servers located in the United States.\ntransfers:\n- mechanism: DPF\n  text: OpusClip complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\n- mechanism: SCC\n  text: We use standard contractual clauses (SCCs) to ensure adequate protection for personal data transferred outside\n    the EU, UK, and Switzerland.\nsubprocessors:\n  url: https://trust.opus.pro\n  text: The current list of sub-processors can be found at Trust Portal .\ndpa:\n  available: true\n  url: null\n  text: We enter into Data Protection Agreements with all of our sub-processors.\ndeletion:\n\
  \  route: Email account.deletion@opus.pro or contact@opus.pro\n  text: 'please send an email to exercise that right at: account.deletion@opus.pro'\nrights:\n- right: Access\n  text: 'Access: You may have the right to request confirmation of or access to the Personal Data that we process\n    about you.'\n- right: Deletion\n  text: 'Deletion: You may have the right to request that we delete the Personal Data that we have collected about\n    you.'\n- right: Correction\n  text: 'Correction: You may have the right to request that we correct any inaccurate Personal Data we have collected\n    about you.'\n- right: Portability\n  text: 'Portability: You may have the right to request a copy of your Personal Data in a machine-readable format,\n    to the extent technically feasible.'\nsale_or_sharing:\n  stance: conditional\n  text: 'We sell or share your Personal Data to the following categories of third parties: Advertising Partners'\n"
source_yaml_url: https://artifacts.apis.io/opus/privacy/opus-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Opus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Video
- Artificial Intelligence
- Video Editing
- Short-Form Video
- Content Creation
- Social Media
- Media
- Agents
---
