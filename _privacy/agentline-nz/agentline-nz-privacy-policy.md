---
api_specs:
- filename: agentline-nz-api-openapi.json
  format: json
  label: Agentline API API
  slug: agentline-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-nz/openapi/_original/agentline-nz-api-openapi.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account information: your email address, chosen inbox name and plan.'
  - category: financial
    text: We receive your Stripe customer ID, subscription status and billing country, but not your full card details.
  - category: communication
    text: 'Message content and metadata: emails sent or received by your Agentline inboxes'
  - category: device
    text: IP addresses, API key usage, sign-in times, the audit log, and which app or AI client made each MCP call (its name and user agent).
  - category: identifying
    text: we keep a normalised form of your email address and a fingerprint of the card you used at checkout, with your account ID and the date.
  deletion:
    route: Close your account; email privacy@agentline.nz to remove a texting waitlist entry
    text: When you close your account, or once the hold after cancellation ends (14 days after a paid plan, 2 days after a cancelled trial), we delete message content within 90 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: route messages (and calls, once offered), store them, and make them available to you and your authorised agents.'
  - purpose: Billing and support
    text: To bill you, provide support, and tell you about changes to the service.
  - purpose: Safety and abuse prevention
    text: 'To keep the service safe: rate limiting, automated content checks for spam and phishing, investigating abuse reports, and meeting legal obligations.'
  residency:
  - region: Outside New Zealand (some providers)
    text: some of which store data outside New Zealand
  - region: United States and Ireland
    text: United States and Ireland.
  retention:
  - period: 90 days
    scope: Message content after account closure or hold end
    text: we delete message content within 90 days.
  - period: 12 months
    scope: Audit logs
    text: Audit logs are kept for 12 months.
  - period: 7 years
    scope: Billing records
    text: Billing records are kept for 7 years, as the Tax Administration Act 1994 requires.
  - period: indefinitely
    scope: Free trial records
    text: Free trial records are kept indefinitely, even after your account is deleted
  - period: 400 days
    scope: Page view totals
    text: We delete these totals after 400 days.
  rights:
  - right: Access and correction
    text: You can ask for access to, or correction of, your personal information at any time by emailing privacy@agentline.nz .
  - right: Complaint to regulator
    text: If you're not satisfied with our response, you can complain to the Office of the Privacy Commissioner
  role:
    text: We are the agency responsible for your personal information under the Privacy Act 2020.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information or use message content for advertising or to train AI models.
  subprocessors:
    text: 'We use these service providers, some of which store data outside New Zealand:'
    url: null
  transfers:
  - mechanism: other
    text: we rely on these providers being subject to comparable safeguards, or on contractual protections, as Information Privacy Principle 12 requires.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentline NZ
provenance_date: '2026-11-09'
provider_name: Agentline NZ
provider_slug: agentline-nz
slug: agentline-nz-privacy-policy
source_date: '2026-11-09'
source_filename: agentline-nz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentline.nz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentline NZ\naid: agentline-nz\nurl: https://agentline.nz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the agency responsible for your personal information under the Privacy Act 2020.\ndata_categories:\n- category: contact\n  text: 'Account information: your email address, chosen inbox name and plan.'\n- category: financial\n  text: We receive your Stripe customer ID, subscription status and billing country, but not your full card details.\n- category: communication\n  text: 'Message content and metadata: emails sent or received by your Agentline inboxes'\n- category: device\n\
  \  text: IP addresses, API key usage, sign-in times, the audit log, and which app or AI client made each MCP call\n    (its name and user agent).\n- category: identifying\n  text: we keep a normalised form of your email address and a fingerprint of the card you used at checkout, with\n    your account ID and the date.\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: route messages (and calls, once offered), store them, and make them available to\n    you and your authorised agents.'\n- purpose: Billing and support\n  text: To bill you, provide support, and tell you about changes to the service.\n- purpose: Safety and abuse prevention\n  text: 'To keep the service safe: rate limiting, automated content checks for spam and phishing, investigating\n    abuse reports, and meeting legal obligations.'\nretention:\n- scope: Message content after account closure or hold end\n  period: 90 days\n  text: we delete message content within 90 days.\n- scope: Audit logs\n\
  \  period: 12 months\n  text: Audit logs are kept for 12 months.\n- scope: Billing records\n  period: 7 years\n  text: Billing records are kept for 7 years, as the Tax Administration Act 1994 requires.\n- scope: Free trial records\n  period: indefinitely\n  text: Free trial records are kept indefinitely, even after your account is deleted\n- scope: Page view totals\n  period: 400 days\n  text: We delete these totals after 400 days.\nresidency:\n- region: Outside New Zealand (some providers)\n  text: some of which store data outside New Zealand\n- region: United States and Ireland\n  text: United States and Ireland.\ntransfers:\n- mechanism: other\n  text: we rely on these providers being subject to comparable safeguards, or on contractual protections, as Information\n    Privacy Principle 12 requires.\nsubprocessors:\n  url: null\n  text: 'We use these service providers, some of which store data outside New Zealand:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ Close your account; email privacy@agentline.nz to remove a texting waitlist entry\n  text: When you close your account, or once the hold after cancellation ends (14 days after a paid plan, 2 days\n    after a cancelled trial), we delete message content within 90 days.\nrights:\n- right: Access and correction\n  text: You can ask for access to, or correction of, your personal information at any time by emailing privacy@agentline.nz\n    .\n- right: Complaint to regulator\n  text: If you're not satisfied with our response, you can complain to the Office of the Privacy Commissioner\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information or use message content for advertising or to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/agentline-nz/privacy/agentline-nz-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Agentline NZ's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Email
- Assistant
- NZ
- Software-as-a-Service
- Company
---
