---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and organisational role of authorised platform users.
  - category: contact
    text: Name, email address, and organisational role of authorised platform users.
  - category: professional
    text: Worker names, roles, employment status, and skill records sourced from connected workforce management systems (e.g., Assignar).
  - category: financial
    text: Project financial records, cost codes, budgets, and variance data sourced from connected ERP systems (e.g., Microsoft Dynamics 365 Business Central).
  - category: behavioral
    text: Analytics events (page views, feature interactions) via Google Analytics 4, with no advertising or cross-site tracking.
  - category: device
    text: Technical logs covering API performance, workflow execution outcomes, adapter connectivity, and system health.
  - category: communication
    text: An email you raise from Outlook. When a user raises an issue from an email in Outlook, Demiton stores that email (and any others attached to the raise) as your organisation’s evidence
  deletion:
    route: Request via privacy@demiton.io
    text: Request deletion of personal information where we have no lawful basis for continued retention, subject to our seven-year audit retention obligation.
  dpa:
    available: true
    text: Customers requiring a multi-region deployment (e.g., for disaster recovery in a nominated jurisdiction) must configure this explicitly and accept an updated Data Processing Agreement (DPA) that reflects the extended residency scope.
    url: null
  purposes:
  - purpose: Workflow execution
    text: To run workflows that fetch, transform, and deliver data between your connected systems at your direction.
  - purpose: AI orchestration
    text: To provide contextually aware responses in the AI Studio by grounding prompts with data from your connected systems.
  - purpose: Audit and governance
    text: To maintain an immutable, append-only audit trail of all workflow executions and data movements for your internal compliance.
  - purpose: Support and diagnostics
    text: To diagnose connectivity issues, workflow failures, and adapter errors with your connected systems.
  - purpose: Billing
    text: To calculate usage, process subscription payments, and generate invoices.
  residency:
  - region: Australia
    text: All Customer Data is stored and processed within Microsoft Azure Australia East (Sydney) , with failover capability to Australia Southeast (Melbourne).
  retention:
  - period: seven years
    scope: Audit trail logs
    text: Workflow execution and data movement logs are immutable and retained for a minimum of seven years.
  rights:
  - right: Access
    text: 'Access: Request a copy of personal information we hold about you (Data Subject Access Request - DSAR).'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete personal information.'
  - right: Deletion
    text: 'Deletion: Request deletion of personal information where we have no lawful basis for continued retention, subject to our seven-year audit retention obligation.'
  - right: Objection
    text: 'Objection: Object to processing of your personal information for purposes beyond those required to deliver the Service.'
  - right: Data portability
    text: 'Data portability: Request an export of your organisation''s data in a machine-readable format.'
  - right: Withdraw consent
    text: Withdraw consent for optional data processing (analytics, Enterprise benchmarking) at any time without affecting your access to the Service.
  role:
    text: We operate as a Data Processor ; you (the Customer) retain the role of Data Controller for all data you bring into the platform.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or Customer Data.
  subprocessors:
    text: The current list - what each one handles, where it runs, and why - is published at demiton.io/subprocessors
    url: https://demiton.io/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Demiton
provenance_date: '2026-11-09'
provider_name: Demiton
provider_slug: demiton-io
slug: demiton-io-privacy-policy
source_date: '2026-11-09'
source_filename: demiton-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://demiton.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Demiton\naid: demiton-io\nurl: https://demiton.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: We operate as a Data Processor ; you (the Customer) retain the role of Data Controller for all data you\n    bring into the platform.\ndata_categories:\n- category: identifying\n  text: Name, email address, and organisational role of authorised platform users.\n- category: contact\n  text: Name, email address, and organisational role of authorised platform users.\n- category: professional\n  text: Worker names, roles, employment status, and skill records sourced from connected workforce\
  \ management systems\n    (e.g., Assignar).\n- category: financial\n  text: Project financial records, cost codes, budgets, and variance data sourced from connected ERP systems (e.g.,\n    Microsoft Dynamics 365 Business Central).\n- category: behavioral\n  text: Analytics events (page views, feature interactions) via Google Analytics 4, with no advertising or cross-site\n    tracking.\n- category: device\n  text: Technical logs covering API performance, workflow execution outcomes, adapter connectivity, and system health.\n- category: communication\n  text: An email you raise from Outlook. When a user raises an issue from an email in Outlook, Demiton stores that\n    email (and any others attached to the raise) as your organisation’s evidence\npurposes:\n- purpose: Workflow execution\n  text: To run workflows that fetch, transform, and deliver data between your connected systems at your direction.\n- purpose: AI orchestration\n  text: To provide contextually aware responses in the AI\
  \ Studio by grounding prompts with data from your connected\n    systems.\n- purpose: Audit and governance\n  text: To maintain an immutable, append-only audit trail of all workflow executions and data movements for your\n    internal compliance.\n- purpose: Support and diagnostics\n  text: To diagnose connectivity issues, workflow failures, and adapter errors with your connected systems.\n- purpose: Billing\n  text: To calculate usage, process subscription payments, and generate invoices.\nretention:\n- scope: Audit trail logs\n  period: seven years\n  text: Workflow execution and data movement logs are immutable and retained for a minimum of seven years.\nresidency:\n- region: Australia\n  text: All Customer Data is stored and processed within Microsoft Azure Australia East (Sydney) , with failover\n    capability to Australia Southeast (Melbourne).\ntransfers: []\nsubprocessors:\n  url: https://demiton.io/subprocessors\n  text: The current list - what each one handles, where it runs,\
  \ and why - is published at demiton.io/subprocessors\ndpa:\n  available: true\n  url: null\n  text: Customers requiring a multi-region deployment (e.g., for disaster recovery in a nominated jurisdiction)\n    must configure this explicitly and accept an updated Data Processing Agreement (DPA) that reflects the extended\n    residency scope.\ndeletion:\n  route: Request via privacy@demiton.io\n  text: Request deletion of personal information where we have no lawful basis for continued retention, subject\n    to our seven-year audit retention obligation.\nrights:\n- right: Access\n  text: 'Access: Request a copy of personal information we hold about you (Data Subject Access Request - DSAR).'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete personal information.'\n- right: Deletion\n  text: 'Deletion: Request deletion of personal information where we have no lawful basis for continued retention,\n    subject to our seven-year audit retention obligation.'\n\
  - right: Objection\n  text: 'Objection: Object to processing of your personal information for purposes beyond those required to deliver\n    the Service.'\n- right: Data portability\n  text: 'Data portability: Request an export of your organisation''s data in a machine-readable format.'\n- right: Withdraw consent\n  text: Withdraw consent for optional data processing (analytics, Enterprise benchmarking) at any time without affecting\n    your access to the Service.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or Customer Data.\n"
source_yaml_url: https://artifacts.apis.io/demiton-io/privacy/demiton-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Demiton's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Civil Engineering
- Project Management
- Compliance
- MCP
- Artificial Intelligence
- Open Contracting
---
