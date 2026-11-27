---
api_specs:
- filename: shopback-account-linking-api-openapi.yml
  format: yaml
  label: ShopBack Account Linking API
  slug: shopback-account-linking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-account-linking-api-openapi.yml
- filename: shopback-authentication-api-openapi.yml
  format: yaml
  label: ShopBack Authentication API
  slug: shopback-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-authentication-api-openapi.yml
- filename: shopback-notification-api-openapi.yml
  format: yaml
  label: ShopBack Notification API
  slug: shopback-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-notification-api-openapi.yml
- filename: shopback-orders-api-openapi.yml
  format: yaml
  label: ShopBack Orders API
  slug: shopback-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-orders-api-openapi.yml
- filename: shopback-pre-auth-api-openapi.yml
  format: yaml
  label: ShopBack Pre Auth API
  slug: shopback-pre-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-pre-auth-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: full name, email address, physical address, telephone number, gender, date of birth
  - category: financial
    text: payment information (e.g., payment methods, bank account details, details of your account with a payment service provider such as PayPal, credit/debit card information, etc.)
  - category: location
    text: location information (including approximate location derived from IP address)
  - category: behavioral
    text: pages that you visit before, during and after using our services, information about the links you click
  - category: communication
    text: email address, email content, mobile number or contact preferences
  deletion:
    route: Request Deletion of your Personal Data via contacting us
    text: Request Deletion of your Personal Data. We may limit or deny your deletion request in certain cases, in accordance with exceptions specified in the applicable laws;
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We may use your information to fulfill our contract with you and provide you with our services
  - purpose: Marketing and advertising
    text: We may use Personal Data to tailor and provide you with content and advertisements
  - purpose: Fraud prevention and security
    text: Detecting security incidents, protecting against malicious, deceptive, fraudulent, or illegal activity, and prosecuting those responsible for that activity
  residency:
  - region: Singapore
    text: As the head office for regional operations of ShopBack group, Ecommerce Enablers Pte. Ltd. is located in Singapore, your Personal Data is transferred to Singapore as part of our contract with you for providing our services.
  retention:
  - period: null
    scope: Personal Data generally
    text: We store the Personal Data we collect as described in this Privacy Notice for as long as you use our services, as described in this Privacy Notice, or as necessary to fulfill the purpose(s) for which it was collected
  rights:
  - right: Access
    text: Confirm and Access your Personal Data
  - right: Portability
    text: Portability of Your Personal Data, including receiving an electronic copy of Personal Data that you have provided to us
  - right: Correction
    text: Request Correction of your Personal Data where it is inaccurate or incomplete
  - right: Deletion
    text: Request Deletion of your Personal Data.
  role:
    text: ShopBack Inc is the controller of the Personal Data we process under this Privacy Notice.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We endeavor to safeguard your information consistent with the requirements of applicable laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ShopBack
provenance_date: '2026-11-10'
provider_name: ShopBack
provider_slug: shopback
slug: shopback-privacy-policy
source_date: '2026-11-10'
source_filename: shopback-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.shopback.com/hc/en-us/articles/33321399347475-ShopBack-Privacy-Policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ShopBack\naid: shopback\nurl: https://support.shopback.com/hc/en-us/articles/33321399347475-ShopBack-Privacy-Policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ShopBack Inc is the controller of the Personal Data we process under this Privacy Notice.\ndata_categories:\n- category: identifying\n  text: full name, email address, physical address, telephone number, gender, date of birth\n- category: financial\n  text: payment information (e.g., payment methods, bank account details, details of your account with a payment\n    service provider such as PayPal, credit/debit card information, etc.)\n\
  - category: location\n  text: location information (including approximate location derived from IP address)\n- category: behavioral\n  text: pages that you visit before, during and after using our services, information about the links you click\n- category: communication\n  text: email address, email content, mobile number or contact preferences\npurposes:\n- purpose: Provide services\n  text: We may use your information to fulfill our contract with you and provide you with our services\n- purpose: Marketing and advertising\n  text: We may use Personal Data to tailor and provide you with content and advertisements\n- purpose: Fraud prevention and security\n  text: Detecting security incidents, protecting against malicious, deceptive, fraudulent, or illegal activity,\n    and prosecuting those responsible for that activity\nretention:\n- scope: Personal Data generally\n  period: null\n  text: We store the Personal Data we collect as described in this Privacy Notice for as long as you use\
  \ our services,\n    as described in this Privacy Notice, or as necessary to fulfill the purpose(s) for which it was collected\nresidency:\n- region: Singapore\n  text: As the head office for regional operations of ShopBack group, Ecommerce Enablers Pte. Ltd. is located in\n    Singapore, your Personal Data is transferred to Singapore as part of our contract with you for providing our\n    services.\ntransfers:\n- mechanism: other\n  text: We endeavor to safeguard your information consistent with the requirements of applicable laws.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request Deletion of your Personal Data via contacting us\n  text: Request Deletion of your Personal Data. We may limit or deny your deletion request in certain cases, in\n    accordance with exceptions specified in the applicable laws;\nrights:\n- right: Access\n  text: Confirm and Access your Personal Data\n- right: Portability\n  text: Portability\
  \ of Your Personal Data, including receiving an electronic copy of Personal Data that you have\n    provided to us\n- right: Correction\n  text: Request Correction of your Personal Data where it is inaccurate or incomplete\n- right: Deletion\n  text: Request Deletion of your Personal Data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shopback/privacy/shopback-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from ShopBack's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cashback
- Rewards
- Loyalty
- E-Commerce
- Buy Now Pay Later
- Point-of-Sale
- Checkout
- Singapore
---
