---
api_specs:
- filename: replicate-accounts-api-openapi.yml
  format: yaml
  label: Replicate Accounts API
  slug: replicate-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-accounts-api-openapi.yml
- filename: replicate-cancel-api-openapi.yml
  format: yaml
  label: Replicate Cancel API
  slug: replicate-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-cancel-api-openapi.yml
- filename: replicate-collections-api-openapi.yml
  format: yaml
  label: Replicate Collections API
  slug: replicate-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-collections-api-openapi.yml
- filename: replicate-deployments-api-openapi.yml
  format: yaml
  label: Replicate Deployments API
  slug: replicate-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-deployments-api-openapi.yml
- filename: replicate-hardware-api-openapi.yml
  format: yaml
  label: Replicate Hardware API
  slug: replicate-hardware-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-hardware-api-openapi.yml
- filename: replicate-model-api-openapi.yml
  format: yaml
  label: Replicate Model API
  slug: replicate-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-model-api-openapi.yml
- filename: replicate-models-api-openapi.yml
  format: yaml
  label: Replicate Models API
  slug: replicate-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-models-api-openapi.yml
- filename: replicate-predictions-api-openapi.yml
  format: yaml
  label: Replicate Predictions API
  slug: replicate-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-predictions-api-openapi.yml
- filename: replicate-secrets-api-openapi.yml
  format: yaml
  label: Replicate Secrets API
  slug: replicate-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-secrets-api-openapi.yml
- filename: replicate-training-api-openapi.yml
  format: yaml
  label: Replicate Training API
  slug: replicate-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-training-api-openapi.yml
- filename: replicate-trainings-api-openapi.yml
  format: yaml
  label: Replicate Trainings API
  slug: replicate-trainings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicate/openapi/replicate-trainings-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: providing us with your name, work or personal email, phone number, company name, position title, website, social media links, and time zone
  - category: financial
    text: providing us with your credit card and billing information
  - category: device
    text: IP address, device information, date/time of visits, new or returning visits, products viewed, page response times, URL clickstreams
  - category: behavioral
    text: how long you stay on our pages, what you do on those pages
  - category: identifying
    text: your GitHub or other account ID
  - category: other
    text: Any training data you upload to our Services to train models
  deletion:
    route: Contact privacy@replicate.com
    text: Delete the personal information we maintain about you, unless such information is necessary for compliance with our legal or regulatory obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Services
    text: To provide our Services, including providing open-source code and models for you to build your AI products and generating production-ready APIs to deploy your AI products.
  - purpose: Customer support
    text: For customer support by responding to your issue reports, questions or feedback.
  - purpose: Improve and troubleshoot
    text: To improve or troubleshoot any issues with our Services.
  - purpose: Communications and marketing
    text: To communicate with you, such as sending you email or SMS updates about new features, products, and services.
  - purpose: Fraud and legal
    text: For other business and legal purposes, such as to detect and prevent fraud, to collect amounts owing to us, and to maintain business records.
  retention:
  - period: null
    scope: Customer personal information
    text: We generally retain customer personal information for as long as necessary to provide our Services.
  - period: null
    scope: Backups
    text: Residual copies of personal data may be stored in backup systems for a limited period as a security measure to protect against data loss.
  rights:
  - right: Access
    text: Access the personal information we maintain about you.
  - right: Delete
    text: Delete the personal information we maintain about you, unless such information is necessary for compliance with our legal or regulatory obligations.
  - right: Correct
    text: Correct inaccurate personal information we maintain about you.
  - right: Opt out of email marketing
    text: 'Email marketing: you may unsubscribe to our commercial email list by following the instructions provided in the email.'
  role:
    text: Replicate is designated as a ‘processor’ or ‘service provider’ when processing customer personal information.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Replicate does not ‘sell’ or ‘share’ personal information, as defined by any U.S. state privacy law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Replicate
provenance_date: '2026-11-10'
provider_name: Replicate
provider_slug: replicate
slug: replicate-privacy-policy
source_date: '2026-11-10'
source_filename: replicate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://replicate.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Replicate\naid: replicate\nurl: https://replicate.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Replicate is designated as a ‘processor’ or ‘service provider’ when processing customer personal information.\ndata_categories:\n- category: contact\n  text: providing us with your name, work or personal email, phone number, company name, position title, website,\n    social media links, and time zone\n- category: financial\n  text: providing us with your credit card and billing information\n- category: device\n  text: IP address, device information, date/time of visits, new or returning\
  \ visits, products viewed, page response\n    times, URL clickstreams\n- category: behavioral\n  text: how long you stay on our pages, what you do on those pages\n- category: identifying\n  text: your GitHub or other account ID\n- category: other\n  text: Any training data you upload to our Services to train models\npurposes:\n- purpose: Provide Services\n  text: To provide our Services, including providing open-source code and models for you to build your AI products\n    and generating production-ready APIs to deploy your AI products.\n- purpose: Customer support\n  text: For customer support by responding to your issue reports, questions or feedback.\n- purpose: Improve and troubleshoot\n  text: To improve or troubleshoot any issues with our Services.\n- purpose: Communications and marketing\n  text: To communicate with you, such as sending you email or SMS updates about new features, products, and services.\n- purpose: Fraud and legal\n  text: For other business and legal purposes,\
  \ such as to detect and prevent fraud, to collect amounts owing to\n    us, and to maintain business records.\nretention:\n- scope: Customer personal information\n  period: null\n  text: We generally retain customer personal information for as long as necessary to provide our Services.\n- scope: Backups\n  period: null\n  text: Residual copies of personal data may be stored in backup systems for a limited period as a security measure\n    to protect against data loss.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@replicate.com\n  text: Delete the personal information we maintain about you, unless such information is necessary for compliance\n    with our legal or regulatory obligations.\nrights:\n- right: Access\n  text: Access the personal information we maintain about you.\n- right: Delete\n  text: Delete the personal information we maintain about you, unless such information\
  \ is necessary for compliance\n    with our legal or regulatory obligations.\n- right: Correct\n  text: Correct inaccurate personal information we maintain about you.\n- right: Opt out of email marketing\n  text: 'Email marketing: you may unsubscribe to our commercial email list by following the instructions provided\n    in the email.'\nsale_or_sharing:\n  stance: prohibited\n  text: Replicate does not ‘sell’ or ‘share’ personal information, as defined by any U.S. state privacy law.\n"
source_yaml_url: https://artifacts.apis.io/replicate/privacy/replicate-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Replicate's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Image Generation
- Language Models
- Model Deployment
- Inference
---
