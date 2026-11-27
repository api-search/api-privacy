---
api_specs:
- filename: alterauth-com-openapi-generated.yml
  format: yaml
  label: Alter API
  slug: alterauth-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alterauth-com/openapi/_ae-authored/alterauth-com-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact data , such as your first and last name, email address, professional title, and company name.
  - category: identifying
    text: Account and profile data , such as the username and password you set to establish an account (we store only a salted, one-way hash of your password)
  - category: financial
    text: Billing and payment data , such as your billing contact and the plan, invoices, and the last four digits and brand of a payment card.
  - category: communication
    text: Communications data based on our exchanges with you, including when you contact support or sales.
  - category: behavioral
    text: Usage and audit data , such as records of API calls and lifecycle events, including the action taken, timestamps, the calling agent/application and actor identifiers
  - category: device
    text: Device and log data , such as browser type and version, device and operating-system information, pages viewed, referrer, approximate location derived from IP address
  deletion:
    route: Contact Alter by email or account closure request
    text: To close your account, please contact us.
  dpa:
    available: true
    text: Alter’s obligations are set out in the Data Processing Agreement.
    url: null
  purposes:
  - purpose: Service delivery and operations
    text: To provide the Service (including storing and refreshing Credentials and enforcing Grants and policies), establish and maintain your account
  - purpose: Service improvement and analytics
    text: To analyze your use of the Service, understand user activity, diagnose errors, improve performance, and develop new features.
  - purpose: Security, fraud prevention, and audit
    text: To authenticate users, protect against fraud, abuse, and security incidents, and create audit logs for security, compliance, and traceability.
  - purpose: Direct marketing
    text: We may send business customers and contacts direct marketing communications about Alter products and features, and may personalize those messages
  - purpose: Compliance and protection
    text: To comply with applicable laws, lawful requests, and legal process
  residency:
  - region: United States
    text: We are headquartered in the United States and may use service providers that operate in other countries
  retention:
  - period: for the life of your account
    scope: Account and billing data
    text: account and billing data are retained for the life of your account and as required afterward for tax, accounting, and legal purposes
  - period: null
    scope: Credentials and Grants
    text: Credentials and Grants are retained until you or your End User revokes them or the associated resource is deleted, after which Credentials are deleted from the vault without a recovery window
  - period: 30 days
    scope: Diagnostic payload capture
    text: When enabled, Alter retains copies of Provider request and response bodies (each capped at 64 KB, with larger content stored truncated and flagged) and deletes them after 30 days.
  - period: backup rotation schedule
    scope: Backups
    text: Data in backups is isolated from ordinary use and deleted on the backup rotation schedule.
  rights:
  - right: Access and correction
    text: Subject to applicable law, you may request access to, and correction, deletion, or a portable copy of, your personal information
  - right: Restrict or object
    text: restrict or object to certain processing (including processing based on legitimate interests and processing for direct marketing)
  - right: Withdraw consent
    text: and withdraw consent.
  - right: Opt out of marketing
    text: You may opt out of marketing-related emails using the unsubscribe instructions in the email or by contacting us
  role:
    text: As a controller , Alter decides how and why to process information about its own account holders and website visitors
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, do not “share” it for cross-context behavioral advertising, and do not use Credentials, Connected-Account contents, captured request bodies, or Customer Data to create advertising profiles.
  subprocessors:
    text: Our current sub-processors are listed on our Subprocessor page .
    url: null
  transfers:
  - mechanism: SCC
    text: Where we transfer personal data out of Europe to a country without an adequacy decision, we use appropriate safeguards — for example, the European Commission’s Standard Contractual Clauses and the UK Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alter
