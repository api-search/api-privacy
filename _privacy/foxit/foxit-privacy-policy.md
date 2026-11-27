---
api_specs:
- filename: foxit-document-generation-api-openapi.yml
  format: yaml
  label: Foxit eSign Document Generation API
  slug: foxit-document-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-document-generation-api-openapi.yml
- filename: foxit-documents-api-openapi.yml
  format: yaml
  label: Foxit eSign Documents API
  slug: foxit-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-documents-api-openapi.yml
- filename: foxit-foxit-esign-api-api-openapi.yml
  format: yaml
  label: Foxit eSign Foxit ESign API
  slug: foxit-foxit-esign-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-foxit-esign-api-api-openapi.yml
- filename: foxit-pdf-services-api-openapi.yml
  format: yaml
  label: Foxit eSign Pdf Services API
  slug: foxit-pdf-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-pdf-services-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and last name; Company; Email; Telephone;
  - category: contact
    text: Your name; Your address; Your phone number; Your email address;
  - category: financial
    text: Payment information, such as your bank account or credit card information (if applicable).
  - category: device
    text: Your device type, model, name, mac, and ID;
  - category: behavioral
    text: Your pattern of use;
  - category: communication
    text: Any feedback you send us;
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Any transfers of personal data to HubSpot Cloud are covered by a Data Processing Agreement concluded between Foxit and HubSpot Cloud (Art. 28 GDPR).
    url: null
  purposes:
  - purpose: Website and service connection
    text: Ensuring a smooth connection to the website, products and services;
  - purpose: System security and stability
    text: Evaluation of system security and stability;
  - purpose: Sales and marketing
    text: For sales and marketing purposes, to follow up on requests, and to provide additional information or to answer questions;
  - purpose: Legal obligations
    text: For meeting legal obligations.
  residency:
  - region: United States
    text: Your data is hosted by Stripe in the United States.
  - region: United States
    text: Your data is hosted by Salesforce in the United States.
  retention:
  - period: until automated deletion
    scope: Website and product usage data
    text: will be stored until automated deletion
  - period: one day
    scope: Uploaded cloud files and outputs
    text: the output files will typically be deleted in one day
  - period: 24 hours
    scope: Azure AI document data
    text: will be deleted within 24 hours.
  - period: 30 days
    scope: Google AdWords conversion cookie
    text: After 30 days these cookies lose their validity
  rights:
  - right: Withdraw consent
    text: You can withdraw your consent at any time.
  - right: Opt out of sale or sharing
    text: Clicking “Do Not Sell or Share My Personal Information” in our cookie banner.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: some cookies may involve sharing of your personal information with third parties for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on the European Commission's Standard Contractual Clauses (SCCs) and the Data Privacy Framework to ensure a high level of protection for your personal data.
  - mechanism: DPF
    text: Any transfers to the US are covered by Google’s participation in the EU-US Data Privacy Framework which has been found to provide an adequate level of data protection (Art. 45 GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Foxit eSign
provenance_date: '2026-11-09'
provider_name: Foxit eSign
provider_slug: foxit
slug: foxit-privacy-policy
source_date: '2026-11-09'
source_filename: foxit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.foxit.com/company/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Foxit eSign\naid: foxit\nurl: https://www.foxit.com/company/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: First and last name; Company; Email; Telephone;\n- category: contact\n  text: Your name; Your address; Your phone number; Your email address;\n- category: financial\n  text: Payment information, such as your bank account or credit card information (if applicable).\n- category: device\n  text: Your device type, model, name, mac, and ID;\n- category: behavioral\n  text: Your pattern of use;\n- category:\
  \ communication\n  text: Any feedback you send us;\npurposes:\n- purpose: Website and service connection\n  text: Ensuring a smooth connection to the website, products and services;\n- purpose: System security and stability\n  text: Evaluation of system security and stability;\n- purpose: Sales and marketing\n  text: For sales and marketing purposes, to follow up on requests, and to provide additional information or to\n    answer questions;\n- purpose: Legal obligations\n  text: For meeting legal obligations.\nretention:\n- scope: Website and product usage data\n  period: until automated deletion\n  text: will be stored until automated deletion\n- scope: Uploaded cloud files and outputs\n  period: one day\n  text: the output files will typically be deleted in one day\n- scope: Azure AI document data\n  period: 24 hours\n  text: will be deleted within 24 hours.\n- scope: Google AdWords conversion cookie\n  period: 30 days\n  text: After 30 days these cookies lose their validity\nresidency:\n\
  - region: United States\n  text: Your data is hosted by Stripe in the United States.\n- region: United States\n  text: Your data is hosted by Salesforce in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on the European Commission's Standard Contractual Clauses (SCCs) and the Data Privacy Framework\n    to ensure a high level of protection for your personal data.\n- mechanism: DPF\n  text: Any transfers to the US are covered by Google’s participation in the EU-US Data Privacy Framework which\n    has been found to provide an adequate level of data protection (Art. 45 GDPR).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Any transfers of personal data to HubSpot Cloud are covered by a Data Processing Agreement concluded between\n    Foxit and HubSpot Cloud (Art. 28 GDPR).\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Withdraw consent\n  text: You can withdraw your consent at any time.\n- right: Opt out of sale or\
  \ sharing\n  text: Clicking “Do Not Sell or Share My Personal Information” in our cookie banner.\nsale_or_sharing:\n  stance: conditional\n  text: some cookies may involve sharing of your personal information with third parties for cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/foxit/privacy/foxit-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Foxit eSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Document Management
- PDF
- Cloud APIs
- Enterprise Software
- Workflow Automation
---
