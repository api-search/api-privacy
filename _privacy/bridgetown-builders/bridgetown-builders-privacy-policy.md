---
api_specs:
- filename: bridgetown-builders-core-openapi-generated.yml
  format: yaml
  label: Bridge Town core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bridgetown-builders/openapi/_ae-authored/bridgetown-builders-core-openapi-generated.yml
- filename: bridgetown-builders-getting-started-openapi-generated.yml
  format: yaml
  label: Bridge Town getting started API
  slug: getting-started-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bridgetown-builders/openapi/_ae-authored/bridgetown-builders-getting-started-openapi-generated.yml
- filename: bridgetown-builders-guides-openapi-generated.yml
  format: yaml
  label: Bridge Town guides API
  slug: guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bridgetown-builders/openapi/_ae-authored/bridgetown-builders-guides-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, and profile picture as provided via Auth0 or your OAuth provider (Google)
  - category: contact
    text: Billing contact details, payment method (card details handled by Stripe directly)
  - category: financial
    text: Financial models and plans you create or import, including any data you upload (CSV, spreadsheets, etc.).
  - category: behavioral
    text: Pages visited and features used within the platform.
  - category: device
    text: Error logs and performance metrics.
  deletion:
    route: Request deletion of account via contact email or account settings
    text: 'Deletion : Request deletion of your account and associated personal data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: We process it solely to provide the Service.
  - purpose: Improve the Service via analytics
    text: We collect anonymised usage data to improve the Service using PostHog and Google Analytics
  retention:
  - period: 90 days after account closure
    scope: Account data
    text: Retained for the duration of your subscription and for 90 days after account closure (to allow recovery).
  - period: within 30 days of account closure
    scope: Financial model data
    text: 'Financial model data : Deleted within 30 days of account closure upon request.'
  - period: up to 2 years
    scope: Usage analytics
    text: 'Usage analytics : Retained in aggregated, anonymised form for up to 2 years.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records : Retained for 7 years as required by law.'
  rights:
  - right: Access
    text: 'Access : Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction : Request that inaccurate data be corrected.'
  - right: Deletion
    text: 'Deletion : Request deletion of your account and associated personal data.'
  - right: Data export
    text: 'Data export : Export your financial models and data in standard formats (CSV, JSON, versioned model archive) via the account settings page.'
  - right: Objection
    text: 'Objection : Object to certain processing activities.'
  role:
    text: Knightian Labs, LLC (“we”, “us”, or “our”) is the data controller for the Bridge Town platform and website
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: For a complete list of third-party services and subprocessors, see our Subprocessors page.
    url: https://www.bridgetown.builders/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bridge Town
provenance_date: '2026-11-09'
provider_name: Bridge Town
provider_slug: bridgetown-builders
slug: bridgetown-builders-privacy-policy
source_date: '2026-11-09'
source_filename: bridgetown-builders-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bridgetown.builders/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bridge Town\naid: bridgetown-builders\nurl: https://www.bridgetown.builders/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Knightian Labs, LLC (“we”, “us”, or “our”) is the data controller for the Bridge Town platform and website\ndata_categories:\n- category: identifying\n  text: your name, email address, and profile picture as provided via Auth0 or your OAuth provider (Google)\n- category: contact\n  text: Billing contact details, payment method (card details handled by Stripe directly)\n- category: financial\n  text: Financial models and plans you create or import, including any\
  \ data you upload (CSV, spreadsheets, etc.).\n- category: behavioral\n  text: Pages visited and features used within the platform.\n- category: device\n  text: Error logs and performance metrics.\npurposes:\n- purpose: Provide the Service\n  text: We process it solely to provide the Service.\n- purpose: Improve the Service via analytics\n  text: We collect anonymised usage data to improve the Service using PostHog and Google Analytics\nretention:\n- scope: Account data\n  period: 90 days after account closure\n  text: Retained for the duration of your subscription and for 90 days after account closure (to allow recovery).\n- scope: Financial model data\n  period: within 30 days of account closure\n  text: 'Financial model data : Deleted within 30 days of account closure upon request.'\n- scope: Usage analytics\n  period: up to 2 years\n  text: 'Usage analytics : Retained in aggregated, anonymised form for up to 2 years.'\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records\
  \ : Retained for 7 years as required by law.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: https://www.bridgetown.builders/subprocessors\n  text: For a complete list of third-party services and subprocessors, see our Subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of account via contact email or account settings\n  text: 'Deletion : Request deletion of your account and associated personal data.'\nrights:\n- right: Access\n  text: 'Access : Request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction : Request that inaccurate data be corrected.'\n- right: Deletion\n  text: 'Deletion : Request deletion of your account and associated personal data.'\n- right: Data export\n  text: 'Data export : Export your financial models and data in standard formats (CSV, JSON, versioned model archive)\n    via the account settings page.'\n- right: Objection\n  text: 'Objection : Object to certain\
  \ processing activities.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/bridgetown-builders/privacy/bridgetown-builders-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Bridge Town's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Artificial Intelligence
- FP&A
- Collaboration
- Version Control
- Company
---
