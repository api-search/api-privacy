---
api_specs:
- filename: open-banking-openapi-generated.yml
  format: yaml
  label: Tatic API
  slug: open-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-banking/openapi/_ae-authored/open-banking-openapi-generated.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Personal data: your email address only, received when you sign in (magic link, emailed code or GitHub).'
  - category: financial
    text: 'Bank data: with your PSD2 consent, we retrieve and store your bank account and transaction data.'
  deletion:
    route: Delete your account, or revoke individual bank consents
    text: When you delete your account, your bank account and transaction data is deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service and invoicing
    text: Providing the service and invoicing — contract, GDPR Art. 6(1)(b)
  - purpose: Security and alerts for bank consent expiry
    text: Security and alerts when a bank consent is about to expire — legitimate interest, GDPR Art. 6(1)(f)
  - purpose: Access to bank data under PSD2
    text: Access to your bank data under PSD2 — your consent, GDPR Art. 6(1)(a), given directly at your bank and revocable at any time
  residency:
  - region: EU
    text: All data is stored and processed within the EU — in data centers in Germany and Finland.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We keep your data for as long as your account is active.
  rights:
  - right: access
    text: Under the GDPR you have the right to access, rectification, erasure, data portability, restriction of processing, and objection.
  - right: complaint to supervisory authority
    text: If you believe we process your data unlawfully, you can complain to Datatilsynet, the Danish Data Protection Agency (datatilsynet.dk).
  role:
    text: The data controller is Tatic ApS (CVR 42532940), Mejsevej 2, Hadbjerg, 8370 Hadsten, Denmark, operating under the secondary name OpenBanking IO ApS.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No marketing without your consent, no data selling, no ads, no profiling.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tatic
provenance_date: '2026-11-10'
provider_name: Tatic
provider_slug: open-banking
slug: open-banking-privacy-policy
source_date: '2026-11-10'
source_filename: open-banking-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://open-banking.io/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tatic\naid: open-banking\nurl: https://open-banking.io/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Tatic ApS (CVR 42532940), Mejsevej 2, Hadbjerg, 8370 Hadsten, Denmark, operating\n    under the secondary name OpenBanking IO ApS.\ndata_categories:\n- category: contact\n  text: 'Personal data: your email address only, received when you sign in (magic link, emailed code or GitHub).'\n- category: financial\n  text: 'Bank data: with your PSD2 consent, we retrieve and store your bank account and transaction data.'\npurposes:\n- purpose: Providing the service\
  \ and invoicing\n  text: Providing the service and invoicing — contract, GDPR Art. 6(1)(b)\n- purpose: Security and alerts for bank consent expiry\n  text: Security and alerts when a bank consent is about to expire — legitimate interest, GDPR Art. 6(1)(f)\n- purpose: Access to bank data under PSD2\n  text: Access to your bank data under PSD2 — your consent, GDPR Art. 6(1)(a), given directly at your bank and revocable\n    at any time\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We keep your data for as long as your account is active.\nresidency:\n- region: EU\n  text: All data is stored and processed within the EU — in data centers in Germany and Finland.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account, or revoke individual bank consents\n  text: When you delete your account, your bank account and transaction data is deleted.\nrights:\n- right:\
  \ access\n  text: Under the GDPR you have the right to access, rectification, erasure, data portability, restriction of processing,\n    and objection.\n- right: complaint to supervisory authority\n  text: If you believe we process your data unlawfully, you can complain to Datatilsynet, the Danish Data Protection\n    Agency (datatilsynet.dk).\nsale_or_sharing:\n  stance: prohibited\n  text: No marketing without your consent, no data selling, no ads, no profiling.\n"
source_yaml_url: https://artifacts.apis.io/open-banking/privacy/open-banking-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Tatic's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
