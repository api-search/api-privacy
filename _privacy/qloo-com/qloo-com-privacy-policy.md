---
api_specs:
- filename: qloo-com-analysis-api-openapi.yml
  format: yaml
  label: Qloo Analysis API
  slug: qloo-com-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-analysis-api-openapi.yml
- filename: qloo-com-audiences-api-openapi.yml
  format: yaml
  label: Qloo Audiences API
  slug: qloo-com-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-audiences-api-openapi.yml
- filename: qloo-com-entities-api-openapi.yml
  format: yaml
  label: Qloo Entities API
  slug: qloo-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-entities-api-openapi.yml
- filename: qloo-com-info-api-openapi.yml
  format: yaml
  label: Qloo Info API
  slug: qloo-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-info-api-openapi.yml
- filename: qloo-com-insights-api-openapi.yml
  format: yaml
  label: Qloo Insights API
  slug: qloo-com-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-insights-api-openapi.yml
- filename: qloo-com-search-api-openapi.yml
  format: yaml
  label: Qloo Search API
  slug: qloo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-search-api-openapi.yml
- filename: qloo-com-tags-api-openapi.yml
  format: yaml
  label: Qloo Tags API
  slug: qloo-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-tags-api-openapi.yml
- filename: qloo-com-trends-api-openapi.yml
  format: yaml
  label: Qloo Trends API
  slug: qloo-com-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qloo-com/openapi/qloo-com-trends-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: When you fill-in our online form to contact our sales team, we ask for your name, email address, and optional fields such as your company name
  - category: device
    text: Qloo’s server logs also automatically collect User information such as Users’ IP addresses, pages on the Site accessed by Users, browser type and language, and the date and time of visits
  - category: financial
    text: If a User utilizes our Services via a Qloo User Account, Qloo also collects billing information as needed to collect payment from the User.
  - category: behavioral
    text: Qloo also works with third-party service providers, such as Google Analytics, which collect information about which site the User came from and Users’ use of the Site and our Services.
  deletion:
    route: Request via contact email addresses
    text: 'Exercising the right to delete: You may request that we delete the personal information we have collected from you, subject to certain limitations under applicable law'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Machine learning on entity arrays
    text: Qloo will incorporate these anonymized vertices into our machine learning models in order to draw associations between A,B,C,D,E,F,G,H,I and further refine future Qloo Output.
  - purpose: Responding to contact inquiries
    text: If a User contacts Qloo via the Site’s contact page, Qloo collects contact information including name and email address so that we may respond to the User’s inquiry.
  - purpose: Site analytics and personalization
    text: Qloo’s Cookies may collect information to facilitate access to our Site and to personalize a User’s online experience.
  residency:
  - region: United States
    text: any information submitted on the Site will be processed in the United States for use by Qloo and its affiliates for any of the purposes described herein
  retention:
  - period: 18 months
    scope: Contact and billing information
    text: for up to 18 months after the User’s last contact with us
  - period: 26 months
    scope: Analytics information
    text: up to 26 months after User’s visit is logged for analytic purposes
  rights:
  - right: Know
    text: 'Exercising the right to know: You may request the following information about the personal information we have collected about you'
  - right: Delete
    text: 'Exercising the right to delete: You may request that we delete the personal information we have collected from you'
  - right: Object
    text: You also have rights to object to some processing and, where Qloo has asked for your consent to process your data, to withdraw this consent.
  - right: Access and portability
    text: You may ask Qloo for a copy of your information to correct it, erase it, and to transfer it to other organizations at your request.
  role:
    text: As a Data Processor Qloo Inc. is required to process data in strict accordance with the instructions provided by the Data Controller, the Company
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent the Personal Data of our Users, their Customers for any purpose.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: you authorize Qloo to transfer your personal information across national borders and to other countries where Qloo and its affiliates operate, including the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Qloo
provenance_date: '2026-11-10'
provider_name: Qloo
provider_slug: qloo-com
slug: qloo-com-privacy-policy
source_date: '2026-11-10'
source_filename: qloo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.qloo.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Qloo\naid: qloo-com\nurl: https://www.qloo.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a Data Processor Qloo Inc. is required to process data in strict accordance with the instructions provided\n    by the Data Controller, the Company\ndata_categories:\n- category: contact\n  text: When you fill-in our online form to contact our sales team, we ask for your name, email address, and optional\n    fields such as your company name\n- category: device\n  text: Qloo’s server logs also automatically collect User information such as Users’ IP addresses, pages on the\n    Site accessed\
  \ by Users, browser type and language, and the date and time of visits\n- category: financial\n  text: If a User utilizes our Services via a Qloo User Account, Qloo also collects billing information as needed\n    to collect payment from the User.\n- category: behavioral\n  text: Qloo also works with third-party service providers, such as Google Analytics, which collect information\n    about which site the User came from and Users’ use of the Site and our Services.\npurposes:\n- purpose: Machine learning on entity arrays\n  text: Qloo will incorporate these anonymized vertices into our machine learning models in order to draw associations\n    between A,B,C,D,E,F,G,H,I and further refine future Qloo Output.\n- purpose: Responding to contact inquiries\n  text: If a User contacts Qloo via the Site’s contact page, Qloo collects contact information including name and\n    email address so that we may respond to the User’s inquiry.\n- purpose: Site analytics and personalization\n  text: Qloo’s\
  \ Cookies may collect information to facilitate access to our Site and to personalize a User’s online\n    experience.\nretention:\n- scope: Contact and billing information\n  period: 18 months\n  text: for up to 18 months after the User’s last contact with us\n- scope: Analytics information\n  period: 26 months\n  text: up to 26 months after User’s visit is logged for analytic purposes\nresidency:\n- region: United States\n  text: any information submitted on the Site will be processed in the United States for use by Qloo and its affiliates\n    for any of the purposes described herein\ntransfers:\n- mechanism: other\n  text: you authorize Qloo to transfer your personal information across national borders and to other countries\n    where Qloo and its affiliates operate, including the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via contact email addresses\n  text: 'Exercising the right to delete:\
  \ You may request that we delete the personal information we have collected\n    from you, subject to certain limitations under applicable law'\nrights:\n- right: Know\n  text: 'Exercising the right to know: You may request the following information about the personal information\n    we have collected about you'\n- right: Delete\n  text: 'Exercising the right to delete: You may request that we delete the personal information we have collected\n    from you'\n- right: Object\n  text: You also have rights to object to some processing and, where Qloo has asked for your consent to process\n    your data, to withdraw this consent.\n- right: Access and portability\n  text: You may ask Qloo for a copy of your information to correct it, erase it, and to transfer it to other organizations\n    at your request.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent the Personal Data of our Users, their Customers for any purpose.\n"
source_yaml_url: https://artifacts.apis.io/qloo-com/privacy/qloo-com-privacy-policy.yml
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
summary_line: 18 quoted statements, read from Qloo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cultural-Intelligence
- Data Analytics
- Personalization
---
