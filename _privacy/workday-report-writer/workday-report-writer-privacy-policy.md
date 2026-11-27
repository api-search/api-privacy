---
api_specs:
- filename: workday-report-writer-agentdefinition-api-openapi.yml
  format: yaml
  label: Workday Report Writer Agent Definition API
  slug: workday-report-writer-agentdefinition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-agentdefinition-api-openapi.yml
- filename: workday-report-writer-buckets-api-openapi.yml
  format: yaml
  label: Workday Report Writer Buckets API
  slug: workday-report-writer-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-buckets-api-openapi.yml
- filename: workday-report-writer-custom-reports-api-openapi.yml
  format: yaml
  label: Workday Report Writer Custom Reports API
  slug: workday-report-writer-custom-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-custom-reports-api-openapi.yml
- filename: workday-report-writer-data-change-tasks-api-openapi.yml
  format: yaml
  label: Workday Report Writer Data Change Tasks API
  slug: workday-report-writer-data-change-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-data-change-tasks-api-openapi.yml
- filename: workday-report-writer-data-sources-api-openapi.yml
  format: yaml
  label: Workday Report Writer Data Sources API
  slug: workday-report-writer-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-data-sources-api-openapi.yml
- filename: workday-report-writer-datasets-api-openapi.yml
  format: yaml
  label: Workday Report Writer Datasets API
  slug: workday-report-writer-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-datasets-api-openapi.yml
- filename: workday-report-writer-query-execution-api-openapi.yml
  format: yaml
  label: Workday Report Writer Query Execution API
  slug: workday-report-writer-query-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-query-execution-api-openapi.yml
- filename: workday-report-writer-tables-api-openapi.yml
  format: yaml
  label: Workday Report Writer Tables API
  slug: workday-report-writer-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-report-writer/openapi/workday-report-writer-tables-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Your business contact information such as name, email, telephone number, company name, job details, and address.
  - category: device
    text: 'Technical Information: This includes your IP address, device type (e.g., iPhone,desktop, PC), unique device identifiers'
  - category: behavioral
    text: 'Usage Information: We also collect information about how you interact with our websites.'
  - category: communication
    text: Audio and, if applicable, video content of recorded calls/meetings.
  - category: health
    text: health and safety details (emergency contact, dietary preferences)
  - category: financial
    text: billing information (name, address, credit card number)
  - category: demographic
    text: gender, age group, and other information relevant to the study.
  deletion:
    route: online form
    text: submit a request through our online form
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision and operation
    text: 'Service provision and operation: To ensure the proper functioning, maintenance, and improvement of our services.'
  - purpose: Analyze and improve offerings
    text: 'Analyze and improve our offerings: We use this information for internal analysis to better understand who our visitors are, where they come from, and what content interests them the most.'
  retention:
  - period: null
    scope: general personal information
    text: We keep your personal information for as long as we have a legitimate business need to do so
  rights:
  - right: access
    text: Obtain access to your personal information that is being processed by us.
  - right: correction
    text: Correct inaccurate personal information.
  - right: deletion
    text: Request the deletion of your personal information.
  - right: opt out of sale or sharing
    text: Opt out of the sale or sharing of personal information for targeted advertising.
  - right: portability
    text: Request the portability of your personal information in a structured, commonly used, and machine-readable format.
  - right: withdraw consent
    text: Withdraw your consent at any time, if we have collected and processed your personal information with your consent.
  role:
    text: Depending on the situation, Workday can be either a controller or a processor.
    value: both
  sale_or_sharing:
    stance: conditional
    text: our disclosure of this information to third parties through cookies and other trackers for targeted advertising may be considered a “sale” or “share” of personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Workday relies on the DPF as a legal basis for transfers of personal information from the EEA, UK, and Switzerland to the United States.
  - mechanism: SCC
    text: entering into “standard contractual clauses” approved by the European Commission or competent governmental authority (as applicable) with the data importer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Workday Report Writer
provenance_date: '2026-11-10'
provider_name: Workday Report Writer
provider_slug: workday-report-writer
slug: workday-report-writer-privacy-policy
source_date: '2026-11-10'
source_filename: workday-report-writer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.workday.com/en-us/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Workday Report Writer\naid: workday-report-writer\nurl: https://www.workday.com/en-us/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Depending on the situation, Workday can be either a controller or a processor.\ndata_categories:\n- category: contact\n  text: Your business contact information such as name, email, telephone number, company name, job details, and\n    address.\n- category: device\n  text: 'Technical Information: This includes your IP address, device type (e.g., iPhone,desktop, PC), unique device\n    identifiers'\n- category: behavioral\n  text: 'Usage Information: We\
  \ also collect information about how you interact with our websites.'\n- category: communication\n  text: Audio and, if applicable, video content of recorded calls/meetings.\n- category: health\n  text: health and safety details (emergency contact, dietary preferences)\n- category: financial\n  text: billing information (name, address, credit card number)\n- category: demographic\n  text: gender, age group, and other information relevant to the study.\npurposes:\n- purpose: Service provision and operation\n  text: 'Service provision and operation: To ensure the proper functioning, maintenance, and improvement of our\n    services.'\n- purpose: Analyze and improve offerings\n  text: 'Analyze and improve our offerings: We use this information for internal analysis to better understand who\n    our visitors are, where they come from, and what content interests them the most.'\nretention:\n- scope: general personal information\n  period: null\n  text: We keep your personal information for\
  \ as long as we have a legitimate business need to do so\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Workday relies on the DPF as a legal basis for transfers of personal information from the EEA, UK, and Switzerland\n    to the United States.\n- mechanism: SCC\n  text: entering into “standard contractual clauses” approved by the European Commission or competent governmental\n    authority (as applicable) with the data importer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: online form\n  text: submit a request through our online form\nrights:\n- right: access\n  text: Obtain access to your personal information that is being processed by us.\n- right: correction\n  text: Correct inaccurate personal information.\n- right: deletion\n  text: Request the deletion of your personal information.\n- right: opt out of sale or sharing\n  text: Opt out of the sale or sharing of personal information for targeted advertising.\n\
  - right: portability\n  text: Request the portability of your personal information in a structured, commonly used, and machine-readable\n    format.\n- right: withdraw consent\n  text: Withdraw your consent at any time, if we have collected and processed your personal information with your\n    consent.\nsale_or_sharing:\n  stance: conditional\n  text: our disclosure of this information to third parties through cookies and other trackers for targeted advertising\n    may be considered a “sale” or “share” of personal information.\n"
source_yaml_url: https://artifacts.apis.io/workday-report-writer/privacy/workday-report-writer-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Workday Report Writer's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Enterprise
- ERP
- Finance
- HRMS
- Reporting
- Software-as-a-Service
---
