---
api_specs:
- filename: bigdata-analyst-estimates-api-openapi.yml
  format: yaml
  label: RavenPack Analyst Estimates API
  slug: bigdata-analyst-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-analyst-estimates-api-openapi.yml
- filename: bigdata-company-events-api-openapi.yml
  format: yaml
  label: RavenPack Company & Events API
  slug: bigdata-company-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-company-events-api-openapi.yml
- filename: bigdata-financials-ratios-api-openapi.yml
  format: yaml
  label: RavenPack Financials & Ratios API
  slug: bigdata-financials-ratios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-financials-ratios-api-openapi.yml
- filename: bigdata-fixed-income-api-openapi.yml
  format: yaml
  label: RavenPack Fixed Income API
  slug: bigdata-fixed-income-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-fixed-income-api-openapi.yml
- filename: bigdata-fund-holdings-api-openapi.yml
  format: yaml
  label: RavenPack Fund Holdings API
  slug: bigdata-fund-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-fund-holdings-api-openapi.yml
- filename: bigdata-market-data-api-openapi.yml
  format: yaml
  label: RavenPack Market Data API
  slug: bigdata-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-market-data-api-openapi.yml
- filename: bigdata-private-markets-api-openapi.yml
  format: yaml
  label: RavenPack Private Markets API
  slug: bigdata-private-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigdata/openapi/bigdata-private-markets-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: The data collected may include your full name, address, job title, company name, phone number, email address, account login credentials, payment card details, tax information, and transaction history
  - category: device
    text: Browser type, device identifiers, and other technical details.
  - category: location
    text: IP address and geographic location of access;
  - category: behavioral
    text: Performance metrics and usage analytics;
  - category: communication
    text: We may collect personal data when you contact us, submit feedback, or upload content to our Services.
  - category: financial
    text: payment method information (e.g. IBAN, credit card, billing address)
  deletion:
    route: contacting legal@bigdata.com
    text: Requests shall be filed free of charge and processed by the Controller within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account setup and customer support
    text: to set up and administer your account, provide technical and customer support and training, verify your identity
  - purpose: Legal obligations
    text: such as the prevention, detection, or investigation of a crime; loss prevention; or fraud.
  - purpose: Direct marketing
    text: We may process your personal data in order to send you newsletters, promotional communications, and updates about our products, services, events, and industry-related insights.
  - purpose: Disaster recovery
    text: This includes the creation and maintenance of secure system backups to ensure that essential data can be restored in the event of an incident
  - purpose: Legal defense
    text: We process personal data to establish, exercise, or defend legal claims, and to manage disputes related to our services.
  - purpose: Payments management
    text: We process personal data to manage and execute payments related to our services or products, through the APP.
  - purpose: Lead qualification
    text: Through the services we may process Usage Data collected through our product analytics platform to identify Product Qualified Leads (“PQLs”).
  retention:
  - period: 12 months
    scope: Account data
    text: for a maximum of 12 months after account closure, unless a longer period is required for legal or contractual reasons
  - period: 10 years
    scope: Legal obligations data
    text: Personal data is retained for a maximum period of 10 years, unless the applicable law provides otherwise.
  - period: 12 months
    scope: Marketing data
    text: In any case, data will not be kept for longer than 12 months from your last interaction
  - period: 12 months
    scope: Disaster recovery backups
    text: are not kept for longer than 12 months, unless required for the investigation of a specific security incident
  - period: 10 years
    scope: Payment and invoicing data
    text: payment and invoicing data is retained for a period of 10 years, in accordance with applicable accounting and tax laws
  - period: 12 months
    scope: Analytics data
    text: Analytics data is retained for 12 months, unless you withdraw your consent earlier.
  rights:
  - right: access
    text: Obtain confirmation that processing is underway (Art. 15);
  - right: rectification
    text: Obtain the rectification of inaccurate or incomplete data (Art. 16);
  - right: erasure
    text: Obtain the deletion of data without undue delay (Art. 17);
  - right: restriction
    text: Limit the processing to only part of the personal data (Art. 18);
  - right: portability
    text: Receive a copy of the personal data in the possession of the data controller, in a commonly used and machine-readable format
  - right: objection
    text: Object to the processing of your personal data at any time. (Art. 21);
  role:
    text: The data controller is RavenPack International S.L.U. (hereinafter, the “Controller”, “Company”, “we” or “us”)
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Transfers shall be carried out by means of appropriate safeguards, such as adequacy decisions, standard contractual clauses approved by the European Commission or other safeguards provided for in the GDPR.
  - mechanism: SCC
    text: standard contractual clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RavenPack
