---
api_specs:
- filename: opplevagent-no-a2a-api-openapi.yml
  format: yaml
  label: Opplevagent A2a API
  slug: opplevagent-no-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-a2a-api-openapi.yml
- filename: opplevagent-no-llms-txt-api-openapi.yml
  format: yaml
  label: Opplevagent Llms.txt API
  slug: opplevagent-no-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-llms-txt-api-openapi.yml
- filename: opplevagent-no-opplevelser-api-openapi.yml
  format: yaml
  label: Opplevagent Opplevelser API
  slug: opplevagent-no-opplevelser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-opplevelser-api-openapi.yml
- filename: opplevagent-no-well-known-api-openapi.yml
  format: yaml
  label: Opplevagent .well Known API
  slug: opplevagent-no-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opplevagent-no/openapi/opplevagent-no-well-known-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Provider profiles: for each provider we store the name, organisation number, address, phone, email address and website'
  - category: communication
    text: We store a send log (the recipient's email address, time and message ID) and the correspondence itself
  - category: device
    text: the AI client's browser/client string and a salted, truncated hash of the IP address
  - category: behavioral
    text: for each page visit the server records, without cookies, which page was shown, where you came from (referrer URL), the time
  deletion:
    route: Email request to kontakt@opplevagent.no; manual deletion
    text: sletting gjør vi manuelt; det finnes ingen automatisk eller selvbetjent sletting.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing visibility in a free catalogue
    text: giving providers visibility in a free catalogue that AI assistants can fetch from
  - purpose: Forwarding and following up visit requests
    text: Formålet er kun å formidle og følge opp forespørselen; opplysningene brukes ikke til markedsføring.
  - purpose: Understanding service use and improving it
    text: 'Legitimate interest: understanding how the service is used and improving it'
  residency:
  - region: Stockholm region (ARN), Sweden
    text: Databasen ligger på en server hos Fly.io i Stockholm-regionen (ARN).
  retention:
  - period: null
    scope: Visit and search statistics and technical MCP/A2A log
    text: Slettes automatisk etter 60 dager.
  - period: null
    scope: Visit requests
    text: Navn, e-post, telefon og kommentar slettes automatisk 30 dager etter at forespørselen er avgjort
  - period: null
    scope: Database backups
    text: Daglige kopier hos Tigris beholdes i 7 dager, og én kopi per uke i 4 uker til.
  - period: null
    scope: Email correspondence and send log
    text: Ingen automatisk sletting i dag. Vi sletter manuelt på forespørsel.
  rights:
  - right: Access
    text: Be om innsyn — vi kan fortelle deg hva vi har lagret om deg.
  - right: Rectify
    text: Rette feil — er du tilbyder og vil korrigere informasjon, send e-post til kontakt@opplevagent.no .
  - right: Delete
    text: Slette data — be om sletting på kontakt@opplevagent.no .
  - right: Object
    text: Protestere — du kan når som helst protestere mot at vi viser en profil om deg eller virksomheten din
  - right: Complain
    text: Klage — du kan klage til Datatilsynet (datatilsynet.no).
  role:
    text: Behandlingsansvarlig for Opplevagent er AGENTPLATFORM.NO AS (org.nr. 938 635 676)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 'Opplysninger kan også behandles utenfor EU/EØS: sikkerhetskopier hos Tigris (USA), KI-kontroll, oversettelse og e-posthåndtering hos Anthropic (USA)'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Opplevagent
provenance_date: '2026-11-10'
provider_name: Opplevagent
provider_slug: opplevagent-no
slug: opplevagent-no-privacy-policy
source_date: '2026-11-10'
source_filename: opplevagent-no-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://opplevagent.no/personvern
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Opplevagent\naid: opplevagent-no\nurl: https://opplevagent.no/personvern\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Behandlingsansvarlig for Opplevagent er AGENTPLATFORM.NO AS (org.nr. 938 635 676)\ndata_categories:\n- category: identifying\n  text: 'Provider profiles: for each provider we store the name, organisation number, address, phone, email address\n    and website'\n- category: communication\n  text: We store a send log (the recipient's email address, time and message ID) and the correspondence itself\n- category: device\n  text: the AI client's browser/client string and a salted,\
  \ truncated hash of the IP address\n- category: behavioral\n  text: for each page visit the server records, without cookies, which page was shown, where you came from (referrer\n    URL), the time\npurposes:\n- purpose: Providing visibility in a free catalogue\n  text: giving providers visibility in a free catalogue that AI assistants can fetch from\n- purpose: Forwarding and following up visit requests\n  text: Formålet er kun å formidle og følge opp forespørselen; opplysningene brukes ikke til markedsføring.\n- purpose: Understanding service use and improving it\n  text: 'Legitimate interest: understanding how the service is used and improving it'\nretention:\n- scope: Visit and search statistics and technical MCP/A2A log\n  period: null\n  text: Slettes automatisk etter 60 dager.\n- scope: Visit requests\n  period: null\n  text: Navn, e-post, telefon og kommentar slettes automatisk 30 dager etter at forespørselen er avgjort\n- scope: Database backups\n  period: null\n  text: Daglige\
  \ kopier hos Tigris beholdes i 7 dager, og én kopi per uke i 4 uker til.\n- scope: Email correspondence and send log\n  period: null\n  text: Ingen automatisk sletting i dag. Vi sletter manuelt på forespørsel.\nresidency:\n- region: Stockholm region (ARN), Sweden\n  text: Databasen ligger på en server hos Fly.io i Stockholm-regionen (ARN).\ntransfers:\n- mechanism: other\n  text: 'Opplysninger kan også behandles utenfor EU/EØS: sikkerhetskopier hos Tigris (USA), KI-kontroll, oversettelse\n    og e-posthåndtering hos Anthropic (USA)'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to kontakt@opplevagent.no; manual deletion\n  text: sletting gjør vi manuelt; det finnes ingen automatisk eller selvbetjent sletting.\nrights:\n- right: Access\n  text: Be om innsyn — vi kan fortelle deg hva vi har lagret om deg.\n- right: Rectify\n  text: Rette feil — er du tilbyder og vil korrigere informasjon, send e-post til\
  \ kontakt@opplevagent.no .\n- right: Delete\n  text: Slette data — be om sletting på kontakt@opplevagent.no .\n- right: Object\n  text: Protestere — du kan når som helst protestere mot at vi viser en profil om deg eller virksomheten din\n- right: Complain\n  text: Klage — du kan klage til Datatilsynet (datatilsynet.no).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/opplevagent-no/privacy/opplevagent-no-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Opplevagent's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Tourism
- Experience
- Activities
- Norway
- Marketplace
- Agent-Native
- A2A
- MCP
- Booking
- Local Food
- Open Data
---
