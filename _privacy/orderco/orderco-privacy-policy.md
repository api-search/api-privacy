---
api_specs:
- filename: orderco-components-api-openapi.yml
  format: yaml
  label: Order.co Components API
  slug: orderco-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-components-api-openapi.yml
- filename: orderco-incidents-api-openapi.yml
  format: yaml
  label: Order.co Incidents API
  slug: orderco-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-incidents-api-openapi.yml
- filename: orderco-maintenance-api-openapi.yml
  format: yaml
  label: Order.co Maintenance API
  slug: orderco-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-maintenance-api-openapi.yml
- filename: orderco-status-api-openapi.yml
  format: yaml
  label: Order.co Status API
  slug: orderco-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderco/openapi/orderco-status-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Names; Email addresses; Personal or business mailing address; Phone number(s); Birth date; Government-issued identification number(s)
  - category: financial
    text: Credit card information (which you submit for invoice payment purposes and is collected by our third party payment gateway service providers (such as Stripe, Inc. )
  - category: location
    text: The city and state in which you are located (but not your precise geographic location)
  - category: behavioral
    text: The pages of our website that you viewed during a visit; What information, content or advertisements you view or interact with using the Services
  - category: device
    text: Unique identifiers that are not connected and cannot reasonably be connected to your identity
  deletion:
    route: Email request for access, correction or deletion
    text: You may request access to your Personal Information by sending an email to [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Services
    text: To assist us in providing, maintaining, and protecting the Services.
  - purpose: Process transactions
    text: To quickly process your transactions.
  - purpose: Communications and marketing
    text: Communicate with you, such as provide you with account- or transaction-related communications, or other newsletters
  - purpose: Research and product development
    text: Perform research and analysis aimed at improving our products and services and developing new products or services.
  residency:
  - region: United States
    text: Information gathered through the Services may be transferred, used, and stored in the United States or in other countries where our service providers or we are located.
  retention:
  - period: null
    scope: Personal Information
    text: We retain each category of your Personal Information for no longer than is reasonably necessary for one or more of the above lawful bases for processing
  rights:
  - right: Access
    text: 'Right of access: You have the right to access your Personal Information.'
  - right: Data portability
    text: 'Right to data portability: you have the right to request that we transfer all your Personal Information to another controller in a reasonably understandable format.'
  - right: Object
    text: 'Right to object: you may object to our processing of your Personal Information.'
  - right: Complain to authority
    text: You have the right to complain to a Data Protection Authority about our collection and use of your Personal Information.
  role:
    text: To the extent Order.co processes Personal Information on behalf of a customer, the customer is the controller, Order.co is the processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Personal Information.
  subprocessors:
    text: Refer to trust.order.co for a list of our Processors and their privacy policies.
    url: trust.order.co
  transfers:
  - mechanism: DPF
    text: Order.co complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Order.co
provenance_date: '2026-11-10'
provider_name: Order.co
provider_slug: orderco
slug: orderco-privacy-policy
source_date: '2026-11-10'
source_filename: orderco-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.order.co/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Order.co\naid: orderco\nurl: https://www.order.co/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: To the extent Order.co processes Personal Information on behalf of a customer, the customer is the controller,\n    Order.co is the processor\ndata_categories:\n- category: identifying\n  text: Names; Email addresses; Personal or business mailing address; Phone number(s); Birth date; Government-issued\n    identification number(s)\n- category: financial\n  text: Credit card information (which you submit for invoice payment purposes and is collected by our third party\n    payment gateway\
  \ service providers (such as Stripe, Inc. )\n- category: location\n  text: The city and state in which you are located (but not your precise geographic location)\n- category: behavioral\n  text: The pages of our website that you viewed during a visit; What information, content or advertisements you\n    view or interact with using the Services\n- category: device\n  text: Unique identifiers that are not connected and cannot reasonably be connected to your identity\npurposes:\n- purpose: Provide and maintain the Services\n  text: To assist us in providing, maintaining, and protecting the Services.\n- purpose: Process transactions\n  text: To quickly process your transactions.\n- purpose: Communications and marketing\n  text: Communicate with you, such as provide you with account- or transaction-related communications, or other\n    newsletters\n- purpose: Research and product development\n  text: Perform research and analysis aimed at improving our products and services and developing new\
  \ products or\n    services.\nretention:\n- scope: Personal Information\n  period: null\n  text: We retain each category of your Personal Information for no longer than is reasonably necessary for one\n    or more of the above lawful bases for processing\nresidency:\n- region: United States\n  text: Information gathered through the Services may be transferred, used, and stored in the United States or in\n    other countries where our service providers or we are located.\ntransfers:\n- mechanism: DPF\n  text: Order.co complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: trust.order.co\n  text: Refer to trust.order.co for a list of our Processors and their privacy policies.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request for access, correction or deletion\n  text:\
  \ You may request access to your Personal Information by sending an email to [email protected] .\nrights:\n- right: Access\n  text: 'Right of access: You have the right to access your Personal Information.'\n- right: Data portability\n  text: 'Right to data portability: you have the right to request that we transfer all your Personal Information\n    to another controller in a reasonably understandable format.'\n- right: Object\n  text: 'Right to object: you may object to our processing of your Personal Information.'\n- right: Complain to authority\n  text: You have the right to complain to a Data Protection Authority about our collection and use of your Personal\n    Information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Personal Information.\n"
source_yaml_url: https://artifacts.apis.io/orderco/privacy/orderco-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Order.co's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Spend Management
- Accounts Payable
- Purchasing
- Vendor Management
- Payments
- Virtual Cards
- Finance Automation
- United States
---
