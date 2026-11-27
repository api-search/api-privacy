---
api_specs:
- filename: whisper-online-a2a-api-openapi.yml
  format: yaml
  label: Whisper Security A2a API
  slug: whisper-online-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-a2a-api-openapi.yml
- filename: whisper-online-checkpoint-api-openapi.yml
  format: yaml
  label: Whisper Security Checkpoint API
  slug: whisper-online-checkpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-checkpoint-api-openapi.yml
- filename: whisper-online-consistency-api-openapi.yml
  format: yaml
  label: Whisper Security Consistency API
  slug: whisper-online-consistency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-consistency-api-openapi.yml
- filename: whisper-online-inclusion-api-openapi.yml
  format: yaml
  label: Whisper Security Inclusion API
  slug: whisper-online-inclusion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-inclusion-api-openapi.yml
- filename: whisper-online-menu-api-openapi.yml
  format: yaml
  label: Whisper Security Menu API
  slug: whisper-online-menu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-menu-api-openapi.yml
- filename: whisper-online-query-api-openapi.yml
  format: yaml
  label: Whisper Security Query API
  slug: whisper-online-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-query-api-openapi.yml
- filename: whisper-online-tile-api-openapi.yml
  format: yaml
  label: Whisper Security Tile API
  slug: whisper-online-tile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-tile-api-openapi.yml
- filename: whisper-online-verify-identity-api-openapi.yml
  format: yaml
  label: Whisper Security Verify Identity API
  slug: whisper-online-verify-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-verify-identity-api-openapi.yml
- filename: whisper-online-well-known-api-openapi.yml
  format: yaml
  label: Whisper Security .well Known API
  slug: whisper-online-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whisper-online/openapi/whisper-online-well-known-api-openapi.yml
claim_count: 44
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact and account details - your email address, and any organization name you provide.
  - category: identifying
    text: Credentials - the API keys issued to your account, and metadata about their use (creation time, scopes, last use).
  - category: financial
    text: 'Billing details - if you buy a paid plan: the information needed to invoice you.'
  - category: communication
    text: DNS query logs - the names queried, query type, timestamp, the answer given (including any policy decision), and the source address the query came from.
  - category: location
    text: 'Egress connection metadata - for agents that route traffic through the Service: connection timestamps, source and destination addresses and ports, and volume.'
  - category: device
    text: TLS fingerprint samples - sampled TLS handshake fingerprints, used for abuse detection and service protection.
  - category: device
    text: Technical data - IP address, browser type, and pages visited, as part of ordinary web-server operation.
  - category: identifying
    source: https://www.whisper.security/privacy-policy
    text: we collect your name and email address, any sign-in provider's identifier, billing details
  - category: contact
    source: https://www.whisper.security/privacy-policy
    text: names, email and postal addresses and telephone numbers of people recorded as contacts in domain-registration records
  - category: device
    source: https://www.whisper.security/privacy-policy
    text: We also record your IP address and user-agent string
  - category: financial
    source: https://www.whisper.security/privacy-policy
    text: billing details
  - category: communication
    source: https://www.whisper.security/privacy-policy
    text: your enquiries and attachments
  - category: location
    source: https://www.whisper.security/privacy-policy
    text: city-level geolocation inferred from an IP address
  deletion:
    route: request by email to privacy@whisper.security
    source: https://www.whisper.security/privacy-policy
    text: Write to privacy@whisper.security to exercise any of them.
  dpa:
    available: null
    text: Infrastructure sub-processors - hosting and network providers that run the servers the Service operates on, bound by data-processing agreements.
    url: null
  purposes:
  - purpose: Operate and provide the Service
    text: To operate and provide the Service - resolve DNS queries, allocate and publish agent identities, route egress traffic, apply the policies you configure, and show you your own logs.
  - purpose: Security and abuse prevention
    text: Security and abuse prevention - detect, investigate, and stop abuse of the Service or of the internet from our network, and protect the Service against attacks.
  - purpose: Billing
    text: Billing - invoice and administer paid accounts.
  - purpose: Legal compliance
    text: Legal compliance - meet obligations we are subject to, including responding to lawful requests from competent authorities.
  - purpose: Product improvement
    text: Product improvement - understand, in aggregate, how the Service is used, so we can improve it.
  - purpose: provide, maintain and improve the Services
    source: https://www.whisper.security/privacy-policy
    text: We process personal data to provide, maintain and improve the Services
  - purpose: investigate incidents and abuse
    source: https://www.whisper.security/privacy-policy
    text: investigate incidents, abuse and security events
  residency:
  - region: European Union
    text: The Service is operated from the European Union, and we keep processing in the EU where we can.
  retention:
  - period: defined, limited retention period
    scope: Service logs
    text: Service logs (DNS queries, egress metadata, TLS fingerprint samples) are kept for a defined, limited retention period for the purposes above, and then deleted automatically.
  - period: lifetime of your account
    scope: Account data
    text: Account data is kept for the lifetime of your account, and after closure only as long as legal minimums (such as invoice retention rules) require.
  - period: up to 90 days
    scope: operational and audit logs
    source: https://www.whisper.security/privacy-policy
    text: 'Operational and audit logs: generally up to 90 days'
  - period: up to 12 months
    scope: query history
    source: https://www.whisper.security/privacy-policy
    text: 'query history behind your usage dashboard: up to 12 months'
  - period: no longer than 26 months
    scope: website analytics and visitor identification
    source: https://www.whisper.security/privacy-policy
    text: by us for no longer than 26 months
  rights:
  - right: Access
    text: Access the personal data we hold about you (Art. 15)
  - right: Rectify
    text: Rectify inaccurate data (Art. 16)
  - right: Erase
    text: Erase your data (Art. 17) - including the crypto-shred mechanism for transparency-log entries described in section 6
  - right: Restrict processing
    text: Restrict processing (Art. 18)
  - right: Portability
    text: Receive your data in a portable format (Art. 20)
  - right: Object
    text: Object to processing based on legitimate interests (Art. 21)
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting processing before withdrawal.
  - right: access, rectification, erasure, restriction, portability and objection
    source: https://www.whisper.security/privacy-policy
    text: including access, rectification, erasure, restriction, portability and objection
  - right: withdraw consent
    source: https://www.whisper.security/privacy-policy
    text: You may withdraw consent at any time without affecting earlier processing.
  role:
    text: For the personal data described in this policy, viaGraph B.V. is the data controller within the meaning of the EU General Data Protection Regulation (GDPR).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Infrastructure sub-processors - hosting and network providers that run the servers the Service operates on, bound by data-processing agreements.
    url: null
  transfers:
  - mechanism: adequacy
    text: an adequacy decision where one exists
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    source: https://www.whisper.security/privacy-policy
    text: we rely primarily on the Standard Contractual Clauses (Implementing Decision (EU) 2021/914)
  - mechanism: other
    source: https://www.whisper.security/privacy-policy
    text: for the United Kingdom and Switzerland, the UK International Data Transfer Addendum and the Swiss-recognized Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Whisper Security
