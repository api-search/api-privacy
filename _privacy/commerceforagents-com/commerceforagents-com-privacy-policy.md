---
api_specs:
- filename: commerceforagents-com-mcp-api-openapi.yml
  format: yaml
  label: Commerce for Agents MCP API
  slug: commerceforagents-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commerceforagents-com/openapi/commerceforagents-com-mcp-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: salutation, first and last name, date of birth, email address, phone number (optional), street and house number
  - category: financial
    text: IBAN and account holder for the SEPA direct debit mandate
  - category: location
    text: the approximate location the host platform relays with the request (country, region, city, and coordinates)
  - category: behavioral
    text: Website. This website is delivered through Cloudflare, which may process IP addresses in connection logs to serve and protect the site.
  - category: device
    text: the browser or client identification
  - category: identifying
    text: a pseudonymous user identifier and session identifier provided by the host platform
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Comparison of energy tariffs
    text: Processing the comparison inputs and forwarding them to our data partner is necessary to provide the comparison the user requested.
  - purpose: Concierge switch contract submission
    text: Processing the booking data is necessary to perform the switching service the user requested, including submitting the contract application to the provider on the user's behalf and sending the confirmation email.
  - purpose: Analytics
    text: The collection of usage data is based on our legitimate interest in operating, securing and improving the Service.
  - purpose: Website analytics
    text: The use of Google Analytics on this website is based on our legitimate interest in understanding how the website is used and improving it.
  residency:
  - region: EEA
    text: Analytics data is processed and stored on our Google Cloud infrastructure within the European Economic Area (EEA).
  - region: EEA
    text: Data is hosted in Google Cloud regions within the EEA.
  retention:
  - period: 24 hours
    scope: Comparison inputs
    text: Comparison inputs are cached for up to 24 hours together with the offers of that comparison and then deleted automatically.
  - period: 180 days
    scope: Booking data
    text: Booking data is retained until the contract application has been submitted to the provider and the provider has confirmed it, and is deleted no later than 180 days after submission
  - period: 90 days
    scope: Analytics data
    text: Analytics data is retained for 90 days and then deleted automatically.
  - period: 2 months
    scope: Google Analytics data of website
    text: Google Analytics data of this website is retained for 2 months and then deleted automatically.
  rights:
  - right: access
    text: Under the GDPR you generally have the right to access, rectification, erasure, restriction of processing, data portability, and objection.
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with a data protection supervisory authority
  role:
    text: Yavio GmbH Maria-Goeppert-Str. 1 23562 Lübeck, Germany
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: To the extent Google's U.S. parent company may have access to data, we rely on the EU Standard Contractual Clauses and the EU-US Data Privacy Framework as transfer safeguards.
  - mechanism: DPF
    text: Google LLC is certified under the EU-US Data Privacy Framework; the transfer relies on the European Commission's adequacy decision for it (Art. 45 GDPR).
  - mechanism: other
    text: Sending the address to the US Census Bureau Geocoder, and where needed the coordinates to the FCC block lookup, is necessary for the performance of the broadband comparison the user requested.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Commerce for Agents
provenance_date: '2026-11-09'
provider_name: Commerce for Agents
provider_slug: commerceforagents-com
slug: commerceforagents-com-privacy-policy
source_date: '2026-11-09'
source_filename: commerceforagents-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://commerceforagents.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Commerce for Agents\naid: commerceforagents-com\nurl: https://commerceforagents.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Yavio GmbH Maria-Goeppert-Str. 1 23562 Lübeck, Germany\ndata_categories:\n- category: contact\n  text: salutation, first and last name, date of birth, email address, phone number (optional), street and house\n    number\n- category: financial\n  text: IBAN and account holder for the SEPA direct debit mandate\n- category: location\n  text: the approximate location the host platform relays with the request (country, region, city, and coordinates)\n- category:\
  \ behavioral\n  text: Website. This website is delivered through Cloudflare, which may process IP addresses in connection logs\n    to serve and protect the site.\n- category: device\n  text: the browser or client identification\n- category: identifying\n  text: a pseudonymous user identifier and session identifier provided by the host platform\npurposes:\n- purpose: Comparison of energy tariffs\n  text: Processing the comparison inputs and forwarding them to our data partner is necessary to provide the comparison\n    the user requested.\n- purpose: Concierge switch contract submission\n  text: Processing the booking data is necessary to perform the switching service the user requested, including\n    submitting the contract application to the provider on the user's behalf and sending the confirmation email.\n- purpose: Analytics\n  text: The collection of usage data is based on our legitimate interest in operating, securing and improving the\n    Service.\n- purpose: Website analytics\n\
  \  text: The use of Google Analytics on this website is based on our legitimate interest in understanding how the\n    website is used and improving it.\nretention:\n- scope: Comparison inputs\n  period: 24 hours\n  text: Comparison inputs are cached for up to 24 hours together with the offers of that comparison and then deleted\n    automatically.\n- scope: Booking data\n  period: 180 days\n  text: Booking data is retained until the contract application has been submitted to the provider and the provider\n    has confirmed it, and is deleted no later than 180 days after submission\n- scope: Analytics data\n  period: 90 days\n  text: Analytics data is retained for 90 days and then deleted automatically.\n- scope: Google Analytics data of website\n  period: 2 months\n  text: Google Analytics data of this website is retained for 2 months and then deleted automatically.\nresidency:\n- region: EEA\n  text: Analytics data is processed and stored on our Google Cloud infrastructure within the\
  \ European Economic Area\n    (EEA).\n- region: EEA\n  text: Data is hosted in Google Cloud regions within the EEA.\ntransfers:\n- mechanism: SCC\n  text: To the extent Google's U.S. parent company may have access to data, we rely on the EU Standard Contractual\n    Clauses and the EU-US Data Privacy Framework as transfer safeguards.\n- mechanism: DPF\n  text: Google LLC is certified under the EU-US Data Privacy Framework; the transfer relies on the European Commission's\n    adequacy decision for it (Art. 45 GDPR).\n- mechanism: other\n  text: Sending the address to the US Census Bureau Geocoder, and where needed the coordinates to the FCC block\n    lookup, is necessary for the performance of the broadband comparison the user requested.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Under the GDPR you generally have the right to access, rectification, erasure, restriction\
  \ of processing,\n    data portability, and objection.\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a data protection supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commerceforagents-com/privacy/commerceforagents-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
summary_line: 22 quoted statements, read from Commerce for Agents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agentic Commerce
- MCP
- Price Comparison
- Energy
- Electricity
- Gas
- Broadband
- Mobile Plans
- eSIM
- VPN
- Germany
---
