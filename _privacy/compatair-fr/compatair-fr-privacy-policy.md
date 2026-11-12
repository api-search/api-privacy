---
api_specs:
- filename: compatair-fr-changefeed-api-openapi.yml
  format: yaml
  label: CompatAir Changefeed API
  slug: compatair-fr-changefeed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatair-fr/openapi/compatair-fr-changefeed-api-openapi.yml
- filename: compatair-fr-compatibility-api-openapi.yml
  format: yaml
  label: CompatAir Compatibility API
  slug: compatair-fr-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatair-fr/openapi/compatair-fr-compatibility-api-openapi.yml
- filename: compatair-fr-evidence-api-openapi.yml
  format: yaml
  label: CompatAir Evidence API
  slug: compatair-fr-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatair-fr/openapi/compatair-fr-evidence-api-openapi.yml
- filename: compatair-fr-search-api-openapi.yml
  format: yaml
  label: CompatAir Search API
  slug: compatair-fr-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatair-fr/openapi/compatair-fr-search-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: device
    text: l’agent utilisateur
  - category: behavioral
    text: l’URL demandée
  - category: contact
    text: l’adresse de l’expéditeur, le contenu et les pièces jointes volontairement transmises
  - category: location
    text: l’adresse IP
  deletion:
    route: Effacer button in the journey bar for local data
    text: Les données locales peuvent être supprimées avec le bouton « Effacer » de la barre de parcours.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service security and diagnostics
    text: afin d’assurer la disponibilité, le diagnostic et la sécurité du service
  - purpose: handling contact requests
    text: Ces informations servent uniquement à traiter la demande ou le signalement.
  retention:
  - period: 91 jours
    scope: weekly anonymous counters
    text: Les compteurs hebdomadaires sont conservés pendant 91 jours sans cookie, identifiant persistant ni ligne d’événement.
  - period: trente jours
    scope: browser local journey memory
    text: le navigateur conserve aussi localement, pendant trente jours au maximum
  rights:
  - right: access, rectification, erasure, restriction, objection
    text: Vous pouvez demander l’accès, la rectification, l’effacement, la limitation ou l’opposition lorsque ces droits sont applicables.
  - right: complaint to CNIL
    text: Vous pouvez aussi saisir la CNIL
  role:
    text: Responsable du traitement
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Aucun fichier client n’est vendu.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CompatAir
provenance_date: '2026-11-09'
provider_name: CompatAir
provider_slug: compatair-fr
slug: compatair-fr-privacy-policy
source_date: '2026-11-09'
source_filename: compatair-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://compatair.fr/confidentialite/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CompatAir\naid: compatair-fr\nurl: https://compatair.fr/confidentialite/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Responsable du traitement\ndata_categories:\n- category: device\n  text: l’agent utilisateur\n- category: behavioral\n  text: l’URL demandée\n- category: contact\n  text: l’adresse de l’expéditeur, le contenu et les pièces jointes volontairement transmises\n- category: location\n  text: l’adresse IP\npurposes:\n- purpose: service security and diagnostics\n  text: afin d’assurer la disponibilité, le diagnostic et la sécurité du service\n- purpose: handling contact requests\n\
  \  text: Ces informations servent uniquement à traiter la demande ou le signalement.\nretention:\n- scope: weekly anonymous counters\n  period: 91 jours\n  text: Les compteurs hebdomadaires sont conservés pendant 91 jours sans cookie, identifiant persistant ni ligne\n    d’événement.\n- scope: browser local journey memory\n  period: trente jours\n  text: le navigateur conserve aussi localement, pendant trente jours au maximum\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Effacer button in the journey bar for local data\n  text: Les données locales peuvent être supprimées avec le bouton « Effacer » de la barre de parcours.\nrights:\n- right: access, rectification, erasure, restriction, objection\n  text: Vous pouvez demander l’accès, la rectification, l’effacement, la limitation ou l’opposition lorsque ces\n    droits sont applicables.\n- right: complaint to CNIL\n  text: Vous pouvez aussi\
  \ saisir la CNIL\nsale_or_sharing:\n  stance: prohibited\n  text: Aucun fichier client n’est vendu.\n"
source_yaml_url: https://artifacts.apis.io/compatair-fr/privacy/compatair-fr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from CompatAir's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Air Compressors
- Pneumatic Tools
- Compatibility
- Product Data
- Industrial Equipment
- MCP
- France
---
