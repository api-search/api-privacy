---
api_specs:
- filename: algrow-online-openapi-generated.yml
  format: yaml
  label: Algrow API
  slug: algrow-online-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algrow-online/openapi/_ae-authored/algrow-online-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: When you register, we collect your email address and authentication credentials through our third-party authentication provider (Supabase).'
  - category: financial
    text: 'Payment Information: Payment details are processed securely through Stripe. We do not store your full credit card number on our servers.'
  - category: behavioral
    text: 'Usage Data: We collect information about how you use the Site, including pages visited, features used, search queries, and interaction patterns.'
  - category: device
    text: 'Device Information: We may collect information about your device, including IP address, browser type, operating system, and device identifiers.'
  - category: other
    text: We do not access your personal YouTube account data without explicit authorization.
  deletion:
    route: Email support@algrow.online to request deletion of request logs; or request deletion of personal information
    text: You can request that we delete your personal information, subject to certain exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our Services
  - purpose: Process transactions
    text: Process transactions and manage your subscription
  - purpose: Service communications
    text: Send you service-related communications
  - purpose: Security and abuse prevention
    text: Detect, prevent, and address technical issues and security threats
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: null
    scope: Personal information
    text: We retain your personal information for as long as your account is active or as needed to provide you services.
  - period: 90 days
    scope: Connected AI app request logs
    text: We delete these logs after 90 days.
  rights:
  - right: Access
    text: 'Access: You can request a copy of the personal information we hold about you.'
  - right: Correction
    text: 'Correction: You can request that we correct inaccurate or incomplete personal information.'
  - right: Deletion
    text: 'Deletion: You can request that we delete your personal information, subject to certain exceptions.'
  - right: Portability
    text: 'Portability: You can request a copy of your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection: You can object to the processing of your personal information in certain circumstances.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'Service Providers: We share information with third-party service providers who perform services on our behalf, including Supabase (authentication), Stripe (payments), Cloudflare (hosting and CDN), and ElevenLabs (text-to-speech).'
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and maintained on servers located outside of your state, province, country, or other governmental jurisdiction where data protection laws may differ.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Algrow
provenance_date: '2026-11-09'
provider_name: Algrow
provider_slug: algrow-online
slug: algrow-online-privacy-policy
source_date: '2026-11-09'
source_filename: algrow-online-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://algrow.online/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Algrow\naid: algrow-online\nurl: https://algrow.online/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: When you register, we collect your email address and authentication credentials through\n    our third-party authentication provider (Supabase).'\n- category: financial\n  text: 'Payment Information: Payment details are processed securely through Stripe. We do not store your full credit\n    card number on our servers.'\n- category: behavioral\n  text: 'Usage Data: We collect information about how you use\
  \ the Site, including pages visited, features used,\n    search queries, and interaction patterns.'\n- category: device\n  text: 'Device Information: We may collect information about your device, including IP address, browser type, operating\n    system, and device identifiers.'\n- category: other\n  text: We do not access your personal YouTube account data without explicit authorization.\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our Services\n- purpose: Process transactions\n  text: Process transactions and manage your subscription\n- purpose: Service communications\n  text: Send you service-related communications\n- purpose: Security and abuse prevention\n  text: Detect, prevent, and address technical issues and security threats\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your personal information for as long as your account is active\
  \ or as needed to provide you services.\n- scope: Connected AI app request logs\n  period: 90 days\n  text: We delete these logs after 90 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and maintained on servers located outside of your state, province,\n    country, or other governmental jurisdiction where data protection laws may differ.\nsubprocessors:\n  url: null\n  text: 'Service Providers: We share information with third-party service providers who perform services on our\n    behalf, including Supabase (authentication), Stripe (payments), Cloudflare (hosting and CDN), and ElevenLabs\n    (text-to-speech).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@algrow.online to request deletion of request logs; or request deletion of personal information\n  text: You can request that we delete your personal information, subject to certain exceptions.\nrights:\n- right: Access\n  text: 'Access: You\
  \ can request a copy of the personal information we hold about you.'\n- right: Correction\n  text: 'Correction: You can request that we correct inaccurate or incomplete personal information.'\n- right: Deletion\n  text: 'Deletion: You can request that we delete your personal information, subject to certain exceptions.'\n- right: Portability\n  text: 'Portability: You can request a copy of your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection: You can object to the processing of your personal information in certain circumstances.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/algrow-online/privacy/algrow-online-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Algrow's own page on 2026-11-09.
synthetic: false
tags:
- YouTube
- Content Creation
- Artificial Intelligence
- Analytics
- Marketing
---
