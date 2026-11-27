---
api_specs:
- filename: ironscales-authorization-api-openapi.yml
  format: yaml
  label: IRONSCALES Authorization API
  slug: ironscales-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-authorization-api-openapi.yml
- filename: ironscales-campaigns-api-openapi.yml
  format: yaml
  label: IRONSCALES Campaigns API
  slug: ironscales-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-campaigns-api-openapi.yml
- filename: ironscales-deepfake-api-openapi.yml
  format: yaml
  label: IRONSCALES Deepfake API
  slug: ironscales-deepfake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-deepfake-api-openapi.yml
- filename: ironscales-emails-api-openapi.yml
  format: yaml
  label: IRONSCALES Emails API
  slug: ironscales-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-emails-api-openapi.yml
- filename: ironscales-incident-api-openapi.yml
  format: yaml
  label: IRONSCALES Incident API
  slug: ironscales-incident-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-incident-api-openapi.yml
- filename: ironscales-mailboxes-api-openapi.yml
  format: yaml
  label: IRONSCALES Mailboxes API
  slug: ironscales-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-mailboxes-api-openapi.yml
- filename: ironscales-mitigation-api-openapi.yml
  format: yaml
  label: IRONSCALES Mitigation API
  slug: ironscales-mitigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-mitigation-api-openapi.yml
- filename: ironscales-sat-api-openapi.yml
  format: yaml
  label: IRONSCALES SAT API
  slug: ironscales-sat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-sat-api-openapi.yml
