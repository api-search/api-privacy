---
api_specs:
- filename: superdocs-app-account-api-openapi.yml
  format: yaml
  label: superdocs-app Account API
  slug: superdocs-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-account-api-openapi.yml
- filename: superdocs-app-agents-api-openapi.yml
  format: yaml
  label: superdocs-app Agents API
  slug: superdocs-app-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-agents-api-openapi.yml
- filename: superdocs-app-approval-api-openapi.yml
  format: yaml
  label: superdocs-app Approval API
  slug: superdocs-app-approval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-approval-api-openapi.yml
- filename: superdocs-app-attachments-api-openapi.yml
  format: yaml
  label: superdocs-app Attachments API
  slug: superdocs-app-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-attachments-api-openapi.yml
- filename: superdocs-app-chat-api-openapi.yml
  format: yaml
  label: superdocs-app Chat API
  slug: superdocs-app-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-chat-api-openapi.yml
- filename: superdocs-app-documents-api-openapi.yml
  format: yaml
  label: superdocs-app Documents API
  slug: superdocs-app-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-documents-api-openapi.yml
- filename: superdocs-app-downloads-api-openapi.yml
  format: yaml
  label: superdocs-app Downloads API
  slug: superdocs-app-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-downloads-api-openapi.yml
- filename: superdocs-app-health-api-openapi.yml
  format: yaml
  label: superdocs-app Health API
  slug: superdocs-app-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-health-api-openapi.yml
- filename: superdocs-app-jobs-api-openapi.yml
  format: yaml
  label: superdocs-app Jobs API
  slug: superdocs-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-jobs-api-openapi.yml
- filename: superdocs-app-mcp-api-openapi.yml
  format: yaml
  label: superdocs-app MCP API
  slug: superdocs-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-mcp-api-openapi.yml
- filename: superdocs-app-promo-api-openapi.yml
  format: yaml
  label: superdocs-app Promo API
  slug: superdocs-app-promo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-promo-api-openapi.yml
- filename: superdocs-app-sessions-api-openapi.yml
  format: yaml
  label: superdocs-app Sessions API
  slug: superdocs-app-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-sessions-api-openapi.yml
- filename: superdocs-app-templates-api-openapi.yml
  format: yaml
  label: superdocs-app Templates API
  slug: superdocs-app-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-templates-api-openapi.yml
- filename: superdocs-app-typebar-api-universal-document-ai-api-openapi.yml
  format: yaml
  label: 'superdocs-app Typebar API: Universal Document AI API'
  slug: superdocs-app-typebar-api-universal-document-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-typebar-api-universal-document-ai-api-openapi.yml
- filename: superdocs-app-uploads-api-openapi.yml
  format: yaml
  label: superdocs-app Uploads API
  slug: superdocs-app-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-uploads-api-openapi.yml
- filename: superdocs-app-users-api-openapi.yml
  format: yaml
  label: superdocs-app Users API
  slug: superdocs-app-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-users-api-openapi.yml
