---
api_specs:
- filename: doximity-openid-connect-api-openapi.yml
  format: yaml
  label: Doximity OpenID Connect API
  slug: doximity-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-openid-connect-api-openapi.yml
- filename: doximity-oauth-api-openapi.yml
  format: yaml
  label: Doximity O Auth API
  slug: doximity-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doximity/openapi/doximity-oauth-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: All Doximity members must provide their email address
  - category: identifying
    text: we require registering members to verify their identity and credentials, which may involve answering identity verification questions and/or sharing a copy of their professional license, medical ID or other relevant documentation
  - category: device
    text: your IP address (which is a unique numerical address that identifies your device when you access the Internet), your browser and device type and model, operating system
  - category: communication
    text: We collect information about usage of these tools, such as when a member uses Dialer and the duration of a call.
  - category: behavioral
    text: whether you view, click or otherwise interact with content, including articles, links, advertisements
  - category: professional
    text: healthcare professionals are required to provide certain information about their education, such as school attended, year of graduation, and specialty
  deletion:
    route: Contact support@doximity.com
    text: if you wish to close your account, please contact us at support@doximity.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve Services
    text: We use your information to provide, operate, support, promote, and improve the Services, including through the development of new tools and features.
  - purpose: Targeted advertising
    text: We use your information to target (and measure the performance of) advertising and other content sponsored by third parties
  - purpose: Fraud and legal compliance
    text: We also use your information to detect, investigate, and prevent fraudulent, harmful, unauthorized, unethical or illegal activities
  residency:
  - region: United States
    text: By using the Services, you consent to your personal information being stored and otherwise processed in the United States as described in this policy.
  retention:
  - period: null
    scope: Personal information
    text: We will retain your personal information for at least the period reasonably necessary to fulfill the purposes outlined in this privacy policy, unless a longer retention period is required or permitted by law.
  rights:
  - right: Review and update account information
    text: If you have registered a Doximity account, you may review and update certain personal information through your account settings.
  - right: Opt out of marketing emails
    text: You may opt-out of receiving marketing emails from Doximity at any time
  - right: Request removal of public profile
    text: if you do not have a Doximity account but would like us to modify or remove your public profile
  role:
    text: This privacy policy describes how Doximity, Inc. (“Doximity,” “we,” “us,” or “our”) collects, uses, shares, and otherwise handles personal information
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell Patient Information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Doximity
provenance_date: '2026-11-09'
provider_name: Doximity
provider_slug: doximity
slug: doximity-privacy-policy
source_date: '2026-11-09'
source_filename: doximity-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.doximity.com/clinicians/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Doximity\naid: doximity\nurl: https://www.doximity.com/clinicians/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This privacy policy describes how Doximity, Inc. (“Doximity,” “we,” “us,” or “our”) collects, uses, shares,\n    and otherwise handles personal information\ndata_categories:\n- category: contact\n  text: All Doximity members must provide their email address\n- category: identifying\n  text: we require registering members to verify their identity and credentials, which may involve answering identity\n    verification questions and/or sharing a copy of their professional license,\
  \ medical ID or other relevant documentation\n- category: device\n  text: your IP address (which is a unique numerical address that identifies your device when you access the Internet),\n    your browser and device type and model, operating system\n- category: communication\n  text: We collect information about usage of these tools, such as when a member uses Dialer and the duration of\n    a call.\n- category: behavioral\n  text: whether you view, click or otherwise interact with content, including articles, links, advertisements\n- category: professional\n  text: healthcare professionals are required to provide certain information about their education, such as school\n    attended, year of graduation, and specialty\npurposes:\n- purpose: Provide and improve Services\n  text: We use your information to provide, operate, support, promote, and improve the Services, including through\n    the development of new tools and features.\n- purpose: Targeted advertising\n  text: We use your information\
  \ to target (and measure the performance of) advertising and other content sponsored\n    by third parties\n- purpose: Fraud and legal compliance\n  text: We also use your information to detect, investigate, and prevent fraudulent, harmful, unauthorized, unethical\n    or illegal activities\nretention:\n- scope: Personal information\n  period: null\n  text: We will retain your personal information for at least the period reasonably necessary to fulfill the purposes\n    outlined in this privacy policy, unless a longer retention period is required or permitted by law.\nresidency:\n- region: United States\n  text: By using the Services, you consent to your personal information being stored and otherwise processed in\n    the United States as described in this policy.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support@doximity.com\n  text: if you wish to close your account, please contact us at\
  \ support@doximity.com\nrights:\n- right: Review and update account information\n  text: If you have registered a Doximity account, you may review and update certain personal information through\n    your account settings.\n- right: Opt out of marketing emails\n  text: You may opt-out of receiving marketing emails from Doximity at any time\n- right: Request removal of public profile\n  text: if you do not have a Doximity account but would like us to modify or remove your public profile\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell Patient Information.\n"
source_yaml_url: https://artifacts.apis.io/doximity/privacy/doximity-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Doximity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Identity
- OAuth
- OpenID Connect
- Authentication
- Physician Network
- Healthcare
- SSO
- Verification
---
