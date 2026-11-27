---
api_specs:
- filename: tenderapi-fr-auth-api-openapi.yml
  format: yaml
  label: tenderapi-fr Auth API
  slug: tenderapi-fr-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-auth-api-openapi.yml
- filename: tenderapi-fr-awards-api-openapi.yml
  format: yaml
  label: tenderapi-fr Awards API
  slug: tenderapi-fr-awards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-awards-api-openapi.yml
- filename: tenderapi-fr-billing-api-openapi.yml
  format: yaml
  label: tenderapi-fr Billing API
  slug: tenderapi-fr-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-billing-api-openapi.yml
- filename: tenderapi-fr-health-api-openapi.yml
  format: yaml
  label: tenderapi-fr Health API
  slug: tenderapi-fr-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-health-api-openapi.yml
- filename: tenderapi-fr-keys-api-openapi.yml
  format: yaml
  label: tenderapi-fr Keys API
  slug: tenderapi-fr-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-keys-api-openapi.yml
- filename: tenderapi-fr-profiles-api-openapi.yml
  format: yaml
  label: tenderapi-fr Profiles API
  slug: tenderapi-fr-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-profiles-api-openapi.yml
- filename: tenderapi-fr-renewals-api-openapi.yml
  format: yaml
  label: tenderapi-fr Renewals API
  slug: tenderapi-fr-renewals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-renewals-api-openapi.yml
- filename: tenderapi-fr-tenders-api-openapi.yml
  format: yaml
  label: tenderapi-fr Tenders API
  slug: tenderapi-fr-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-fr/openapi/tenderapi-fr-tenders-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Adresse email : identifiant unique pour votre clé API et vos communications transactionnelles'
  - category: device
    text: 'Adresse IP : utilisée temporairement (24h en mémoire) pour limiter les créations de clés abusives, non persistée en base de données'
  - category: financial
    text: 'Données de facturation : gérées exclusivement par Stripe. TenderAPI ne stocke aucune donnée de carte bancaire'
  - category: behavioral
    text: 'Logs d''usage API : compteurs de requêtes (non nominatifs) pour l''application des limites par tier'
  deletion:
    route: Email à contact@tenderapi.fr
    text: 'Pour exercer vos droits ou demander la suppression de votre compte : contact@tenderapi.fr'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fourniture du service API
    text: 'Fourniture du service API (base légale : exécution du contrat)'
  - purpose: Prévention des abus
    text: 'Prévention des abus (base légale : intérêt légitime)'
  - purpose: Facturation et abonnements via Stripe
    text: 'Facturation et gestion des abonnements via Stripe (base légale : exécution du contrat)'
  - purpose: Communications transactionnelles
    text: 'Communications transactionnelles liées à votre compte (base légale : exécution du contrat)'
  residency:
  - region: France
    text: Données stockées en France.
  retention:
  - period: tant que le compte est actif
    scope: Email et clé API
    text: 'Email + clé API : conservés tant que le compte est actif, puis supprimés sur demande'
  - period: 10 ans
    scope: Données de facturation
    text: 'Données de facturation : conservées 10 ans (obligation légale comptable)'
  - period: null
    scope: Logs d'usage
    text: 'Logs d''usage : compteurs remis à zéro quotidiennement / mensuellement'
  rights:
  - right: Accès
    text: 'Accès : obtenir une copie de vos données'
  - right: Rectification
    text: 'Rectification : corriger une donnée inexacte'
  - right: Effacement
    text: 'Effacement : demander la suppression de votre compte et de vos données'
  - right: Portabilité
    text: 'Portabilité : recevoir vos données dans un format structuré'
  - right: Opposition
    text: 'Opposition : vous opposer à un traitement fondé sur l''intérêt légitime'
  - right: Limitation
    text: 'Limitation : demander la suspension temporaire d''un traitement'
  role:
    text: TenderAPI est édité à titre individuel.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfert encadré par les clauses contractuelles types UE.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tenderapi-fr
provenance_date: '2026-11-10'
provider_name: tenderapi-fr
provider_slug: tenderapi-fr
slug: tenderapi-fr-privacy-policy
source_date: '2026-11-10'
source_filename: tenderapi-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tenderapi.fr/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tenderapi-fr\naid: tenderapi-fr\nurl: https://tenderapi.fr/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TenderAPI est édité à titre individuel.\ndata_categories:\n- category: contact\n  text: 'Adresse email : identifiant unique pour votre clé API et vos communications transactionnelles'\n- category: device\n  text: 'Adresse IP : utilisée temporairement (24h en mémoire) pour limiter les créations de clés abusives, non\n    persistée en base de données'\n- category: financial\n  text: 'Données de facturation : gérées exclusivement par Stripe. TenderAPI ne stocke aucune donnée de carte\
  \ bancaire'\n- category: behavioral\n  text: 'Logs d''usage API : compteurs de requêtes (non nominatifs) pour l''application des limites par tier'\npurposes:\n- purpose: Fourniture du service API\n  text: 'Fourniture du service API (base légale : exécution du contrat)'\n- purpose: Prévention des abus\n  text: 'Prévention des abus (base légale : intérêt légitime)'\n- purpose: Facturation et abonnements via Stripe\n  text: 'Facturation et gestion des abonnements via Stripe (base légale : exécution du contrat)'\n- purpose: Communications transactionnelles\n  text: 'Communications transactionnelles liées à votre compte (base légale : exécution du contrat)'\nretention:\n- scope: Email et clé API\n  period: tant que le compte est actif\n  text: 'Email + clé API : conservés tant que le compte est actif, puis supprimés sur demande'\n- scope: Données de facturation\n  period: 10 ans\n  text: 'Données de facturation : conservées 10 ans (obligation légale comptable)'\n- scope: Logs d'usage\n  period:\
  \ null\n  text: 'Logs d''usage : compteurs remis à zéro quotidiennement / mensuellement'\nresidency:\n- region: France\n  text: Données stockées en France.\ntransfers:\n- mechanism: SCC\n  text: Transfert encadré par les clauses contractuelles types UE.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email à contact@tenderapi.fr\n  text: 'Pour exercer vos droits ou demander la suppression de votre compte : contact@tenderapi.fr'\nrights:\n- right: Accès\n  text: 'Accès : obtenir une copie de vos données'\n- right: Rectification\n  text: 'Rectification : corriger une donnée inexacte'\n- right: Effacement\n  text: 'Effacement : demander la suppression de votre compte et de vos données'\n- right: Portabilité\n  text: 'Portabilité : recevoir vos données dans un format structuré'\n- right: Opposition\n  text: 'Opposition : vous opposer à un traitement fondé sur l''intérêt légitime'\n- right: Limitation\n  text: 'Limitation :\
  \ demander la suspension temporaire d''un traitement'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tenderapi-fr/privacy/tenderapi-fr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from tenderapi-fr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Public Data
- France
- Europe
---
