---
api_specs:
- filename: woz-api-nl-account-api-openapi.yml
  format: yaml
  label: woz-api-nl Account API
  slug: woz-api-nl-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-account-api-openapi.yml
- filename: woz-api-nl-adressen-api-openapi.yml
  format: yaml
  label: woz-api-nl Adressen API
  slug: woz-api-nl-adressen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-adressen-api-openapi.yml
- filename: woz-api-nl-lijst-api-openapi.yml
  format: yaml
  label: woz-api-nl Lijst API
  slug: woz-api-nl-lijst-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-lijst-api-openapi.yml
- filename: woz-api-nl-proef-api-openapi.yml
  format: yaml
  label: woz-api-nl Proef API
  slug: woz-api-nl-proef-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woz-api-nl/openapi/woz-api-nl-proef-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: contact
    text: Je e-mailadres. Dat is tegelijk je inlognaam en het adres waarop wij je bereiken.
  - category: financial
    text: Bij een betaling met iDEAL geeft Mollie ons ook de naam en het rekeningnummer van de betaler door
  - category: device
    text: Het IP-adres en de user agent van de aanroep.
  - category: behavioral
    text: Wij meten elk bezoek aan de site, zonder cookie
  - category: communication
    text: Mail die je ons stuurt komt in onze mailbox en blijft daar bewaard zolang dat voor de afhandeling nodig is.
  - category: other
    text: Bestanden die je in de Excel-wizard uploadt, inclusief de adressen die erin staan
  deletion:
    route: 'Account settings: close the account'
    text: Zeg je op, dan verwijderen wij het account en de bijbehorende gegevens.
  dpa:
    available: true
    text: zie de verwerkersovereenkomst
    url: null
  purposes:
  - purpose: Levering van de dienst
    text: Om de dienst te leveren. Account, API-sleutels, credits, opvragingen en facturen.
  - purpose: Beveiliging
    text: Om de dienst te beveiligen. IP-adressen, foutlogboeken en misbruikdetectie.
  - purpose: Statistieken zonder cookie
    text: Om te begrijpen hoe de site gebruikt wordt.
  - purpose: Referral programma
    text: Om het referral programma eerlijk te houden.
  - purpose: Wettelijke plicht
    text: Om aan de wet te voldoen. Facturen en de administratie daaromheen.
  residency:
  - region: EU
    text: ook op een tweede plek binnen de EU
  - region: United States
    text: OpenAI verwerkt dit in de Verenigde Staten
  - region: Outside EEA
    text: Anthropic verwerkt dit mede buiten de Europese Economische Ruimte.
  retention:
  - period: zolang je account bestaat
    scope: Account
    text: 'Je account en de gegevens die eraan hangen: zolang je account bestaat.'
  - period: zeven jaar
    scope: Facturen en betaalgegevens
    text: 'Facturen en betaalgegevens: zeven jaar, omdat de Belastingdienst dat voorschrijft.'
  - period: tot je de opdracht hebt opgehaald
    scope: Geüploade Excel-bestanden
    text: 'Geüploade Excel-bestanden: tot je de opdracht hebt opgehaald.'
  - period: dertien maanden
    scope: Bezoeken zonder cookie
    text: 'Bezoeken en pagina''s uit de meting zonder cookie: dertien maanden.'
  - period: zeven dagen
    scope: Code van IP-adres en browser
    text: 'De code van je IP-adres en browser: zeven dagen.'
  rights:
  - right: Access
    text: inzage in de gegevens die wij van je hebben
  - right: Rectification
    text: correctie van gegevens die niet kloppen
  - right: Erasure
    text: verwijdering van je gegevens
  - right: Restriction
    text: beperking van wat wij ermee doen
  - right: Portability
    text: je gegevens in een leesbaar bestand, zodat je ze kunt meenemen
  - right: Objection
    text: bezwaar tegen het gebruik op grond van ons gerechtvaardigd belang
  - right: Withdraw consent
    text: je toestemming voor statistieken en marketing intrekken
  role:
    text: Lever je zelf adressen aan, dan verwerken wij die uitsluitend in jouw opdracht; zie de verwerkersovereenkomst
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Wij verkopen je gegevens niet en wij gebruiken ze niet voor advertenties van derden.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: op basis van de standaardcontractbepalingen van de Europese Commissie
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: woz-api-nl
provenance_date: '2026-11-10'
provider_name: woz-api-nl
provider_slug: woz-api-nl
slug: woz-api-nl-privacy-policy
source_date: '2026-11-10'
source_filename: woz-api-nl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://woz-api.nl/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: woz-api-nl\naid: woz-api-nl\nurl: https://woz-api.nl/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Lever je zelf adressen aan, dan verwerken wij die uitsluitend in jouw opdracht; zie de verwerkersovereenkomst\ndata_categories:\n- category: contact\n  text: Je e-mailadres. Dat is tegelijk je inlognaam en het adres waarop wij je bereiken.\n- category: financial\n  text: Bij een betaling met iDEAL geeft Mollie ons ook de naam en het rekeningnummer van de betaler door\n- category: device\n  text: Het IP-adres en de user agent van de aanroep.\n- category: behavioral\n  text: Wij meten elk bezoek\
  \ aan de site, zonder cookie\n- category: communication\n  text: Mail die je ons stuurt komt in onze mailbox en blijft daar bewaard zolang dat voor de afhandeling nodig\n    is.\n- category: other\n  text: Bestanden die je in de Excel-wizard uploadt, inclusief de adressen die erin staan\npurposes:\n- purpose: Levering van de dienst\n  text: Om de dienst te leveren. Account, API-sleutels, credits, opvragingen en facturen.\n- purpose: Beveiliging\n  text: Om de dienst te beveiligen. IP-adressen, foutlogboeken en misbruikdetectie.\n- purpose: Statistieken zonder cookie\n  text: Om te begrijpen hoe de site gebruikt wordt.\n- purpose: Referral programma\n  text: Om het referral programma eerlijk te houden.\n- purpose: Wettelijke plicht\n  text: Om aan de wet te voldoen. Facturen en de administratie daaromheen.\nretention:\n- scope: Account\n  period: zolang je account bestaat\n  text: 'Je account en de gegevens die eraan hangen: zolang je account bestaat.'\n- scope: Facturen en betaalgegevens\n\
  \  period: zeven jaar\n  text: 'Facturen en betaalgegevens: zeven jaar, omdat de Belastingdienst dat voorschrijft.'\n- scope: Geüploade Excel-bestanden\n  period: tot je de opdracht hebt opgehaald\n  text: 'Geüploade Excel-bestanden: tot je de opdracht hebt opgehaald.'\n- scope: Bezoeken zonder cookie\n  period: dertien maanden\n  text: 'Bezoeken en pagina''s uit de meting zonder cookie: dertien maanden.'\n- scope: Code van IP-adres en browser\n  period: zeven dagen\n  text: 'De code van je IP-adres en browser: zeven dagen.'\nresidency:\n- region: EU\n  text: ook op een tweede plek binnen de EU\n- region: United States\n  text: OpenAI verwerkt dit in de Verenigde Staten\n- region: Outside EEA\n  text: Anthropic verwerkt dit mede buiten de Europese Economische Ruimte.\ntransfers:\n- mechanism: SCC\n  text: op basis van de standaardcontractbepalingen van de Europese Commissie\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: zie de verwerkersovereenkomst\n\
  deletion:\n  route: 'Account settings: close the account'\n  text: Zeg je op, dan verwijderen wij het account en de bijbehorende gegevens.\nrights:\n- right: Access\n  text: inzage in de gegevens die wij van je hebben\n- right: Rectification\n  text: correctie van gegevens die niet kloppen\n- right: Erasure\n  text: verwijdering van je gegevens\n- right: Restriction\n  text: beperking van wat wij ermee doen\n- right: Portability\n  text: je gegevens in een leesbaar bestand, zodat je ze kunt meenemen\n- right: Objection\n  text: bezwaar tegen het gebruik op grond van ons gerechtvaardigd belang\n- right: Withdraw consent\n  text: je toestemming voor statistieken en marketing intrekken\nsale_or_sharing:\n  stance: prohibited\n  text: Wij verkopen je gegevens niet en wij gebruiken ze niet voor advertenties van derden.\n"
source_yaml_url: https://artifacts.apis.io/woz-api-nl/privacy/woz-api-nl-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from woz-api-nl's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Netherlands
- Property Valuation
- WOZ
---