provenance_date: '2026-11-10'
provider_name: Whisper Security
provider_slug: whisper-online
slug: whisper-online-privacy-policy
source_date: '2026-11-10'
source_filename: whisper-online-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://whisper.online/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Whisper Security\naid: whisper-online\nurl: https://whisper.online/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://whisper.online/privacy\n  - https://www.whisper.security/privacy-policy\nrole:\n  value: controller\n  text: For the personal data described in this policy, viaGraph B.V. is the data controller within the meaning\n    of the EU General Data Protection Regulation (GDPR).\ndata_categories:\n- category: contact\n  text: Contact and account details - your email address, and any organization name you provide.\n- category: identifying\n  text: Credentials - the API keys issued to your account,\
  \ and metadata about their use (creation time, scopes,\n    last use).\n- category: financial\n  text: 'Billing details - if you buy a paid plan: the information needed to invoice you.'\n- category: communication\n  text: DNS query logs - the names queried, query type, timestamp, the answer given (including any policy decision),\n    and the source address the query came from.\n- category: location\n  text: 'Egress connection metadata - for agents that route traffic through the Service: connection timestamps,\n    source and destination addresses and ports, and volume.'\n- category: device\n  text: TLS fingerprint samples - sampled TLS handshake fingerprints, used for abuse detection and service protection.\n- category: device\n  text: Technical data - IP address, browser type, and pages visited, as part of ordinary web-server operation.\n- category: identifying\n  text: we collect your name and email address, any sign-in provider's identifier, billing details\n  source: https://www.whisper.security/privacy-policy\n\
  - category: contact\n  text: names, email and postal addresses and telephone numbers of people recorded as contacts in domain-registration\n    records\n  source: https://www.whisper.security/privacy-policy\n- category: device\n  text: We also record your IP address and user-agent string\n  source: https://www.whisper.security/privacy-policy\n- category: financial\n  text: billing details\n  source: https://www.whisper.security/privacy-policy\n- category: communication\n  text: your enquiries and attachments\n  source: https://www.whisper.security/privacy-policy\n- category: location\n  text: city-level geolocation inferred from an IP address\n  source: https://www.whisper.security/privacy-policy\npurposes:\n- purpose: Operate and provide the Service\n  text: To operate and provide the Service - resolve DNS queries, allocate and publish agent identities, route egress\n    traffic, apply the policies you configure, and show you your own logs.\n- purpose: Security and abuse prevention\n\
  \  text: Security and abuse prevention - detect, investigate, and stop abuse of the Service or of the internet from\n    our network, and protect the Service against attacks.\n- purpose: Billing\n  text: Billing - invoice and administer paid accounts.\n- purpose: Legal compliance\n  text: Legal compliance - meet obligations we are subject to, including responding to lawful requests from competent\n    authorities.\n- purpose: Product improvement\n  text: Product improvement - understand, in aggregate, how the Service is used, so we can improve it.\n- purpose: provide, maintain and improve the Services\n  text: We process personal data to provide, maintain and improve the Services\n  source: https://www.whisper.security/privacy-policy\n- purpose: investigate incidents and abuse\n  text: investigate incidents, abuse and security events\n  source: https://www.whisper.security/privacy-policy\nretention:\n- scope: Service logs\n  period: defined, limited retention period\n  text: Service logs\
  \ (DNS queries, egress metadata, TLS fingerprint samples) are kept for a defined, limited retention\n    period for the purposes above, and then deleted automatically.\n- scope: Account data\n  period: lifetime of your account\n  text: Account data is kept for the lifetime of your account, and after closure only as long as legal minimums\n    (such as invoice retention rules) require.\n- scope: operational and audit logs\n  period: up to 90 days\n  text: 'Operational and audit logs: generally up to 90 days'\n  source: https://www.whisper.security/privacy-policy\n- scope: query history\n  period: up to 12 months\n  text: 'query history behind your usage dashboard: up to 12 months'\n  source: https://www.whisper.security/privacy-policy\n- scope: website analytics and visitor identification\n  period: no longer than 26 months\n  text: by us for no longer than 26 months\n  source: https://www.whisper.security/privacy-policy\nresidency:\n- region: European Union\n  text: The Service is operated\
  \ from the European Union, and we keep processing in the EU where we can.\ntransfers:\n- mechanism: adequacy\n  text: an adequacy decision where one exists\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses.\n- mechanism: SCC\n  text: we rely primarily on the Standard Contractual Clauses (Implementing Decision (EU) 2021/914)\n  source: https://www.whisper.security/privacy-policy\n- mechanism: other\n  text: for the United Kingdom and Switzerland, the UK International Data Transfer Addendum and the Swiss-recognized\n    Clauses\n  source: https://www.whisper.security/privacy-policy\nsubprocessors:\n  url: null\n  text: Infrastructure sub-processors - hosting and network providers that run the servers the Service operates\n    on, bound by data-processing agreements.\ndpa:\n  available: null\n  url: null\n  text: Infrastructure sub-processors - hosting and network providers that run the servers the Service operates\n    on, bound by data-processing agreements.\n\
  deletion:\n  route: request by email to privacy@whisper.security\n  text: Write to privacy@whisper.security to exercise any of them.\n  source: https://www.whisper.security/privacy-policy\nrights:\n- right: Access\n  text: Access the personal data we hold about you (Art. 15)\n- right: Rectify\n  text: Rectify inaccurate data (Art. 16)\n- right: Erase\n  text: Erase your data (Art. 17) - including the crypto-shred mechanism for transparency-log entries described\n    in section 6\n- right: Restrict processing\n  text: Restrict processing (Art. 18)\n- right: Portability\n  text: Receive your data in a portable format (Art. 20)\n- right: Object\n  text: Object to processing based on legitimate interests (Art. 21)\n- right: Withdraw consent\n  text: Withdraw consent at any time, without affecting processing before withdrawal.\n- right: access, rectification, erasure, restriction, portability and objection\n  text: including access, rectification, erasure, restriction, portability and objection\n\
  \  source: https://www.whisper.security/privacy-policy\n- right: withdraw consent\n  text: You may withdraw consent at any time without affecting earlier processing.\n  source: https://www.whisper.security/privacy-policy\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/whisper-online/privacy/whisper-online-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 44 quoted statements, read from Whisper Security's own page on 2026-11-10.
synthetic: false
tags:
- Agent Identity
- Agents
- IPv6
- DNS
- DNSSEC
- Threat Intelligence
- Security
- Egress
- A2A
- MCP
- RDAP
- Transparency Log
- Graph Database
- Agent-Native
- Netherlands
---
