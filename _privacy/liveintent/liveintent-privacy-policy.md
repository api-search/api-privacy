---
api_specs:
- filename: liveintent-api-references-api-openapi.yml
  format: yaml
  label: LiveIntent API references API
  slug: liveintent-api-references-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-api-references-api-openapi.yml
- filename: liveintent-audiences-api-openapi.yml
  format: yaml
  label: LiveIntent Audiences API
  slug: liveintent-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-audiences-api-openapi.yml
- filename: liveintent-eventtrackers-api-openapi.yml
  format: yaml
  label: LiveIntent Eventtrackers API
  slug: liveintent-eventtrackers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-eventtrackers-api-openapi.yml
- filename: liveintent-legacy-api-openapi.yml
  format: yaml
  label: LiveIntent Legacy API
  slug: liveintent-legacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-legacy-api-openapi.yml
- filename: liveintent-search-api-openapi.yml
  format: yaml
  label: LiveIntent Search API
  slug: liveintent-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-search-api-openapi.yml
- filename: liveintent-trackers-api-openapi.yml
  format: yaml
  label: LiveIntent Trackers API
  slug: liveintent-trackers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-trackers-api-openapi.yml
- filename: liveintent-urltrackers-api-openapi.yml
  format: yaml
  label: LiveIntent Urltrackers API
  slug: liveintent-urltrackers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveintent/openapi/liveintent-urltrackers-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers, such as your name, email address, and phone number, as well as other demographic data like your age, gender, and language preference.
  - category: location
    text: Imprecise geolocation information, such as your ZIP code, city, state, or country.
  - category: behavioral
    text: Internet and Electronic Network Activity Information, such as whether an email sent by one of our business partners has been opened, or whether a link has been clicked in one of those emails.
  - category: professional
    text: Professional and employment-related information such as your employer and job title, if you provide it when applying for a job with us or in other direct communications to us.
  - category: financial
    text: Commercial Information, such as whether you purchased a product or service after viewing a related advertisement.
  - category: health
    text: data about health conditions
  - category: demographic
    text: Sensitive Data. Some privacy laws define certain categories of data as “Sensitive Data.”
  deletion:
    route: privacy center or email request for data deletion
    text: Data Deletion —you can ask us to delete your personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: personalized and interest-based advertising
    text: to deliver personalized messages that match your interests, including interest-based advertising to efficiently distribute email publications
  - purpose: website operation and communications
    text: LiveIntent uses the data we collect at this Site to fulfill your requests, respond to your inquiries, communicate with you, provide LiveIntent news or updates
  - purpose: analytics and campaign statistics
    text: We and our service providers also use the data we collect to generate and analyze statistics about the performance of our advertising campaigns
  - purpose: AI-based audience building
    text: Our AI analyzes signals from consumer interactions across email and digital channels to build interest-based audience profiles that enable targeted advertising.
  residency:
  - region: United States
    text: LiveIntent is headquartered in the United States, and the majority of our Services are performed in the United States and Canada
  retention:
  - period: null
    scope: personal information generally
    text: We keep data only for the period of time needed in order to achieve our stated purposes
  - period: 180 days
    scope: data that can identify a computer or device
    text: LiveIntent only keeps personal information in a form that can identify your computer or device for 180 days.
  - period: past six months
    scope: interest data
    text: rely only on the past six months’ data to inform our marketing choices
  rights:
  - right: correction
    text: Correction —you can ask us to correct personal information that we hold and is related to you if it is inaccurate.
  - right: deletion
    text: Data Deletion —you can ask us to delete your personal information.
  - right: objection or restriction
    text: Objection / Restricting Processing –in some US states and countries you have a legal right to object to processing of your personal information, or to ask that such processing be restricted.
  - right: opt-out of sensitive data use
    text: Opt-Out of our use of Sensitive Data –you can ask LiveIntent not to use Sensitive Data that relates to you.
  - right: opt-out of sale or sharing
    text: Opt-Out of Sales or Sharing of Data -you can request that we do not make your personal information available to our clients for their own use.
  role:
    text: When LiveIntent acts as a service provider, the client’s privacy policy governs its processing of personal information, not this policy.
    value: both
  sale_or_sharing:
    stance: allowed
    text: LiveIntent recognizes and processes Global Privacy Control (GPC) signals and other universal opt-out preference signals as valid requests to opt out of the sale and sharing of personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: When you provide data to LiveIntent, you consent to its processing in any of our other locations around the world.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LiveIntent
