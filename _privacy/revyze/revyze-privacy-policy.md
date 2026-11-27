---
api_specs:
- filename: revyze-admin-api-openapi.yml
  format: yaml
  label: Revyze Admin API
  slug: revyze-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-admin-api-openapi.yml
- filename: revyze-coach-api-openapi.yml
  format: yaml
  label: Revyze Coach API
  slug: revyze-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-coach-api-openapi.yml
- filename: revyze-fastapi-api-openapi.yml
  format: yaml
  label: Revyze FastAPI API
  slug: revyze-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-fastapi-api-openapi.yml
- filename: revyze-force-upgrade-app-api-openapi.yml
  format: yaml
  label: Revyze Force Upgrade App API
  slug: revyze-force-upgrade-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-force-upgrade-app-api-openapi.yml
- filename: revyze-graphql3-api-openapi.yml
  format: yaml
  label: Revyze Graphql3 API
  slug: revyze-graphql3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-graphql3-api-openapi.yml
- filename: revyze-health-api-openapi.yml
  format: yaml
  label: Revyze Health API
  slug: revyze-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-health-api-openapi.yml
- filename: revyze-multiplayer-api-openapi.yml
  format: yaml
  label: Revyze Multiplayer API
  slug: revyze-multiplayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-multiplayer-api-openapi.yml
- filename: revyze-privacy-policy-api-openapi.yml
  format: yaml
  label: Revyze Privacy Policy API
  slug: revyze-privacy-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-privacy-policy-api-openapi.yml
- filename: revyze-privacy-policy-en-api-openapi.yml
  format: yaml
  label: Revyze Privacy Policy En API
  slug: revyze-privacy-policy-en-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-privacy-policy-en-api-openapi.yml
- filename: revyze-webhook-api-openapi.yml
  format: yaml
  label: Revyze Webhook API
  slug: revyze-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-webhook-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Inscription (téléphone, nom, année scolaire)
  - category: location
    text: localisation et accès média (avec accord)
  - category: financial
    text: Tes informations de facturation sont collectées uniquement par nos prestataires tiers (Stripe ou Apple).
  - category: behavioral
    text: Utilisation (fréquence, contenus)
  - category: device
    text: 'Automatiques : Utilisation (fréquence, contenus) et données de l''appareil.'
  deletion:
    route: in-app account deletion option or email to privacy@revyze.fr
    text: Tu peux demander une suppression anticipée à tout moment en contactant privacy@revyze.fr ou via l'option de suppression de compte dans l'application.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery, subscription, personalisation, security
    text: Nous collectons tes données pour te fournir notre produit, gérer ton abonnement Plus, personnaliser ton expérience et assurer ta sécurité.
  - purpose: audience measurement
    text: à des fins de mesure d'audience
  retention:
  - period: tant que ton compte est actif
    scope: account data
    text: 'Données de compte (téléphone, nom, année scolaire) : conservées tant que ton compte est actif.'
  - period: 30 jours
    scope: account data after deletion
    text: En cas de suppression de compte, ces données sont effacées sous 30 jours
  - period: jusqu'à 10 ans
    scope: billing documents
    text: pendant la durée légale (jusqu'à 10 ans en France)
  - period: jusqu'à 25 mois
    scope: usage and device data
    text: conservées jusqu'à 25 mois à des fins de mesure d'audience
  - period: plus de 4 ans
    scope: inactive accounts
    text: les comptes inactifs depuis plus de 4 ans sont anonymisés ou supprimés.
  rights:
  - right: access, correction, deletion
    text: Tu peux accéder, corriger ou supprimer tes données via les paramètres de l'application ou à notre DPO privacy@revyze.fr .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nous ne vendons jamais tes données.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Revyze
provenance_date: '2026-11-10'
provider_name: Revyze
provider_slug: revyze
slug: revyze-privacy-policy
source_date: '2026-11-10'
source_filename: revyze-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://api.revyze.fr/privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Revyze\naid: revyze\nurl: https://api.revyze.fr/privacy_policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Inscription (téléphone, nom, année scolaire)\n- category: location\n  text: localisation et accès média (avec accord)\n- category: financial\n  text: Tes informations de facturation sont collectées uniquement par nos prestataires tiers (Stripe ou Apple).\n- category: behavioral\n  text: Utilisation (fréquence, contenus)\n- category: device\n  text: 'Automatiques : Utilisation (fréquence, contenus) et données de l''appareil.'\n\
  purposes:\n- purpose: service delivery, subscription, personalisation, security\n  text: Nous collectons tes données pour te fournir notre produit, gérer ton abonnement Plus, personnaliser ton\n    expérience et assurer ta sécurité.\n- purpose: audience measurement\n  text: à des fins de mesure d'audience\nretention:\n- scope: account data\n  period: tant que ton compte est actif\n  text: 'Données de compte (téléphone, nom, année scolaire) : conservées tant que ton compte est actif.'\n- scope: account data after deletion\n  period: 30 jours\n  text: En cas de suppression de compte, ces données sont effacées sous 30 jours\n- scope: billing documents\n  period: jusqu'à 10 ans\n  text: pendant la durée légale (jusqu'à 10 ans en France)\n- scope: usage and device data\n  period: jusqu'à 25 mois\n  text: conservées jusqu'à 25 mois à des fins de mesure d'audience\n- scope: inactive accounts\n  period: plus de 4 ans\n  text: les comptes inactifs depuis plus de 4 ans sont anonymisés ou supprimés.\n\
  residency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app account deletion option or email to privacy@revyze.fr\n  text: Tu peux demander une suppression anticipée à tout moment en contactant privacy@revyze.fr ou via l'option\n    de suppression de compte dans l'application.\nrights:\n- right: access, correction, deletion\n  text: Tu peux accéder, corriger ou supprimer tes données via les paramètres de l'application ou à notre DPO privacy@revyze.fr\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: Nous ne vendons jamais tes données.\n"
source_yaml_url: https://artifacts.apis.io/revyze/privacy/revyze-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Revyze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- Education
- Mobile
- Video
- Learning
- Quiz
- France
- GraphQL
---
