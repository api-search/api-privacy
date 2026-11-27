---
api_specs:
- filename: cariqa-billing-details-api-openapi.yml
  format: yaml
  label: Cariqa Billing Details API
  slug: cariqa-billing-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-billing-details-api-openapi.yml
- filename: cariqa-charging-sessions-api-openapi.yml
  format: yaml
  label: Cariqa Charging Sessions API
  slug: cariqa-charging-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-charging-sessions-api-openapi.yml
- filename: cariqa-debts-api-openapi.yml
  format: yaml
  label: Cariqa Debts API
  slug: cariqa-debts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-debts-api-openapi.yml
- filename: cariqa-invoices-api-openapi.yml
  format: yaml
  label: Cariqa Invoices API
  slug: cariqa-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-invoices-api-openapi.yml
- filename: cariqa-payments-api-openapi.yml
  format: yaml
  label: Cariqa Payments API
  slug: cariqa-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-payments-api-openapi.yml
- filename: cariqa-stations-api-openapi.yml
  format: yaml
  label: Cariqa Stations API
  slug: cariqa-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-stations-api-openapi.yml
- filename: cariqa-users-api-openapi.yml
  format: yaml
  label: Cariqa Users API
  slug: cariqa-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cariqa/openapi/cariqa-users-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data for user identification that you make available to us when using our offers, e.g. by registering or filling out your user profile, such as name, e-mail address, address, telephone number.
  - category: demographic
    text: Additional information that you provide when completing your profile, such as vehicle information, gender, date of birth.
  - category: device
    text: Information about your access device and your visits to our website or the use of our mobile offers, such as date and time and length of access, IP address of the accessing device
  - category: location
    text: For the use of our offers -mobile offers included, your device location, vehicle data, information about charging transactions and your usage behavior with regard to our mobile app can also be processed.
  deletion:
    route: Request deletion via email to help@cariqa.com or account deletion
    text: will be deleted upon request or account deletion etc.
  dpa:
    available: true
    text: we’ve concluded respective Data Processing Agreements (DPA) with them as per Art. 28 para. 3 GDPR.
    url: null
  purposes:
  - purpose: Provision of routing and charging services
    text: provision of routing and charging services
  - purpose: Communication and newsletters
    text: Communicate with you, e.g. by sending you communications or requested newsletters
  - purpose: Statistical analysis via anonymized data
    text: Anonymize the data to use them for statistical purposes
  - purpose: Security and stability evaluation
    text: Evaluation of system security and stability as well for other administrative purposes.
  - purpose: App analysis
    text: analyze your behavior when using our app
  residency:
  - region: Germany
    text: At the moment, however, your data is only stored in Germany.
  retention:
  - period: null
    scope: Contact form data
    text: The personal data collected for the use of the contact form will be automatically deleted after the request you have made has been dealt with.
  - period: null
    scope: Google Firebase data
    text: Your data will be stored here permanently for the use of Google Firebase and will be deleted upon request or account deletion etc.
  rights:
  - right: Access
    text: To request information about your processed personal data in accordance with Art. 15 GDPR.
  - right: Correction
    text: in accordance with Art. 16 GDPR, to immediately request the correction of incorrect or incomplete personal data stored by us
  - right: Deletion
    text: According to Art. 17 GDPR, to request the deletion of your personal data stored by us
  - right: Restriction
    text: pursuant to Art. 18 GDPR, to request the restriction of the processing of your personal data
  - right: Portability
    text: in accordance with Art. 20 GDPR, to receive your personal data that you have provided to us in a structured, common and machine-readable format
  - right: Objection
    text: you have the right to object to the processing of your personal data in accordance with Article 21 GDPR
  - right: Consent withdrawal
    text: pursuant to Art. 7 para. 3 GDPR, to revoke your consent once given to us at any time.
  - right: Complaint
    text: to complain to a supervisory authority in accordance with Art. 77 GDPR.
  role:
    text: The contact person and person responsible for the processing of your personal data is KZY Marketplace Solutions GmbH, Chausseestr. 41B, 10115 Berlin
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: This includes, among other things, the use of the corresponding standard contractual clauses of the EU Commission as well as necessary additional measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cariqa
provenance_date: '2026-11-09'
provider_name: Cariqa
provider_slug: cariqa
slug: cariqa-privacy-policy
source_date: '2026-11-09'
source_filename: cariqa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cariqa.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cariqa\naid: cariqa\nurl: https://www.cariqa.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The contact person and person responsible for the processing of your personal data is KZY Marketplace Solutions\n    GmbH, Chausseestr. 41B, 10115 Berlin\ndata_categories:\n- category: identifying\n  text: Personal data for user identification that you make available to us when using our offers, e.g. by registering\n    or filling out your user profile, such as name, e-mail address, address, telephone number.\n- category: demographic\n  text: Additional information that you provide when\
  \ completing your profile, such as vehicle information, gender,\n    date of birth.\n- category: device\n  text: Information about your access device and your visits to our website or the use of our mobile offers, such\n    as date and time and length of access, IP address of the accessing device\n- category: location\n  text: For the use of our offers -mobile offers included, your device location, vehicle data, information about\n    charging transactions and your usage behavior with regard to our mobile app can also be processed.\npurposes:\n- purpose: Provision of routing and charging services\n  text: provision of routing and charging services\n- purpose: Communication and newsletters\n  text: Communicate with you, e.g. by sending you communications or requested newsletters\n- purpose: Statistical analysis via anonymized data\n  text: Anonymize the data to use them for statistical purposes\n- purpose: Security and stability evaluation\n  text: Evaluation of system security and stability\
  \ as well for other administrative purposes.\n- purpose: App analysis\n  text: analyze your behavior when using our app\nretention:\n- scope: Contact form data\n  period: null\n  text: The personal data collected for the use of the contact form will be automatically deleted after the request\n    you have made has been dealt with.\n- scope: Google Firebase data\n  period: null\n  text: Your data will be stored here permanently for the use of Google Firebase and will be deleted upon request\n    or account deletion etc.\nresidency:\n- region: Germany\n  text: At the moment, however, your data is only stored in Germany.\ntransfers:\n- mechanism: SCC\n  text: This includes, among other things, the use of the corresponding standard contractual clauses of the EU Commission\n    as well as necessary additional measures.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we’ve concluded respective Data Processing Agreements (DPA) with them as per Art. 28\
  \ para. 3 GDPR.\ndeletion:\n  route: Request deletion via email to help@cariqa.com or account deletion\n  text: will be deleted upon request or account deletion etc.\nrights:\n- right: Access\n  text: To request information about your processed personal data in accordance with Art. 15 GDPR.\n- right: Correction\n  text: in accordance with Art. 16 GDPR, to immediately request the correction of incorrect or incomplete personal\n    data stored by us\n- right: Deletion\n  text: According to Art. 17 GDPR, to request the deletion of your personal data stored by us\n- right: Restriction\n  text: pursuant to Art. 18 GDPR, to request the restriction of the processing of your personal data\n- right: Portability\n  text: in accordance with Art. 20 GDPR, to receive your personal data that you have provided to us in a structured,\n    common and machine-readable format\n- right: Objection\n  text: you have the right to object to the processing of your personal data in accordance with Article 21 GDPR\n\
  - right: Consent withdrawal\n  text: pursuant to Art. 7 para. 3 GDPR, to revoke your consent once given to us at any time.\n- right: Complaint\n  text: to complain to a supervisory authority in accordance with Art. 77 GDPR.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cariqa/privacy/cariqa-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 24 quoted statements, read from Cariqa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Electric Vehicles
- Payments
- Mobility
- E-Mobility
- Charge Point Operator
- Energy
---
