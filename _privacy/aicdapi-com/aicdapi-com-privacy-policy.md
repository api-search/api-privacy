---
api_specs:
- filename: aicdapi-com-agenda-hits-api-openapi.yml
  format: yaml
  label: aicdapi-com Agenda hits API
  slug: aicdapi-com-agenda-hits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-agenda-hits-api-openapi.yml
- filename: aicdapi-com-customer-civic-data-api-openapi.yml
  format: yaml
  label: aicdapi-com Customer civic data API
  slug: aicdapi-com-customer-civic-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-customer-civic-data-api-openapi.yml
- filename: aicdapi-com-data-reports-api-openapi.yml
  format: yaml
  label: aicdapi-com Data reports API
  slug: aicdapi-com-data-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-data-reports-api-openapi.yml
- filename: aicdapi-com-mcp-api-openapi.yml
  format: yaml
  label: aicdapi-com MCP API
  slug: aicdapi-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-mcp-api-openapi.yml
- filename: aicdapi-com-public-api-specification-api-openapi.yml
  format: yaml
  label: aicdapi-com Public API specification API
  slug: aicdapi-com-public-api-specification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-public-api-specification-api-openapi.yml
- filename: aicdapi-com-research-coverage-api-openapi.yml
  format: yaml
  label: aicdapi-com Research coverage API
  slug: aicdapi-com-research-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-research-coverage-api-openapi.yml
- filename: aicdapi-com-sources-api-openapi.yml
  format: yaml
  label: aicdapi-com Sources API
  slug: aicdapi-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-sources-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses passwords contact or authentication data billing addresses
  - category: financial
    text: debit/credit card numbers
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: communication
    text: Email sent to us. Resend receives the complete message for delivery and forwarding.
  - category: behavioral
    text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically collect
  deletion:
    route: Contact hello@aicdapi.com or use the data-rights request method in this notice, or submit a data subject access request
    text: Contact hello@aicdapi.com or use the data-rights request method in this notice to request access, correction, or deletion, subject to applicable law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management and authentication
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: Security and fraud prevention
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: Targeted advertising and event promotion
    text: This information includes mailing addresses, job titles, email addresses, phone numbers, intent data (or user behavior data), Internet Protocol (IP) addresses, social media profiles, social media URLs, and custom profiles, for purposes of targeted advertising and event promotion.
  retention:
  - period: 35 days
    scope: Anonymous daily visit records
    text: Anonymous daily visit records are deleted after 35 days.
  - period: 90 days after closure
    scope: Private missing-data report details and retry records
    text: Report details and retry records become eligible for deletion 90 days after closure.
  - period: 30 days
    scope: Stored raw validation captures
    text: Stored raw validation captures become eligible after 30 days.
  rights:
  - right: Access
    text: Right to access your personal data
  - right: Correction
    text: Right to correct inaccuracies in your personal data
  - right: Deletion
    text: Right to request the deletion of your personal data
  - right: Portability
    text: Right to obtain a copy of the personal data you previously shared with us
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: We use providers for hosting and storage (including Vercel and Neon), account authentication (Clerk), card payments (Stripe), email delivery and subscription management (Resend), analytics (PostHog and Vercel), error monitoring (Sentry), and AI-assisted extraction and classification (Google Gemini and, where configured, Anthropic).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: aicdapi-com
provenance_date: '2026-11-09'
provider_name: aicdapi-com
provider_slug: aicdapi-com
slug: aicdapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: aicdapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aicdapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: aicdapi-com\naid: aicdapi-com\nurl: https://aicdapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names email addresses passwords contact or authentication data billing addresses\n- category: financial\n  text: debit/credit card numbers\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: location\n  text:\
  \ Location Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: communication\n  text: Email sent to us. Resend receives the complete message for delivery and forwarding.\n- category: behavioral\n  text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information\n    our servers automatically collect\npurposes:\n- purpose: Account management and authentication\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: Security and fraud prevention\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: Targeted advertising and event promotion\n  text: This information includes mailing addresses, job titles, email addresses, phone numbers, intent data (or\n    user behavior data),\
  \ Internet Protocol (IP) addresses, social media profiles, social media URLs, and custom\n    profiles, for purposes of targeted advertising and event promotion.\nretention:\n- scope: Anonymous daily visit records\n  period: 35 days\n  text: Anonymous daily visit records are deleted after 35 days.\n- scope: Private missing-data report details and retry records\n  period: 90 days after closure\n  text: Report details and retry records become eligible for deletion 90 days after closure.\n- scope: Stored raw validation captures\n  period: 30 days\n  text: Stored raw validation captures become eligible after 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use providers for hosting and storage (including Vercel and Neon), account authentication (Clerk), card\n    payments (Stripe), email delivery and subscription management (Resend), analytics (PostHog and Vercel), error\n    monitoring (Sentry), and AI-assisted extraction and classification (Google Gemini and,\
  \ where configured, Anthropic).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@aicdapi.com or use the data-rights request method in this notice, or submit a data subject\n    access request\n  text: Contact hello@aicdapi.com or use the data-rights request method in this notice to request access, correction,\n    or deletion, subject to applicable law.\nrights:\n- right: Access\n  text: Right to access your personal data\n- right: Correction\n  text: Right to correct inaccuracies in your personal data\n- right: Deletion\n  text: Right to request the deletion of your personal data\n- right: Portability\n  text: Right to obtain a copy of the personal data you previously shared with us\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California’s privacy law), the sale of personal data, or profiling in furtherance\
  \ of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: prohibited\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/aicdapi-com/privacy/aicdapi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from aicdapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Civic Data
- Government
- MCP
---
