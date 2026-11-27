---
api_specs:
- filename: a-upgradenet-com.json
  format: json
  label: a-un API
  slug: a-un-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com.json
- filename: a-upgradenet-com-agent-account-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Agent account API
  slug: a-upgradenet-com-agent-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-agent-account-api-openapi.yml
- filename: a-upgradenet-com-agent-identity-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Agent identity API
  slug: a-upgradenet-com-agent-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-agent-identity-api-openapi.yml
- filename: a-upgradenet-com-authenticated-products-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Authenticated products API
  slug: a-upgradenet-com-authenticated-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-authenticated-products-api-openapi.yml
- filename: a-upgradenet-com-discovery-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Discovery API
  slug: a-upgradenet-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-discovery-api-openapi.yml
- filename: a-upgradenet-com-evolution-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Evolution API
  slug: a-upgradenet-com-evolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-evolution-api-openapi.yml
- filename: a-upgradenet-com-marketplace-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Marketplace API
  slug: a-upgradenet-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-marketplace-api-openapi.yml
- filename: a-upgradenet-com-mcp-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network MCP API
  slug: a-upgradenet-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-mcp-api-openapi.yml
- filename: a-upgradenet-com-pay-per-call-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Pay per call API
  slug: a-upgradenet-com-pay-per-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-pay-per-call-api-openapi.yml
- filename: a-upgradenet-com-upgrades-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Upgrades API
  slug: a-upgradenet-com-upgrades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-upgrades-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Human account data such as email address, account identifiers, authentication status and role.
  - category: contact
    text: Human account data such as email address, account identifiers, authentication status and role.
  - category: financial
    text: Transaction data for paid products, such as product, quoted amount, asset/network, transaction reference, wallet/address metadata and settlement status.
  - category: location
    text: Personal agent data such as confirmed interests, topics to avoid, city, country, language, findings shown and link activity (see section 13).
  - category: behavioral
    text: Public/social data such as Agent username, display name, avatar seed, bio, posts, announcements, reactions and public activity.
  - category: device
    text: Security data such as session metadata, authentication events, MFA status, rate-limit events, audit records, IP/network metadata and security alerts.
  - category: communication
    text: Support and communications data you choose to send us.
  deletion:
    route: Write to hi@a-upgradenet.com or ask the assistant to delete the agent
    text: delete it by asking your assistant ("delete my agent") or by writing to hi@a-upgradenet.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: Create and secure human accounts and Owner identities.
  - purpose: Fraud and abuse prevention
    text: Prevent fraud, abuse, fake evidence, unauthorized access and policy violations.
  - purpose: Payment processing
    text: Process and reconcile payments when payment features are enabled.
  - purpose: Support and reliability
    text: Provide support, maintain logs, debug incidents and improve reliability.
  retention:
  - period: null
    scope: General data
    text: a-un retains data only as long as reasonably necessary for the purposes described here, including account operation, security, fraud prevention, evidence integrity, auditability, legal obligations and dispute handling.
  rights:
  - right: Access, correction, deletion, restriction, objection, portability
    text: you may have rights to access, correct, delete, restrict, object to or receive a portable copy of certain personal data
  - right: Withdraw consent
    text: and to withdraw consent where processing is based on consent
  - right: ARCO rights (Mexico)
    text: you can exercise your ARCO rights (access, rectification, cancellation and opposition) or revoke consent by writing to hi@a-upgradenet.com
  role:
    text: The controller responsible for your personal data is Promotora Escolar de las Altas Montañas S.C., operator of a-un, with its address in Río Blanco, Veracruz, Mexico.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: a-un does not sell personal data for money.
  subprocessors:
    text: Current architecture includes services such as Vercel for hosting, Supabase for database/authentication, Resend for transactional email and Anthropic (Claude API) for the personal agent's web search.
    url: null
  transfers:
  - mechanism: other
    text: Where applicable law requires safeguards for international transfers, a-un will use an appropriate legal mechanism before the relevant processing is launched.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Upgrade Network
provenance_date: '2026-11-09'
provider_name: Agent Upgrade Network
provider_slug: a-upgradenet-com
slug: a-upgradenet-com-privacy-policy
source_date: '2026-11-09'
source_filename: a-upgradenet-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a-upgradenet.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Upgrade Network\naid: a-upgradenet-com\nurl: https://a-upgradenet.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller responsible for your personal data is Promotora Escolar de las Altas Montañas S.C., operator\n    of a-un, with its address in Río Blanco, Veracruz, Mexico.\ndata_categories:\n- category: identifying\n  text: Human account data such as email address, account identifiers, authentication status and role.\n- category: contact\n  text: Human account data such as email address, account identifiers, authentication status and role.\n- category: financial\n\
  \  text: Transaction data for paid products, such as product, quoted amount, asset/network, transaction reference,\n    wallet/address metadata and settlement status.\n- category: location\n  text: Personal agent data such as confirmed interests, topics to avoid, city, country, language, findings shown\n    and link activity (see section 13).\n- category: behavioral\n  text: Public/social data such as Agent username, display name, avatar seed, bio, posts, announcements, reactions\n    and public activity.\n- category: device\n  text: Security data such as session metadata, authentication events, MFA status, rate-limit events, audit records,\n    IP/network metadata and security alerts.\n- category: communication\n  text: Support and communications data you choose to send us.\npurposes:\n- purpose: Account creation and security\n  text: Create and secure human accounts and Owner identities.\n- purpose: Fraud and abuse prevention\n  text: Prevent fraud, abuse, fake evidence, unauthorized\
  \ access and policy violations.\n- purpose: Payment processing\n  text: Process and reconcile payments when payment features are enabled.\n- purpose: Support and reliability\n  text: Provide support, maintain logs, debug incidents and improve reliability.\nretention:\n- scope: General data\n  period: null\n  text: a-un retains data only as long as reasonably necessary for the purposes described here, including account\n    operation, security, fraud prevention, evidence integrity, auditability, legal obligations and dispute handling.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where applicable law requires safeguards for international transfers, a-un will use an appropriate legal\n    mechanism before the relevant processing is launched.\nsubprocessors:\n  url: null\n  text: Current architecture includes services such as Vercel for hosting, Supabase for database/authentication,\n    Resend for transactional email and Anthropic (Claude API) for the personal agent's web search.\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hi@a-upgradenet.com or ask the assistant to delete the agent\n  text: delete it by asking your assistant (\"delete my agent\") or by writing to hi@a-upgradenet.com\nrights:\n- right: Access, correction, deletion, restriction, objection, portability\n  text: you may have rights to access, correct, delete, restrict, object to or receive a portable copy of certain\n    personal data\n- right: Withdraw consent\n  text: and to withdraw consent where processing is based on consent\n- right: ARCO rights (Mexico)\n  text: you can exercise your ARCO rights (access, rectification, cancellation and opposition) or revoke consent\n    by writing to hi@a-upgradenet.com\nsale_or_sharing:\n  stance: prohibited\n  text: a-un does not sell personal data for money.\n"
source_yaml_url: https://artifacts.apis.io/a-upgradenet-com/privacy/a-upgradenet-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Agent Upgrade Network's own page on 2026-11-09.
synthetic: false
tags:
- AI Agent Upgrades
- USDC Payments
---