provenance_date: '2026-11-09'
provider_name: LiveIntent
provider_slug: liveintent
slug: liveintent-privacy-policy
source_date: '2026-11-09'
source_filename: liveintent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.liveintent.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LiveIntent\naid: liveintent\nurl: https://www.liveintent.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When LiveIntent acts as a service provider, the client’s privacy policy governs its processing of personal\n    information, not this policy.\ndata_categories:\n- category: identifying\n  text: Identifiers, such as your name, email address, and phone number, as well as other demographic data like\n    your age, gender, and language preference.\n- category: location\n  text: Imprecise geolocation information, such as your ZIP code, city, state, or country.\n- category: behavioral\n\
  \  text: Internet and Electronic Network Activity Information, such as whether an email sent by one of our business\n    partners has been opened, or whether a link has been clicked in one of those emails.\n- category: professional\n  text: Professional and employment-related information such as your employer and job title, if you provide it when\n    applying for a job with us or in other direct communications to us.\n- category: financial\n  text: Commercial Information, such as whether you purchased a product or service after viewing a related advertisement.\n- category: health\n  text: data about health conditions\n- category: demographic\n  text: Sensitive Data. Some privacy laws define certain categories of data as “Sensitive Data.”\npurposes:\n- purpose: personalized and interest-based advertising\n  text: to deliver personalized messages that match your interests, including interest-based advertising to efficiently\n    distribute email publications\n- purpose: website operation\
  \ and communications\n  text: LiveIntent uses the data we collect at this Site to fulfill your requests, respond to your inquiries, communicate\n    with you, provide LiveIntent news or updates\n- purpose: analytics and campaign statistics\n  text: We and our service providers also use the data we collect to generate and analyze statistics about the performance\n    of our advertising campaigns\n- purpose: AI-based audience building\n  text: Our AI analyzes signals from consumer interactions across email and digital channels to build interest-based\n    audience profiles that enable targeted advertising.\nretention:\n- scope: personal information generally\n  period: null\n  text: We keep data only for the period of time needed in order to achieve our stated purposes\n- scope: data that can identify a computer or device\n  period: 180 days\n  text: LiveIntent only keeps personal information in a form that can identify your computer or device for 180 days.\n- scope: interest data\n  period:\
  \ past six months\n  text: rely only on the past six months’ data to inform our marketing choices\nresidency:\n- region: United States\n  text: LiveIntent is headquartered in the United States, and the majority of our Services are performed in the\n    United States and Canada\ntransfers:\n- mechanism: other\n  text: When you provide data to LiveIntent, you consent to its processing in any of our other locations around\n    the world.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy center or email request for data deletion\n  text: Data Deletion —you can ask us to delete your personal information.\nrights:\n- right: correction\n  text: Correction —you can ask us to correct personal information that we hold and is related to you if it is inaccurate.\n- right: deletion\n  text: Data Deletion —you can ask us to delete your personal information.\n- right: objection or restriction\n  text: Objection / Restricting Processing\
  \ –in some US states and countries you have a legal right to object to\n    processing of your personal information, or to ask that such processing be restricted.\n- right: opt-out of sensitive data use\n  text: Opt-Out of our use of Sensitive Data –you can ask LiveIntent not to use Sensitive Data that relates to you.\n- right: opt-out of sale or sharing\n  text: Opt-Out of Sales or Sharing of Data -you can request that we do not make your personal information available\n    to our clients for their own use.\nsale_or_sharing:\n  stance: allowed\n  text: LiveIntent recognizes and processes Global Privacy Control (GPC) signals and other universal opt-out preference\n    signals as valid requests to opt out of the sale and sharing of personal information.\n"
source_yaml_url: https://artifacts.apis.io/liveintent/privacy/liveintent-privacy-policy.yml
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
summary_line: 24 quoted statements, read from LiveIntent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- Identity
- Email Marketing
- Audiences
- Publishers
- Marketers
- Data
---