- filename: ironscales-settings-api-openapi.yml
  format: yaml
  label: IRONSCALES Settings API
  slug: ironscales-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironscales/openapi/ironscales-settings-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact data, such as your first and last name, job title, department, phone number, location, language, email address, and billing address.
  - category: identifying
    text: Profile data, such as the username and password that you may have set to establish an online account with us
  - category: financial
    text: Financial data, such as your account details and billing address.
  - category: biometric
    text: Biometric information, such as facial characteristics extracted from photos uploaded or video conversations, and audio or voice patterns collected for the purpose of creating a template for live comparison and identity verification.
  - category: device
    text: 'Browser and Device Information: we collect your IP address and user agent string.'
  - category: behavioral
    text: 'Usage Data: we collect information about the Services’ performance and analytics such as the referral host that brought you to the Sites'
  - category: communication
    text: Communications data based on our exchanges with you, including when you contact us, communicate with us via chat features or otherwise.
  deletion:
    route: Email privacy@ironscales.com
    text: Your Personal Data will be stored until we delete our records in accordance with this Privacy Policy, or if you send a valid deletion request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and operation
    text: 'Service delivery and operation: we use your Personal Data to: Provide, operate or improve our business and the Services we provide'
  - purpose: Research and development
    text: we use your Personal Data for research and development purposes
  - purpose: Marketing and advertising
    text: 'Marketing and advertising: we, our service providers, and our third-party advertising partners collect and use your Personal Data for marketing and advertising purposes'
  - purpose: Compliance and protection
    text: Comply with applicable laws, lawful requests and legal processes such as to respond to subpoenas, investigations or requests from government authorities
  retention:
  - period: null
    scope: General retention
    text: We store the data we collect for as long as is necessary for the purpose(s) for which we originally collected it.
  rights:
  - right: Access
    text: Access. Provide you with information about our processing of your Personal Data and give you access to your Personal Data.
  - right: Correct
    text: Correct. Update or correct inaccuracies in your Personal Data.
  - right: Delete
    text: Delete. Delete your Personal Data where there is no good reason for us continuing to process it
  - right: Portability
    text: Portability. Port a machine-readable copy of your Personal Data to you or a third party of your choice.
  - right: Restrict
    text: Restrict. Restrict the processing of your Personal Data
  - right: Object
    text: Object. Object to our processing of your Personal Data where we are relying on Legitimate Interests
  - right: Withdraw consent
    text: Withdraw Consent. When we use your Personal Data based on your consent, you may have the right to withdraw that consent at any time.
  role:
    text: we act as a data controller or “business” for the Personal Data we process
    value: both
  sale_or_sharing:
    stance: conditional
    text: Right to Opt Out of the Sale of Personal Data. You may have the right to ask us to not sell your Personal Data at any time, referred to as the right to opt out.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: We adhere to the Data Privacy Framework and have certified to the Department of Commerce our commitment to comply with the Data Privacy Framework Principles.
  - mechanism: SCC
    text: or use safeguards like the Data Privacy Framework (as defined below) or the Standard Contractual Clauses (also known as the “SCCs” ) approved by the European Commission under Article 46.2 of the GDPR
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IRONSCALES
provenance_date: '2026-11-09'
provider_name: IRONSCALES
provider_slug: ironscales
slug: ironscales-privacy-policy
source_date: '2026-11-09'
source_filename: ironscales-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ironscales.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IRONSCALES\naid: ironscales\nurl: https://ironscales.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a data controller or “business” for the Personal Data we process\ndata_categories:\n- category: contact\n  text: Contact data, such as your first and last name, job title, department, phone number, location, language,\n    email address, and billing address.\n- category: identifying\n  text: Profile data, such as the username and password that you may have set to establish an online account with\n    us\n- category: financial\n  text: Financial data, such as your account\
  \ details and billing address.\n- category: biometric\n  text: Biometric information, such as facial characteristics extracted from photos uploaded or video conversations,\n    and audio or voice patterns collected for the purpose of creating a template for live comparison and identity\n    verification.\n- category: device\n  text: 'Browser and Device Information: we collect your IP address and user agent string.'\n- category: behavioral\n  text: 'Usage Data: we collect information about the Services’ performance and analytics such as the referral host\n    that brought you to the Sites'\n- category: communication\n  text: Communications data based on our exchanges with you, including when you contact us, communicate with us\n    via chat features or otherwise.\npurposes:\n- purpose: Service delivery and operation\n  text: 'Service delivery and operation: we use your Personal Data to: Provide, operate or improve our business\n    and the Services we provide'\n- purpose: Research and development\n\
  \  text: we use your Personal Data for research and development purposes\n- purpose: Marketing and advertising\n  text: 'Marketing and advertising: we, our service providers, and our third-party advertising partners collect\n    and use your Personal Data for marketing and advertising purposes'\n- purpose: Compliance and protection\n  text: Comply with applicable laws, lawful requests and legal processes such as to respond to subpoenas, investigations\n    or requests from government authorities\nretention:\n- scope: General retention\n  period: null\n  text: We store the data we collect for as long as is necessary for the purpose(s) for which we originally collected\n    it.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: We adhere to the Data Privacy Framework and have certified to the Department of Commerce our commitment\n    to comply with the Data Privacy Framework Principles.\n- mechanism: SCC\n  text: or use safeguards like the Data Privacy Framework (as defined below) or\
  \ the Standard Contractual Clauses\n    (also known as the “SCCs” ) approved by the European Commission under Article 46.2 of the GDPR\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@ironscales.com\n  text: Your Personal Data will be stored until we delete our records in accordance with this Privacy Policy, or\n    if you send a valid deletion request.\nrights:\n- right: Access\n  text: Access. Provide you with information about our processing of your Personal Data and give you access to your\n    Personal Data.\n- right: Correct\n  text: Correct. Update or correct inaccuracies in your Personal Data.\n- right: Delete\n  text: Delete. Delete your Personal Data where there is no good reason for us continuing to process it\n- right: Portability\n  text: Portability. Port a machine-readable copy of your Personal Data to you or a third party of your choice.\n- right: Restrict\n  text: Restrict. Restrict the processing\
  \ of your Personal Data\n- right: Object\n  text: Object. Object to our processing of your Personal Data where we are relying on Legitimate Interests\n- right: Withdraw consent\n  text: Withdraw Consent. When we use your Personal Data based on your consent, you may have the right to withdraw\n    that consent at any time.\nsale_or_sharing:\n  stance: conditional\n  text: Right to Opt Out of the Sale of Personal Data. You may have the right to ask us to not sell your Personal\n    Data at any time, referred to as the right to opt out.\n"
source_yaml_url: https://artifacts.apis.io/ironscales/privacy/ironscales-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from IRONSCALES's own page on 2026-11-09.
synthetic: false
tags:
- Email Security
- Cybersecurity
- Phishing
- Anti-Phishing
- Business Email Compromise
- Account Takeover
- Threat Intelligence
- Incident Response
- Security Awareness Training
- Phishing Simulation
- Microsoft 365
- Google Workspace
- SOC Automation
- Deepfake Detection
- MCP
---
