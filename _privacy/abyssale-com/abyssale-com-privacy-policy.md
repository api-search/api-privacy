---
api_specs:
- filename: abyssale-com-auth-api-openapi.yml
  format: yaml
  label: Abyssale Auth API
  slug: abyssale-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-auth-api-openapi.yml
- filename: abyssale-com-credits-api-openapi.yml
  format: yaml
  label: Abyssale Credits API
  slug: abyssale-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-credits-api-openapi.yml
- filename: abyssale-com-design-duplication-requests-api-openapi.yml
  format: yaml
  label: Abyssale Design Duplication Requests API
  slug: abyssale-com-design-duplication-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-design-duplication-requests-api-openapi.yml
- filename: abyssale-com-designs-api-openapi.yml
  format: yaml
  label: Abyssale Designs API
  slug: abyssale-com-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-designs-api-openapi.yml
- filename: abyssale-com-examples-api-openapi.yml
  format: yaml
  label: Abyssale Examples API
  slug: abyssale-com-examples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-examples-api-openapi.yml
- filename: abyssale-com-export-abyssale-api-openapi.yml
  format: yaml
  label: Abyssale Export Abyssale API
  slug: abyssale-com-export-abyssale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-export-abyssale-api-openapi.yml
- filename: abyssale-com-fonts-api-openapi.yml
  format: yaml
  label: Abyssale Fonts API
  slug: abyssale-com-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-fonts-api-openapi.yml
- filename: abyssale-com-images-api-openapi.yml
  format: yaml
  label: Abyssale Images API
  slug: abyssale-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-images-api-openapi.yml
- filename: abyssale-com-projects-api-openapi.yml
  format: yaml
  label: Abyssale Projects API
  slug: abyssale-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-projects-api-openapi.yml
- filename: abyssale-com-workspace-template-categories-api-openapi.yml
  format: yaml
  label: Abyssale Workspace Template Categories API
  slug: abyssale-com-workspace-template-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-workspace-template-categories-api-openapi.yml
- filename: abyssale-com-workspace-templates-api-openapi.yml
  format: yaml
  label: Abyssale Workspace Templates API
  slug: abyssale-com-workspace-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abyssale-com/openapi/abyssale-com-workspace-templates-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, last name, first name, photograph (optional data), IP address, Password (except SSO connection), Phone (optional), Connection data and logs.
  - category: communication
    text: 'Exchanges with Customer Support: Content of messages, emails, and tickets sent to support (via Intercom or email).'
  - category: other
    text: 'API & Integration Data: Data transmitted via the Abyssale API or third-party integrations (e.g., Make, Zapier) for the purpose of generating content.'
  deletion:
    route: Client retrieval window then deletion timelines
    text: Upon termination of the Contract, the Client has a thirty (30) day period to retrieve its Content as set out in the Terms of Service; after this period the deletion timelines above apply
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication of users
    text: Authentication of Users to access and use the Platform.
  - purpose: Marketing communications
    text: Transmission of marketing communications.
  - purpose: Statistical analysis and improvement
    text: Statistical analysis of the Platform and usage data for the purpose of improving the Platform and its Features.
  - purpose: R&D and AI model training
    text: Training and refining internal algorithms and machine learning models (AI) to improve generation quality, using anonymized and/or aggregated data on the basis of the Company's legitimate interest.
  residency:
  - region: European Union
    text: The Client's data is primarily hosted on servers located within the European Union (AWS - Ireland).
  retention:
  - period: three (3) months
    scope: User account data
    text: From the creation of the User account to the deletion of the User account plus three (3) months
  - period: five (5) years
    scope: Archived data for litigation
    text: the data may be archived for a period of five (5) years after the end of the Contract for evidentiary purposes only in case of litigation.
  - period: indefinitely
    scope: Anonymized or aggregated data
    text: may be retained indefinitely for statistical, analytical, and product improvement (R&D) purposes.
  rights:
  - right: Access
    text: 'Right of access: you can obtain information concerning the processing of your personal data as well as a copy of this personal data.'
  - right: Rectification
    text: 'Right to rectification of your data:'
  - right: Erasure
    text: 'Right to erasure of your data: you can require the erasure of your personal data within the limits permitted by law.'
  - right: Restriction
    text: 'Right to restriction of processing:'
  - right: Portability
    text: 'Right to data portability:'
  - right: Object
    text: 'Right to object: you can object at any time, for reasons relating to your particular situation, to processing of your personal data whose legal basis is legitimate interest.'
  - right: Withdraw consent
    text: 'Right to withdraw your consent: if you have given your consent to the processing of your personal data, you have the right to withdraw your consent at any time.'
  role:
    text: 'Either by a Client who is a natural person who will also be a User of the Platform: in this context, ABYSSALE is the data controller. Or by a Client who is a legal entity, which subscribes to the Platform for one or more Users according to the chosen commitment level: in this context, ABYSSALE is the data processor.'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Amazon Web Services - Ireland: hosting Auth0, Inc. (subsidiary of Okta) - European Union: User authentication and storage and securing of passwords. Brevo - European Union: Marketing and transactional communication by email Intercom - European Union: Instant messaging tool'
    url: null
  transfers:
  - mechanism: DPF
    text: Adherence by the sub-processor to the Data Privacy Framework (DPF) recognized by the European Commission;
  - mechanism: SCC
    text: the signature of Standard Contractual Clauses (SCCs) adopted by the European Commission, ensuring a level of protection equivalent to that of the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Abyssale
