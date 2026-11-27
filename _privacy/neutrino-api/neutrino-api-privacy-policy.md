---
api_specs:
- filename: neutrino-api-data-tools-api-openapi.yml
  format: yaml
  label: Neutrino API Data Tools API
  slug: neutrino-api-data-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-data-tools-api-openapi.yml
- filename: neutrino-api-geolocation-api-openapi.yml
  format: yaml
  label: Neutrino API Geolocation API
  slug: neutrino-api-geolocation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-geolocation-api-openapi.yml
- filename: neutrino-api-imaging-api-openapi.yml
  format: yaml
  label: Neutrino API Imaging API
  slug: neutrino-api-imaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-imaging-api-openapi.yml
- filename: neutrino-api-security-and-networking-api-openapi.yml
  format: yaml
  label: Neutrino API Security and Networking API
  slug: neutrino-api-security-and-networking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-security-and-networking-api-openapi.yml
- filename: neutrino-api-telephony-api-openapi.yml
  format: yaml
  label: Neutrino API Telephony API
  slug: neutrino-api-telephony-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-telephony-api-openapi.yml
- filename: neutrino-api-www-api-openapi.yml
  format: yaml
  label: Neutrino API WWW API
  slug: neutrino-api-www-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-www-api-openapi.yml
- filename: neutrino-api-ecommerce-api-openapi.yml
  format: yaml
  label: Neutrino API Ecommerce API
  slug: neutrino-api-ecommerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neutrino-api/openapi/neutrino-api-ecommerce-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: 1. Contact Information
  - category: other
    text: Any other Personal Data submitted by you, or your end users, via the API service.
  - category: contact
    source: https://www.neutrinoapi.com/privacy-policy/
    text: We collect (optionally) your email address if you choose to provide this information for your account.
  - category: contact
    source: https://www.neutrinoapi.com/privacy-policy/
    text: We collect (optionally) your phone number for verification purposes and for 2FA recovery and backup.
  - category: financial
    source: https://www.neutrinoapi.com/privacy-policy/
    text: We collect your name and postal code when making credit card payments as required to process payments.
  deletion:
    route: Deletion by Processor within 10 business days of cessation, with written certification on request
    text: Processor shall provide written certification to Controller that it has fully complied with this section 9 within 10 business days of the Cessation Date.
  dpa:
    available: true
    text: This Neutrino API Data Processing Agreement and its Annexes (“DPA”) reflects the parties’ agreement with respect to the Processing of Personal Data by us on behalf of you
    url: https://www.neutrinoapi.com/data-processing-agreement/
  purposes:
  - purpose: Provide API services
    text: We will process Personal Data as necessary to provide the API service pursuant to the Principal Agreement.
  - purpose: Legal disclosure
    text: Disclosure in accordance with the Principal Agreement and/or as compelled by applicable laws.
  - purpose: Process payments
    source: https://www.neutrinoapi.com/privacy-policy/
    text: To process payment transactions.
  - purpose: Account usage emails
    source: https://www.neutrinoapi.com/privacy-policy/
    text: To send emails regarding your API usage or any important account or API updates. We do not ever send any marketing or sales emails.
  - purpose: Account verification and recovery
    source: https://www.neutrinoapi.com/privacy-policy/
    text: To verify your account and to enable account recovery via email or phone number.
  - purpose: Email support
    source: https://www.neutrinoapi.com/privacy-policy/
    text: To provide email support via our ticketing system.
  residency:
  - region: Subprocessor data centers
    text: Google Cloud Platform (GCP) Hosting & Infrastructure Australia, Germany, Netherlands, USA
  - region: Subprocessor data centers
    text: Amazon Web Services (AWS) Hosting & Infrastructure Germany, Ireland, Singapore, USA
  - region: multi-region
    source: https://www.neutrinoapi.com/privacy-policy/
    text: Our server infrastructure is distributed globally across multiple cloud providers and data center regions.
  retention:
  - period: 0.1 to 30 seconds
    scope: API request data
    text: Personal Data is kept in volatile server memory only for the duration required to execute and process any API request and is then discarded immediately after. This duration typically ranges from 0.1 to 30 seconds depending on the performance of the specific API service endpoint being called.
  - period: 10 business days
    scope: Company Personal Data on cessation
    text: Processor shall promptly and in any event within 10 business days of the date of cessation of any Services involving the Processing of Company Personal Data (the "Cessation Date"), delete and procure the deletion of all copies of those Company Personal Data.
  - period: null
    scope: API request payloads and metadata
    source: https://www.neutrinoapi.com/privacy-policy/
    text: We do not under any circumstance collect, log, store or transmit any of your information sent via the API.
  - period: null
    scope: API data in memory
    source: https://www.neutrinoapi.com/privacy-policy/
    text: Data sent to the API is briefly kept in volatile server memory for the execution of the API request and is then discarded immediately after, no logs are ever used
  rights:
  - right: Audit
    text: Processor shall make available to Controller on request all information necessary to demonstrate compliance with this Agreement, and shall allow for and contribute to audits, including inspections
  - right: Data subject request assistance
    text: Processor shall assist Controller by implementing appropriate technical and organisational measures, insofar as this is possible, for the fulfilment of Controller obligations
  role:
    text: Processing of Personal Data by us on behalf of you in connection with the Neutrino API Services
    value: processor
  sale_or_sharing:
    source: https://www.neutrinoapi.com/privacy-policy/
    stance: prohibited
    text: We do not ever sell, trade, or otherwise transfer to outside parties any of the information you provide to us via our website or API service.
  subprocessors:
    text: We have currently appointed, as Subprocessors, the third parties listed in ANNEX 1 of this DPA.
    url: https://www.neutrinoapi.com/data-processing-agreement/
  transfers:
  - mechanism: other
    text: The Processor may not transfer or authorize the transfer of Data to countries outside the EU and/or the European Economic Area (EEA) or the UK.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Neutrino API
