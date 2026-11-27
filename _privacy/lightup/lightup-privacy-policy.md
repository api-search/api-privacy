---
api_specs:
- filename: lightup-api-credentials-api-openapi.yml
  format: yaml
  label: Lightup API Credentials API
  slug: lightup-api-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-api-credentials-api-openapi.yml
- filename: lightup-catalogs-api-openapi.yml
  format: yaml
  label: Lightup Catalogs API
  slug: lightup-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-catalogs-api-openapi.yml
- filename: lightup-dashboard-chart-api-openapi.yml
  format: yaml
  label: Lightup Dashboard chart API
  slug: lightup-dashboard-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-dashboard-chart-api-openapi.yml
- filename: lightup-datapoints-api-openapi.yml
  format: yaml
  label: Lightup Datapoints API
  slug: lightup-datapoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-datapoints-api-openapi.yml
- filename: lightup-health-check-api-openapi.yml
  format: yaml
  label: Lightup Health check API
  slug: lightup-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-health-check-api-openapi.yml
- filename: lightup-incidents-api-openapi.yml
  format: yaml
  label: Lightup Incidents API
  slug: lightup-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-incidents-api-openapi.yml
- filename: lightup-integrations-api-openapi.yml
  format: yaml
  label: Lightup Integrations API
  slug: lightup-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-integrations-api-openapi.yml
- filename: lightup-metrics-api-openapi.yml
  format: yaml
  label: Lightup Metrics API
  slug: lightup-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-metrics-api-openapi.yml
- filename: lightup-monitors-api-openapi.yml
  format: yaml
  label: Lightup Monitors API
  slug: lightup-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-monitors-api-openapi.yml
- filename: lightup-users-api-openapi.yml
  format: yaml
  label: Lightup Users API
  slug: lightup-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-users-api-openapi.yml
- filename: lightup-workspaces-api-openapi.yml
  format: yaml
  label: Lightup Workspaces API
  slug: lightup-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-workspaces-api-openapi.yml
- filename: lightup-data-sources-api-openapi.yml
  format: yaml
  label: Lightup Data Sources API
  slug: lightup-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-data-sources-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and last name
  - category: contact
    text: Business email address
  - category: professional
    text: Job title
  - category: device
    text: your IP address or device ID (or other persistent identifier that uniquely identifies your computer or mobile device on the Internet)
  - category: location
    text: we are also able to determine general location information (“Location Information”)
  - category: behavioral
    text: 'Usage Information: information about your interactions with the Platform'
  - category: communication
    text: When you communicate with us, we collect information, including what’s contained in those communications.
  deletion:
    route: Contact info@lightup.ai
    text: If you live in a jurisdiction that provides these rights to you and you wish to exercise any of the rights set out above, you may contact us at info@lightup.ai.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing access to and use of the Site and Services
    text: Providing you access to and use of the Site and Services
  - purpose: Detecting fraud and security breaches
    text: Detecting fraud, illegal activities, or security, breaches
  - purpose: Marketing and advertising
    text: Increasing the number of customers who use our Platform through marketing and advertising, including sending commercial communications
  residency:
  - region: United States and EEA
    text: Lightup is a United States Delaware corporation with primary storage of your information in the United States and the EEA.
  retention:
  - period: null
    scope: Personal information
    text: We retain personal information for as long as needed to provide our Services.
  rights:
  - right: Access
    text: The right of access – your right to request a copy of the personal data we hold about you
  - right: Rectification
    text: The right to rectification – your right to request that we correct personal data about you if it is incomplete or inaccurate
  - right: Erasure
    text: The right to erasure (also known as the ‘right to be forgotten’)
  - right: Restrict processing
    text: The right to restrict processing
  - right: Object
    text: The right to object
  - right: Opt out of sale or sharing
    text: The right to opt out from the sale or sharing of your personal data
  role:
    text: We may collect your personal data as a ‘data controller’ or a ‘business’ (and equivalent terms under other applicable laws) when we determine the means and purpose of processing
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell or share personal data as those terms are commonly understood.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lightup
provenance_date: '2026-11-09'
provider_name: Lightup
provider_slug: lightup
slug: lightup-privacy-policy
source_date: '2026-11-09'
source_filename: lightup-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lightup.ai/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lightup\naid: lightup\nurl: https://www.lightup.ai/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We may collect your personal data as a ‘data controller’ or a ‘business’ (and equivalent terms under other\n    applicable laws) when we determine the means and purpose of processing\ndata_categories:\n- category: identifying\n  text: First and last name\n- category: contact\n  text: Business email address\n- category: professional\n  text: Job title\n- category: device\n  text: your IP address or device ID (or other persistent identifier that uniquely identifies your computer or mobile\n\
  \    device on the Internet)\n- category: location\n  text: we are also able to determine general location information (“Location Information”)\n- category: behavioral\n  text: 'Usage Information: information about your interactions with the Platform'\n- category: communication\n  text: When you communicate with us, we collect information, including what’s contained in those communications.\npurposes:\n- purpose: Providing access to and use of the Site and Services\n  text: Providing you access to and use of the Site and Services\n- purpose: Detecting fraud and security breaches\n  text: Detecting fraud, illegal activities, or security, breaches\n- purpose: Marketing and advertising\n  text: Increasing the number of customers who use our Platform through marketing and advertising, including sending\n    commercial communications\nretention:\n- scope: Personal information\n  period: null\n  text: We retain personal information for as long as needed to provide our Services.\nresidency:\n\
  - region: United States and EEA\n  text: Lightup is a United States Delaware corporation with primary storage of your information in the United States\n    and the EEA.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact info@lightup.ai\n  text: If you live in a jurisdiction that provides these rights to you and you wish to exercise any of the rights\n    set out above, you may contact us at info@lightup.ai.\nrights:\n- right: Access\n  text: The right of access – your right to request a copy of the personal data we hold about you\n- right: Rectification\n  text: The right to rectification – your right to request that we correct personal data about you if it is incomplete\n    or inaccurate\n- right: Erasure\n  text: The right to erasure (also known as the ‘right to be forgotten’)\n- right: Restrict processing\n  text: The right to restrict processing\n- right: Object\n  text: The right to object\n-\
  \ right: Opt out of sale or sharing\n  text: The right to opt out from the sale or sharing of your personal data\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell or share personal data as those terms are commonly understood.\n"
source_yaml_url: https://artifacts.apis.io/lightup/privacy/lightup-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Lightup's own page on 2026-11-09.
synthetic: false
tags:
- Data Quality
- Data Observability
- Data Monitoring
- Anomaly Detection
- Data Engineering
- Analytics
- Incident Management
- Artificial Intelligence
- Data Governance
- Company
---
