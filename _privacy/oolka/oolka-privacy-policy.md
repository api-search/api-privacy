---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: such as your name, address, phone number, and email address
  - category: financial
    text: personal information, financial information, credit information, contact details, employment details, device information, transaction information, payment information
  - category: communication
    text: we ask for permission to access your messages (SMS data), storage and phone/device state
  - category: behavioral
    text: the IP address of the device you use to connect to the Internet, information such as what browser, browser version, operating system you have
  deletion:
    route: Delete Account option in the app profile/settings, or email legal@oolka.in
    text: Using the “Delete Account” option available within the profile/settings section of the Oolka app
  dpa:
    available: null
    text: Oolka requires third-party AI / LLM service providers to protect such information through contractual, confidentiality, privacy and security obligations
    url: null
  purposes:
  - purpose: provide requested services
    text: To provide you with the Services that you request or access.
  - purpose: credit insights
    text: Providing you with personalised insights, recommendations and information regarding financial products that may be relevant to you, including loans and credit cards
  - purpose: lender processing
    text: To provide lenders with information which enables them to process your loan/credit card application.
  - purpose: Gmail dispute features
    text: 'Dispute identification: Scanning your inbox to detect credit report emails and parse dispute-relevant information from PDF attachments.'
  retention:
  - period: 12 months
    scope: Gmail active dispute data
    text: Duration of the dispute + 12 months for audit trail
  - period: 24 months
    scope: Sent email records
    text: 24 months from date of sending
  - period: 90 days
    scope: Hashed UPI handler identifier
    text: 90 days, then deleted, except where longer retention is required by NPCI/RBI for dispute or audit purposes
  - period: null
    scope: Credit Information
    text: In any case, such data shall not be retained beyond six (6) months, unless required by law
  rights:
  - right: Access
    text: 'Access: Request a copy of the data Oolka holds about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data (see Section 6.2).'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format.'
  - right: Withdraw consent
    text: 'Withdraw consent: Revoke your consent for Gmail access at any time via Google Account settings.'
  role:
    text: Depending on the nature of the Services availed by you, your Personal Information may be collected and processed by STPL, OFSPL or both acting together.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your Personal Information to third parties for any purpose.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Oolka
provenance_date: '2026-11-10'
provider_name: Oolka
provider_slug: oolka
slug: oolka-privacy-policy
source_date: '2026-11-10'
source_filename: oolka-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://oolka.in/app-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Oolka\naid: oolka\nurl: https://oolka.in/app-privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Depending on the nature of the Services availed by you, your Personal Information may be collected and processed\n    by STPL, OFSPL or both acting together.\ndata_categories:\n- category: contact\n  text: such as your name, address, phone number, and email address\n- category: financial\n  text: personal information, financial information, credit information, contact details, employment details, device\n    information, transaction information, payment information\n- category: communication\n\
  \  text: we ask for permission to access your messages (SMS data), storage and phone/device state\n- category: behavioral\n  text: the IP address of the device you use to connect to the Internet, information such as what browser, browser\n    version, operating system you have\npurposes:\n- purpose: provide requested services\n  text: To provide you with the Services that you request or access.\n- purpose: credit insights\n  text: Providing you with personalised insights, recommendations and information regarding financial products that\n    may be relevant to you, including loans and credit cards\n- purpose: lender processing\n  text: To provide lenders with information which enables them to process your loan/credit card application.\n- purpose: Gmail dispute features\n  text: 'Dispute identification: Scanning your inbox to detect credit report emails and parse dispute-relevant information\n    from PDF attachments.'\nretention:\n- scope: Gmail active dispute data\n  period: 12 months\n\
  \  text: Duration of the dispute + 12 months for audit trail\n- scope: Sent email records\n  period: 24 months\n  text: 24 months from date of sending\n- scope: Hashed UPI handler identifier\n  period: 90 days\n  text: 90 days, then deleted, except where longer retention is required by NPCI/RBI for dispute or audit purposes\n- scope: Credit Information\n  period: null\n  text: In any case, such data shall not be retained beyond six (6) months, unless required by law\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Oolka requires third-party AI / LLM service providers to protect such information through contractual, confidentiality,\n    privacy and security obligations\ndeletion:\n  route: Delete Account option in the app profile/settings, or email legal@oolka.in\n  text: Using the “Delete Account” option available within the profile/settings section of the Oolka app\nrights:\n- right: Access\n  text: 'Access: Request\
  \ a copy of the data Oolka holds about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data (see Section 6.2).'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format.'\n- right: Withdraw consent\n  text: 'Withdraw consent: Revoke your consent for Gmail access at any time via Google Account settings.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your Personal Information to third parties for any purpose.\n"
source_yaml_url: https://artifacts.apis.io/oolka/privacy/oolka-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Oolka's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Score
- Credit Building
- Consumer Finance
- Personal Finance
- India
---
