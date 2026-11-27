---
api_specs:
- filename: postman.yaml
  format: yaml
  label: LeadSquared REST API
  slug: rest-api
  spec_type: Postman
  url: https://apidocs.leadsquared.com/leadsquared-run-in-postman/
- filename: leadsquared-activities-api-openapi.yml
  format: yaml
  label: LeadSquared Activities API
  slug: leadsquared-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadsquared/openapi/leadsquared-activities-api-openapi.yml
- filename: leadsquared-leads-api-openapi.yml
  format: yaml
  label: LeadSquared Leads API
  slug: leadsquared-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadsquared/openapi/leadsquared-leads-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, e-mail; Your IP Address; Your location (Unless you deactivate location services in the relevant section of the App)
  - category: device
    text: What device you use to access the Website/App and its details (model, operating system, etc.)
  - category: behavioral
    text: How you behave in the relevant product environment and use the features
  - category: communication
    text: Phone call logs to record your call activities with Leads (i.e. call time, duration, phone number of relevant Lead)
  - category: financial
    text: Credit Card/Debit Card/Other Payment Mode information to check your financial qualifications, detect fraud and facilitate payments for our Services.
  deletion:
    route: Request to privacy@leadsquared.com or the contact details in Section 12
    text: In case you want to exercise any of the rights set out above you can reach us at privacy@leadsquared.com or at the contact details mentioned in Section 12 below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Analyse behaviour and enhance website interactions
    text: We use this information to analyse and identify your behaviour and enhance the interactions you have with the Website.
  - purpose: Register and provide Services
    text: We collect this data in order to help you register for and facilitate provision of our Services.
  - purpose: Payment processing
    text: We also use this data to enable you to make payments for our Services.
  - purpose: Marketing e-mails and newsletters with consent
    text: If you give us your consent, we may send you newsletters and e-mails to market other products and services we may provide.
  retention:
  - period: null
    scope: Personal data collected from you
    text: We will store any personal data we collect from you as long as it is necessary in order to facilitate your use of the Services and for ancillary legitimate and essential business purposes
  - period: null
    scope: Customer data after termination
    text: after you terminate your usage of a Service, we may, unless legally prohibited, delete all data provided or collected by you (including Lead information) from our servers.
  rights:
  - right: Right of access
    text: You have a right to access the personal data you have provided by requesting us to provide you with the same.
  - right: Right to erasure
    text: You have a right to request us to delete your personal data.
  - right: Right to object to direct marketing
    text: You have a right, at any time, to object to us processing your personal data for the purposes of direct marketing.
  - right: Right to data portability
    text: You have a right to request us to provide you with a copy of your personal data in electronic format and you can transmit that personal data for using another third-party’s product/service.
  role:
    text: We process such personal data as a processor on behalf of our customer, who is the controller of such data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any data of our users/customers/leads.
  subprocessors:
    text: Some of the examples of where we may sub-contract processing activities to third parties include—data analysis, marketing assistance, processing credit card payments, and providing customer service.
    url: null
  transfers:
  - mechanism: other
    text: ensuring that the recipients of your data are certified under recognized data protection frameworks
  - mechanism: other
    text: entering into data transfer agreements based on requirements of relevant data protection authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LeadSquared
provenance_date: '2026-11-09'
provider_name: LeadSquared
provider_slug: leadsquared
slug: leadsquared-privacy-policy
source_date: '2026-11-09'
source_filename: leadsquared-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.leadsquared.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LeadSquared\naid: leadsquared\nurl: https://www.leadsquared.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We process such personal data as a processor on behalf of our customer, who is the controller of such data.\ndata_categories:\n- category: identifying\n  text: Your name, e-mail; Your IP Address; Your location (Unless you deactivate location services in the relevant\n    section of the App)\n- category: device\n  text: What device you use to access the Website/App and its details (model, operating system, etc.)\n- category: behavioral\n  text: How you behave in the relevant\
  \ product environment and use the features\n- category: communication\n  text: Phone call logs to record your call activities with Leads (i.e. call time, duration, phone number of relevant\n    Lead)\n- category: financial\n  text: Credit Card/Debit Card/Other Payment Mode information to check your financial qualifications, detect fraud\n    and facilitate payments for our Services.\npurposes:\n- purpose: Analyse behaviour and enhance website interactions\n  text: We use this information to analyse and identify your behaviour and enhance the interactions you have with\n    the Website.\n- purpose: Register and provide Services\n  text: We collect this data in order to help you register for and facilitate provision of our Services.\n- purpose: Payment processing\n  text: We also use this data to enable you to make payments for our Services.\n- purpose: Marketing e-mails and newsletters with consent\n  text: If you give us your consent, we may send you newsletters and e-mails to market other\
  \ products and services\n    we may provide.\nretention:\n- scope: Personal data collected from you\n  period: null\n  text: We will store any personal data we collect from you as long as it is necessary in order to facilitate your\n    use of the Services and for ancillary legitimate and essential business purposes\n- scope: Customer data after termination\n  period: null\n  text: after you terminate your usage of a Service, we may, unless legally prohibited, delete all data provided\n    or collected by you (including Lead information) from our servers.\nresidency: []\ntransfers:\n- mechanism: other\n  text: ensuring that the recipients of your data are certified under recognized data protection frameworks\n- mechanism: other\n  text: entering into data transfer agreements based on requirements of relevant data protection authorities\nsubprocessors:\n  url: null\n  text: Some of the examples of where we may sub-contract processing activities to third parties include—data analysis,\n\
  \    marketing assistance, processing credit card payments, and providing customer service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to privacy@leadsquared.com or the contact details in Section 12\n  text: In case you want to exercise any of the rights set out above you can reach us at privacy@leadsquared.com\n    or at the contact details mentioned in Section 12 below.\nrights:\n- right: Right of access\n  text: You have a right to access the personal data you have provided by requesting us to provide you with the\n    same.\n- right: Right to erasure\n  text: You have a right to request us to delete your personal data.\n- right: Right to object to direct marketing\n  text: You have a right, at any time, to object to us processing your personal data for the purposes of direct\n    marketing.\n- right: Right to data portability\n  text: You have a right to request us to provide you with a copy of your personal data in electronic format and\n    you\
  \ can transmit that personal data for using another third-party’s product/service.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any data of our users/customers/leads.\n"
source_yaml_url: https://artifacts.apis.io/leadsquared/privacy/leadsquared-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from LeadSquared's own page on 2026-11-09.
synthetic: false
tags:
- Marketing Automation
- CRM
- Sales Automation
- Lead Management
- Customer Engagement
- Field Force Automation
---
