---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (used for authentication, communications, and account recovery).
  - category: identifying
    text: Name, if provided during registration.
  - category: financial
    text: Saved wallet addresses and labels, scan requests and results
  - category: location
    text: IP address, browser type, and device information (collected via server logs).
  - category: device
    text: Session data and authentication tokens.
  - category: professional
    text: The company's display name, and its QuickBooks company identifier (realm ID), which is stored encrypted.
  - category: financial
    text: Scan Results (token balances, USD valuations, verification metadata).
  deletion:
    route: Email jono@asof.xyz to request deletion
    text: Account closure and data deletion currently require a request to jono@asof.xyz.
  dpa:
    available: true
    text: These providers process data under their own data processing agreements.
    url: null
  purposes:
  - purpose: Service provision
    text: Account data, workspace data, and scan data — necessary to provide and manage the service.
  - purpose: Security and service improvement
    text: Technical data — for security, debugging, and service improvement.
  - purpose: Communications
    text: Communications — for service updates and support.
  residency:
  - region: United Kingdom
    text: Google Cloud (hosting of the AsOf Accounting service, in London)
  retention:
  - period: 12 months
    scope: Technical logs
    text: 'Technical logs: Retained for a maximum of 12 months.'
  - period: null
    scope: Account data
    text: 'Account data: Kept while your account is in use.'
  - period: null
    scope: Scan Results
    text: 'Scan Results: Kept for retrieval while your account is in use.'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate or incomplete data.'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data (subject to legal retention obligations).'
  - right: Restriction
    text: 'Restriction: Request that we restrict processing in certain circumstances.'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests.'
  - right: Withdraw consent
    text: 'Withdraw consent: Where processing is based on consent, withdraw at any time.'
  role:
    text: AsOf is the data controller for personal data processed through the platform.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: They include Google Cloud (hosting of the AsOf Accounting service, in London), Supabase (database and authentication), and Vercel (website hosting).
    url: null
  transfers:
  - mechanism: SCC
    text: including Standard Contractual Clauses (SCCs) or adequacy decisions, as required under UK GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: asof-xyz
provenance_date: '2026-11-09'
provider_name: asof-xyz
provider_slug: asof-xyz
slug: asof-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: asof-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asof.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: asof-xyz\naid: asof-xyz\nurl: https://asof.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AsOf is the data controller for personal data processed through the platform.\ndata_categories:\n- category: identifying\n  text: Email address (used for authentication, communications, and account recovery).\n- category: identifying\n  text: Name, if provided during registration.\n- category: financial\n  text: Saved wallet addresses and labels, scan requests and results\n- category: location\n  text: IP address, browser type, and device information (collected via server logs).\n- category:\
  \ device\n  text: Session data and authentication tokens.\n- category: professional\n  text: The company's display name, and its QuickBooks company identifier (realm ID), which is stored encrypted.\n- category: financial\n  text: Scan Results (token balances, USD valuations, verification metadata).\npurposes:\n- purpose: Service provision\n  text: Account data, workspace data, and scan data — necessary to provide and manage the service.\n- purpose: Security and service improvement\n  text: Technical data — for security, debugging, and service improvement.\n- purpose: Communications\n  text: Communications — for service updates and support.\nretention:\n- scope: Technical logs\n  period: 12 months\n  text: 'Technical logs: Retained for a maximum of 12 months.'\n- scope: Account data\n  period: null\n  text: 'Account data: Kept while your account is in use.'\n- scope: Scan Results\n  period: null\n  text: 'Scan Results: Kept for retrieval while your account is in use.'\nresidency:\n- region:\
  \ United Kingdom\n  text: Google Cloud (hosting of the AsOf Accounting service, in London)\ntransfers:\n- mechanism: SCC\n  text: including Standard Contractual Clauses (SCCs) or adequacy decisions, as required under UK GDPR.\nsubprocessors:\n  url: null\n  text: They include Google Cloud (hosting of the AsOf Accounting service, in London), Supabase (database and authentication),\n    and Vercel (website hosting).\ndpa:\n  available: true\n  url: null\n  text: These providers process data under their own data processing agreements.\ndeletion:\n  route: Email jono@asof.xyz to request deletion\n  text: Account closure and data deletion currently require a request to jono@asof.xyz.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data (subject to legal retention obligations).'\n\
  - right: Restriction\n  text: 'Restriction: Request that we restrict processing in certain circumstances.'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests.'\n- right: Withdraw consent\n  text: 'Withdraw consent: Where processing is based on consent, withdraw at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/asof-xyz/privacy/asof-xyz-privacy-policy.yml
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
summary_line: 27 quoted statements, read from asof-xyz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Cryptocurrency
- Wallets
- Analytics
---
