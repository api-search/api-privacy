---
api_specs:
- filename: citeerbaar-nl-agents-api-openapi.yml
  format: yaml
  label: Citeerbaar Agents API
  slug: citeerbaar-nl-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citeerbaar-nl/openapi/citeerbaar-nl-agents-api-openapi.yml
- filename: citeerbaar-nl-open-data-api-openapi.yml
  format: yaml
  label: Citeerbaar Open data API
  slug: citeerbaar-nl-open-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citeerbaar-nl/openapi/citeerbaar-nl-open-data-api-openapi.yml
- filename: citeerbaar-nl-status-api-openapi.yml
  format: yaml
  label: Citeerbaar Status API
  slug: citeerbaar-nl-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citeerbaar-nl/openapi/citeerbaar-nl-status-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: naam, e-mailadres, bedrijfsnaam (bij een pakketaanvraag), telefoonnummer (optioneel) en website-URL
  - category: behavioral
    text: Google Analytics en Microsoft Clarity leggen vast welke pagina’s je bekijkt, waar je klikt en hoe ver je scrolt.
  - category: device
    text: tijdstip, user-agent, pad en een gepseudonimiseerd IP-adres
  deletion:
    route: email
    text: Stuur een mail naar hello@citeerbaar.nl en we regelen het.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer requests
    text: 'Je aanvraag beantwoorden (Quick Check, Scan, contact): op jouw verzoek, voorafgaand aan een eventuele overeenkomst.'
  - purpose: execute contracts and invoicing
    text: 'Opdrachten uitvoeren en factureren : voor de uitvoering van de overeenkomst.'
  - purpose: site analytics and bot logging
    text: 'Bezoekersstatistiek, sessie-opnames en het logboek van bots : ons gerechtvaardigd belang om te weten hoe de site gebruikt wordt'
  - purpose: spam filtering and security
    text: 'Spamfilter en beveiliging : ons gerechtvaardigd belang om de site en de formulieren veilig te houden.'
  residency:
  - region: Germany
    text: Strato (onderdeel van IONOS SE), waar de website en e-mail draaien, in datacenters in Duitsland.
  retention:
  - period: 2 jaar
    scope: request data
    text: Aanvraag-gegevens bewaren we maximaal 2 jaar na het laatste contact.
  - period: 7 jaar
    scope: customer data
    text: Klantgegevens bewaren we zolang we zakelijke relatie hebben en 7 jaar daarna voor de fiscale bewaarplicht.
  - period: 90 dagen
    scope: bot log
    text: Het logboek wordt na 90 dagen automatisch verwijderd
  - period: 30 dagen
    scope: Clarity recordings
    text: Microsoft Clarity bewaart opnames 30 dagen.
  - period: 14 maanden
    scope: Google Analytics user data
    text: Google Analytics bewaart gebeurtenisgegevens 2 maanden en gebruikersgegevens 14 maanden
  - period: 2 uur
    scope: agent conversation memory
    text: Tijdens het gesprek onthoudt de agent de berichten maximaal 2 uur vanaf het begin
  rights:
  - right: access
    text: Inzage in je gegevens
  - right: rectification
    text: Correctie van je gegevens
  - right: erasure
    text: Verwijdering van je gegevens
  - right: restriction
    text: Beperking van de verwerking
  - right: objection
    text: Bezwaar tegen verwerking op basis van gerechtvaardigd belang, zoals statistiek
  - right: portability
    text: Overdraagbaarheid van de gegevens die je zelf hebt gegeven
  - right: withdraw consent
    text: Het intrekken van toestemming
  - right: complaint
    text: Indienen van een klacht bij de Autoriteit Persoonsgegevens
  role:
    text: 'Bedrijfsgegevens (verwerkingsverantwoordelijke): Mixx’d Media Julianaplantsoen 295, 1111 XP Diemen'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Met al deze partijen hebben we verwerkersovereenkomsten waar nodig.
    url: null
  transfers:
  - mechanism: DPF
    text: Google kan gegevens ook in de Verenigde Staten verwerken, onder het EU-VS Data Privacy Framework.
  - mechanism: SCC
    text: kunnen ook bij Microsoft Corporation in de Verenigde Staten worden verwerkt, onder standaardcontractbepalingen.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Citeerbaar
