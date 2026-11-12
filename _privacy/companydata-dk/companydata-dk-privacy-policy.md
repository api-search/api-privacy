---
api_specs:
- filename: companydata-dk-account-api-openapi.yml
  format: yaml
  label: companydata.dk Account API
  slug: companydata-dk-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-account-api-openapi.yml
- filename: companydata-dk-auditors-api-openapi.yml
  format: yaml
  label: companydata.dk Auditors API
  slug: companydata-dk-auditors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-auditors-api-openapi.yml
- filename: companydata-dk-companies-api-openapi.yml
  format: yaml
  label: companydata.dk Companies API
  slug: companydata-dk-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-companies-api-openapi.yml
- filename: companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
  format: yaml
  label: companydata.dk cvrapi.dk compatibility API
  slug: companydata-dk-cvrapi-dk-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
- filename: companydata-dk-e-invoicing-api-openapi.yml
  format: yaml
  label: companydata.dk E Invoicing API
  slug: companydata-dk-e-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-e-invoicing-api-openapi.yml
- filename: companydata-dk-legal-notices-api-openapi.yml
  format: yaml
  label: companydata.dk Legal notices API
  slug: companydata-dk-legal-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-legal-notices-api-openapi.yml
- filename: companydata-dk-participants-api-openapi.yml
  format: yaml
  label: companydata.dk Participants API
  slug: companydata-dk-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-participants-api-openapi.yml
- filename: companydata-dk-production-units-api-openapi.yml
  format: yaml
  label: companydata.dk Production Units API
  slug: companydata-dk-production-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-production-units-api-openapi.yml
- filename: companydata-dk-properties-api-openapi.yml
  format: yaml
  label: companydata.dk Properties API
  slug: companydata-dk-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-properties-api-openapi.yml
- filename: companydata-dk-reference-data-api-openapi.yml
  format: yaml
  label: companydata.dk Reference Data API
  slug: companydata-dk-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-reference-data-api-openapi.yml
- filename: companydata-dk-screening-api-openapi.yml
  format: yaml
  label: companydata.dk Screening API
  slug: companydata-dk-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-screening-api-openapi.yml
- filename: companydata-dk-webhooks-api-openapi.yml
  format: yaml
  label: companydata.dk Webhooks API
  slug: companydata-dk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-webhooks-api-openapi.yml
- filename: companydata-dk-working-lists-api-openapi.yml
  format: yaml
  label: companydata.dk Working Lists API
  slug: companydata-dk-working-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-working-lists-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, navn og adgangskode ved oprettelse af konto
  - category: financial
    text: 'Betalingsoplysninger: Håndteres af Stripe - vi gemmer ikke betalingskortoplysninger'
  - category: behavioral
    text: 'Brugsdata: Hvilke funktioner du bruger, søgehistorik og API-kald'
  - category: device
    text: 'Tekniske data: IP-adresse, browsertype og enhedsoplysninger'
  deletion:
    route: delete account
    text: Hvis du sletter din konto, anonymiserer eller sletter vi dine personoplysninger inden for 30 dage.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Levere og forbedre tjenesten
    text: Levere og forbedre vores tjeneste
  - purpose: Behandle betalinger
    text: Behandle betalinger og administrere dit abonnement
  - purpose: Analyse
    text: Analysere og forbedre tjenestens ydeevne
  retention:
  - period: null
    scope: active account
    text: Vi opbevarer dine data så længe du har en aktiv konto.
  - period: 30 dage
    scope: after account deletion
    text: Hvis du sletter din konto, anonymiserer eller sletter vi dine personoplysninger inden for 30 dage.
  rights:
  - right: access
    text: Ret til indsigt i dine personoplysninger
  - right: portability
    text: Ret til dataportabilitet
  - right: objection
    text: Ret til at gøre indsigelse mod behandling
  role:
    text: Vi er dataansvarlig for behandlingen af dine personoplysninger
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Vi sælger aldrig dine personoplysninger til tredjeparter.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: companydata.dk
provenance_date: '2026-11-09'
provider_name: companydata.dk
provider_slug: companydata-dk
slug: companydata-dk-privacy-policy
source_date: '2026-11-09'
source_filename: companydata-dk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://companydata.dk/da/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: companydata.dk\naid: companydata-dk\nurl: https://companydata.dk/da/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Vi er dataansvarlig for behandlingen af dine personoplysninger\ndata_categories:\n- category: identifying\n  text: Email, navn og adgangskode ved oprettelse af konto\n- category: financial\n  text: 'Betalingsoplysninger: Håndteres af Stripe - vi gemmer ikke betalingskortoplysninger'\n- category: behavioral\n  text: 'Brugsdata: Hvilke funktioner du bruger, søgehistorik og API-kald'\n- category: device\n  text: 'Tekniske data: IP-adresse, browsertype og enhedsoplysninger'\n\
  purposes:\n- purpose: Levere og forbedre tjenesten\n  text: Levere og forbedre vores tjeneste\n- purpose: Behandle betalinger\n  text: Behandle betalinger og administrere dit abonnement\n- purpose: Analyse\n  text: Analysere og forbedre tjenestens ydeevne\nretention:\n- scope: active account\n  period: null\n  text: Vi opbevarer dine data så længe du har en aktiv konto.\n- scope: after account deletion\n  period: 30 dage\n  text: Hvis du sletter din konto, anonymiserer eller sletter vi dine personoplysninger inden for 30 dage.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account\n  text: Hvis du sletter din konto, anonymiserer eller sletter vi dine personoplysninger inden for 30 dage.\nrights:\n- right: access\n  text: Ret til indsigt i dine personoplysninger\n- right: portability\n  text: Ret til dataportabilitet\n- right: objection\n  text: Ret til at gøre indsigelse mod behandling\n\
  sale_or_sharing:\n  stance: prohibited\n  text: Vi sælger aldrig dine personoplysninger til tredjeparter.\n"
source_yaml_url: https://artifacts.apis.io/companydata-dk/privacy/companydata-dk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from companydata.dk's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Business Registry
- CVR
- Denmark
- Credit Scoring
- Financial Statements
- Lead Generation
- MCP
- REST API
---
