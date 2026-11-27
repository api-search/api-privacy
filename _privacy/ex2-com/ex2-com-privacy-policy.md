---
api_specs:
- filename: ex2-com-compare-api-openapi.yml
  format: yaml
  label: ex2-com Compare API
  slug: ex2-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-compare-api-openapi.yml
- filename: ex2-com-domains-api-openapi.yml
  format: yaml
  label: ex2-com Domains API
  slug: ex2-com-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-domains-api-openapi.yml
- filename: ex2-com-ex2-catalogue-api-api-openapi.yml
  format: yaml
  label: ex2-com Ex2 Catalogue API
  slug: ex2-com-ex2-catalogue-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-ex2-catalogue-api-api-openapi.yml
- filename: ex2-com-migration-api-openapi.yml
  format: yaml
  label: ex2-com Migration API
  slug: ex2-com-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-migration-api-openapi.yml
- filename: ex2-com-plans-api-openapi.yml
  format: yaml
  label: ex2-com Plans API
  slug: ex2-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-plans-api-openapi.yml
- filename: ex2-com-status-api-openapi.yml
  format: yaml
  label: ex2-com Status API
  slug: ex2-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ex2-com/openapi/ex2-com-status-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: votre nom, adresse postale, courriel, numéro de téléphone, données de paiement, informations de facturation, adresse IP et interactions avec notre site Web.
  - category: device
    text: Nos serveurs consignent automatiquement certaines données techniques, notamment l’adresse IP, le type de navigateur, le système d’exploitation, l’URL de provenance, les pages consultées et la durée des visites.
  deletion:
    route: service cancellation
    text: En cas d’annulation de service, les données sont supprimées ou anonymisées dans un délai raisonnable, sauf obligation légale contraire.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: (a) création et gestion de votre compte d’hébergement
  - purpose: transactions and payments
    text: (b) traitement des transactions et paiements
  - purpose: technical support
    text: (c) fourniture du soutien technique
  - purpose: service site performance improvement
    text: (e) amélioration de la convivialité et des performances du site
  residency:
  - region: Canada and France
    text: Les principaux centres de données d’Ex2 sont situés au Canada et en France.
  retention:
  - period: pendant la durée nécessaire à la fourniture des services
    scope: general
    text: Ex2 conserve les renseignements personnels uniquement pendant la durée nécessaire à la fourniture des services et au respect de ses obligations légales ou comptables.
  - period: null
    scope: backups
    text: Les données incluses dans les sauvegardes sont automatiquement supprimées selon notre calendrier de rétention.
  - period: dans un délai raisonnable
    scope: after service cancellation
    text: En cas d’annulation de service, les données sont supprimées ou anonymisées dans un délai raisonnable, sauf obligation légale contraire.
  rights:
  - right: access, rectification, erasure, portability and others
    text: accès, rectification, mise à jour, suppression, retrait du consentement, portabilité des données et opposition à certaines formes de traitement.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nous ne vendons ni ne louons vos renseignements personnels.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Ex2 applique des garanties appropriées, telles que les Clauses contractuelles types de l’Union européenne
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ex2-com
provenance_date: '2026-11-09'
provider_name: ex2-com
provider_slug: ex2-com
slug: ex2-com-privacy-policy
source_date: '2026-11-09'
source_filename: ex2-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ex2.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ex2-com\naid: ex2-com\nurl: https://www.ex2.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: votre nom, adresse postale, courriel, numéro de téléphone, données de paiement, informations de facturation,\n    adresse IP et interactions avec notre site Web.\n- category: device\n  text: Nos serveurs consignent automatiquement certaines données techniques, notamment l’adresse IP, le type de\n    navigateur, le système d’exploitation, l’URL de provenance, les pages consultées et la durée des visites.\npurposes:\n- purpose: account\
  \ management\n  text: (a) création et gestion de votre compte d’hébergement\n- purpose: transactions and payments\n  text: (b) traitement des transactions et paiements\n- purpose: technical support\n  text: (c) fourniture du soutien technique\n- purpose: service site performance improvement\n  text: (e) amélioration de la convivialité et des performances du site\nretention:\n- scope: general\n  period: pendant la durée nécessaire à la fourniture des services\n  text: Ex2 conserve les renseignements personnels uniquement pendant la durée nécessaire à la fourniture des services\n    et au respect de ses obligations légales ou comptables.\n- scope: backups\n  period: null\n  text: Les données incluses dans les sauvegardes sont automatiquement supprimées selon notre calendrier de rétention.\n- scope: after service cancellation\n  period: dans un délai raisonnable\n  text: En cas d’annulation de service, les données sont supprimées ou anonymisées dans un délai raisonnable, sauf\n    obligation\
  \ légale contraire.\nresidency:\n- region: Canada and France\n  text: Les principaux centres de données d’Ex2 sont situés au Canada et en France.\ntransfers:\n- mechanism: SCC\n  text: Ex2 applique des garanties appropriées, telles que les Clauses contractuelles types de l’Union européenne\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: service cancellation\n  text: En cas d’annulation de service, les données sont supprimées ou anonymisées dans un délai raisonnable, sauf\n    obligation légale contraire.\nrights:\n- right: access, rectification, erasure, portability and others\n  text: accès, rectification, mise à jour, suppression, retrait du consentement, portabilité des données et opposition\n    à certaines formes de traitement.\nsale_or_sharing:\n  stance: prohibited\n  text: Nous ne vendons ni ne louons vos renseignements personnels.\n"
source_yaml_url: https://artifacts.apis.io/ex2-com/privacy/ex2-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from ex2-com's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- Sustainability
- Web Hosting
- Quebec
- GreenTech
---
