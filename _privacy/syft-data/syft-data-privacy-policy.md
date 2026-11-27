---
api_specs:
- filename: syft-data-export-api-openapi.yml
  format: yaml
  label: Syft Data Export API
  slug: syft-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-export-api-openapi.yml
- filename: syft-data-lookup-api-openapi.yml
  format: yaml
  label: Syft Data Lookup API
  slug: syft-data-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-lookup-api-openapi.yml
- filename: syft-data-events-api-openapi.yml
  format: yaml
  label: Syft Data Event Collection API
  slug: syft-data-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syft-data/openapi/syft-data-events-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: email addresses usernames passwords names
  - category: device
    text: device and usage information, such as your IP address, browser and device characteristics, operating system, language preferences, referring URLs, device name, country, location, information about how and when you use our Services
  - category: behavioral
    text: Browsing history, search history, online behavior, interest data, and interactions with our and other websites, applications, systems, and advertisements
  - category: identifying
    source: https://www.syftdata.com/dpa
    text: 'Identifiers and contact data: name, business email, personal email (where provided by Customer), LinkedIn profile URL, other social handles.'
  - category: professional
    source: https://www.syftdata.com/dpa
    text: 'Professional and employment data: job title, seniority, function, employer / company name, company domain, employment history.'
  - category: device
    source: https://www.syftdata.com/dpa
    text: 'Online identifiers and device data collected via Provider''s tracking technologies on Customer''s properties: IP address, approximate geolocation derived from IP, user-agent, cookie and session identifiers, page and event activity.'
  - category: behavioral
    source: https://www.syftdata.com/dpa
    text: 'Third-party intent signals: topic engagement signals, content engagement signals, event attendance signals, and similar behavioral indicators derived from third-party data partners, public sources, and intent-signal networks.'
  - category: financial
    source: https://www.syftdata.com/dpa
    text: Payment card data is handled directly by Provider's payment processor and is not stored by Provider.
  deletion:
    route: contact privacy@syftdata.com
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: true
    source: https://www.syftdata.com/dpa
    text: 'Version: v2.0'
    url: https://www.syftdata.com/dpa
  purposes:
  - purpose: provide, improve, and administer services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: targeted advertising
    text: To deliver targeted advertising to you.
  - purpose: identify usage trends
    text: To identify usage trends.
  - purpose: analysis, testing, automated decision making, profiling
    source: https://www.syftdata.com/dpa
    text: Using data, including analysis, consultation, testing, automated decision making, and profiling
  - purpose: disclosure and making data available
    source: https://www.syftdata.com/dpa
    text: Sharing data, including disclosure, dissemination, allowing access, or otherwise making available
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: three (3) months
    scope: account termination
    text: No purpose in this notice will require us keeping your personal information for longer than three (3) months past the termination of the user's account.
  - period: null
    scope: Customer Personal Data
    source: https://www.syftdata.com/dpa
    text: Provider will process Customer Personal Data as long as required (i) to conduct the Processing activities instructed in Section 2.2(a)-(d) of the Standard Terms; or (ii) by Applicable Laws.
  rights:
  - right: access
    text: Right to access your personal data
  - right: correction
    text: Right to correct inaccuracies in your personal data
  - right: deletion
    text: Right to request the deletion of your personal data
  - right: portability
    text: Right to obtain a copy of the personal data you previously shared with us
  - right: opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    source: https://www.syftdata.com/dpa
    text: Approved Subprocessors https://trust.syftdata.com
    url: https://trust.syftdata.com
  transfers:
  - mechanism: SCC
    text: We have implemented measures to protect your personal information, including by using the European Commission's Standard Contractual Clauses for transfers of personal information between our group companies and between us and our third-party providers.
  - mechanism: SCC
    source: https://www.syftdata.com/dpa
    text: Clause 13 of the EEA SCCs
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Syft Data
provenance_date: '2026-11-10'
provider_name: Syft Data
provider_slug: syft-data
slug: syft-data-privacy-policy
source_date: '2026-11-10'
source_filename: syft-data-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.syftdata.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Syft Data\naid: syft-data\nurl: https://www.syftdata.com/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.syftdata.com/dpa\n  - https://www.syftdata.com/privacy.html\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: email addresses usernames passwords names\n- category: device\n  text: device and usage information, such as your IP address, browser and device characteristics, operating system,\n    language preferences, referring URLs, device name, country, location,\
  \ information about how and when you use\n    our Services\n- category: behavioral\n  text: Browsing history, search history, online behavior, interest data, and interactions with our and other websites,\n    applications, systems, and advertisements\n- category: identifying\n  text: 'Identifiers and contact data: name, business email, personal email (where provided by Customer), LinkedIn\n    profile URL, other social handles.'\n  source: https://www.syftdata.com/dpa\n- category: professional\n  text: 'Professional and employment data: job title, seniority, function, employer / company name, company domain,\n    employment history.'\n  source: https://www.syftdata.com/dpa\n- category: device\n  text: 'Online identifiers and device data collected via Provider''s tracking technologies on Customer''s properties:\n    IP address, approximate geolocation derived from IP, user-agent, cookie and session identifiers, page and event\n    activity.'\n  source: https://www.syftdata.com/dpa\n- category:\
  \ behavioral\n  text: 'Third-party intent signals: topic engagement signals, content engagement signals, event attendance signals,\n    and similar behavioral indicators derived from third-party data partners, public sources, and intent-signal\n    networks.'\n  source: https://www.syftdata.com/dpa\n- category: financial\n  text: Payment card data is handled directly by Provider's payment processor and is not stored by Provider.\n  source: https://www.syftdata.com/dpa\npurposes:\n- purpose: provide, improve, and administer services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: targeted advertising\n  text: To deliver targeted advertising to you.\n- purpose: identify usage trends\n  text: To identify usage trends.\n- purpose: analysis, testing, automated decision making, profiling\n  text: Using data, including analysis, consultation, testing, automated\
  \ decision making, and profiling\n  source: https://www.syftdata.com/dpa\n- purpose: disclosure and making data available\n  text: Sharing data, including disclosure, dissemination, allowing access, or otherwise making available\n  source: https://www.syftdata.com/dpa\nretention:\n- scope: account termination\n  period: three (3) months\n  text: No purpose in this notice will require us keeping your personal information for longer than three (3) months\n    past the termination of the user's account.\n- scope: Customer Personal Data\n  period: null\n  text: Provider will process Customer Personal Data as long as required (i) to conduct the Processing activities\n    instructed in Section 2.2(a)-(d) of the Standard Terms; or (ii) by Applicable Laws.\n  source: https://www.syftdata.com/dpa\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: SCC\n  text: We have implemented measures to protect your personal information, including\
  \ by using the European Commission's\n    Standard Contractual Clauses for transfers of personal information between our group companies and between us\n    and our third-party providers.\n- mechanism: SCC\n  text: Clause 13 of the EEA SCCs\n  source: https://www.syftdata.com/dpa\nsubprocessors:\n  url: https://trust.syftdata.com\n  text: Approved Subprocessors https://trust.syftdata.com\n  source: https://www.syftdata.com/dpa\ndpa:\n  available: true\n  url: https://www.syftdata.com/dpa\n  text: 'Version: v2.0'\n  source: https://www.syftdata.com/dpa\ndeletion:\n  route: contact privacy@syftdata.com\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: access\n  text: Right to access your personal data\n- right: correction\n  text: Right to correct inaccuracies in your personal data\n- right: deletion\n  text: Right to request the deletion of your personal data\n- right: portability\n\
  \  text: Right to obtain a copy of the personal data you previously shared with us\n- right: opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/syft-data/privacy/syft-data-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from Syft Data's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Lead Intelligence
- Intent Data
- Website Visitor Identification
- Sales Intelligence
- Go-To-Market
- Analytics
- MCP
---
