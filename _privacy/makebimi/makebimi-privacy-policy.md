---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: makeBIMI SVG Validation API
  slug: makebimi-validation-api
  spec_type: OpenAPI
  url: https://makebimi.com/public/openapi.yaml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Email addresses submitted via the contact form or audit request form on veriBIMI.com, and email addresses voluntarily submitted on makeBIMI.com to receive DNS record delivery.
  - category: other
    text: Files uploaded for conversion are processed in volatile memory and deleted immediately after the conversion completes.
  deletion:
    route: email request to the listed contact address
    text: You may request deletion at any time by contacting us at [email protected]
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to inquiries
    text: Contact and audit request submissions are used solely to respond to your inquiry.
  - purpose: site performance analytics
    text: We utilise strictly anonymised analytics to measure site performance.
  - purpose: traffic measurement
    text: Google Analytics 4 (GA4) is active on both sites to measure traffic and understand how visitors use the tools.
  residency:
  - region: Switzerland
    text: Both properties are hosted on Infomaniak Network SA, Geneva, Switzerland.
  retention:
  - period: 24 months
    scope: makeBIMI DNS delivery email addresses
    text: Records are retained for a maximum of 24 months from the date of submission, after which they are permanently deleted.
  - period: 12 months
    scope: veriBIMI audit request submissions
    text: deleted within 12 months of engagement close, or immediately upon written request.
  - period: immediately after the conversion completes
    scope: uploaded conversion files
    text: Files uploaded for conversion are processed in volatile memory and deleted immediately after the conversion completes.
  rights:
  - right: access
    text: For any privacy inquiry, data access request, or deletion request, contact us at [email protected]
  - right: analytics opt-out
    text: You may opt out at any time using the Google Analytics Opt-out Browser Add-on
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell, share, licence, or use your email address for any marketing purpose without your explicit consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: GA4 data is processed by Google LLC on servers in the United States under Google's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: makeBIMI
provenance_date: '2026-11-10'
provider_name: makeBIMI
provider_slug: makebimi
slug: makebimi-privacy-policy
source_date: '2026-11-10'
source_filename: makebimi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://veribimi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: makeBIMI\naid: makebimi\nurl: https://veribimi.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email addresses submitted via the contact form or audit request form on veriBIMI.com, and email addresses\n    voluntarily submitted on makeBIMI.com to receive DNS record delivery.\n- category: other\n  text: Files uploaded for conversion are processed in volatile memory and deleted immediately after the conversion\n    completes.\npurposes:\n- purpose: respond to inquiries\n  text: Contact and audit request submissions are used solely\
  \ to respond to your inquiry.\n- purpose: site performance analytics\n  text: We utilise strictly anonymised analytics to measure site performance.\n- purpose: traffic measurement\n  text: Google Analytics 4 (GA4) is active on both sites to measure traffic and understand how visitors use the\n    tools.\nretention:\n- scope: makeBIMI DNS delivery email addresses\n  period: 24 months\n  text: Records are retained for a maximum of 24 months from the date of submission, after which they are permanently\n    deleted.\n- scope: veriBIMI audit request submissions\n  period: 12 months\n  text: deleted within 12 months of engagement close, or immediately upon written request.\n- scope: uploaded conversion files\n  period: immediately after the conversion completes\n  text: Files uploaded for conversion are processed in volatile memory and deleted immediately after the conversion\n    completes.\nresidency:\n- region: Switzerland\n  text: Both properties are hosted on Infomaniak Network SA, Geneva,\
  \ Switzerland.\ntransfers:\n- mechanism: SCC\n  text: GA4 data is processed by Google LLC on servers in the United States under Google's standard contractual\n    clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the listed contact address\n  text: You may request deletion at any time by contacting us at [email protected]\nrights:\n- right: access\n  text: For any privacy inquiry, data access request, or deletion request, contact us at [email protected]\n- right: analytics opt-out\n  text: You may opt out at any time using the Google Analytics Opt-out Browser Add-on\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, share, licence, or use your email address for any marketing purpose without your explicit\n    consent.\n"
source_yaml_url: https://artifacts.apis.io/makebimi/privacy/makebimi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from makeBIMI's own page on 2026-11-10.
synthetic: false
tags:
- BIMI
- DMARC
- Email Authentication
- SVG
- brand indicators
- SVG validation
---
