---
api_specs:
- filename: housingfeed-com-sample-api-openapi.yml
  format: yaml
  label: housingfeed-com Sample API
  slug: housingfeed-com-sample-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/housingfeed-com/openapi/housingfeed-com-sample-api-openapi.yml
claim_count: 19
description: ''
doc:
  deletion:
    route: Email hello@housingfeed.com
    text: One email to hello@housingfeed.com does it, we reply within a business day and act within 30 days at the latest.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Reply to sample or access requests
    text: To reply, send the sample or access you asked for, and follow up about it (contract / pre-contractual steps, Art. 6(1)(b))
  - purpose: Answer chat questions
    text: Answering your question (legitimate interest, Art. 6(1)(f))
  - purpose: Seeing which pages are useful
    text: Seeing which pages are useful (legitimate interest); no personal data is collected, no fingerprinting, no cross-site tracking
  - purpose: Serve demo and prevent abuse
    text: Serving the demo and preventing abuse (rate limiting by IP, held in memory only)
  - purpose: Showing listing as publisher wrote it
    text: Our basis is legitimate interest (Art. 6(1)(f)) in showing a listing as its publisher wrote it
  retention:
  - period: 2 years of inactivity
    scope: Email address
    text: Until you ask us to delete it, or 2 years of inactivity
  - period: 12 months
    scope: Chat messages
    text: 12 months
  - period: n/a
    scope: Aggregate page statistics
    text: n/a, aggregate only
  - period: Minutes
    scope: Sample-query rate limiting
    text: Minutes, never written to a database
  rights:
  - right: Access, correction, deletion, export
    text: Under the GDPR you can ask us at any time to access, correct, delete, or export the personal data we hold about you
  - right: Restrict or object
    text: to restrict or object to its processing
  - right: Withdraw consent
    text: and to withdraw any consent
  - right: Complain to supervisory authority
    text: You also have the right to complain to a supervisory authority; ours is the Dutch Autoriteit Persoonsgegevens
  role:
    text: Iron Holding B.V. is the controller for any personal data described on this page.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, we do not run advertising, and we never use your data for anything beyond what is listed above.
  subprocessors:
    text: Netlify (hosting, US), Formspree (form delivery, US), Crisp (chat, EU), Simple Analytics (analytics, EU), Supabase (listings database, no personal data), and Apify (API runtime).
    url: null
  transfers:
  - mechanism: DPF
    text: Where a processor is outside the EU, transfers rely on the EU-US Data Privacy Framework or Standard Contractual Clauses.
  - mechanism: SCC
    text: Where a processor is outside the EU, transfers rely on the EU-US Data Privacy Framework or Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: housingfeed-com
provenance_date: '2026-11-09'
provider_name: housingfeed-com
provider_slug: housingfeed-com
slug: housingfeed-com-privacy-policy
source_date: '2026-11-09'
source_filename: housingfeed-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://housingfeed.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: housingfeed-com\naid: housingfeed-com\nurl: https://housingfeed.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Iron Holding B.V. is the controller for any personal data described on this page.\ndata_categories: []\npurposes:\n- purpose: Reply to sample or access requests\n  text: To reply, send the sample or access you asked for, and follow up about it (contract / pre-contractual steps,\n    Art. 6(1)(b))\n- purpose: Answer chat questions\n  text: Answering your question (legitimate interest, Art. 6(1)(f))\n- purpose: Seeing which pages are useful\n  text: Seeing which pages are\
  \ useful (legitimate interest); no personal data is collected, no fingerprinting, no\n    cross-site tracking\n- purpose: Serve demo and prevent abuse\n  text: Serving the demo and preventing abuse (rate limiting by IP, held in memory only)\n- purpose: Showing listing as publisher wrote it\n  text: Our basis is legitimate interest (Art. 6(1)(f)) in showing a listing as its publisher wrote it\nretention:\n- scope: Email address\n  period: 2 years of inactivity\n  text: Until you ask us to delete it, or 2 years of inactivity\n- scope: Chat messages\n  period: 12 months\n  text: 12 months\n- scope: Aggregate page statistics\n  period: n/a\n  text: n/a, aggregate only\n- scope: Sample-query rate limiting\n  period: Minutes\n  text: Minutes, never written to a database\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Where a processor is outside the EU, transfers rely on the EU-US Data Privacy Framework or Standard Contractual\n    Clauses.\n- mechanism: SCC\n  text: Where a processor\
  \ is outside the EU, transfers rely on the EU-US Data Privacy Framework or Standard Contractual\n    Clauses.\nsubprocessors:\n  url: null\n  text: Netlify (hosting, US), Formspree (form delivery, US), Crisp (chat, EU), Simple Analytics (analytics, EU),\n    Supabase (listings database, no personal data), and Apify (API runtime).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@housingfeed.com\n  text: One email to hello@housingfeed.com does it, we reply within a business day and act within 30 days at the\n    latest.\nrights:\n- right: Access, correction, deletion, export\n  text: Under the GDPR you can ask us at any time to access, correct, delete, or export the personal data we hold\n    about you\n- right: Restrict or object\n  text: to restrict or object to its processing\n- right: Withdraw consent\n  text: and to withdraw any consent\n- right: Complain to supervisory authority\n  text: You also have the right to complain to a supervisory authority;\
  \ ours is the Dutch Autoriteit Persoonsgegevens\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, we do not run advertising, and we never use your data for anything beyond\n    what is listed above.\n"
source_yaml_url: https://artifacts.apis.io/housingfeed-com/privacy/housingfeed-com-privacy-policy.yml
stated_fields:
- role
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from housingfeed-com's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Rentals
- Data API
- US
- Listings
---
