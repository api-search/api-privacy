---
api_specs:
- filename: trato-contracts-api-openapi.yml
  format: yaml
  label: Trato Contracts API
  slug: trato-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-contracts-api-openapi.yml
- filename: trato-custom-properties-api-openapi.yml
  format: yaml
  label: Trato Custom Properties API
  slug: trato-custom-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-custom-properties-api-openapi.yml
- filename: trato-participants-api-openapi.yml
  format: yaml
  label: Trato Participants API
  slug: trato-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-participants-api-openapi.yml
- filename: trato-spectators-api-openapi.yml
  format: yaml
  label: Trato Spectators API
  slug: trato-spectators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-spectators-api-openapi.yml
- filename: trato-templates-api-openapi.yml
  format: yaml
  label: Trato Templates API
  slug: trato-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-templates-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, surname, email, phone, company name, position or role, postal address.
  - category: financial
    text: Tax information, billing address, payment method information (processed securely through our payment service providers).
  - category: device
    text: IP address, device type, operating system, browser type, unique device identifiers, mobile network information.
  - category: behavioral
    text: Information about how you interact with our Services, such as pages visited, features used, access dates and times, clicks, time spent, search terms.
  - category: communication
    text: Information you provide when communicating with us for technical support, inquiries or any other reason.
  - category: other
    text: Any information, documents or data that you upload, create, send, store or manage through our Services (for example, contracts, agreements, comments).
  deletion:
    route: Written request to the Data Controller email or postal address for your jurisdiction
    text: To exercise any of these rights, you can send a written request, duly proving your identity
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision and management
    text: Create and manage your user account.
  - purpose: Communication and support
    text: Respond to your inquiries, information requests or technical support.
  - purpose: Service improvement and personalization
    text: Analyze Service usage to understand how they are used and how we can improve them.
  - purpose: Marketing and promotion
    text: Send you information about our products, services, solutions, events, special offers and other news we think may interest you.
  - purpose: Legal compliance and security
    text: Prevent fraud, abuse and other illegal activities.
  retention:
  - period: null
    scope: Personal data generally
    text: We will retain your personal data only for as long as necessary to fulfill the purposes for which it was collected
  - period: null
    scope: Data after purpose ends
    text: Once your personal data is no longer necessary for these purposes, it will be securely deleted or anonymized, in accordance with our internal policies and applicable legislation.
  rights:
  - right: Access
    text: 'Right of Access: Obtain confirmation of whether we are processing your data and, if so, access it and certain information about the processing.'
  - right: Rectification
    text: 'Right of Rectification: Request correction of inaccurate data or completion of incomplete data.'
  - right: Erasure
    text: 'Right of Erasure (Right to be Forgotten): Request deletion of your data when, among other reasons, it is no longer necessary for the purposes for which it was collected.'
  - right: Portability
    text: 'Right to Data Portability: Receive your personal data in a structured, commonly used and machine-readable format'
  - right: Object
    text: 'Right to Object: Object to processing of your data for reasons related to your particular situation, including processing for direct marketing purposes.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: When processing is based on your consent, you can withdraw it at any time'
  role:
    text: The TRATO entity responsible for processing your personal data will depend on your geographic location
    value: controller
  sale_or_sharing:
    stance: conditional
    text: TRATO will not transfer or sell your personal data to third parties without your prior consent, except in the following cases or when there is a legal obligation
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we will implement appropriate safeguards, such as Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Trato
provenance_date: '2026-11-10'
provider_name: Trato
provider_slug: trato
slug: trato-privacy-policy
source_date: '2026-11-10'
source_filename: trato-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://trato.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Trato\naid: trato\nurl: https://trato.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The TRATO entity responsible for processing your personal data will depend on your geographic location\ndata_categories:\n- category: contact\n  text: Name, surname, email, phone, company name, position or role, postal address.\n- category: financial\n  text: Tax information, billing address, payment method information (processed securely through our payment service\n    providers).\n- category: device\n  text: IP address, device type, operating system, browser type, unique device identifiers,\
  \ mobile network information.\n- category: behavioral\n  text: Information about how you interact with our Services, such as pages visited, features used, access dates\n    and times, clicks, time spent, search terms.\n- category: communication\n  text: Information you provide when communicating with us for technical support, inquiries or any other reason.\n- category: other\n  text: Any information, documents or data that you upload, create, send, store or manage through our Services (for\n    example, contracts, agreements, comments).\npurposes:\n- purpose: Service provision and management\n  text: Create and manage your user account.\n- purpose: Communication and support\n  text: Respond to your inquiries, information requests or technical support.\n- purpose: Service improvement and personalization\n  text: Analyze Service usage to understand how they are used and how we can improve them.\n- purpose: Marketing and promotion\n  text: Send you information about our products, services,\
  \ solutions, events, special offers and other news we think\n    may interest you.\n- purpose: Legal compliance and security\n  text: Prevent fraud, abuse and other illegal activities.\nretention:\n- scope: Personal data generally\n  period: null\n  text: We will retain your personal data only for as long as necessary to fulfill the purposes for which it was\n    collected\n- scope: Data after purpose ends\n  period: null\n  text: Once your personal data is no longer necessary for these purposes, it will be securely deleted or anonymized,\n    in accordance with our internal policies and applicable legislation.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we will implement appropriate safeguards, such as Standard Contractual Clauses approved by the European\n    Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Written request to the Data Controller email or postal address for your jurisdiction\n  text:\
  \ To exercise any of these rights, you can send a written request, duly proving your identity\nrights:\n- right: Access\n  text: 'Right of Access: Obtain confirmation of whether we are processing your data and, if so, access it and certain\n    information about the processing.'\n- right: Rectification\n  text: 'Right of Rectification: Request correction of inaccurate data or completion of incomplete data.'\n- right: Erasure\n  text: 'Right of Erasure (Right to be Forgotten): Request deletion of your data when, among other reasons, it is\n    no longer necessary for the purposes for which it was collected.'\n- right: Portability\n  text: 'Right to Data Portability: Receive your personal data in a structured, commonly used and machine-readable\n    format'\n- right: Object\n  text: 'Right to Object: Object to processing of your data for reasons related to your particular situation, including\n    processing for direct marketing purposes.'\n- right: Withdraw consent\n  text: 'Right to Withdraw\
  \ Consent: When processing is based on your consent, you can withdraw it at any time'\nsale_or_sharing:\n  stance: conditional\n  text: TRATO will not transfer or sell your personal data to third parties without your prior consent, except in\n    the following cases or when there is a legal obligation\n"
source_yaml_url: https://artifacts.apis.io/trato/privacy/trato-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Trato's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contract Management
- Contract Lifecycle Management
- E-Signature
- Legal Tech
- Document Management
- Workflow Automation
- Legal
---
