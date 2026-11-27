---
api_specs:
- filename: xcures-application-api-openapi.yml
  format: yaml
  label: xCures Application API
  slug: xcures-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-application-api-openapi.yml
- filename: xcures-checklist-api-openapi.yml
  format: yaml
  label: xCures Checklist API
  slug: xcures-checklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-checklist-api-openapi.yml
- filename: xcures-clinical-concepts-api-openapi.yml
  format: yaml
  label: xCures Clinical Concepts API
  slug: xcures-clinical-concepts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-clinical-concepts-api-openapi.yml
- filename: xcures-document-api-openapi.yml
  format: yaml
  label: xCures Document API
  slug: xcures-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-document-api-openapi.yml
- filename: xcures-fhir-api-openapi.yml
  format: yaml
  label: xCures FHIR API
  slug: xcures-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-fhir-api-openapi.yml
- filename: xcures-project-api-openapi.yml
  format: yaml
  label: xCures Project API
  slug: xcures-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-project-api-openapi.yml
- filename: xcures-query-api-openapi.yml
  format: yaml
  label: xCures Query API
  slug: xcures-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-query-api-openapi.yml
- filename: xcures-reciprocity-template-api-openapi.yml
  format: yaml
  label: xCures Reciprocity Template API
  slug: xcures-reciprocity-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-reciprocity-template-api-openapi.yml
- filename: xcures-subject-api-openapi.yml
  format: yaml
  label: xCures Subject API
  slug: xcures-subject-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-subject-api-openapi.yml
- filename: xcures-summary-api-openapi.yml
  format: yaml
  label: xCures Summary API
  slug: xcures-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-summary-api-openapi.yml
- filename: xcures-oauth-api-openapi.yml
  format: yaml
  label: xCures O Auth API
  slug: xcures-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-oauth-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: you may provide us with your contact information, such as your name, email address, mailing address, and/or phone number
  - category: health
    text: Individually identifiable health information as more fully explained in Section 4 below.
  - category: professional
    text: personal information about your work and education history, contact information
  - category: device
    text: computer browser type, Internet protocol address, pages visited, and average time spent on the site
  deletion:
    route: In-platform Remove My Info / Delete My Info workflow, or email privacy@xcures.com
    text: On the My Profile page, select the red Remove My Info button in the bottom-right corner.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: Provide the Services to you, your health care providers, or other third parties with whom you have a direct relationship
  - purpose: Billing
    text: Bill and collect payment for the Services
  - purpose: Evaluate and improve the Services
    text: Evaluate and improve the Services
  - purpose: De-identified information
    text: Create de-identified information, which we may use for any purpose in accordance with applicable laws, including for product development and/or other purposes for which we may receive remuneration
  residency:
  - region: United States
    text: we only store individually identifiable information or data in our control in data centers located in the United States
  retention:
  - period: null
    scope: Individually identifiable information
    text: We retain individually identifiable information for as long as needed to provide the Services, maintain our information systems, and comply with applicable laws.
  - period: in perpetuity
    scope: De-identified information
    text: In general, we retain de-identified information in perpetuity.
  rights:
  - right: Access a copy
    text: Request a copy of their individually identifiable information.
  - right: Amend, correct or delete
    text: Request that their individually identifiable information be amended, corrected or deleted.
  - right: Direct sharing with third parties
    text: Direct xCures to share a copy of their individually identifiable information with third parties.
  - right: Restrict sharing
    text: Restrict access to copies of their individually identifiable information.
  - right: Revoke authorization
    text: Revoke xCures’ authorization to request health information.
  - right: Accounting of disclosures
    text: Request an accounting of disclosures to third parties.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your individually identifiable information or disclose such information to third parties for such third parties’ marketing purposes without your explicit consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We do not knowingly transfer any health information outside of the United States unless that transfer is subject to an agreement for safeguarding the health information, consistent with applicable medical privacy laws in the United States, including HIPAA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: xCures
provenance_date: '2026-11-10'
provider_name: xCures
provider_slug: xcures
slug: xcures-privacy-policy
source_date: '2026-11-10'
source_filename: xcures-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://xcures.com/privacy-security-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: xCures\naid: xcures\nurl: https://xcures.com/privacy-security-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: you may provide us with your contact information, such as your name, email address, mailing address, and/or\n    phone number\n- category: health\n  text: Individually identifiable health information as more fully explained in Section 4 below.\n- category: professional\n  text: personal information about your work and education history, contact information\n- category: device\n  text: computer browser type, Internet protocol\
  \ address, pages visited, and average time spent on the site\npurposes:\n- purpose: Provide the Services\n  text: Provide the Services to you, your health care providers, or other third parties with whom you have a direct\n    relationship\n- purpose: Billing\n  text: Bill and collect payment for the Services\n- purpose: Evaluate and improve the Services\n  text: Evaluate and improve the Services\n- purpose: De-identified information\n  text: Create de-identified information, which we may use for any purpose in accordance with applicable laws, including\n    for product development and/or other purposes for which we may receive remuneration\nretention:\n- scope: Individually identifiable information\n  period: null\n  text: We retain individually identifiable information for as long as needed to provide the Services, maintain\n    our information systems, and comply with applicable laws.\n- scope: De-identified information\n  period: in perpetuity\n  text: In general, we retain de-identified\
  \ information in perpetuity.\nresidency:\n- region: United States\n  text: we only store individually identifiable information or data in our control in data centers located in the\n    United States\ntransfers:\n- mechanism: other\n  text: We do not knowingly transfer any health information outside of the United States unless that transfer is\n    subject to an agreement for safeguarding the health information, consistent with applicable medical privacy\n    laws in the United States, including HIPAA.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-platform Remove My Info / Delete My Info workflow, or email privacy@xcures.com\n  text: On the My Profile page, select the red Remove My Info button in the bottom-right corner.\nrights:\n- right: Access a copy\n  text: Request a copy of their individually identifiable information.\n- right: Amend, correct or delete\n  text: Request that their individually identifiable information\
  \ be amended, corrected or deleted.\n- right: Direct sharing with third parties\n  text: Direct xCures to share a copy of their individually identifiable information with third parties.\n- right: Restrict sharing\n  text: Restrict access to copies of their individually identifiable information.\n- right: Revoke authorization\n  text: Revoke xCures’ authorization to request health information.\n- right: Accounting of disclosures\n  text: Request an accounting of disclosures to third parties.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your individually identifiable information or disclose such information to third parties\n    for such third parties’ marketing purposes without your explicit consent.\n"
source_yaml_url: https://artifacts.apis.io/xcures/privacy/xcures-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from xCures's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- Medical Records
- Interoperability
- FHIR
- Oncology
- Real-World Data
- Clinical Data
- Artificial Intelligence
- TEFCA
- Carequality
- Patient Data
- HITRUST
- HIPAA
- A2A
---
