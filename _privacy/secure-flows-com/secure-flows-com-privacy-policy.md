---
api_specs:
- filename: secure-flows-com-ai-optional-api-openapi.yml
  format: yaml
  label: secure-flows-com AI Optional API
  slug: secure-flows-com-ai-optional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-ai-optional-api-openapi.yml
- filename: secure-flows-com-ai-safe-api-openapi.yml
  format: yaml
  label: secure-flows-com AI Safe API
  slug: secure-flows-com-ai-safe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-ai-safe-api-openapi.yml
- filename: secure-flows-com-applications-api-openapi.yml
  format: yaml
  label: secure-flows-com Applications API
  slug: secure-flows-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-applications-api-openapi.yml
- filename: secure-flows-com-audit-api-openapi.yml
  format: yaml
  label: secure-flows-com Audit API
  slug: secure-flows-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-audit-api-openapi.yml
- filename: secure-flows-com-hosted-ui-api-openapi.yml
  format: yaml
  label: secure-flows-com Hosted UI API
  slug: secure-flows-com-hosted-ui-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-hosted-ui-api-openapi.yml
- filename: secure-flows-com-human-only-api-openapi.yml
  format: yaml
  label: secure-flows-com Human Only API
  slug: secure-flows-com-human-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-human-only-api-openapi.yml
- filename: secure-flows-com-users-api-openapi.yml
  format: yaml
  label: secure-flows-com Users API
  slug: secure-flows-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secure-flows-com/openapi/secure-flows-com-users-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: your full name, email address, phone number, name, address, job title
  - category: identifying
    text: authentication credentials (usernames, passwords, etc.)
  - category: device
    text: internet Protocol (IP) addresses, unique cookie identifiers, pixel tags, web beacons
  - category: behavioral
    text: clickstream data, access timestamps, and internal activity logs
  - category: financial
    text: financial payment configurations, including credit card details, bank account identifiers
  - category: professional
    text: Curriculum Vitae (CV/Resume) files, application text, contact variables, cover letters
  - category: communication
    text: the full text, attachments, or metadata of support tickets
  deletion:
    route: formal deletion request to compliance team at [email protected]
    text: To exercise any of these statutory rights, please submit a formal request to our compliance team at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate users and deliver core services
    text: We process this Account and Contact Details dataset primarily to authenticate user identities, configure secure access controls and user roles within our platform
  - purpose: security and fraud prevention
    text: Core operational functionality, stability, platform infrastructure security, anomaly monitoring, and proactive cyber-threat or fraud prevention
  - purpose: machine learning model training
    text: utilizing anonymized datasets for machine learning model training and global threat intelligence aggregation
  - purpose: invoicing and payment
    text: To facilitate invoicing, authenticate financial transactions, manage corporate subscription renewals
  residency:
  - region: global
    text: Secure-Flows operates a globally distributed cloud infrastructure.
  retention:
  - period: null
    scope: personal data in active systems
    text: In the event of an authorized formal deletion request, your Personal Data will be promptly deleted or anonymized from our active production systems.
  - period: null
    scope: backups
    text: such data may temporarily persist in our backup, archival, or disaster recovery environments in an encrypted and isolated state until it is systematically overwritten, purged, or fully deleted
  rights:
  - right: Access
    text: Right of Access – to view a copy of your data
  - right: Rectification
    text: Right to Rectification – to correct inaccurate data
  - right: Erasure
    text: Right to Erasure – to request data deletion
  - right: Object or Restrict
    text: Right to Object or Restrict – to stop or limit data processing
  - right: Portability
    text: Right to Data Portability – to download or transfer your data to you
  - right: Withdraw consent
    text: Right to Withdraw Consent – to revoke previously given approval
  - right: Complaint
    text: Right to Lodge a Complaint – to complain to a privacy authority
  role:
    text: Secure-Flows operates as the Data Controller (or equivalent legal designation under applicable privacy laws) for the data processed in connection with our core platform, operational interfaces, and digital assets.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Secure-Flows does not sell personal data.
  subprocessors:
    text: Firebase (Google), Cloudflare and Render are 3 examples of Secure-Flows Service providers.
    url: null
  transfers:
  - mechanism: SCC
    text: including the execution of the EU Standard Contractual Clauses (SCCs) as authorized by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: secure-flows-com
