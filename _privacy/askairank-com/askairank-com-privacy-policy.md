---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account we collect your email address and, optionally, your name.
  - category: behavioral
    text: 'We collect information about how you use AskAiRank: pages visited, features used, session duration, and actions taken inside the dashboard.'
  - category: financial
    text: We do store your Stripe customer ID and subscription status so we can enforce plan limits and send billing receipts.
  - category: device
    text: Server logs and error reports (via Sentry) may include IP addresses, browser type, and the URL that triggered an error.
  - category: communication
    text: Your public Instagram or Facebook user ID and username, the text of your comment, the comment ID and the post ID.
  deletion:
    route: Email the privacy contact to exercise erasure rights
    text: Erasure - request deletion of your data (subject to legal retention requirements).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service and visibility reports
    text: To provide the AskAiRank service and generate visibility reports.
  - purpose: Product alerts
    text: To send product alerts (email, Telegram) when your visibility changes.
  - purpose: Billing
    text: To process billing via Stripe.
  - purpose: Advertising
    text: We do not use it for advertising.
  residency:
  - region: EU
    text: PostHog Product analytics (self-hosted) Self-hosted on our EU infrastructure
  retention:
  - period: lifetime of your account plus 30 days after deletion
    scope: Account data
    text: Account data is retained for the lifetime of your account plus 30 days after deletion.
  - period: 90 days
    scope: Visibility run data
    text: Visibility run data (prompts, LLM responses, mentions) is retained for 90 days on primary storage, up to 1 year on warm storage, then archived to encrypted S3 or deleted.
  - period: 7 years
    scope: Billing records
    text: Billing records are retained for 7 years to meet tax and accounting obligations.
  - period: up to 90 days
    scope: Log and error data
    text: Log and error data is retained for up to 90 days.
  rights:
  - right: Access
    text: Access - request a copy of the data we hold about you.
  - right: Rectification
    text: Rectification - ask us to correct inaccurate data.
  - right: Erasure
    text: Erasure - request deletion of your data (subject to legal retention requirements).
  - right: Portability
    text: Portability - receive your data in a machine-readable format.
  - right: Restriction
    text: Restriction - ask us to limit how we process your data.
  - right: Objection
    text: Objection - object to processing based on legitimate interests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'We share data with the following sub-processors to deliver the service: Sub-processor Purpose Data transfer Stripe Payment processing EEA/US - Standard Contractual Clauses OpenAI LLM visibility queries (ChatGPT) US - Data Processing Agreement Anthropic LLM visibility queries (Claude) US - Data Processing Agreement'
    url: null
  transfers:
  - mechanism: SCC
    text: Stripe Payment processing EEA/US - Standard Contractual Clauses
  - mechanism: other
    text: OpenAI LLM visibility queries (ChatGPT) US - Data Processing Agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskAiRank
provenance_date: '2026-11-09'
provider_name: AskAiRank
provider_slug: askairank-com
slug: askairank-com-privacy-policy
source_date: '2026-11-09'
source_filename: askairank-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askairank.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskAiRank\naid: askairank-com\nurl: https://askairank.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account we collect your email address and, optionally, your name.\n- category: behavioral\n  text: 'We collect information about how you use AskAiRank: pages visited, features used, session duration, and\n    actions taken inside the dashboard.'\n- category: financial\n  text: We do store your Stripe customer ID and subscription status so we can enforce plan limits and send billing\n    receipts.\n- category:\
  \ device\n  text: Server logs and error reports (via Sentry) may include IP addresses, browser type, and the URL that triggered\n    an error.\n- category: communication\n  text: Your public Instagram or Facebook user ID and username, the text of your comment, the comment ID and the\n    post ID.\npurposes:\n- purpose: Provide the service and visibility reports\n  text: To provide the AskAiRank service and generate visibility reports.\n- purpose: Product alerts\n  text: To send product alerts (email, Telegram) when your visibility changes.\n- purpose: Billing\n  text: To process billing via Stripe.\n- purpose: Advertising\n  text: We do not use it for advertising.\nretention:\n- scope: Account data\n  period: lifetime of your account plus 30 days after deletion\n  text: Account data is retained for the lifetime of your account plus 30 days after deletion.\n- scope: Visibility run data\n  period: 90 days\n  text: Visibility run data (prompts, LLM responses, mentions) is retained for 90\
  \ days on primary storage, up to\n    1 year on warm storage, then archived to encrypted S3 or deleted.\n- scope: Billing records\n  period: 7 years\n  text: Billing records are retained for 7 years to meet tax and accounting obligations.\n- scope: Log and error data\n  period: up to 90 days\n  text: Log and error data is retained for up to 90 days.\nresidency:\n- region: EU\n  text: PostHog Product analytics (self-hosted) Self-hosted on our EU infrastructure\ntransfers:\n- mechanism: SCC\n  text: Stripe Payment processing EEA/US - Standard Contractual Clauses\n- mechanism: other\n  text: OpenAI LLM visibility queries (ChatGPT) US - Data Processing Agreement\nsubprocessors:\n  url: null\n  text: 'We share data with the following sub-processors to deliver the service: Sub-processor Purpose Data transfer\n    Stripe Payment processing EEA/US - Standard Contractual Clauses OpenAI LLM visibility queries (ChatGPT) US -\n    Data Processing Agreement Anthropic LLM visibility queries (Claude)\
  \ US - Data Processing Agreement'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy contact to exercise erasure rights\n  text: Erasure - request deletion of your data (subject to legal retention requirements).\nrights:\n- right: Access\n  text: Access - request a copy of the data we hold about you.\n- right: Rectification\n  text: Rectification - ask us to correct inaccurate data.\n- right: Erasure\n  text: Erasure - request deletion of your data (subject to legal retention requirements).\n- right: Portability\n  text: Portability - receive your data in a machine-readable format.\n- right: Restriction\n  text: Restriction - ask us to limit how we process your data.\n- right: Objection\n  text: Objection - object to processing based on legitimate interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/askairank-com/privacy/askairank-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from AskAiRank's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Software-as-a-Service
- Marketing
- Visibility
- Analytics
- Company
---
