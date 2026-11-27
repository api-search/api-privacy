---
api_specs:
- filename: savee-boards-api-openapi.yml
  format: yaml
  label: Savee Boards API
  slug: savee-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-boards-api-openapi.yml
- filename: savee-saves-api-openapi.yml
  format: yaml
  label: Savee Saves API
  slug: savee-saves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-saves-api-openapi.yml
- filename: savee-search-api-openapi.yml
  format: yaml
  label: Savee Search API
  slug: savee-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-search-api-openapi.yml
- filename: savee-system-api-openapi.yml
  format: yaml
  label: Savee System API
  slug: savee-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-system-api-openapi.yml
- filename: savee-user-api-openapi.yml
  format: yaml
  label: Savee User API
  slug: savee-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/savee/openapi/savee-user-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: We get your name and email from that sign-in, and your profile picture if the provider shares it.
  - category: contact
    text: 'Email you at that address: service email, and product news if it is on in your settings'
  - category: device
    text: Device, IP address, and browser information we need to run the service, keep you logged in, and stop abuse.
  - category: financial
    text: We receive what we need to keep the subscription running (for example, that a charge succeeded), not your full card number.
  - category: professional
    text: Your employer or school and your role. We learn this from your email domain, your profile, and service providers that enrich data for us
  - category: behavioral
    text: Saves (the images and videos you collect), boards, comments, and how you use the product.
  deletion:
    route: Delete account in settings or email hey@savee.com
    text: When you delete your account (in settings, or by writing hey@savee.com ), we delete your profile, saves, boards, and comments.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: Run Savee — your account, saves, boards, comments, and Teams
  - purpose: Show related content
    text: 'Show related content: more like what you just saved, using tags, context, and visual cues.'
  - purpose: Security and spam prevention
    text: Keep the product working, secure, and free of spam
  - purpose: Process subscriptions
    text: Process a subscription if you have one
  - purpose: Understand members' work for Team plans
    text: Understand where members work and what they do, so we can offer Team plans to their companies and schools
  - purpose: Product news and offers
    text: Send product news, announcements, and offers about Savee, including Team plans.
  residency:
  - region: United States
    text: Savee is operated from the United States. If you use Savee from elsewhere, your information is processed in the U.S.
  retention:
  - period: null
    scope: Account and content data
    text: We keep account and content data while your account is open.
  - period: null
    scope: Logs
    text: Logs are kept only as long as we need them to run and protect the service.
  - period: null
    scope: Google user data
    text: We keep it while your account is open.
  rights:
  - right: access, correct, delete, export
    text: you may also ask to access, correct, delete, or export your data, or object to processing, by writing hey@savee.com .
  - right: object to processing
    text: object to processing
  - right: complain to data protection authority
    text: You can also complain to your local data protection authority.
  - right: withdraw consent
    text: You can withdraw it anytime
  role:
    text: Savee, Inc. (7162 Beverly Blvd, PMB 520, Los Angeles, CA 90036, USA) is the controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Savee
provenance_date: '2026-11-10'
provider_name: Savee
provider_slug: savee
slug: savee-privacy-policy
source_date: '2026-11-10'
source_filename: savee-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://savee.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Savee\naid: savee\nurl: https://savee.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Savee, Inc. (7162 Beverly Blvd, PMB 520, Los Angeles, CA 90036, USA) is the controller of your personal\n    data.\ndata_categories:\n- category: identifying\n  text: We get your name and email from that sign-in, and your profile picture if the provider shares it.\n- category: contact\n  text: 'Email you at that address: service email, and product news if it is on in your settings'\n- category: device\n  text: Device, IP address, and browser information we need to run the service, keep you logged\
  \ in, and stop abuse.\n- category: financial\n  text: We receive what we need to keep the subscription running (for example, that a charge succeeded), not your\n    full card number.\n- category: professional\n  text: Your employer or school and your role. We learn this from your email domain, your profile, and service providers\n    that enrich data for us\n- category: behavioral\n  text: Saves (the images and videos you collect), boards, comments, and how you use the product.\npurposes:\n- purpose: Run the service\n  text: Run Savee — your account, saves, boards, comments, and Teams\n- purpose: Show related content\n  text: 'Show related content: more like what you just saved, using tags, context, and visual cues.'\n- purpose: Security and spam prevention\n  text: Keep the product working, secure, and free of spam\n- purpose: Process subscriptions\n  text: Process a subscription if you have one\n- purpose: Understand members' work for Team plans\n  text: Understand where members work\
  \ and what they do, so we can offer Team plans to their companies and schools\n- purpose: Product news and offers\n  text: Send product news, announcements, and offers about Savee, including Team plans.\nretention:\n- scope: Account and content data\n  period: null\n  text: We keep account and content data while your account is open.\n- scope: Logs\n  period: null\n  text: Logs are kept only as long as we need them to run and protect the service.\n- scope: Google user data\n  period: null\n  text: We keep it while your account is open.\nresidency:\n- region: United States\n  text: Savee is operated from the United States. If you use Savee from elsewhere, your information is processed\n    in the U.S.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in settings or email hey@savee.com\n  text: When you delete your account (in settings, or by writing hey@savee.com ), we delete your profile, saves,\n\
  \    boards, and comments.\nrights:\n- right: access, correct, delete, export\n  text: you may also ask to access, correct, delete, or export your data, or object to processing, by writing hey@savee.com\n    .\n- right: object to processing\n  text: object to processing\n- right: complain to data protection authority\n  text: You can also complain to your local data protection authority.\n- right: withdraw consent\n  text: You can withdraw it anytime\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/savee/privacy/savee-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Savee's own page on 2026-11-10.
synthetic: false
tags:
- Design
- visual inspiration
- Image
- Creative
- Moodboards
- Artificial Intelligence
---
