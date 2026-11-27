---
api_specs:
- filename: fini-agents-api-openapi.yml
  format: yaml
  label: Fini Agents API
  slug: fini-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-agents-api-openapi.yml
- filename: fini-articles-api-openapi.yml
  format: yaml
  label: Fini Articles API
  slug: fini-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-articles-api-openapi.yml
- filename: fini-conversations-api-openapi.yml
  format: yaml
  label: Fini Conversations API
  slug: fini-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-conversations-api-openapi.yml
- filename: fini-knowledge-api-openapi.yml
  format: yaml
  label: Fini Knowledge API
  slug: fini-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-knowledge-api-openapi.yml
- filename: fini-knowledge-folders-api-openapi.yml
  format: yaml
  label: Fini Knowledge Folders API
  slug: fini-knowledge-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-knowledge-folders-api-openapi.yml
- filename: fini-prompts-api-openapi.yml
  format: yaml
  label: Fini Prompts API
  slug: fini-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-prompts-api-openapi.yml
- filename: fini-rules-api-openapi.yml
  format: yaml
  label: Fini Rules API
  slug: fini-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-rules-api-openapi.yml
- filename: fini-sources-api-openapi.yml
  format: yaml
  label: Fini Sources API
  slug: fini-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-sources-api-openapi.yml
- filename: fini-tags-api-openapi.yml
  format: yaml
  label: Fini Tags API
  slug: fini-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fini/openapi/fini-tags-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: First name and last name
  - category: contact
    text: Phone number
  - category: device
    text: your computer's Internet Protocol address (e.g. IP address), browser type, browser version
  - category: device
    text: your mobile device unique ID
  - category: behavioral
    text: the pages of our Service that you visit, the time and date of your visit, the time spent on those pages
  deletion:
    route: email
    text: If you wish to be informed what Personal Data we hold about you and if you want it to be removed from our systems, please email us at legal@usefini.com.
  dpa:
    available: true
    text: Our handling of Customer Data is governed by our Data Processing Addendum (DPA)
    url: null
  purposes:
  - purpose: provide, maintain, and secure website and Services
    text: provide, maintain, and secure our website and Services
  - purpose: create and administer customer accounts
    text: create and administer customer accounts, including billing, invoicing, and renewals
  - purpose: marketing communications
    text: send product updates, newsletters, and relevant marketing communications, which you can opt out of at any time via the unsubscribe link or by emailing legal@usefini.com
  - purpose: website analytics
    text: analyze website traffic and usage to improve our website and marketing
  - purpose: Customer Data processing
    text: we process Customer Data only for the purposes of providing the Services, including insights, reporting, analytics, and platform abuse, trust, and safety monitoring
  residency:
  - region: United States
    text: we transfer the data, including Personal Data, to United States and process it there
  retention:
  - period: 30 days
    scope: Customer Data
    text: deleted or returned within 30 days of termination, as set out in our DPA and Section 15 of our Terms of Service
  - period: null
    scope: Customer Data
    text: Customer Data is retained for the term of the agreement between Fini and the Customer
  - period: null
    scope: Website and account data
    text: We retain Personal Data only for as long as necessary for the purposes set out in this Privacy Policy, or as required to comply with legal obligations, resolve disputes, and enforce our agreements.
  rights:
  - right: access
    text: the right of access to the personal data we hold about you
  - right: rectification
    text: the right of rectification, where the data is inaccurate or incomplete
  - right: erasure
    text: the right to erasure (the right to be forgotten)
  - right: restrict processing
    text: the right to restrict processing
  - right: portability
    text: the right to data portability, in a structured, machine-readable, commonly used format
  - right: object
    text: the right to object to processing
  - right: withdraw consent
    text: the right to withdraw consent at any time where we rely on consent as the legal basis for processing
  - right: delete (CCPA)
    text: ask to delete your data and not to sell (share) it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share Customer Data, or personal data of website visitors, with any third party for that party's own marketing or commercial purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Fini Technologies Inc. will take all the steps reasonably necessary to ensure that your data is treated securely and in accordance with this Privacy Policy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fini
provenance_date: '2026-11-09'
provider_name: Fini
provider_slug: fini
slug: fini-privacy-policy
source_date: '2026-11-09'
source_filename: fini-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.usefini.com/security/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fini\naid: fini\nurl: https://www.usefini.com/security/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: First name and last name\n- category: contact\n  text: Phone number\n- category: device\n  text: your computer's Internet Protocol address (e.g. IP address), browser type, browser version\n- category: device\n  text: your mobile device unique ID\n- category: behavioral\n  text: the pages of our Service that you visit, the time and date of your visit, the time spent on those pages\n\
  purposes:\n- purpose: provide, maintain, and secure website and Services\n  text: provide, maintain, and secure our website and Services\n- purpose: create and administer customer accounts\n  text: create and administer customer accounts, including billing, invoicing, and renewals\n- purpose: marketing communications\n  text: send product updates, newsletters, and relevant marketing communications, which you can opt out of at any\n    time via the unsubscribe link or by emailing legal@usefini.com\n- purpose: website analytics\n  text: analyze website traffic and usage to improve our website and marketing\n- purpose: Customer Data processing\n  text: we process Customer Data only for the purposes of providing the Services, including insights, reporting,\n    analytics, and platform abuse, trust, and safety monitoring\nretention:\n- scope: Customer Data\n  period: 30 days\n  text: deleted or returned within 30 days of termination, as set out in our DPA and Section 15 of our Terms of\n  \
  \  Service\n- scope: Customer Data\n  period: null\n  text: Customer Data is retained for the term of the agreement between Fini and the Customer\n- scope: Website and account data\n  period: null\n  text: We retain Personal Data only for as long as necessary for the purposes set out in this Privacy Policy, or\n    as required to comply with legal obligations, resolve disputes, and enforce our agreements.\nresidency:\n- region: United States\n  text: we transfer the data, including Personal Data, to United States and process it there\ntransfers:\n- mechanism: other\n  text: Fini Technologies Inc. will take all the steps reasonably necessary to ensure that your data is treated\n    securely and in accordance with this Privacy Policy\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our handling of Customer Data is governed by our Data Processing Addendum (DPA)\ndeletion:\n  route: email\n  text: If you wish to be informed what Personal Data we hold\
  \ about you and if you want it to be removed from our\n    systems, please email us at legal@usefini.com.\nrights:\n- right: access\n  text: the right of access to the personal data we hold about you\n- right: rectification\n  text: the right of rectification, where the data is inaccurate or incomplete\n- right: erasure\n  text: the right to erasure (the right to be forgotten)\n- right: restrict processing\n  text: the right to restrict processing\n- right: portability\n  text: the right to data portability, in a structured, machine-readable, commonly used format\n- right: object\n  text: the right to object to processing\n- right: withdraw consent\n  text: the right to withdraw consent at any time where we rely on consent as the legal basis for processing\n- right: delete (CCPA)\n  text: ask to delete your data and not to sell (share) it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share Customer Data, or personal data of website visitors, with any third party for\
  \ that\n    party's own marketing or commercial purposes.\n"
source_yaml_url: https://artifacts.apis.io/fini/privacy/fini-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Fini's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Customer Service
- Customer Experience
- Knowledge Management
- Conversational AI
- Voice AI
- Help Desk
- Regulated Industries
---