provenance_date: '2026-11-09'
provider_name: RavenPack
provider_slug: bigdata
slug: bigdata-privacy-policy
source_date: '2026-11-09'
source_filename: bigdata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bigdata.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RavenPack\naid: bigdata\nurl: https://bigdata.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is RavenPack International S.L.U. (hereinafter, the “Controller”, “Company”, “we” or\n    “us”)\ndata_categories:\n- category: identifying\n  text: The data collected may include your full name, address, job title, company name, phone number, email address,\n    account login credentials, payment card details, tax information, and transaction history\n- category: device\n  text: Browser type, device identifiers, and other technical details.\n- category: location\n\
  \  text: IP address and geographic location of access;\n- category: behavioral\n  text: Performance metrics and usage analytics;\n- category: communication\n  text: We may collect personal data when you contact us, submit feedback, or upload content to our Services.\n- category: financial\n  text: payment method information (e.g. IBAN, credit card, billing address)\npurposes:\n- purpose: Account setup and customer support\n  text: to set up and administer your account, provide technical and customer support and training, verify your\n    identity\n- purpose: Legal obligations\n  text: such as the prevention, detection, or investigation of a crime; loss prevention; or fraud.\n- purpose: Direct marketing\n  text: We may process your personal data in order to send you newsletters, promotional communications, and updates\n    about our products, services, events, and industry-related insights.\n- purpose: Disaster recovery\n  text: This includes the creation and maintenance of secure system\
  \ backups to ensure that essential data can be\n    restored in the event of an incident\n- purpose: Legal defense\n  text: We process personal data to establish, exercise, or defend legal claims, and to manage disputes related\n    to our services.\n- purpose: Payments management\n  text: We process personal data to manage and execute payments related to our services or products, through the\n    APP.\n- purpose: Lead qualification\n  text: Through the services we may process Usage Data collected through our product analytics platform to identify\n    Product Qualified Leads (“PQLs”).\nretention:\n- scope: Account data\n  period: 12 months\n  text: for a maximum of 12 months after account closure, unless a longer period is required for legal or contractual\n    reasons\n- scope: Legal obligations data\n  period: 10 years\n  text: Personal data is retained for a maximum period of 10 years, unless the applicable law provides otherwise.\n- scope: Marketing data\n  period: 12 months\n  text:\
  \ In any case, data will not be kept for longer than 12 months from your last interaction\n- scope: Disaster recovery backups\n  period: 12 months\n  text: are not kept for longer than 12 months, unless required for the investigation of a specific security incident\n- scope: Payment and invoicing data\n  period: 10 years\n  text: payment and invoicing data is retained for a period of 10 years, in accordance with applicable accounting\n    and tax laws\n- scope: Analytics data\n  period: 12 months\n  text: Analytics data is retained for 12 months, unless you withdraw your consent earlier.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Transfers shall be carried out by means of appropriate safeguards, such as adequacy decisions, standard\n    contractual clauses approved by the European Commission or other safeguards provided for in the GDPR.\n- mechanism: SCC\n  text: standard contractual clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contacting legal@bigdata.com\n  text: Requests shall be filed free of charge and processed by the Controller within 30 days.\nrights:\n- right: access\n  text: Obtain confirmation that processing is underway (Art. 15);\n- right: rectification\n  text: Obtain the rectification of inaccurate or incomplete data (Art. 16);\n- right: erasure\n  text: Obtain the deletion of data without undue delay (Art. 17);\n- right: restriction\n  text: Limit the processing to only part of the personal data (Art. 18);\n- right: portability\n  text: Receive a copy of the personal data in the possession of the data controller, in a commonly used and machine-readable\n    format\n- right: objection\n  text: Object to the processing of your personal data at any time. (Art. 21);\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bigdata/privacy/bigdata-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 29 quoted statements, read from RavenPack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Data Analytics
- Market Insights
---
