---
api_specs:
- filename: pointcheckout-branches-api-openapi.yml
  format: yaml
  label: PointCheckout Branches API
  slug: pointcheckout-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-branches-api-openapi.yml
- filename: pointcheckout-checkout-api-openapi.yml
  format: yaml
  label: PointCheckout Checkout API
  slug: pointcheckout-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-checkout-api-openapi.yml
- filename: pointcheckout-customer-subscription-api-openapi.yml
  format: yaml
  label: PointCheckout Customer subscription API
  slug: pointcheckout-customer-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-customer-subscription-api-openapi.yml
- filename: pointcheckout-webhooks-api-openapi.yml
  format: yaml
  label: PointCheckout Webhooks API
  slug: pointcheckout-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: user account information that you upload on our Sites, such as your picture, name, home address, email address and phone number
  - category: financial
    text: purchase and sale transaction information such as your credit card information and the details of your transaction
  - category: location
    text: your current geographic location
  - category: device
    text: your IP address; the date and time you accessed our services, the hardware, software or internet browser you used to access our Sites
  - category: behavioral
    text: information about which pages have been shown to you, site navigation details and links on our Sites that you follow
  - category: communication
    text: information contained in any email messages, questions, comments, complaints or requests you send us
  deletion:
    route: contact dpo@pointcheckout.com
    text: If you wish to cancel your account or request that we no longer use your information to provide you services, contact us at dpo@pointcheckout.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: profiling and analytics
    text: for profiling and analytical purposes, including marketing and website analytics
  - purpose: direct marketing
    text: communicating with you and providing you with information on and direct marketing of special offers or promotions
  - purpose: advertising
    text: to serve advertisements to you in various marketing channels, including but not limited to social media, search engines, mobile apps, and various websites including our own Sites
  - purpose: fraud prevention
    text: preventing and prosecuting fraud and/or credit risk
  - purpose: legal compliance
    text: meeting legal and regulatory requirements
  retention:
  - period: null
    scope: account and service data
    text: We will retain your personal information for as long as your account is active; your personal information is needed to provide you services; or it is necessary to meet legal, regulatory, insurance and audit requirements.
  rights:
  - right: access
    text: You are entitled to be informed or and have access to any of your personal information in our custody or control.
  - right: correction
    text: If you wish to change any of your personal information we have on file in our records
  - right: erasure
    text: You have the right to erasure of your personal data (“right to be forgotten”) in certain circumstances.
  - right: restriction
    text: You have the right, where there is a dispute in relation to the accuracy or basis of processing of your personal data, to request a restriction on further processing by us.
  - right: data portability
    text: You have the right to request that personal data that you have provided to us be returned to you, or be provided to another third party of your choice
  - right: opt out of direct marketing
    text: You may elect to “opt out” of direct marketing activities, including any profiling we may conduct for direct marketing purposes.
  - right: lodge complaint
    text: You have the right to lodge a complaint with a data protection supervisory authority in your country.
  role:
    text: PointCheckout, our Partners and our service providers are located in various jurisdictions
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your personal information may be stored, processed or transferred into or out of these countries
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PointCheckout
provenance_date: '2026-11-10'
provider_name: PointCheckout
provider_slug: pointcheckout
slug: pointcheckout-privacy-policy
source_date: '2026-11-10'
source_filename: pointcheckout-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.pointcheckout.com/en/legal/privacy/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PointCheckout\naid: pointcheckout\nurl: https://www.pointcheckout.com/en/legal/privacy/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: PointCheckout, our Partners and our service providers are located in various jurisdictions\ndata_categories:\n- category: identifying\n  text: user account information that you upload on our Sites, such as your picture, name, home address, email address\n    and phone number\n- category: financial\n  text: purchase and sale transaction information such as your credit card information and the details of your transaction\n- category: location\n\
  \  text: your current geographic location\n- category: device\n  text: your IP address; the date and time you accessed our services, the hardware, software or internet browser\n    you used to access our Sites\n- category: behavioral\n  text: information about which pages have been shown to you, site navigation details and links on our Sites that\n    you follow\n- category: communication\n  text: information contained in any email messages, questions, comments, complaints or requests you send us\npurposes:\n- purpose: profiling and analytics\n  text: for profiling and analytical purposes, including marketing and website analytics\n- purpose: direct marketing\n  text: communicating with you and providing you with information on and direct marketing of special offers or promotions\n- purpose: advertising\n  text: to serve advertisements to you in various marketing channels, including but not limited to social media,\n    search engines, mobile apps, and various websites including our own\
  \ Sites\n- purpose: fraud prevention\n  text: preventing and prosecuting fraud and/or credit risk\n- purpose: legal compliance\n  text: meeting legal and regulatory requirements\nretention:\n- scope: account and service data\n  period: null\n  text: We will retain your personal information for as long as your account is active; your personal information\n    is needed to provide you services; or it is necessary to meet legal, regulatory, insurance and audit requirements.\nresidency: []\ntransfers:\n- mechanism: other\n  text: your personal information may be stored, processed or transferred into or out of these countries\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact dpo@pointcheckout.com\n  text: If you wish to cancel your account or request that we no longer use your information to provide you services,\n    contact us at dpo@pointcheckout.com\nrights:\n- right: access\n  text: You are entitled to be informed\
  \ or and have access to any of your personal information in our custody or\n    control.\n- right: correction\n  text: If you wish to change any of your personal information we have on file in our records\n- right: erasure\n  text: You have the right to erasure of your personal data (“right to be forgotten”) in certain circumstances.\n- right: restriction\n  text: You have the right, where there is a dispute in relation to the accuracy or basis of processing of your\n    personal data, to request a restriction on further processing by us.\n- right: data portability\n  text: You have the right to request that personal data that you have provided to us be returned to you, or be\n    provided to another third party of your choice\n- right: opt out of direct marketing\n  text: You may elect to “opt out” of direct marketing activities, including any profiling we may conduct for direct\n    marketing purposes.\n- right: lodge complaint\n  text: You have the right to lodge a complaint with a\
  \ data protection supervisory authority in your country.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pointcheckout/privacy/pointcheckout-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from PointCheckout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Checkout
- Subscription
- Rewards
- Loyalty
- Webhook
- MENA
- E-Commerce
---
