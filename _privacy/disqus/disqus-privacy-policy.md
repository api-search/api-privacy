---
api_specs:
- filename: disqus-categories-api-openapi.yml
  format: yaml
  label: Disqus Categories API
  slug: disqus-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-categories-api-openapi.yml
- filename: disqus-forums-api-openapi.yml
  format: yaml
  label: Disqus Forums API
  slug: disqus-forums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-forums-api-openapi.yml
- filename: disqus-posts-api-openapi.yml
  format: yaml
  label: Disqus Posts API
  slug: disqus-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-posts-api-openapi.yml
- filename: disqus-threads-api-openapi.yml
  format: yaml
  label: Disqus Threads API
  slug: disqus-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-threads-api-openapi.yml
- filename: disqus-users-api-openapi.yml
  format: yaml
  label: Disqus Users API
  slug: disqus-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-users-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers (“Identity Data”) such as first name, last name, username or similar identifier, internet protocol (IP) address, unique Cookie ID, Device ID, date of birth, email address, telephone number, and mailing address
  - category: behavioral
    text: Internet or other electronic network activity information, such as browsing and comment history, feedback and survey responses
  - category: demographic
    text: Protected classification characteristics under California or federal law, such as race, gender, or age
  - category: professional
    text: Professional or employment-related information, to the extent that you include it in your profile or comments
  - category: other
    text: Sensitive Personal Information. We do not intentionally collect any personal data about your race or ethnicity
  deletion:
    route: Privacy request via Privacy Choices page or email privacy@disqus.com
    text: Request that we delete data we have collected about you
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Targeted advertising
    text: Disqus uses cookies and allows partners to also set cookies through the Service in order to facilitate cross-context behavioral advertising.
  - purpose: Marketing and email
    text: Disqus may also send you email newsletters and email marketing messages if you have provided us with permission, or consented to receive such emails
  - purpose: Service operation and analytics
    text: To use data analytics to improve our Service
  - purpose: AI content moderation
    text: AI is used to help moderate content on the platform — detecting spam and content that violates our community guidelines
  retention:
  - period: null
    scope: Personal data generally
    text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting requirements.
  rights:
  - right: Access
    text: Request a copy of personal data we have collected about you
  - right: Opt-out of sale or sharing
    text: Opt-out of our sale or sharing of personal data about you
  - right: Deletion
    text: Request that we delete data we have collected about you
  - right: Correction
    text: Request that we correct incorrect data
  - right: Limit sensitive personal data use
    text: Request that we limit our use of, or delete sensitive personal data that you may have previously provided in a comment
  role:
    text: Disqus is also a marketing and data company, and uses and shares personal data collected from third party sites where our Service is enabled for marketing purposes
    value: controller
  sale_or_sharing:
    stance: allowed
    text: In the past 12 months, we have sold and/or shared all of the categories of personal data listed above with Zeta Global and our Business Partners
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we protect it using specific contracts approved by the European Commission and/or the equivalent contractual provisions approved by the UK’s Information Commissioner’s Office
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Disqus
provenance_date: '2026-11-09'
provider_name: Disqus
provider_slug: disqus
slug: disqus-privacy-policy
source_date: '2026-11-09'
source_filename: disqus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://help.disqus.com/en/articles/1717103-disqus-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Disqus\naid: disqus\nurl: https://help.disqus.com/en/articles/1717103-disqus-privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Disqus is also a marketing and data company, and uses and shares personal data collected from third party\n    sites where our Service is enabled for marketing purposes\ndata_categories:\n- category: identifying\n  text: Identifiers (“Identity Data”) such as first name, last name, username or similar identifier, internet protocol\n    (IP) address, unique Cookie ID, Device ID, date of birth, email address, telephone number, and mailing address\n- category:\
  \ behavioral\n  text: Internet or other electronic network activity information, such as browsing and comment history, feedback\n    and survey responses\n- category: demographic\n  text: Protected classification characteristics under California or federal law, such as race, gender, or age\n- category: professional\n  text: Professional or employment-related information, to the extent that you include it in your profile or comments\n- category: other\n  text: Sensitive Personal Information. We do not intentionally collect any personal data about your race or ethnicity\npurposes:\n- purpose: Targeted advertising\n  text: Disqus uses cookies and allows partners to also set cookies through the Service in order to facilitate cross-context\n    behavioral advertising.\n- purpose: Marketing and email\n  text: Disqus may also send you email newsletters and email marketing messages if you have provided us with permission,\n    or consented to receive such emails\n- purpose: Service operation and\
  \ analytics\n  text: To use data analytics to improve our Service\n- purpose: AI content moderation\n  text: AI is used to help moderate content on the platform — detecting spam and content that violates our community\n    guidelines\nretention:\n- scope: Personal data generally\n  period: null\n  text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it\n    for, including for the purposes of satisfying any legal, accounting, or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we protect it using specific contracts approved by the European Commission and/or the equivalent contractual\n    provisions approved by the UK’s Information Commissioner’s Office\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy request via Privacy Choices page or email privacy@disqus.com\n  text: Request that we delete data we have collected about you\nrights:\n\
  - right: Access\n  text: Request a copy of personal data we have collected about you\n- right: Opt-out of sale or sharing\n  text: Opt-out of our sale or sharing of personal data about you\n- right: Deletion\n  text: Request that we delete data we have collected about you\n- right: Correction\n  text: Request that we correct incorrect data\n- right: Limit sensitive personal data use\n  text: Request that we limit our use of, or delete sensitive personal data that you may have previously provided\n    in a comment\nsale_or_sharing:\n  stance: allowed\n  text: In the past 12 months, we have sold and/or shared all of the categories of personal data listed above with\n    Zeta Global and our Business Partners\n"
source_yaml_url: https://artifacts.apis.io/disqus/privacy/disqus-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Disqus's own page on 2026-11-09.
synthetic: false
tags:
- Comments
- Community
- Discussions
- Publishing
- Audience Engagement
- Social
---
