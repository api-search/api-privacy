---
api_specs:
- filename: ivalt-openapi-generated.yml
  format: yaml
  label: iVALT API
  slug: ivalt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ivalt/openapi/_ae-authored/ivalt-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Full name Business email address Company name and size Job title and department Phone number (when provided)
  - category: device
    text: Device type, browser, and operating system
  - category: location
    text: Approximate geographic location (country/region level)
  - category: behavioral
    text: Pages viewed, time on site, and navigation paths
  - category: biometric
    text: Facial biometric data is captured and encoded on the user's device
  deletion:
    route: Email info@ivalt.com with the subject line "Data Deletion Request"
    text: You may request deletion of your personal data at any time by emailing info@ivalt.com with the subject line "Data Deletion Request." We will process your request within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to requests
    text: We use contact and form data to respond to assessment requests, answer inquiries, and fulfill any resource or report you have specifically requested.
  - purpose: Deliver requested resources
    text: When you register for a webinar, request an executive report, or download content, we use your information to fulfill that request and send confirmation communications.
  - purpose: Improve the website
    text: Analytics data helps us understand which content is most valuable, where visitors encounter friction, and how to improve overall experience.
  - purpose: Marketing with consent
    text: Where you have opted in, we may send email communications about iVALT product updates, industry insights, or events relevant to enterprise AI security.
  retention:
  - period: 24 months
    scope: Form submission data
    text: iVALT retains form submission data (including contact requests, assessment registrations, and webinar sign-ups) for 24 months from the date of submission, unless a deletion is requested earlier.
  - period: null
    scope: Raw facial imagery
    text: Raw facial imagery is not retained after the encoding process
  rights:
  - right: Access
    text: You may request a copy of the personal information iVALT holds about you by contacting info@ivalt.com.
  - right: Deletion
    text: You may request deletion of your personal data at any time by emailing info@ivalt.com with the subject line "Data Deletion Request."
  - right: Opt out of analytics
    text: You may opt out of Google Analytics data collection by installing the Google Analytics Opt-out Browser Add-on, or by adjusting your browser's cookie settings.
  - right: Opt out of marketing
    text: Every marketing email we send includes an unsubscribe link.
  - right: Data portability
    text: Where technically feasible, you may request a copy of your personal data in a structured, machine-readable format.
  role:
    text: iVALT, Inc. (“iVALT,” “we,” “us,” or “our”) is committed to protecting your personal information
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: iVALT does not sell, rent, or trade personal information to third parties for their own marketing or commercial purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iVALT
provenance_date: '2026-11-09'
provider_name: iVALT
provider_slug: ivalt
slug: ivalt-privacy-policy
source_date: '2026-11-09'
source_filename: ivalt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ivalt.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iVALT\naid: ivalt\nurl: https://www.ivalt.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: iVALT, Inc. (“iVALT,” “we,” “us,” or “our”) is committed to protecting your personal information\ndata_categories:\n- category: contact\n  text: Full name Business email address Company name and size Job title and department Phone number (when provided)\n- category: device\n  text: Device type, browser, and operating system\n- category: location\n  text: Approximate geographic location (country/region level)\n- category: behavioral\n  text: Pages viewed, time on site, and navigation paths\n\
  - category: biometric\n  text: Facial biometric data is captured and encoded on the user's device\npurposes:\n- purpose: Respond to requests\n  text: We use contact and form data to respond to assessment requests, answer inquiries, and fulfill any resource\n    or report you have specifically requested.\n- purpose: Deliver requested resources\n  text: When you register for a webinar, request an executive report, or download content, we use your information\n    to fulfill that request and send confirmation communications.\n- purpose: Improve the website\n  text: Analytics data helps us understand which content is most valuable, where visitors encounter friction, and\n    how to improve overall experience.\n- purpose: Marketing with consent\n  text: Where you have opted in, we may send email communications about iVALT product updates, industry insights,\n    or events relevant to enterprise AI security.\nretention:\n- scope: Form submission data\n  period: 24 months\n  text: iVALT retains\
  \ form submission data (including contact requests, assessment registrations, and webinar sign-ups)\n    for 24 months from the date of submission, unless a deletion is requested earlier.\n- scope: Raw facial imagery\n  period: null\n  text: Raw facial imagery is not retained after the encoding process\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email info@ivalt.com with the subject line \"Data Deletion Request\"\n  text: You may request deletion of your personal data at any time by emailing info@ivalt.com with the subject line\n    \"Data Deletion Request.\" We will process your request within 30 days.\nrights:\n- right: Access\n  text: You may request a copy of the personal information iVALT holds about you by contacting info@ivalt.com.\n- right: Deletion\n  text: You may request deletion of your personal data at any time by emailing info@ivalt.com with the subject line\n    \"Data Deletion\
  \ Request.\"\n- right: Opt out of analytics\n  text: You may opt out of Google Analytics data collection by installing the Google Analytics Opt-out Browser Add-on,\n    or by adjusting your browser's cookie settings.\n- right: Opt out of marketing\n  text: Every marketing email we send includes an unsubscribe link.\n- right: Data portability\n  text: Where technically feasible, you may request a copy of your personal data in a structured, machine-readable\n    format.\nsale_or_sharing:\n  stance: prohibited\n  text: iVALT does not sell, rent, or trade personal information to third parties for their own marketing or commercial\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/ivalt/privacy/ivalt-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from iVALT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Identity
- Security
- HumanAuthority
---
