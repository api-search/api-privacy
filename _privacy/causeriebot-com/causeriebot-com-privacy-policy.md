---
api_specs:
- filename: causeriebot-com-chatbots-api-openapi.yml
  format: yaml
  label: Causerie Chatbots API
  slug: causeriebot-com-chatbots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-chatbots-api-openapi.yml
- filename: causeriebot-com-conversations-api-openapi.yml
  format: yaml
  label: Causerie Conversations API
  slug: causeriebot-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-conversations-api-openapi.yml
- filename: causeriebot-com-leads-api-openapi.yml
  format: yaml
  label: Causerie Leads API
  slug: causeriebot-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/causeriebot-com/openapi/causeriebot-com-leads-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Adresse e-mail, nom, avatar, date d'inscription, plan d'abonnement.
  - category: communication
    text: Messages échangés entre vos visiteurs et vos chatbots, adresses IP, identifiants de session, e-mails collectés via les formulaires de contact.
  - category: financial
    text: Identifiant client Stripe, références d'abonnement.
  - category: behavioral
    text: Statistiques quotidiennes (conversations, messages, leads), temps de réponse, domaines d'installation détectés.
  deletion:
    route: Email to contact@causeriebot.com
    text: Demander la suppression de vos données (« droit à l'oubli »), sous réserve de nos obligations légales.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fournir, maintenir et améliorer la plateforme
    text: Fournir, maintenir et améliorer la plateforme CauserieBot
  - purpose: Faire fonctionner les chatbots
    text: Faire fonctionner vos chatbots et traiter les conversations de vos visiteurs
  - purpose: Détecter la fraude et les abus
    text: Détecter et prévenir les utilisations frauduleuses ou abusives
  - purpose: Respecter les obligations légales
    text: Respecter nos obligations légales et réglementaires
  residency:
  - region: Europe (Frankfurt)
    text: Supabase — Base de données, authentification 🇪🇺 Europe (Frankfurt)
  - region: États-Unis
    text: OpenAI — Modèles GPT-4o et GPT-4o Mini (génération des réponses chatbot) 🇺🇸 États-Unis CCT
  retention:
  - period: Durée du compte + 30 jours
    scope: Données de compte
    text: Durée du compte + 30 jours après suppression
  - period: Durée du compte + 30 jours
    scope: Données de chatbots et conversations
    text: 'Rétention : Durée du compte + 30 jours'
  - period: 13 mois glissants
    scope: Données d'usage et analytics
    text: 'Rétention : 13 mois glissants'
  - period: 10 ans
    scope: Données de facturation
    text: 'Rétention : 10 ans (obligation comptable)'
  - period: Durée du compte
    scope: Données de connexion Google
    text: 'Rétention : Durée du compte'
  rights:
  - right: Access
    text: Obtenir une copie de l'ensemble de vos données personnelles détenues par CauserieBot.
  - right: Rectification
    text: Corriger des données inexactes ou incomplètes.
  - right: Erasure
    text: Demander la suppression de vos données (« droit à l'oubli »), sous réserve de nos obligations légales.
  - right: Portability
    text: Recevoir vos données dans un format structuré, couramment utilisé et lisible par machine.
  - right: Objection
    text: Vous opposer au traitement fondé sur l'intérêt légitime, notamment aux communications marketing.
  - right: Restriction
    text: Demander la restriction du traitement dans certains cas prévus par le RGPD.
  role:
    text: CauserieBot agit en qualité de sous-traitant pour le stockage et le traitement de ces données pour votre compte.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Nous ne vendons jamais vos données.
  subprocessors:
    text: CauserieBot fait appel aux prestataires suivants pour fournir le Service.
    url: null
  transfers:
  - mechanism: SCC
    text: le transfert est encadré par les Clauses Contractuelles Types (CCT) approuvées par la Commission européenne.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Causerie
provenance_date: '2026-11-09'
provider_name: Causerie
provider_slug: causeriebot-com
slug: causeriebot-com-privacy-policy
source_date: '2026-11-09'
source_filename: causeriebot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dashboard.causeriebot.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Causerie\naid: causeriebot-com\nurl: https://dashboard.causeriebot.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: CauserieBot agit en qualité de sous-traitant pour le stockage et le traitement de ces données pour votre\n    compte.\ndata_categories:\n- category: contact\n  text: Adresse e-mail, nom, avatar, date d'inscription, plan d'abonnement.\n- category: communication\n  text: Messages échangés entre vos visiteurs et vos chatbots, adresses IP, identifiants de session, e-mails collectés\n    via les formulaires de contact.\n- category: financial\n  text: Identifiant client Stripe,\
  \ références d'abonnement.\n- category: behavioral\n  text: Statistiques quotidiennes (conversations, messages, leads), temps de réponse, domaines d'installation détectés.\npurposes:\n- purpose: Fournir, maintenir et améliorer la plateforme\n  text: Fournir, maintenir et améliorer la plateforme CauserieBot\n- purpose: Faire fonctionner les chatbots\n  text: Faire fonctionner vos chatbots et traiter les conversations de vos visiteurs\n- purpose: Détecter la fraude et les abus\n  text: Détecter et prévenir les utilisations frauduleuses ou abusives\n- purpose: Respecter les obligations légales\n  text: Respecter nos obligations légales et réglementaires\nretention:\n- scope: Données de compte\n  period: Durée du compte + 30 jours\n  text: Durée du compte + 30 jours après suppression\n- scope: Données de chatbots et conversations\n  period: Durée du compte + 30 jours\n  text: 'Rétention : Durée du compte + 30 jours'\n- scope: Données d'usage et analytics\n  period: 13 mois glissants\n  text:\
  \ 'Rétention : 13 mois glissants'\n- scope: Données de facturation\n  period: 10 ans\n  text: 'Rétention : 10 ans (obligation comptable)'\n- scope: Données de connexion Google\n  period: Durée du compte\n  text: 'Rétention : Durée du compte'\nresidency:\n- region: Europe (Frankfurt)\n  text: Supabase — Base de données, authentification \U0001F1EA\U0001F1FA Europe (Frankfurt)\n- region: États-Unis\n  text: OpenAI — Modèles GPT-4o et GPT-4o Mini (génération des réponses chatbot) \U0001F1FA\U0001F1F8 États-Unis CCT\ntransfers:\n- mechanism: SCC\n  text: le transfert est encadré par les Clauses Contractuelles Types (CCT) approuvées par la Commission européenne.\nsubprocessors:\n  url: null\n  text: CauserieBot fait appel aux prestataires suivants pour fournir le Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to contact@causeriebot.com\n  text: Demander la suppression de vos données (« droit à l'oubli »), sous réserve de nos obligations légales.\nrights:\n\
  - right: Access\n  text: Obtenir une copie de l'ensemble de vos données personnelles détenues par CauserieBot.\n- right: Rectification\n  text: Corriger des données inexactes ou incomplètes.\n- right: Erasure\n  text: Demander la suppression de vos données (« droit à l'oubli »), sous réserve de nos obligations légales.\n- right: Portability\n  text: Recevoir vos données dans un format structuré, couramment utilisé et lisible par machine.\n- right: Objection\n  text: Vous opposer au traitement fondé sur l'intérêt légitime, notamment aux communications marketing.\n- right: Restriction\n  text: Demander la restriction du traitement dans certains cas prévus par le RGPD.\nsale_or_sharing:\n  stance: prohibited\n  text: Nous ne vendons jamais vos données.\n"
source_yaml_url: https://artifacts.apis.io/causeriebot-com/privacy/causeriebot-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Causerie's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Customer Service
- Lead Qualification
- French
---
