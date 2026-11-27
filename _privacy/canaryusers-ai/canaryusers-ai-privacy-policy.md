---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: other
    text: URLs you submit for scanning and the public page content fetched from them
  - category: identifying
    text: basic account and billing details (handled by Stripe)
  - category: behavioral
    text: standard usage/diagnostic logs
  deletion:
    route: email privacy@canaryusers.ai
    text: You can request access to or deletion of your data at privacy@canaryusers.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run scans and generate reports
    text: To run scans, generate reports, provide and improve the Service
  - purpose: aggregate model calibration
    text: in aggregate and de-identified form — to calibrate our models
  rights:
  - right: access and deletion
    text: You can request access to or deletion of your data at privacy@canaryusers.ai .
  role:
    text: Your data is controlled by Salescadia, Inc. (operator of CanaryUsers).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your personal data.
  subprocessors:
    text: We use third-party processors including Stripe (payments), our hosting/infrastructure provider, and AI model providers used to generate report narratives.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CanaryUsers
provenance_date: '2026-11-09'
provider_name: CanaryUsers
provider_slug: canaryusers-ai
slug: canaryusers-ai-privacy-policy
source_date: '2026-11-09'
source_filename: canaryusers-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.canaryusers.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CanaryUsers\naid: canaryusers-ai\nurl: https://www.canaryusers.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Your data is controlled by Salescadia, Inc. (operator of CanaryUsers).\ndata_categories:\n- category: other\n  text: URLs you submit for scanning and the public page content fetched from them\n- category: identifying\n  text: basic account and billing details (handled by Stripe)\n- category: behavioral\n  text: standard usage/diagnostic logs\npurposes:\n- purpose: run scans and generate reports\n  text: To run scans, generate reports, provide and improve the Service\n\
  - purpose: aggregate model calibration\n  text: in aggregate and de-identified form — to calibrate our models\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use third-party processors including Stripe (payments), our hosting/infrastructure provider, and AI model\n    providers used to generate report narratives.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@canaryusers.ai\n  text: You can request access to or deletion of your data at privacy@canaryusers.ai .\nrights:\n- right: access and deletion\n  text: You can request access to or deletion of your data at privacy@canaryusers.ai .\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/canaryusers-ai/privacy/canaryusers-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from CanaryUsers's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Testing
- User Experience
- Software-as-a-Service
- CanaryUsers
---
