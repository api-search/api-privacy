---
api_specs:
- filename: codebahn-net-activitypub-api-openapi.yml
  format: yaml
  label: Codebahn Activitypub API
  slug: codebahn-net-activitypub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-activitypub-api-openapi.yml
- filename: codebahn-net-admin-api-openapi.yml
  format: yaml
  label: Codebahn Admin API
  slug: codebahn-net-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-admin-api-openapi.yml
- filename: codebahn-net-issue-api-openapi.yml
  format: yaml
  label: Codebahn Issue API
  slug: codebahn-net-issue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-issue-api-openapi.yml
- filename: codebahn-net-miscellaneous-api-openapi.yml
  format: yaml
  label: Codebahn Miscellaneous API
  slug: codebahn-net-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-miscellaneous-api-openapi.yml
- filename: codebahn-net-notification-api-openapi.yml
  format: yaml
  label: Codebahn Notification API
  slug: codebahn-net-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-notification-api-openapi.yml
- filename: codebahn-net-organization-api-openapi.yml
  format: yaml
  label: Codebahn Organization API
  slug: codebahn-net-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-organization-api-openapi.yml
- filename: codebahn-net-package-api-openapi.yml
  format: yaml
  label: Codebahn Package API
  slug: codebahn-net-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-package-api-openapi.yml
- filename: codebahn-net-repository-api-openapi.yml
  format: yaml
  label: Codebahn Repository API
  slug: codebahn-net-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-repository-api-openapi.yml
- filename: codebahn-net-settings-api-openapi.yml
  format: yaml
  label: Codebahn Settings API
  slug: codebahn-net-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-settings-api-openapi.yml
- filename: codebahn-net-user-api-openapi.yml
  format: yaml
  label: Codebahn User API
  slug: codebahn-net-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-user-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address Authentication, notifications, billing Contract performance (Art. 6(1)(b))
  - category: identifying
    text: Display name, username Identification within the Service Contract performance
  - category: financial
    text: Organisation name Invoicing Contract performance
  - category: device
    text: IP addresses (in server logs) Security, abuse prevention, debugging Legitimate interest (Art. 6(1)(f))
  - category: behavioral
    text: Your answer to “What brought you here?” during onboarding, and optionally what prompted you to look
  - category: communication
    text: Words you give us for publication, with a description you write or approve
  deletion:
    route: Email privacy@codebahn.net to exercise erasure rights
    text: Erasure (Art. 17). Request deletion of your personal data, subject to legal retention requirements (see section 6).
  dpa:
    available: true
    text: For organisations that require a DPA under GDPR Article 28, our Data Processing Agreement is published and applies automatically to all customers.
    url: codebahn.net/docs/dpa
  purposes:
  - purpose: Hosting the Service
    text: Issues, pull requests, comments Hosting the Service Contract performance
  - purpose: Billing and quota enforcement
    text: Compute-minute consumption Billing, quota enforcement Contract performance
  - purpose: Security and abuse prevention
    text: IP addresses (in server logs) Security, abuse prevention, debugging Legitimate interest (Art. 6(1)(f))
  - purpose: Advertising or profiling
    text: We do not use personal data for advertising or profiling.
  residency:
  - region: EU/EEA
    text: Customer Data does not leave the EU/EEA.
  - region: fr-par (Paris, France)
    text: Primary infrastructure Scaleway (Iliad Group) fr-par (Paris, France)
  - region: fsn1 (Falkenstein, Germany)
    text: Backups Hetzner Online GmbH fsn1 (Falkenstein, Germany)
  retention:
  - period: 30 days
    scope: Server logs (IP addresses)
    text: Server logs containing IP addresses are retained for 30 days, then deleted.
  - period: 90 days
    scope: Build logs
    text: Build logs 90 days after the job finishes (up to 365 days until 15 December 2026)
  - period: 30 days read-only
    scope: Customer Data after cancellation
    text: Customer Data (after cancellation) 30 days read-only; deleted from live systems within 90 days after termination
  - period: 7 years
    scope: Billing records
    text: Billing records 7 years (Swedish Bokforingslag, BFL)
  - period: 12 months of inactivity
    scope: Personal accounts without subscription
    text: Personal accounts (no subscription) Until you delete the account or 12 months of inactivity
  rights:
  - right: Access
    text: Access (Art. 15). Request a copy of your personal data.
  - right: Rectification
    text: Rectification (Art. 16). Correct inaccurate personal data.
  - right: Erasure
    text: Erasure (Art. 17). Request deletion of your personal data, subject to legal retention requirements (see section 6).
  - right: Restriction
    text: Restriction (Art. 18). Request restriction of processing in certain circumstances.
  - right: Portability
    text: Portability (Art. 20). Receive your personal data in a structured, machine-readable format.
  - right: Objection
    text: Objection (Art. 21). Object to processing based on legitimate interest.
  role:
    text: Hackerman AB is the data controller for the personal data described in this policy. For Customer Data hosted on the Service (repository content, issues, CI artifacts), we act as a data processor on behalf of the organisation that owns the data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The full list of sub-processors and service providers is published at codebahn.net/docs/subprocessors and is kept current.
    url: codebahn.net/docs/subprocessors
  transfers:
  - mechanism: adequacy
    text: Corporate email is handled by Proton Mail (Geneva, Switzerland), which is covered by an EU adequacy decision.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Codebahn
