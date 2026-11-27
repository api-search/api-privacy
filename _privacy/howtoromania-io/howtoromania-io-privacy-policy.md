---
api_specs:
- filename: howtoromania-io-billing-api-openapi.yml
  format: yaml
  label: HowToRomania Billing API
  slug: howtoromania-io-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-billing-api-openapi.yml
- filename: howtoromania-io-bnr-rates-free-api-openapi.yml
  format: yaml
  label: HowToRomania BNR rates (free) API
  slug: howtoromania-io-bnr-rates-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-bnr-rates-free-api-openapi.yml
- filename: howtoromania-io-companies-api-openapi.yml
  format: yaml
  label: HowToRomania Companies API
  slug: howtoromania-io-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-companies-api-openapi.yml
- filename: howtoromania-io-courts-api-openapi.yml
  format: yaml
  label: HowToRomania Courts API
  slug: howtoromania-io-courts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-courts-api-openapi.yml
- filename: howtoromania-io-e-factura-api-openapi.yml
  format: yaml
  label: HowToRomania E Factura API
  slug: howtoromania-io-e-factura-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-e-factura-api-openapi.yml
- filename: howtoromania-io-keys-api-openapi.yml
  format: yaml
  label: HowToRomania Keys API
  slug: howtoromania-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-keys-api-openapi.yml
- filename: howtoromania-io-legislation-api-openapi.yml
  format: yaml
  label: HowToRomania Legislation API
  slug: howtoromania-io-legislation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-legislation-api-openapi.yml
- filename: howtoromania-io-me-api-openapi.yml
  format: yaml
  label: HowToRomania Me API
  slug: howtoromania-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-me-api-openapi.yml
- filename: howtoromania-io-pricing-api-openapi.yml
  format: yaml
  label: HowToRomania Pricing API
  slug: howtoromania-io-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-pricing-api-openapi.yml
- filename: howtoromania-io-validation-api-openapi.yml
  format: yaml
  label: HowToRomania Validation API
  slug: howtoromania-io-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtoromania-io/openapi/howtoromania-io-validation-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address Create your API key, contact you about your account, billing and service changes
  - category: financial
    text: Payment records (amount, date, Stripe customer/payment ID)
  - category: identifying
    text: IP address at key signup; per-IP daily call counter for the demo key
  - category: behavioral
    text: Credit balance and usage (credits used per endpoint per day, lifetime totals)
  - category: professional
    text: Representatives come from a snapshot of the ONRC open dataset
  deletion:
    route: Email hello@howtoromania.io
    text: or after a verified deletion request
  dpa:
    available: true
    text: Our Data Processing Addendum (available at howtoromania.io/dpa and incorporated by reference into our Terms of Service)
    url: howtoromania.io/dpa
  purposes:
  - purpose: Create API key and account
    text: Create your API key, contact you about your account, billing and service changes
  - purpose: Metering and billing
    text: Meter and bill credits, show usage, support
  - purpose: Fraud prevention
    text: Limit free keys to 3 per IP per day; apply the demo limit
  - purpose: Know-your-business checks
    text: We make this public data available to businesses for know-your-business (KYB) checks, supplier and partner verification, fraud prevention, invoicing and legal compliance
  residency:
  - region: EU
    text: the database (D1) is stored in the EU (Cloudflare EU jurisdiction)
  - region: Romania
    text: A computer we run in Romania, connected to Cloudflare over an encrypted Cloudflare Tunnel
  retention:
  - period: 30 days
    scope: Signup IP and demo per-IP counters
    text: Deleted after 30 days by a daily automatic job
  - period: at most 7 days
    scope: Error logs
    text: Deleted automatically by Cloudflare after at most 7 days (currently 3 days)
  - period: 12 months
    scope: Email, API key, balance, usage totals
    text: While the key is active, then for 12 months after the key's last use or after a verified deletion request, whichever is earlier
  - period: up to 10 years
    scope: Payment and invoicing records
    text: currently up to 10 years from the end of the financial year to which the record relates
  - period: 3 years
    scope: Checkout consent records
    text: 3 years from the purchase (the general limitation period)
  - period: 24 months
    scope: Support emails
    text: Support emails 24 months after the last exchange
  - period: not stored
    scope: Invoice content sent in calls
    text: Not stored; discarded once the response is sent
  rights:
  - right: access
    text: You can request access, rectification, erasure, restriction, portability and object to processing based on legitimate interest.
  - right: rectification
    text: ask us to correct data we have changed or added (rectification)
  - right: objection
    text: object to the processing (art. 21)
  - right: erasure or restriction
    text: ask for erasure or restriction where the law allows
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it for advertising.
  subprocessors:
    text: 4. Service providers (sub-processors) Provider Role Location / transfer safeguard Cloudflare, Inc. Hosting (Workers), database (D1), cache (KV), error logs, DNS, security
    url: null
  transfers:
  - mechanism: DPF
    text: EU-US Data Privacy Framework / Standard Contractual Clauses for any access from outside the EU
  - mechanism: SCC
    text: incorporating Standard Contractual Clauses or relying on the EU-US Data Privacy Framework for any transfer outside the EU/EEA, as applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: howtoromania-io
