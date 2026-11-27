---
api_specs:
- filename: franklin-whole-home-authentication-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Authentication API
  slug: franklin-whole-home-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-authentication-api-openapi.yml
- filename: franklin-whole-home-device-data-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Device Data API
  slug: franklin-whole-home-device-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-device-data-api-openapi.yml
- filename: franklin-whole-home-devices-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Devices API
  slug: franklin-whole-home-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-devices-api-openapi.yml
- filename: franklin-whole-home-grid-events-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Grid Events API
  slug: franklin-whole-home-grid-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-grid-events-api-openapi.yml
- filename: franklin-whole-home-groups-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Groups API
  slug: franklin-whole-home-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-groups-api-openapi.yml
- filename: franklin-whole-home-modification-records-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Modification Records API
  slug: franklin-whole-home-modification-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-modification-records-api-openapi.yml
- filename: franklin-whole-home-sites-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sites API
  slug: franklin-whole-home-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sites-api-openapi.yml
- filename: franklin-whole-home-sunrun-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun API
  slug: franklin-whole-home-sunrun-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-api-openapi.yml
- filename: franklin-whole-home-sunrun-sites-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun Sites API
  slug: franklin-whole-home-sunrun-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-sites-api-openapi.yml
- filename: franklin-whole-home-sunrun-system-setup-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun System Setup API
  slug: franklin-whole-home-sunrun-system-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-system-setup-api-openapi.yml
- filename: franklin-whole-home-system-settings-api-openapi.yml
  format: yaml
  label: Franklin Whole Home System Settings API
  slug: franklin-whole-home-system-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-system-settings-api-openapi.yml
- filename: franklin-whole-home-warnings-and-events-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Warnings and Events API
  slug: franklin-whole-home-warnings-and-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-warnings-and-events-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number, mailing address, account credentials.
  - category: location
    text: Installation address (precise), utility service territory, IP-derived location, mobile device GPS (if enabled).
  - category: behavioral
    text: Battery charge/discharge cycles, state of charge, energy consumption patterns, solar production data, grid import/export, power flow data, system alerts, battery health metrics, inverter performance.
  - category: financial
    text: Credit/debit card numbers, billing address, transaction history.
  - category: communication
    text: Emails, chat transcripts, phone call recordings (where permitted), support tickets, remote diagnostic session logs, service visit records.
  - category: device
    text: IP address, mobile advertising IDs (IDFA, AAID), MAC address, device type, operating system, browser type, app version.
  deletion:
    route: email request to dataprivacy@franklinwh.com
    text: 'Email: dataprivacy@franklinwh.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and support
    text: Account creation, order fulfillment, warranty registration, customer communications, and support.
  - purpose: marketing
    text: Sending marketing communications (with your consent or as permitted by law)
  residency:
  - region: United States
    text: 'United States: Primary data storage (AWS servers), customer support, engineering, and corporate operations'
  - region: Singapore
    text: 'Singapore: Regional operations, customer support, and business administration'
  retention:
  - period: Duration of account + 90 days
    scope: Account information
    text: 'Account Information: Duration of account + 90 days'
  - period: 7 years
    scope: Energy system data
    text: 'Energy System Data: 7 years (for warranty support and battery degradation tracking)'
  - period: Short-term (typically < 13 months)
    scope: Device and online identifiers
    text: 'Device/Online Identifiers: Short-term (typically < 13 months)'
  - period: null
    scope: Payment card data
    text: Payment card data is processed by third-party payment processors and not stored by FranklinWH.
  rights:
  - right: deletion
    text: 'Right to Deletion: Request deletion of your personal information (subject to exceptions)'
  - right: access
    text: 'Right to Know/Access: Request information about what personal information we collect and how we use it'
  - right: correction
    text: 'Right to Correction: Request correction of inaccurate personal information'
  - right: portability
    text: 'Right to Portability: Receive your personal information in a structured, machine-readable format'
  role:
    text: FranklinWH Energy Storage Inc. is the data controller responsible for your personal data.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We may share certain online identifiers with advertising partners through cookies, which may constitute "sharing" under California law.
  subprocessors:
    text: 'Cloud Infrastructure (AWS): Data hosting, storage, and processing'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission and/or UK ICO
  - mechanism: BCR
    text: Binding Corporate Rules where applicable
  - mechanism: adequacy
    text: Adequacy decisions where recognized by relevant authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Franklin Whole Home