provenance_date: '2026-11-10'
provider_name: secure-flows-com
provider_slug: secure-flows-com
slug: secure-flows-com-privacy-policy
source_date: '2026-11-10'
source_filename: secure-flows-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.secure-flows.com/docs/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: secure-flows-com\naid: secure-flows-com\nurl: https://www.secure-flows.com/docs/legal/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Secure-Flows operates as the Data Controller (or equivalent legal designation under applicable privacy laws)\n    for the data processed in connection with our core platform, operational interfaces, and digital assets.\ndata_categories:\n- category: contact\n  text: your full name, email address, phone number, name, address, job title\n- category: identifying\n  text: authentication credentials (usernames, passwords, etc.)\n- category: device\n  text:\
  \ internet Protocol (IP) addresses, unique cookie identifiers, pixel tags, web beacons\n- category: behavioral\n  text: clickstream data, access timestamps, and internal activity logs\n- category: financial\n  text: financial payment configurations, including credit card details, bank account identifiers\n- category: professional\n  text: Curriculum Vitae (CV/Resume) files, application text, contact variables, cover letters\n- category: communication\n  text: the full text, attachments, or metadata of support tickets\npurposes:\n- purpose: authenticate users and deliver core services\n  text: We process this Account and Contact Details dataset primarily to authenticate user identities, configure\n    secure access controls and user roles within our platform\n- purpose: security and fraud prevention\n  text: Core operational functionality, stability, platform infrastructure security, anomaly monitoring, and proactive\n    cyber-threat or fraud prevention\n- purpose: machine learning model\
  \ training\n  text: utilizing anonymized datasets for machine learning model training and global threat intelligence aggregation\n- purpose: invoicing and payment\n  text: To facilitate invoicing, authenticate financial transactions, manage corporate subscription renewals\nretention:\n- scope: personal data in active systems\n  period: null\n  text: In the event of an authorized formal deletion request, your Personal Data will be promptly deleted or anonymized\n    from our active production systems.\n- scope: backups\n  period: null\n  text: such data may temporarily persist in our backup, archival, or disaster recovery environments in an encrypted\n    and isolated state until it is systematically overwritten, purged, or fully deleted\nresidency:\n- region: global\n  text: Secure-Flows operates a globally distributed cloud infrastructure.\ntransfers:\n- mechanism: SCC\n  text: including the execution of the EU Standard Contractual Clauses (SCCs) as authorized by the European Commission\n\
  subprocessors:\n  url: null\n  text: Firebase (Google), Cloudflare and Render are 3 examples of Secure-Flows Service providers.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: formal deletion request to compliance team at [email protected]\n  text: To exercise any of these statutory rights, please submit a formal request to our compliance team at [email\n    protected] .\nrights:\n- right: Access\n  text: Right of Access – to view a copy of your data\n- right: Rectification\n  text: Right to Rectification – to correct inaccurate data\n- right: Erasure\n  text: Right to Erasure – to request data deletion\n- right: Object or Restrict\n  text: Right to Object or Restrict – to stop or limit data processing\n- right: Portability\n  text: Right to Data Portability – to download or transfer your data to you\n- right: Withdraw consent\n  text: Right to Withdraw Consent – to revoke previously given approval\n- right: Complaint\n  text: Right to Lodge a Complaint – to complain\
  \ to a privacy authority\nsale_or_sharing:\n  stance: prohibited\n  text: Secure-Flows does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/secure-flows-com/privacy/secure-flows-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from secure-flows-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Data-Encryption
- No-Code
- Authentication
---
