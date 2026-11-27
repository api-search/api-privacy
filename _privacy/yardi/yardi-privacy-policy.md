---
api_specs:
- filename: yardi-billing-and-payments-api-openapi.yml
  format: yaml
  label: Yardi Billing and Payments Interface
  slug: yardi-billing-and-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-billing-and-payments-api-openapi.yml
- filename: yardi-common-data-api-openapi.yml
  format: yaml
  label: Yardi Common Data Interface
  slug: yardi-common-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-common-data-api-openapi.yml
- filename: yardi-job-cost-api-openapi.yml
  format: yaml
  label: Yardi Job Cost Interface
  slug: yardi-job-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-job-cost-api-openapi.yml
- filename: yardi-service-requests-api-openapi.yml
  format: yaml
  label: Yardi Service Requests Interface
  slug: yardi-service-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-service-requests-api-openapi.yml
- filename: yardi-vendor-invoicing-api-openapi.yml
  format: yaml
  label: Yardi Vendor Invoicing Interface
  slug: yardi-vendor-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yardi/openapi/yardi-vendor-invoicing-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: identifiers (such as name, address, email address, IP address, and account name)
  - category: contact
    text: contact information (such as your name, address, telephone number and email address)
  - category: professional
    text: professional information (such as your company name, job title, company address)
  - category: location
    text: geolocation data (derived from IP addresses)
  - category: behavioral
    text: internet or other electronic network activity information (such as browsing history, search history, and information regarding interactions with the Yardi Sites)
  - category: device
    text: device information, unique device identifiers, mobile network information
  - category: communication
    text: Recordings of telephone calls, video calls, live chat sessions, chatbot interactions, or other communications with you
  deletion:
    route: Privacy Request Form or contacting us
    text: Upon receiving a deletion request covered by the GDPR, the CCPA, or other applicable privacy law with respect to Yardi Sites, Yardi will delete the personal information we have collected about you
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to inquiries and fulfill requests
    text: To respond to your inquiries and fulfill your requests
  - purpose: marketing communications
    text: To send you marketing communications, including via email and SMS
  - purpose: targeted advertising
    text: To deliver and measure the effectiveness of targeted advertising, including cross-context behavioral advertising
  - purpose: business purposes
    text: For our business purposes, such as data analysis, audits, fraud monitoring and prevention, developing new products
  retention:
  - period: for the duration of your relationship with Yardi
    scope: Yardi Sites personal information
    text: Yardi retains the personal information we receive on the Yardi Sites for the duration of your relationship with Yardi, and where we have an ongoing legitimate business need to do so
  rights:
  - right: access
    text: the right to request information about the personal information we collect and share, to request access to, correction of, and deletion of such information
  - right: correction
    text: You have the right to request that Yardi correct inaccurate personal information that we maintain about you.
  - right: opt out of sale or sharing
    text: to opt out of the sale or sharing of personal information
  - right: restrict/object
    text: You can ask us to restrict processing of your personal data where
  - right: data portability
    text: You have the right to receive your information in a structured, commonly used, and machine-readable format and to share it with a third party.
  - right: withdraw consent
    text: you can withdraw your consent at any time by contacting us using the Privacy Request Form
  role:
    text: Yardi is a data processor and not a data controller under GDPR with respect to Client Data.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'A list of our service providers can be found here: https://resources.yardi.com/legal/yardi-service-providers/'
    url: https://resources.yardi.com/legal/yardi-service-providers/
  transfers:
  - mechanism: DPF
    text: The recipient of the personal information is located in the U.S. and has certified to the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yardi
provenance_date: '2026-11-10'
provider_name: Yardi
provider_slug: yardi
slug: yardi-privacy-policy
source_date: '2026-11-10'
source_filename: yardi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://resources.yardi.com/legal/privacy-statement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yardi\naid: yardi\nurl: https://resources.yardi.com/legal/privacy-statement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Yardi is a data processor and not a data controller under GDPR with respect to Client Data.\ndata_categories:\n- category: identifying\n  text: identifiers (such as name, address, email address, IP address, and account name)\n- category: contact\n  text: contact information (such as your name, address, telephone number and email address)\n- category: professional\n  text: professional information (such as your company name, job title, company address)\n- category: location\n\
  \  text: geolocation data (derived from IP addresses)\n- category: behavioral\n  text: internet or other electronic network activity information (such as browsing history, search history, and\n    information regarding interactions with the Yardi Sites)\n- category: device\n  text: device information, unique device identifiers, mobile network information\n- category: communication\n  text: Recordings of telephone calls, video calls, live chat sessions, chatbot interactions, or other communications\n    with you\npurposes:\n- purpose: respond to inquiries and fulfill requests\n  text: To respond to your inquiries and fulfill your requests\n- purpose: marketing communications\n  text: To send you marketing communications, including via email and SMS\n- purpose: targeted advertising\n  text: To deliver and measure the effectiveness of targeted advertising, including cross-context behavioral advertising\n- purpose: business purposes\n  text: For our business purposes, such as data analysis,\
  \ audits, fraud monitoring and prevention, developing new\n    products\nretention:\n- scope: Yardi Sites personal information\n  period: for the duration of your relationship with Yardi\n  text: Yardi retains the personal information we receive on the Yardi Sites for the duration of your relationship\n    with Yardi, and where we have an ongoing legitimate business need to do so\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: The recipient of the personal information is located in the U.S. and has certified to the EU-U.S. Data Privacy\n    Framework\nsubprocessors:\n  url: https://resources.yardi.com/legal/yardi-service-providers/\n  text: 'A list of our service providers can be found here: https://resources.yardi.com/legal/yardi-service-providers/'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Request Form or contacting us\n  text: Upon receiving a deletion request covered by the GDPR, the CCPA, or other applicable privacy law with respect\n \
  \   to Yardi Sites, Yardi will delete the personal information we have collected about you\nrights:\n- right: access\n  text: the right to request information about the personal information we collect and share, to request access\n    to, correction of, and deletion of such information\n- right: correction\n  text: You have the right to request that Yardi correct inaccurate personal information that we maintain about\n    you.\n- right: opt out of sale or sharing\n  text: to opt out of the sale or sharing of personal information\n- right: restrict/object\n  text: You can ask us to restrict processing of your personal data where\n- right: data portability\n  text: You have the right to receive your information in a structured, commonly used, and machine-readable format\n    and to share it with a third party.\n- right: withdraw consent\n  text: you can withdraw your consent at any time by contacting us using the Privacy Request Form\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yardi/privacy/yardi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from Yardi's own page on 2026-11-10.
synthetic: false
tags:
- Accounting
- Commercial Real Estate
- Co-Working
- Investment Management
- MCP
- Multifamily
- Property Management
- PropTech
- Real Estate
- Residential
- Self Storage
- Senior Living
---
