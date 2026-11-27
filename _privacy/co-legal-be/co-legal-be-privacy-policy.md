---
claim_count: 42
description: ''
doc:
  data_categories:
  - category: communication
    text: Berichten die u zelf aan ons mailt, verwerken we om uw vraag te beantwoorden.
  - category: communication
    text: Voor multi-turn bewaren we vraag, antwoord en technische taakmetadata in onze Europese operationele database.
  - category: device
    text: volledig IP-adres, user-agent, adres en tijdstip van het verzoek en de status
  - category: device
    text: uw IP-adres ingekort tot een /24-netwerk (IPv4) of /48-netwerk (IPv6)
  - category: identifying
    source: https://co-legal.be/platform-privacy
    text: gebruikers (naam, werk-e-mailadres, rol), dossiergegevens, documenten, tijdsregistratie, facturen en de bijbehorende boekhoudkundige gegevens
  - category: contact
    source: https://co-legal.be/platform-privacy
    text: 'Over cliënten en tegenpartijen van het kantoor: naam, adres, contactgegevens, ondernemingsnummer en de inhoud van dossierstukken'
  - category: device
    source: https://co-legal.be/platform-privacy
    text: een auditlogboek van handelingen in de applicatie (wie deed wat, wanneer) en foutmeldingen voor het oplossen van storingen
  - category: financial
    source: https://co-legal.be/platform-privacy
    text: de toegangstokens van die koppeling, de gekoppelde administratie, en de verwijzing tussen een cliënt in het platform en de bijbehorende relatie in de boekhouding
  - category: contact
    source: https://co-legal.be/security
    text: Co·Legal verwerkt vertrouwelijke juridische, fiscale en financiële gegevens.
  - category: communication
    source: https://co-legal.be/security
    text: 'Een vrije-tekstprompt kan wel persoonsgegevens bevatten: voer daarom geen cliëntgeheimen of dossierinhoud in.'
  deletion:
    route: email to privacy contact
    text: Een verzoek stuurt u naar [email protected]
  dpa:
    available: true
    text: dat legt de verwerkersovereenkomst tussen ons vast
    url: null
  purposes:
  - purpose: technical operation and improvement of the website
    text: Voor de technische werking en verbetering gebruiken we geaggregeerde tellingen uit Cloud Run-originverzoeklogs
  - purpose: reach, content and security of the site
    text: Doel is bereik, inhoud en technische werking van de site verbeteren en misbruik beveiligen
  - purpose: produce the requested answer (MCP)
    text: 'Doel: het gevraagde antwoord maken.'
  - purpose: rate limiting
    text: 'Doel: misbruik en overbelasting van de bronnen voorkomen.'
  - purpose: operate platform for the office
    source: https://co-legal.be/platform-privacy
    text: 'Alleen om het platform te laten werken voor dat kantoor: dossiers beheren, documenten opstellen, uren registreren, factureren, en die facturen doorboeken naar de boekhouding van het kantoor.'
  - purpose: no advertising or resale
    source: https://co-legal.be/platform-privacy
    text: De gegevens worden niet gebruikt voor reclame, niet doorverkocht en niet gedeeld met andere kantoren.
  - purpose: Hosting, opslag en modelverwerking van dossiers
    source: https://co-legal.be/security
    text: Hosting, opslag en modelverwerking van de dossier-, website- én publieke agent draaien binnen de EU.
  residency:
  - region: EU
    text: via Google Cloud Vertex AI's EU-multiregio
  - region: Netherlands
    text: Google Cloud host de server (Cloud Run, regio europe-west4
  - region: European Union
    source: https://co-legal.be/platform-privacy
    text: De gegevens staan bij Google Cloud Platform in de Europese Unie (regio europe-west).
  - region: European Union
    source: https://co-legal.be/security
    text: Hosting, opslag en modelverwerking van de dossier-, website- én publieke agent draaien binnen de EU.
  retention:
  - period: 7 dagen
    scope: A2A conversation history
    text: Een gesprek dat 7 dagen niet gebruikt is, wordt verwijderd
  - period: 7 dagen
    scope: A2A message text
    text: de tekst van een bericht uiterlijk 7 dagen na ontvangst
  - period: maximaal 90 dagen
    scope: A2A operational logs
    text: de bewaartermijn is maximaal 90 dagen
  - period: maximaal 90 dagen
    scope: MCP operational logs
    text: 'Bewaartermijn: maximaal 90 dagen'
  - period: null
    scope: rate limit counter
    text: Die staat alleen in het werkgeheugen, wordt niet weggeschreven
  - period: null
    scope: website chat session storage
    text: De browser bewaart maximaal 24 recente gespreksberichten in de sessieopslag van uw tab
  - period: null
    scope: platform data while office uses service
    source: https://co-legal.be/platform-privacy
    text: Gegevens blijven staan zolang het kantoor het platform gebruikt; het kantoor bepaalt zelf wat het bewaart en wat het verwijdert.
  - period: null
    scope: integration access tokens
    source: https://co-legal.be/platform-privacy
    text: Toegangstokens van een koppeling worden verwijderd zodra het kantoor die koppeling verbreekt.
  - period: null
    scope: Dossierdata
    source: https://co-legal.be/security
    text: Dossierdata blijft staan gedurende de samenwerking en volgens de gedocumenteerde bewaarinstructie van het kantoor.
  - period: 90 dagen
    scope: Backend-logs
    source: https://co-legal.be/security
    text: 'Backend-logs (HTTP-toegang, request-correlatie, security-events): 90 dagen, daarna automatische verwijdering.'
  - period: 7 dagen
    scope: Publieke agent-vragen
    source: https://co-legal.be/security
    text: verwijderd zodra een gesprek 7 dagen niet gebruikt is
  rights:
  - right: access, rectification, erasure, restriction, portability and objection
    text: de rechten op inzage, rectificatie, verwijdering, beperking van verwerking, dataportabiliteit en bezwaar
  - right: complaint
    text: Dan kunt u een klacht indienen bij de Autoriteit Persoonsgegevens (Nederland) of de Gegevensbeschermingsautoriteit (België)
  - right: access, correction, deletion
    source: https://co-legal.be/platform-privacy
    text: Verzoeken over persoonsgegevens (inzage, correctie, verwijdering) lopen via het kantoor, dat verwerkingsverantwoordelijke is.
  - right: GDPR rights (access, rectification, erasure, portability)
    source: https://co-legal.be/security
    text: Heeft u een GDPR-recht (inzage, rectificatie, verwijdering, dataportabiliteit) dat u wil uitoefenen — stuur de aanvraag naar hetzelfde adres .
  role:
    text: 'Verantwoordelijke entiteit: Co-Legal B.V., Nederland.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We verkopen geen gegevens en gebruiken ze niet voor advertenties of om een model te trainen.
  subprocessors:
    source: https://co-legal.be/security
    text: 'Onderverwerkers Voor het Co·Legal partner-platform:'
    url: https://co-legal.be/security
  transfers:
  - mechanism: other
    text: Na de klik verwerkt Calendly (Verenigde Staten) de gegevens die u daar invult in onze opdracht, als verwerker; voor doorgifte buiten de EU gelden passende waarborgen.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Co-Legal
provenance_date: '2026-11-09'
provider_name: Co-Legal
provider_slug: co-legal-be
slug: co-legal-be-privacy-policy
source_date: '2026-11-09'
source_filename: co-legal-be-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://co-legal.be/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Co-Legal\naid: co-legal-be\nurl: https://co-legal.be/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://co-legal.be/legal\n  - https://co-legal.be/platform-privacy\n  - https://co-legal.be/security\nrole:\n  value: controller\n  text: 'Verantwoordelijke entiteit: Co-Legal B.V., Nederland.'\ndata_categories:\n- category: communication\n  text: Berichten die u zelf aan ons mailt, verwerken we om uw vraag te beantwoorden.\n- category: communication\n  text: Voor multi-turn bewaren we vraag, antwoord en technische taakmetadata in onze Europese operationele database.\n- category: device\n  text: volledig\
  \ IP-adres, user-agent, adres en tijdstip van het verzoek en de status\n- category: device\n  text: uw IP-adres ingekort tot een /24-netwerk (IPv4) of /48-netwerk (IPv6)\n- category: identifying\n  text: gebruikers (naam, werk-e-mailadres, rol), dossiergegevens, documenten, tijdsregistratie, facturen en de\n    bijbehorende boekhoudkundige gegevens\n  source: https://co-legal.be/platform-privacy\n- category: contact\n  text: 'Over cliënten en tegenpartijen van het kantoor: naam, adres, contactgegevens, ondernemingsnummer en de\n    inhoud van dossierstukken'\n  source: https://co-legal.be/platform-privacy\n- category: device\n  text: een auditlogboek van handelingen in de applicatie (wie deed wat, wanneer) en foutmeldingen voor het oplossen\n    van storingen\n  source: https://co-legal.be/platform-privacy\n- category: financial\n  text: de toegangstokens van die koppeling, de gekoppelde administratie, en de verwijzing tussen een cliënt in\n    het platform en de bijbehorende relatie in\
  \ de boekhouding\n  source: https://co-legal.be/platform-privacy\n- category: contact\n  text: Co·Legal verwerkt vertrouwelijke juridische, fiscale en financiële gegevens.\n  source: https://co-legal.be/security\n- category: communication\n  text: 'Een vrije-tekstprompt kan wel persoonsgegevens bevatten: voer daarom geen cliëntgeheimen of dossierinhoud\n    in.'\n  source: https://co-legal.be/security\npurposes:\n- purpose: technical operation and improvement of the website\n  text: Voor de technische werking en verbetering gebruiken we geaggregeerde tellingen uit Cloud Run-originverzoeklogs\n- purpose: reach, content and security of the site\n  text: Doel is bereik, inhoud en technische werking van de site verbeteren en misbruik beveiligen\n- purpose: produce the requested answer (MCP)\n  text: 'Doel: het gevraagde antwoord maken.'\n- purpose: rate limiting\n  text: 'Doel: misbruik en overbelasting van de bronnen voorkomen.'\n- purpose: operate platform for the office\n  text: 'Alleen\
  \ om het platform te laten werken voor dat kantoor: dossiers beheren, documenten opstellen, uren registreren,\n    factureren, en die facturen doorboeken naar de boekhouding van het kantoor.'\n  source: https://co-legal.be/platform-privacy\n- purpose: no advertising or resale\n  text: De gegevens worden niet gebruikt voor reclame, niet doorverkocht en niet gedeeld met andere kantoren.\n  source: https://co-legal.be/platform-privacy\n- purpose: Hosting, opslag en modelverwerking van dossiers\n  text: Hosting, opslag en modelverwerking van de dossier-, website- én publieke agent draaien binnen de EU.\n  source: https://co-legal.be/security\nretention:\n- scope: A2A conversation history\n  period: 7 dagen\n  text: Een gesprek dat 7 dagen niet gebruikt is, wordt verwijderd\n- scope: A2A message text\n  period: 7 dagen\n  text: de tekst van een bericht uiterlijk 7 dagen na ontvangst\n- scope: A2A operational logs\n  period: maximaal 90 dagen\n  text: de bewaartermijn is maximaal 90 dagen\n\
  - scope: MCP operational logs\n  period: maximaal 90 dagen\n  text: 'Bewaartermijn: maximaal 90 dagen'\n- scope: rate limit counter\n  period: null\n  text: Die staat alleen in het werkgeheugen, wordt niet weggeschreven\n- scope: website chat session storage\n  period: null\n  text: De browser bewaart maximaal 24 recente gespreksberichten in de sessieopslag van uw tab\n- scope: platform data while office uses service\n  period: null\n  text: Gegevens blijven staan zolang het kantoor het platform gebruikt; het kantoor bepaalt zelf wat het bewaart\n    en wat het verwijdert.\n  source: https://co-legal.be/platform-privacy\n- scope: integration access tokens\n  period: null\n  text: Toegangstokens van een koppeling worden verwijderd zodra het kantoor die koppeling verbreekt.\n  source: https://co-legal.be/platform-privacy\n- scope: Dossierdata\n  period: null\n  text: Dossierdata blijft staan gedurende de samenwerking en volgens de gedocumenteerde bewaarinstructie van het\n    kantoor.\n\
  \  source: https://co-legal.be/security\n- scope: Backend-logs\n  period: 90 dagen\n  text: 'Backend-logs (HTTP-toegang, request-correlatie, security-events): 90 dagen, daarna automatische verwijdering.'\n  source: https://co-legal.be/security\n- scope: Publieke agent-vragen\n  period: 7 dagen\n  text: verwijderd zodra een gesprek 7 dagen niet gebruikt is\n  source: https://co-legal.be/security\nresidency:\n- region: EU\n  text: via Google Cloud Vertex AI's EU-multiregio\n- region: Netherlands\n  text: Google Cloud host de server (Cloud Run, regio europe-west4\n- region: European Union\n  text: De gegevens staan bij Google Cloud Platform in de Europese Unie (regio europe-west).\n  source: https://co-legal.be/platform-privacy\n- region: European Union\n  text: Hosting, opslag en modelverwerking van de dossier-, website- én publieke agent draaien binnen de EU.\n  source: https://co-legal.be/security\ntransfers:\n- mechanism: other\n  text: Na de klik verwerkt Calendly (Verenigde Staten)\
  \ de gegevens die u daar invult in onze opdracht, als verwerker;\n    voor doorgifte buiten de EU gelden passende waarborgen.\nsubprocessors:\n  url: https://co-legal.be/security\n  text: 'Onderverwerkers Voor het Co·Legal partner-platform:'\n  source: https://co-legal.be/security\ndpa:\n  available: true\n  url: null\n  text: dat legt de verwerkersovereenkomst tussen ons vast\ndeletion:\n  route: email to privacy contact\n  text: Een verzoek stuurt u naar [email protected]\nrights:\n- right: access, rectification, erasure, restriction, portability and objection\n  text: de rechten op inzage, rectificatie, verwijdering, beperking van verwerking, dataportabiliteit en bezwaar\n- right: complaint\n  text: Dan kunt u een klacht indienen bij de Autoriteit Persoonsgegevens (Nederland) of de Gegevensbeschermingsautoriteit\n    (België)\n- right: access, correction, deletion\n  text: Verzoeken over persoonsgegevens (inzage, correctie, verwijdering) lopen via het kantoor, dat verwerkingsverantwoordelijke\n\
  \    is.\n  source: https://co-legal.be/platform-privacy\n- right: GDPR rights (access, rectification, erasure, portability)\n  text: Heeft u een GDPR-recht (inzage, rectificatie, verwijdering, dataportabiliteit) dat u wil uitoefenen — stuur\n    de aanvraag naar hetzelfde adres .\n  source: https://co-legal.be/security\nsale_or_sharing:\n  stance: prohibited\n  text: We verkopen geen gegevens en gebruiken ze niet voor advertenties of om een model te trainen.\n"
source_yaml_url: https://artifacts.apis.io/co-legal-be/privacy/co-legal-be-privacy-policy.yml
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
- sale_or_sharing
summary_line: 42 quoted statements, read from Co-Legal's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Legal Research
- Tax
- Case Law
- Legislation
- Company Registry
- VAT Validation
- Belgium
- Netherlands
- European Union
- A2A
- MCP
- Agent-Native
- Artificial Intelligence
- Legal Tech
---
