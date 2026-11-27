---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address and hashed password
  - category: financial
    text: Billing information (processed by Stripe, never stored by us)
  - category: behavioral
    text: Page URL and referrer
  - category: device
    text: Browser type and viewport size (from the User-Agent header)
  - category: location
    text: Country, region, and city (derived from IP at ingest, then the IP is discarded — no raw IPs are stored)
  deletion:
    route: Delete account in account settings; data removed within 30 days
    text: When you delete your account, all associated data is permanently removed within 30 days.
  dpa:
    available: true
    text: Our Data Processing Agreement governs that relationship and is incorporated by reference into our Terms of Service.
    url: https://clamp.sh/dpa
  purposes:
  - purpose: Provide and operate the service
    text: To provide and operate the Clamp service
  - purpose: Process payments
    text: To process payments and manage your subscription
  - purpose: Product updates and offers
    text: To send product updates and offers (only if you opted in)
  - purpose: Support requests
    text: To respond to support requests
  residency:
  - region: Germany
    text: All visitor analytics data — events, sessions, dashboards, and account data — is hosted exclusively in Germany (Falkenstein and Nuremberg)
  retention:
  - period: 12 months (Free), 3 years (Pro and Growth), or 5 years (Business)
    scope: Analytics event data
    text: 'Analytics event data is retained according to your plan: 12 months (Free), 3 years (Pro and Growth), or 5 years (Business).'
  - period: for as long as your account exists
    scope: Account data
    text: Account data is retained for as long as your account exists.
  rights:
  - right: Delete account and data
    text: Delete your account and all associated data
  - right: Opt out of marketing
    text: Opt out of marketing communications at any time
  - right: Access copy of data
    text: Request a copy of all personal data we hold about you
  - right: Rectify
    text: Rectify inaccurate data
  - right: Object or restrict
    text: Object to or restrict processing
  - right: Complain to authority
    text: Lodge a complaint with your local data protection authority
  role:
    text: When you use Clamp to track visitors on your own site, you act as the data controller and Clamp acts as the data processor on your behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not use it for advertising, we do not sell it, and we do not share it with third parties.
  subprocessors:
    text: The full list with purpose, location, and transfer mechanism is published at clamp.sh/sub-processors .
    url: https://clamp.sh/sub-processors
  transfers:
  - mechanism: DPF
    text: Transfers to these sub-processors are covered by the EU-US Data Privacy Framework and Standard Contractual Clauses.
  - mechanism: SCC
    text: Transfers to these sub-processors are covered by the EU-US Data Privacy Framework and Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clamp
provenance_date: '2026-11-09'
provider_name: Clamp
provider_slug: clamp-sh
slug: clamp-sh-privacy-policy
source_date: '2026-11-09'
source_filename: clamp-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clamp.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clamp\naid: clamp-sh\nurl: https://clamp.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When you use Clamp to track visitors on your own site, you act as the data controller and Clamp acts as\n    the data processor on your behalf.\ndata_categories:\n- category: contact\n  text: Email address and hashed password\n- category: financial\n  text: Billing information (processed by Stripe, never stored by us)\n- category: behavioral\n  text: Page URL and referrer\n- category: device\n  text: Browser type and viewport size (from the User-Agent header)\n- category: location\n  text: Country,\
  \ region, and city (derived from IP at ingest, then the IP is discarded — no raw IPs are stored)\npurposes:\n- purpose: Provide and operate the service\n  text: To provide and operate the Clamp service\n- purpose: Process payments\n  text: To process payments and manage your subscription\n- purpose: Product updates and offers\n  text: To send product updates and offers (only if you opted in)\n- purpose: Support requests\n  text: To respond to support requests\nretention:\n- scope: Analytics event data\n  period: 12 months (Free), 3 years (Pro and Growth), or 5 years (Business)\n  text: 'Analytics event data is retained according to your plan: 12 months (Free), 3 years (Pro and Growth), or\n    5 years (Business).'\n- scope: Account data\n  period: for as long as your account exists\n  text: Account data is retained for as long as your account exists.\nresidency:\n- region: Germany\n  text: All visitor analytics data — events, sessions, dashboards, and account data — is hosted exclusively\
  \ in Germany\n    (Falkenstein and Nuremberg)\ntransfers:\n- mechanism: DPF\n  text: Transfers to these sub-processors are covered by the EU-US Data Privacy Framework and Standard Contractual\n    Clauses.\n- mechanism: SCC\n  text: Transfers to these sub-processors are covered by the EU-US Data Privacy Framework and Standard Contractual\n    Clauses.\nsubprocessors:\n  url: https://clamp.sh/sub-processors\n  text: The full list with purpose, location, and transfer mechanism is published at clamp.sh/sub-processors .\ndpa:\n  available: true\n  url: https://clamp.sh/dpa\n  text: Our Data Processing Agreement governs that relationship and is incorporated by reference into our Terms\n    of Service.\ndeletion:\n  route: Delete account in account settings; data removed within 30 days\n  text: When you delete your account, all associated data is permanently removed within 30 days.\nrights:\n- right: Delete account and data\n  text: Delete your account and all associated data\n- right: Opt out\
  \ of marketing\n  text: Opt out of marketing communications at any time\n- right: Access copy of data\n  text: Request a copy of all personal data we hold about you\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Object or restrict\n  text: Object to or restrict processing\n- right: Complain to authority\n  text: Lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use it for advertising, we do not sell it, and we do not share it with third parties.\n"
source_yaml_url: https://artifacts.apis.io/clamp-sh/privacy/clamp-sh-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Clamp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Dashboards
- Artificial Intelligence
- Metrics
- Monitoring
---
