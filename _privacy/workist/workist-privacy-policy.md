---
api_specs:
- filename: workist-delivery-notes-api-openapi.yml
  format: yaml
  label: Workist Delivery Notes API
  slug: workist-delivery-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-delivery-notes-api-openapi.yml
- filename: workist-invoices-api-openapi.yml
  format: yaml
  label: Workist Invoices API
  slug: workist-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-invoices-api-openapi.yml
- filename: workist-list-of-services-api-openapi.yml
  format: yaml
  label: Workist List Of Services API
  slug: workist-list-of-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-list-of-services-api-openapi.yml
- filename: workist-master-data-api-openapi.yml
  format: yaml
  label: Workist Master Data API
  slug: workist-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-master-data-api-openapi.yml
- filename: workist-order-confirmations-api-openapi.yml
  format: yaml
  label: Workist Order Confirmations API
  slug: workist-order-confirmations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-order-confirmations-api-openapi.yml
- filename: workist-orders-api-openapi.yml
  format: yaml
  label: Workist Orders API
  slug: workist-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-orders-api-openapi.yml
- filename: workist-property-bills-api-openapi.yml
  format: yaml
  label: Workist Property Bills API
  slug: workist-property-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-property-bills-api-openapi.yml
- filename: workist-rfq-api-openapi.yml
  format: yaml
  label: Workist Rfq API
  slug: workist-rfq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-rfq-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name Your email address Your company name
  - category: contact
    text: Contact data (telephone number, email address)
  - category: device
    text: Device and browser information
  - category: location
    text: the time, location, and frequency of your use of our website
  - category: communication
    text: Information that you convey to the AI assistant by voice
  deletion:
    route: null
    text: Personal data will be deleted or blocked as soon as the purpose for its storage no longer applies.
  dpa:
    available: null
    text: each provider is required to enter into a data processing agreement with us.
    url: null
  purposes:
  - purpose: Provide functional website and secure use
    text: To ensure a smooth connection to the website
  - purpose: AI training of classification and recognition models
    text: the additional use of such documents for the improvement of our classification and recognition models (AI training), which we carry out as a controller
  - purpose: Advertising and remarketing
    text: enabling targeted advertising and remarketing
  - purpose: Customer relationship management
    text: optimizing our customer relationship management
  residency:
  - region: European Union
    text: We process your data primarily within the European Union (EU) and the European Economic Area (EEA).
  - region: Germany
    text: A server location in Germany has been selected; however, data transfers to the USA cannot be ruled out.
  retention:
  - period: 30 days
    scope: Website log files (www.workist.com)
    text: at the latest after 30 days for data collected during visits to www.workist.com
  - period: 90 days
    scope: Website log files (wb.workist.com)
    text: after 90 days for data collected when using wb.workist.com
  - period: 90 days
    scope: Meta cookies
    text: The cookies "_fbp" and "_fbc" are stored for up to 90 days.
  - period: 13 months
    scope: Contentsquare data
    text: The collected data is deleted after 13 months.
  rights:
  - right: Access
    text: You have the right to obtain confirmation as to whether we are processing your personal data.
  - right: Rectification
    text: You have the right to request the prompt rectification of inaccurate personal data.
  - right: Erasure
    text: You have the right to request erasure of your personal data where processing is no longer necessary.
  - right: Restriction
    text: You have the right to request restriction of processing
  - right: Portability
    text: You have the right to receive your personal data in a structured, commonly used, and machine-readable format.
  - right: Object
    text: You have the right to object, on grounds relating to your particular situation, at any time to the processing of certain personal data concerning you.
  - right: Withdraw consent
    text: You may withdraw your consent to the processing of your personal data at any time with effect for the future.
  role:
    text: we process these documents on behalf of and in accordance with the instructions of our customers as a processor within the meaning of Art. 28 GDPR; the respective customer is the controller responsible for this processing.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: the EU-U.S. Data Privacy Framework applies. Microsoft is certified under this framework
  - mechanism: SCC
    text: In addition, Standard Contractual Clauses (SCCs) have been concluded.
  - mechanism: other
    text: Clay is not certified under the EU-U.S. Data Privacy Framework. The transfer is therefore based on Standard Contractual Clauses of the European Commission (Article 46(2)(c) GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Workist
provenance_date: '2026-11-10'
provider_name: Workist
provider_slug: workist
slug: workist-privacy-policy
source_date: '2026-11-10'
source_filename: workist-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.workist.com/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Workist\naid: workist\nurl: https://www.workist.com/en/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we process these documents on behalf of and in accordance with the instructions of our customers as a processor\n    within the meaning of Art. 28 GDPR; the respective customer is the controller responsible for this processing.\ndata_categories:\n- category: identifying\n  text: Your name Your email address Your company name\n- category: contact\n  text: Contact data (telephone number, email address)\n- category: device\n  text: Device and browser information\n- category: location\n\
  \  text: the time, location, and frequency of your use of our website\n- category: communication\n  text: Information that you convey to the AI assistant by voice\npurposes:\n- purpose: Provide functional website and secure use\n  text: To ensure a smooth connection to the website\n- purpose: AI training of classification and recognition models\n  text: the additional use of such documents for the improvement of our classification and recognition models (AI\n    training), which we carry out as a controller\n- purpose: Advertising and remarketing\n  text: enabling targeted advertising and remarketing\n- purpose: Customer relationship management\n  text: optimizing our customer relationship management\nretention:\n- scope: Website log files (www.workist.com)\n  period: 30 days\n  text: at the latest after 30 days for data collected during visits to www.workist.com\n- scope: Website log files (wb.workist.com)\n  period: 90 days\n  text: after 90 days for data collected when using wb.workist.com\n\
  - scope: Meta cookies\n  period: 90 days\n  text: The cookies \"_fbp\" and \"_fbc\" are stored for up to 90 days.\n- scope: Contentsquare data\n  period: 13 months\n  text: The collected data is deleted after 13 months.\nresidency:\n- region: European Union\n  text: We process your data primarily within the European Union (EU) and the European Economic Area (EEA).\n- region: Germany\n  text: A server location in Germany has been selected; however, data transfers to the USA cannot be ruled out.\ntransfers:\n- mechanism: DPF\n  text: the EU-U.S. Data Privacy Framework applies. Microsoft is certified under this framework\n- mechanism: SCC\n  text: In addition, Standard Contractual Clauses (SCCs) have been concluded.\n- mechanism: other\n  text: Clay is not certified under the EU-U.S. Data Privacy Framework. The transfer is therefore based on Standard\n    Contractual Clauses of the European Commission (Article 46(2)(c) GDPR).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: each provider is required to enter into a data processing agreement with us.\ndeletion:\n  route: null\n  text: Personal data will be deleted or blocked as soon as the purpose for its storage no longer applies.\nrights:\n- right: Access\n  text: You have the right to obtain confirmation as to whether we are processing your personal data.\n- right: Rectification\n  text: You have the right to request the prompt rectification of inaccurate personal data.\n- right: Erasure\n  text: You have the right to request erasure of your personal data where processing is no longer necessary.\n- right: Restriction\n  text: You have the right to request restriction of processing\n- right: Portability\n  text: You have the right to receive your personal data in a structured, commonly used, and machine-readable format.\n- right: Object\n  text: You have the right to object, on grounds relating to your particular situation, at any time to the processing\n    of certain personal\
  \ data concerning you.\n- right: Withdraw consent\n  text: You may withdraw your consent to the processing of your personal data at any time with effect for the future.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workist/privacy/workist-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Workist's own page on 2026-11-10.
synthetic: false
tags:
- Documents
- Document Processing
- Artificial Intelligence
- Automation
- Order
- Invoices
- ERP
- B2B
- Master Data
---
