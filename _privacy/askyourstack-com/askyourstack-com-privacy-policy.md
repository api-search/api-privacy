---
api_specs:
- filename: askyourstack-com-openapi-generated.yml
  format: yaml
  label: AskYourStack API
  slug: askyourstack-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askyourstack-com/openapi/_ae-authored/askyourstack-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: email address, name if you sign in with Google, and sign-in sessions.'
  - category: financial
    text: 'Billing: handled by Stripe. We keep your Stripe customer id and plan, not your card details.'
  - category: device
    text: 'Servers: name, hostname, the facts the agent reports (operating system, memory, disk, running services) and when it last checked in.'
  - category: communication
    text: 'Support: tickets you send, and AI Support chats (kept 90 days and sent to Anthropic, which runs the AI, to answer them).'
  deletion:
    route: Info email or dashboard disconnect
    text: Deleting your account deletes all of it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: We process it to provide the service you signed up for and to meet our legal obligations, such as keeping invoices.
  - purpose: Show trends and warn on clicks, index status or vitals
    text: We use them to show you trends and to warn you when clicks fall, a page leaves the index or a vital turns poor.
  residency:
  - region: Germany
    text: Our servers are in Germany (Hetzner), inside the European Union.
  retention:
  - period: 90 days
    scope: Activity and approvals
    text: Your activity, approvals and alerts are shown to you for 90 days.
  - period: 2 years
    scope: Records and sign-in history
    text: that record and your sign-in history are deleted after 2 years.
  - period: 90 days
    scope: Replaced WordPress content
    text: So that every change can be undone, we keep what a change replaced (the old title, text or other field of that post or page) for 90 days, then delete it.
  - period: 30 days
    scope: Umami session recordings
    text: These recordings also stay on our server and are deleted after 30 days.
  rights:
  - right: Copy, correction or deletion
    text: You can ask for a copy of your data, a correction or deletion at info@askyourstack.com.
  - right: Complain to supervisory authority
    text: You can also complain to the Portuguese data protection authority (CNPD) or the one where you live.
  role:
    text: The controller of your personal data is AskYourStack, Portugal (info@askyourstack.com)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell this data, use it for advertising, share it with anyone other than the AI client you connected, or use it to train AI models.
  subprocessors:
    text: Who else sees it Stripe (payments), Anthropic (AI Support answers), Google (email for sign-in and alerts, Google sign-in and Search Console if you use them, and Analytics if you accept it) and our hosting provider (Hetzner, in Germany).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskYourStack
provenance_date: '2026-11-09'
provider_name: AskYourStack
provider_slug: askyourstack-com
slug: askyourstack-com-privacy-policy
source_date: '2026-11-09'
source_filename: askyourstack-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askyourstack.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskYourStack\naid: askyourstack-com\nurl: https://askyourstack.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is AskYourStack, Portugal (info@askyourstack.com)\ndata_categories:\n- category: identifying\n  text: 'Your account: email address, name if you sign in with Google, and sign-in sessions.'\n- category: financial\n  text: 'Billing: handled by Stripe. We keep your Stripe customer id and plan, not your card details.'\n- category: device\n  text: 'Servers: name, hostname, the facts the agent reports (operating system, memory, disk, running\
  \ services)\n    and when it last checked in.'\n- category: communication\n  text: 'Support: tickets you send, and AI Support chats (kept 90 days and sent to Anthropic, which runs the AI,\n    to answer them).'\npurposes:\n- purpose: Provide the service\n  text: We process it to provide the service you signed up for and to meet our legal obligations, such as keeping\n    invoices.\n- purpose: Show trends and warn on clicks, index status or vitals\n  text: We use them to show you trends and to warn you when clicks fall, a page leaves the index or a vital turns\n    poor.\nretention:\n- scope: Activity and approvals\n  period: 90 days\n  text: Your activity, approvals and alerts are shown to you for 90 days.\n- scope: Records and sign-in history\n  period: 2 years\n  text: that record and your sign-in history are deleted after 2 years.\n- scope: Replaced WordPress content\n  period: 90 days\n  text: So that every change can be undone, we keep what a change replaced (the old title, text or\
  \ other field of\n    that post or page) for 90 days, then delete it.\n- scope: Umami session recordings\n  period: 30 days\n  text: These recordings also stay on our server and are deleted after 30 days.\nresidency:\n- region: Germany\n  text: Our servers are in Germany (Hetzner), inside the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who else sees it Stripe (payments), Anthropic (AI Support answers), Google (email for sign-in and alerts,\n    Google sign-in and Search Console if you use them, and Analytics if you accept it) and our hosting provider\n    (Hetzner, in Germany).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Info email or dashboard disconnect\n  text: Deleting your account deletes all of it.\nrights:\n- right: Copy, correction or deletion\n  text: You can ask for a copy of your data, a correction or deletion at info@askyourstack.com.\n- right: Complain to supervisory authority\n  text: You can also complain to the Portuguese\
  \ data protection authority (CNPD) or the one where you live.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell this data, use it for advertising, share it with anyone other than the AI client you connected,\n    or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/askyourstack-com/privacy/askyourstack-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AskYourStack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Server Management
- SEO
- Automation
---
