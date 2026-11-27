---
api_specs:
- filename: mailfloss-account-api-openapi.yml
  format: yaml
  label: mailfloss Account API
  slug: mailfloss-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-account-api-openapi.yml
- filename: mailfloss-batch-api-openapi.yml
  format: yaml
  label: mailfloss Batch API
  slug: mailfloss-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-batch-api-openapi.yml
- filename: mailfloss-integrations-api-openapi.yml
  format: yaml
  label: mailfloss Integrations API
  slug: mailfloss-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-integrations-api-openapi.yml
- filename: mailfloss-privacy-api-openapi.yml
  format: yaml
  label: mailfloss Privacy API
  slug: mailfloss-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-privacy-api-openapi.yml
- filename: mailfloss-reports-api-openapi.yml
  format: yaml
  label: mailfloss Reports API
  slug: mailfloss-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-reports-api-openapi.yml
- filename: mailfloss-team-api-openapi.yml
  format: yaml
  label: mailfloss Team API
  slug: mailfloss-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-team-api-openapi.yml
- filename: mailfloss-verification-api-openapi.yml
  format: yaml
  label: mailfloss Verification API
  slug: mailfloss-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-verification-api-openapi.yml
- filename: mailfloss-verification-api-openapi.yml
  format: yaml
  label: mailfloss API
  slug: mailfloss-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-verification-api-openapi.yml
- filename: mailfloss-webhooks-api-openapi.yml
  format: yaml
  label: mailfloss Webhooks API
  slug: mailfloss-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-webhooks-api-openapi.yml
- filename: mailfloss-batch-verify-api-openapi.yml
  format: yaml
  label: Mailfloss batch verify API
  slug: mailfloss-batch-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-batch-verify-api-openapi.yml
- filename: mailfloss-verify-api-openapi.yml
  format: yaml
  label: Mailfloss Verify API
  slug: mailfloss-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailfloss/openapi/mailfloss-verify-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, mailing address, email address, phone number, and other contact information.
  - category: financial
    text: Credit and debit card numbers and other financial information necessary to receive payment for Services purchased.
  - category: device
    text: IP address, browser type and version, browser plug-in types and versions, operating system and platform, device type and device identifiers.
  - category: location
    text: Approximate location, such as city and country, derived from your IP address when you sign in.
  - category: behavioral
    text: Information generated from your use of our Services reflecting your preferences, and fraud risk scores
  - category: professional
    text: Title, industry category and organization name.
  deletion:
    route: Request to the contact email; deletion on confirmed request
    text: Once we have received and confirmed your request, we will delete (and direct our partners and service providers to delete) your personal information, unless an exception under applicable law applies.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide Services
    text: provide you with our Services
  - purpose: fraud prevention
    text: To prevent fraud and abuse, we use automated tools to score the risk that an account is fraudulent
  - purpose: marketing
    text: provide you with, and improve, relevant marketing offers or information from us or relevant third parties
  retention:
  - period: 60 days
    scope: signup risk-evaluation records
    text: Signup risk-evaluation records are deleted automatically 60 days after the evaluation.
  - period: up to seven days
    scope: deleted information in backups
    text: Deleted information can remain in database backups for up to seven days.
  rights:
  - right: access
    text: You have the right to request access to the personal information that we collect, use, and disclose about you.
  - right: deletion
    text: You have the right to request that we delete your personal information, subject to some exceptions under applicable law.
  - right: rectification
    text: Right of rectification – you may have the right to request that we rectify inaccurate personal information about you;
  - right: portability
    text: Right to data portability – you may have the right to receive your personal information in a structured, commonly used and machine-readable format
  - right: object
    text: Right to object – where we are processing your personal information based on a legitimate interest (or those of a third party) you may challenge this.
  - right: opt out of sale/sharing
    text: You can opt out of the sale or sharing of your personal information, or its use for targeted advertising
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Adequacy of data protection is instead ensured by Standard Contractual Clauses approved by the European Commission in accordance with Article 46(2)(c) of the General Data Protection Regulation
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mailfloss
provenance_date: '2026-11-10'
provider_name: Mailfloss
provider_slug: mailfloss
slug: mailfloss-privacy-policy
source_date: '2026-11-10'
source_filename: mailfloss-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailfloss.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mailfloss\naid: mailfloss\nurl: https://mailfloss.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, mailing address, email address, phone number, and other contact information.\n- category: financial\n  text: Credit and debit card numbers and other financial information necessary to receive payment for Services\n    purchased.\n- category: device\n  text: IP address, browser type and version, browser plug-in types and versions, operating system and platform,\n    device type and device identifiers.\n- category: location\n\
  \  text: Approximate location, such as city and country, derived from your IP address when you sign in.\n- category: behavioral\n  text: Information generated from your use of our Services reflecting your preferences, and fraud risk scores\n- category: professional\n  text: Title, industry category and organization name.\npurposes:\n- purpose: provide Services\n  text: provide you with our Services\n- purpose: fraud prevention\n  text: To prevent fraud and abuse, we use automated tools to score the risk that an account is fraudulent\n- purpose: marketing\n  text: provide you with, and improve, relevant marketing offers or information from us or relevant third parties\nretention:\n- scope: signup risk-evaluation records\n  period: 60 days\n  text: Signup risk-evaluation records are deleted automatically 60 days after the evaluation.\n- scope: deleted information in backups\n  period: up to seven days\n  text: Deleted information can remain in database backups for up to seven days.\nresidency:\
  \ []\ntransfers:\n- mechanism: SCC\n  text: Adequacy of data protection is instead ensured by Standard Contractual Clauses approved by the European\n    Commission in accordance with Article 46(2)(c) of the General Data Protection Regulation\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the contact email; deletion on confirmed request\n  text: Once we have received and confirmed your request, we will delete (and direct our partners and service providers\n    to delete) your personal information, unless an exception under applicable law applies.\nrights:\n- right: access\n  text: You have the right to request access to the personal information that we collect, use, and disclose about\n    you.\n- right: deletion\n  text: You have the right to request that we delete your personal information, subject to some exceptions under\n    applicable law.\n- right: rectification\n  text: Right of rectification – you may\
  \ have the right to request that we rectify inaccurate personal information\n    about you;\n- right: portability\n  text: Right to data portability – you may have the right to receive your personal information in a structured,\n    commonly used and machine-readable format\n- right: object\n  text: Right to object – where we are processing your personal information based on a legitimate interest (or those\n    of a third party) you may challenge this.\n- right: opt out of sale/sharing\n  text: You can opt out of the sale or sharing of your personal information, or its use for targeted advertising\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailfloss/privacy/mailfloss-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from mailfloss's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Marketing
- Software-as-a-Service
- Automation
- Deliverability
---
