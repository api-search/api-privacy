---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name (as provided by the authentication provider)
  - category: contact
    text: Your email address
  - category: identifying
    text: A unique identifier from the authentication provider
  - category: device
    text: Browser type and version
  - category: location
    text: IP addresses
  - category: behavioral
    text: Pages visited and actions taken
  - category: other
    text: Private keys (encrypted at rest using AES-256-GCM) for managed certificates
  deletion:
    route: Request deletion of account and associated data
    text: You can request deletion of your account and associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Provide and maintain the Certman service
  - purpose: Account authentication
    text: Authenticate your identity and manage your account
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud or abuse
  - purpose: Legal compliance
    text: Comply with legal obligations
  - purpose: Service improvement
    text: Improve our service and develop new features
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your data for as long as your account is active or as needed to provide you with our services.
  - period: a minimum of one year
    scope: Audit logs
    text: Audit logs are retained for a minimum of one year for security and compliance purposes.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your certificates and data
  - right: Object
    text: Object to certain processing of your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 'We do not sell your personal information. We may share your information only in the following circumstances:'
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Certman
provenance_date: '2026-11-09'
provider_name: Certman
provider_slug: certman-app
slug: certman-app-privacy-policy
source_date: '2026-11-09'
source_filename: certman-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://certman.app/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Certman\naid: certman-app\nurl: https://certman.app/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name (as provided by the authentication provider)\n- category: contact\n  text: Your email address\n- category: identifying\n  text: A unique identifier from the authentication provider\n- category: device\n  text: Browser type and version\n- category: location\n  text: IP addresses\n- category: behavioral\n  text: Pages visited and actions taken\n- category: other\n  text: Private keys (encrypted at rest using AES-256-GCM)\
  \ for managed certificates\npurposes:\n- purpose: Provide and maintain service\n  text: Provide and maintain the Certman service\n- purpose: Account authentication\n  text: Authenticate your identity and manage your account\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud or abuse\n- purpose: Legal compliance\n  text: Comply with legal obligations\n- purpose: Service improvement\n  text: Improve our service and develop new features\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your data for as long as your account is active or as needed to provide you with our services.\n- scope: Audit logs\n  period: a minimum of one year\n  text: Audit logs are retained for a minimum of one year for security and compliance purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of account and associated data\n\
  \  text: You can request deletion of your account and associated data at any time.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your certificates and data\n- right: Object\n  text: Object to certain processing of your data\nsale_or_sharing:\n  stance: conditional\n  text: 'We do not sell your personal information. We may share your information only in the following circumstances:'\n"
source_yaml_url: https://artifacts.apis.io/certman-app/privacy/certman-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Certman's own page on 2026-11-09.
synthetic: false
tags:
- Certificate Authority
- PKI
- TLS
- Automation
---