provenance_date: '2026-11-09'
provider_name: Alter
provider_slug: alterauth-com
slug: alterauth-com-privacy-policy
source_date: '2026-11-09'
source_filename: alterauth-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alterauth.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alter\naid: alterauth-com\nurl: https://alterauth.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a controller , Alter decides how and why to process information about its own account holders and website\n    visitors\ndata_categories:\n- category: contact\n  text: Contact data , such as your first and last name, email address, professional title, and company name.\n- category: identifying\n  text: Account and profile data , such as the username and password you set to establish an account (we store only\n    a salted, one-way hash of your password)\n- category: financial\n\
  \  text: Billing and payment data , such as your billing contact and the plan, invoices, and the last four digits\n    and brand of a payment card.\n- category: communication\n  text: Communications data based on our exchanges with you, including when you contact support or sales.\n- category: behavioral\n  text: Usage and audit data , such as records of API calls and lifecycle events, including the action taken, timestamps,\n    the calling agent/application and actor identifiers\n- category: device\n  text: Device and log data , such as browser type and version, device and operating-system information, pages viewed,\n    referrer, approximate location derived from IP address\npurposes:\n- purpose: Service delivery and operations\n  text: To provide the Service (including storing and refreshing Credentials and enforcing Grants and policies),\n    establish and maintain your account\n- purpose: Service improvement and analytics\n  text: To analyze your use of the Service, understand user\
  \ activity, diagnose errors, improve performance, and\n    develop new features.\n- purpose: Security, fraud prevention, and audit\n  text: To authenticate users, protect against fraud, abuse, and security incidents, and create audit logs for security,\n    compliance, and traceability.\n- purpose: Direct marketing\n  text: We may send business customers and contacts direct marketing communications about Alter products and features,\n    and may personalize those messages\n- purpose: Compliance and protection\n  text: To comply with applicable laws, lawful requests, and legal process\nretention:\n- scope: Account and billing data\n  period: for the life of your account\n  text: account and billing data are retained for the life of your account and as required afterward for tax, accounting,\n    and legal purposes\n- scope: Credentials and Grants\n  period: null\n  text: Credentials and Grants are retained until you or your End User revokes them or the associated resource is\n    deleted,\
  \ after which Credentials are deleted from the vault without a recovery window\n- scope: Diagnostic payload capture\n  period: 30 days\n  text: When enabled, Alter retains copies of Provider request and response bodies (each capped at 64 KB, with larger\n    content stored truncated and flagged) and deletes them after 30 days.\n- scope: Backups\n  period: backup rotation schedule\n  text: Data in backups is isolated from ordinary use and deleted on the backup rotation schedule.\nresidency:\n- region: United States\n  text: We are headquartered in the United States and may use service providers that operate in other countries\ntransfers:\n- mechanism: SCC\n  text: Where we transfer personal data out of Europe to a country without an adequacy decision, we use appropriate\n    safeguards — for example, the European Commission’s Standard Contractual Clauses and the UK Addendum\nsubprocessors:\n  url: null\n  text: Our current sub-processors are listed on our Subprocessor page .\ndpa:\n  available:\
  \ true\n  url: null\n  text: Alter’s obligations are set out in the Data Processing Agreement.\ndeletion:\n  route: Contact Alter by email or account closure request\n  text: To close your account, please contact us.\nrights:\n- right: Access and correction\n  text: Subject to applicable law, you may request access to, and correction, deletion, or a portable copy of, your\n    personal information\n- right: Restrict or object\n  text: restrict or object to certain processing (including processing based on legitimate interests and processing\n    for direct marketing)\n- right: Withdraw consent\n  text: and withdraw consent.\n- right: Opt out of marketing\n  text: You may opt out of marketing-related emails using the unsubscribe instructions in the email or by contacting\n    us\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, do not “share” it for cross-context behavioral advertising, and do\n    not use Credentials, Connected-Account contents, captured\
  \ request bodies, or Customer Data to create advertising\n    profiles.\n"
source_yaml_url: https://artifacts.apis.io/alterauth-com/privacy/alterauth-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Alter's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Artificial Intelligence
- Privileged Access Management
- Identity and Access Management
- Privileged
---
