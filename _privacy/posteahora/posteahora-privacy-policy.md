---
api_specs:
- filename: posteahora-accounts-api-openapi.yml
  format: yaml
  label: PosteAhora Accounts API
  slug: posteahora-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-accounts-api-openapi.yml
- filename: posteahora-analytics-api-openapi.yml
  format: yaml
  label: PosteAhora Analytics API
  slug: posteahora-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-analytics-api-openapi.yml
- filename: posteahora-ideas-api-openapi.yml
  format: yaml
  label: PosteAhora Ideas API
  slug: posteahora-ideas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-ideas-api-openapi.yml
- filename: posteahora-media-api-openapi.yml
  format: yaml
  label: PosteAhora Media API
  slug: posteahora-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-media-api-openapi.yml
- filename: posteahora-posts-api-openapi.yml
  format: yaml
  label: PosteAhora Posts API
  slug: posteahora-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/posteahora/openapi/posteahora-posts-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (required for account creation and authentication)
  - category: contact
    text: Full name (as provided during registration)
  - category: financial
    text: We receive payment confirmation, subscription status, and billing information (name, email, billing address) from Polar.sh for account management purposes.
  - category: location
    text: IP address and approximate location (country/region)
  - category: device
    text: Browser type and version
  - category: behavioral
    text: Usage patterns and feature interactions
  - category: communication
    text: Direct messages people send to your Instagram account or Facebook Page (the text, the sender's ID and display name)
  - category: other
    text: 'OAuth Tokens: Encrypted access tokens and refresh tokens for platforms including Facebook, Instagram, TikTok, YouTube, X (Twitter), LinkedIn, and Threads.'
  deletion:
    route: Account deletion request via privacy@posteahora.com or account settings
    text: 'Deletion: Request deletion of your account and associated data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To provide, maintain, and improve our social media management services.
  - purpose: Authentication
    text: To authenticate your identity and secure access to your account.
  - purpose: Platform integration
    text: To connect with and interact with third-party social media platforms via their APIs on your behalf.
  - purpose: Analytics and insights
    text: To provide you with performance analytics and insights about your content.
  - purpose: Communication
    text: To send you service-related notifications, updates, security alerts, and support communications.
  - purpose: Legal compliance
    text: To comply with applicable laws, regulations, legal processes, or governmental requests.
  - purpose: Inbox and automations
    text: We use this data only to run the Inbox and the automations you set up — never for advertising, profiling, or training AI models
  retention:
  - period: 30 days after account deletion
    scope: Account data
    text: Retained while your account is active and for 30 days after account deletion (unless longer retention is required by law).
  - period: deleted immediately upon disconnection
    scope: OAuth tokens
    text: 'OAuth Tokens: Retained while accounts are connected and deleted immediately upon disconnection.'
  - period: 24 months
    scope: Analytics data
    text: 'Analytics Data: Retained for 24 months from the date of collection for historical analysis.'
  - period: 90 days
    scope: Automation message logs
    text: The log of comments and messages your automations received is deleted after 90 days
  - period: 7 years
    scope: Payment records
    text: 'Payment Records: Retained for 7 years as required by tax and accounting laws (managed by Polar.sh).'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Update or correct inaccurate personal information through your account settings.'
  - right: Data portability
    text: 'Data Portability: Request a machine-readable copy of your data in a structured format.'
  - right: Opt-out of marketing
    text: 'Opt-Out: Unsubscribe from marketing communications (service-related communications are required).'
  - right: Withdraw consent
    text: 'Withdraw Consent: Withdraw consent for data processing where consent is the legal basis.'
  - right: Complaint to authority
    text: 'EU/UK Residents (GDPR): You have the right to lodge a complaint with your local data protection authority if you believe we have violated your privacy rights.'
  role:
    text: 'PosteAhora is operated by Aleksandr Borisov (CUIT: 27-96484697-4), Monotributo - Régimen Simplificado para Pequeños Contribuyentes, Categoría A.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Data transfers are protected by appropriate safeguards, including Standard Contractual Clauses (SCCs) for EU/UK data transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PosteAhora
provenance_date: '2026-11-10'
provider_name: PosteAhora
provider_slug: posteahora
slug: posteahora-privacy-policy
source_date: '2026-11-10'
source_filename: posteahora-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://posteahora.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PosteAhora\naid: posteahora\nurl: https://posteahora.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'PosteAhora is operated by Aleksandr Borisov (CUIT: 27-96484697-4), Monotributo - Régimen Simplificado para\n    Pequeños Contribuyentes, Categoría A.'\ndata_categories:\n- category: identifying\n  text: Email address (required for account creation and authentication)\n- category: contact\n  text: Full name (as provided during registration)\n- category: financial\n  text: We receive payment confirmation, subscription status, and billing information (name, email, billing address)\n\
  \    from Polar.sh for account management purposes.\n- category: location\n  text: IP address and approximate location (country/region)\n- category: device\n  text: Browser type and version\n- category: behavioral\n  text: Usage patterns and feature interactions\n- category: communication\n  text: Direct messages people send to your Instagram account or Facebook Page (the text, the sender's ID and display\n    name)\n- category: other\n  text: 'OAuth Tokens: Encrypted access tokens and refresh tokens for platforms including Facebook, Instagram, TikTok,\n    YouTube, X (Twitter), LinkedIn, and Threads.'\npurposes:\n- purpose: Service delivery\n  text: To provide, maintain, and improve our social media management services.\n- purpose: Authentication\n  text: To authenticate your identity and secure access to your account.\n- purpose: Platform integration\n  text: To connect with and interact with third-party social media platforms via their APIs on your behalf.\n- purpose: Analytics and\
  \ insights\n  text: To provide you with performance analytics and insights about your content.\n- purpose: Communication\n  text: To send you service-related notifications, updates, security alerts, and support communications.\n- purpose: Legal compliance\n  text: To comply with applicable laws, regulations, legal processes, or governmental requests.\n- purpose: Inbox and automations\n  text: We use this data only to run the Inbox and the automations you set up — never for advertising, profiling,\n    or training AI models\nretention:\n- scope: Account data\n  period: 30 days after account deletion\n  text: Retained while your account is active and for 30 days after account deletion (unless longer retention is\n    required by law).\n- scope: OAuth tokens\n  period: deleted immediately upon disconnection\n  text: 'OAuth Tokens: Retained while accounts are connected and deleted immediately upon disconnection.'\n- scope: Analytics data\n  period: 24 months\n  text: 'Analytics Data: Retained\
  \ for 24 months from the date of collection for historical analysis.'\n- scope: Automation message logs\n  period: 90 days\n  text: The log of comments and messages your automations received is deleted after 90 days\n- scope: Payment records\n  period: 7 years\n  text: 'Payment Records: Retained for 7 years as required by tax and accounting laws (managed by Polar.sh).'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Data transfers are protected by appropriate safeguards, including Standard Contractual Clauses (SCCs) for\n    EU/UK data transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request via privacy@posteahora.com or account settings\n  text: 'Deletion: Request deletion of your account and associated data.'\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction: Update or correct inaccurate personal\
  \ information through your account settings.'\n- right: Data portability\n  text: 'Data Portability: Request a machine-readable copy of your data in a structured format.'\n- right: Opt-out of marketing\n  text: 'Opt-Out: Unsubscribe from marketing communications (service-related communications are required).'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Withdraw consent for data processing where consent is the legal basis.'\n- right: Complaint to authority\n  text: 'EU/UK Residents (GDPR): You have the right to lodge a complaint with your local data protection authority\n    if you believe we have violated your privacy rights.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/posteahora/privacy/posteahora-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from PosteAhora's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- AI Automation
- Marketing
- Software-as-a-Service
---
