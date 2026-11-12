---
api_specs:
- filename: corporary-com-change-api-openapi.yml
  format: yaml
  label: corporary Change API
  slug: corporary-com-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-change-api-openapi.yml
- filename: corporary-com-company-api-openapi.yml
  format: yaml
  label: corporary Company API
  slug: corporary-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-company-api-openapi.yml
- filename: corporary-com-search-api-openapi.yml
  format: yaml
  label: corporary Search API
  slug: corporary-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corporary-com/openapi/corporary-com-search-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: votre adresse électronique, nécessaire à l’envoi du lien de connexion
  - category: identifying
    text: vos clés, et un décompte quotidien des appels par clé et par point d’accès
  - category: device
    text: Journaux techniques du serveur, dont l’adresse IP
  - category: behavioral
    text: vos listes de surveillance et règles d’alerte
  - category: communication
    text: 'Réclamations : les informations que vous transmettez'
  deletion:
    route: Write to the DPO at donnees@corporary.com
    text: Écrivez au délégué à la protection des données, donnees@corporary.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account login
    text: votre adresse électronique, nécessaire à l’envoi du lien de connexion
  - purpose: Quota enforcement
    text: un décompte quotidien des appels par clé et par point d’accès, nécessaire à l’application des quotas
  - purpose: Service security
    text: conservés au plus un an, pour la sécurité du service
  - purpose: Legitimate interest in public economic information
    text: l’intérêt légitime d’Edge Query et du public à accéder à une information économique fiable
  residency:
  - region: France
    text: Les données sont hébergées en France par Scaleway.
  retention:
  - period: Tant que le compte existe
    scope: Account data
    text: Conservées tant que le compte existe, puis supprimées.
  - period: Tant que le compte existe
    scope: API keys and call counts
    text: Conservés tant que le compte existe.
  - period: au plus un an
    scope: Server technical logs including IP address
    text: conservés au plus un an, pour la sécurité du service.
  - period: null
    scope: Claims
    text: les informations que vous transmettez, conservées le temps nécessaire au traitement et à la preuve de son exécution.
  rights:
  - right: Access
    text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.
  - right: Rectification
    text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.
  - right: Erasure
    text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.
  - right: Objection to publication of registry data
    text: Vous pouvez vous opposer à la publication de vos données sur la page de réclamation
  - right: Complaint to CNIL
    text: Vous pouvez aussi saisir la Commission nationale de l’informatique et des libertés (CNIL).
  role:
    text: Responsable du traitement Edge Query, SAS, 19 rue du Sperl, 67130 Lutzelhouse, France.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Aucune donnée d’utilisateur n’est vendue ni cédée.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: corporary
provenance_date: '2026-11-09'
provider_name: corporary
provider_slug: corporary-com
slug: corporary-com-privacy-policy
source_date: '2026-11-09'
source_filename: corporary-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corporary.com/fr/confidentialite
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: corporary\naid: corporary-com\nurl: https://corporary.com/fr/confidentialite\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Responsable du traitement Edge Query, SAS, 19 rue du Sperl, 67130 Lutzelhouse, France.\ndata_categories:\n- category: contact\n  text: votre adresse électronique, nécessaire à l’envoi du lien de connexion\n- category: identifying\n  text: vos clés, et un décompte quotidien des appels par clé et par point d’accès\n- category: device\n  text: Journaux techniques du serveur, dont l’adresse IP\n- category: behavioral\n  text: vos listes de surveillance et règles d’alerte\n\
  - category: communication\n  text: 'Réclamations : les informations que vous transmettez'\npurposes:\n- purpose: Account login\n  text: votre adresse électronique, nécessaire à l’envoi du lien de connexion\n- purpose: Quota enforcement\n  text: un décompte quotidien des appels par clé et par point d’accès, nécessaire à l’application des quotas\n- purpose: Service security\n  text: conservés au plus un an, pour la sécurité du service\n- purpose: Legitimate interest in public economic information\n  text: l’intérêt légitime d’Edge Query et du public à accéder à une information économique fiable\nretention:\n- scope: Account data\n  period: Tant que le compte existe\n  text: Conservées tant que le compte existe, puis supprimées.\n- scope: API keys and call counts\n  period: Tant que le compte existe\n  text: Conservés tant que le compte existe.\n- scope: Server technical logs including IP address\n  period: au plus un an\n  text: conservés au plus un an, pour la sécurité du service.\n- scope:\
  \ Claims\n  period: null\n  text: les informations que vous transmettez, conservées le temps nécessaire au traitement et à la preuve de son\n    exécution.\nresidency:\n- region: France\n  text: Les données sont hébergées en France par Scaleway.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to the DPO at donnees@corporary.com\n  text: Écrivez au délégué à la protection des données, donnees@corporary.com.\nrights:\n- right: Access\n  text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.\n- right: Rectification\n  text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.\n- right: Erasure\n  text: Vous disposez d’un droit d’accès, de rectification, d’effacement, de limitation, d’opposition et de portabilité.\n- right: Objection to publication of registry data\n  text: Vous pouvez\
  \ vous opposer à la publication de vos données sur la page de réclamation\n- right: Complaint to CNIL\n  text: Vous pouvez aussi saisir la Commission nationale de l’informatique et des libertés (CNIL).\nsale_or_sharing:\n  stance: prohibited\n  text: Aucune donnée d’utilisateur n’est vendue ni cédée.\n"
source_yaml_url: https://artifacts.apis.io/corporary-com/privacy/corporary-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from corporary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Business Registry
- France
- Financial Data
- Legal Announcements
- MCP
- Open Data
---