provenance_date: '2026-11-10'
provider_name: Neutrino API
provider_slug: neutrino-api
slug: neutrino-api-privacy-policy
source_date: '2026-11-10'
source_filename: neutrino-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.neutrinoapi.com/data-processing-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Neutrino API\naid: neutrino-api\nurl: https://www.neutrinoapi.com/data-processing-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.neutrinoapi.com/data-processing-agreement/\n  - https://www.neutrinoapi.com/privacy-policy/\nrole:\n  value: processor\n  text: Processing of Personal Data by us on behalf of you in connection with the Neutrino API Services\ndata_categories:\n- category: contact\n  text: 1. Contact Information\n- category: other\n  text: Any other Personal Data submitted by you, or your end users, via the API service.\n- category: contact\n  text: We collect (optionally) your\
  \ email address if you choose to provide this information for your account.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- category: contact\n  text: We collect (optionally) your phone number for verification purposes and for 2FA recovery and backup.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- category: financial\n  text: We collect your name and postal code when making credit card payments as required to process payments.\n  source: https://www.neutrinoapi.com/privacy-policy/\npurposes:\n- purpose: Provide API services\n  text: We will process Personal Data as necessary to provide the API service pursuant to the Principal Agreement.\n- purpose: Legal disclosure\n  text: Disclosure in accordance with the Principal Agreement and/or as compelled by applicable laws.\n- purpose: Process payments\n  text: To process payment transactions.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- purpose: Account usage emails\n  text: To send emails regarding your API\
  \ usage or any important account or API updates. We do not ever send any\n    marketing or sales emails.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- purpose: Account verification and recovery\n  text: To verify your account and to enable account recovery via email or phone number.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- purpose: Email support\n  text: To provide email support via our ticketing system.\n  source: https://www.neutrinoapi.com/privacy-policy/\nretention:\n- scope: API request data\n  period: 0.1 to 30 seconds\n  text: Personal Data is kept in volatile server memory only for the duration required to execute and process any\n    API request and is then discarded immediately after. This duration typically ranges from 0.1 to 30 seconds depending\n    on the performance of the specific API service endpoint being called.\n- scope: Company Personal Data on cessation\n  period: 10 business days\n  text: Processor shall promptly and in any event within\
  \ 10 business days of the date of cessation of any Services\n    involving the Processing of Company Personal Data (the \"Cessation Date\"), delete and procure the deletion of\n    all copies of those Company Personal Data.\n- scope: API request payloads and metadata\n  period: null\n  text: We do not under any circumstance collect, log, store or transmit any of your information sent via the API.\n  source: https://www.neutrinoapi.com/privacy-policy/\n- scope: API data in memory\n  period: null\n  text: Data sent to the API is briefly kept in volatile server memory for the execution of the API request and\n    is then discarded immediately after, no logs are ever used\n  source: https://www.neutrinoapi.com/privacy-policy/\nresidency:\n- region: Subprocessor data centers\n  text: Google Cloud Platform (GCP) Hosting & Infrastructure Australia, Germany, Netherlands, USA\n- region: Subprocessor data centers\n  text: Amazon Web Services (AWS) Hosting & Infrastructure Germany, Ireland, Singapore,\
  \ USA\n- region: multi-region\n  text: Our server infrastructure is distributed globally across multiple cloud providers and data center regions.\n  source: https://www.neutrinoapi.com/privacy-policy/\ntransfers:\n- mechanism: other\n  text: The Processor may not transfer or authorize the transfer of Data to countries outside the EU and/or the\n    European Economic Area (EEA) or the UK.\nsubprocessors:\n  url: https://www.neutrinoapi.com/data-processing-agreement/\n  text: We have currently appointed, as Subprocessors, the third parties listed in ANNEX 1 of this DPA.\ndpa:\n  available: true\n  url: https://www.neutrinoapi.com/data-processing-agreement/\n  text: This Neutrino API Data Processing Agreement and its Annexes (“DPA”) reflects the parties’ agreement with\n    respect to the Processing of Personal Data by us on behalf of you\ndeletion:\n  route: Deletion by Processor within 10 business days of cessation, with written certification on request\n  text: Processor shall provide\
  \ written certification to Controller that it has fully complied with this section\n    9 within 10 business days of the Cessation Date.\nrights:\n- right: Audit\n  text: Processor shall make available to Controller on request all information necessary to demonstrate compliance\n    with this Agreement, and shall allow for and contribute to audits, including inspections\n- right: Data subject request assistance\n  text: Processor shall assist Controller by implementing appropriate technical and organisational measures, insofar\n    as this is possible, for the fulfilment of Controller obligations\nsale_or_sharing:\n  stance: prohibited\n  text: We do not ever sell, trade, or otherwise transfer to outside parties any of the information you provide\n    to us via our website or API service.\n  source: https://www.neutrinoapi.com/privacy-policy/\n"
source_yaml_url: https://artifacts.apis.io/neutrino-api/privacy/neutrino-api-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Neutrino API's own page on 2026-11-10.
synthetic: false
tags:
- Data Validation
- Data Tools
- Telephony
- Communications
- SMS
- Voice
- Geolocation
- IP Intelligence
- Security
- Networking
- Fraud Prevention
- E-Commerce
- Payments
- Imaging
- Rendering
- Currency
- Foreign Exchange
---
