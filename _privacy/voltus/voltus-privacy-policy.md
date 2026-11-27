---
api_specs:
- filename: voltus-dispatches-api-openapi.yml
  format: yaml
  label: Voltus Dispatches API
  slug: voltus-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-dispatches-api-openapi.yml
- filename: voltus-sites-api-openapi.yml
  format: yaml
  label: Voltus Sites API
  slug: voltus-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-sites-api-openapi.yml
- filename: voltus-telemetry-api-openapi.yml
  format: yaml
  label: Voltus Telemetry API
  slug: voltus-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-telemetry-api-openapi.yml
- filename: voltus-webhooks-api-openapi.yml
  format: yaml
  label: Voltus Webhooks API
  slug: voltus-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltus/openapi/voltus-webhooks-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Voltus may collect your name, business email, and phone number.
  - category: financial
    text: your business’s bank account number and routing number, may be used by our third- party payment provider during the bank account verification process.
  - category: behavioral
    text: Internet or other electronic network activity information, including, but not limited to, browsing history, search history, and information regarding your interaction with an internet website application, or advertisement.
  - category: device
    text: Log Files & IP Addresses We may collect IP addresses to analyze trends, administer the site, identify problems accessing the site, and gather broad demographic information for aggregate use.
  - category: location
    text: Energy Demand Data Voltus receives energy demand data from its own network of meters (Voltlets), from your utility or grid operator, and potentially from third-party metering providers.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Demand response notifications and energy market updates
    text: This information is used for notifications during Demand Response dispatches and to send important energy market updates.
  - purpose: Bank account verification and payments
    text: to enable direct, automatic payments to your business for Demand Response performance.
  - purpose: Marketing communications
    text: Voltus uses email outreach to keep potential Customers and stakeholders informed of industry trends, product updates, upcoming events, Voltus news, and other select content.
  - purpose: Site analytics and administration
    text: We may collect IP addresses to analyze trends, administer the site, identify problems accessing the site, and gather broad demographic information for aggregate use.
  retention:
  - period: null
    scope: Personal Information
    text: We retain your Personal Information only as long as necessary for the Purposes described above or otherwise disclosed to you when you provide your personal information.
  rights:
  - right: Confirm processing
    text: The right to confirm whether we process your Personal Information;
  - right: Access or delete
    text: The right to request access to or delete certain Personal Information (subject to certain exceptions);
  - right: Correction
    text: The right to request correction of inaccuracies in your Personal Information;
  - right: Portability
    text: The right to request your Personal Information in a portable format; and
  - right: Limit or opt out
    text: The right to limit or opt out of certain forms of Personal Information processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will not sell, share, or rent Personal Information we may receive from you to any third party or use your e-mail address for unsolicited mail.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Voltus
provenance_date: '2026-11-10'
provider_name: Voltus
provider_slug: voltus
slug: voltus-privacy-policy
source_date: '2026-11-10'
source_filename: voltus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.voltus.co/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Voltus\naid: voltus\nurl: https://www.voltus.co/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Voltus may collect your name, business email, and phone number.\n- category: financial\n  text: your business’s bank account number and routing number, may be used by our third- party payment provider\n    during the bank account verification process.\n- category: behavioral\n  text: Internet or other electronic network activity information, including, but not limited to, browsing history,\n    search history, and information\
  \ regarding your interaction with an internet website application, or advertisement.\n- category: device\n  text: Log Files & IP Addresses We may collect IP addresses to analyze trends, administer the site, identify problems\n    accessing the site, and gather broad demographic information for aggregate use.\n- category: location\n  text: Energy Demand Data Voltus receives energy demand data from its own network of meters (Voltlets), from your\n    utility or grid operator, and potentially from third-party metering providers.\npurposes:\n- purpose: Demand response notifications and energy market updates\n  text: This information is used for notifications during Demand Response dispatches and to send important energy\n    market updates.\n- purpose: Bank account verification and payments\n  text: to enable direct, automatic payments to your business for Demand Response performance.\n- purpose: Marketing communications\n  text: Voltus uses email outreach to keep potential Customers and stakeholders\
  \ informed of industry trends, product\n    updates, upcoming events, Voltus news, and other select content.\n- purpose: Site analytics and administration\n  text: We may collect IP addresses to analyze trends, administer the site, identify problems accessing the site,\n    and gather broad demographic information for aggregate use.\nretention:\n- scope: Personal Information\n  period: null\n  text: We retain your Personal Information only as long as necessary for the Purposes described above or otherwise\n    disclosed to you when you provide your personal information.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Confirm processing\n  text: The right to confirm whether we process your Personal Information;\n- right: Access or delete\n  text: The right to request access to or delete certain Personal Information (subject to certain exceptions);\n- right:\
  \ Correction\n  text: The right to request correction of inaccuracies in your Personal Information;\n- right: Portability\n  text: The right to request your Personal Information in a portable format; and\n- right: Limit or opt out\n  text: The right to limit or opt out of certain forms of Personal Information processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell, share, or rent Personal Information we may receive from you to any third party or use\n    your e-mail address for unsolicited mail.\n"
source_yaml_url: https://artifacts.apis.io/voltus/privacy/voltus-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Voltus's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Electricity
- Demand Response
- Virtual Power Plant
- DER
- Grid
- Energy Markets
- Flexibility
- Energy Storage
- OpenADR
- Telemetry
---
