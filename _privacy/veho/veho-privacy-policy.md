---
api_specs:
- filename: veho-labels-api-openapi.yml
  format: yaml
  label: Veho Labels API
  slug: veho-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-labels-api-openapi.yml
- filename: veho-manifests-api-openapi.yml
  format: yaml
  label: Veho Manifests API
  slug: veho-manifests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-manifests-api-openapi.yml
- filename: veho-merchants-api-openapi.yml
  format: yaml
  label: Veho Merchants API
  slug: veho-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-merchants-api-openapi.yml
- filename: veho-orders-api-openapi.yml
  format: yaml
  label: Veho Orders API
  slug: veho-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-orders-api-openapi.yml
- filename: veho-packages-api-openapi.yml
  format: yaml
  label: Veho Packages API
  slug: veho-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-packages-api-openapi.yml
- filename: veho-quotes-api-openapi.yml
  format: yaml
  label: Veho Quotes API
  slug: veho-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-quotes-api-openapi.yml
- filename: veho-webhooks-api-openapi.yml
  format: yaml
  label: Veho Webhooks API
  slug: veho-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-webhooks-api-openapi.yml
- filename: veho-zips-api-openapi.yml
  format: yaml
  label: Veho Zips API
  slug: veho-zips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-zips-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact data , such as your first and last name, salutation, email address, shipping and delivery addresses, and phone number.
  - category: demographic
    text: Demographic data , such as your city, state, country of residence, postal code, and age.
  - category: professional
    text: Business data , such as company or employer name, job title, business email address, company or employer size, and business phone number.
  - category: identifying
    text: Account data , such as the username and password that you may set to establish an online account on the Service
  - category: location
    text: Precise location data when your device settings allow our mobile application to access your device’s location.
  - category: device
    text: Device data , such as your computer’s or mobile device’s operating system type and version, manufacturer and model, browser type
  - category: behavioral
    text: Online activity data , such as pages or screens you viewed, how long you spent on a page or screen
  - category: financial
    text: Financial information, such as payment information collected by our payment processors
  - category: health
    text: Health information, such as information associated with driving incidents of drivers
  deletion:
    route: Close your account request via privacy@shipveho.com; deletion requests under applicable law
    text: If you wish to request to close your account, please contact us at privacy@shipveho.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and business operations
    text: provide, operate and improve the Service and our business; establish and maintain your user account on the Service
  - purpose: Research and development
    text: We may use information about you for research and development purposes, including to analyze and improve the Service and our business by applying various data analytic techniques including but not limited to machine learning and artificial intelligence.
  - purpose: Marketing and advertising
    text: We, our vendors and our third-party advertising partners may collect and use information about you for marketing and advertising purposes
  - purpose: Compliance and protection
    text: comply with applicable laws, lawful requests, and legal process
  retention:
  - period: null
    scope: General personal information
    text: We generally retain information about you to fulfill the purposes for which we collected it, including for the purposes of satisfying any legal, accounting, or reporting requirements, to establish or defend legal claims, or for fraud prevention purposes.
  rights:
  - right: Access
    text: Provide you access to and/or a copy of certain personal information we hold about you.
  - right: Correct
    text: Correct or update personal information we hold about you.
  - right: Delete
    text: Delete certain personal information we have about you.
  - right: Opt out of profiling
    text: Opt you out of the processing of your personal information for purposes of profiling in furtherance of decisions that produce legal or similarly significant effects, if applicable.
  - right: Revoke consent
    text: Revoke your consent for the processing of your information.
  - right: Opt out of sales or targeted advertising
    text: You may also have the right to opt out of sales of your “personal information” or “personal data” (as defined in applicable law), or the processing of such information for targeted advertising.
  role:
    text: We are headquartered in the United States and may use vendors that operate in other countries.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Our use of third-party analytics services and online advertising services may result in the sharing of online identifiers (e.g., cookie data, IP addresses, device identifiers, and usage information) in a way that may be considered a “sale” under the CCPA.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Information about you may be transferred to the United States or other locations where privacy laws may not be as protective as those in your state, province, or country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Veho
provenance_date: '2026-11-10'
provider_name: Veho
provider_slug: veho
slug: veho-privacy-policy
source_date: '2026-11-10'
source_filename: veho-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.shipveho.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Veho\naid: veho\nurl: https://www.shipveho.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are headquartered in the United States and may use vendors that operate in other countries.\ndata_categories:\n- category: contact\n  text: Contact data , such as your first and last name, salutation, email address, shipping and delivery addresses,\n    and phone number.\n- category: demographic\n  text: Demographic data , such as your city, state, country of residence, postal code, and age.\n- category: professional\n  text: Business data , such as company or employer name, job title,\
  \ business email address, company or employer\n    size, and business phone number.\n- category: identifying\n  text: Account data , such as the username and password that you may set to establish an online account on the\n    Service\n- category: location\n  text: Precise location data when your device settings allow our mobile application to access your device’s location.\n- category: device\n  text: Device data , such as your computer’s or mobile device’s operating system type and version, manufacturer\n    and model, browser type\n- category: behavioral\n  text: Online activity data , such as pages or screens you viewed, how long you spent on a page or screen\n- category: financial\n  text: Financial information, such as payment information collected by our payment processors\n- category: health\n  text: Health information, such as information associated with driving incidents of drivers\npurposes:\n- purpose: Service delivery and business operations\n  text: provide, operate and improve\
  \ the Service and our business; establish and maintain your user account on the\n    Service\n- purpose: Research and development\n  text: We may use information about you for research and development purposes, including to analyze and improve\n    the Service and our business by applying various data analytic techniques including but not limited to machine\n    learning and artificial intelligence.\n- purpose: Marketing and advertising\n  text: We, our vendors and our third-party advertising partners may collect and use information about you for marketing\n    and advertising purposes\n- purpose: Compliance and protection\n  text: comply with applicable laws, lawful requests, and legal process\nretention:\n- scope: General personal information\n  period: null\n  text: We generally retain information about you to fulfill the purposes for which we collected it, including for\n    the purposes of satisfying any legal, accounting, or reporting requirements, to establish or defend legal claims,\n\
  \    or for fraud prevention purposes.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Information about you may be transferred to the United States or other locations where privacy laws may\n    not be as protective as those in your state, province, or country.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close your account request via privacy@shipveho.com; deletion requests under applicable law\n  text: If you wish to request to close your account, please contact us at privacy@shipveho.com.\nrights:\n- right: Access\n  text: Provide you access to and/or a copy of certain personal information we hold about you.\n- right: Correct\n  text: Correct or update personal information we hold about you.\n- right: Delete\n  text: Delete certain personal information we have about you.\n- right: Opt out of profiling\n  text: Opt you out of the processing of your personal information for purposes of profiling in furtherance\
  \ of decisions\n    that produce legal or similarly significant effects, if applicable.\n- right: Revoke consent\n  text: Revoke your consent for the processing of your information.\n- right: Opt out of sales or targeted advertising\n  text: You may also have the right to opt out of sales of your “personal information” or “personal data” (as defined\n    in applicable law), or the processing of such information for targeted advertising.\nsale_or_sharing:\n  stance: conditional\n  text: Our use of third-party analytics services and online advertising services may result in the sharing of online\n    identifiers (e.g., cookie data, IP addresses, device identifiers, and usage information) in a way that may be\n    considered a “sale” under the CCPA.\n"
source_yaml_url: https://artifacts.apis.io/veho/privacy/veho-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Veho's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Last Mile Delivery
- Package Tracking
- E-Commerce
- Webhook
- Delivery
---
