---
api_specs:
- filename: workday-finance-accounts-api-openapi.yml
  format: yaml
  label: Workday Finance Accounts API
  slug: workday-finance-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-accounts-api-openapi.yml
- filename: workday-finance-cost-centers-api-openapi.yml
  format: yaml
  label: Workday Finance Cost Centers API
  slug: workday-finance-cost-centers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-cost-centers-api-openapi.yml
- filename: workday-finance-financial-periods-api-openapi.yml
  format: yaml
  label: Workday Finance Financial Periods API
  slug: workday-finance-financial-periods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-financial-periods-api-openapi.yml
- filename: workday-finance-journal-entries-api-openapi.yml
  format: yaml
  label: Workday Finance Journal Entries API
  slug: workday-finance-journal-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-journal-entries-api-openapi.yml
- filename: workday-finance-purchase-orders-api-openapi.yml
  format: yaml
  label: Workday Finance Purchase Orders API
  slug: workday-finance-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-purchase-orders-api-openapi.yml
- filename: workday-finance-requisitions-api-openapi.yml
  format: yaml
  label: Workday Finance Requisitions API
  slug: workday-finance-requisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-requisitions-api-openapi.yml
- filename: workday-finance-supplier-invoices-api-openapi.yml
  format: yaml
  label: Workday Finance Supplier Invoices API
  slug: workday-finance-supplier-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-supplier-invoices-api-openapi.yml
- filename: workday-finance-suppliers-api-openapi.yml
  format: yaml
  label: Workday Finance Suppliers API
  slug: workday-finance-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-suppliers-api-openapi.yml
- filename: workday-finance-worktags-api-openapi.yml
  format: yaml
  label: Workday Finance Worktags API
  slug: workday-finance-worktags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-finance/openapi/workday-finance-worktags-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Your business contact information such as name, email, telephone number, company name, job details, and address.
  - category: identifying
    text: Your name, email, company name, optional profile details (like a photo), authentication information (like a mobile number or other unique verification identifier)
  - category: device
    text: IP address, device type (e.g., iPhone,desktop, PC), unique device identifiers, the type of browser you are using
  - category: behavioral
    text: Which pages you visit and the features you use.
  - category: location
    text: broad geographic location from which you are accessing our site (country or city-level location based on your IP address).
  - category: health
    text: health and safety details (emergency contact, dietary preferences)
  - category: financial
    text: billing information (name, address, credit card number)
  - category: communication
    text: Audio and, if applicable, video content of recorded calls/meetings.
  deletion:
    route: Exercise request via online form or contact details
    text: When we no longer have a legitimate business need to process your personal information, we will either delete or anonymize it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to requests and provide product information
    text: To respond to your requests and provide you with product information (including telemarketing calls and marketing emails, in accordance with your marketing preferences).
  - purpose: Analyze and improve offerings
    text: We use this information for internal analysis to better understand who our visitors are, where they come from, and what content interests them the most.
  - purpose: Operate and secure the website
    text: We use this data to run, maintain, and protect our websites, ensure you can access the content you requested, and display information specific to your location.
  - purpose: Security and fraud prevention
    text: To detect and prevent security incidents and fraudulent activities.
  retention:
  - period: null
    scope: Personal information generally
    text: We keep your personal information for as long as we have a legitimate business need to do so
  - period: null
    scope: Backup archives
    text: If this is not possible (for example, because your personal information has been stored in backup archives), then we will securely store your personal information and isolate it from any further processing until deletion is possible.
  rights:
  - right: Access
    text: Obtain access to your personal information that is being processed by us.
  - right: Correction
    text: Correct inaccurate personal information.
  - right: Deletion
    text: Request the deletion of your personal information.
  - right: Opt out of sale or sharing for targeted advertising
    text: Opt out of the sale or sharing of personal information for targeted advertising.
  - right: Objection and restriction
    text: Object to the processing of your personal information carried out on the basis of our legitimate interests in the EEA, UK, and Switzerland, and ask us to restrict the processing of your personal information.
  - right: Portability
    text: Request the portability of your personal information in a structured, commonly used, and machine-readable format.
  - right: Withdraw consent
    text: Withdraw your consent at any time, if we have collected and processed your personal information with your consent.
  role:
    text: Depending on the situation, Workday can be either a controller or a processor.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Workday relies on the DPF as a legal basis for transfers of personal information from the EEA, UK, and Switzerland to the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Workday Finance
