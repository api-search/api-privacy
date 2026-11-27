---
api_specs:
- filename: ayurak-com-openapi-generated.yml
  format: yaml
  label: ayurak-com API
  slug: ayurak-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayurak-com/openapi/_ae-authored/ayurak-com-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name Email address Company name and details Job title/role Password (stored in hashed form only) Phone number (optional)
  - category: device
    text: Browser type, operating system, and device information
  - category: behavioral
    text: Feature usage patterns and frequency
  - category: location
    text: 'Geolocation: Approximate location derived from IP address'
  - category: communication
    text: Support tickets and correspondence
  - category: other
    text: Cloud resource metadata (resource types, names, configurations, regions, tags)
  deletion:
    route: Contact DPO at privacy@aristiun.com
    text: To exercise any of these rights, contact our DPO at privacy@aristiun.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing cloud security scanning and compliance analysis
    text: Providing cloud security scanning, threat modeling, and compliance analysis
  - purpose: Platform improvement
    text: Analyzing usage patterns to improve features and performance
  - purpose: Marketing communications
    text: Sending marketing communications (with your consent, which you may withdraw at any time)
  - purpose: Billing
    text: Processing billing and subscription management (via Stripe)
  residency:
  - region: United States (us-central1)
    text: All customer data is hosted on Google Cloud Platform (GCP) in the us-central1 region (Council Bluffs, Iowa, United States).
  retention:
  - period: Duration of active account + 90 days after account deletion
    scope: Account data
    text: Account data (profile, settings) | Duration of active account + 90 days after account deletion
  - period: 1 year from generation date
    scope: Scan results and reports
    text: Scan results and reports | 1 year from generation date
  - period: 30 days
    scope: Application and access logs
    text: Application and access logs | 30 days
  - period: As required by Dutch tax law (7 years)
    scope: Billing records
    text: Billing records | As required by Dutch tax law (7 years)
  rights:
  - right: Access
    text: You may request a copy of the personal data we hold about you.
  - right: Rectification
    text: You may request correction of inaccurate or incomplete personal data.
  - right: Erasure
    text: You may request deletion of your personal data, subject to legal retention obligations.
  - right: Portability
    text: You may request your personal data in a structured, commonly used, machine-readable format.
  - right: Object
    text: You may object to processing based on legitimate interest, including profiling and direct marketing.
  - right: Restriction
    text: You may request that we restrict processing of your personal data in certain circumstances.
  - right: Withdraw consent
    text: Where processing is based on consent, you may withdraw consent at any time without affecting the lawfulness of prior processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information for cross-context behavioral advertising purposes.
  subprocessors:
    text: We maintain an up-to-date list of sub-processors. Under our Data Processing Agreement, customers are notified of changes and have the right to object to new sub-processors.
    url: null
  transfers:
  - mechanism: DPF
    text: 'EU-U.S. Data Privacy Framework (DPF): For transfers to U.S.-based processors certified under the DPF'
  - mechanism: SCC
    text: 'EU Commission-approved SCCs (Module 2: Controller-to-Processor) for transfers to processors not covered by adequacy decisions'
  - mechanism: adequacy
    text: 'Adequacy Decisions: Where the European Commission has determined that a third country provides an adequate level of data protection'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ayurak-com
provenance_date: '2026-11-09'
provider_name: ayurak-com
provider_slug: ayurak-com
slug: ayurak-com-privacy-policy
source_date: '2026-11-09'
source_filename: ayurak-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ayurak.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ayurak-com\naid: ayurak-com\nurl: https://ayurak.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Full name Email address Company name and details Job title/role Password (stored in hashed form only) Phone\n    number (optional)\n- category: device\n  text: Browser type, operating system, and device information\n- category: behavioral\n  text: Feature usage patterns and frequency\n- category: location\n  text: 'Geolocation: Approximate location derived from IP address'\n- category: communication\n  text: Support tickets\
  \ and correspondence\n- category: other\n  text: Cloud resource metadata (resource types, names, configurations, regions, tags)\npurposes:\n- purpose: Providing cloud security scanning and compliance analysis\n  text: Providing cloud security scanning, threat modeling, and compliance analysis\n- purpose: Platform improvement\n  text: Analyzing usage patterns to improve features and performance\n- purpose: Marketing communications\n  text: Sending marketing communications (with your consent, which you may withdraw at any time)\n- purpose: Billing\n  text: Processing billing and subscription management (via Stripe)\nretention:\n- scope: Account data\n  period: Duration of active account + 90 days after account deletion\n  text: Account data (profile, settings) | Duration of active account + 90 days after account deletion\n- scope: Scan results and reports\n  period: 1 year from generation date\n  text: Scan results and reports | 1 year from generation date\n- scope: Application and access\
  \ logs\n  period: 30 days\n  text: Application and access logs | 30 days\n- scope: Billing records\n  period: As required by Dutch tax law (7 years)\n  text: Billing records | As required by Dutch tax law (7 years)\nresidency:\n- region: United States (us-central1)\n  text: All customer data is hosted on Google Cloud Platform (GCP) in the us-central1 region (Council Bluffs, Iowa,\n    United States).\ntransfers:\n- mechanism: DPF\n  text: 'EU-U.S. Data Privacy Framework (DPF): For transfers to U.S.-based processors certified under the DPF'\n- mechanism: SCC\n  text: 'EU Commission-approved SCCs (Module 2: Controller-to-Processor) for transfers to processors not covered\n    by adequacy decisions'\n- mechanism: adequacy\n  text: 'Adequacy Decisions: Where the European Commission has determined that a third country provides an adequate\n    level of data protection'\nsubprocessors:\n  url: null\n  text: We maintain an up-to-date list of sub-processors. Under our Data Processing Agreement,\
  \ customers are notified\n    of changes and have the right to object to new sub-processors.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact DPO at privacy@aristiun.com\n  text: To exercise any of these rights, contact our DPO at privacy@aristiun.com .\nrights:\n- right: Access\n  text: You may request a copy of the personal data we hold about you.\n- right: Rectification\n  text: You may request correction of inaccurate or incomplete personal data.\n- right: Erasure\n  text: You may request deletion of your personal data, subject to legal retention obligations.\n- right: Portability\n  text: You may request your personal data in a structured, commonly used, machine-readable format.\n- right: Object\n  text: You may object to processing based on legitimate interest, including profiling and direct marketing.\n- right: Restriction\n  text: You may request that we restrict processing of your personal data in certain circumstances.\n- right: Withdraw consent\n\
  \  text: Where processing is based on consent, you may withdraw consent at any time without affecting the lawfulness\n    of prior processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information for cross-context behavioral advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/ayurak-com/privacy/ayurak-com-privacy-policy.yml
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
summary_line: 28 quoted statements, read from ayurak-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Healthcare
- Emergency Response
- Technology
---
