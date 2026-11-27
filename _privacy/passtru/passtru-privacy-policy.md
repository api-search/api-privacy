---
api_specs:
- filename: passtru-openapi-generated.yml
  format: yaml
  label: Passtru API
  slug: passtru-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passtru/openapi/_ae-authored/passtru-openapi-generated.yml
claim_count: 36
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details — name, email address, profile photo (optional), preferred language, and the password or sign-in credential associated with your account.
  - category: identifying
    text: Document images — photographs of the front and back of the identity document, including the machine-readable zone (MRZ) where present.
  - category: biometric
    text: A short selfie video and a single still frame used for passive liveness detection and for a one-to-one similarity comparison against the photo on your identity document.
  - category: financial
    text: proof-of-income documents (tax returns, payslips)
  - category: location
    text: approximate location (city-level) derived from your IP address
  - category: device
    text: Device and connection data — IP address, device identifiers, operating system, browser, and approximate location (city-level) derived from your IP address.
  - category: behavioral
    text: Service-usage data — interactions with the application (page views, button clicks, document uploads, form-fill events, feature usage), error events, performance traces, and audit logs of decryption events.
  - category: communication
    text: Support requests — the contents of messages you send to our support team and any attachments you include.
  deletion:
    route: Delete via the vault or close account; or email legal@passtru.io
    text: Until you delete them or close your account, then 30 days for recovery before permanent deletion
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: Create and maintain your account, including authenticating you and protecting your account from unauthorised access.
  - purpose: Operate identity vault
    text: Operate the identity vault, including extracting structured data from the documents you upload so that you can use that data to fill forms.
  - purpose: Identity verification
    text: Run identity verifications you request, or that a business customer has asked you to complete in order to use their service.
  - purpose: Legal compliance
    text: Comply with legal obligations, including identity-verification recordkeeping rules, tax obligations, anti-money-laundering requirements where they apply to a business customer for whom we perform a verification, and responding to lawful requests from authorities.
  - purpose: Fraud and security
    text: Detect, investigate, and prevent fraud, abuse, and security incidents.
  residency:
  - region: Germany (EEA)
    text: Our production infrastructure is located in Falkenstein, Germany (within the European Economic Area).
  - region: Sweden (EEA)
    text: Transactional email is sent from Amazon Web Services facilities in Stockholm, Sweden (also within the European Economic Area).
  retention:
  - period: 30 days after closure
    scope: Account record
    text: For the lifetime of your account and 30 days after closure
  - period: within 60 seconds of verification-session termination
    scope: Biometric data (capture frames and template)
    text: In-memory only; destroyed within 60 seconds of verification-session termination
  - period: 5 years after the verification
    scope: Verification decision logs and audit records
    text: 5 years after the verification, as required by US Bank Secrecy Act / FinCEN customer-identification recordkeeping (31 CFR § 1020.220)
  - period: 7 years
    scope: Consent receipts
    text: 'Consent receipts; Retention: 7 years, hash-chained and stored on write-once media'
  - period: 13 months
    scope: Server logs and security telemetry
    text: 'Server logs and security telemetry; Retention: 13 months unless required for a longer period to investigate a security incident'
  - period: 3 years from the last message
    scope: Customer-support messages
    text: 'Customer-support messages; Retention: 3 years from the last message'
  rights:
  - right: Access
    text: Access — to obtain a copy of the personal information we hold about you.
  - right: Rectification
    text: Rectification — to correct inaccurate or incomplete personal information.
  - right: Erasure
    text: Erasure — to ask us to delete personal information, subject to exceptions for information we must keep to comply with a legal obligation, exercise or defend legal claims, or for similar reasons recognised by applicable law.
  - right: Restriction
    text: Restriction — to limit how we use your personal information in defined circumstances.
  - right: Portability
    text: Portability — to receive personal information you provided to us in a structured, commonly used, machine-readable format and to ask us to transmit it to another controller where technically feasible.
  - right: Objection
    text: Objection — to object to processing carried out on the basis of our legitimate interests, on grounds relating to your particular situation.
  - right: Withdrawal of consent
    text: Withdrawal of consent — to withdraw any consent you have given us.
  - right: Human review of automated decisions
    text: The right not to be subject to solely automated decision-making — to obtain human review of significant automated decisions, as explained in Section 5.
  role:
    text: We are the controller of the personal information described below, except where we act as a processor on behalf of a business customer that uses our identity-verification or identity-provider services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information for money, and we do not share personal information for cross-context behavioural advertising.
  subprocessors:
    text: The full list, with the role of each provider, is on the Subprocessors page.
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (2021/914) Module Two (controller-to-processor)
  - mechanism: DPF
    text: supplemented where the provider is also self-certified to the EU-US Data Privacy Framework
  - mechanism: adequacy
    text: the recognition of mutual adequacy between the European Union and Brazil (Commission Implementing Decision (EU) 2026/179) for transfers to Brazilian-domiciled providers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Passtru
