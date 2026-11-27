---
api_specs:
- filename: uplead-account-api-openapi.yml
  format: yaml
  label: UpLead Account API
  slug: uplead-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-account-api-openapi.yml
- filename: uplead-combined-api-openapi.yml
  format: yaml
  label: UpLead Combined API
  slug: uplead-combined-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-combined-api-openapi.yml
- filename: uplead-company-api-openapi.yml
  format: yaml
  label: UpLead Company API
  slug: uplead-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-company-api-openapi.yml
- filename: uplead-lists-api-openapi.yml
  format: yaml
  label: UpLead Lists API
  slug: uplead-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-lists-api-openapi.yml
- filename: uplead-person-api-openapi.yml
  format: yaml
  label: UpLead Person API
  slug: uplead-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-person-api-openapi.yml
- filename: uplead-prospector-api-openapi.yml
  format: yaml
  label: UpLead Prospector API
  slug: uplead-prospector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-prospector-api-openapi.yml
- filename: uplead-reference-api-openapi.yml
  format: yaml
  label: UpLead Reference API
  slug: uplead-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-reference-api-openapi.yml
- filename: uplead-search-api-openapi.yml
  format: yaml
  label: UpLead Search API
  slug: uplead-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-search-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and last name
  - category: contact
    text: Business e-mail address
  - category: device
    text: Device Information – information about the devices and software you use to access the Site
  - category: location
    text: Location Information – based on this Device and Usage Information – mainly IP address – we are also able to determine general location information (country, city).
  - category: professional
    text: Company Job Title Location (City) Photo Education Experience Public social media handles
  - category: behavioral
    text: Usage Information – information about your interactions with the Site, including access dates and times, device event information, log data, crash data, and cookie data.
  - category: financial
    text: Billing address
  deletion:
    route: Account deletion from the Profile menu; Business Profile Data deletion via the opt-out form
    text: If you are a Customer, you may delete your account information at any time by deleting your account from the Profile menu.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing, updating and maintaining the Platform
    text: In particular, we will use your data to ensure that the Site loads and works for you, to set-up an account
  - purpose: Processing transactions and invoices
    text: we will use your data to complete any purchases for the Services, set up billing and resolve any issues
  - purpose: Improving the Platform
    text: Improving the content and general administration of the Platform, including to perform system maintenance and upgrades
  - purpose: Detecting fraud and security breaches
    text: Detecting fraud, illegal activities or security breaches
  - purpose: Marketing and targeted advertising
    text: Interacting with individuals on social media via our social media accounts and marketing our Platform
  residency:
  - region: United States
    text: We are located in the United States, and the personal information that we collect is stored on servers located in the United States.
  retention:
  - period: null
    scope: Personal information generally
    text: We will retain personal information we collect from you where we have an ongoing legitimate business need to do so (for example, to comply with applicable legal, tax or accounting requirements).
  - period: null
    scope: Account deletion
    text: We may retain certain information about you as required by law or for legitimate business purposes after you delete your account.
  rights:
  - right: Access
    text: The right of access – your right to request a copy of the personal data we hold about you
  - right: Rectification
    text: The right to rectification – your right to request that we correct personal data about you if it is incomplete or inaccurate
  - right: Erasure
    text: The right to erasure (also known as the ‘right to be forgotten’)
  - right: Restrict processing
    text: The right to restrict processing
  - right: Data portability
    text: The right to data portability – your right to ask us for a copy of your personal data in a common format
  - right: Object
    text: The right to object – your right to object to us processing your personal data
  - right: Opt out of sale
    text: Opting-out of Sales of Personal Information
  role:
    text: Customers are considered independent controllers of Business Profile Data that they receive in connection with the Services.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We may sell your personal information within the scope of, and according to the defined meaning of, a “sale” under NRS 603A.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: entering into standard contractual clauses in connection with any onward transfers of personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UpLead
provenance_date: '2026-11-10'
provider_name: UpLead
provider_slug: uplead
slug: uplead-privacy-policy
source_date: '2026-11-10'
source_filename: uplead-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.uplead.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UpLead\naid: uplead\nurl: https://www.uplead.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Customers are considered independent controllers of Business Profile Data that they receive in connection\n    with the Services.\ndata_categories:\n- category: identifying\n  text: First and last name\n- category: contact\n  text: Business e-mail address\n- category: device\n  text: Device Information – information about the devices and software you use to access the Site\n- category: location\n  text: Location Information – based on this Device and Usage Information – mainly IP address\
  \ – we are also able\n    to determine general location information (country, city).\n- category: professional\n  text: Company Job Title Location (City) Photo Education Experience Public social media handles\n- category: behavioral\n  text: Usage Information – information about your interactions with the Site, including access dates and times,\n    device event information, log data, crash data, and cookie data.\n- category: financial\n  text: Billing address\npurposes:\n- purpose: Providing, updating and maintaining the Platform\n  text: In particular, we will use your data to ensure that the Site loads and works for you, to set-up an account\n- purpose: Processing transactions and invoices\n  text: we will use your data to complete any purchases for the Services, set up billing and resolve any issues\n- purpose: Improving the Platform\n  text: Improving the content and general administration of the Platform, including to perform system maintenance\n    and upgrades\n- purpose: Detecting\
  \ fraud and security breaches\n  text: Detecting fraud, illegal activities or security breaches\n- purpose: Marketing and targeted advertising\n  text: Interacting with individuals on social media via our social media accounts and marketing our Platform\nretention:\n- scope: Personal information generally\n  period: null\n  text: We will retain personal information we collect from you where we have an ongoing legitimate business need\n    to do so (for example, to comply with applicable legal, tax or accounting requirements).\n- scope: Account deletion\n  period: null\n  text: We may retain certain information about you as required by law or for legitimate business purposes after\n    you delete your account.\nresidency:\n- region: United States\n  text: We are located in the United States, and the personal information that we collect is stored on servers located\n    in the United States.\ntransfers:\n- mechanism: SCC\n  text: entering into standard contractual clauses in connection with\
  \ any onward transfers of personal information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion from the Profile menu; Business Profile Data deletion via the opt-out form\n  text: If you are a Customer, you may delete your account information at any time by deleting your account from\n    the Profile menu.\nrights:\n- right: Access\n  text: The right of access – your right to request a copy of the personal data we hold about you\n- right: Rectification\n  text: The right to rectification – your right to request that we correct personal data about you if it is incomplete\n    or inaccurate\n- right: Erasure\n  text: The right to erasure (also known as the ‘right to be forgotten’)\n- right: Restrict processing\n  text: The right to restrict processing\n- right: Data portability\n  text: The right to data portability – your right to ask us for a copy of your personal data in a common format\n- right: Object\n\
  \  text: The right to object – your right to object to us processing your personal data\n- right: Opt out of sale\n  text: Opting-out of Sales of Personal Information\nsale_or_sharing:\n  stance: conditional\n  text: We may sell your personal information within the scope of, and according to the defined meaning of, a “sale”\n    under NRS 603A.\n"
source_yaml_url: https://artifacts.apis.io/uplead/privacy/uplead-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from UpLead's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Lead Generation
- Contact Data
- Company Data
- Email Verification
- Data Enrichment
- Sales Intelligence
---
