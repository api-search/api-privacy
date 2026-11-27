---
api_specs:
- filename: annsa-ai-agents-api-openapi.yml
  format: yaml
  label: Annsa Agents API
  slug: annsa-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-agents-api-openapi.yml
- filename: annsa-ai-ingest-api-openapi.yml
  format: yaml
  label: Annsa Ingest API
  slug: annsa-ai-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-ingest-api-openapi.yml
- filename: annsa-ai-service-api-openapi.yml
  format: yaml
  label: Annsa Service API
  slug: annsa-ai-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/annsa-ai/openapi/annsa-ai-service-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, name and profile picture (from Google sign-in)
  - category: identifying
    text: Customer identifiers (names, emails, or IDs if included in your data)
  - category: financial
    text: Billing information (processed securely by Stripe; we never see or store credit card details)
  - category: location
    text: IP addresses and approximate location (country/region level)
  - category: device
    text: Browser type, operating system, and device information
  - category: behavioral
    text: Pages visited, features used, and interaction patterns
  - category: communication
    text: Messages from channels you select for feedback collection
  - category: professional
    text: Company or organization name (optional)
  deletion:
    route: Settings → Delete Workspace or email privacy@annsa.ai
    text: Request immediate deletion at privacy@annsa.ai or via Settings → Delete Workspace.
  dpa:
    available: true
    text: 'Enterprise customers requiring a DPA for GDPR compliance: contact privacy@annsa.ai .'
    url: null
  purposes:
  - purpose: Provide the service
    text: Operating Annsa, processing feedback, generating specs
  - purpose: AI processing
    text: Classifying feedback and generating specifications using AI
  - purpose: Behavioral learning
    text: Learning from your actions to improve prioritization and spec quality
  - purpose: Service improvement
    text: Analyzing usage patterns to improve Annsa
  - purpose: Analytics
    text: Understanding how users interact with Annsa
  residency:
  - region: Singapore
    text: 'Singapore: Where our main database is hosted'
  - region: Australia
    text: 'Australia: Where Annsa is headquartered and our application servers run'
  - region: United States
    text: 'United States: Where our AI providers and some cloud services are located'
  retention:
  - period: Deleted after 30 days
    scope: Account information
    text: Account Information Duration of account Deleted after 30 days
  - period: 90 days, then compressed to quarterly summaries
    scope: Behavioral memory
    text: Behavioral Memory 90 days, then compressed to quarterly summaries
  - period: 24 months
    scope: Usage analytics
    text: Usage Analytics 24 months Anonymized or deleted
  - period: As required by law (typically 7 years)
    scope: Payment records
    text: Payment Records As required by law (typically 7 years)
  - period: 90 days rolling
    scope: System backups
    text: System Backups 90 days rolling Purged within 90 days
  rights:
  - right: Access
    text: 'Access: Settings → Account → Export Data'
  - right: Deletion
    text: 'Deletion: Settings → Account → Delete Workspace'
  - right: Correction
    text: 'Correction: Update inaccurate information'
  - right: Withdraw consent
    text: 'Withdraw Consent: Opt out of analytics cookies via cookie settings'
  - right: Portability, restriction, objection (EU/UK GDPR)
    text: Portability, restriction, objection to legitimate interest processing, and human review of automated decisions.
  - right: Know, delete, opt-out, non-discrimination (CCPA/CPRA)
    text: Know, delete, opt-out (we do not sell data), and non-discrimination.
  role:
    text: 'Data Controller: Circuit Software Pty Ltd, Sydney, NSW, Australia'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: 4. Data Sharing and Sub-processors Category Providers Purpose Cloud Infrastructure AWS, Supabase, Vercel, CloudFront Hosting, database, CDN
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers outside of the EEA or UK, we rely on Standard Contractual Clauses and Data Processing Agreements with all sub-processors.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Annsa
provenance_date: '2026-11-09'
provider_name: Annsa
provider_slug: annsa-ai
slug: annsa-ai-privacy-policy
source_date: '2026-11-09'
source_filename: annsa-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://annsa.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Annsa\naid: annsa-ai\nurl: https://annsa.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: Circuit Software Pty Ltd, Sydney, NSW, Australia'\ndata_categories:\n- category: contact\n  text: Email address, name and profile picture (from Google sign-in)\n- category: identifying\n  text: Customer identifiers (names, emails, or IDs if included in your data)\n- category: financial\n  text: Billing information (processed securely by Stripe; we never see or store credit card details)\n- category: location\n  text: IP addresses and approximate location (country/region level)\n\
  - category: device\n  text: Browser type, operating system, and device information\n- category: behavioral\n  text: Pages visited, features used, and interaction patterns\n- category: communication\n  text: Messages from channels you select for feedback collection\n- category: professional\n  text: Company or organization name (optional)\npurposes:\n- purpose: Provide the service\n  text: Operating Annsa, processing feedback, generating specs\n- purpose: AI processing\n  text: Classifying feedback and generating specifications using AI\n- purpose: Behavioral learning\n  text: Learning from your actions to improve prioritization and spec quality\n- purpose: Service improvement\n  text: Analyzing usage patterns to improve Annsa\n- purpose: Analytics\n  text: Understanding how users interact with Annsa\nretention:\n- scope: Account information\n  period: Deleted after 30 days\n  text: Account Information Duration of account Deleted after 30 days\n- scope: Behavioral memory\n  period: 90 days,\
  \ then compressed to quarterly summaries\n  text: Behavioral Memory 90 days, then compressed to quarterly summaries\n- scope: Usage analytics\n  period: 24 months\n  text: Usage Analytics 24 months Anonymized or deleted\n- scope: Payment records\n  period: As required by law (typically 7 years)\n  text: Payment Records As required by law (typically 7 years)\n- scope: System backups\n  period: 90 days rolling\n  text: System Backups 90 days rolling Purged within 90 days\nresidency:\n- region: Singapore\n  text: 'Singapore: Where our main database is hosted'\n- region: Australia\n  text: 'Australia: Where Annsa is headquartered and our application servers run'\n- region: United States\n  text: 'United States: Where our AI providers and some cloud services are located'\ntransfers:\n- mechanism: SCC\n  text: For transfers outside of the EEA or UK, we rely on Standard Contractual Clauses and Data Processing Agreements\n    with all sub-processors.\nsubprocessors:\n  url: null\n  text: 4. Data\
  \ Sharing and Sub-processors Category Providers Purpose Cloud Infrastructure AWS, Supabase, Vercel,\n    CloudFront Hosting, database, CDN\ndpa:\n  available: true\n  url: null\n  text: 'Enterprise customers requiring a DPA for GDPR compliance: contact privacy@annsa.ai .'\ndeletion:\n  route: Settings → Delete Workspace or email privacy@annsa.ai\n  text: Request immediate deletion at privacy@annsa.ai or via Settings → Delete Workspace.\nrights:\n- right: Access\n  text: 'Access: Settings → Account → Export Data'\n- right: Deletion\n  text: 'Deletion: Settings → Account → Delete Workspace'\n- right: Correction\n  text: 'Correction: Update inaccurate information'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Opt out of analytics cookies via cookie settings'\n- right: Portability, restriction, objection (EU/UK GDPR)\n  text: Portability, restriction, objection to legitimate interest processing, and human review of automated decisions.\n- right: Know, delete, opt-out, non-discrimination\
  \ (CCPA/CPRA)\n  text: Know, delete, opt-out (we do not sell data), and non-discrimination.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/annsa-ai/privacy/annsa-ai-privacy-policy.yml
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
summary_line: 33 quoted statements, read from Annsa's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Customer Management
- Agent Teams
- Artificial Intelligence
- Software-as-a-Service
---
