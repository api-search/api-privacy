---
api_specs:
- filename: centrapay-payment-requests-api-openapi.yml
  format: yaml
  label: Centrapay Payment Requests API
  slug: centrapay-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centrapay/openapi/centrapay-payment-requests-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact Information – name, email address, phone number
  - category: identifying
    text: Identify Verification Documentation - passport, license information or other applicable
  - category: financial
    text: Bank Account information – Account name, Bank account number
  - category: device
    text: Technical Data – IP address, browser type, pages visited (via cookies or analytics tools)
  - category: biometric
    text: Biometric Information – facial images or other physical or behavioural identifiers used to verify your identity or authenticate transactions
  - category: behavioral
    text: Metadata – from user interactions (session duration, device identifiers, etc.)
  deletion:
    route: Contact support email
    text: Requesting deletion of your data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to enquiries and support
    text: Respond to your enquiries and support requests
  - purpose: Merchant onboarding
    text: Enable merchant onboarding to use our app and services
  - purpose: Billing services
    text: Provide and manage billing services securely and efficiently
  - purpose: Identity verification with biometrics
    text: Verify your identity using biometric information, where required
  - purpose: Marketing communications
    text: Send marketing communications (where you've opted in)
  - purpose: Improve website and services
    text: Improve our website and services
  residency:
  - region: New Zealand
    text: When we transfer your information outside Centrapay, it may be to a company in New Zealand or overseas.
  retention:
  - period: 12 months
    scope: Contact form submissions
    text: 'Contact form submissions: retained for 12 months'
  - period: 12 months
    scope: Job applications
    text: 'Job applications: retained for 12 months unless you request deletion sooner'
  - period: seven years
    scope: Biometric information
    text: 'Biometric information: retained only to complete the verification and for compliance purposes, and then deleted securely after seven years.'
  rights:
  - right: Access
    text: Accessing the personal information we hold about you as a data controller, including biometric information
  - right: Correction
    text: Correcting inaccurate information, including biometric information
  - right: Deletion
    text: Requesting deletion of your data
  - right: Objection or restriction
    text: Objecting to or restricting processing of your data
  - right: Withdraw consent
    text: Withdrawing your consent, including consent to biometric collection
  role:
    text: Where we determine how your data is processed, we are the "data controller". Where we simply process your data on behalf of another data controller, we are the "data processor".
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, lease, or trade biometric information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Our contract with the company will require the company to protect your personal information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Centrapay
provenance_date: '2026-11-09'
provider_name: Centrapay
provider_slug: centrapay
slug: centrapay-privacy-policy
source_date: '2026-11-09'
source_filename: centrapay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.centrapay.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Centrapay\naid: centrapay\nurl: https://www.centrapay.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where we determine how your data is processed, we are the \"data controller\". Where we simply process your\n    data on behalf of another data controller, we are the \"data processor\".\ndata_categories:\n- category: contact\n  text: Contact Information – name, email address, phone number\n- category: identifying\n  text: Identify Verification Documentation - passport, license information or other applicable\n- category: financial\n  text: Bank Account information – Account\
  \ name, Bank account number\n- category: device\n  text: Technical Data – IP address, browser type, pages visited (via cookies or analytics tools)\n- category: biometric\n  text: Biometric Information – facial images or other physical or behavioural identifiers used to verify your identity\n    or authenticate transactions\n- category: behavioral\n  text: Metadata – from user interactions (session duration, device identifiers, etc.)\npurposes:\n- purpose: Respond to enquiries and support\n  text: Respond to your enquiries and support requests\n- purpose: Merchant onboarding\n  text: Enable merchant onboarding to use our app and services\n- purpose: Billing services\n  text: Provide and manage billing services securely and efficiently\n- purpose: Identity verification with biometrics\n  text: Verify your identity using biometric information, where required\n- purpose: Marketing communications\n  text: Send marketing communications (where you've opted in)\n- purpose: Improve website and\
  \ services\n  text: Improve our website and services\nretention:\n- scope: Contact form submissions\n  period: 12 months\n  text: 'Contact form submissions: retained for 12 months'\n- scope: Job applications\n  period: 12 months\n  text: 'Job applications: retained for 12 months unless you request deletion sooner'\n- scope: Biometric information\n  period: seven years\n  text: 'Biometric information: retained only to complete the verification and for compliance purposes, and then\n    deleted securely after seven years.'\nresidency:\n- region: New Zealand\n  text: When we transfer your information outside Centrapay, it may be to a company in New Zealand or overseas.\ntransfers:\n- mechanism: other\n  text: Our contract with the company will require the company to protect your personal information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support email\n  text: Requesting deletion of your data\nrights:\n\
  - right: Access\n  text: Accessing the personal information we hold about you as a data controller, including biometric information\n- right: Correction\n  text: Correcting inaccurate information, including biometric information\n- right: Deletion\n  text: Requesting deletion of your data\n- right: Objection or restriction\n  text: Objecting to or restricting processing of your data\n- right: Withdraw consent\n  text: Withdrawing your consent, including consent to biometric collection\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, lease, or trade biometric information.\n"
source_yaml_url: https://artifacts.apis.io/centrapay/privacy/centrapay-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Centrapay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Digital Wallet
- Open Banking
- QR Code Payments
- Loyalty
- Gift Cards
- Fintech
---
