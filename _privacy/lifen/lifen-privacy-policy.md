---
api_specs:
- filename: lifen-communicationrequest-api-openapi.yml
  format: yaml
  label: Lifen CommunicationRequest API
  slug: lifen-communicationrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-communicationrequest-api-openapi.yml
- filename: lifen-coverage-api-openapi.yml
  format: yaml
  label: Lifen Coverage API
  slug: lifen-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-coverage-api-openapi.yml
- filename: lifen-encounter-api-openapi.yml
  format: yaml
  label: Lifen Encounter API
  slug: lifen-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-encounter-api-openapi.yml
- filename: lifen-organization-api-openapi.yml
  format: yaml
  label: Lifen Organization API
  slug: lifen-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-organization-api-openapi.yml
- filename: lifen-patient-api-openapi.yml
  format: yaml
  label: Lifen Patient API
  slug: lifen-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-patient-api-openapi.yml
- filename: lifen-practitioner-api-openapi.yml
  format: yaml
  label: Lifen Practitioner API
  slug: lifen-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-practitioner-api-openapi.yml
- filename: lifen-token-api-openapi.yml
  format: yaml
  label: Lifen Token API
  slug: lifen-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-token-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Des données personnelles de contact (nom, prénom, date de naissance, email, numéro de mobile, adresse postale)
  - category: health
    text: Des données personnelles sensibles (Données de santé) que sont par exemple, les comptes rendus médicaux, les questionnaires médicaux, etc
  - category: device
    text: Des données personnelles de traçabilité et de navigation sur le site (adresse IP, cookies, logs…)
  deletion:
    route: Au choix du Responsable de traitement, détruire ou restituer les données
    text: 'À l’issue des délais de conservation, Lifen s’engage, au choix du Responsable de traitement, à : Détruire les Données personnelles ; ou Restituer les Données à caractère personnelles au Responsable de traitement'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: échange de documents médicaux
    text: permettre l’échange de documents médicaux entre les Utilisateurs dans le cadre de la solution Lifen Documents
  - purpose: suivi de l'usage des services
    text: suivre l'usage et le fonctionnement des services Lifen
  - purpose: optimisation de la navigation
    text: optimiser la navigation sur notre site
  residency:
  - region: France
    text: dont les espaces de stockage sont situés en France (Région AWS Paris)
  retention:
  - period: trois ans
    scope: Données administratives
    text: sont conservées pendant une durée de trois ans à compter de leur collecte ou du dernier contact avec Lifen
  - period: 13 mois
    scope: Données de navigation
    text: seront conservés conformément à la réglementation applicable pour une durée de 13 mois
  rights:
  - right: accès, rectification, limitation, opposition, effacement, portabilité
    text: vous disposez d’un droit d’accès, de rectification, de limitation, d’opposition, d’effacement et de portabilité sur vos Données personnelles
  - right: contact DPO
    text: dpo@lifen.fr
  role:
    text: Lifen agit comme Sous-traitant. Cela signifie que Lifen, en sa qualité de Sous-traitant, ne traite ces Données personnelles que sur instruction du Responsable de traitement.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Les Sous-traitants de second rang avec lesquels Lifen a conclu un contrat, à la date de publication de la Charte, sont ceux mentionnés dans la l'" Annexe Sous-traitants ".
    url: null
  transfers:
  - mechanism: other
    text: Lifen ne procède à aucun transfert de Données de santé à caractère personnel vers un pays tiers à l’espace économique européen.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lifen
provenance_date: '2026-11-09'
provider_name: Lifen
provider_slug: lifen
slug: lifen-privacy-policy
source_date: '2026-11-09'
source_filename: lifen-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lifen.fr/donnees-personnelles
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lifen\naid: lifen\nurl: https://www.lifen.fr/donnees-personnelles\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Lifen agit comme Sous-traitant. Cela signifie que Lifen, en sa qualité de Sous-traitant, ne traite ces Données\n    personnelles que sur instruction du Responsable de traitement.\ndata_categories:\n- category: contact\n  text: Des données personnelles de contact (nom, prénom, date de naissance, email, numéro de mobile, adresse postale)\n- category: health\n  text: Des données personnelles sensibles (Données de santé) que sont par exemple, les comptes rendus médicaux,\n    les questionnaires\
  \ médicaux, etc\n- category: device\n  text: Des données personnelles de traçabilité et de navigation sur le site (adresse IP, cookies, logs…)\npurposes:\n- purpose: échange de documents médicaux\n  text: permettre l’échange de documents médicaux entre les Utilisateurs dans le cadre de la solution Lifen Documents\n- purpose: suivi de l'usage des services\n  text: suivre l'usage et le fonctionnement des services Lifen\n- purpose: optimisation de la navigation\n  text: optimiser la navigation sur notre site\nretention:\n- scope: Données administratives\n  period: trois ans\n  text: sont conservées pendant une durée de trois ans à compter de leur collecte ou du dernier contact avec Lifen\n- scope: Données de navigation\n  period: 13 mois\n  text: seront conservés conformément à la réglementation applicable pour une durée de 13 mois\nresidency:\n- region: France\n  text: dont les espaces de stockage sont situés en France (Région AWS Paris)\ntransfers:\n- mechanism: other\n  text: Lifen ne\
  \ procède à aucun transfert de Données de santé à caractère personnel vers un pays tiers à l’espace\n    économique européen.\nsubprocessors:\n  url: null\n  text: Les Sous-traitants de second rang avec lesquels Lifen a conclu un contrat, à la date de publication de la\n    Charte, sont ceux mentionnés dans la l'\" Annexe Sous-traitants \".\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Au choix du Responsable de traitement, détruire ou restituer les données\n  text: 'À l’issue des délais de conservation, Lifen s’engage, au choix du Responsable de traitement, à : Détruire\n    les Données personnelles ; ou Restituer les Données à caractère personnelles au Responsable de traitement'\nrights:\n- right: accès, rectification, limitation, opposition, effacement, portabilité\n  text: vous disposez d’un droit d’accès, de rectification, de limitation, d’opposition, d’effacement et de portabilité\n    sur vos Données personnelles\n- right: contact DPO\n  text: dpo@lifen.fr\n\
  sale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lifen/privacy/lifen-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 15 quoted statements, read from Lifen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- FHIR
- Interoperability
- Health Data
- Electronic Health Records
- Medical Documents
- Secure Messaging
- France
- HL7
---
