---
api_specs:
- filename: comparr-fr-comparatifs-api-openapi.yml
  format: yaml
  label: Comparr Comparatifs API
  slug: comparr-fr-comparatifs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-comparatifs-api-openapi.yml
- filename: comparr-fr-deals-api-openapi.yml
  format: yaml
  label: Comparr Deals API
  slug: comparr-fr-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-deals-api-openapi.yml
- filename: comparr-fr-discovery-api-openapi.yml
  format: yaml
  label: Comparr Discovery API
  slug: comparr-fr-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-discovery-api-openapi.yml
- filename: comparr-fr-products-api-openapi.yml
  format: yaml
  label: Comparr Products API
  slug: comparr-fr-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-products-api-openapi.yml
- filename: comparr-fr-searches-api-openapi.yml
  format: yaml
  label: Comparr Searches API
  slug: comparr-fr-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-searches-api-openapi.yml
- filename: comparr-fr-versus-api-openapi.yml
  format: yaml
  label: Comparr Versus API
  slug: comparr-fr-versus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comparr-fr/openapi/comparr-fr-versus-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: behavioral
    text: pages vues, provenance (moteur de recherche, assistant IA, lien direct)
  - category: device
    text: type d'appareil et navigateur
  - category: location
    text: l'offre cliquée, la date, le pays et la région déduits de l'adresse IP
  - category: communication
    text: nous conservons votre message
  - category: contact
    text: nous conservons votre adresse e-mail
  deletion:
    route: unsubscribe link in each email
    text: chaque message contient un lien de désinscription en un clic, qui supprime votre adresse
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Audience measurement
    text: Nous utilisons Google Analytics 4 pour comprendre quelles pages sont consultées et comment le site est utilisé.
  - purpose: Click fraud prevention
    text: pour détecter le trafic automatisé
  - purpose: Price alerts and deals by email
    text: Si vous demandez une alerte de prix ou vous abonnez aux bons plans
  residency:
  - region: United States
    text: Le site est hébergé par Railway Corporation (États-Unis).
  retention:
  - period: 14 mois maximum
    scope: Google Analytics measurement
    text: 'Durée : 14 mois maximum.'
  - period: 25 mois
    scope: Offer click events
    text: 'Durée : 25 mois.'
  - period: 24 mois
    scope: Feedback form messages
    text: 'Durée : 24 mois, ou jusqu''à votre demande de suppression.'
  - period: 24 mois
    scope: Product rating responses
    text: 24 mois pour les réponses.
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: Conformément au RGPD, vous disposez d'un droit d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité.
  - right: complaint to CNIL
    text: Vous pouvez également introduire une réclamation auprès de la CNIL
  role:
    text: Le responsable du traitement est Sofyan Achalhi EI
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nous ne vendons aucune donnée.
  subprocessors:
    text: Nous faisons appel à des prestataires techniques pour l'analyse des produits et la collecte des prix
    url: null
  transfers:
  - mechanism: SCC
    text: Les transferts hors Union européenne sont encadrés par les clauses contractuelles types de la Commission européenne.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Comparr
provenance_date: '2026-11-09'
provider_name: Comparr
provider_slug: comparr-fr
slug: comparr-fr-privacy-policy
source_date: '2026-11-09'
source_filename: comparr-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.comparr.fr/confidentialite
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Comparr\naid: comparr-fr\nurl: https://www.comparr.fr/confidentialite\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Le responsable du traitement est Sofyan Achalhi EI\ndata_categories:\n- category: behavioral\n  text: pages vues, provenance (moteur de recherche, assistant IA, lien direct)\n- category: device\n  text: type d'appareil et navigateur\n- category: location\n  text: l'offre cliquée, la date, le pays et la région déduits de l'adresse IP\n- category: communication\n  text: nous conservons votre message\n- category: contact\n  text: nous conservons votre adresse e-mail\npurposes:\n\
  - purpose: Audience measurement\n  text: Nous utilisons Google Analytics 4 pour comprendre quelles pages sont consultées et comment le site est utilisé.\n- purpose: Click fraud prevention\n  text: pour détecter le trafic automatisé\n- purpose: Price alerts and deals by email\n  text: Si vous demandez une alerte de prix ou vous abonnez aux bons plans\nretention:\n- scope: Google Analytics measurement\n  period: 14 mois maximum\n  text: 'Durée : 14 mois maximum.'\n- scope: Offer click events\n  period: 25 mois\n  text: 'Durée : 25 mois.'\n- scope: Feedback form messages\n  period: 24 mois\n  text: 'Durée : 24 mois, ou jusqu''à votre demande de suppression.'\n- scope: Product rating responses\n  period: 24 mois\n  text: 24 mois pour les réponses.\nresidency:\n- region: United States\n  text: Le site est hébergé par Railway Corporation (États-Unis).\ntransfers:\n- mechanism: SCC\n  text: Les transferts hors Union européenne sont encadrés par les clauses contractuelles types de la Commission\n\
  \    européenne.\nsubprocessors:\n  url: null\n  text: Nous faisons appel à des prestataires techniques pour l'analyse des produits et la collecte des prix\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: unsubscribe link in each email\n  text: chaque message contient un lien de désinscription en un clic, qui supprime votre adresse\nrights:\n- right: access, rectification, erasure, restriction, objection, portability\n  text: Conformément au RGPD, vous disposez d'un droit d'accès, de rectification, d'effacement, de limitation, d'opposition\n    et de portabilité.\n- right: complaint to CNIL\n  text: Vous pouvez également introduire une réclamation auprès de la CNIL\nsale_or_sharing:\n  stance: prohibited\n  text: Nous ne vendons aucune donnée.\n"
source_yaml_url: https://artifacts.apis.io/comparr-fr/privacy/comparr-fr-privacy-policy.yml
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
- sale_or_sharing
summary_line: 20 quoted statements, read from Comparr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Price Comparison
- E-Commerce
- Shopping
- Artificial Intelligence
- Product Reviews
- AI Agents
- MCP
- France
---
