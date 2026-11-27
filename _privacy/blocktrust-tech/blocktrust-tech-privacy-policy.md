---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Données d''identification : nom, prénom, adresse e-mail, identifiants de compte.'
  - category: contact
    text: 'Données de vérification : statut de certification, coordonnées déclarées (e-mails, domaines, téléphones), dates d''émission et d''expiration.'
  - category: financial
    text: 'Données de facturation et de paiement : abonnement, historique de facturation'
  - category: biometric
    text: 'Données biométriques : uniquement dans le cadre de la vérification d''identité via Stripe Identity'
  - category: device
    text: 'Données de connexion : journaux techniques, adresses IP hashées, horodatages, identifiants de session.'
  - category: communication
    text: 'Données extension Chrome TrustScan : adresse e-mail de l''expéditeur Gmail transmise pour vérification'
  - category: professional
    text: 'Données organisationnelles (B2B) : nom d''organisation, rôle, entrées de coffre équipe (BLOCKTRUST™ Vault).'
  deletion:
    route: Account settings
    text: Vous pouvez également supprimer votre compte depuis Paramètres
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and management
    text: Création et gestion du compte utilisateur Exécution du contrat (art. 6.1.b)
  - purpose: Identity verification
    text: 'Finalité : vérifier que vous êtes bien la personne déclarée, lutter contre l''usurpation d''identité et respecter nos obligations LCB-FT.'
  - purpose: Chrome extension sender verification
    text: L'adresse e-mail de l'expéditeur est transmise à l'API BLOCKTRUST™ pour vérification contre vos contacts certifiés.
  residency:
  - region: United States
    text: Vercel — hébergement applicatif (États-Unis, CDN mondial)
  retention:
  - period: 12 mois, puis anonymisation
    scope: Verification history
    text: Historique des vérifications 12 mois, puis anonymisation
  - period: 30 jours maximum
    scope: Sessions and authentication tokens
    text: Sessions et tokens d'authentification 30 jours maximum
  - period: 5 ans à compter de la fin de la relation contractuelle
    scope: Identity verification and biometric data (Stripe Identity)
    text: 'Durée de conservation : 5 ans à compter de la fin de la relation contractuelle (obligations LCB-FT).'
  - period: 5 minutes maximum
    scope: TrustScan extension cache
    text: Cache extension TrustScan 5 minutes maximum (local, appareil utilisateur)
  rights:
  - right: Access and rectification
    text: Droit d'accès et de rectification
  - right: Erasure
    text: Droit à l'effacement (« droit à l'oubli »)
  - right: Portability
    text: Droit à la portabilité (export JSON depuis les paramètres du compte)
  - right: Objection to legitimate-interest processing
    text: Droit d'opposition aux traitements fondés sur l'intérêt légitime
  - right: Withdraw consent
    text: Droit de retirer votre consentement à tout moment (sans affecter la licéité du traitement antérieur)
  role:
    text: 'Responsable de traitement : BRNB Tech SAS'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: BLOCKTRUST™ ne vend pas vos données personnelles à des tiers.
  subprocessors:
    text: Vos données peuvent être communiquées aux sous-traitants suivants
    url: null
  transfers:
  - mechanism: SCC
    text: Ces transferts sont encadrés par les Clauses Contractuelles Types (CCT) de la Commission européenne
  - mechanism: DPF
    text: le Data Privacy Framework (DPF) lorsque applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BLOCKTRUST
provenance_date: '2026-11-09'
provider_name: BLOCKTRUST
provider_slug: blocktrust-tech
slug: blocktrust-tech-privacy-policy
source_date: '2026-11-09'
source_filename: blocktrust-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blocktrust.tech/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BLOCKTRUST\naid: blocktrust-tech\nurl: https://blocktrust.tech/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Responsable de traitement : BRNB Tech SAS'\ndata_categories:\n- category: identifying\n  text: 'Données d''identification : nom, prénom, adresse e-mail, identifiants de compte.'\n- category: contact\n  text: 'Données de vérification : statut de certification, coordonnées déclarées (e-mails, domaines, téléphones),\n    dates d''émission et d''expiration.'\n- category: financial\n  text: 'Données de facturation et de paiement : abonnement, historique de facturation'\n- category:\
  \ biometric\n  text: 'Données biométriques : uniquement dans le cadre de la vérification d''identité via Stripe Identity'\n- category: device\n  text: 'Données de connexion : journaux techniques, adresses IP hashées, horodatages, identifiants de session.'\n- category: communication\n  text: 'Données extension Chrome TrustScan : adresse e-mail de l''expéditeur Gmail transmise pour vérification'\n- category: professional\n  text: 'Données organisationnelles (B2B) : nom d''organisation, rôle, entrées de coffre équipe (BLOCKTRUST™ Vault).'\npurposes:\n- purpose: Account creation and management\n  text: Création et gestion du compte utilisateur Exécution du contrat (art. 6.1.b)\n- purpose: Identity verification\n  text: 'Finalité : vérifier que vous êtes bien la personne déclarée, lutter contre l''usurpation d''identité et\n    respecter nos obligations LCB-FT.'\n- purpose: Chrome extension sender verification\n  text: L'adresse e-mail de l'expéditeur est transmise à l'API BLOCKTRUST™ pour\
  \ vérification contre vos contacts\n    certifiés.\nretention:\n- scope: Verification history\n  period: 12 mois, puis anonymisation\n  text: Historique des vérifications 12 mois, puis anonymisation\n- scope: Sessions and authentication tokens\n  period: 30 jours maximum\n  text: Sessions et tokens d'authentification 30 jours maximum\n- scope: Identity verification and biometric data (Stripe Identity)\n  period: 5 ans à compter de la fin de la relation contractuelle\n  text: 'Durée de conservation : 5 ans à compter de la fin de la relation contractuelle (obligations LCB-FT).'\n- scope: TrustScan extension cache\n  period: 5 minutes maximum\n  text: Cache extension TrustScan 5 minutes maximum (local, appareil utilisateur)\nresidency:\n- region: United States\n  text: Vercel — hébergement applicatif (États-Unis, CDN mondial)\ntransfers:\n- mechanism: SCC\n  text: Ces transferts sont encadrés par les Clauses Contractuelles Types (CCT) de la Commission européenne\n- mechanism: DPF\n  text:\
  \ le Data Privacy Framework (DPF) lorsque applicable\nsubprocessors:\n  url: null\n  text: Vos données peuvent être communiquées aux sous-traitants suivants\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings\n  text: Vous pouvez également supprimer votre compte depuis Paramètres\nrights:\n- right: Access and rectification\n  text: Droit d'accès et de rectification\n- right: Erasure\n  text: Droit à l'effacement (« droit à l'oubli »)\n- right: Portability\n  text: Droit à la portabilité (export JSON depuis les paramètres du compte)\n- right: Objection to legitimate-interest processing\n  text: Droit d'opposition aux traitements fondés sur l'intérêt légitime\n- right: Withdraw consent\n  text: Droit de retirer votre consentement à tout moment (sans affecter la licéité du traitement antérieur)\nsale_or_sharing:\n  stance: prohibited\n  text: BLOCKTRUST™ ne vend pas vos données personnelles à des tiers.\n"
source_yaml_url: https://artifacts.apis.io/blocktrust-tech/privacy/blocktrust-tech-privacy-policy.yml
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
summary_line: 26 quoted statements, read from BLOCKTRUST's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- B2B
- Freelance
- E-Commerce
- Trust Monitoring
---
