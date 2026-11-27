---
api_specs:
- filename: codecombat-auth-api-openapi.yml
  format: yaml
  label: CodeCombat Auth API
  slug: codecombat-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codecombat/openapi/codecombat-auth-api-openapi.yml
- filename: codecombat-clans-api-openapi.yml
  format: yaml
  label: CodeCombat Clans API
  slug: codecombat-clans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codecombat/openapi/codecombat-clans-api-openapi.yml
- filename: codecombat-classrooms-api-openapi.yml
  format: yaml
  label: CodeCombat Classrooms API
  slug: codecombat-classrooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codecombat/openapi/codecombat-classrooms-api-openapi.yml
- filename: codecombat-stats-api-openapi.yml
  format: yaml
  label: CodeCombat Stats API
  slug: codecombat-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codecombat/openapi/codecombat-stats-api-openapi.yml
- filename: codecombat-users-api-openapi.yml
  format: yaml
  label: CodeCombat Users API
  slug: codecombat-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codecombat/openapi/codecombat-users-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Email address
  - category: demographic
    text: Year and month of birth (without specific day)
  - category: location
    text: Country and region location information (without specific address or fine-grained location)
  - category: financial
    text: CodeCombat purchase history
  - category: device
    text: IP addresses
  - category: behavioral
    text: Web and email usage data
  deletion:
    route: Delete Your Account section in account settings
    text: To delete your account and all personal data relating to your account, go to https://codecombat.com/account/settings and scroll down to the section Delete Your Account .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and rostering
    text: To provide authentication and rostering features.
  - purpose: Personalize experience
    text: To personalize your experience.
  - purpose: Improve website
    text: To improve our website.
  - purpose: Customer service
    text: To respond to your customer service requests.
  - purpose: Licensing and sales
    text: To assist with district-wide licensing.
  residency:
  - region: United States
    text: EU users' personal data are processed on US-based CodeCombat servers and at CodeCombat's San Francisco office.
  retention:
  - period: 30 days
    scope: Server log files
    text: CodeCombat will retain server log files for no more than 30 days
  - period: 2 years
    scope: Inactive, unpaid EU user accounts
    text: will retain inactive, unpaid EU user accounts for no more than 2 years
  rights:
  - right: Access
    text: Access their personal data.
  - right: Rectification
    text: Verify and seek rectification.
  - right: Erasure
    text: Have their personal data deleted or otherwise removed.
  - right: Restriction
    text: Restrict the processing of their personal data.
  - right: Portability
    text: Receive their personal data and have data transferred to another controller.
  - right: Objection
    text: Object to processing of their personal data.
  - right: Withdraw consent
    text: Withdraw their consent at any time.
  - right: Complain
    text: Lodge a complaint.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or trade to outside parties your personally identifiable information, and do not otherwise transfer it except as described in this privacy notice.
  subprocessors:
    text: CodeCombat is assisted by the following GDPR-compliant data processors and data controllers
    url: null
  transfers:
  - mechanism: SCC
    text: Privacy Policy Standard Contractual Clauses
  - mechanism: other
    text: As CodeCombat does not yet have the Privacy Shield certification necessary to ensure adequacy, EU users may either explicitly consent to such a transfer or refrain from granting CodeCombat consent while creating a CodeCombat account.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CodeCombat
provenance_date: '2026-11-09'
provider_name: CodeCombat
provider_slug: codecombat
slug: codecombat-privacy-policy
source_date: '2026-11-09'
source_filename: codecombat-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codecombat.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CodeCombat\naid: codecombat\nurl: https://codecombat.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Email address\n- category: demographic\n  text: Year and month of birth (without specific day)\n- category: location\n  text: Country and region location information (without specific address or fine-grained location)\n- category: financial\n  text: CodeCombat purchase history\n- category: device\n  text: IP addresses\n- category: behavioral\n  text: Web and email usage data\npurposes:\n- purpose:\
  \ Authentication and rostering\n  text: To provide authentication and rostering features.\n- purpose: Personalize experience\n  text: To personalize your experience.\n- purpose: Improve website\n  text: To improve our website.\n- purpose: Customer service\n  text: To respond to your customer service requests.\n- purpose: Licensing and sales\n  text: To assist with district-wide licensing.\nretention:\n- scope: Server log files\n  period: 30 days\n  text: CodeCombat will retain server log files for no more than 30 days\n- scope: Inactive, unpaid EU user accounts\n  period: 2 years\n  text: will retain inactive, unpaid EU user accounts for no more than 2 years\nresidency:\n- region: United States\n  text: EU users' personal data are processed on US-based CodeCombat servers and at CodeCombat's San Francisco office.\ntransfers:\n- mechanism: SCC\n  text: Privacy Policy Standard Contractual Clauses\n- mechanism: other\n  text: As CodeCombat does not yet have the Privacy Shield certification\
  \ necessary to ensure adequacy, EU users\n    may either explicitly consent to such a transfer or refrain from granting CodeCombat consent while creating\n    a CodeCombat account.\nsubprocessors:\n  url: null\n  text: CodeCombat is assisted by the following GDPR-compliant data processors and data controllers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete Your Account section in account settings\n  text: To delete your account and all personal data relating to your account, go to https://codecombat.com/account/settings\n    and scroll down to the section Delete Your Account .\nrights:\n- right: Access\n  text: Access their personal data.\n- right: Rectification\n  text: Verify and seek rectification.\n- right: Erasure\n  text: Have their personal data deleted or otherwise removed.\n- right: Restriction\n  text: Restrict the processing of their personal data.\n- right: Portability\n  text: Receive their personal data and have data transferred to another\
  \ controller.\n- right: Objection\n  text: Object to processing of their personal data.\n- right: Withdraw consent\n  text: Withdraw their consent at any time.\n- right: Complain\n  text: Lodge a complaint.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or trade to outside parties your personally identifiable information, and do not otherwise\n    transfer it except as described in this privacy notice.\n"
source_yaml_url: https://artifacts.apis.io/codecombat/privacy/codecombat-privacy-policy.yml
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
summary_line: 28 quoted statements, read from CodeCombat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Coding
- Learning
- Classroom
- Students
- Gamification
- SSO
- Developer Tools
---
