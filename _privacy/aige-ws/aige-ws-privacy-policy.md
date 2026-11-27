---
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Display name, username, and profile photograph or avatar
  - category: contact
    text: Email address and, where chosen, phone number
  - category: financial
    text: 'Transaction records: amount, currency, date, product purchased, and transaction status'
  - category: location
    text: IP address and approximate location (city/country level)
  - category: behavioral
    text: Pages and features accessed, time spent, click paths, and navigation sequences
  - category: device
    text: Browser type, version, and language preference
  - category: biometric
    text: Face templates (mathematical representations of facial geometry, also called embeddings) from the photos you upload
  - category: demographic
    text: Your confirmation that you are 18 or older, and when you gave it. We do not ask for your date of birth
  - category: communication
    text: Direct messages and group chat content
  deletion:
    route: In-app account deletion (Profile → Edit profile → Delete Account) or email to privacy@aige.ws
    text: You can delete your account yourself in the app (Profile → Edit profile → Delete Account). We delete your account, profile, character data, face data, agent conversations and memory, API keys and connected social accounts straight away; this can't be undone.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision and account management
    text: Creating, authenticating, and managing your account
  - purpose: Platform improvement
    text: Analyzing aggregated, de-identified usage patterns to prioritize feature development
  - purpose: Safety and content moderation
    text: Detecting and preventing fraud, abuse, unauthorized access, and violations of our Acceptable Use Policy
  - purpose: Communications
    text: Sending emails about new features, products and offers to people with an AIGE or AIGORA account.
  - purpose: Legal compliance
    text: Complying with applicable laws, regulations, court orders, and government requests
  residency:
  - region: United States
    text: Our primary infrastructure (Firebase / Google Cloud) is hosted in the United States, mainly in Google's us-central1 region.
  - region: Singapore
    text: for example, BytePlus processes requests in Singapore
  retention:
  - period: 90 days without use
    scope: Face templates for registered faces
    text: deleted automatically after 90 days without use, and in any case no later than 3 years after collection
  - period: Maximum 90 days from submission
    scope: KYC identity documents (images)
    text: Maximum 90 days from submission
  - period: 7 years from transaction date
    scope: Payment and transaction records
    text: 7 years from transaction date
  - period: 30 days
    scope: Usage analytics events (with consent)
    text: 30 days, then only totals that don't identify you
  - period: 12 months
    scope: Security and fraud logs
    text: Security and fraud logs 12 months
  - period: Duration of account + 3 years
    scope: KYC verification outcome record
    text: Duration of account + 3 years
  rights:
  - right: Access
    text: Right of access (Art. 15) — You may request a copy of the personal information we hold about you and information about how we process it.
  - right: Erasure
    text: Right to erasure / "right to be forgotten" (Art. 17) — You may request deletion of your personal information where we no longer have a legal basis to retain it.
  - right: Portability
    text: Right to data portability (Art. 20) — You may request your personal information in a structured, commonly used, machine-readable format for transfer to another controller.
  - right: Correction
    text: Right to rectification (Art. 16) — You may request that we correct inaccurate or incomplete personal information.
  - right: Opt out of sale or sharing
    text: Right to opt out of sale or sharing — You may direct us not to sell or share your personal information with third parties.
  - right: Non-discrimination
    text: Right to non-discrimination — We will not discriminate against you for exercising your CCPA/CPRA rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information. We do not sell or rent personal information to third parties for monetary consideration.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) — We incorporate the European Commission's approved Standard Contractual Clauses (2021/914) into our data processing agreements with service providers that receive EEA personal data.
  - mechanism: other
    text: UK International Data Transfer Agreements (IDTAs) — For transfers from the United Kingdom, we use the ICO-approved International Data Transfer Agreement or addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIGE
