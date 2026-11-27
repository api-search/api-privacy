---
api_specs:
- filename: nimble-activities-api-openapi.yml
  format: yaml
  label: Nimble Activities API
  slug: nimble-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-activities-api-openapi.yml
- filename: nimble-contacts-api-openapi.yml
  format: yaml
  label: Nimble Contacts API
  slug: nimble-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-api-openapi.yml
- filename: nimble-contacts-fields-api-openapi.yml
  format: yaml
  label: Nimble Contacts Fields API
  slug: nimble-contacts-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-fields-api-openapi.yml
- filename: nimble-contacts-pipelines-api-openapi.yml
  format: yaml
  label: Nimble Contacts Pipelines API
  slug: nimble-contacts-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-contacts-pipelines-api-openapi.yml
- filename: nimble-deals-api-openapi.yml
  format: yaml
  label: Nimble Deals API
  slug: nimble-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-api-openapi.yml
- filename: nimble-deals-fields-api-openapi.yml
  format: yaml
  label: Nimble Deals Fields API
  slug: nimble-deals-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-fields-api-openapi.yml
- filename: nimble-deals-pipelines-api-openapi.yml
  format: yaml
  label: Nimble Deals Pipelines API
  slug: nimble-deals-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-pipelines-api-openapi.yml
- filename: nimble-deals-pipelines-fields-api-openapi.yml
  format: yaml
  label: Nimble Deals Pipelines Fields API
  slug: nimble-deals-pipelines-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-deals-pipelines-fields-api-openapi.yml
- filename: nimble-leads-api-openapi.yml
  format: yaml
  label: Nimble Leads API
  slug: nimble-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-leads-api-openapi.yml
- filename: nimble-messages-api-openapi.yml
  format: yaml
  label: Nimble Messages API
  slug: nimble-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-messages-api-openapi.yml
- filename: nimble-tasks-api-openapi.yml
  format: yaml
  label: Nimble Tasks API
  slug: nimble-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-tasks-api-openapi.yml
- filename: nimble-users-api-openapi.yml
  format: yaml
  label: Nimble Users API
  slug: nimble-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nimble/openapi/nimble-users-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, username, password, email address, postal address and other contact information
  - category: contact
    text: You must provide contact information (such as name, email, telephone number).
  - category: financial
    text: we encrypt the transmission of that information using secure socket layer technology (SSL)
  - category: location
    text: Nimble may access your geographic location data at the time that you login to Nimble Services.
  - category: behavioral
    text: We use cookies for our shopping cart, to remember users’ settings (e.g. language preference), user analysis and for authentication.
  - category: demographic
    text: The requested information typically includes contact information and demographic information (such as zip code).
  deletion:
    route: Contact Customer Care or edit within account
    text: you may correct, update, delete your Personal Information by making the changes on the My Account section page within your Nimble account or by emailing our Customer Care at care@nimble.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: The use of information collected through our service shall be limited to the purpose of providing the service for which the Customer has engaged Nimble.
  - purpose: Marketing and promotional communications
    text: We use Personal Information to send you information about our company or our products or services, or promotional material from some of our Partners
  - purpose: Targeted advertising
    text: Our ad network partners use cookies and/or similar technologies to collect information about your activities on this and other web sites to provide you targeted advertising based upon your interests.
  retention:
  - period: 30 days
    scope: Customer-controlled personal data
    text: If the Customer requests Nimble to remove the data, we will respond to their request within 30 days.
  - period: null
    scope: Personal information
    text: We will retain your information for as long as your account is active or as needed to provide you services.
  rights:
  - right: Access
    text: Upon request Nimble will provide you with information about whether we hold, share, or process on behalf of a third party, any of your Personal Information.
  - right: Correction and deletion
    text: you may correct, update, delete your Personal Information by making the changes on the My Account section page within your Nimble account
  - right: Opt out of disclosures and materially different uses
    text: You have the right to opt out of (a) disclosures of your Personal Information to third parties not identified at the time of collection or subsequently authorized
  role:
    text: Nimble collects information under the direction of its Customers and has no direct relationship with the individuals whose personal data it processes.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Nimble complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nimble
provenance_date: '2026-11-10'
provider_name: Nimble
provider_slug: nimble
slug: nimble-privacy-policy
source_date: '2026-11-10'
source_filename: nimble-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.nimble.com/company/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nimble\naid: nimble\nurl: https://www.nimble.com/company/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Nimble collects information under the direction of its Customers and has no direct relationship with the\n    individuals whose personal data it processes.\ndata_categories:\n- category: identifying\n  text: name, username, password, email address, postal address and other contact information\n- category: contact\n  text: You must provide contact information (such as name, email, telephone number).\n- category: financial\n  text: we encrypt the transmission of that information using secure\
  \ socket layer technology (SSL)\n- category: location\n  text: Nimble may access your geographic location data at the time that you login to Nimble Services.\n- category: behavioral\n  text: We use cookies for our shopping cart, to remember users’ settings (e.g. language preference), user analysis\n    and for authentication.\n- category: demographic\n  text: The requested information typically includes contact information and demographic information (such as zip\n    code).\npurposes:\n- purpose: Providing the service\n  text: The use of information collected through our service shall be limited to the purpose of providing the service\n    for which the Customer has engaged Nimble.\n- purpose: Marketing and promotional communications\n  text: We use Personal Information to send you information about our company or our products or services, or promotional\n    material from some of our Partners\n- purpose: Targeted advertising\n  text: Our ad network partners use cookies and/or similar\
  \ technologies to collect information about your activities\n    on this and other web sites to provide you targeted advertising based upon your interests.\nretention:\n- scope: Customer-controlled personal data\n  period: 30 days\n  text: If the Customer requests Nimble to remove the data, we will respond to their request within 30 days.\n- scope: Personal information\n  period: null\n  text: We will retain your information for as long as your account is active or as needed to provide you services.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Nimble complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF,\n    and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Customer Care or edit within account\n  text: you may correct, update, delete your Personal Information\
  \ by making the changes on the My Account section\n    page within your Nimble account or by emailing our Customer Care at care@nimble.com\nrights:\n- right: Access\n  text: Upon request Nimble will provide you with information about whether we hold, share, or process on behalf\n    of a third party, any of your Personal Information.\n- right: Correction and deletion\n  text: you may correct, update, delete your Personal Information by making the changes on the My Account section\n    page within your Nimble account\n- right: Opt out of disclosures and materially different uses\n  text: You have the right to opt out of (a) disclosures of your Personal Information to third parties not identified\n    at the time of collection or subsequently authorized\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nimble/privacy/nimble-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Nimble's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Contact Management
- Relationship Management
- Marketing Automation
- Pipeline Management
- Small Business
- Email Marketing
- Sales Automation
- Lead Management
---