- filename: superdocs-app-well-known-api-openapi.yml
  format: yaml
  label: superdocs-app .well Known API
  slug: superdocs-app-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdocs-app/openapi/superdocs-app-well-known-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, display name, profile picture (if provided), authentication method (email/password or Google Sign-In)
  - category: behavioral
    text: Usage Data Features used, number of AI operations performed, session identifiers, timestamps of interactions
  - category: device
    text: Browser type, operating system, IP address, referring URL
  - category: financial
    text: Billing information, payment method details (when payment processing is enabled)
  - category: location
    text: The country derived from your IP address (including the IP address you signed up from)
  - category: communication
    text: Emails or messages you send to us via support or contact channels
  - category: other
    text: Document Content Documents you create, upload, or edit within Typebar, including text, formatting, and structure
  deletion:
    route: Delete your account in the service or email hello@superdocs.app
    text: Request deletion of your account and associated data Email hello@superdocs.app
  dpa:
    available: true
    text: Enterprise customers may request a formal Data Processing Agreement that details our obligations as a data processor. Contact hello@superdocs.app to request a DPA.
    url: null
  purposes:
  - purpose: Providing the Service
    text: Providing the Service — To operate Typebar, process your documents, deliver AI-assisted features, and maintain your session and document state across visits.
  - purpose: Security and abuse prevention
    text: Security and Abuse Prevention — To detect, prevent, and respond to fraud, abuse, security incidents, and technical issues.
  - purpose: Service improvement
    text: Service Improvement — To understand how the Service is used in aggregate, identify issues, and improve functionality.
  residency:
  - region: United States
    text: Typebar data is hosted in the United States.
  retention:
  - period: Until you delete your account
    scope: Account information
    text: Account information Until you delete your account
  - period: Up to 90 days
    scope: Server logs (IP, device info)
    text: Server logs (IP, device info) Up to 90 days
  - period: 24 months from the decision
    scope: Sanctions and provider-region check logs
    text: Sanctions and provider-region check logs (refusals, AI features turned off, cases sent for review) 24 months from the decision
  - period: within 30 days
    scope: Deleted account data
    text: Your account information, documents, attachments, and conversation history are deleted within 30 days of your deletion request.
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you Email hello@superdocs.app
  - right: Correction
    text: Request correction of inaccurate personal data Update your profile in-app, or email us
  - right: Deletion
    text: Request deletion of your account and associated data Email hello@superdocs.app
  - right: Export
    text: Request a portable copy of your data (documents and account info) Email hello@superdocs.app
  - right: Objection
    text: Object to processing based on legitimate interest Email hello@superdocs.app
  role:
    text: Typebar (“we,” “us,” or “our”) collects, uses, stores, and protects your information when you use the Typebar platform
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: To protect data transferred from the EEA to the United States, we rely on the Standard Contractual Clauses (SCCs) approved by the European Commission, or on another transfer safeguard recognised under the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: superdocs-app
provenance_date: '2026-11-10'
provider_name: superdocs-app
provider_slug: superdocs-app
slug: superdocs-app-privacy-policy
source_date: '2026-11-10'
source_filename: superdocs-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://typebar.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: superdocs-app\naid: superdocs-app\nurl: https://typebar.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Typebar (“we,” “us,” or “our”) collects, uses, stores, and protects your information when you use the Typebar\n    platform\ndata_categories:\n- category: identifying\n  text: Email address, display name, profile picture (if provided), authentication method (email/password or Google\n    Sign-In)\n- category: behavioral\n  text: Usage Data Features used, number of AI operations performed, session identifiers, timestamps of interactions\n- category: device\n  text: Browser type,\
  \ operating system, IP address, referring URL\n- category: financial\n  text: Billing information, payment method details (when payment processing is enabled)\n- category: location\n  text: The country derived from your IP address (including the IP address you signed up from)\n- category: communication\n  text: Emails or messages you send to us via support or contact channels\n- category: other\n  text: Document Content Documents you create, upload, or edit within Typebar, including text, formatting, and structure\npurposes:\n- purpose: Providing the Service\n  text: Providing the Service — To operate Typebar, process your documents, deliver AI-assisted features, and maintain\n    your session and document state across visits.\n- purpose: Security and abuse prevention\n  text: Security and Abuse Prevention — To detect, prevent, and respond to fraud, abuse, security incidents, and\n    technical issues.\n- purpose: Service improvement\n  text: Service Improvement — To understand how the\
  \ Service is used in aggregate, identify issues, and improve functionality.\nretention:\n- scope: Account information\n  period: Until you delete your account\n  text: Account information Until you delete your account\n- scope: Server logs (IP, device info)\n  period: Up to 90 days\n  text: Server logs (IP, device info) Up to 90 days\n- scope: Sanctions and provider-region check logs\n  period: 24 months from the decision\n  text: Sanctions and provider-region check logs (refusals, AI features turned off, cases sent for review) 24 months\n    from the decision\n- scope: Deleted account data\n  period: within 30 days\n  text: Your account information, documents, attachments, and conversation history are deleted within 30 days of\n    your deletion request.\nresidency:\n- region: United States\n  text: Typebar data is hosted in the United States.\ntransfers:\n- mechanism: SCC\n  text: To protect data transferred from the EEA to the United States, we rely on the Standard Contractual Clauses\n\
  \    (SCCs) approved by the European Commission, or on another transfer safeguard recognised under the GDPR.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Enterprise customers may request a formal Data Processing Agreement that details our obligations as a data\n    processor. Contact hello@superdocs.app to request a DPA.\ndeletion:\n  route: Delete your account in the service or email hello@superdocs.app\n  text: Request deletion of your account and associated data Email hello@superdocs.app\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you Email hello@superdocs.app\n- right: Correction\n  text: Request correction of inaccurate personal data Update your profile in-app, or email us\n- right: Deletion\n  text: Request deletion of your account and associated data Email hello@superdocs.app\n- right: Export\n  text: Request a portable copy of your data (documents and account info) Email hello@superdocs.app\n\
  - right: Objection\n  text: Object to processing based on legitimate interest Email hello@superdocs.app\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/superdocs-app/privacy/superdocs-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from superdocs-app's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document Editing
- REST API
- MCP
- Software-as-a-Service
---