provenance_date: '2026-11-09'
provider_name: Franklin Whole Home
provider_slug: franklin-whole-home
slug: franklin-whole-home-privacy-policy
source_date: '2026-11-09'
source_filename: franklin-whole-home-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.franklinwh.com/cybersecurity/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Franklin Whole Home\naid: franklin-whole-home\nurl: https://www.franklinwh.com/cybersecurity/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: FranklinWH Energy Storage Inc. is the data controller responsible for your personal data.\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number, mailing address, account credentials.\n- category: location\n  text: Installation address (precise), utility service territory, IP-derived location, mobile device GPS (if enabled).\n- category: behavioral\n  text: Battery charge/discharge cycles, state of charge,\
  \ energy consumption patterns, solar production data, grid\n    import/export, power flow data, system alerts, battery health metrics, inverter performance.\n- category: financial\n  text: Credit/debit card numbers, billing address, transaction history.\n- category: communication\n  text: Emails, chat transcripts, phone call recordings (where permitted), support tickets, remote diagnostic session\n    logs, service visit records.\n- category: device\n  text: IP address, mobile advertising IDs (IDFA, AAID), MAC address, device type, operating system, browser type,\n    app version.\npurposes:\n- purpose: account and support\n  text: Account creation, order fulfillment, warranty registration, customer communications, and support.\n- purpose: marketing\n  text: Sending marketing communications (with your consent or as permitted by law)\nretention:\n- scope: Account information\n  period: Duration of account + 90 days\n  text: 'Account Information: Duration of account + 90 days'\n- scope:\
  \ Energy system data\n  period: 7 years\n  text: 'Energy System Data: 7 years (for warranty support and battery degradation tracking)'\n- scope: Device and online identifiers\n  period: Short-term (typically < 13 months)\n  text: 'Device/Online Identifiers: Short-term (typically < 13 months)'\n- scope: Payment card data\n  period: null\n  text: Payment card data is processed by third-party payment processors and not stored by FranklinWH.\nresidency:\n- region: United States\n  text: 'United States: Primary data storage (AWS servers), customer support, engineering, and corporate operations'\n- region: Singapore\n  text: 'Singapore: Regional operations, customer support, and business administration'\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission and/or UK ICO\n- mechanism: BCR\n  text: Binding Corporate Rules where applicable\n- mechanism: adequacy\n  text: Adequacy decisions where recognized by relevant authorities\nsubprocessors:\n\
  \  url: null\n  text: 'Cloud Infrastructure (AWS): Data hosting, storage, and processing'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to dataprivacy@franklinwh.com\n  text: 'Email: dataprivacy@franklinwh.com'\nrights:\n- right: deletion\n  text: 'Right to Deletion: Request deletion of your personal information (subject to exceptions)'\n- right: access\n  text: 'Right to Know/Access: Request information about what personal information we collect and how we use it'\n- right: correction\n  text: 'Right to Correction: Request correction of inaccurate personal information'\n- right: portability\n  text: 'Right to Portability: Receive your personal information in a structured, machine-readable format'\nsale_or_sharing:\n  stance: conditional\n  text: We may share certain online identifiers with advertising partners through cookies, which may constitute\n    \"sharing\" under California law.\n"
source_yaml_url: https://artifacts.apis.io/franklin-whole-home/privacy/franklin-whole-home-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Franklin Whole Home's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Energy Storage
- Home Energy Management
- Solar
- Batteries
- IoT
- Smart Home
- Electric Vehicles
- Cleantech
- Device Telemetry
---
