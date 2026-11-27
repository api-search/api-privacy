---
api_specs:
- filename: mspsoftware-net-categories-api-openapi.yml
  format: yaml
  label: MSP Software Categories API
  slug: mspsoftware-net-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-categories-api-openapi.yml
- filename: mspsoftware-net-compare-api-openapi.yml
  format: yaml
  label: MSP Software Compare API
  slug: mspsoftware-net-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-compare-api-openapi.yml
- filename: mspsoftware-net-msp-software-api-api-openapi.yml
  format: yaml
  label: MSP Software MSP Software API
  slug: mspsoftware-net-msp-software-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-msp-software-api-api-openapi.yml
- filename: mspsoftware-net-posts-api-openapi.yml
  format: yaml
  label: MSP Software Posts API
  slug: mspsoftware-net-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-posts-api-openapi.yml
- filename: mspsoftware-net-recent-api-openapi.yml
  format: yaml
  label: MSP Software Recent API
  slug: mspsoftware-net-recent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-recent-api-openapi.yml
- filename: mspsoftware-net-software-api-openapi.yml
  format: yaml
  label: MSP Software Software API
  slug: mspsoftware-net-software-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-software-api-openapi.yml
- filename: mspsoftware-net-vendors-api-openapi.yml
  format: yaml
  label: MSP Software Vendors API
  slug: mspsoftware-net-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mspsoftware-net/openapi/mspsoftware-net-vendors-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address and the display name, role and company size band you give us
  - category: location
    text: an account's country
  - category: behavioral
    text: the content of any review, price report, claim or flag you submit
  - category: device
    text: a hashed IP address and a browser identifier
  - category: identifying
    text: sign-in sessions, each with a hashed identifier, the time it was created and last used
  deletion:
    route: Export and deletion available from account once signed in
    text: Export and deletion are available from your account once you are signed in.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running accounts and publishing submissions
    text: 'Running your account, publishing a review or price report you chose to submit, and running a sponsorship you bought: contract.'
  - purpose: Moderation and security
    text: 'Moderating content, preventing fraud and abuse, rate-limiting sign-in and submissions, and keeping security and audit logs: legitimate interest.'
  - purpose: Analytics
    text: 'Listing pages record daily counts: views, outbound clicks, the country a view came from and the site or search that sent it'
  retention:
  - period: 48 hours
    scope: Magic sign-in link
    text: A magic sign-in link is kept for 48 hours, whether or not it is used, then removed.
  - period: 90 days
    scope: Stripe billing events
    text: Records of Stripe billing events are kept for 90 days.
  - period: 90 days
    scope: Analytics rows keyed by visitor identifier
    text: rows keyed by it are deleted after 90 days
  - period: 180 days
    scope: Review IP and device hashes
    text: the three hashes are deleted 180 days after the review is submitted
  - period: as long as the account exists
    scope: Account data
    text: Everything else tied to your account is kept for as long as the account exists
  rights:
  - right: Access
    text: You can ask to see the data we hold about you
  - right: Rectification
    text: correct it
  - right: Erasure
    text: have it erased
  - right: Restriction or objection
    text: restrict or object to processing
  - right: Portability
    text: receive it in a portable format
  - right: Complain to regulator
    text: you can complain to the Information Commissioner's Office at ico.org.uk
  role:
    text: The data controller is MSP Software.
    value: controller
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
name: MSP Software
provenance_date: '2026-11-10'
provider_name: MSP Software
provider_slug: mspsoftware-net
slug: mspsoftware-net-privacy-policy
source_date: '2026-11-10'
source_filename: mspsoftware-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mspsoftware.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MSP Software\naid: mspsoftware-net\nurl: https://mspsoftware.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is MSP Software.\ndata_categories:\n- category: contact\n  text: Your email address and the display name, role and company size band you give us\n- category: location\n  text: an account's country\n- category: behavioral\n  text: the content of any review, price report, claim or flag you submit\n- category: device\n  text: a hashed IP address and a browser identifier\n- category: identifying\n  text: sign-in sessions, each with a hashed identifier, the\
  \ time it was created and last used\npurposes:\n- purpose: Running accounts and publishing submissions\n  text: 'Running your account, publishing a review or price report you chose to submit, and running a sponsorship\n    you bought: contract.'\n- purpose: Moderation and security\n  text: 'Moderating content, preventing fraud and abuse, rate-limiting sign-in and submissions, and keeping security\n    and audit logs: legitimate interest.'\n- purpose: Analytics\n  text: 'Listing pages record daily counts: views, outbound clicks, the country a view came from and the site or\n    search that sent it'\nretention:\n- scope: Magic sign-in link\n  period: 48 hours\n  text: A magic sign-in link is kept for 48 hours, whether or not it is used, then removed.\n- scope: Stripe billing events\n  period: 90 days\n  text: Records of Stripe billing events are kept for 90 days.\n- scope: Analytics rows keyed by visitor identifier\n  period: 90 days\n  text: rows keyed by it are deleted after 90 days\n\
  - scope: Review IP and device hashes\n  period: 180 days\n  text: the three hashes are deleted 180 days after the review is submitted\n- scope: Account data\n  period: as long as the account exists\n  text: Everything else tied to your account is kept for as long as the account exists\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Export and deletion available from account once signed in\n  text: Export and deletion are available from your account once you are signed in.\nrights:\n- right: Access\n  text: You can ask to see the data we hold about you\n- right: Rectification\n  text: correct it\n- right: Erasure\n  text: have it erased\n- right: Restriction or objection\n  text: restrict or object to processing\n- right: Portability\n  text: receive it in a portable format\n- right: Complain to regulator\n  text: you can complain to the Information Commissioner's Office at ico.org.uk\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mspsoftware-net/privacy/mspsoftware-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 21 quoted statements, read from MSP Software's own page on 2026-11-10.
synthetic: false
tags:
- Directory
- MSP
- Software
- Comparison
- Reviews
- OpenAPI
---
