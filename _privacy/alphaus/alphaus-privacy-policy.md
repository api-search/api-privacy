---
api_specs:
- filename: alphaus-admin-api-openapi.yml
  format: yaml
  label: Alphaus Admin API
  slug: alphaus-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-admin-api-openapi.yml
- filename: alphaus-billing-api-openapi.yml
  format: yaml
  label: Alphaus Billing API
  slug: alphaus-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-billing-api-openapi.yml
- filename: alphaus-cost-api-openapi.yml
  format: yaml
  label: Alphaus Cost API
  slug: alphaus-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-cost-api-openapi.yml
- filename: alphaus-cover-api-openapi.yml
  format: yaml
  label: Alphaus Cover API
  slug: alphaus-cover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-cover-api-openapi.yml
- filename: alphaus-flags-api-openapi.yml
  format: yaml
  label: Alphaus Flags API
  slug: alphaus-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-flags-api-openapi.yml
- filename: alphaus-flow-api-openapi.yml
  format: yaml
  label: Alphaus Flow API
  slug: alphaus-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-flow-api-openapi.yml
- filename: alphaus-guaranteedcommitments-api-openapi.yml
  format: yaml
  label: Alphaus GuaranteedCommitments API
  slug: alphaus-guaranteedcommitments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-guaranteedcommitments-api-openapi.yml
- filename: alphaus-iam-api-openapi.yml
  format: yaml
  label: Alphaus Iam API
  slug: alphaus-iam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-iam-api-openapi.yml
- filename: alphaus-luster-api-openapi.yml
  format: yaml
  label: Alphaus Luster API
  slug: alphaus-luster-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-luster-api-openapi.yml
- filename: alphaus-operations-api-openapi.yml
  format: yaml
  label: Alphaus Operations API
  slug: alphaus-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-operations-api-openapi.yml
- filename: alphaus-organization-api-openapi.yml
  format: yaml
  label: Alphaus Organization API
  slug: alphaus-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-organization-api-openapi.yml
- filename: alphaus-preferences-api-openapi.yml
  format: yaml
  label: Alphaus Preferences API
  slug: alphaus-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-preferences-api-openapi.yml
- filename: alphaus-pricing-api-openapi.yml
  format: yaml
  label: Alphaus Pricing API
  slug: alphaus-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-pricing-api-openapi.yml
- filename: alphaus-prism-api-openapi.yml
  format: yaml
  label: Alphaus Prism API
  slug: alphaus-prism-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-prism-api-openapi.yml
- filename: alphaus-vortex-api-openapi.yml
  format: yaml
  label: Alphaus Vortex API
  slug: alphaus-vortex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaus/openapi/alphaus-vortex-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Email address Telephone number Corporate information (corporate name, location, telephone number)
  - category: device
    text: Device information. The Company may, when the users use the Service on any user’s device, collect the information of the device used by the users (such as the ID information that can identify the device)
  - category: behavioral
    text: Activity log information in the Service. The Company may, in order to maintain and improve the Service or to prevent any fraudulent acts, collect information such as the IP address, date and time of the request by users, and the activity history within the Service
  deletion:
    route: Request to the Company to delete personal information
    text: When the Company is requested by a user to delete the personal information of the said user, if the Company determines that it is necessary to meet the request, the Company shall, after confirming that the request has been made by the user of himself or herself, delete the information and then notify the user of the deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision, maintenance and improvement of the Service
    text: Provision, Maintenance, Improvement of the Service
  - purpose: Notice and response to users
    text: Notice, Response to Users
  - purpose: Advertising and marketing by third parties
    text: To display advertising information etc. that suits the interests and concerns of users; To analyze advertising effectiveness; For market analysis and marketing;
  rights:
  - right: Disclosure
    text: The Company shall, when requested by a user to disclose the personal information under the provisions of the Act on the Protection of Personal Information, make a disclosure to the user without delay
  - right: Correction
    text: correct the contents of personal information under the provisions of the Act on the Protection of Personal Information on the grounds that the personal information is untrue
  - right: Suspension of use
    text: suspend the use of personal information under the provisions of the Act on the Protection of Personal Information on the grounds that the information has been used for a purpose beyond the scope that has been publicly announced beforehand
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alphaus
provenance_date: '2026-11-09'
provider_name: Alphaus
provider_slug: alphaus
slug: alphaus-privacy-policy
source_date: '2026-11-09'
source_filename: alphaus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.alphaus.cloud/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alphaus\naid: alphaus\nurl: https://www.alphaus.cloud/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name Email address Telephone number Corporate information (corporate name, location, telephone number)\n- category: device\n  text: Device information. The Company may, when the users use the Service on any user’s device, collect the information\n    of the device used by the users (such as the ID information that can identify the device)\n- category: behavioral\n  text: Activity log information in the Service. The Company may,\
  \ in order to maintain and improve the Service or\n    to prevent any fraudulent acts, collect information such as the IP address, date and time of the request by\n    users, and the activity history within the Service\npurposes:\n- purpose: Provision, maintenance and improvement of the Service\n  text: Provision, Maintenance, Improvement of the Service\n- purpose: Notice and response to users\n  text: Notice, Response to Users\n- purpose: Advertising and marketing by third parties\n  text: To display advertising information etc. that suits the interests and concerns of users; To analyze advertising\n    effectiveness; For market analysis and marketing;\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the Company to delete personal information\n  text: When the Company is requested by a user to delete the personal information of the said user, if the Company\n    determines\
  \ that it is necessary to meet the request, the Company shall, after confirming that the request has\n    been made by the user of himself or herself, delete the information and then notify the user of the deletion.\nrights:\n- right: Disclosure\n  text: The Company shall, when requested by a user to disclose the personal information under the provisions of\n    the Act on the Protection of Personal Information, make a disclosure to the user without delay\n- right: Correction\n  text: correct the contents of personal information under the provisions of the Act on the Protection of Personal\n    Information on the grounds that the personal information is untrue\n- right: Suspension of use\n  text: suspend the use of personal information under the provisions of the Act on the Protection of Personal Information\n    on the grounds that the information has been used for a purpose beyond the scope that has been publicly announced\n    beforehand\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/alphaus/privacy/alphaus-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
summary_line: 10 quoted statements, read from Alphaus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FinOps
- Cloud Cost Management
- Cloud
- Billing
- Multi-Cloud
- Amazon Web Services
- Microsoft Azure
- GCP
- gRPC
- Cost Optimization
- Reseller Billing
---
