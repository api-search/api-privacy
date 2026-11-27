---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: The certificate itself
  - category: contact
    text: Vendor and agent contact details
  - category: behavioral
    text: PostHog — counts visits and which buttons get used
  deletion:
    route: Close organization in account; or email hello@certifikit.ai for deletion request
    text: Deleting your account deletes everything
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Emailing issuing agent with list of fixes
    text: emailing the issuing agent the exact list of fixes is the product
  - purpose: Site and product measurement
    text: Four tools measure how the site and the product get used.
  retention:
  - period: 7 years
    scope: Vendor and certificate records
    text: While a vendor is active, and for 7 years after you stop tracking them.
  - period: 30 days
    scope: Deleted organization data
    text: Close your organization and we purge it after 30 days
  role:
    text: Each is a processor acting on our instructions, and none of them receive your data for their own purposes.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any of it, we do not use your vendors’ certificates to train models, and we do not share a vendor’s documents with anyone outside your organization.
  subprocessors:
    text: Documents are stored with Vercel, records with Neon, sign-in is handled by Clerk, and email and text messages go out through Resend and Twilio.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CertifiKit
provenance_date: '2026-11-09'
provider_name: CertifiKit
provider_slug: certifikit-ai
slug: certifikit-ai-privacy-policy
source_date: '2026-11-09'
source_filename: certifikit-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://certifikit.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CertifiKit\naid: certifikit-ai\nurl: https://certifikit.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Each is a processor acting on our instructions, and none of them receive your data for their own purposes.\ndata_categories:\n- category: identifying\n  text: The certificate itself\n- category: contact\n  text: Vendor and agent contact details\n- category: behavioral\n  text: PostHog — counts visits and which buttons get used\npurposes:\n- purpose: Emailing issuing agent with list of fixes\n  text: emailing the issuing agent the exact list of fixes is the product\n- purpose: Site\
  \ and product measurement\n  text: Four tools measure how the site and the product get used.\nretention:\n- scope: Vendor and certificate records\n  period: 7 years\n  text: While a vendor is active, and for 7 years after you stop tracking them.\n- scope: Deleted organization data\n  period: 30 days\n  text: Close your organization and we purge it after 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Documents are stored with Vercel, records with Neon, sign-in is handled by Clerk, and email and text messages\n    go out through Resend and Twilio.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close organization in account; or email hello@certifikit.ai for deletion request\n  text: Deleting your account deletes everything\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any of it, we do not use your vendors’ certificates to train models, and we do not share\n    a vendor’s documents with anyone outside your\
  \ organization.\n"
source_yaml_url: https://artifacts.apis.io/certifikit-ai/privacy/certifikit-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from CertifiKit's own page on 2026-11-09.
synthetic: false
tags:
- COI tracking
- Contractor tools
- Property Management
- Compliance Software
---