provenance_date: '2026-11-09'
provider_name: HowToRomania
provider_slug: howtoromania-io
slug: howtoromania-io-privacy-policy
source_date: '2026-11-09'
source_filename: howtoromania-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://howtoromania.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: howtoromania-io\naid: howtoromania-io\nurl: https://howtoromania.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address Create your API key, contact you about your account, billing and service changes\n- category: financial\n  text: Payment records (amount, date, Stripe customer/payment ID)\n- category: identifying\n  text: IP address at key signup; per-IP daily call counter for the demo key\n- category: behavioral\n  text: Credit balance and usage (credits used per endpoint per day, lifetime totals)\n- category: professional\n\
  \  text: Representatives come from a snapshot of the ONRC open dataset\npurposes:\n- purpose: Create API key and account\n  text: Create your API key, contact you about your account, billing and service changes\n- purpose: Metering and billing\n  text: Meter and bill credits, show usage, support\n- purpose: Fraud prevention\n  text: Limit free keys to 3 per IP per day; apply the demo limit\n- purpose: Know-your-business checks\n  text: We make this public data available to businesses for know-your-business (KYB) checks, supplier and partner\n    verification, fraud prevention, invoicing and legal compliance\nretention:\n- scope: Signup IP and demo per-IP counters\n  period: 30 days\n  text: Deleted after 30 days by a daily automatic job\n- scope: Error logs\n  period: at most 7 days\n  text: Deleted automatically by Cloudflare after at most 7 days (currently 3 days)\n- scope: Email, API key, balance, usage totals\n  period: 12 months\n  text: While the key is active, then for 12 months\
  \ after the key's last use or after a verified deletion request,\n    whichever is earlier\n- scope: Payment and invoicing records\n  period: up to 10 years\n  text: currently up to 10 years from the end of the financial year to which the record relates\n- scope: Checkout consent records\n  period: 3 years\n  text: 3 years from the purchase (the general limitation period)\n- scope: Support emails\n  period: 24 months\n  text: Support emails 24 months after the last exchange\n- scope: Invoice content sent in calls\n  period: not stored\n  text: Not stored; discarded once the response is sent\nresidency:\n- region: EU\n  text: the database (D1) is stored in the EU (Cloudflare EU jurisdiction)\n- region: Romania\n  text: A computer we run in Romania, connected to Cloudflare over an encrypted Cloudflare Tunnel\ntransfers:\n- mechanism: DPF\n  text: EU-US Data Privacy Framework / Standard Contractual Clauses for any access from outside the EU\n- mechanism: SCC\n  text: incorporating Standard\
  \ Contractual Clauses or relying on the EU-US Data Privacy Framework for any transfer\n    outside the EU/EEA, as applicable\nsubprocessors:\n  url: null\n  text: 4. Service providers (sub-processors) Provider Role Location / transfer safeguard Cloudflare, Inc. Hosting\n    (Workers), database (D1), cache (KV), error logs, DNS, security\ndpa:\n  available: true\n  url: howtoromania.io/dpa\n  text: Our Data Processing Addendum (available at howtoromania.io/dpa and incorporated by reference into our Terms\n    of Service)\ndeletion:\n  route: Email hello@howtoromania.io\n  text: or after a verified deletion request\nrights:\n- right: access\n  text: You can request access, rectification, erasure, restriction, portability and object to processing based\n    on legitimate interest.\n- right: rectification\n  text: ask us to correct data we have changed or added (rectification)\n- right: objection\n  text: object to the processing (art. 21)\n- right: erasure or restriction\n  text: ask for\
  \ erasure or restriction where the law allows\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/howtoromania-io/privacy/howtoromania-io-privacy-policy.yml
stated_fields:
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
summary_line: 28 quoted statements, read from howtoromania-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Finance
- Legal
- Artificial Intelligence
---
