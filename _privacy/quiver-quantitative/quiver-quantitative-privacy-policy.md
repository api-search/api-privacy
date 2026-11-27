---
api_specs:
- filename: quiver-quantitative-beta-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Beta API
  slug: quiver-quantitative-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-beta-api-openapi.yml
- filename: quiver-quantitative-tier-1-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier 1 API
  slug: quiver-quantitative-tier-1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-1-api-openapi.yml
- filename: quiver-quantitative-tier-2-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier 2 API
  slug: quiver-quantitative-tier-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-2-api-openapi.yml
- filename: quiver-quantitative-tier-new-constructs-ratings-api-openapi.yml
  format: yaml
  label: Quiver Quantitative Tier New Constructs Ratings API
  slug: quiver-quantitative-tier-new-constructs-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quiver-quantitative/openapi/quiver-quantitative-tier-new-constructs-ratings-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: real name, username/alias, unique personal identifier, email address, credit or debit card number, and billing address country and zip code
  - category: device
    text: Information about your computer and internet connection, i.e., your IP address, operating system, and browser type.
  - category: behavioral
    text: browsing history, search history, traffic data, location data, logs, referring/exit pages
  - category: communication
    text: records and copies of your correspondence (including email addresses), if you contact us
  - category: financial
    text: You may be required to provide financial information before placing an order through our Website or Mobile App.
  deletion:
    route: email request to privacy contact
    text: You may send us an email at [email protected] to request access to, correct, or delete any Personal Data that you have provided to us. We cannot delete your Personal Data except by also deleting your user account.
  dpa:
    available: null
    text: Quiver Quantitative uses Data Protection Agreements between Quiver Quantitative and all other recipients of your Personal Data when legally required.
    url: null
  purposes:
  - purpose: provide and personalize website and content
    text: to provide and personalize our Website or Mobile App and their content to you
  - purpose: authenticate API and AI-assistant requests
    text: to authenticate API and AI-assistant requests and match them to your account and subscription level
  - purpose: enforce usage limits and security
    text: to enforce usage limits and protect the reliability and security of our services, including abuse and fraud prevention
  - purpose: product development and research
    text: for internal testing, research, analysis, and product development, including to develop and improve our Website
  - purpose: marketing own products
    text: We may also use your information to contact you about our own products and services that may be of interest to you.
  residency:
  - region: United States
    text: Your Personal Data may be processed and stored in the United States
  retention:
  - period: 30 days
    scope: API and AI-assistant request logs
    text: API and AI-assistant request logs are retained for 30 days for security and reliability purposes and are then deleted or de-identified.
  - period: minutes
    scope: authentication caches
    text: to operate short-lived technical caches (measured in minutes) that reduce repeated authentication lookups
  rights:
  - right: access
    text: to request access to, correct, or delete any Personal Data that you have provided to us
  - right: correction
    text: to request access to, correct, or delete any Personal Data that you have provided to us
  - right: opt out of promotional email
    text: you may click the unsubscribe link in the body of that email to be omitted from future email distributions
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not share, sell, or otherwise disclose your Personal Data for purposes other than those outlined in this Privacy Notice.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your Personal Data is transferred by Quiver Quantitative to another country only if it is required or permitted under applicable data protection law and provided that there are appropriate safeguards in place to protect your Personal Data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Quiver Quantitative
provenance_date: '2026-11-10'
provider_name: Quiver Quantitative
provider_slug: quiver-quantitative
slug: quiver-quantitative-privacy-policy
source_date: '2026-11-10'
source_filename: quiver-quantitative-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.quiverquant.com/privacypolicy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Quiver Quantitative\naid: quiver-quantitative\nurl: https://www.quiverquant.com/privacypolicy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: real name, username/alias, unique personal identifier, email address, credit or debit card number, and billing\n    address country and zip code\n- category: device\n  text: Information about your computer and internet connection, i.e., your IP address, operating system, and browser\n    type.\n- category: behavioral\n  text: browsing history, search history, traffic data, location data, logs, referring/exit\
  \ pages\n- category: communication\n  text: records and copies of your correspondence (including email addresses), if you contact us\n- category: financial\n  text: You may be required to provide financial information before placing an order through our Website or Mobile\n    App.\npurposes:\n- purpose: provide and personalize website and content\n  text: to provide and personalize our Website or Mobile App and their content to you\n- purpose: authenticate API and AI-assistant requests\n  text: to authenticate API and AI-assistant requests and match them to your account and subscription level\n- purpose: enforce usage limits and security\n  text: to enforce usage limits and protect the reliability and security of our services, including abuse and fraud\n    prevention\n- purpose: product development and research\n  text: for internal testing, research, analysis, and product development, including to develop and improve our\n    Website\n- purpose: marketing own products\n  text: We may\
  \ also use your information to contact you about our own products and services that may be of interest\n    to you.\nretention:\n- scope: API and AI-assistant request logs\n  period: 30 days\n  text: API and AI-assistant request logs are retained for 30 days for security and reliability purposes and are\n    then deleted or de-identified.\n- scope: authentication caches\n  period: minutes\n  text: to operate short-lived technical caches (measured in minutes) that reduce repeated authentication lookups\nresidency:\n- region: United States\n  text: Your Personal Data may be processed and stored in the United States\ntransfers:\n- mechanism: other\n  text: Your Personal Data is transferred by Quiver Quantitative to another country only if it is required or permitted\n    under applicable data protection law and provided that there are appropriate safeguards in place to protect\n    your Personal Data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text:\
  \ Quiver Quantitative uses Data Protection Agreements between Quiver Quantitative and all other recipients\n    of your Personal Data when legally required.\ndeletion:\n  route: email request to privacy contact\n  text: You may send us an email at [email protected] to request access to, correct, or delete any Personal Data\n    that you have provided to us. We cannot delete your Personal Data except by also deleting your user account.\nrights:\n- right: access\n  text: to request access to, correct, or delete any Personal Data that you have provided to us\n- right: correction\n  text: to request access to, correct, or delete any Personal Data that you have provided to us\n- right: opt out of promotional email\n  text: you may click the unsubscribe link in the body of that email to be omitted from future email distributions\nsale_or_sharing:\n  stance: conditional\n  text: We do not share, sell, or otherwise disclose your Personal Data for purposes other than those outlined in\n    this\
  \ Privacy Notice.\n"
source_yaml_url: https://artifacts.apis.io/quiver-quantitative/privacy/quiver-quantitative-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Quiver Quantitative's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Finance
- Politics
- Alternative Data
- Financial Data
- Investment Research
- Market Data
- Government Data
- Congressional Trading
---
