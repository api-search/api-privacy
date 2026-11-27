---
api_specs:
- filename: extend-claims-management-api-openapi.yml
  format: yaml
  label: Extend Claims Management API
  slug: extend-claims-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-claims-management-api-openapi.yml
- filename: extend-contracts-api-openapi.yml
  format: yaml
  label: Extend Contracts API
  slug: extend-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-contracts-api-openapi.yml
- filename: extend-leads-api-openapi.yml
  format: yaml
  label: Extend Leads API
  slug: extend-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-leads-api-openapi.yml
- filename: extend-offers-api-openapi.yml
  format: yaml
  label: Extend Offers API
  slug: extend-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-offers-api-openapi.yml
- filename: extend-orders-api-openapi.yml
  format: yaml
  label: Extend Orders API
  slug: extend-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-orders-api-openapi.yml
- filename: extend-products-api-openapi.yml
  format: yaml
  label: Extend Products API
  slug: extend-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-products-api-openapi.yml
- filename: extend-refunds-api-openapi.yml
  format: yaml
  label: Extend Refunds API
  slug: extend-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-refunds-api-openapi.yml
- filename: extend-service-orders-api-openapi.yml
  format: yaml
  label: Extend Service Orders API
  slug: extend-service-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-service-orders-api-openapi.yml
- filename: extend-dynamic-return-policy-api-openapi.yml
  format: yaml
  label: Extend Dynamic Return Policy API
  slug: extend-dynamic-return-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-dynamic-return-policy-api-openapi.yml
- filename: extend-line-items-api-openapi.yml
  format: yaml
  label: Extend Line Items API
  slug: extend-line-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-line-items-api-openapi.yml
- filename: extend-shippingoffers-api-openapi.yml
  format: yaml
  label: Extend Shipping Offers API
  slug: extend-shippingoffers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-shippingoffers-api-openapi.yml
- filename: extend-webhooks-api-openapi.yml
  format: yaml
  label: Extend Webhooks API
  slug: extend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/extend/openapi/extend-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Government-issued IDs (e.g., driver’s license number or passport number) for identity verification and anti-fraud purposes
  - category: contact
    text: Contact information, such as name, email and postal address, and phone number
  - category: biometric
    text: Biometric information (collected by our service provider on our behalf) for identity verification and anti-fraud purposes
  - category: device
    text: The information we obtain in this manner may include the type of web browser you use, your device identification information, your IP address, the pages you view, and the time and duration of your visits to the Site.
  - category: behavioral
    text: Internet and other electronic network activity information, including, but not limited to, browsing history, search history, and information regarding your interaction with websites, applications or advertisements
  - category: professional
    text: 'Commercial Information: commercial information, including records of personal property, products or services purchased, obtained, or considered'
  deletion:
    route: Email privacy@extend.com
    text: You have the right to request that we delete certain personal information we have collected from you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and manage relationship
    text: Provide our Services, and manage our relationship with you
  - purpose: Process and fulfill claims and orders
    text: Process and fulfill claims and orders in connection with our Services
  - purpose: Fraud prevention and security
    text: Protect against, identify and prevent fraud and other criminal activity, claims and other liabilities
  - purpose: Interest-based advertising
    text: Through such ad services, we can tailor our messaging to users considering demographic data, users’ inferred interests and browsing context.
  - purpose: Improve services and analytics
    text: Operate, evaluate and improve our Services (including managing the Services, developing new services and offerings; enhancing and improving our Services; managing our communications; analyzing our Services; performing data analytics
  retention:
  - period: null
    scope: Personal information generally
    text: We will retain your personal information for the period reasonably necessary to achieve the purposes described in our Privacy Policy and this Statement
  rights:
  - right: Access
    text: You have the right to request, twice in a 12-month period, that we disclose to you the personal information we have collected
  - right: Correction
    text: You have the right to request that we correct the personal information we maintain about you, if that information is inaccurate.
  - right: Deletion
    text: You have the right to request that we delete certain personal information we have collected from you.
  - right: Opt-out of sale or sharing
    text: You have the right to opt-out of the sale of your personal information and the sharing of your personal information for cross-context behavioral advertising purposes.
  role:
    text: to the extent that we act as data controller. In many cases, we process personal information as a data processor (i.e., a service provider) to our merchant clients.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information to third parties in exchange for monetary consideration.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We, our affiliates and our service providers may transfer, access, store and otherwise process the personal information we collect about you outside of the jurisdiction in which you are located
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Extend
provenance_date: '2026-11-09'
provider_name: Extend
provider_slug: extend
slug: extend-privacy-policy
source_date: '2026-11-09'
source_filename: extend-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.extend.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Extend\naid: extend\nurl: https://www.extend.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: to the extent that we act as data controller. In many cases, we process personal information as a data processor\n    (i.e., a service provider) to our merchant clients.\ndata_categories:\n- category: identifying\n  text: Government-issued IDs (e.g., driver’s license number or passport number) for identity verification and anti-fraud\n    purposes\n- category: contact\n  text: Contact information, such as name, email and postal address, and phone number\n- category: biometric\n\
  \  text: Biometric information (collected by our service provider on our behalf) for identity verification and anti-fraud\n    purposes\n- category: device\n  text: The information we obtain in this manner may include the type of web browser you use, your device identification\n    information, your IP address, the pages you view, and the time and duration of your visits to the Site.\n- category: behavioral\n  text: Internet and other electronic network activity information, including, but not limited to, browsing history,\n    search history, and information regarding your interaction with websites, applications or advertisements\n- category: professional\n  text: 'Commercial Information: commercial information, including records of personal property, products or services\n    purchased, obtained, or considered'\npurposes:\n- purpose: Provide services and manage relationship\n  text: Provide our Services, and manage our relationship with you\n- purpose: Process and fulfill claims and\
  \ orders\n  text: Process and fulfill claims and orders in connection with our Services\n- purpose: Fraud prevention and security\n  text: Protect against, identify and prevent fraud and other criminal activity, claims and other liabilities\n- purpose: Interest-based advertising\n  text: Through such ad services, we can tailor our messaging to users considering demographic data, users’ inferred\n    interests and browsing context.\n- purpose: Improve services and analytics\n  text: Operate, evaluate and improve our Services (including managing the Services, developing new services and\n    offerings; enhancing and improving our Services; managing our communications; analyzing our Services; performing\n    data analytics\nretention:\n- scope: Personal information generally\n  period: null\n  text: We will retain your personal information for the period reasonably necessary to achieve the purposes described\n    in our Privacy Policy and this Statement\nresidency: []\ntransfers:\n- mechanism:\
  \ other\n  text: We, our affiliates and our service providers may transfer, access, store and otherwise process the personal\n    information we collect about you outside of the jurisdiction in which you are located\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@extend.com\n  text: You have the right to request that we delete certain personal information we have collected from you.\nrights:\n- right: Access\n  text: You have the right to request, twice in a 12-month period, that we disclose to you the personal information\n    we have collected\n- right: Correction\n  text: You have the right to request that we correct the personal information we maintain about you, if that information\n    is inaccurate.\n- right: Deletion\n  text: You have the right to request that we delete certain personal information we have collected from you.\n- right: Opt-out of sale or sharing\n  text: You have the right to opt-out\
  \ of the sale of your personal information and the sharing of your personal\n    information for cross-context behavioral advertising purposes.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information to third parties in exchange for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/extend/privacy/extend-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Extend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Product Protection
- Extended Warranty
- Shipping Protection
- E-Commerce
- Warranty
- Claims
- Contracts
- Retail
- Insurance
---
