---
api_specs:
- filename: collager-ai-account-api-openapi.yml
  format: yaml
  label: Collager.ai Account API
  slug: collager-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collager-ai/openapi/collager-ai-account-api-openapi.yml
- filename: collager-ai-collages-api-openapi.yml
  format: yaml
  label: Collager.ai Collages API
  slug: collager-ai-collages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collager-ai/openapi/collager-ai-collages-api-openapi.yml
- filename: collager-ai-mosaics-api-openapi.yml
  format: yaml
  label: Collager.ai Mosaics API
  slug: collager-ai-mosaics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collager-ai/openapi/collager-ai-mosaics-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address - Date and time of the visit - Request context - User ID (if applicable)
  - category: device
    text: Identification data of the browser and operating system used
  - category: behavioral
    text: URL accessed
  - category: other
    text: When users upload files to create their collages, these files are securely stored in the AWS (Amazon Web Services) cloud.
  deletion:
    route: Account project deletion in the account main page (trash icon) or email account@collager.ai for login data
    text: go to the main page of your account and click on the delete icon in the form of a trash can on the right.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Collage creation
    text: only used to perform requested image processing
  - purpose: Security and service improvement
    text: The collection of this data is based on our legitimate interest in ensuring system security, providing technical support, and improving the quality of our service.
  - purpose: Aggregate website statistics
    text: to understand, in aggregate, how the Website is used (Google Analytics, described below)
  - purpose: Promotional emails
    text: your consent (promotional emails, which you can withdraw at any time with the “unsubscribe” link)
  residency:
  - region: European Union and United States
    text: Your data is stored with Amazon Web Services and may be processed in the European Union and in the United States.
  - region: EU (Frankfurt)
    text: are stored in Amazon S3 in the EU (Frankfurt)
  retention:
  - period: null
    scope: Uploaded images
    text: Any uploaded images, processed or non-processed will be deleted automatically.
  - period: 30 days
    scope: Uncompleted collages
    text: Collages that have been created but not unlocked for download are deleted automatically, normally after 30 days and in any case within 45 days
  - period: 12 hours
    scope: Deleted collage projects
    text: Once a collage or project is deleted, all associated photos are removed within 12 hours.
  - period: 30 days
    scope: AI assistant photos
    text: are deleted automatically within 30 days
  rights:
  - right: Access
    text: You have the right to access your personal data, to have it corrected or deleted, to restrict or object to its processing, to receive it in a portable format, and to withdraw your consent at any time.
  - right: Complaint to supervisory authority
    text: You also have the right to lodge a complaint with the data protection supervisory authority of your country.
  role:
    text: The controller of your personal data is Eugene Baryshnikov, the owner of collager.ai; you can reach him at privacy@collager.ai.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: A share or publish of information to any third parties are prohibited.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Collager.ai
provenance_date: '2026-11-09'
provider_name: Collager.ai
provider_slug: collager-ai
slug: collager-ai-privacy-policy
source_date: '2026-11-09'
source_filename: collager-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://collager.ai/privacy-policy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Collager.ai\naid: collager-ai\nurl: https://collager.ai/privacy-policy.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is Eugene Baryshnikov, the owner of collager.ai; you can reach him\n    at privacy@collager.ai.\ndata_categories:\n- category: identifying\n  text: IP address - Date and time of the visit - Request context - User ID (if applicable)\n- category: device\n  text: Identification data of the browser and operating system used\n- category: behavioral\n  text: URL accessed\n- category: other\n  text: When users upload files to create their collages,\
  \ these files are securely stored in the AWS (Amazon Web\n    Services) cloud.\npurposes:\n- purpose: Collage creation\n  text: only used to perform requested image processing\n- purpose: Security and service improvement\n  text: The collection of this data is based on our legitimate interest in ensuring system security, providing technical\n    support, and improving the quality of our service.\n- purpose: Aggregate website statistics\n  text: to understand, in aggregate, how the Website is used (Google Analytics, described below)\n- purpose: Promotional emails\n  text: your consent (promotional emails, which you can withdraw at any time with the “unsubscribe” link)\nretention:\n- scope: Uploaded images\n  period: null\n  text: Any uploaded images, processed or non-processed will be deleted automatically.\n- scope: Uncompleted collages\n  period: 30 days\n  text: Collages that have been created but not unlocked for download are deleted automatically, normally after\n    30 days and in\
  \ any case within 45 days\n- scope: Deleted collage projects\n  period: 12 hours\n  text: Once a collage or project is deleted, all associated photos are removed within 12 hours.\n- scope: AI assistant photos\n  period: 30 days\n  text: are deleted automatically within 30 days\nresidency:\n- region: European Union and United States\n  text: Your data is stored with Amazon Web Services and may be processed in the European Union and in the United\n    States.\n- region: EU (Frankfurt)\n  text: are stored in Amazon S3 in the EU (Frankfurt)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account project deletion in the account main page (trash icon) or email account@collager.ai for login data\n  text: go to the main page of your account and click on the delete icon in the form of a trash can on the right.\nrights:\n- right: Access\n  text: You have the right to access your personal data, to have it corrected\
  \ or deleted, to restrict or object\n    to its processing, to receive it in a portable format, and to withdraw your consent at any time.\n- right: Complaint to supervisory authority\n  text: You also have the right to lodge a complaint with the data protection supervisory authority of your country.\nsale_or_sharing:\n  stance: prohibited\n  text: A share or publish of information to any third parties are prohibited.\n"
source_yaml_url: https://artifacts.apis.io/collager-ai/privacy/collager-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Collager.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Photo Mosaic
- Photo Collage
- Image Generation
- Artificial Intelligence
- MCP
- Photography
---