provenance_date: '2026-11-10'
provider_name: Workday Finance
provider_slug: workday-finance
slug: workday-finance-privacy-policy
source_date: '2026-11-10'
source_filename: workday-finance-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.workday.com/en-us/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Workday Finance\naid: workday-finance\nurl: https://www.workday.com/en-us/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Depending on the situation, Workday can be either a controller or a processor.\ndata_categories:\n- category: contact\n  text: Your business contact information such as name, email, telephone number, company name, job details, and\n    address.\n- category: identifying\n  text: Your name, email, company name, optional profile details (like a photo), authentication information (like\n    a mobile number or other unique verification identifier)\n- category: device\n\
  \  text: IP address, device type (e.g., iPhone,desktop, PC), unique device identifiers, the type of browser you are\n    using\n- category: behavioral\n  text: Which pages you visit and the features you use.\n- category: location\n  text: broad geographic location from which you are accessing our site (country or city-level location based on\n    your IP address).\n- category: health\n  text: health and safety details (emergency contact, dietary preferences)\n- category: financial\n  text: billing information (name, address, credit card number)\n- category: communication\n  text: Audio and, if applicable, video content of recorded calls/meetings.\npurposes:\n- purpose: Respond to requests and provide product information\n  text: To respond to your requests and provide you with product information (including telemarketing calls and\n    marketing emails, in accordance with your marketing preferences).\n- purpose: Analyze and improve offerings\n  text: We use this information for internal\
  \ analysis to better understand who our visitors are, where they come\n    from, and what content interests them the most.\n- purpose: Operate and secure the website\n  text: We use this data to run, maintain, and protect our websites, ensure you can access the content you requested,\n    and display information specific to your location.\n- purpose: Security and fraud prevention\n  text: To detect and prevent security incidents and fraudulent activities.\nretention:\n- scope: Personal information generally\n  period: null\n  text: We keep your personal information for as long as we have a legitimate business need to do so\n- scope: Backup archives\n  period: null\n  text: If this is not possible (for example, because your personal information has been stored in backup archives),\n    then we will securely store your personal information and isolate it from any further processing until deletion\n    is possible.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Workday relies on the\
  \ DPF as a legal basis for transfers of personal information from the EEA, UK, and Switzerland\n    to the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Exercise request via online form or contact details\n  text: When we no longer have a legitimate business need to process your personal information, we will either delete\n    or anonymize it.\nrights:\n- right: Access\n  text: Obtain access to your personal information that is being processed by us.\n- right: Correction\n  text: Correct inaccurate personal information.\n- right: Deletion\n  text: Request the deletion of your personal information.\n- right: Opt out of sale or sharing for targeted advertising\n  text: Opt out of the sale or sharing of personal information for targeted advertising.\n- right: Objection and restriction\n  text: Object to the processing of your personal information carried out on the basis of our legitimate interests\n    in\
  \ the EEA, UK, and Switzerland, and ask us to restrict the processing of your personal information.\n- right: Portability\n  text: Request the portability of your personal information in a structured, commonly used, and machine-readable\n    format.\n- right: Withdraw consent\n  text: Withdraw your consent at any time, if we have collected and processed your personal information with your\n    consent.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workday-finance/privacy/workday-finance-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 24 quoted statements, read from Workday Finance's own page on 2026-11-10.
synthetic: false
tags:
- Accounting
- Cloud
- Enterprise
- ERP
- Finance
- Financial Management
---
