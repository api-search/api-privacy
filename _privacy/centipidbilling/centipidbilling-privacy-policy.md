---
api_specs:
- filename: centipidbilling-async-api-openapi.yml
  format: yaml
  label: Centipid Technologies Async API
  slug: centipidbilling-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-async-api-openapi.yml
- filename: centipidbilling-collections-api-openapi.yml
  format: yaml
  label: Centipid Technologies Collections API
  slug: centipidbilling-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-collections-api-openapi.yml
- filename: centipidbilling-interface-api-openapi.yml
  format: yaml
  label: Centipid Technologies Interface API
  slug: centipidbilling-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-interface-api-openapi.yml
- filename: centipidbilling-mcp-api-openapi.yml
  format: yaml
  label: Centipid Technologies MCP API
  slug: centipidbilling-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centipidbilling/openapi/centipidbilling-mcp-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: The information we collect includes customer identification details, service usage data, and payment information.
  - category: contact
    text: If you start signing up and stop before your account is created, we keep the name, email and phone number you entered.
  - category: financial
    text: Payment card information is encrypted using PCI DSS compliant protocols
  - category: behavioral
    text: Usage data is automatically collected and processed for billing purposes
  - category: device
    text: Internet session logs (when a subscriber was online, from which device, and how much data they used)
  deletion:
    route: Contact sales@centipidtechnologies.com or ISP; on termination non-essential data is deleted
    text: Upon service termination, non-essential data is securely deleted from our systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run billing system
    text: We process subscriber data only to run the billing system on the ISP's instructions.
  - purpose: Answer AI service requests
    text: To answer the request the operator made through the AI service, and nothing else.
  residency:
  - region: United Kingdom (London)
    text: The database and file storage are in the United Kingdom (London), and some servers run in Germany and the Netherlands.
  retention:
  - period: 12 months
    scope: Internet session logs
    text: Internet session logs (when a subscriber was online, from which device, and how much data they used) are deleted automatically 12 months after the session.
  - period: 14 days
    scope: Web server request logs (MCP)
    text: Web server request logs are kept for 14 days.
  - period: 1 hour
    scope: MCP access tokens
    text: Access tokens expire after 1 hour.
  - period: 30 days
    scope: MCP connections and refresh tokens
    text: Connections and refresh tokens expire after 30 days unless they are disconnected sooner.
  - period: as long as the ISP's account exists
    scope: Payment and transaction records
    text: Payment and transaction records are kept for as long as the ISP's account exists and are deleted when the account is deleted.
  rights:
  - right: Access report
    text: Request a comprehensive report of your stored data
  - right: Correction
    text: Correct any inaccurate information
  - right: Portability
    text: Export your data in a standard format
  - right: Deletion
    text: Request deletion of your information upon service termination
  - right: Objection
    text: Object to processing, including refusing direct marketing
  - right: Complaint
    text: Complain to the Office of the Data Protection Commissioner ( odpc.go.ke )
  role:
    text: For ISP accounts (the people who sign up for and run a workspace), Centipid Technologies is the data controller . For an ISP's subscribers , the ISP is the data controller and Centipid Technologies is its data processor .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Centipid does not sell customer data or share it with advertising or marketing agencies.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We transfer data there under section 48 of the Data Protection Act, using providers bound by contracts that require them to protect it to a standard at least equal to Kenyan law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Centipid Technologies
provenance_date: '2026-11-09'
provider_name: Centipid Technologies
provider_slug: centipidbilling
slug: centipidbilling-privacy-policy
source_date: '2026-11-09'
source_filename: centipidbilling-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://centipidbilling.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Centipid Technologies\naid: centipidbilling\nurl: https://centipidbilling.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For ISP accounts (the people who sign up for and run a workspace), Centipid Technologies is the data controller\n    . For an ISP's subscribers , the ISP is the data controller and Centipid Technologies is its data processor\n    .\ndata_categories:\n- category: identifying\n  text: The information we collect includes customer identification details, service usage data, and payment information.\n- category: contact\n  text: If you start signing up and stop before your\
  \ account is created, we keep the name, email and phone number\n    you entered.\n- category: financial\n  text: Payment card information is encrypted using PCI DSS compliant protocols\n- category: behavioral\n  text: Usage data is automatically collected and processed for billing purposes\n- category: device\n  text: Internet session logs (when a subscriber was online, from which device, and how much data they used)\npurposes:\n- purpose: Run billing system\n  text: We process subscriber data only to run the billing system on the ISP's instructions.\n- purpose: Answer AI service requests\n  text: To answer the request the operator made through the AI service, and nothing else.\nretention:\n- scope: Internet session logs\n  period: 12 months\n  text: Internet session logs (when a subscriber was online, from which device, and how much data they used) are\n    deleted automatically 12 months after the session.\n- scope: Web server request logs (MCP)\n  period: 14 days\n  text: Web server\
  \ request logs are kept for 14 days.\n- scope: MCP access tokens\n  period: 1 hour\n  text: Access tokens expire after 1 hour.\n- scope: MCP connections and refresh tokens\n  period: 30 days\n  text: Connections and refresh tokens expire after 30 days unless they are disconnected sooner.\n- scope: Payment and transaction records\n  period: as long as the ISP's account exists\n  text: Payment and transaction records are kept for as long as the ISP's account exists and are deleted when the\n    account is deleted.\nresidency:\n- region: United Kingdom (London)\n  text: The database and file storage are in the United Kingdom (London), and some servers run in Germany and the\n    Netherlands.\ntransfers:\n- mechanism: other\n  text: We transfer data there under section 48 of the Data Protection Act, using providers bound by contracts that\n    require them to protect it to a standard at least equal to Kenyan law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Contact sales@centipidtechnologies.com or ISP; on termination non-essential data is deleted\n  text: Upon service termination, non-essential data is securely deleted from our systems.\nrights:\n- right: Access report\n  text: Request a comprehensive report of your stored data\n- right: Correction\n  text: Correct any inaccurate information\n- right: Portability\n  text: Export your data in a standard format\n- right: Deletion\n  text: Request deletion of your information upon service termination\n- right: Objection\n  text: Object to processing, including refusing direct marketing\n- right: Complaint\n  text: Complain to the Office of the Data Protection Commissioner ( odpc.go.ke )\nsale_or_sharing:\n  stance: prohibited\n  text: Centipid does not sell customer data or share it with advertising or marketing agencies.\n"
source_yaml_url: https://artifacts.apis.io/centipidbilling/privacy/centipidbilling-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Centipid Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ISP
- Billing
- OSS BSS
- Telecommunications
---
