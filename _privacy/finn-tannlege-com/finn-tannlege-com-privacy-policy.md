---
api_specs:
- filename: finn-tannlege-com-a2a-api-openapi.yml
  format: yaml
  label: Finn-tannlege A2a API
  slug: finn-tannlege-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finn-tannlege-com/openapi/finn-tannlege-com-a2a-api-openapi.yml
- filename: finn-tannlege-com-llms-txt-api-openapi.yml
  format: yaml
  label: Finn-tannlege Llms.txt API
  slug: finn-tannlege-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finn-tannlege-com/openapi/finn-tannlege-com-llms-txt-api-openapi.yml
- filename: finn-tannlege-com-mcp-api-openapi.yml
  format: yaml
  label: Finn-tannlege MCP API
  slug: finn-tannlege-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finn-tannlege-com/openapi/finn-tannlege-com-mcp-api-openapi.yml
- filename: finn-tannlege-com-tannlege-api-openapi.yml
  format: yaml
  label: Finn-tannlege Tannlege API
  slug: finn-tannlege-com-tannlege-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finn-tannlege-com/openapi/finn-tannlege-com-tannlege-api-openapi.yml
- filename: finn-tannlege-com-well-known-api-openapi.yml
  format: yaml
  label: Finn-tannlege .well Known API
  slug: finn-tannlege-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finn-tannlege-com/openapi/finn-tannlege-com-well-known-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: for tannleger lagrer vi navn, HPR-nummer, spesialitet(er) og kobling til klinikk
  - category: contact
    text: navn, e-postadresse, emne og melding du selv sender oss
  - category: behavioral
    text: Når du søker på nettsiden eller via API-et, lagrer vi i tillegg søketeksten og filtrene du valgte
  - category: device
    text: en grov klassifisering av nettleseren
  - category: professional
    text: åpningstider, behandlingstilbud og presentasjonstekst
  deletion:
    route: email to kontakt@finn-tannlege.com
    text: Send forespørsel til kontakt@finn-tannlege.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service usage statistics
    text: For å forstå hvordan tjenesten brukes
  - purpose: handling contact requests
    text: Meldingen lagres for å behandle forespørselen din.
  - purpose: verifying health personnel authorisation
    text: verifisere helsepersonells autorisasjon
  residency:
  - region: Stockholm, Sweden (Fly.io arn)
    text: Tjenesten kjører i Fly.ios region arn (Stockholm, Sverige)
  retention:
  - period: 60 dager
    scope: visit and search log entries
    text: Disse enkeltregistreringene slettes automatisk etter 60 dager.
  rights:
  - right: access
    text: be om innsyn i hvilke opplysninger vi har om deg
  - right: rectification
    text: be om korrigering av feilaktige opplysninger
  - right: erasure
    text: be om sletting der vilkårene er oppfylt
  - right: objection
    text: protestere mot behandling basert på berettiget interesse
  role:
    text: Behandlingsansvarlig for Finn-tannlege.com er AGENTPLATFORM.NO AS (org.nr. 938 635 676), Haakon Tveters vei 66, 0686 Oslo.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Vi selger ikke personopplysninger og deler dem ikke med tredjeparter for kommersielle formål.
  subprocessors:
    text: Vi bruker følgende leverandører til driften
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Finn-tannlege
provenance_date: '2026-11-09'
provider_name: Finn-tannlege
provider_slug: finn-tannlege-com
slug: finn-tannlege-com-privacy-policy
source_date: '2026-11-09'
source_filename: finn-tannlege-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://finn-tannlege.com/personvern
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Finn-tannlege\naid: finn-tannlege-com\nurl: https://finn-tannlege.com/personvern\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Behandlingsansvarlig for Finn-tannlege.com er AGENTPLATFORM.NO AS (org.nr. 938 635 676), Haakon Tveters\n    vei 66, 0686 Oslo.\ndata_categories:\n- category: identifying\n  text: for tannleger lagrer vi navn, HPR-nummer, spesialitet(er) og kobling til klinikk\n- category: contact\n  text: navn, e-postadresse, emne og melding du selv sender oss\n- category: behavioral\n  text: Når du søker på nettsiden eller via API-et, lagrer vi i tillegg søketeksten og filtrene\
  \ du valgte\n- category: device\n  text: en grov klassifisering av nettleseren\n- category: professional\n  text: åpningstider, behandlingstilbud og presentasjonstekst\npurposes:\n- purpose: service usage statistics\n  text: For å forstå hvordan tjenesten brukes\n- purpose: handling contact requests\n  text: Meldingen lagres for å behandle forespørselen din.\n- purpose: verifying health personnel authorisation\n  text: verifisere helsepersonells autorisasjon\nretention:\n- scope: visit and search log entries\n  period: 60 dager\n  text: Disse enkeltregistreringene slettes automatisk etter 60 dager.\nresidency:\n- region: Stockholm, Sweden (Fly.io arn)\n  text: Tjenesten kjører i Fly.ios region arn (Stockholm, Sverige)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Vi bruker følgende leverandører til driften\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to kontakt@finn-tannlege.com\n  text: Send forespørsel til kontakt@finn-tannlege.com\nrights:\n\
  - right: access\n  text: be om innsyn i hvilke opplysninger vi har om deg\n- right: rectification\n  text: be om korrigering av feilaktige opplysninger\n- right: erasure\n  text: be om sletting der vilkårene er oppfylt\n- right: objection\n  text: protestere mot behandling basert på berettiget interesse\nsale_or_sharing:\n  stance: prohibited\n  text: Vi selger ikke personopplysninger og deler dem ikke med tredjeparter for kommersielle formål.\n"
source_yaml_url: https://artifacts.apis.io/finn-tannlege-com/privacy/finn-tannlege-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Finn-tannlege's own page on 2026-11-09.
synthetic: false
tags:
- Dental
- Healthcare
- Directory
- Norway
- Search
- Open Data
- A2A
- MCP
- AI Agents
- Clinics
---