provenance_date: '2026-11-10'
provider_name: Passtru
provider_slug: passtru
slug: passtru-privacy-policy
source_date: '2026-11-10'
source_filename: passtru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://passtru.io/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Passtru\naid: passtru\nurl: https://passtru.io/en/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal information described below, except where we act as a processor on\n    behalf of a business customer that uses our identity-verification or identity-provider services.\ndata_categories:\n- category: identifying\n  text: Account details — name, email address, profile photo (optional), preferred language, and the password or\n    sign-in credential associated with your account.\n- category: identifying\n  text: Document images — photographs of\
  \ the front and back of the identity document, including the machine-readable\n    zone (MRZ) where present.\n- category: biometric\n  text: A short selfie video and a single still frame used for passive liveness detection and for a one-to-one similarity\n    comparison against the photo on your identity document.\n- category: financial\n  text: proof-of-income documents (tax returns, payslips)\n- category: location\n  text: approximate location (city-level) derived from your IP address\n- category: device\n  text: Device and connection data — IP address, device identifiers, operating system, browser, and approximate\n    location (city-level) derived from your IP address.\n- category: behavioral\n  text: Service-usage data — interactions with the application (page views, button clicks, document uploads, form-fill\n    events, feature usage), error events, performance traces, and audit logs of decryption events.\n- category: communication\n  text: Support requests — the contents of messages\
  \ you send to our support team and any attachments you include.\npurposes:\n- purpose: Account creation and authentication\n  text: Create and maintain your account, including authenticating you and protecting your account from unauthorised\n    access.\n- purpose: Operate identity vault\n  text: Operate the identity vault, including extracting structured data from the documents you upload so that you\n    can use that data to fill forms.\n- purpose: Identity verification\n  text: Run identity verifications you request, or that a business customer has asked you to complete in order to\n    use their service.\n- purpose: Legal compliance\n  text: Comply with legal obligations, including identity-verification recordkeeping rules, tax obligations, anti-money-laundering\n    requirements where they apply to a business customer for whom we perform a verification, and responding to lawful\n    requests from authorities.\n- purpose: Fraud and security\n  text: Detect, investigate, and prevent\
  \ fraud, abuse, and security incidents.\nretention:\n- scope: Account record\n  period: 30 days after closure\n  text: For the lifetime of your account and 30 days after closure\n- scope: Biometric data (capture frames and template)\n  period: within 60 seconds of verification-session termination\n  text: In-memory only; destroyed within 60 seconds of verification-session termination\n- scope: Verification decision logs and audit records\n  period: 5 years after the verification\n  text: 5 years after the verification, as required by US Bank Secrecy Act / FinCEN customer-identification recordkeeping\n    (31 CFR § 1020.220)\n- scope: Consent receipts\n  period: 7 years\n  text: 'Consent receipts; Retention: 7 years, hash-chained and stored on write-once media'\n- scope: Server logs and security telemetry\n  period: 13 months\n  text: 'Server logs and security telemetry; Retention: 13 months unless required for a longer period to investigate\n    a security incident'\n- scope: Customer-support\
  \ messages\n  period: 3 years from the last message\n  text: 'Customer-support messages; Retention: 3 years from the last message'\nresidency:\n- region: Germany (EEA)\n  text: Our production infrastructure is located in Falkenstein, Germany (within the European Economic Area).\n- region: Sweden (EEA)\n  text: Transactional email is sent from Amazon Web Services facilities in Stockholm, Sweden (also within the European\n    Economic Area).\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses (2021/914) Module Two (controller-to-processor)\n- mechanism: DPF\n  text: supplemented where the provider is also self-certified to the EU-US Data Privacy Framework\n- mechanism: adequacy\n  text: the recognition of mutual adequacy between the European Union and Brazil (Commission Implementing Decision\n    (EU) 2026/179) for transfers to Brazilian-domiciled providers\nsubprocessors:\n  url: null\n  text: The full list, with the role of each provider, is on\
  \ the Subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete via the vault or close account; or email legal@passtru.io\n  text: Until you delete them or close your account, then 30 days for recovery before permanent deletion\nrights:\n- right: Access\n  text: Access — to obtain a copy of the personal information we hold about you.\n- right: Rectification\n  text: Rectification — to correct inaccurate or incomplete personal information.\n- right: Erasure\n  text: Erasure — to ask us to delete personal information, subject to exceptions for information we must keep to\n    comply with a legal obligation, exercise or defend legal claims, or for similar reasons recognised by applicable\n    law.\n- right: Restriction\n  text: Restriction — to limit how we use your personal information in defined circumstances.\n- right: Portability\n  text: Portability — to receive personal information you provided to us in a structured, commonly used, machine-readable\n\
  \    format and to ask us to transmit it to another controller where technically feasible.\n- right: Objection\n  text: Objection — to object to processing carried out on the basis of our legitimate interests, on grounds relating\n    to your particular situation.\n- right: Withdrawal of consent\n  text: Withdrawal of consent — to withdraw any consent you have given us.\n- right: Human review of automated decisions\n  text: The right not to be subject to solely automated decision-making — to obtain human review of significant\n    automated decisions, as explained in Section 5.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information for money, and we do not share personal information for cross-context\n    behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/passtru/privacy/passtru-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 36 quoted statements, read from Passtru's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- Age Verification
- KYC
- Document Verification
- Sanctions Screening
---
