---
api_specs:
- filename: yoti-accounts-api-openapi.yml
  format: yaml
  label: Yoti Accounts API
  slug: yoti-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-accounts-api-openapi.yml
- filename: yoti-ai-api-openapi.yml
  format: yaml
  label: Yoti AI API
  slug: yoti-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-ai-api-openapi.yml
- filename: yoti-oauth-api-openapi.yml
  format: yaml
  label: Yoti OAuth API
  slug: yoti-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-oauth-api-openapi.yml
- filename: yoti-path-api-openapi.yml
  format: yaml
  label: Yoti Path API
  slug: yoti-path-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-path-api-openapi.yml
- filename: yoti-poa-api-openapi.yml
  format: yaml
  label: Yoti Poa API
  slug: yoti-poa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-poa-api-openapi.yml
- filename: yoti-sessions-api-openapi.yml
  format: yaml
  label: Yoti Sessions API
  slug: yoti-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-sessions-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: the data could include your selfie (e.g. for age estimation), your ID Document (e.g. for identity verification) or your address (e.g. for KYC)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: creating Digital ID or completing checks
    text: Yoti only collects the minimum data needed for the purpose of creating your Digital ID or for completing an age or identity verification check on behalf of our Clients.
  - purpose: fraud prevention
    text: Yoti also shares data with our trusted 3rd party suppliers for limited purposes such as fraud prevention
  retention:
  - period: null
    scope: personal data after age check
    text: Yoti deletes your personal data following completion of the age check.
  - period: 28 days
    scope: ID Document for manual verification
    text: If you added an ID Document we may keep this for 28 days for manual verification.
  rights:
  - right: access/download own data
    text: If you are using the Digital ID App you can download your data at any time in your app settings.
  role:
    text: Yoti is the controller of the data used when you download the Digital ID app because we decide the means and purposes of processing. But when it comes to our age and identity verification products, in most cases, Yoti is a processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Yoti does not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yoti
provenance_date: '2026-11-10'
provider_name: Yoti
provider_slug: yoti
slug: yoti-privacy-policy
source_date: '2026-11-10'
source_filename: yoti-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.yoti.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yoti\naid: yoti\nurl: https://www.yoti.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Yoti is the controller of the data used when you download the Digital ID app because we decide the means\n    and purposes of processing. But when it comes to our age and identity verification products, in most cases,\n    Yoti is a processor\ndata_categories:\n- category: identifying\n  text: the data could include your selfie (e.g. for age estimation), your ID Document (e.g. for identity verification)\n    or your address (e.g. for KYC)\npurposes:\n- purpose: creating Digital ID or completing checks\n\
  \  text: Yoti only collects the minimum data needed for the purpose of creating your Digital ID or for completing\n    an age or identity verification check on behalf of our Clients.\n- purpose: fraud prevention\n  text: Yoti also shares data with our trusted 3rd party suppliers for limited purposes such as fraud prevention\nretention:\n- scope: personal data after age check\n  period: null\n  text: Yoti deletes your personal data following completion of the age check.\n- scope: ID Document for manual verification\n  period: 28 days\n  text: If you added an ID Document we may keep this for 28 days for manual verification.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access/download own data\n  text: If you are using the Digital ID App you can download your data at any time in your app settings.\nsale_or_sharing:\n  stance: prohibited\n  text: Yoti does\
  \ not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/yoti/privacy/yoti-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 8 quoted statements, read from Yoti's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Verification
- DigitalID
- SDK
---
