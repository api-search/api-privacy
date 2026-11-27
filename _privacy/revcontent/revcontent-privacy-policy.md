---
api_specs:
- filename: revcontent-access-api-openapi.yml
  format: yaml
  label: RevContent Access API
  slug: revcontent-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-access-api-openapi.yml
- filename: revcontent-ccpa-api-openapi.yml
  format: yaml
  label: RevContent CCPA API
  slug: revcontent-ccpa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-ccpa-api-openapi.yml
- filename: revcontent-content-api-openapi.yml
  format: yaml
  label: RevContent Content API
  slug: revcontent-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-content-api-openapi.yml
- filename: revcontent-conversions-api-openapi.yml
  format: yaml
  label: RevContent Conversions API
  slug: revcontent-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-conversions-api-openapi.yml
- filename: revcontent-helpers-api-openapi.yml
  format: yaml
  label: RevContent Helpers API
  slug: revcontent-helpers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-helpers-api-openapi.yml
- filename: revcontent-targeting-api-openapi.yml
  format: yaml
  label: RevContent Targeting API
  slug: revcontent-targeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-targeting-api-openapi.yml
- filename: revcontent-widget-internal-content-api-openapi.yml
  format: yaml
  label: RevContent Widget Internal Content API
  slug: revcontent-widget-internal-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-widget-internal-content-api-openapi.yml
- filename: revcontent-widget-optimizer-api-openapi.yml
  format: yaml
  label: RevContent Widget Optimizer API
  slug: revcontent-widget-optimizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-widget-optimizer-api-openapi.yml
- filename: revcontent-campaigns-api-openapi.yml
  format: yaml
  label: RevContent Campaigns API
  slug: revcontent-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-campaigns-api-openapi.yml
- filename: revcontent-widget-api-openapi.yml
  format: yaml
  label: RevContent Widget API
  slug: revcontent-widget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-widget-api-openapi.yml
- filename: revcontent-subaccounts-api-openapi.yml
  format: yaml
  label: RevContent Subaccounts API
  slug: revcontent-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revcontent/openapi/revcontent-subaccounts-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect your IP address and user agent string.
  - category: device
    text: identifiers assigned to your browser version and/or device type
  - category: behavioral
    text: We collect information about whether you view various elements of the Services as well as the content and ads that you click on within the Services.
  - category: location
    text: we infer operating system, ISP, broad geo-location
  - category: contact
    text: Advertisers and publishers (the “Clients”) may provide contact information through our Site
  deletion:
    route: online request, email, or toll-free phone
    text: To exercise any of the above rights, you or your authorized agent may contact us and submit the required verifying information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: personalized recommendations and ads
    text: In order to help provide recommendations and promoted content that is relevant to your interests as well as compatible with your device
  - purpose: measure and report on user interaction
    text: to understand, measure, and report on how users interact with the Services
  - purpose: invoicing and billing
    text: We will also use the information we collect from Clients for invoicing and billing purposes.
  - purpose: sharing with programmatic demand partners
    text: With unaffiliated third party programmatic demand partners in order to serve tailored sponsored recommendations
  retention:
  - period: up to 12 months
    scope: Consumer data collected from Services
    text: We retain Consumer data collected from our Services for up to 12 months.
  rights:
  - right: access
    text: Know/Access. You can request the following information about how we have collected and used your Personal Information
  - right: delete
    text: Delete. You can ask us to delete the Personal Information that we have collected from you.
  - right: correct
    text: Correct. You can ask us to correct inaccurate Personal Information that we maintain about you.
  - right: opt out of sales, sharing, targeted advertising
    text: Opt-out of sales/sharing. If we “sell” or “share” your Personal Information, you can opt-out.
  - right: portability
    text: Port. You can request to obtain a copy of Personal Information that you have previously provided to us in a portable and, to the extent technically feasible, readily usable format.
  role:
    text: This Services Privacy Policy explains how information about you is collected, used and disclosed by RevContent, LLC (“RevContent”) via its Services.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: If we “sell” or “share” your Personal Information, you can opt-out.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: we comply with the EU-U.S. Data Privacy Framework, the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RevContent
provenance_date: '2026-11-10'
provider_name: RevContent
provider_slug: revcontent
slug: revcontent-privacy-policy
source_date: '2026-11-10'
source_filename: revcontent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.revcontent.com/policy/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RevContent\naid: revcontent\nurl: https://www.revcontent.com/policy/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Services Privacy Policy explains how information about you is collected, used and disclosed by RevContent,\n    LLC (“RevContent”) via its Services.\ndata_categories:\n- category: identifying\n  text: We collect your IP address and user agent string.\n- category: device\n  text: identifiers assigned to your browser version and/or device type\n- category: behavioral\n  text: We collect information about whether you view various elements of the Services as well\
  \ as the content and\n    ads that you click on within the Services.\n- category: location\n  text: we infer operating system, ISP, broad geo-location\n- category: contact\n  text: Advertisers and publishers (the “Clients”) may provide contact information through our Site\npurposes:\n- purpose: personalized recommendations and ads\n  text: In order to help provide recommendations and promoted content that is relevant to your interests as well\n    as compatible with your device\n- purpose: measure and report on user interaction\n  text: to understand, measure, and report on how users interact with the Services\n- purpose: invoicing and billing\n  text: We will also use the information we collect from Clients for invoicing and billing purposes.\n- purpose: sharing with programmatic demand partners\n  text: With unaffiliated third party programmatic demand partners in order to serve tailored sponsored recommendations\nretention:\n- scope: Consumer data collected from Services\n  period:\
  \ up to 12 months\n  text: We retain Consumer data collected from our Services for up to 12 months.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: we comply with the EU-U.S. Data Privacy Framework, the UK Extension to the EU-U.S. DPF, and the Swiss-U.S.\n    Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: online request, email, or toll-free phone\n  text: To exercise any of the above rights, you or your authorized agent may contact us and submit the required\n    verifying information\nrights:\n- right: access\n  text: Know/Access. You can request the following information about how we have collected and used your Personal\n    Information\n- right: delete\n  text: Delete. You can ask us to delete the Personal Information that we have collected from you.\n- right: correct\n  text: Correct. You can ask us to correct inaccurate Personal Information that we maintain about you.\n- right: opt out\
  \ of sales, sharing, targeted advertising\n  text: Opt-out of sales/sharing. If we “sell” or “share” your Personal Information, you can opt-out.\n- right: portability\n  text: Port. You can request to obtain a copy of Personal Information that you have previously provided to us in\n    a portable and, to the extent technically feasible, readily usable format.\nsale_or_sharing:\n  stance: conditional\n  text: If we “sell” or “share” your Personal Information, you can opt-out.\n"
source_yaml_url: https://artifacts.apis.io/revcontent/privacy/revcontent-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from RevContent's own page on 2026-11-10.
synthetic: false
tags:
- Native Advertising
- Content Recommendation
- Ad Network
- Publisher Monetization
- Programmatic Advertising
- AdTech
- Campaign Management
- Audience Targeting
- Conversion Tracking
- Marketing
---
