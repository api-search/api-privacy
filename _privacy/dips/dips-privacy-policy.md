---
api_specs:
- filename: dips-account-api-openapi.yml
  format: yaml
  label: DIPS Account API
  slug: dips-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-account-api-openapi.yml
- filename: dips-connect-api-openapi.yml
  format: yaml
  label: DIPS Connect API
  slug: dips-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-connect-api-openapi.yml
- filename: dips-consent-api-openapi.yml
  format: yaml
  label: DIPS Consent API
  slug: dips-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-consent-api-openapi.yml
- filename: dips-default-api-openapi.yml
  format: yaml
  label: DIPS * API
  slug: dips-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-default-api-openapi.yml
- filename: dips-home-api-openapi.yml
  format: yaml
  label: DIPS Home API
  slug: dips-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-home-api-openapi.yml
- filename: dips-login-api-openapi.yml
  format: yaml
  label: DIPS Login API
  slug: dips-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-login-api-openapi.yml
- filename: dips-status-api-openapi.yml
  format: yaml
  label: DIPS Status API
  slug: dips-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-status-api-openapi.yml
- filename: dips-well-known-api-openapi.yml
  format: yaml
  label: DIPS .well Known API
  slug: dips-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-well-known-api-openapi.yml
- filename: dips-user-role-api-openapi.yml
  format: yaml
  label: DIPS User Role API
  slug: dips-user-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dips/openapi/dips-user-role-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: behavioral
    text: DIPS samler inn opplysninger om besøkende på dips.com.
  - category: contact
    text: i denne løsningen kan du melde deg på kurs ved å oppgi navn, kontaktinformasjon og arbeidsgiver.
  - category: identifying
    text: For at vi skal kunne sende e-post må du registrere en e-postadresse.
  deletion:
    route: Request to DIPS / unsubscribe
    text: Opplysningene slettes på forespørsel, og e-postadressen slettes fra registeret.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website statistics and improvement
    text: Formålet med dette er å utarbeide statistikk som vi bruker for å forbedre og videreutvikle informasjonstilbudet på nettstedet vårt.
  - purpose: Course administration
    text: Personopplysninger vi får inn ved påmelding til kurs blir ikke benyttet til andre formål enn å administrere kurset.
  retention:
  - period: 12 måneder
    scope: Course sign-up data
    text: Personopplysningene slettes fra våre systemer innen 12 måneder etter at kurset er avholdt.
  - period: ett og et halvt år
    scope: Course sign-up copy for statistics
    text: DIPS vil ha en kopi av påmeldingsopplysningene som oppbevares inntil ett og et halvt år av statistikkhensyn.
  role:
    text: TRY er databehandler og driftsleverandør for dips.com.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: Dips videreselger under ingen omstendigheter informasjon og/eller e-postadresser samlet inn via dips.com.
  subprocessors:
    text: HubSpot og Mailchimp er databehandler for våre nyhetsbrev.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DIPS
provenance_date: '2026-11-09'
provider_name: DIPS
provider_slug: dips
slug: dips-privacy-policy
source_date: '2026-11-09'
source_filename: dips-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.dips.com/personvern
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DIPS\naid: dips\nurl: https://www.dips.com/personvern\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: TRY er databehandler og driftsleverandør for dips.com.\ndata_categories:\n- category: behavioral\n  text: DIPS samler inn opplysninger om besøkende på dips.com.\n- category: contact\n  text: i denne løsningen kan du melde deg på kurs ved å oppgi navn, kontaktinformasjon og arbeidsgiver.\n- category: identifying\n  text: For at vi skal kunne sende e-post må du registrere en e-postadresse.\npurposes:\n- purpose: Website statistics and improvement\n  text: Formålet med dette er å utarbeide statistikk\
  \ som vi bruker for å forbedre og videreutvikle informasjonstilbudet\n    på nettstedet vårt.\n- purpose: Course administration\n  text: Personopplysninger vi får inn ved påmelding til kurs blir ikke benyttet til andre formål enn å administrere\n    kurset.\nretention:\n- scope: Course sign-up data\n  period: 12 måneder\n  text: Personopplysningene slettes fra våre systemer innen 12 måneder etter at kurset er avholdt.\n- scope: Course sign-up copy for statistics\n  period: ett og et halvt år\n  text: DIPS vil ha en kopi av påmeldingsopplysningene som oppbevares inntil ett og et halvt år av statistikkhensyn.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: HubSpot og Mailchimp er databehandler for våre nyhetsbrev.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to DIPS / unsubscribe\n  text: Opplysningene slettes på forespørsel, og e-postadressen slettes fra registeret.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Dips\
  \ videreselger under ingen omstendigheter informasjon og/eller e-postadresser samlet inn via dips.com.\n"
source_yaml_url: https://artifacts.apis.io/dips/privacy/dips-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from DIPS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Electronic Health Records
- Health IT
- FHIR
- openEHR
- Interoperability
- Identity
- OpenID Connect
- Norway
- Hospitals
- SMART on FHIR
---
