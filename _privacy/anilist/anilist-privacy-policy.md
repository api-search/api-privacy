---
api_specs:
- filename: anilist-oauth2-api-openapi.yml
  format: yaml
  label: AniList O Auth2 API
  slug: anilist-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-oauth2-api-openapi.yml
- filename: anilist-graph-ql-api-openapi.yml
  format: yaml
  label: AniList Graph QL API
  slug: anilist-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-graph-ql-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: location
    text: geographic position
  - category: device
    text: browser fingerprint; browser information; IP address
  - category: behavioral
    text: Usage Data; Cookies
  deletion:
    route: Account deletion or direct data deletion request
    text: In the event of direct data or account deletion, all associated personal data will be removed or anonymized within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Advertising
    text: Advertising Google Ads conversion tracking and Venatus
  - purpose: Registration and authentication
    text: Direct registration
  - purpose: Spam and bots protection
    text: Cloudflare Turnstile
  - purpose: Handling payments
    text: PayPal
  - purpose: Managing contacts and sending messages
    text: Mailgun
  residency:
  - region: Place of processing
    text: The Data is processed at the Owner's operating offices and in any other places where the parties involved in the processing are located.
  retention:
  - period: 30 days
    scope: Account and personal data
    text: In the event of direct data or account deletion, all associated personal data will be removed or anonymized within 30 days.
  - period: null
    scope: General personal data
    text: Data may be stored indefinitely until the request of direct data or account deletion.
  rights:
  - right: Access
    text: Access their Data. Users have the right to learn if Data is being processed by the Owner
  - right: Erasure
    text: Have their Personal Data deleted or otherwise removed.
  - right: Rectification
    text: Verify and seek rectification.
  - right: Object
    text: Object to processing of their Data.
  - right: Portability
    text: Receive their Data and have it transferred to another controller.
  - right: Withdraw consent
    text: Withdraw their consent at any time.
  - right: Opt out of sale or sharing
    text: the right to opt out from the Sale of your Personal Information
  - right: Complaint
    text: Lodge a complaint.
  role:
    text: 'Owner and Data Controller AniList LLC 1207 Delaware Ave #3769, Wilmington, DE 19806'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The updated list of these parties may be requested from the Owner at any time.
    url: null
  transfers:
  - mechanism: SCC
    text: Data transfer abroad based on standard contractual clauses
  - mechanism: adequacy
    text: Data transfer to countries that guarantee European standards
  - mechanism: DPF
    text: Data transfer from the EU and/or Switzerland to the U.S based on Privacy Shield
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AniList
provenance_date: '2026-11-09'
provider_name: AniList
provider_slug: anilist
slug: anilist-privacy-policy
source_date: '2026-11-09'
source_filename: anilist-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anilist.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AniList\naid: anilist\nurl: https://anilist.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Owner and Data Controller AniList LLC 1207 Delaware Ave #3769, Wilmington, DE 19806'\ndata_categories:\n- category: location\n  text: geographic position\n- category: device\n  text: browser fingerprint; browser information; IP address\n- category: behavioral\n  text: Usage Data; Cookies\npurposes:\n- purpose: Advertising\n  text: Advertising Google Ads conversion tracking and Venatus\n- purpose: Registration and authentication\n  text: Direct registration\n- purpose: Spam and bots protection\n\
  \  text: Cloudflare Turnstile\n- purpose: Handling payments\n  text: PayPal\n- purpose: Managing contacts and sending messages\n  text: Mailgun\nretention:\n- scope: Account and personal data\n  period: 30 days\n  text: In the event of direct data or account deletion, all associated personal data will be removed or anonymized\n    within 30 days.\n- scope: General personal data\n  period: null\n  text: Data may be stored indefinitely until the request of direct data or account deletion.\nresidency:\n- region: Place of processing\n  text: The Data is processed at the Owner's operating offices and in any other places where the parties involved\n    in the processing are located.\ntransfers:\n- mechanism: SCC\n  text: Data transfer abroad based on standard contractual clauses\n- mechanism: adequacy\n  text: Data transfer to countries that guarantee European standards\n- mechanism: DPF\n  text: Data transfer from the EU and/or Switzerland to the U.S based on Privacy Shield\nsubprocessors:\n\
  \  url: null\n  text: The updated list of these parties may be requested from the Owner at any time.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or direct data deletion request\n  text: In the event of direct data or account deletion, all associated personal data will be removed or anonymized\n    within 30 days.\nrights:\n- right: Access\n  text: Access their Data. Users have the right to learn if Data is being processed by the Owner\n- right: Erasure\n  text: Have their Personal Data deleted or otherwise removed.\n- right: Rectification\n  text: Verify and seek rectification.\n- right: Object\n  text: Object to processing of their Data.\n- right: Portability\n  text: Receive their Data and have it transferred to another controller.\n- right: Withdraw consent\n  text: Withdraw their consent at any time.\n- right: Opt out of sale or sharing\n  text: the right to opt out from the Sale of your Personal Information\n- right: Complaint\n  text:\
  \ Lodge a complaint.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anilist/privacy/anilist-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 25 quoted statements, read from AniList's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Manga
- Entertainment
- Media
- Social
- Database
- GraphQL
- OAuth
- Public APIs
- Authentication
---
