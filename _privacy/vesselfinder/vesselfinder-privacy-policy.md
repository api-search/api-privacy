---
api_specs:
- filename: vesselfinder-containers-api-openapi.yml
  format: yaml
  label: VesselFinder Containers API
  slug: vesselfinder-containers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-containers-api-openapi.yml
- filename: vesselfinder-distance-api-openapi.yml
  format: yaml
  label: VesselFinder Distance API
  slug: vesselfinder-distance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-distance-api-openapi.yml
- filename: vesselfinder-expected-arrivals-api-openapi.yml
  format: yaml
  label: VesselFinder Expected Arrivals API
  slug: vesselfinder-expected-arrivals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-expected-arrivals-api-openapi.yml
- filename: vesselfinder-list-manager-api-openapi.yml
  format: yaml
  label: VesselFinder List Manager API
  slug: vesselfinder-list-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-list-manager-api-openapi.yml
- filename: vesselfinder-live-data-api-openapi.yml
  format: yaml
  label: VesselFinder Live Data API
  slug: vesselfinder-live-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-live-data-api-openapi.yml
- filename: vesselfinder-master-data-api-openapi.yml
  format: yaml
  label: VesselFinder Master Data API
  slug: vesselfinder-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-master-data-api-openapi.yml
- filename: vesselfinder-port-calls-api-openapi.yml
  format: yaml
  label: VesselFinder Port Calls API
  slug: vesselfinder-port-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-port-calls-api-openapi.yml
- filename: vesselfinder-status-api-openapi.yml
  format: yaml
  label: VesselFinder Status API
  slug: vesselfinder-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-status-api-openapi.yml
- filename: vesselfinder-vessels-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels API
  slug: vesselfinder-vessels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-api-openapi.yml
- filename: vesselfinder-vessels-list-api-openapi.yml
  format: yaml
  label: VesselFinder Vessels List API
  slug: vesselfinder-vessels-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vesselfinder/openapi/vesselfinder-vessels-list-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data : name, email address, password (stored in hashed form), account settings.'
  - category: financial
    text: 'Billing data : invoice details, VAT/company fields (if provided), purchase history, payment status.'
  - category: communication
    text: 'Support communications : messages and attachments you send us.'
  - category: behavioral
    text: 'Usage and log data : pages/features used, interactions, timestamps, referring URLs, error logs.'
  - category: device
    text: 'Device and network data : IP address, browser/app version, device identifiers, OS, language, time zone, approximate location derived from IP.'
  - category: location
    text: approximate location derived from IP
  deletion:
    route: Account deletion function at https://www.vesselfinder.com/user-profile#/delete-account
    text: 'You can delete your VesselFinder account at any time by using the account deletion function available here: https://www.vesselfinder.com/user-profile#/delete-account .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: Provide the Services (account access, entitlements, API access, customer support).
  - purpose: Process purchases and billing
    text: Process purchases and billing administration.
  - purpose: Security and improvement
    text: Operate, maintain, secure, and improve the Services (including troubleshooting, fraud/abuse prevention).
  - purpose: Analytics
    text: Measure usage and performance (analytics).
  - purpose: Advertising
    text: Show ads on the free plan and measure ad performance.
  retention:
  - period: null
    scope: Account data
    text: 'Account data: for the life of the account plus a reasonable period for dispute handling and compliance.'
  - period: null
    scope: Billing/tax data
    text: 'Billing/tax data: as required by applicable law.'
  - period: null
    scope: Logs/security records
    text: 'Logs/security records: retained for a limited period appropriate to security and troubleshooting.'
  - period: null
    scope: Backups
    text: 'Backups: retained on a rolling basis and overwritten according to our backup lifecycle.'
  rights:
  - right: access
    text: you may have rights to access, correct, delete, restrict/objection, data portability, and to withdraw consent
  - right: complaint to supervisory authority
    text: You also may lodge a complaint with a supervisory authority (EEA/UK users).
  role:
    text: 'Controller : VesselFinder Ltd'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where personal data is transferred outside the EEA/UK, we use appropriate safeguards (e.g., adequacy decisions or Standard Contractual Clauses and related measures), as required by law.
  - mechanism: SCC
    text: Where personal data is transferred outside the EEA/UK, we use appropriate safeguards (e.g., adequacy decisions or Standard Contractual Clauses and related measures), as required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: VesselFinder
provenance_date: '2026-11-10'
provider_name: VesselFinder
provider_slug: vesselfinder
slug: vesselfinder-privacy-policy
source_date: '2026-11-10'
source_filename: vesselfinder-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.vesselfinder.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: VesselFinder\naid: vesselfinder\nurl: https://www.vesselfinder.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller : VesselFinder Ltd'\ndata_categories:\n- category: contact\n  text: 'Account data : name, email address, password (stored in hashed form), account settings.'\n- category: financial\n  text: 'Billing data : invoice details, VAT/company fields (if provided), purchase history, payment status.'\n- category: communication\n  text: 'Support communications : messages and attachments you send us.'\n- category: behavioral\n  text: 'Usage and log data : pages/features\
  \ used, interactions, timestamps, referring URLs, error logs.'\n- category: device\n  text: 'Device and network data : IP address, browser/app version, device identifiers, OS, language, time zone,\n    approximate location derived from IP.'\n- category: location\n  text: approximate location derived from IP\npurposes:\n- purpose: Provide the Services\n  text: Provide the Services (account access, entitlements, API access, customer support).\n- purpose: Process purchases and billing\n  text: Process purchases and billing administration.\n- purpose: Security and improvement\n  text: Operate, maintain, secure, and improve the Services (including troubleshooting, fraud/abuse prevention).\n- purpose: Analytics\n  text: Measure usage and performance (analytics).\n- purpose: Advertising\n  text: Show ads on the free plan and measure ad performance.\nretention:\n- scope: Account data\n  period: null\n  text: 'Account data: for the life of the account plus a reasonable period for dispute handling\
  \ and compliance.'\n- scope: Billing/tax data\n  period: null\n  text: 'Billing/tax data: as required by applicable law.'\n- scope: Logs/security records\n  period: null\n  text: 'Logs/security records: retained for a limited period appropriate to security and troubleshooting.'\n- scope: Backups\n  period: null\n  text: 'Backups: retained on a rolling basis and overwritten according to our backup lifecycle.'\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where personal data is transferred outside the EEA/UK, we use appropriate safeguards (e.g., adequacy decisions\n    or Standard Contractual Clauses and related measures), as required by law.\n- mechanism: SCC\n  text: Where personal data is transferred outside the EEA/UK, we use appropriate safeguards (e.g., adequacy decisions\n    or Standard Contractual Clauses and related measures), as required by law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account\
  \ deletion function at https://www.vesselfinder.com/user-profile#/delete-account\n  text: 'You can delete your VesselFinder account at any time by using the account deletion function available here:\n    https://www.vesselfinder.com/user-profile#/delete-account .'\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, restrict/objection, data portability, and to withdraw consent\n- right: complaint to supervisory authority\n  text: You also may lodge a complaint with a supervisory authority (EEA/UK users).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/vesselfinder/privacy/vesselfinder-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from VesselFinder's own page on 2026-11-10.
synthetic: false
tags:
- AIS
- Maritime
- Vessel Tracking
- Container Tracking
- Geospatial
- Logistics
- Ports
- Supply Chain
---
