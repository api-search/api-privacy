---
api_specs:
- filename: pushcut-automation-server-api-openapi.yml
  format: yaml
  label: Pushcut Automation Server API
  slug: pushcut-automation-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-automation-server-api-openapi.yml
- filename: pushcut-notifications-api-openapi.yml
  format: yaml
  label: Pushcut Notifications API
  slug: pushcut-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-notifications-api-openapi.yml
- filename: pushcut-subscriptions-api-openapi.yml
  format: yaml
  label: Pushcut Subscriptions API
  slug: pushcut-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pushcut/openapi/pushcut-subscriptions-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: an account is created using a unique identifier representing your device
  - category: identifying
    text: we store a similar anonymous identifier representing your iCloud account
  - category: contact
    text: We do not collect or store your name or email address.
  - category: location
    text: Your location is never stored or sent to servers in any way.
  - category: behavioral
    text: We collect anonymized, aggregate information about general app/service usage, such as how frequently individual features are used
  - category: device
    text: 'general analytics information like operating system version, device model and general geography information (ie: which country or territory)'
  - category: communication
    text: If you contact us for support or feedback via email we may keep a copy of this email
  deletion:
    route: Delete account in the Account section of the app
    text: You can delete your account in the Account section in the app directly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and provide service
    text: We collect the information as described in this policy to operate our service as described and provide support
  - purpose: detect problems
    text: detect potential problems with our service or app
  - purpose: usage analysis
    text: learn about usage and customer behavior to understand how to best improve Pushcut
  - purpose: security monitoring
    text: monitor and analyze security-relevant information to detect malicious activities
  residency:
  - region: United States of America
    text: Your data is transferred, stored, and processed on Google Cloud Plattform servers in several countries around the world, including the United States of America.
  retention:
  - period: 180 days
    scope: server logs in backup systems
    text: Certain server logs containing anonymous account identifiers will be deleted from backup systems within 180 days.
  rights:
  - right: revoke consent
    text: the GDPR explicitly defines certain rights you have, including the right to revoke your consent view and obtain a copy of your data delete your data
  - right: access and copy
    text: view and obtain a copy of your data
  - right: deletion
    text: delete your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We rely on the following third-party services to operate Pushcut Firebase (Authentication, Cloud Functions/Messaging/Firestore/Storage, Google Analytics for Firebase, Hosting)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pushcut
provenance_date: '2026-11-10'
provider_name: Pushcut
provider_slug: pushcut
slug: pushcut-privacy-policy
source_date: '2026-11-10'
source_filename: pushcut-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.pushcut.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pushcut\naid: pushcut\nurl: https://www.pushcut.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: an account is created using a unique identifier representing your device\n- category: identifying\n  text: we store a similar anonymous identifier representing your iCloud account\n- category: contact\n  text: We do not collect or store your name or email address.\n- category: location\n  text: Your location is never stored or sent to servers in any way.\n- category: behavioral\n  text: We collect anonymized, aggregate information\
  \ about general app/service usage, such as how frequently individual\n    features are used\n- category: device\n  text: 'general analytics information like operating system version, device model and general geography information\n    (ie: which country or territory)'\n- category: communication\n  text: If you contact us for support or feedback via email we may keep a copy of this email\npurposes:\n- purpose: operate and provide service\n  text: We collect the information as described in this policy to operate our service as described and provide support\n- purpose: detect problems\n  text: detect potential problems with our service or app\n- purpose: usage analysis\n  text: learn about usage and customer behavior to understand how to best improve Pushcut\n- purpose: security monitoring\n  text: monitor and analyze security-relevant information to detect malicious activities\nretention:\n- scope: server logs in backup systems\n  period: 180 days\n  text: Certain server logs containing\
  \ anonymous account identifiers will be deleted from backup systems within\n    180 days.\nresidency:\n- region: United States of America\n  text: Your data is transferred, stored, and processed on Google Cloud Plattform servers in several countries around\n    the world, including the United States of America.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We rely on the following third-party services to operate Pushcut Firebase (Authentication, Cloud Functions/Messaging/Firestore/Storage,\n    Google Analytics for Firebase, Hosting)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the Account section of the app\n  text: You can delete your account in the Account section in the app directly.\nrights:\n- right: revoke consent\n  text: the GDPR explicitly defines certain rights you have, including the right to revoke your consent view and\n    obtain a copy of your data delete your data\n- right: access and copy\n  text: view and obtain a\
  \ copy of your data\n- right: deletion\n  text: delete your data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pushcut/privacy/pushcut-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from Pushcut's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- iOS
- Shortcuts
- Webhook
- Integration
---
