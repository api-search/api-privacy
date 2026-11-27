---
api_specs:
- filename: routebase-api-specs-api-openapi.yml
  format: yaml
  label: Routebase API Specs API
  slug: routebase-api-specs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-api-specs-api-openapi.yml
- filename: routebase-ci-test-runs-api-openapi.yml
  format: yaml
  label: Routebase CI & Test Runs API
  slug: routebase-ci-test-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-ci-test-runs-api-openapi.yml
- filename: routebase-docs-as-code-api-openapi.yml
  format: yaml
  label: Routebase Docs as Code API
  slug: routebase-docs-as-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-docs-as-code-api-openapi.yml
- filename: routebase-scim-api-openapi.yml
  format: yaml
  label: Routebase SCIM API
  slug: routebase-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-scim-api-openapi.yml
- filename: routebase-security-api-openapi.yml
  format: yaml
  label: Routebase Security API
  slug: routebase-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routebase/openapi/routebase-security-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: we process the name, e-mail address, topic and message you enter, together with the IP address the request was sent from
  - category: device
    text: technical connection data (IP address, user agent, timestamp, requested resource) is processed to deliver the site and to protect it against abuse
  - category: behavioral
    text: Clarity records how you scroll, move, click and tap on our pages and turns this into session replays and heatmaps.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answer enquiries and prevent form misuse
    text: in order to answer you and to keep the form free of abuse
  - purpose: Operate and secure website
    text: to deliver the site and to protect it against abuse
  - purpose: Aggregate site usage statistics
    text: to derive aggregate, non-identifying statistics (page views, referrer, country, device type)
  - purpose: Ad conversion measurement
    text: To find out which ads lead to sign-ups, we use the Google Ads conversion tag
  - purpose: Session analytics
    text: To understand how visitors use this website and where they leave it, we use Microsoft Clarity
  residency:
  - region: EU
    text: Access logs are retained for 30 days in a log store located in the EU
  - region: Germany
    text: with all data processed and stored on servers in Germany
  - region: European Union
    text: The provider acts as our processor and stores this data within the European Union.
  retention:
  - period: 30 days
    scope: Access logs
    text: Access logs are retained for 30 days in a log store located in the EU, after which they are deleted automatically.
  - period: null
    scope: Contact form correspondence
    text: We keep the resulting correspondence for as long as it takes to handle your request, and where commercial or tax law requires it, for the statutory retention period.
  - period: browser session
    scope: OpenAI and Microsoft click references
    text: Each reference is stored for the duration of your browser session only and is deleted when you close the tab.
  rights:
  - right: access
    text: Under the GDPR you have the right to access, rectification, erasure, restriction of processing, data portability, and objection.
  - right: withdraw consent
    text: You can withdraw your consent at any time with effect for the future via the Cookie settings link at the bottom of every page
  - right: complain to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority
  role:
    text: Controller Routebase GmbH, Wegedornstraße 253Q, 12524 Berlin, Germany
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers to Microsoft Corporation in the USA are based on the EU-U.S. Data Privacy Framework.
  - mechanism: SCC
    text: Our server then reports that one sign-up to OpenAI OpCo, LLC, 1455 3rd Street, San Francisco, CA 94158, USA, on the basis of standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Routebase
provenance_date: '2026-11-10'
provider_name: Routebase
provider_slug: routebase
slug: routebase-privacy-policy
source_date: '2026-11-10'
source_filename: routebase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://routebase.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Routebase\naid: routebase\nurl: https://routebase.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Routebase GmbH, Wegedornstraße 253Q, 12524 Berlin, Germany\ndata_categories:\n- category: contact\n  text: we process the name, e-mail address, topic and message you enter, together with the IP address the request\n    was sent from\n- category: device\n  text: technical connection data (IP address, user agent, timestamp, requested resource) is processed to deliver\n    the site and to protect it against abuse\n- category: behavioral\n  text: Clarity records how you scroll,\
  \ move, click and tap on our pages and turns this into session replays and\n    heatmaps.\npurposes:\n- purpose: Answer enquiries and prevent form misuse\n  text: in order to answer you and to keep the form free of abuse\n- purpose: Operate and secure website\n  text: to deliver the site and to protect it against abuse\n- purpose: Aggregate site usage statistics\n  text: to derive aggregate, non-identifying statistics (page views, referrer, country, device type)\n- purpose: Ad conversion measurement\n  text: To find out which ads lead to sign-ups, we use the Google Ads conversion tag\n- purpose: Session analytics\n  text: To understand how visitors use this website and where they leave it, we use Microsoft Clarity\nretention:\n- scope: Access logs\n  period: 30 days\n  text: Access logs are retained for 30 days in a log store located in the EU, after which they are deleted automatically.\n- scope: Contact form correspondence\n  period: null\n  text: We keep the resulting correspondence\
  \ for as long as it takes to handle your request, and where commercial\n    or tax law requires it, for the statutory retention period.\n- scope: OpenAI and Microsoft click references\n  period: browser session\n  text: Each reference is stored for the duration of your browser session only and is deleted when you close the\n    tab.\nresidency:\n- region: EU\n  text: Access logs are retained for 30 days in a log store located in the EU\n- region: Germany\n  text: with all data processed and stored on servers in Germany\n- region: European Union\n  text: The provider acts as our processor and stores this data within the European Union.\ntransfers:\n- mechanism: DPF\n  text: Transfers to Microsoft Corporation in the USA are based on the EU-U.S. Data Privacy Framework.\n- mechanism: SCC\n  text: Our server then reports that one sign-up to OpenAI OpCo, LLC, 1455 3rd Street, San Francisco, CA 94158,\n    USA, on the basis of standard contractual clauses.\nsubprocessors:\n  url: null\n  text:\
  \ null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Under the GDPR you have the right to access, rectification, erasure, restriction of processing, data portability,\n    and objection.\n- right: withdraw consent\n  text: You can withdraw your consent at any time with effect for the future via the Cookie settings link at the\n    bottom of every page\n- right: complain to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/routebase/privacy/routebase-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
summary_line: 20 quoted statements, read from Routebase's own page on 2026-11-10.
synthetic: false
tags:
- API lifecycle management
- API Design
- OpenAPI
- API Documentation
- API Testing
- API Mocking
- API Monitoring
- API Security
- MCP
- AI Agents
- Developer Tools
- CI/CD
- REST
- OAuth 2.1
- SCIM
- Streamable HTTP
---
