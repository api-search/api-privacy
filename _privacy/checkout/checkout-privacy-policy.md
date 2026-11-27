---
api_specs:
- filename: checkout-openapi-generated.yml
  format: yaml
  label: Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/_ae-authored/checkout-openapi-generated.yml
- filename: checkout-checkout-api-api-openapi.yml
  format: yaml
  label: Checkout Checkout API
  slug: checkout-checkout-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-checkout-api-api-openapi.yml
- filename: checkout-connect-api-openapi.yml
  format: yaml
  label: Checkout Connect API
  slug: checkout-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-connect-api-openapi.yml
- filename: checkout-payments-api-openapi.yml
  format: yaml
  label: Checkout Payments API
  slug: checkout-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-payments-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact information: your name, email address, phone number, personal or business postal address'
  - category: financial
    text: 'Cardholder information: your payment card details and billing address'
  - category: biometric
    text: 'Audio visual and, subject to your consent, biometric information: any videos, images, copies of relevant identity documents, face and voice recordings, from which biometric data such as a faceprint, or a voiceprint, can be extracted'
  - category: device
    text: 'Technical information: your IP address and device information (including the type of browser and operating system and version you use, unique device identifier, and mobile network information)'
  - category: identifying
    text: 'Verification information: proof of address, copy of a personal identification card or passport and other information as required to validate your identity'
  - category: behavioral
    text: your activity when using this website including information on your access times to this website (for example time zone settings and location), pages viewed, URLs clicked on
  deletion:
    route: Contact the DPO at dpo@checkout.com to request erasure
    text: This enables you to ask us to delete or remove your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process payments and provide services
    text: We use your contact, cardholder, transaction, technical and verification information to process payments and otherwise provide our services to you
  - purpose: Fraud detection and prevention
    text: We use your contact, cardholder, transaction, technical and verification information to detect and prevent fraudulent activity, financial crime and any other illegal or unauthorized use of Checkout services
  - purpose: Marketing communications to merchant representatives
    text: We use your contact information to send you marketing communications via email or text about relevant products and services
  - purpose: Identity verification
    text: We use your contact, and audio visual and biometric information to validate your identity (when using Checkout’s Identity Verification Services)
  - purpose: Website analytics
    text: We use your technical information to perform data analytics to improve and optimize our website, products, services, marketing, customer relationships and experiences as further described in our Cookies Policy
  retention:
  - period: 365 days
    scope: Biometric information
    text: We will delete your biometric information no later than 365 days after the date you provide it.
  - period: 96 hours
    scope: Hashed facial image
    text: stored for no more than 96 hours
  - period: null
    scope: General personal data
    text: Once the data is no longer required for these purposes, we securely erase it.
  rights:
  - right: Access
    text: Right to request access to your personal data
  - right: Correction
    text: Right to request correction of the personal data we hold about you
  - right: Erasure
    text: Right to request erasure of your personal data
  - right: Object to processing
    text: Right to object to processing of your personal data
  - right: Restriction
    text: Request restriction of processing of your personal data
  - right: Withdraw consent
    text: 'Withdrawal of consent: You can withdraw consent at any time where we are relying on consent to process your personal data'
  - right: Opt out of direct marketing
    text: Right to opt-out of direct marketing communications
  role:
    text: This notice applies where Checkout act as a data controller, but we may sometimes operate as a data processor for Merchant Customer data where we carry out instructions and process data on a Merchant’s behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Checkout.com does not sell personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the EU Standard Contractual Clauses (SCCs) or contractual clauses approved by the ICO (such as the UK Addendum to the EU SCCs) respectively
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Checkout
provenance_date: '2026-11-09'
provider_name: Checkout
provider_slug: checkout
slug: checkout-privacy-policy
source_date: '2026-11-09'
source_filename: checkout-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.checkout.com/legal/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Checkout\naid: checkout\nurl: https://www.checkout.com/legal/privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This notice applies where Checkout act as a data controller, but we may sometimes operate as a data processor\n    for Merchant Customer data where we carry out instructions and process data on a Merchant’s behalf.\ndata_categories:\n- category: contact\n  text: 'Contact information: your name, email address, phone number, personal or business postal address'\n- category: financial\n  text: 'Cardholder information: your payment card details and billing address'\n- category:\
  \ biometric\n  text: 'Audio visual and, subject to your consent, biometric information: any videos, images, copies of relevant\n    identity documents, face and voice recordings, from which biometric data such as a faceprint, or a voiceprint,\n    can be extracted'\n- category: device\n  text: 'Technical information: your IP address and device information (including the type of browser and operating\n    system and version you use, unique device identifier, and mobile network information)'\n- category: identifying\n  text: 'Verification information: proof of address, copy of a personal identification card or passport and other\n    information as required to validate your identity'\n- category: behavioral\n  text: your activity when using this website including information on your access times to this website (for example\n    time zone settings and location), pages viewed, URLs clicked on\npurposes:\n- purpose: Process payments and provide services\n  text: We use your contact, cardholder,\
  \ transaction, technical and verification information to process payments\n    and otherwise provide our services to you\n- purpose: Fraud detection and prevention\n  text: We use your contact, cardholder, transaction, technical and verification information to detect and prevent\n    fraudulent activity, financial crime and any other illegal or unauthorized use of Checkout services\n- purpose: Marketing communications to merchant representatives\n  text: We use your contact information to send you marketing communications via email or text about relevant products\n    and services\n- purpose: Identity verification\n  text: We use your contact, and audio visual and biometric information to validate your identity (when using Checkout’s\n    Identity Verification Services)\n- purpose: Website analytics\n  text: We use your technical information to perform data analytics to improve and optimize our website, products,\n    services, marketing, customer relationships and experiences as further\
  \ described in our Cookies Policy\nretention:\n- scope: Biometric information\n  period: 365 days\n  text: We will delete your biometric information no later than 365 days after the date you provide it.\n- scope: Hashed facial image\n  period: 96 hours\n  text: stored for no more than 96 hours\n- scope: General personal data\n  period: null\n  text: Once the data is no longer required for these purposes, we securely erase it.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on the EU Standard Contractual Clauses (SCCs) or contractual clauses approved by the ICO (such as\n    the UK Addendum to the EU SCCs) respectively\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the DPO at dpo@checkout.com to request erasure\n  text: This enables you to ask us to delete or remove your personal data.\nrights:\n- right: Access\n  text: Right to request access to your personal data\n- right: Correction\n  text: Right\
  \ to request correction of the personal data we hold about you\n- right: Erasure\n  text: Right to request erasure of your personal data\n- right: Object to processing\n  text: Right to object to processing of your personal data\n- right: Restriction\n  text: Request restriction of processing of your personal data\n- right: Withdraw consent\n  text: 'Withdrawal of consent: You can withdraw consent at any time where we are relying on consent to process\n    your personal data'\n- right: Opt out of direct marketing\n  text: Right to opt-out of direct marketing communications\nsale_or_sharing:\n  stance: prohibited\n  text: Checkout.com does not sell personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/checkout/privacy/checkout-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Checkout's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fintech
- E-Commerce
- Global
---
