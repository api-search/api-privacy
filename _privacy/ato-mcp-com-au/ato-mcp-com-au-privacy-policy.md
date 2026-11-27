---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and your name, if we have it
  - category: contact
    text: Your approximate location when you signed up (city, state, postcode and country, worked out from your IP address).
  - category: financial
    text: Stripe customer and subscription IDs, plan, status, billing period dates, renewal amount, card brand, last four digits and expiry month and year
  - category: behavioral
    text: Which documents in our library we returned to you each day (document IDs only)
  - category: device
    text: Its IP address, browser type, the page and the time, and its Google Analytics, Meta and Reddit browser identifiers.
  - category: professional
    text: Your ABN (if applicable)
  - category: communication
    text: The message, your address and anything attached.
  deletion:
    route: Account page deletion or email to privacy@ato-mcp.com.au
    text: You can delete your account any time from your account page .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'Run the service: sign you in, answer your AI app''s tool calls, and personalise workflow tools to your tax profile.'
  - purpose: Billing
    text: Bill you, and send receipts and account notices.
  - purpose: Analytics and advertising
    text: Understand how the service is used and found, including which ads bring people to it, so we can improve it.
  - purpose: Legal obligations
    text: Meet legal obligations, such as keeping tax records.
  residency:
  - region: Australia
    text: Supabase Database and sign-in Australia (Sydney)
  - region: United States
    text: Vercel Hosting and the servers that handle every request United States
  retention:
  - period: While your account is open
    scope: Account and tax profile
    text: Account, tax profile, usage, lookup counts, connected apps, how you found us, last browser you signed in with, cancellation feedback, email preferences While your account is open. Deleted when you delete your account.
  - period: null
    scope: Billing history
    text: Billing history Kept after you delete your account, with the link to you removed.
  - period: Five years
    scope: Stripe records
    text: Australian tax law requires invoice records to be kept for five years.
  - period: About an hour
    scope: Rate-limit counters
    text: Rate-limit counters About an hour.
  - period: 30 days
    scope: Document returns
    text: Which documents we returned to you each day 30 days, or until you delete your account if sooner.
  rights:
  - right: Access
    text: For a copy of everything we hold about you, or to correct anything else, email privacy@ato-mcp.com.au .
  - right: Correction
    text: You can view and edit your tax profile and email preferences on your account page.
  - right: Complaint
    text: If you're not satisfied, you can complain to the OAIC .
  role:
    text: Australian Tax MCP (ato-mcp.com.au) is operated by William Laverty (ABN 90 296 100 276), Canberra ACT ("we", "us").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your information.
  subprocessors:
    text: These providers process information for us.
    url: null
  transfers:
  - mechanism: other
    text: Most are overseas, so your information is stored or handled outside Australia in the countries listed.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Australian Tax MCP
provenance_date: '2026-11-09'
provider_name: Australian Tax MCP
provider_slug: ato-mcp-com-au
slug: ato-mcp-com-au-privacy-policy
source_date: '2026-11-09'
source_filename: ato-mcp-com-au-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ato-mcp.com.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Australian Tax MCP\naid: ato-mcp-com-au\nurl: https://ato-mcp.com.au/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Australian Tax MCP (ato-mcp.com.au) is operated by William Laverty (ABN 90 296 100 276), Canberra ACT (\"we\",\n    \"us\").\ndata_categories:\n- category: identifying\n  text: Your email address and your name, if we have it\n- category: contact\n  text: Your approximate location when you signed up (city, state, postcode and country, worked out from your IP\n    address).\n- category: financial\n  text: Stripe customer and subscription IDs, plan, status, billing period\
  \ dates, renewal amount, card brand, last\n    four digits and expiry month and year\n- category: behavioral\n  text: Which documents in our library we returned to you each day (document IDs only)\n- category: device\n  text: Its IP address, browser type, the page and the time, and its Google Analytics, Meta and Reddit browser identifiers.\n- category: professional\n  text: Your ABN (if applicable)\n- category: communication\n  text: The message, your address and anything attached.\npurposes:\n- purpose: Run the service\n  text: 'Run the service: sign you in, answer your AI app''s tool calls, and personalise workflow tools to your\n    tax profile.'\n- purpose: Billing\n  text: Bill you, and send receipts and account notices.\n- purpose: Analytics and advertising\n  text: Understand how the service is used and found, including which ads bring people to it, so we can improve\n    it.\n- purpose: Legal obligations\n  text: Meet legal obligations, such as keeping tax records.\nretention:\n\
  - scope: Account and tax profile\n  period: While your account is open\n  text: Account, tax profile, usage, lookup counts, connected apps, how you found us, last browser you signed in\n    with, cancellation feedback, email preferences While your account is open. Deleted when you delete your account.\n- scope: Billing history\n  period: null\n  text: Billing history Kept after you delete your account, with the link to you removed.\n- scope: Stripe records\n  period: Five years\n  text: Australian tax law requires invoice records to be kept for five years.\n- scope: Rate-limit counters\n  period: About an hour\n  text: Rate-limit counters About an hour.\n- scope: Document returns\n  period: 30 days\n  text: Which documents we returned to you each day 30 days, or until you delete your account if sooner.\nresidency:\n- region: Australia\n  text: Supabase Database and sign-in Australia (Sydney)\n- region: United States\n  text: Vercel Hosting and the servers that handle every request United\
  \ States\ntransfers:\n- mechanism: other\n  text: Most are overseas, so your information is stored or handled outside Australia in the countries listed.\nsubprocessors:\n  url: null\n  text: These providers process information for us.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page deletion or email to privacy@ato-mcp.com.au\n  text: You can delete your account any time from your account page .\nrights:\n- right: Access\n  text: For a copy of everything we hold about you, or to correct anything else, email privacy@ato-mcp.com.au .\n- right: Correction\n  text: You can view and edit your tax profile and email preferences on your account page.\n- right: Complaint\n  text: If you're not satisfied, you can complain to the OAIC .\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your information.\n"
source_yaml_url: https://artifacts.apis.io/ato-mcp-com-au/privacy/ato-mcp-com-au-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Australian Tax MCP's own page on 2026-11-09.
synthetic: false
tags:
- Tax
- Artificial Intelligence
- Australia
- MCP
- Open Data
---
