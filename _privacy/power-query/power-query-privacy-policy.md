---
api_specs:
- filename: power-query-items-api-openapi.yml
  format: yaml
  label: Power Query Items API
  slug: power-query-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-items-api-openapi.yml
- filename: power-query-background-jobs-api-openapi.yml
  format: yaml
  label: Power Query Background Jobs API
  slug: power-query-background-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-background-jobs-api-openapi.yml
- filename: power-query-query-execution-api-openapi.yml
  format: yaml
  label: Power Query Query Execution API
  slug: power-query-query-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/power-query/openapi/power-query-query-execution-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Name and contact details . Your first and last name, email address, mailing address, phone number, and other similar contact details.
  - category: location
    text: Location data . Data about your device’s location, which may be either precise (typically based on GPS, cell tower, or Wi-Fi hotspot location) or imprecise
  - category: biometric
    text: Biometric data . Unique data about you from specific technical processing related to your physical, physiological, or behavioral characteristics to verify or confirm your identity.
  - category: communication
    text: Content . Information in files and messages, emails, chats, calls, meetings, photos, documents, and other media you create or share using Microsoft products.
  - category: behavioral
    text: Searches and commands . Search queries and commands you provide in Microsoft products, such as interactions with a chat bot.
  deletion:
    route: privacy dashboard or privacy support request
    text: You can control your personal data that Microsoft has obtained and exercise your data protection rights by contacting Microsoft or using various tools we provide, such as the Microsoft privacy dashboard .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products
    text: Provide our products, which includes updating, securing, and troubleshooting, as well as providing support and making recommendations.
  - purpose: Improve and develop products including AI models
    text: Improve and develop our products. As part of our efforts to improve and develop our products, we may use your data to develop and train our AI models.
  - purpose: Advertising and marketing
    text: Advertise and market to you, which includes sending promotional communications, personalized advertising, and presenting relevant offers.
  - purpose: Legal compliance
    text: Legal compliance . We process data to comply with applicable laws.
  residency:
  - region: your region, the United States, and other jurisdictions
    text: Microsoft may store and process your personal data in your region, the United States, and any other jurisdiction where Microsoft or its affiliates, subsidiaries, or service providers operate facilities.
  retention:
  - period: null
    scope: general personal data
    text: Microsoft retains personal data for as long as necessary to provide the products and services you use and to fulfill the transactions you request.
  - period: 30 days
    scope: authenticated child data deletion requests
    text: We process authenticated deletion requests within 30 days of receipt.
  - period: 60 days
    scope: closed accounts
    text: After requesting account closure, the account is marked for deletion, but we will wait 60 days before permanently deleting the account in case you change your mind or need to access information.
  rights:
  - right: withdraw consent
    text: If Microsoft obtained your consent to use your personal data, you can withdraw that consent at any time.
  - right: access, erasure, and update
    text: You can request access to , erasure of , and updates to your personal data.
  - right: portability
    text: If you’d like to port your data elsewhere, you can use tools Microsoft provides to do so, or if none are available, you can contact Microsoft for assistance.
  - right: object or restrict
    text: You can also object to or restrict the use of your personal data by Microsoft.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Microsoft will turn off sharing your data with third parties for personalized ads and turn off the “Share my data with third parties for personalized ads” toggle if we receive a GPC signal from you when you visit our sites.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we implement legal safeguards-such as standard contractual clauses approved by the European Commission
  - mechanism: DPF
    text: Microsoft Corporation complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Power Query
provenance_date: '2026-11-10'
provider_name: Power Query
provider_slug: power-query
slug: power-query-privacy-policy
source_date: '2026-11-10'
source_filename: power-query-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.microsoft.com/en-us/privacy/privacystatement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Power Query\naid: power-query\nurl: https://www.microsoft.com/en-us/privacy/privacystatement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name and contact details . Your first and last name, email address, mailing address, phone number, and other\n    similar contact details.\n- category: location\n  text: Location data . Data about your device’s location, which may be either precise (typically based on GPS,\n    cell tower, or Wi-Fi hotspot location) or imprecise\n- category: biometric\n  text: Biometric data . Unique\
  \ data about you from specific technical processing related to your physical, physiological,\n    or behavioral characteristics to verify or confirm your identity.\n- category: communication\n  text: Content . Information in files and messages, emails, chats, calls, meetings, photos, documents, and other\n    media you create or share using Microsoft products.\n- category: behavioral\n  text: Searches and commands . Search queries and commands you provide in Microsoft products, such as interactions\n    with a chat bot.\npurposes:\n- purpose: Provide products\n  text: Provide our products, which includes updating, securing, and troubleshooting, as well as providing support\n    and making recommendations.\n- purpose: Improve and develop products including AI models\n  text: Improve and develop our products. As part of our efforts to improve and develop our products, we may use\n    your data to develop and train our AI models.\n- purpose: Advertising and marketing\n  text: Advertise and\
  \ market to you, which includes sending promotional communications, personalized advertising,\n    and presenting relevant offers.\n- purpose: Legal compliance\n  text: Legal compliance . We process data to comply with applicable laws.\nretention:\n- scope: general personal data\n  period: null\n  text: Microsoft retains personal data for as long as necessary to provide the products and services you use and\n    to fulfill the transactions you request.\n- scope: authenticated child data deletion requests\n  period: 30 days\n  text: We process authenticated deletion requests within 30 days of receipt.\n- scope: closed accounts\n  period: 60 days\n  text: After requesting account closure, the account is marked for deletion, but we will wait 60 days before permanently\n    deleting the account in case you change your mind or need to access information.\nresidency:\n- region: your region, the United States, and other jurisdictions\n  text: Microsoft may store and process your personal data\
  \ in your region, the United States, and any other jurisdiction\n    where Microsoft or its affiliates, subsidiaries, or service providers operate facilities.\ntransfers:\n- mechanism: SCC\n  text: we implement legal safeguards-such as standard contractual clauses approved by the European Commission\n- mechanism: DPF\n  text: Microsoft Corporation complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to\n    the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department\n    of Commerce.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy dashboard or privacy support request\n  text: You can control your personal data that Microsoft has obtained and exercise your data protection rights\n    by contacting Microsoft or using various tools we provide, such as the Microsoft privacy dashboard .\nrights:\n- right: withdraw consent\n  text: If Microsoft\
  \ obtained your consent to use your personal data, you can withdraw that consent at any time.\n- right: access, erasure, and update\n  text: You can request access to , erasure of , and updates to your personal data.\n- right: portability\n  text: If you’d like to port your data elsewhere, you can use tools Microsoft provides to do so, or if none are\n    available, you can contact Microsoft for assistance.\n- right: object or restrict\n  text: You can also object to or restrict the use of your personal data by Microsoft.\nsale_or_sharing:\n  stance: conditional\n  text: Microsoft will turn off sharing your data with third parties for personalized ads and turn off the “Share\n    my data with third parties for personalized ads” toggle if we receive a GPC signal from you when you visit our\n    sites.\n"
source_yaml_url: https://artifacts.apis.io/power-query/privacy/power-query-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Power Query's own page on 2026-11-10.
synthetic: false
tags:
- Business Intelligence
- Data Integration
- Data Transformation
- ETL
- Microsoft
- Microsoft Fabric
- Power BI
- Dataflows
- M Language
- Data Connectors
- Self-Service ETL
---
