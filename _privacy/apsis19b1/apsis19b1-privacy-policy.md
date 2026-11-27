---
api_specs:
- filename: apsis19b1-audience-api-openapi.yml
  format: yaml
  label: Apsis19b1 Audience API
  slug: apsis19b1-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apsis19b1/openapi/apsis19b1-audience-api-openapi.yml
- filename: apsis19b1-oauth-api-openapi.yml
  format: yaml
  label: Apsis19b1 OAuth API
  slug: apsis19b1-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apsis19b1/openapi/apsis19b1-oauth-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: Data created and/or uploaded by customers (such as email, documents, contact information, etc.).
  - category: identifying
    text: Name, email, mobile number, birth date, CRM-ID, and cookie ID.
  - category: behavioral
    text: IP address, behavioural data, and geo-location (only Apsis Profile Cloud).
  deletion:
    route: Built-in product features allow customers to correct, export, and delete personal data on their own.
    text: all Apsis products include built-in features that allow you to handle data subject requests autonomously — including the ability to correct, export, and delete personal data on your own.
  dpa:
    available: null
    text: null
    url: null
  residency:
  - region: EEA/EU
    text: All personal data is hosted and processed within the EEA/EU, with no transfer to third parties outside, except for a limited use of Intercom (for support chat in some of our products), which can be disabled on request.
  - region: Ireland
    text: Apsis One and Apsis Pro data is stored in Ireland and backed up in Germany.
  retention:
  - period: null
    scope: Logs and backups
    text: Logs and backups are cleaned and deleted in cycles, with GDPR requirements taken into consideration.
  rights:
  - right: Data subject requests
    text: When Apsis receives a data subject request, we forward it to the controller (you) and assist as needed.
  role:
    text: Under the GDPR, you (our customer) are the controller of your personal data, and efficy acts as your processor.
    value: processor
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Apsis list of sub-processors is listed on efficy''s website, available here: Sub-processors information | efficy.'
    url: https://www.efficy.com
  transfers:
  - mechanism: other
    text: conducted a supplier compliance and data transfer assessment following the Schrems II decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apsis19b1
provenance_date: '2026-11-09'
provider_name: Apsis19b1
provider_slug: apsis19b1
slug: apsis19b1-privacy-policy
source_date: '2026-11-09'
source_filename: apsis19b1-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.apsis.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apsis19b1\naid: apsis19b1\nurl: https://www.apsis.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Under the GDPR, you (our customer) are the controller of your personal data, and efficy acts as your processor.\ndata_categories:\n- category: contact\n  text: Data created and/or uploaded by customers (such as email, documents, contact information, etc.).\n- category: identifying\n  text: Name, email, mobile number, birth date, CRM-ID, and cookie ID.\n- category: behavioral\n  text: IP address, behavioural data, and geo-location (only Apsis Profile Cloud).\npurposes: []\nretention:\n\
  - scope: Logs and backups\n  period: null\n  text: Logs and backups are cleaned and deleted in cycles, with GDPR requirements taken into consideration.\nresidency:\n- region: EEA/EU\n  text: All personal data is hosted and processed within the EEA/EU, with no transfer to third parties outside,\n    except for a limited use of Intercom (for support chat in some of our products), which can be disabled on request.\n- region: Ireland\n  text: Apsis One and Apsis Pro data is stored in Ireland and backed up in Germany.\ntransfers:\n- mechanism: other\n  text: conducted a supplier compliance and data transfer assessment following the Schrems II decision\nsubprocessors:\n  url: https://www.efficy.com\n  text: 'Apsis list of sub-processors is listed on efficy''s website, available here: Sub-processors information\n    | efficy.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Built-in product features allow customers to correct, export, and delete personal data on their\
  \ own.\n  text: all Apsis products include built-in features that allow you to handle data subject requests autonomously\n    — including the ability to correct, export, and delete personal data on your own.\nrights:\n- right: Data subject requests\n  text: When Apsis receives a data subject request, we forward it to the controller (you) and assist as needed.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apsis19b1/privacy/apsis19b1-privacy-policy.yml
stated_fields:
- role
- data_categories
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from Apsis19b1's own page on 2026-11-09.
synthetic: false
tags:
- Marketing
- Email
- Automation
- Artificial Intelligence
- GDPR
---
