---
api_specs:
- filename: attest-studies-api-openapi.yml
  format: yaml
  label: Attest Studies API
  slug: attest-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attest/openapi/attest-studies-api-openapi.yml
- filename: attest-study-api-openapi.yml
  format: yaml
  label: Attest Study API
  slug: attest-study-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attest/openapi/attest-study-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact → your name, email address, phone number, job title, etc.
  - category: financial
    text: Financial → your bank details or billing information.
  - category: device
    text: Technical → browser type and other technology on the devices you use to access the platform.
  - category: behavioral
    text: Usage → information about how you use our website, products and the Attest Service.
  - category: communication
    text: Survey → your survey responses.
  - category: identifying
    text: Unique ID → Customers who use Own Audience Surveys may choose to upload a unique identifier to the platform.
  - category: demographic
    text: 'Demographic data: → Customers who use Own Audience Surveys may choose to upload demographic data about you to the platform.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: To create and manage your account with us.
  - purpose: provide the service
    text: To provide the Attest Service.
  - purpose: analytics and improvement
    text: To understand how the Attest Service is used and what we could do to improve them
  - purpose: security
    text: To make our site more secure, to administer our site and for internal operations, including troubleshooting.
  residency:
  - region: Dublin
    text: We currently use Amazon Web Services and data is stored on servers located in Dublin.
  retention:
  - period: null
    scope: personal data generally
    text: We’ll keep your personal data for as long as necessary to fulfil the purposes we collected it for, including for the purposes of satisfying any accounting or legal requirements.
  rights:
  - right: access
    text: access personal data (also known as a “subject access request”)
  - right: erasure
    text: ask Attest to erase the personal data we hold about you
  - right: objection
    text: object to how Attest is using your personal data
  - right: withdraw consent
    text: withdraw your consent to Attest handling your personal data
  role:
    text: As a data controller, we understand it’s really important for you to know how we’re using your information
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal data and we will not sell it without providing you the right to opt out.
  subprocessors:
    text: We’ve set out a list of the main service providers we may share data with in order to provide the Attest Service under the ‘Service providers’ section at the bottom of this privacy policy.
    url: null
  transfers:
  - mechanism: adequacy
    text: we rely on the relevant “adequacy decisions” from the European Commission
  - mechanism: SCC
    text: relying on Standard Contractual Clauses or other lawful measures in order to protect personal data shared between Europe and the US.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Attest
provenance_date: '2026-11-09'
provider_name: Attest
provider_slug: attest
slug: attest-privacy-policy
source_date: '2026-11-09'
source_filename: attest-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.askattest.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Attest\naid: attest\nurl: https://www.askattest.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: As a data controller, we understand it’s really important for you to know how we’re using your information\ndata_categories:\n- category: contact\n  text: Contact → your name, email address, phone number, job title, etc.\n- category: financial\n  text: Financial → your bank details or billing information.\n- category: device\n  text: Technical → browser type and other technology on the devices you use to access the platform.\n- category: behavioral\n  text: Usage → information\
  \ about how you use our website, products and the Attest Service.\n- category: communication\n  text: Survey → your survey responses.\n- category: identifying\n  text: Unique ID → Customers who use Own Audience Surveys may choose to upload a unique identifier to the platform.\n- category: demographic\n  text: 'Demographic data: → Customers who use Own Audience Surveys may choose to upload demographic data about\n    you to the platform.'\npurposes:\n- purpose: account management\n  text: To create and manage your account with us.\n- purpose: provide the service\n  text: To provide the Attest Service.\n- purpose: analytics and improvement\n  text: To understand how the Attest Service is used and what we could do to improve them\n- purpose: security\n  text: To make our site more secure, to administer our site and for internal operations, including troubleshooting.\nretention:\n- scope: personal data generally\n  period: null\n  text: We’ll keep your personal data for as long as necessary\
  \ to fulfil the purposes we collected it for, including\n    for the purposes of satisfying any accounting or legal requirements.\nresidency:\n- region: Dublin\n  text: We currently use Amazon Web Services and data is stored on servers located in Dublin.\ntransfers:\n- mechanism: adequacy\n  text: we rely on the relevant “adequacy decisions” from the European Commission\n- mechanism: SCC\n  text: relying on Standard Contractual Clauses or other lawful measures in order to protect personal data shared\n    between Europe and the US.\nsubprocessors:\n  url: null\n  text: We’ve set out a list of the main service providers we may share data with in order to provide the Attest\n    Service under the ‘Service providers’ section at the bottom of this privacy policy.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: access personal data (also known as a “subject access request”)\n- right: erasure\n  text: ask Attest to\
  \ erase the personal data we hold about you\n- right: objection\n  text: object to how Attest is using your personal data\n- right: withdraw consent\n  text: withdraw your consent to Attest handling your personal data\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal data and we will not sell it without providing you the right to opt out.\n"
source_yaml_url: https://artifacts.apis.io/attest/privacy/attest-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Attest's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Consumer Insights
- Market Research
- Consumer
- Analytics
---
