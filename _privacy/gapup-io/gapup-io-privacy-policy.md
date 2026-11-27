---
api_specs:
- filename: gapup-io-openapi-generated.yml
  format: yaml
  label: gapup-io API
  slug: gapup-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gapup-io/openapi/_ae-authored/gapup-io-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identité : email, nom (facultatif), mot de passe (hashé via scrypt).'
  - category: device
    text: 'Données de session : cookies authentification (httpOnly, sameSite=lax), IP, user-agent, horodatage.'
  - category: financial
    text: 'Données de facturation (lors d''un abonnement) : adresse de facturation, identifiant client Stripe — gérées par Stripe.'
  - category: other
    text: 'Données métier : tout contenu que tu saisis ou génères dans les services Gapup.'
  deletion:
    route: Erasure request via the rights form or dpo@gapup.io
    text: Effacement — droit à l'oubli, supprimer mon compte (Art. 17)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate subscribed services
    text: Fournir et exploiter les services souscrits.
  - purpose: Authentication and fraud prevention
    text: Authentifier l'utilisateur, prévenir la fraude.
  - purpose: Subscription billing via Stripe
    text: Facturer les abonnements via Stripe (sous-traitant agréé).
  - purpose: Product improvement with aggregated statistics
    text: Améliorer le produit (statistiques agrégées non identifiantes).
  residency:
  - region: EU (Frankfurt)
    text: Supabase (hébergement DB, EU Frankfurt) — données utilisateur + sessions
  - region: EU (Ireland)
    text: Stripe (paiement, EU Ireland) — données de facturation
  retention:
  - period: tant que le compte est actif + 12 mois après suppression
    scope: User account
    text: 'Compte utilisateur : tant que le compte est actif + 12 mois après suppression.'
  - period: 12 mois
    scope: Authentication logs
    text: 'Logs d''authentification : 12 mois.'
  - period: 10 ans
    scope: Invoices
    text: 'Factures : 10 ans (obligation légale comptable).'
  - period: tant que l'abonnement est actif
    scope: Business data
    text: 'Données métier : tant que l''abonnement est actif. Export sur demande.'
  rights:
  - right: Access
    text: Accès — recevoir une copie de mes données (Art. 15)
  - right: Rectification
    text: Rectification — corriger des données inexactes (Art. 16)
  - right: Erasure
    text: Effacement — droit à l'oubli, supprimer mon compte (Art. 17)
  - right: Restriction
    text: Limitation — geler temporairement le traitement (Art. 18)
  - right: Portability
    text: Portabilité — recevoir mes données en format JSON/CSV (Art. 20)
  - right: Objection
    text: Opposition — m'opposer à un traitement basé sur l'intérêt légitime (Art. 21)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Supabase (hébergement DB, EU Frankfurt) — données utilisateur + sessions
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: gapup-io
provenance_date: '2026-11-09'
provider_name: gapup-io
provider_slug: gapup-io
slug: gapup-io-privacy-policy
source_date: '2026-11-09'
source_filename: gapup-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.gapup.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: gapup-io\naid: gapup-io\nurl: https://www.gapup.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Identité : email, nom (facultatif), mot de passe (hashé via scrypt).'\n- category: device\n  text: 'Données de session : cookies authentification (httpOnly, sameSite=lax), IP, user-agent, horodatage.'\n- category: financial\n  text: 'Données de facturation (lors d''un abonnement) : adresse de facturation, identifiant client Stripe — gérées\n    par Stripe.'\n- category: other\n  text: 'Données métier : tout contenu que tu saisis\
  \ ou génères dans les services Gapup.'\npurposes:\n- purpose: Provide and operate subscribed services\n  text: Fournir et exploiter les services souscrits.\n- purpose: Authentication and fraud prevention\n  text: Authentifier l'utilisateur, prévenir la fraude.\n- purpose: Subscription billing via Stripe\n  text: Facturer les abonnements via Stripe (sous-traitant agréé).\n- purpose: Product improvement with aggregated statistics\n  text: Améliorer le produit (statistiques agrégées non identifiantes).\nretention:\n- scope: User account\n  period: tant que le compte est actif + 12 mois après suppression\n  text: 'Compte utilisateur : tant que le compte est actif + 12 mois après suppression.'\n- scope: Authentication logs\n  period: 12 mois\n  text: 'Logs d''authentification : 12 mois.'\n- scope: Invoices\n  period: 10 ans\n  text: 'Factures : 10 ans (obligation légale comptable).'\n- scope: Business data\n  period: tant que l'abonnement est actif\n  text: 'Données métier : tant que l''abonnement\
  \ est actif. Export sur demande.'\nresidency:\n- region: EU (Frankfurt)\n  text: Supabase (hébergement DB, EU Frankfurt) — données utilisateur + sessions\n- region: EU (Ireland)\n  text: Stripe (paiement, EU Ireland) — données de facturation\ntransfers: []\nsubprocessors:\n  url: null\n  text: Supabase (hébergement DB, EU Frankfurt) — données utilisateur + sessions\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Erasure request via the rights form or dpo@gapup.io\n  text: Effacement — droit à l'oubli, supprimer mon compte (Art. 17)\nrights:\n- right: Access\n  text: Accès — recevoir une copie de mes données (Art. 15)\n- right: Rectification\n  text: Rectification — corriger des données inexactes (Art. 16)\n- right: Erasure\n  text: Effacement — droit à l'oubli, supprimer mon compte (Art. 17)\n- right: Restriction\n  text: Limitation — geler temporairement le traitement (Art. 18)\n- right: Portability\n  text: Portabilité — recevoir mes données en format JSON/CSV\
  \ (Art. 20)\n- right: Objection\n  text: Opposition — m'opposer à un traitement basé sur l'intérêt légitime (Art. 21)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gapup-io/privacy/gapup-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from gapup-io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Compliance
- Enterprise
---
