---
api_specs:
- filename: justfill-app-openapi-generated.yml
  format: yaml
  label: justfill-app API
  slug: justfill-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justfill-app/openapi/_ae-authored/justfill-app-openapi-generated.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (required for account creation)
  - category: financial
    text: Name and billing address (as provided to Stripe during payment)
  - category: device
    text: Device fingerprint hash (derived from IP address and browser information) for session security and fraud prevention.
  - category: location
    text: IP address and approximate geolocation (country/region level)
  - category: behavioral
    text: Feature usage patterns (e.g., which tools are used, frequency of exports)
  - category: other
    text: PDF documents and images uploaded for AI processing
  deletion:
    route: 'Account settings: Account Deletion, initiating cascading deletion'
    text: You can delete your account through your account settings, which initiates a cascading deletion of all associated data
  dpa:
    available: true
    text: our Data Processing Agreement (available at justfill.app/dpa and summarized in Section 22 of this Policy) governs the processing.
    url: justfill.app/dpa
  purposes:
  - purpose: Account creation, authentication, service delivery
    text: Account creation, authentication, service delivery
  - purpose: Payment processing, invoicing, tax compliance
    text: Payment processing, invoicing, tax compliance
  - purpose: Security, fraud prevention, abuse detection
    text: Security, fraud prevention, abuse detection, service reliability, and first-party operational funnel measurement.
  - purpose: Service improvement, usage analysis (analytics with consent)
    text: Service improvement, usage analysis
  - purpose: Advertising conversion tracking via Meta Pixel with consent
    text: Advertising conversion tracking and audience retargeting.
  residency:
  - region: EU (Germany)
    text: Our primary infrastructure is hosted on OVH SAS infrastructure in the European Union (Limburg, Germany)
  - region: United States
    text: 'Third-party AI and speech-to-text processing: Document images, text data, and audio data may be processed by our providers'' infrastructure, which may include servers in the United States.'
  retention:
  - period: 7 days
    scope: Uploaded documents (one-time processing)
    text: Rendered page images sent to the AI for processing are automatically deleted within 7 days
  - period: 30 days
    scope: Uploaded source documents
    text: uploaded source documents within 30 days unless you save them as a reusable template
  - period: 30 days
    scope: Draft sessions
    text: Is automatically deleted after 30 days of inactivity
  - period: 90 days
    scope: Processing, usage, and security logs
    text: Processing, usage, and security logs 90 days (rolling)
  - period: Duration of account
    scope: Account data
    text: Account data (email, password hash) Duration of account
  - period: 5 years
    scope: Anonymized financial records
    text: Anonymized financial records (transaction amounts, dates, invoice numbers — personal identifiers removed) 5 years from the end of the financial year in which the transaction occurred
  rights:
  - right: Access
    text: Right of Access (Art. 15 GDPR)
  - right: Rectification
    text: Right to Rectification (Art. 16 GDPR)
  - right: Erasure
    text: Right to Erasure (Art. 17 GDPR)
  - right: Restriction
    text: Right to Restriction of Processing (Art. 18 GDPR)
  - right: Portability
    text: Right to Data Portability (Art. 20 GDPR)
  - right: Object
    text: Right to Object (Art. 21 GDPR)
  - right: Withdraw consent
    text: Right to Withdraw Consent (Art. 7(3) GDPR)
  role:
    text: JustFill acts as the data controller under Art. 6(1)(b) (performance of a contract). When you process personal data of third parties (e.g., filling in forms on behalf of clients or employees), JustFill acts as a data processor on your behalf
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, lease, or trade your personal data to any third party for their own marketing or commercial purposes.
  subprocessors:
    text: We engage the following third-party data processors to deliver the Service. Each processor is bound by a Data Processing Agreement (DPA) or equivalent contractual safeguards
    url: null
  transfers:
  - mechanism: DPF
    text: The EU-US Data Privacy Framework (DPF), which constitutes an adequacy decision by the European Commission under Art. 45 GDPR.
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) adopted by the European Commission (Art. 46(2)(c) GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: justfill-app
provenance_date: '2026-11-09'
provider_name: justfill-app
provider_slug: justfill-app
slug: justfill-app-privacy-policy
source_date: '2026-11-09'
source_filename: justfill-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://justfill.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: justfill-app\naid: justfill-app\nurl: https://justfill.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: JustFill acts as the data controller under Art. 6(1)(b) (performance of a contract). When you process personal\n    data of third parties (e.g., filling in forms on behalf of clients or employees), JustFill acts as a data processor\n    on your behalf\ndata_categories:\n- category: identifying\n  text: Email address (required for account creation)\n- category: financial\n  text: Name and billing address (as provided to Stripe during payment)\n- category: device\n \
  \ text: Device fingerprint hash (derived from IP address and browser information) for session security and fraud\n    prevention.\n- category: location\n  text: IP address and approximate geolocation (country/region level)\n- category: behavioral\n  text: Feature usage patterns (e.g., which tools are used, frequency of exports)\n- category: other\n  text: PDF documents and images uploaded for AI processing\npurposes:\n- purpose: Account creation, authentication, service delivery\n  text: Account creation, authentication, service delivery\n- purpose: Payment processing, invoicing, tax compliance\n  text: Payment processing, invoicing, tax compliance\n- purpose: Security, fraud prevention, abuse detection\n  text: Security, fraud prevention, abuse detection, service reliability, and first-party operational funnel measurement.\n- purpose: Service improvement, usage analysis (analytics with consent)\n  text: Service improvement, usage analysis\n- purpose: Advertising conversion tracking via\
  \ Meta Pixel with consent\n  text: Advertising conversion tracking and audience retargeting.\nretention:\n- scope: Uploaded documents (one-time processing)\n  period: 7 days\n  text: Rendered page images sent to the AI for processing are automatically deleted within 7 days\n- scope: Uploaded source documents\n  period: 30 days\n  text: uploaded source documents within 30 days unless you save them as a reusable template\n- scope: Draft sessions\n  period: 30 days\n  text: Is automatically deleted after 30 days of inactivity\n- scope: Processing, usage, and security logs\n  period: 90 days\n  text: Processing, usage, and security logs 90 days (rolling)\n- scope: Account data\n  period: Duration of account\n  text: Account data (email, password hash) Duration of account\n- scope: Anonymized financial records\n  period: 5 years\n  text: Anonymized financial records (transaction amounts, dates, invoice numbers — personal identifiers removed)\n    5 years from the end of the financial year in\
  \ which the transaction occurred\nresidency:\n- region: EU (Germany)\n  text: Our primary infrastructure is hosted on OVH SAS infrastructure in the European Union (Limburg, Germany)\n- region: United States\n  text: 'Third-party AI and speech-to-text processing: Document images, text data, and audio data may be processed\n    by our providers'' infrastructure, which may include servers in the United States.'\ntransfers:\n- mechanism: DPF\n  text: The EU-US Data Privacy Framework (DPF), which constitutes an adequacy decision by the European Commission\n    under Art. 45 GDPR.\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) adopted by the European Commission (Art. 46(2)(c) GDPR)\nsubprocessors:\n  url: null\n  text: We engage the following third-party data processors to deliver the Service. Each processor is bound by a\n    Data Processing Agreement (DPA) or equivalent contractual safeguards\ndpa:\n  available: true\n  url: justfill.app/dpa\n  text: our Data Processing Agreement\
  \ (available at justfill.app/dpa and summarized in Section 22 of this Policy)\n    governs the processing.\ndeletion:\n  route: 'Account settings: Account Deletion, initiating cascading deletion'\n  text: You can delete your account through your account settings, which initiates a cascading deletion of all associated\n    data\nrights:\n- right: Access\n  text: Right of Access (Art. 15 GDPR)\n- right: Rectification\n  text: Right to Rectification (Art. 16 GDPR)\n- right: Erasure\n  text: Right to Erasure (Art. 17 GDPR)\n- right: Restriction\n  text: Right to Restriction of Processing (Art. 18 GDPR)\n- right: Portability\n  text: Right to Data Portability (Art. 20 GDPR)\n- right: Object\n  text: Right to Object (Art. 21 GDPR)\n- right: Withdraw consent\n  text: Right to Withdraw Consent (Art. 7(3) GDPR)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, lease, or trade your personal data to any third party for their own marketing or commercial\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/justfill-app/privacy/justfill-app-privacy-policy.yml
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
summary_line: 33 quoted statements, read from justfill-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- PDF
- Form Filling
- Software-as-a-Service
---