provenance_date: '2026-11-09'
provider_name: AIGE
provider_slug: aige-ws
slug: aige-ws-privacy-policy
source_date: '2026-11-09'
source_filename: aige-ws-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aige.ws/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIGE\naid: aige-ws\nurl: https://aige.ws/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Display name, username, and profile photograph or avatar\n- category: contact\n  text: Email address and, where chosen, phone number\n- category: financial\n  text: 'Transaction records: amount, currency, date, product purchased, and transaction status'\n- category: location\n  text: IP address and approximate location (city/country level)\n- category: behavioral\n  text: Pages and features accessed, time spent, click paths, and navigation\
  \ sequences\n- category: device\n  text: Browser type, version, and language preference\n- category: biometric\n  text: Face templates (mathematical representations of facial geometry, also called embeddings) from the photos\n    you upload\n- category: demographic\n  text: Your confirmation that you are 18 or older, and when you gave it. We do not ask for your date of birth\n- category: communication\n  text: Direct messages and group chat content\npurposes:\n- purpose: Service provision and account management\n  text: Creating, authenticating, and managing your account\n- purpose: Platform improvement\n  text: Analyzing aggregated, de-identified usage patterns to prioritize feature development\n- purpose: Safety and content moderation\n  text: Detecting and preventing fraud, abuse, unauthorized access, and violations of our Acceptable Use Policy\n- purpose: Communications\n  text: Sending emails about new features, products and offers to people with an AIGE or AIGORA account.\n- purpose:\
  \ Legal compliance\n  text: Complying with applicable laws, regulations, court orders, and government requests\nretention:\n- scope: Face templates for registered faces\n  period: 90 days without use\n  text: deleted automatically after 90 days without use, and in any case no later than 3 years after collection\n- scope: KYC identity documents (images)\n  period: Maximum 90 days from submission\n  text: Maximum 90 days from submission\n- scope: Payment and transaction records\n  period: 7 years from transaction date\n  text: 7 years from transaction date\n- scope: Usage analytics events (with consent)\n  period: 30 days\n  text: 30 days, then only totals that don't identify you\n- scope: Security and fraud logs\n  period: 12 months\n  text: Security and fraud logs 12 months\n- scope: KYC verification outcome record\n  period: Duration of account + 3 years\n  text: Duration of account + 3 years\nresidency:\n- region: United States\n  text: Our primary infrastructure (Firebase / Google Cloud)\
  \ is hosted in the United States, mainly in Google's\n    us-central1 region.\n- region: Singapore\n  text: for example, BytePlus processes requests in Singapore\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) — We incorporate the European Commission's approved Standard Contractual\n    Clauses (2021/914) into our data processing agreements with service providers that receive EEA personal data.\n- mechanism: other\n  text: UK International Data Transfer Agreements (IDTAs) — For transfers from the United Kingdom, we use the ICO-approved\n    International Data Transfer Agreement or addendum.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion (Profile → Edit profile → Delete Account) or email to privacy@aige.ws\n  text: You can delete your account yourself in the app (Profile → Edit profile → Delete Account). We delete your\n    account, profile, character data, face data,\
  \ agent conversations and memory, API keys and connected social accounts\n    straight away; this can't be undone.\nrights:\n- right: Access\n  text: Right of access (Art. 15) — You may request a copy of the personal information we hold about you and information\n    about how we process it.\n- right: Erasure\n  text: Right to erasure / \"right to be forgotten\" (Art. 17) — You may request deletion of your personal information\n    where we no longer have a legal basis to retain it.\n- right: Portability\n  text: Right to data portability (Art. 20) — You may request your personal information in a structured, commonly\n    used, machine-readable format for transfer to another controller.\n- right: Correction\n  text: Right to rectification (Art. 16) — You may request that we correct inaccurate or incomplete personal information.\n- right: Opt out of sale or sharing\n  text: Right to opt out of sale or sharing — You may direct us not to sell or share your personal information with\n    third\
  \ parties.\n- right: Non-discrimination\n  text: Right to non-discrimination — We will not discriminate against you for exercising your CCPA/CPRA rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information. We do not sell or rent personal information to third parties for\n    monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/aige-ws/privacy/aige-ws-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from AIGE's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Branding
- Platform
---
