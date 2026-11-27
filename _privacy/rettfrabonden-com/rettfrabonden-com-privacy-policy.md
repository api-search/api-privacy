---
api_specs:
- filename: rettfrabonden-com-a2a-api-openapi.yml
  format: yaml
  label: Rett fra Bonden A2a API
  slug: rettfrabonden-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-a2a-api-openapi.yml
- filename: rettfrabonden-com-marketplace-api-openapi.yml
  format: yaml
  label: Rett fra Bonden Marketplace API
  slug: rettfrabonden-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-marketplace-api-openapi.yml
- filename: rettfrabonden-com-mcp-api-openapi.yml
  format: yaml
  label: Rett fra Bonden MCP API
  slug: rettfrabonden-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-mcp-api-openapi.yml
- filename: rettfrabonden-com-stats-api-openapi.yml
  format: yaml
  label: Rett fra Bonden Stats API
  slug: rettfrabonden-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-stats-api-openapi.yml
- filename: rettfrabonden-com-well-known-api-openapi.yml
  format: yaml
  label: Rett fra Bonden .well Known API
  slug: rettfrabonden-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rettfrabonden-com/openapi/rettfrabonden-com-well-known-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: En pseudonymisert, saltet hash av IP-adressen din (SHA-256, forkortet — vi lagrer ikke fullstendig IP-adresse)
  - category: behavioral
    text: Hvilken side du besøker (URL-sti)
  - category: behavioral
    text: Søketeksten du skrev
  - category: contact
    text: Navn, e-postadresse og eventuelt telefonnummer
  - category: communication
    text: E-postene vi har sendt deg og svarene dine (e-postadresse, navn og innhold) lagres i kundeservicesystemet vårt og i en utsendingslogg.
  deletion:
    route: kontakt@rettfrabonden.com, or reply «fjern» to an email from us
    text: Slette data — kontakt oss, eller svar «fjern» på en e-post fra oss, for å få fjernet profilen.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Forbedre tjenesten
    text: Vi lagrer dette for å forstå hvilke søk som gir gode resultater, og for å forbedre tjenesten.
  - purpose: Vise produsentprofiler
    text: Å gi forbrukere og KI-assistenter en oppdatert oversikt over lokale matprodusenter.
  - purpose: Formidle bestilling
    text: For å formidle bestillingen til produsenten du bestiller fra.
  residency:
  - region: Stockholm-regionen (ARN)
    text: Databasen ligger på en server hos Fly.io i Stockholm-regionen (ARN).
  retention:
  - period: 60 dager
    scope: Sidebesøk-analytikk
    text: Enkeltbesøk (med pseudonymisert IP-hash) slettes automatisk etter 60 dager.
  - period: 60 dager
    scope: Søkelogger
    text: Enkeltsøk (med pseudonymisert IP-hash) slettes automatisk etter 60 dager.
  - period: 60 dager
    scope: MCP/A2A-verktøykall-logg
    text: Slettes automatisk etter 60 dager, i samme daglige kjøring som sidebesøk og søk.
  - period: 30 dager
    scope: Kjøperkontaktinfo
    text: Slettes automatisk 30 dager etter bestillingen er endelig avgjort (levert/avvist/kansellert)
  - period: Slettes ikke automatisk i dag
    scope: Kontakt-klikk
    text: Slettes ikke automatisk i dag.
  - period: 7 dager
    scope: Sikkerhetskopier
    text: Daglige kopier hos Tigris beholdes i 7 dager
  rights:
  - right: Innsyn
    text: Be om innsyn — vi kan fortelle deg hva vi har lagret om deg
  - right: Rettelse
    text: Rette feil — selgere kan oppdatere profilen sin direkte via dashboardet, og alle andre kan kontakte oss
  - right: Innsigelse
    text: Protestere — du kan når som helst protestere mot at vi viser en profil om deg eller virksomheten din, eller mot at vi sender deg e-post om den.
  - right: Tilbakekalle samtykke
    text: Trekke tilbake samtykke — for opplysninger du selv har lagt inn eller samtykket til, kan du når som helst trekke samtykket tilbake
  - right: Klage
    text: Klage — du kan klage til Datatilsynet (datatilsynet.no) hvis du mener vi bryter reglene
  role:
    text: Behandlingsansvarlig for Rett fra Bonden er AGENTPLATFORM.NO AS (org.nr. 938 635 676), Haakon Tveters vei 66, 0686 Oslo.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Vi selger aldri data til tredjeparter
  subprocessors:
    text: Fly.io (drift av serveren)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rett fra Bonden
