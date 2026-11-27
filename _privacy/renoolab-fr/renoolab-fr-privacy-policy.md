---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nom complet ou nom commercial, ville, code postal et coordonnées géographiques associées à la ville
  - category: contact
    text: 'Demandes de contact sans compte : nom, e-mail, téléphone, message et artisan destinataire'
  - category: financial
    text: Statut d'abonnement et historique de paiement gérés avec RevenueCat, Apple ou Google
  - category: communication
    text: Messages privés échangés entre utilisateurs
  - category: device
    text: Token de notifications push, si vous autorisez les notifications
  - category: location
    text: coordonnées géographiques associées à la ville
  deletion:
    route: in-app account deletion
    text: Vous pouvez supprimer votre compte depuis l'application
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and requested features
    text: 'Créer et gérer votre compte et exécuter les fonctionnalités demandées : exécution du contrat'
  - purpose: Audience and campaign measurement
    text: 'Mesurer l''audience et les campagnes sur le site et la webapp : consentement préalable, y compris pour la mesure de conversion côté serveur'
  - purpose: Payments and accounting
    text: 'Gérer les paiements et obligations comptables : contrat et obligations légales'
  residency:
  - region: Paris (eu-west-3)
    text: Les comptes et données applicatives sont hébergés sur Supabase en région Paris (eu-west-3).
  - region: European jurisdiction
    text: Les justificatifs de vérification sont placés dans un bucket Cloudflare R2 privé avec juridiction européenne.
  retention:
  - period: pendant son activité
    scope: Account data
    text: Les données du compte sont conservées pendant son activité.
  - period: 24 mois
    scope: Private messages
    text: 'Contenu des messages privés : pseudonymisé après 24 mois'
  - period: 12 mois
    scope: Artisan profile views
    text: 'Vues de profils artisan : supprimées après 12 mois'
  - period: 30 jours
    scope: Anti-abuse logs
    text: 'Journaux anti-abus des contacts et créations agentiques : supprimés après 30 jours'
  - period: dix ans
    scope: Accounting records
    text: Les pièces comptables peuvent être conservées dix ans.
  - period: 12 mois
    scope: Assistant journey logs
    text: 'Journaux de parcours assistant : conservation limitée à 12 mois, dans les seules tables techniques mcp_tool_calls et mcp_funnel_events'
  rights:
  - right: Access, rectification, erasure, portability, objection, restriction
    text: Vous disposez des droits d'accès, rectification, effacement, portabilité, opposition et limitation du traitement.
  - right: Complaint to supervisory authority
    text: 'Vous pouvez également saisir la Commission Nationale de l''Informatique et des Libertés (CNIL) : www.cnil.fr .'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Selon la fonctionnalité utilisée, des données strictement nécessaires sont traitées par RevenueCat, Apple ou Google pour les achats, Expo puis Apple APNs ou Google FCM pour les notifications, et Brevo pour les e-mails transactionnels.
    url: null
  transfers:
  - mechanism: other
    text: Les transferts éventuels hors de l'Espace économique européen sont encadrés par les mécanismes contractuels applicables.
  - mechanism: other
    text: Ces services peuvent transférer des données vers les États-Unis dans le cadre des garanties juridiques applicables.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RenooLab
provenance_date: '2026-11-10'
provider_name: RenooLab
provider_slug: renoolab-fr
slug: renoolab-fr-privacy-policy
source_date: '2026-11-10'
source_filename: renoolab-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://renoolab.fr/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RenooLab\naid: renoolab-fr\nurl: https://renoolab.fr/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Nom complet ou nom commercial, ville, code postal et coordonnées géographiques associées à la ville\n- category: contact\n  text: 'Demandes de contact sans compte : nom, e-mail, téléphone, message et artisan destinataire'\n- category: financial\n  text: Statut d'abonnement et historique de paiement gérés avec RevenueCat, Apple ou Google\n- category: communication\n  text: Messages privés échangés entre utilisateurs\n- category:\
  \ device\n  text: Token de notifications push, si vous autorisez les notifications\n- category: location\n  text: coordonnées géographiques associées à la ville\npurposes:\n- purpose: Account and requested features\n  text: 'Créer et gérer votre compte et exécuter les fonctionnalités demandées : exécution du contrat'\n- purpose: Audience and campaign measurement\n  text: 'Mesurer l''audience et les campagnes sur le site et la webapp : consentement préalable, y compris pour\n    la mesure de conversion côté serveur'\n- purpose: Payments and accounting\n  text: 'Gérer les paiements et obligations comptables : contrat et obligations légales'\nretention:\n- scope: Account data\n  period: pendant son activité\n  text: Les données du compte sont conservées pendant son activité.\n- scope: Private messages\n  period: 24 mois\n  text: 'Contenu des messages privés : pseudonymisé après 24 mois'\n- scope: Artisan profile views\n  period: 12 mois\n  text: 'Vues de profils artisan : supprimées après\
  \ 12 mois'\n- scope: Anti-abuse logs\n  period: 30 jours\n  text: 'Journaux anti-abus des contacts et créations agentiques : supprimés après 30 jours'\n- scope: Accounting records\n  period: dix ans\n  text: Les pièces comptables peuvent être conservées dix ans.\n- scope: Assistant journey logs\n  period: 12 mois\n  text: 'Journaux de parcours assistant : conservation limitée à 12 mois, dans les seules tables techniques mcp_tool_calls\n    et mcp_funnel_events'\nresidency:\n- region: Paris (eu-west-3)\n  text: Les comptes et données applicatives sont hébergés sur Supabase en région Paris (eu-west-3).\n- region: European jurisdiction\n  text: Les justificatifs de vérification sont placés dans un bucket Cloudflare R2 privé avec juridiction européenne.\ntransfers:\n- mechanism: other\n  text: Les transferts éventuels hors de l'Espace économique européen sont encadrés par les mécanismes contractuels\n    applicables.\n- mechanism: other\n  text: Ces services peuvent transférer des données\
  \ vers les États-Unis dans le cadre des garanties juridiques applicables.\nsubprocessors:\n  url: null\n  text: Selon la fonctionnalité utilisée, des données strictement nécessaires sont traitées par RevenueCat, Apple\n    ou Google pour les achats, Expo puis Apple APNs ou Google FCM pour les notifications, et Brevo pour les e-mails\n    transactionnels.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app account deletion\n  text: Vous pouvez supprimer votre compte depuis l'application\nrights:\n- right: Access, rectification, erasure, portability, objection, restriction\n  text: Vous disposez des droits d'accès, rectification, effacement, portabilité, opposition et limitation du traitement.\n- right: Complaint to supervisory authority\n  text: 'Vous pouvez également saisir la Commission Nationale de l''Informatique et des Libertés (CNIL) : www.cnil.fr\n    .'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/renoolab-fr/privacy/renoolab-fr-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 23 quoted statements, read from RenooLab's own page on 2026-11-10.
synthetic: false
tags:
- Home Services
- Construction
- Building Trades
- Renovation
- Marketplace
- Local Services
- MCP
- A2A
- AI Agents
- Agent Skills
- France
---
