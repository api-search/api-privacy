---
api_specs:
- filename: brandnamemaker-com-hero-api-openapi.yml
  format: yaml
  label: True Frontier Hero API
  slug: brandnamemaker-com-hero-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandnamemaker-com/openapi/brandnamemaker-com-hero-api-openapi.yml
- filename: brandnamemaker-com-name-api-openapi.yml
  format: yaml
  label: True Frontier Name API
  slug: brandnamemaker-com-name-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandnamemaker-com/openapi/brandnamemaker-com-name-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifiers What: your IP address and payment or job reference IDs.'
  - category: contact
    text: 'Communications What: feedback you send through our feedback endpoint, and any contact address you include.'
  - category: financial
    text: 'Payment and purchase information What: card payments handled by Stripe (we never see the full card number)'
  - category: behavioral
    text: 'Usage information What: pages you visit, features you use, links you click, the site that referred you, and the date and time of your visit.'
  - category: device
    text: 'Device and technical information What: IP address, browser type and version, operating system, device type, language settings, and error or crash reports.'
  - category: other
    text: 'Content you provide What: the product description, audience and preferences you send us to generate names or headlines.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate services
    text: Provide and operate our services, including your account and anything you buy.
  - purpose: Fix bugs and improve services
    text: Fix bugs, monitor performance, and develop new features.
  - purpose: Process payments
    text: Process payments, issue refunds, and keep financial records.
  - purpose: Legal compliance
    text: Comply with legal obligations, such as tax and accounting rules and valid requests from authorities.
  - purpose: Security and fraud prevention
    text: Keep our services secure and prevent fraud, abuse, and spam.
  residency:
  - region: United States
    text: We are based in the United States and store information there.
  retention:
  - period: 90 days
    scope: Content you provide
    text: For as long as your account is active or until you delete the content, then removed from backups within 90 days.
  - period: generally up to 7 years
    scope: Payment and purchase information
    text: Transaction records are kept for as long as tax and accounting laws require (generally up to 7 years).
  - period: Up to 3 years
    scope: Communications
    text: Up to 3 years after our last interaction, so we have a history if you contact us again.
  - period: Up to 25 months
    scope: Usage information
    text: 'Usage information: Up to 25 months, in aggregated or de-identified form where possible.'
  - period: up to 90 days
    scope: Device and technical information
    text: Server and error logs are kept for up to 90 days unless needed longer to investigate a security issue.
  rights:
  - right: Access
    text: Access your personal information and get a copy of it.
  - right: Correct
    text: Correct information that is inaccurate or incomplete.
  - right: Erase
    text: Erase your information in certain cases ("right to be forgotten").
  - right: Portability
    text: 'Data portability: receive information you gave us in a machine-readable format, or have it sent to another company.'
  - right: Object
    text: Object to processing based on legitimate interests, and to direct marketing at any time.
  - right: Opt out of sale or targeted advertising
    text: Opt out of targeted advertising (called "sharing" for cross-context behavioral advertising in California).
  role:
    text: We are responsible for your personal information as described in this policy (the "controller" under data protection law).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and we do not share it for cross-context behavioral (targeted) advertising, as those terms are defined by US state privacy laws
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: the EU-U.S. Data Privacy Framework (and its UK and Swiss extensions) where the recipient is certified
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission (with the UK Addendum where needed).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: True Frontier
provenance_date: '2026-11-09'
provider_name: True Frontier
provider_slug: brandnamemaker-com
slug: brandnamemaker-com-privacy-policy
source_date: '2026-11-09'
source_filename: brandnamemaker-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brandnamemaker.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: True Frontier\naid: brandnamemaker-com\nurl: https://brandnamemaker.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for your personal information as described in this policy (the \"controller\" under data\n    protection law).\ndata_categories:\n- category: identifying\n  text: 'Identifiers What: your IP address and payment or job reference IDs.'\n- category: contact\n  text: 'Communications What: feedback you send through our feedback endpoint, and any contact address you include.'\n- category: financial\n  text: 'Payment and purchase information What: card payments\
  \ handled by Stripe (we never see the full card number)'\n- category: behavioral\n  text: 'Usage information What: pages you visit, features you use, links you click, the site that referred you,\n    and the date and time of your visit.'\n- category: device\n  text: 'Device and technical information What: IP address, browser type and version, operating system, device type,\n    language settings, and error or crash reports.'\n- category: other\n  text: 'Content you provide What: the product description, audience and preferences you send us to generate names\n    or headlines.'\npurposes:\n- purpose: Provide and operate services\n  text: Provide and operate our services, including your account and anything you buy.\n- purpose: Fix bugs and improve services\n  text: Fix bugs, monitor performance, and develop new features.\n- purpose: Process payments\n  text: Process payments, issue refunds, and keep financial records.\n- purpose: Legal compliance\n  text: Comply with legal obligations,\
  \ such as tax and accounting rules and valid requests from authorities.\n- purpose: Security and fraud prevention\n  text: Keep our services secure and prevent fraud, abuse, and spam.\nretention:\n- scope: Content you provide\n  period: 90 days\n  text: For as long as your account is active or until you delete the content, then removed from backups within\n    90 days.\n- scope: Payment and purchase information\n  period: generally up to 7 years\n  text: Transaction records are kept for as long as tax and accounting laws require (generally up to 7 years).\n- scope: Communications\n  period: Up to 3 years\n  text: Up to 3 years after our last interaction, so we have a history if you contact us again.\n- scope: Usage information\n  period: Up to 25 months\n  text: 'Usage information: Up to 25 months, in aggregated or de-identified form where possible.'\n- scope: Device and technical information\n  period: up to 90 days\n  text: Server and error logs are kept for up to 90 days unless needed\
  \ longer to investigate a security issue.\nresidency:\n- region: United States\n  text: We are based in the United States and store information there.\ntransfers:\n- mechanism: DPF\n  text: the EU-U.S. Data Privacy Framework (and its UK and Swiss extensions) where the recipient is certified\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission (with the UK Addendum where needed).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access your personal information and get a copy of it.\n- right: Correct\n  text: Correct information that is inaccurate or incomplete.\n- right: Erase\n  text: Erase your information in certain cases (\"right to be forgotten\").\n- right: Portability\n  text: 'Data portability: receive information you gave us in a machine-readable format, or have it sent to another\n    company.'\n- right: Object\n  text:\
  \ Object to processing based on legitimate interests, and to direct marketing at any time.\n- right: Opt out of sale or targeted advertising\n  text: Opt out of targeted advertising (called \"sharing\" for cross-context behavioral advertising in California).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and we do not share it for cross-context behavioral (targeted) advertising,\n    as those terms are defined by US state privacy laws\n"
source_yaml_url: https://artifacts.apis.io/brandnamemaker-com/privacy/brandnamemaker-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from True Frontier's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Naming
- Branding
- Domain Check
---
