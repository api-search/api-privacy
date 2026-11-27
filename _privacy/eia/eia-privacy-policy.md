---
api_specs:
- filename: eia-aeo-api-openapi.yml
  format: yaml
  label: EIA AEO API
  slug: eia-aeo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-aeo-api-openapi.yml
- filename: eia-coal-api-openapi.yml
  format: yaml
  label: EIA COAL API
  slug: eia-coal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-coal-api-openapi.yml
- filename: eia-crud-imports-api-openapi.yml
  format: yaml
  label: EIA CRUD IMPORTS API
  slug: eia-crud-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-crud-imports-api-openapi.yml
- filename: eia-dbf-api-openapi.yml
  format: yaml
  label: EIA DBF API
  slug: eia-dbf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-dbf-api-openapi.yml
- filename: eia-elec-api-openapi.yml
  format: yaml
  label: EIA ELEC API
  slug: eia-elec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-elec-api-openapi.yml
- filename: eia-emiss-api-openapi.yml
  format: yaml
  label: EIA EMISS API
  slug: eia-emiss-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-emiss-api-openapi.yml
- filename: eia-ieo-api-openapi.yml
  format: yaml
  label: EIA IEO API
  slug: eia-ieo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-ieo-api-openapi.yml
- filename: eia-intl-api-openapi.yml
  format: yaml
  label: EIA INTL API
  slug: eia-intl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-intl-api-openapi.yml
- filename: eia-ng-api-openapi.yml
  format: yaml
  label: EIA NG API
  slug: eia-ng-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-ng-api-openapi.yml
- filename: eia-nuc-status-api-openapi.yml
  format: yaml
  label: EIA NUC STATUS API
  slug: eia-nuc-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-nuc-status-api-openapi.yml
- filename: eia-root-api-openapi.yml
  format: yaml
  label: EIA Root API
  slug: eia-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-root-api-openapi.yml
- filename: eia-rto-api-openapi.yml
  format: yaml
  label: EIA RTO API
  slug: eia-rto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-rto-api-openapi.yml
- filename: eia-seds-api-openapi.yml
  format: yaml
  label: EIA SEDS API
  slug: eia-seds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-seds-api-openapi.yml
- filename: eia-sep-api-openapi.yml
  format: yaml
  label: EIA SEP API
  slug: eia-sep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-sep-api-openapi.yml
- filename: eia-steo-api-openapi.yml
  format: yaml
  label: EIA STEO API
  slug: eia-steo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-steo-api-openapi.yml
- filename: eia-total-api-openapi.yml
  format: yaml
  label: EIA TOTAL API
  slug: eia-total-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-total-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: collects and stores a standard set of Internet-related information, such as an Internet Protocol (IP) address
  - category: contact
    text: If you choose to provide us with personal information such as submitting information through the website on our Feedback page
  - category: behavioral
    text: These technologies anonymously track how visitors interact with EIA.gov, including where they came from, what they did on the site
  - category: device
    text: the type of browser and operating system used
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: optimize website and user experience
    text: This information is used to optimize our website; improve our user interface and ensure our content meets the needs of our customers.
  - purpose: respond to messages
    text: we use that information to respond to your message and to help us get you the information you have requested
  retention:
  - period: null
    scope: web measurement data
    text: The measurement data that is collected is only retained for as long as is needed for proper analysis and optimization of the website
  rights:
  - right: opt out of web measurement
    text: If you wish to opt-out from these web measurement technologies, you can find instructions for changing your browser settings
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: EIA does not give, sell, or transfer personal information to third parties, unless required by law, such as the Freedom of Information Act.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EIA
provenance_date: '2026-11-09'
provider_name: EIA
provider_slug: eia
slug: eia-privacy-policy
source_date: '2026-11-09'
source_filename: eia-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.eia.gov/about/privacy_security_policy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EIA\naid: eia\nurl: https://www.eia.gov/about/privacy_security_policy.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: collects and stores a standard set of Internet-related information, such as an Internet Protocol (IP) address\n- category: contact\n  text: If you choose to provide us with personal information such as submitting information through the website\n    on our Feedback page\n- category: behavioral\n  text: These technologies anonymously track how visitors interact with EIA.gov, including where they came from,\n    what they\
  \ did on the site\n- category: device\n  text: the type of browser and operating system used\npurposes:\n- purpose: optimize website and user experience\n  text: This information is used to optimize our website; improve our user interface and ensure our content meets\n    the needs of our customers.\n- purpose: respond to messages\n  text: we use that information to respond to your message and to help us get you the information you have requested\nretention:\n- scope: web measurement data\n  period: null\n  text: The measurement data that is collected is only retained for as long as is needed for proper analysis and\n    optimization of the website\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: opt out of web measurement\n  text: If you wish to opt-out from these web measurement technologies, you can find instructions for changing your\n    browser settings\n\
  sale_or_sharing:\n  stance: prohibited\n  text: EIA does not give, sell, or transfer personal information to third parties, unless required by law, such\n    as the Freedom of Information Act.\n"
source_yaml_url: https://artifacts.apis.io/eia/privacy/eia-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from EIA's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United States
- Energy Markets
- Electricity
- Natural Gas
- Petroleum
- Coal
- Nuclear
- Renewables
- Grid
- Emissions
- Government
- Open Data
- Energy Statistics
---
