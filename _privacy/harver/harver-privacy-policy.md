---
api_specs:
- filename: harver-accounts-api-openapi.yml
  format: yaml
  label: Harver Accounts API
  slug: harver-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-accounts-api-openapi.yml
- filename: harver-applications-api-openapi.yml
  format: yaml
  label: Harver Applications API
  slug: harver-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-applications-api-openapi.yml
- filename: harver-candidate-statuses-api-openapi.yml
  format: yaml
  label: Harver Candidate Statuses API
  slug: harver-candidate-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-candidate-statuses-api-openapi.yml
- filename: harver-candidateapplications-api-openapi.yml
  format: yaml
  label: Harver Candidate Applications API
  slug: harver-candidateapplications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-candidateapplications-api-openapi.yml
- filename: harver-scheduling-api-openapi.yml
  format: yaml
  label: Harver Scheduling API
  slug: harver-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-scheduling-api-openapi.yml
- filename: harver-user-profile-api-openapi.yml
  format: yaml
  label: Harver User Profile API
  slug: harver-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-user-profile-api-openapi.yml
- filename: harver-vacancies-api-openapi.yml
  format: yaml
  label: Harver Vacancies API
  slug: harver-vacancies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-vacancies-api-openapi.yml
- filename: harver-webhook-api-openapi.yml
  format: yaml
  label: Harver Webhook API
  slug: harver-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-webhook-api-openapi.yml
- filename: harver-oauth-api-openapi.yml
  format: yaml
  label: Harver OAUTH API
  slug: harver-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harver/openapi/harver-oauth-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: First name; Last name; Phone Number; E-mail address; Your question.
  - category: professional
    text: Company name; First name; Last name; Company E-mail address;
  - category: demographic
    text: Date of birth (age); Level of education.
  - category: identifying
    text: Name; Home address; References; E-mail address; Phone Number; Picture; Cover Letter; Resume; LinkedIn Profile;
  - category: device
    text: Device and browser; Requests and responses sent from and to your device;
  - category: behavioral
    text: Behavior on the Website.
  deletion:
    route: Email privacy@harver.com
    text: We will delete your personal data, unless we have a legal obligation to keep processing your personal data.
  dpa:
    available: null
    text: We only provide your personal data, subject to data processing agreements, which state that the sub-processors must keep your personal data confidential
    url: null
  purposes:
  - purpose: Replying to website questions
    text: We will process your personal data based on the performance of a contract (to reply to your enquiries)
  - purpose: Recruitment
    text: We process your personal data based on our legitimate interests for recruitment purposes.
  - purpose: Newsletter and content
    text: We will process your personal data based on consent.
  - purpose: User testing
    text: We process your personal data based on our legitimate interests for User Testing purposes and to improve our product.
  retention:
  - period: eight (8) weeks
    scope: Job applicants
    text: We will store your personal data up to eight (8) weeks after the application process has ended.
  - period: one (1) year
    scope: Job applicants with permission
    text: If you provide Harver permission to store your personal data for a longer period, we will store your personal data up to one (1) year.
  rights:
  - right: Right to be informed
    text: You have the right to know if we use (i.e. process) your personal data.
  - right: Right of access
    text: you have the right to access your personal data and retain a copy.
  - right: Right to rectification
    text: If your personal data is incorrect, you have the right to ask us to rectify your personal data.
  - right: Right to erasure
    text: If you want us to delete your personal data, you have the right to request us to delete your personal data.
  - right: Right to restrict processing
    text: you can request us to restrict your personal data.
  - right: Right to data portability
    text: You can request us for an export of all the personal data that is processed by Harver.
  - right: Right to object
    text: The right to object (when processing under legitimate interest).
  role:
    text: Harver is considered a “Processor” for this data, meaning that we only handle the data on behalf of the hiring company.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We (can) use certain sub-processors, but these sub-processors only process/use the personal data that is strictly necessary for these sub-processors to complete their specific task or service.
    url: null
  transfers:
  - mechanism: other
    text: If you are located in the European Economic Area, we reserve the right to transfer your personal data to a country outside the European Economic Area or international organisation.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Harver
provenance_date: '2026-11-09'
provider_name: Harver
provider_slug: harver
slug: harver-privacy-policy
source_date: '2026-11-09'
source_filename: harver-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://harver.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Harver\naid: harver\nurl: https://harver.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Harver is considered a “Processor” for this data, meaning that we only handle the data on behalf of the\n    hiring company.\ndata_categories:\n- category: contact\n  text: First name; Last name; Phone Number; E-mail address; Your question.\n- category: professional\n  text: Company name; First name; Last name; Company E-mail address;\n- category: demographic\n  text: Date of birth (age); Level of education.\n- category: identifying\n  text: Name; Home address; References; E-mail address;\
  \ Phone Number; Picture; Cover Letter; Resume; LinkedIn Profile;\n- category: device\n  text: Device and browser; Requests and responses sent from and to your device;\n- category: behavioral\n  text: Behavior on the Website.\npurposes:\n- purpose: Replying to website questions\n  text: We will process your personal data based on the performance of a contract (to reply to your enquiries)\n- purpose: Recruitment\n  text: We process your personal data based on our legitimate interests for recruitment purposes.\n- purpose: Newsletter and content\n  text: We will process your personal data based on consent.\n- purpose: User testing\n  text: We process your personal data based on our legitimate interests for User Testing purposes and to improve\n    our product.\nretention:\n- scope: Job applicants\n  period: eight (8) weeks\n  text: We will store your personal data up to eight (8) weeks after the application process has ended.\n- scope: Job applicants with permission\n  period: one (1) year\n\
  \  text: If you provide Harver permission to store your personal data for a longer period, we will store your personal\n    data up to one (1) year.\nresidency: []\ntransfers:\n- mechanism: other\n  text: If you are located in the European Economic Area, we reserve the right to transfer your personal data to\n    a country outside the European Economic Area or international organisation.\nsubprocessors:\n  url: null\n  text: We (can) use certain sub-processors, but these sub-processors only process/use the personal data that is\n    strictly necessary for these sub-processors to complete their specific task or service.\ndpa:\n  available: null\n  url: null\n  text: We only provide your personal data, subject to data processing agreements, which state that the sub-processors\n    must keep your personal data confidential\ndeletion:\n  route: Email privacy@harver.com\n  text: We will delete your personal data, unless we have a legal obligation to keep processing your personal data.\nrights:\n\
  - right: Right to be informed\n  text: You have the right to know if we use (i.e. process) your personal data.\n- right: Right of access\n  text: you have the right to access your personal data and retain a copy.\n- right: Right to rectification\n  text: If your personal data is incorrect, you have the right to ask us to rectify your personal data.\n- right: Right to erasure\n  text: If you want us to delete your personal data, you have the right to request us to delete your personal data.\n- right: Right to restrict processing\n  text: you can request us to restrict your personal data.\n- right: Right to data portability\n  text: You can request us for an export of all the personal data that is processed by Harver.\n- right: Right to object\n  text: The right to object (when processing under legitimate interest).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/harver/privacy/harver-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 24 quoted statements, read from Harver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Recruiting
- Hiring
- Talent Intelligence
- Pre-Employment Assessment
- Candidate Experience
- Applicant Tracking
---