provenance_date: '2026-11-09'
provider_name: Abyssale
provider_slug: abyssale-com
slug: abyssale-com-privacy-policy
source_date: '2026-11-09'
source_filename: abyssale-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.abyssale.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Abyssale\naid: abyssale-com\nurl: https://www.abyssale.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Either by a Client who is a natural person who will also be a User of the Platform: in this context, ABYSSALE\n    is the data controller. Or by a Client who is a legal entity, which subscribes to the Platform for one or more\n    Users according to the chosen commitment level: in this context, ABYSSALE is the data processor.'\ndata_categories:\n- category: identifying\n  text: Email, last name, first name, photograph (optional data), IP address, Password (except SSO connection),\n\
  \    Phone (optional), Connection data and logs.\n- category: communication\n  text: 'Exchanges with Customer Support: Content of messages, emails, and tickets sent to support (via Intercom\n    or email).'\n- category: other\n  text: 'API & Integration Data: Data transmitted via the Abyssale API or third-party integrations (e.g., Make,\n    Zapier) for the purpose of generating content.'\npurposes:\n- purpose: Authentication of users\n  text: Authentication of Users to access and use the Platform.\n- purpose: Marketing communications\n  text: Transmission of marketing communications.\n- purpose: Statistical analysis and improvement\n  text: Statistical analysis of the Platform and usage data for the purpose of improving the Platform and its Features.\n- purpose: R&D and AI model training\n  text: Training and refining internal algorithms and machine learning models (AI) to improve generation quality,\n    using anonymized and/or aggregated data on the basis of the Company's legitimate\
  \ interest.\nretention:\n- scope: User account data\n  period: three (3) months\n  text: From the creation of the User account to the deletion of the User account plus three (3) months\n- scope: Archived data for litigation\n  period: five (5) years\n  text: the data may be archived for a period of five (5) years after the end of the Contract for evidentiary purposes\n    only in case of litigation.\n- scope: Anonymized or aggregated data\n  period: indefinitely\n  text: may be retained indefinitely for statistical, analytical, and product improvement (R&D) purposes.\nresidency:\n- region: European Union\n  text: The Client's data is primarily hosted on servers located within the European Union (AWS - Ireland).\ntransfers:\n- mechanism: DPF\n  text: Adherence by the sub-processor to the Data Privacy Framework (DPF) recognized by the European Commission;\n- mechanism: SCC\n  text: the signature of Standard Contractual Clauses (SCCs) adopted by the European Commission, ensuring a level\n\
  \    of protection equivalent to that of the GDPR.\nsubprocessors:\n  url: null\n  text: 'Amazon Web Services - Ireland: hosting Auth0, Inc. (subsidiary of Okta) - European Union: User authentication\n    and storage and securing of passwords. Brevo - European Union: Marketing and transactional communication by\n    email Intercom - European Union: Instant messaging tool'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Client retrieval window then deletion timelines\n  text: Upon termination of the Contract, the Client has a thirty (30) day period to retrieve its Content as set\n    out in the Terms of Service; after this period the deletion timelines above apply\nrights:\n- right: Access\n  text: 'Right of access: you can obtain information concerning the processing of your personal data as well as\n    a copy of this personal data.'\n- right: Rectification\n  text: 'Right to rectification of your data:'\n- right: Erasure\n  text: 'Right to erasure of your data:\
  \ you can require the erasure of your personal data within the limits permitted\n    by law.'\n- right: Restriction\n  text: 'Right to restriction of processing:'\n- right: Portability\n  text: 'Right to data portability:'\n- right: Object\n  text: 'Right to object: you can object at any time, for reasons relating to your particular situation, to processing\n    of your personal data whose legal basis is legitimate interest.'\n- right: Withdraw consent\n  text: 'Right to withdraw your consent: if you have given your consent to the processing of your personal data,\n    you have the right to withdraw your consent at any time.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abyssale-com/privacy/abyssale-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Abyssale's own page on 2026-11-09.
synthetic: false
tags:
- Creative Automation
- Marketing
- Agencies
- Visual-Production
- Software-as-a-Service
---