provenance_date: '2026-11-09'
provider_name: Citeerbaar
provider_slug: citeerbaar-nl
slug: citeerbaar-nl-privacy-policy
source_date: '2026-11-09'
source_filename: citeerbaar-nl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.citeerbaar.nl/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Citeerbaar\naid: citeerbaar-nl\nurl: https://www.citeerbaar.nl/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Bedrijfsgegevens (verwerkingsverantwoordelijke): Mixx’d Media Julianaplantsoen 295, 1111 XP Diemen'\ndata_categories:\n- category: contact\n  text: naam, e-mailadres, bedrijfsnaam (bij een pakketaanvraag), telefoonnummer (optioneel) en website-URL\n- category: behavioral\n  text: Google Analytics en Microsoft Clarity leggen vast welke pagina’s je bekijkt, waar je klikt en hoe ver je\n    scrolt.\n- category: device\n  text: tijdstip, user-agent, pad en een gepseudonimiseerd\
  \ IP-adres\npurposes:\n- purpose: answer requests\n  text: 'Je aanvraag beantwoorden (Quick Check, Scan, contact): op jouw verzoek, voorafgaand aan een eventuele overeenkomst.'\n- purpose: execute contracts and invoicing\n  text: 'Opdrachten uitvoeren en factureren : voor de uitvoering van de overeenkomst.'\n- purpose: site analytics and bot logging\n  text: 'Bezoekersstatistiek, sessie-opnames en het logboek van bots : ons gerechtvaardigd belang om te weten hoe\n    de site gebruikt wordt'\n- purpose: spam filtering and security\n  text: 'Spamfilter en beveiliging : ons gerechtvaardigd belang om de site en de formulieren veilig te houden.'\nretention:\n- scope: request data\n  period: 2 jaar\n  text: Aanvraag-gegevens bewaren we maximaal 2 jaar na het laatste contact.\n- scope: customer data\n  period: 7 jaar\n  text: Klantgegevens bewaren we zolang we zakelijke relatie hebben en 7 jaar daarna voor de fiscale bewaarplicht.\n- scope: bot log\n  period: 90 dagen\n  text: Het logboek wordt\
  \ na 90 dagen automatisch verwijderd\n- scope: Clarity recordings\n  period: 30 dagen\n  text: Microsoft Clarity bewaart opnames 30 dagen.\n- scope: Google Analytics user data\n  period: 14 maanden\n  text: Google Analytics bewaart gebeurtenisgegevens 2 maanden en gebruikersgegevens 14 maanden\n- scope: agent conversation memory\n  period: 2 uur\n  text: Tijdens het gesprek onthoudt de agent de berichten maximaal 2 uur vanaf het begin\nresidency:\n- region: Germany\n  text: Strato (onderdeel van IONOS SE), waar de website en e-mail draaien, in datacenters in Duitsland.\ntransfers:\n- mechanism: DPF\n  text: Google kan gegevens ook in de Verenigde Staten verwerken, onder het EU-VS Data Privacy Framework.\n- mechanism: SCC\n  text: kunnen ook bij Microsoft Corporation in de Verenigde Staten worden verwerkt, onder standaardcontractbepalingen.\nsubprocessors:\n  url: null\n  text: Met al deze partijen hebben we verwerkersovereenkomsten waar nodig.\ndpa:\n  available: null\n  url: null\n  text:\
  \ null\ndeletion:\n  route: email\n  text: Stuur een mail naar hello@citeerbaar.nl en we regelen het.\nrights:\n- right: access\n  text: Inzage in je gegevens\n- right: rectification\n  text: Correctie van je gegevens\n- right: erasure\n  text: Verwijdering van je gegevens\n- right: restriction\n  text: Beperking van de verwerking\n- right: objection\n  text: Bezwaar tegen verwerking op basis van gerechtvaardigd belang, zoals statistiek\n- right: portability\n  text: Overdraagbaarheid van de gegevens die je zelf hebt gegeven\n- right: withdraw consent\n  text: Het intrekken van toestemming\n- right: complaint\n  text: Indienen van een klacht bij de Autoriteit Persoonsgegevens\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citeerbaar-nl/privacy/citeerbaar-nl-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Citeerbaar's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Digital-PR
- Netherlands
- Citations
---