provenance_date: '2026-11-10'
provider_name: Rett fra Bonden
provider_slug: rettfrabonden-com
slug: rettfrabonden-com-privacy-policy
source_date: '2026-11-10'
source_filename: rettfrabonden-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rettfrabonden.com/personvern
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rett fra Bonden\naid: rettfrabonden-com\nurl: https://rettfrabonden.com/personvern\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Behandlingsansvarlig for Rett fra Bonden er AGENTPLATFORM.NO AS (org.nr. 938 635 676), Haakon Tveters vei\n    66, 0686 Oslo.\ndata_categories:\n- category: identifying\n  text: En pseudonymisert, saltet hash av IP-adressen din (SHA-256, forkortet — vi lagrer ikke fullstendig IP-adresse)\n- category: behavioral\n  text: Hvilken side du besøker (URL-sti)\n- category: behavioral\n  text: Søketeksten du skrev\n- category: contact\n  text: Navn, e-postadresse og eventuelt\
  \ telefonnummer\n- category: communication\n  text: E-postene vi har sendt deg og svarene dine (e-postadresse, navn og innhold) lagres i kundeservicesystemet\n    vårt og i en utsendingslogg.\npurposes:\n- purpose: Forbedre tjenesten\n  text: Vi lagrer dette for å forstå hvilke søk som gir gode resultater, og for å forbedre tjenesten.\n- purpose: Vise produsentprofiler\n  text: Å gi forbrukere og KI-assistenter en oppdatert oversikt over lokale matprodusenter.\n- purpose: Formidle bestilling\n  text: For å formidle bestillingen til produsenten du bestiller fra.\nretention:\n- scope: Sidebesøk-analytikk\n  period: 60 dager\n  text: Enkeltbesøk (med pseudonymisert IP-hash) slettes automatisk etter 60 dager.\n- scope: Søkelogger\n  period: 60 dager\n  text: Enkeltsøk (med pseudonymisert IP-hash) slettes automatisk etter 60 dager.\n- scope: MCP/A2A-verktøykall-logg\n  period: 60 dager\n  text: Slettes automatisk etter 60 dager, i samme daglige kjøring som sidebesøk og søk.\n- scope: Kjøperkontaktinfo\n\
  \  period: 30 dager\n  text: Slettes automatisk 30 dager etter bestillingen er endelig avgjort (levert/avvist/kansellert)\n- scope: Kontakt-klikk\n  period: Slettes ikke automatisk i dag\n  text: Slettes ikke automatisk i dag.\n- scope: Sikkerhetskopier\n  period: 7 dager\n  text: Daglige kopier hos Tigris beholdes i 7 dager\nresidency:\n- region: Stockholm-regionen (ARN)\n  text: Databasen ligger på en server hos Fly.io i Stockholm-regionen (ARN).\ntransfers: []\nsubprocessors:\n  url: null\n  text: Fly.io (drift av serveren)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: kontakt@rettfrabonden.com, or reply «fjern» to an email from us\n  text: Slette data — kontakt oss, eller svar «fjern» på en e-post fra oss, for å få fjernet profilen.\nrights:\n- right: Innsyn\n  text: Be om innsyn — vi kan fortelle deg hva vi har lagret om deg\n- right: Rettelse\n  text: Rette feil — selgere kan oppdatere profilen sin direkte via dashboardet, og alle andre kan kontakte oss\n\
  - right: Innsigelse\n  text: Protestere — du kan når som helst protestere mot at vi viser en profil om deg eller virksomheten din, eller\n    mot at vi sender deg e-post om den.\n- right: Tilbakekalle samtykke\n  text: Trekke tilbake samtykke — for opplysninger du selv har lagt inn eller samtykket til, kan du når som helst\n    trekke samtykket tilbake\n- right: Klage\n  text: Klage — du kan klage til Datatilsynet (datatilsynet.no) hvis du mener vi bryter reglene\nsale_or_sharing:\n  stance: prohibited\n  text: Vi selger aldri data til tredjeparter\n"
source_yaml_url: https://artifacts.apis.io/rettfrabonden-com/privacy/rettfrabonden-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Rett fra Bonden's own page on 2026-11-10.
synthetic: false
tags:
- Local Food
- Agriculture
- Food
- Marketplace
- Directory
- Search
- Geolocation
- A2A
- MCP
- Norway
- Open Source
- Company
---
