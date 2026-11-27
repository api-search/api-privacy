---
api_specs:
- filename: aivideocheck-net-openapi-generated.yml
  format: yaml
  label: AI Video Check API
  slug: aivideocheck-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivideocheck-net/openapi/_ae-authored/aivideocheck-net-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your email address, store a hashed password
  - category: identifying
    text: your chosen display name or avatar
  - category: identifying
    text: your Google-registered email address, full name, and profile picture URL
  - category: device
    text: User-Agent, cookie, Fingerprint ID
  - category: behavioral
    text: Analytics & Advertising Cookies (Google Analytics; advertising networks, where advertising is enabled)
  - category: financial
    text: the data required to process the payment (e-mail address, amount, invoice identifiers)
  - category: other
    text: the submitted video file itself is never stored beyond the moment of analysis
  deletion:
    route: Self-service deletion in dashboard or by email to support@aivideocheck.net; completed within 7 business days
    text: You may delete your account and all associated data directly in your dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: We process your registration, authentication data, and video submissions to perform the core functionality of the Service
  - purpose: Fraud prevention
    text: We leverage technical identifiers (User-Agent, cookie, Fingerprint ID) and internal logs to identify suspicious patterns
  - purpose: Account security
    text: Your email, password hash, OAuth tokens, and session cookies enable secure login, session continuity, and protection against unauthorized access.
  residency:
  - region: Germany (Frankfurt)
    text: the database is hosted in Frankfurt, Germany (Amazon Web Services)
  - region: Finland
    text: these machines are located in Finland
  retention:
  - period: immediately after analysis
    scope: Video files
    text: 'Video files: automatically deleted immediately after analysis completion.'
  - period: null
    scope: Technical fingerprint
    text: for checks performed via a public link we may retain, for up to twenty-one (21) days, a compact technical fingerprint
  - period: 30 days
    scope: Paid single-frame previews
    text: a single frozen frame (JPEG/PNG) is stored securely on S3/MinIO for up to 30 days
  - period: null
    scope: Wrong-result link addresses
    text: is deleted after ninety (90) days
  - period: null
    scope: Manual review material and opinion
    text: deleted thirty (30) days after the opinion is delivered, or sooner at your request
  - period: null
    scope: Anonymous check device identifier
    text: That identifier is erased automatically twelve (12) months after the check
  - period: null
    scope: Account details
    text: Account details (email, password hash, OAuth tokens) are retained until you delete your account.
  rights:
  - right: Access and portability
    text: You may request a copy of all personal data we hold about you, in a structured, commonly used format.
  - right: Rectification
    text: You have the right to correct any inaccurate or incomplete personal data.
  - right: Erasure
    text: You may request deletion of your personal data and analysis history
  - right: Withdraw consent
    text: You can withdraw consent for analytics/advertising cookies at any time.
  - right: Object
    text: You may object to processing based on legitimate interests
  role:
    text: 'As Data Controller, we are responsible for:'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell or rent your personal data.
  subprocessors:
    text: 6.5. Service Providers (Sub-processors). Running the Service requires a small number of providers.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Video Check
provenance_date: '2026-11-09'
provider_name: AI Video Check
provider_slug: aivideocheck-net
slug: aivideocheck-net-privacy-policy
source_date: '2026-11-09'
source_filename: aivideocheck-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aivideocheck.net/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Video Check\naid: aivideocheck-net\nurl: https://www.aivideocheck.net/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'As Data Controller, we are responsible for:'\ndata_categories:\n- category: contact\n  text: we collect your email address, store a hashed password\n- category: identifying\n  text: your chosen display name or avatar\n- category: identifying\n  text: your Google-registered email address, full name, and profile picture URL\n- category: device\n  text: User-Agent, cookie, Fingerprint ID\n- category: behavioral\n  text: Analytics & Advertising Cookies (Google\
  \ Analytics; advertising networks, where advertising is enabled)\n- category: financial\n  text: the data required to process the payment (e-mail address, amount, invoice identifiers)\n- category: other\n  text: the submitted video file itself is never stored beyond the moment of analysis\npurposes:\n- purpose: Service delivery\n  text: We process your registration, authentication data, and video submissions to perform the core functionality\n    of the Service\n- purpose: Fraud prevention\n  text: We leverage technical identifiers (User-Agent, cookie, Fingerprint ID) and internal logs to identify suspicious\n    patterns\n- purpose: Account security\n  text: Your email, password hash, OAuth tokens, and session cookies enable secure login, session continuity, and\n    protection against unauthorized access.\nretention:\n- scope: Video files\n  period: immediately after analysis\n  text: 'Video files: automatically deleted immediately after analysis completion.'\n- scope: Technical fingerprint\n\
  \  period: null\n  text: for checks performed via a public link we may retain, for up to twenty-one (21) days, a compact technical\n    fingerprint\n- scope: Paid single-frame previews\n  period: 30 days\n  text: a single frozen frame (JPEG/PNG) is stored securely on S3/MinIO for up to 30 days\n- scope: Wrong-result link addresses\n  period: null\n  text: is deleted after ninety (90) days\n- scope: Manual review material and opinion\n  period: null\n  text: deleted thirty (30) days after the opinion is delivered, or sooner at your request\n- scope: Anonymous check device identifier\n  period: null\n  text: That identifier is erased automatically twelve (12) months after the check\n- scope: Account details\n  period: null\n  text: Account details (email, password hash, OAuth tokens) are retained until you delete your account.\nresidency:\n- region: Germany (Frankfurt)\n  text: the database is hosted in Frankfurt, Germany (Amazon Web Services)\n- region: Finland\n  text: these machines are\
  \ located in Finland\ntransfers: []\nsubprocessors:\n  url: null\n  text: 6.5. Service Providers (Sub-processors). Running the Service requires a small number of providers.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service deletion in dashboard or by email to support@aivideocheck.net; completed within 7 business\n    days\n  text: You may delete your account and all associated data directly in your dashboard.\nrights:\n- right: Access and portability\n  text: You may request a copy of all personal data we hold about you, in a structured, commonly used format.\n- right: Rectification\n  text: You have the right to correct any inaccurate or incomplete personal data.\n- right: Erasure\n  text: You may request deletion of your personal data and analysis history\n- right: Withdraw consent\n  text: You can withdraw consent for analytics/advertising cookies at any time.\n- right: Object\n  text: You may object to processing based on legitimate interests\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We never sell or rent your personal data.\n"
source_yaml_url: https://artifacts.apis.io/aivideocheck-net/privacy/aivideocheck-net-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AI Video Check's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Detection
- Ukrainian
- Services
---
