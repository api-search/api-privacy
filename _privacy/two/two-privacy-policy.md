---
api_specs:
- filename: two-api-key-api-openapi.yml
  format: yaml
  label: Two API Key API
  slug: two-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/two/openapi/two-api-key-api-openapi.yml
- filename: two-invoice-api-openapi.yml
  format: yaml
  label: Two Invoice API
  slug: two-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/two/openapi/two-invoice-api-openapi.yml
- filename: two-order-api-openapi.yml
  format: yaml
  label: Two Order API
  slug: two-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/two/openapi/two-order-api-openapi.yml
- filename: two-order-intent-api-openapi.yml
  format: yaml
  label: Two Order intent API
  slug: two-order-intent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/two/openapi/two-order-intent-api-openapi.yml
- filename: two-settlement-report-api-openapi.yml
  format: yaml
  label: Two Settlement report API
  slug: two-settlement-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/two/openapi/two-settlement-report-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity Data : includes name, job title, company name'
  - category: identifying
    text: 'Identity Data : includes name, social security number (Sweden only).'
  - category: contact
    text: 'Contact Data : includes company email address and telephone number'
  - category: financial
    text: details about payments to and from the bank account you provide during the credit application process
  - category: behavioral
    text: 'Usage Data : information about how you use our website, IT, communication and other systems.'
  - category: device
    text: 'Technical Data: includes your computer’s Internet Protocol (IP) address, your browser type and version'
  - category: device
    text: unique device identifiers, device settings, and geo-location data.
  deletion:
    route: Request erasure
    text: Request erasure of your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract performance
    text: Where we need to perform the contract we are about to enter into or have entered into with you.
  - purpose: Marketing
    text: We may use your Identity, Contact, Technical, Usage, and Profile Data to form a view on what we think you may want or need
  - purpose: Legitimate interests
    text: Where it is necessary for our legitimate interests (or those of a third party) and your interests and fundamental rights do not override those interests.
  - purpose: Legal obligation
    text: Where we need to comply with a legal obligation.
  - purpose: Consent
    text: In limited circumstances where you have given your consent.
  retention:
  - period: null
    scope: General retention
    text: We will only retain your personal data for as long as reasonably necessary to fulfil the purposes we collected it for
  - period: null
    scope: Retention periods by data aspect
    text: Details of retention periods for different aspects of your personal data are available from us by contacting us.
  rights:
  - right: Access
    text: Request access to your personal data
  - right: Correction
    text: Request correction of the personal data that we hold about you.
  - right: Erasure
    text: Request erasure of your personal data.
  - right: Objection
    text: Object to processing of your personal data where we are relying on a legitimate interest
  - right: Restriction
    text: Request restriction of processing of your personal data.
  - right: Portability
    text: Request the transfer of your personal data to you or to a third party.
  - right: Withdraw consent
    text: Withdraw consent at any time where we are relying on consent to process your personal data.
  role:
    text: Two is the data controller and is responsible for certain personal data about you that we collect and use
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data;
  - mechanism: other
    text: we may use specific contracts approved for use in the UK which give personal data the same protection it has in the UK/EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Two
provenance_date: '2026-11-10'
provider_name: Two
provider_slug: two
slug: two-privacy-policy
source_date: '2026-11-10'
source_filename: two-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.two.inc/company/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Two\naid: two\nurl: https://www.two.inc/company/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Two is the data controller and is responsible for certain personal data about you that we collect and use\ndata_categories:\n- category: identifying\n  text: 'Identity Data : includes name, job title, company name'\n- category: identifying\n  text: 'Identity Data : includes name, social security number (Sweden only).'\n- category: contact\n  text: 'Contact Data : includes company email address and telephone number'\n- category: financial\n  text: details about payments to and\
  \ from the bank account you provide during the credit application process\n- category: behavioral\n  text: 'Usage Data : information about how you use our website, IT, communication and other systems.'\n- category: device\n  text: 'Technical Data: includes your computer’s Internet Protocol (IP) address, your browser type and version'\n- category: device\n  text: unique device identifiers, device settings, and geo-location data.\npurposes:\n- purpose: Contract performance\n  text: Where we need to perform the contract we are about to enter into or have entered into with you.\n- purpose: Marketing\n  text: We may use your Identity, Contact, Technical, Usage, and Profile Data to form a view on what we think you\n    may want or need\n- purpose: Legitimate interests\n  text: Where it is necessary for our legitimate interests (or those of a third party) and your interests and fundamental\n    rights do not override those interests.\n- purpose: Legal obligation\n  text: Where we need to comply\
  \ with a legal obligation.\n- purpose: Consent\n  text: In limited circumstances where you have given your consent.\nretention:\n- scope: General retention\n  period: null\n  text: We will only retain your personal data for as long as reasonably necessary to fulfil the purposes we collected\n    it for\n- scope: Retention periods by data aspect\n  period: null\n  text: Details of retention periods for different aspects of your personal data are available from us by contacting\n    us.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data;\n- mechanism: other\n  text: we may use specific contracts approved for use in the UK which give personal data the same protection it\n    has in the UK/EEA.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request erasure\n  text: Request erasure\
  \ of your personal data.\nrights:\n- right: Access\n  text: Request access to your personal data\n- right: Correction\n  text: Request correction of the personal data that we hold about you.\n- right: Erasure\n  text: Request erasure of your personal data.\n- right: Objection\n  text: Object to processing of your personal data where we are relying on a legitimate interest\n- right: Restriction\n  text: Request restriction of processing of your personal data.\n- right: Portability\n  text: Request the transfer of your personal data to you or to a third party.\n- right: Withdraw consent\n  text: Withdraw consent at any time where we are relying on consent to process your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/two/privacy/two-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 25 quoted statements, read from Two's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B Payments
- Fintech
- API Platform
- Checkout
- Trade Accounts
---
