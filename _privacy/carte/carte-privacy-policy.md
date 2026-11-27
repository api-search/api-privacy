---
api_specs:
- filename: carte-v1alpha1-api-openapi.yml
  format: yaml
  label: Carte V1Alpha1 API
  slug: carte-v1alpha1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carte/openapi/carte-v1alpha1-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect identifiers and contact information such as your full name, postal address, email address, telephone number, account username, online identifiers, internet protocol (IP) address, device identifiers, and similar identifiers.
  - category: financial
    text: We collect financial information necessary to provide the Carta Services, including bank account information, payment card details, brokerage and custodial account information, tax identification numbers, equity holdings, transaction histories
  - category: location
    text: We collect approximate geolocation data (such as that derived from IP address)
  - category: behavioral
    text: We automatically collect information about your interaction with the Services, including browsing history, search history, pages viewed, links clicked
  - category: other
    text: Carta may collect sensitive personal information, including social security numbers, passport numbers, driver's license numbers, taxpayer identification numbers, and other government-issued identifiers.
  deletion:
    route: Privacy request via https://preferences.carta.com/privacy or email to privacy@carta.com
    text: You may have the right to request that we delete your personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate, maintain, and improve the Services
    text: Operate, maintain, and improve the Services, such as supporting delivery of our services
  - purpose: Marketing emails
    text: Send marketing emails related to the Services, which you may opt out of using provided unsubscribe links or the opt-out mechanism in those communications.
  - purpose: Online advertising
    text: Facilitate online advertising, such as enabling third-party advertising companies and social media companies to use cookies, pixels, and similar technologies to collect information about your interaction over time across the Services
  - purpose: AML/KYC checks
    text: Complete AML/KYC checks, where applicable, on behalf of our clients pursuant to their AML regulatory obligations
  retention:
  - period: null
    scope: Carta Services
    text: For personal information collected through the Carta Services, we apply the general retention principles described in Sections 5.1 and 5.2.
  - period: Duration of account
    scope: 'Carta Law: commercial information'
    text: D. Commercial information Transaction information, purchase history, financial details, payment information Duration of account
  - period: 6 years
    scope: 'Carta Law: sensitive PI for AML/KYC'
    text: L. Sensitive personal information Social security numbers or other government identifiers collected for AML/KYC purposes 6 years
  rights:
  - right: Right to know, confirm, and access
    text: You may have the right to know the categories of personal information we have collected about you, confirm that we process your personal information, know details about the personal information we process and who we disclose personal information to, and access your personal information.
  - right: Right to portability
    text: You may have the right to request a copy of your personal information in a portable format.
  - right: Right to correct
    text: You may request that we correct personal information that we maintain about you if you believe such personal information is inaccurate.
  - right: Right to opt out of sales and sharing for Targeted Advertising
    text: You may have the right to opt out of the sale of your personal information or the sharing of your personal information for Targeted Advertising, as described above.
  - right: Right to opt out of profiling
    text: We do not profile in furtherance of decisions that produce legal or similarly significant effects.
  - right: Right to non-discrimination
    text: We will not discriminate against you for choosing to exercise any of your privacy rights.
  role:
    text: Carta and / or Carta Law each process personal information as a processor (or business, as applicable) in accordance with this Privacy Policy.
    value: both
  sale_or_sharing:
    stance: allowed
    text: We do not sell personal information for monetary consideration, but we share personal information with third parties for cross-context behavioral advertising and targeted advertising
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Carte
provenance_date: '2026-11-09'
provider_name: Carte
provider_slug: carte
slug: carte-privacy-policy
source_date: '2026-11-09'
source_filename: carte-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carta.com/legal/privacy/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Carte\naid: carte\nurl: https://carta.com/legal/privacy/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Carta and / or Carta Law each process personal information as a processor (or business, as applicable) in\n    accordance with this Privacy Policy.\ndata_categories:\n- category: identifying\n  text: We collect identifiers and contact information such as your full name, postal address, email address, telephone\n    number, account username, online identifiers, internet protocol (IP) address, device identifiers, and similar\n    identifiers.\n- category: financial\n\
  \  text: We collect financial information necessary to provide the Carta Services, including bank account information,\n    payment card details, brokerage and custodial account information, tax identification numbers, equity holdings,\n    transaction histories\n- category: location\n  text: We collect approximate geolocation data (such as that derived from IP address)\n- category: behavioral\n  text: We automatically collect information about your interaction with the Services, including browsing history,\n    search history, pages viewed, links clicked\n- category: other\n  text: Carta may collect sensitive personal information, including social security numbers, passport numbers, driver's\n    license numbers, taxpayer identification numbers, and other government-issued identifiers.\npurposes:\n- purpose: Operate, maintain, and improve the Services\n  text: Operate, maintain, and improve the Services, such as supporting delivery of our services\n- purpose: Marketing emails\n  text:\
  \ Send marketing emails related to the Services, which you may opt out of using provided unsubscribe links\n    or the opt-out mechanism in those communications.\n- purpose: Online advertising\n  text: Facilitate online advertising, such as enabling third-party advertising companies and social media companies\n    to use cookies, pixels, and similar technologies to collect information about your interaction over time across\n    the Services\n- purpose: AML/KYC checks\n  text: Complete AML/KYC checks, where applicable, on behalf of our clients pursuant to their AML regulatory obligations\nretention:\n- scope: Carta Services\n  period: null\n  text: For personal information collected through the Carta Services, we apply the general retention principles\n    described in Sections 5.1 and 5.2.\n- scope: 'Carta Law: commercial information'\n  period: Duration of account\n  text: D. Commercial information Transaction information, purchase history, financial details, payment information\n  \
  \  Duration of account\n- scope: 'Carta Law: sensitive PI for AML/KYC'\n  period: 6 years\n  text: L. Sensitive personal information Social security numbers or other government identifiers collected for\n    AML/KYC purposes 6 years\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy request via https://preferences.carta.com/privacy or email to privacy@carta.com\n  text: You may have the right to request that we delete your personal information.\nrights:\n- right: Right to know, confirm, and access\n  text: You may have the right to know the categories of personal information we have collected about you, confirm\n    that we process your personal information, know details about the personal information we process and who we\n    disclose personal information to, and access your personal information.\n- right: Right to portability\n  text: You may have the right to request a copy of your\
  \ personal information in a portable format.\n- right: Right to correct\n  text: You may request that we correct personal information that we maintain about you if you believe such personal\n    information is inaccurate.\n- right: Right to opt out of sales and sharing for Targeted Advertising\n  text: You may have the right to opt out of the sale of your personal information or the sharing of your personal\n    information for Targeted Advertising, as described above.\n- right: Right to opt out of profiling\n  text: We do not profile in furtherance of decisions that produce legal or similarly significant effects.\n- right: Right to non-discrimination\n  text: We will not discriminate against you for choosing to exercise any of your privacy rights.\nsale_or_sharing:\n  stance: allowed\n  text: We do not sell personal information for monetary consideration, but we share personal information with third\n    parties for cross-context behavioral advertising and targeted advertising\n"
source_yaml_url: https://artifacts.apis.io/carte/privacy/carte-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Carte's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Equity
- Fund Management
---
