---
api_specs:
- filename: ambitioninc-account-api-openapi.yml
  format: yaml
  label: Ambitioninc Account API
  slug: ambitioninc-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambitioninc/openapi/ambitioninc-account-api-openapi.yml
- filename: ambitioninc-data-api-openapi.yml
  format: yaml
  label: Ambitioninc Data API
  slug: ambitioninc-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambitioninc/openapi/ambitioninc-data-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you enter your first and last name, email address, and password to create an account
  - category: contact
    text: This information may include your first and last name, company name, job title, email address, phone number.
  - category: financial
    text: When you enter information using your account, including but not limited to personal details, company name, and billing information.
  - category: device
    text: the operating system (“OS”) running on your device, internet protocol address (“IP Address”) (which may be used to obtain your geolocation), access times, browser type, language settings of the OS
  - category: behavioral
    text: We also collect information about how you use Ambition’s Site and Application, including the elements you have interacted with, metadata and other details about these elements, clicks, change states and other user actions.
  deletion:
    route: Email request to compliance@ambition.com or account deletion request
    text: Our Customers can view, edit, or delete their personal information at any time.
  dpa:
    available: null
    text: provided that such third parties have entered into an applicable data processing agreement or provide at least the same level of privacy protection.
    url: null
  purposes:
  - purpose: Provide and improve services
    text: we use the information we collect primarily to provide, maintain, protect, and improve our current products and to develop new ones.
  - purpose: Marketing communications
    text: Communicate with you about promotions, upcoming events and news about products and services offered by Ambition and our selected partners, and for other marketing purposes of Ambition
  - purpose: Customer End User Data processing
    text: We process the Customer End User Data only according to the instructions of Customers
  retention:
  - period: null
    scope: Customer account personal information
    text: Ambition retains your personal information while you are a Customer and will delete your personal information upon request.
  - period: null
    scope: Customer End User Data
    text: Ambition only retains the Customer End User Data we process on behalf of our Customers for as long as necessary to provide the Application to our Customers or as required to comply with legal obligations, resolve disputes, and enforce any agreement.
  rights:
  - right: Access
    text: Customers may also send requests for access to your personal information by emailing compliance@ambition.com.
  - right: Delete
    text: Ambition will respond to any request to delete Customer personal information.
  - right: Opt out of marketing emails
    text: You may opt out of receiving promotional or marketing emails from Ambition by following the instructions in those emails.
  role:
    text: With respect to Ambition’s Customers, we are a data processor.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: If you would like to see the list of third parties with whom Ambition currently shares your information, you may request a copy of the list by emailing us at compliance@ambition.com
    url: null
  transfers:
  - mechanism: other
    text: Ambition participates in the EU-U.S. Privacy Shield Framework as set forth by the U.S. Department of Commerce regarding the collection, use, and retention of personal information transferred from the European Union (EU) to the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ambitioninc
provenance_date: '2026-11-09'
provider_name: Ambitioninc
provider_slug: ambitioninc
slug: ambitioninc-privacy-policy
source_date: '2026-11-09'
source_filename: ambitioninc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ambition.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ambitioninc\naid: ambitioninc\nurl: https://ambition.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: With respect to Ambition’s Customers, we are a data processor.\ndata_categories:\n- category: identifying\n  text: When you enter your first and last name, email address, and password to create an account\n- category: contact\n  text: This information may include your first and last name, company name, job title, email address, phone number.\n- category: financial\n  text: When you enter information using your account, including but not limited to personal details, company name,\n    and\
  \ billing information.\n- category: device\n  text: the operating system (“OS”) running on your device, internet protocol address (“IP Address”) (which may\n    be used to obtain your geolocation), access times, browser type, language settings of the OS\n- category: behavioral\n  text: We also collect information about how you use Ambition’s Site and Application, including the elements you\n    have interacted with, metadata and other details about these elements, clicks, change states and other user\n    actions.\npurposes:\n- purpose: Provide and improve services\n  text: we use the information we collect primarily to provide, maintain, protect, and improve our current products\n    and to develop new ones.\n- purpose: Marketing communications\n  text: Communicate with you about promotions, upcoming events and news about products and services offered by Ambition\n    and our selected partners, and for other marketing purposes of Ambition\n- purpose: Customer End User Data processing\n\
  \  text: We process the Customer End User Data only according to the instructions of Customers\nretention:\n- scope: Customer account personal information\n  period: null\n  text: Ambition retains your personal information while you are a Customer and will delete your personal information\n    upon request.\n- scope: Customer End User Data\n  period: null\n  text: Ambition only retains the Customer End User Data we process on behalf of our Customers for as long as necessary\n    to provide the Application to our Customers or as required to comply with legal obligations, resolve disputes,\n    and enforce any agreement.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Ambition participates in the EU-U.S. Privacy Shield Framework as set forth by the U.S. Department of Commerce\n    regarding the collection, use, and retention of personal information transferred from the European Union (EU)\n    to the United States.\nsubprocessors:\n  url: null\n  text: If you would like to see the\
  \ list of third parties with whom Ambition currently shares your information,\n    you may request a copy of the list by emailing us at compliance@ambition.com\ndpa:\n  available: null\n  url: null\n  text: provided that such third parties have entered into an applicable data processing agreement or provide at\n    least the same level of privacy protection.\ndeletion:\n  route: Email request to compliance@ambition.com or account deletion request\n  text: Our Customers can view, edit, or delete their personal information at any time.\nrights:\n- right: Access\n  text: Customers may also send requests for access to your personal information by emailing compliance@ambition.com.\n- right: Delete\n  text: Ambition will respond to any request to delete Customer personal information.\n- right: Opt out of marketing emails\n  text: You may opt out of receiving promotional or marketing emails from Ambition by following the instructions\n    in those emails.\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambitioninc/privacy/ambitioninc-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 18 quoted statements, read from Ambitioninc's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Revenue Operations
- Sales Enablement
- Artificial Intelligence
- Platform
---