provenance_date: '2026-11-09'
provider_name: Codebahn
provider_slug: codebahn-net
slug: codebahn-net-privacy-policy
source_date: '2026-11-09'
source_filename: codebahn-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codebahn.net/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Codebahn\naid: codebahn-net\nurl: https://codebahn.net/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Hackerman AB is the data controller for the personal data described in this policy. For Customer Data hosted\n    on the Service (repository content, issues, CI artifacts), we act as a data processor on behalf of the organisation\n    that owns the data.\ndata_categories:\n- category: contact\n  text: Email address Authentication, notifications, billing Contract performance (Art. 6(1)(b))\n- category: identifying\n  text: Display name, username Identification within the Service Contract\
  \ performance\n- category: financial\n  text: Organisation name Invoicing Contract performance\n- category: device\n  text: IP addresses (in server logs) Security, abuse prevention, debugging Legitimate interest (Art. 6(1)(f))\n- category: behavioral\n  text: Your answer to “What brought you here?” during onboarding, and optionally what prompted you to look\n- category: communication\n  text: Words you give us for publication, with a description you write or approve\npurposes:\n- purpose: Hosting the Service\n  text: Issues, pull requests, comments Hosting the Service Contract performance\n- purpose: Billing and quota enforcement\n  text: Compute-minute consumption Billing, quota enforcement Contract performance\n- purpose: Security and abuse prevention\n  text: IP addresses (in server logs) Security, abuse prevention, debugging Legitimate interest (Art. 6(1)(f))\n- purpose: Advertising or profiling\n  text: We do not use personal data for advertising or profiling.\nretention:\n- scope:\
  \ Server logs (IP addresses)\n  period: 30 days\n  text: Server logs containing IP addresses are retained for 30 days, then deleted.\n- scope: Build logs\n  period: 90 days\n  text: Build logs 90 days after the job finishes (up to 365 days until 15 December 2026)\n- scope: Customer Data after cancellation\n  period: 30 days read-only\n  text: Customer Data (after cancellation) 30 days read-only; deleted from live systems within 90 days after termination\n- scope: Billing records\n  period: 7 years\n  text: Billing records 7 years (Swedish Bokforingslag, BFL)\n- scope: Personal accounts without subscription\n  period: 12 months of inactivity\n  text: Personal accounts (no subscription) Until you delete the account or 12 months of inactivity\nresidency:\n- region: EU/EEA\n  text: Customer Data does not leave the EU/EEA.\n- region: fr-par (Paris, France)\n  text: Primary infrastructure Scaleway (Iliad Group) fr-par (Paris, France)\n- region: fsn1 (Falkenstein, Germany)\n  text: Backups Hetzner\
  \ Online GmbH fsn1 (Falkenstein, Germany)\ntransfers:\n- mechanism: adequacy\n  text: Corporate email is handled by Proton Mail (Geneva, Switzerland), which is covered by an EU adequacy decision.\nsubprocessors:\n  url: codebahn.net/docs/subprocessors\n  text: The full list of sub-processors and service providers is published at codebahn.net/docs/subprocessors and\n    is kept current.\ndpa:\n  available: true\n  url: codebahn.net/docs/dpa\n  text: For organisations that require a DPA under GDPR Article 28, our Data Processing Agreement is published and\n    applies automatically to all customers.\ndeletion:\n  route: Email privacy@codebahn.net to exercise erasure rights\n  text: Erasure (Art. 17). Request deletion of your personal data, subject to legal retention requirements (see\n    section 6).\nrights:\n- right: Access\n  text: Access (Art. 15). Request a copy of your personal data.\n- right: Rectification\n  text: Rectification (Art. 16). Correct inaccurate personal data.\n- right:\
  \ Erasure\n  text: Erasure (Art. 17). Request deletion of your personal data, subject to legal retention requirements (see\n    section 6).\n- right: Restriction\n  text: Restriction (Art. 18). Request restriction of processing in certain circumstances.\n- right: Portability\n  text: Portability (Art. 20). Receive your personal data in a structured, machine-readable format.\n- right: Objection\n  text: Objection (Art. 21). Object to processing based on legitimate interest.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/codebahn-net/privacy/codebahn-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from Codebahn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Git Hosting
- Source Code Management
- Continuous Integration
- Forgejo
- Developer Tools
- EU Hosted
- Data Sovereignty
- MCP
---
