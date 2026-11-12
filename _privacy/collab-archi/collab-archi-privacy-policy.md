---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nom et prénom
  - category: contact
    text: Adresse email professionnelle
  - category: professional
    text: Fonction au sein de l'agence
  - category: behavioral
    text: Actions effectuées sur la plateforme
  - category: device
    text: Type et version du navigateur
  - category: financial
    text: Historique des transactions
  deletion:
    route: Request by email to the DPO
    text: Vous pouvez demander la suppression de vos données, sauf obligation légale de conservation.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and management
    text: Création et gestion de votre compte
  - purpose: Fraud prevention
    text: Prévention de la fraude
  - purpose: Newsletters with consent
    text: Envoi de newsletters (si vous y avez consenti)
  - purpose: Anonymised statistics
    text: Analyses statistiques anonymisées
  retention:
  - period: Durée de vie du compte + 3 ans
    scope: Account data
    text: 'Données de compte : Durée de vie du compte + 3 ans'
  - period: 5 ans après la fin du projet
    scope: Project data
    text: 'Données de projets : 5 ans après la fin du projet'
  - period: 10 ans
    scope: Invoices
    text: 'Factures : 10 ans (obligation légale)'
  - period: 1 an
    scope: Technical logs
    text: 'Logs techniques : 1 an'
  rights:
  - right: Access
    text: Vous pouvez demander une copie de toutes les données personnelles vous concernant.
  - right: Rectification
    text: Vous pouvez demander la correction de données inexactes ou incomplètes.
  - right: Erasure
    text: Vous pouvez demander la suppression de vos données, sauf obligation légale de conservation.
  - right: Portability
    text: Vous pouvez recevoir vos données dans un format structuré et les transférer à un autre responsable de traitement.
  - right: Objection
    text: Vous pouvez vous opposer au traitement de vos données pour des finalités spécifiques.
  - right: Withdraw consent
    text: Vous pouvez retirer votre consentement à tout moment pour les traitements basés sur celui-ci.
  role:
    text: 'Le responsable du traitement des données personnelles est : Groupe J'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Nous partageons vos données avec les prestataires suivants : Neon : Base de données PostgreSQL'
    url: null
  transfers:
  - mechanism: SCC
    text: Ces transferts sont encadrés par des clauses contractuelles types ou le Data Privacy Framework.
  - mechanism: DPF
    text: Ces transferts sont encadrés par des clauses contractuelles types ou le Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ArchiCollab
provenance_date: '2026-11-09'
provider_name: ArchiCollab
provider_slug: collab-archi
slug: collab-archi-privacy-policy
source_date: '2026-11-09'
source_filename: collab-archi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://collab.archi/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ArchiCollab\naid: collab-archi\nurl: https://collab.archi/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Le responsable du traitement des données personnelles est : Groupe J'\ndata_categories:\n- category: identifying\n  text: Nom et prénom\n- category: contact\n  text: Adresse email professionnelle\n- category: professional\n  text: Fonction au sein de l'agence\n- category: behavioral\n  text: Actions effectuées sur la plateforme\n- category: device\n  text: Type et version du navigateur\n- category: financial\n  text: Historique des transactions\npurposes:\n- purpose:\
  \ Account creation and management\n  text: Création et gestion de votre compte\n- purpose: Fraud prevention\n  text: Prévention de la fraude\n- purpose: Newsletters with consent\n  text: Envoi de newsletters (si vous y avez consenti)\n- purpose: Anonymised statistics\n  text: Analyses statistiques anonymisées\nretention:\n- scope: Account data\n  period: Durée de vie du compte + 3 ans\n  text: 'Données de compte : Durée de vie du compte + 3 ans'\n- scope: Project data\n  period: 5 ans après la fin du projet\n  text: 'Données de projets : 5 ans après la fin du projet'\n- scope: Invoices\n  period: 10 ans\n  text: 'Factures : 10 ans (obligation légale)'\n- scope: Technical logs\n  period: 1 an\n  text: 'Logs techniques : 1 an'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Ces transferts sont encadrés par des clauses contractuelles types ou le Data Privacy Framework.\n- mechanism: DPF\n  text: Ces transferts sont encadrés par des clauses contractuelles types ou le Data Privacy Framework.\n\
  subprocessors:\n  url: null\n  text: 'Nous partageons vos données avec les prestataires suivants : Neon : Base de données PostgreSQL'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request by email to the DPO\n  text: Vous pouvez demander la suppression de vos données, sauf obligation légale de conservation.\nrights:\n- right: Access\n  text: Vous pouvez demander une copie de toutes les données personnelles vous concernant.\n- right: Rectification\n  text: Vous pouvez demander la correction de données inexactes ou incomplètes.\n- right: Erasure\n  text: Vous pouvez demander la suppression de vos données, sauf obligation légale de conservation.\n- right: Portability\n  text: Vous pouvez recevoir vos données dans un format structuré et les transférer à un autre responsable de traitement.\n- right: Objection\n  text: Vous pouvez vous opposer au traitement de vos données pour des finalités spécifiques.\n- right: Withdraw consent\n  text: Vous pouvez retirer votre\
  \ consentement à tout moment pour les traitements basés sur celui-ci.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/collab-archi/privacy/collab-archi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 25 quoted statements, read from ArchiCollab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Architecture
- Collaboration
- PDF Annotation
- Construction
- Document Management
- MCP
- SaaS
- France
---
