---
api_specs:
- filename: valotcg-analysis-api-openapi.yml
  format: yaml
  label: Valo.Data Analysis API
  slug: valotcg-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-analysis-api-openapi.yml
- filename: valotcg-cards-api-openapi.yml
  format: yaml
  label: Valo.Data Cards API
  slug: valotcg-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-cards-api-openapi.yml
- filename: valotcg-editions-api-openapi.yml
  format: yaml
  label: Valo.Data Editions API
  slug: valotcg-editions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-editions-api-openapi.yml
- filename: valotcg-games-api-openapi.yml
  format: yaml
  label: Valo.Data Games API
  slug: valotcg-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-games-api-openapi.yml
- filename: valotcg-sealed-api-openapi.yml
  format: yaml
  label: Valo.Data Sealed API
  slug: valotcg-sealed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-sealed-api-openapi.yml
- filename: valotcg-usage-api-openapi.yml
  format: yaml
  label: Valo.Data Usage API
  slug: valotcg-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valotcg/openapi/valotcg-usage-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Adresse email (obligatoire) Mot de passe (crypté, non visible par ValoTCG) Pseudonyme (optionnel, si fourni)
  - category: financial
    text: Données de facturation (nom, adresse de facturation)
  - category: location
    text: Adresse IP
  - category: device
    text: Identifiants d'appareil (pour l'application mobile)
  - category: behavioral
    text: Données d'usage (statistiques anonymisées d'utilisation)
  deletion:
    route: In-app, web profile, or email to contact@valotcg.com
    text: Depuis l'application mobile ValoTCG Connectez-vous à votre compte Ouvrez l'onglet « … » (Plus) ou accédez à Profil Faites défiler jusqu'à Supprimer mon compte
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and management
    text: Création et gestion du compte utilisateur
  - purpose: Support
    text: Support utilisateur (réponses aux demandes, assistance technique)
  - purpose: Service improvement
    text: Amélioration du Service (analyse anonyme de l'usage, correction de bugs)
  residency:
  - region: European Union
    text: Par défaut, les données sont hébergées dans l'Union européenne.
  retention:
  - period: Durée de vie du compte
    scope: Account data
    text: Durée de vie du compte, puis suppression ou anonymisation à l'issue du délai d'annulation de 14 jours
  - period: 12 mois
    scope: Valo.IA conversations
    text: Chaque conversation est conservée 12 mois après sa dernière réponse, puis supprimée
  - period: 10 ans
    scope: Payment and invoices
    text: Données de paiement et factures 10 ans (obligations comptables et fiscales)
  - period: 12 mois maximum
    scope: Connection logs
    text: Logs de connexion 12 mois maximum
  rights:
  - right: Access
    text: Vous pouvez obtenir une copie de vos données personnelles détenues par ValoTCG.
  - right: Rectification
    text: Vous pouvez corriger des données inexactes ou incomplètes (email, pseudonyme, adresse de facturation).
  - right: Erasure
    text: Vous pouvez demander la suppression de vos données personnelles (« droit à l'oubli »)
  - right: Restriction
    text: Vous pouvez demander la limitation du traitement de vos données dans certains cas
  - right: Portability
    text: Vous pouvez recevoir vos données dans un format structuré et lisible
  - right: Objection
    text: Vous pouvez vous opposer au traitement de vos données pour motif légitime
  - right: Withdraw consent
    text: Si un traitement est fondé sur votre consentement (OAuth Google, analytics futurs), vous pouvez le retirer à tout moment
  role:
    text: Responsable du traitement La présente politique de confidentialité s'applique au site web et à l'application mobile ValoTCG , édités par ValoTCG , Entreprise Individuelle
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Aucune donnée personnelle n'est cédée ou vendue à des tiers à des fins commerciales.
  subprocessors:
    text: Prestataires d'hébergement, de stockage et de diffusion , notamment Railway et Cloudflare, selon les services utilisés
    url: null
  transfers:
  - mechanism: other
    text: 'Prestataire de modèle d''intelligence artificielle : les questions posées à Valo.IA et les données nécessaires à la réponse sont traitées aux États-Unis, dans le cadre d''un transfert encadré.'
  - mechanism: SCC
    text: les clauses contractuelles types de la Commission européenne
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Valo.Data
provenance_date: '2026-11-10'
provider_name: Valo.Data
provider_slug: valotcg
slug: valotcg-privacy-policy
source_date: '2026-11-10'
source_filename: valotcg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://valotcg.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Valo.Data\naid: valotcg\nurl: https://valotcg.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Responsable du traitement La présente politique de confidentialité s'applique au site web et à l'application\n    mobile ValoTCG , édités par ValoTCG , Entreprise Individuelle\ndata_categories:\n- category: identifying\n  text: Adresse email (obligatoire) Mot de passe (crypté, non visible par ValoTCG) Pseudonyme (optionnel, si fourni)\n- category: financial\n  text: Données de facturation (nom, adresse de facturation)\n- category: location\n  text: Adresse IP\n- category: device\n  text:\
  \ Identifiants d'appareil (pour l'application mobile)\n- category: behavioral\n  text: Données d'usage (statistiques anonymisées d'utilisation)\npurposes:\n- purpose: Account creation and management\n  text: Création et gestion du compte utilisateur\n- purpose: Support\n  text: Support utilisateur (réponses aux demandes, assistance technique)\n- purpose: Service improvement\n  text: Amélioration du Service (analyse anonyme de l'usage, correction de bugs)\nretention:\n- scope: Account data\n  period: Durée de vie du compte\n  text: Durée de vie du compte, puis suppression ou anonymisation à l'issue du délai d'annulation de 14 jours\n- scope: Valo.IA conversations\n  period: 12 mois\n  text: Chaque conversation est conservée 12 mois après sa dernière réponse, puis supprimée\n- scope: Payment and invoices\n  period: 10 ans\n  text: Données de paiement et factures 10 ans (obligations comptables et fiscales)\n- scope: Connection logs\n  period: 12 mois maximum\n  text: Logs de connexion 12\
  \ mois maximum\nresidency:\n- region: European Union\n  text: Par défaut, les données sont hébergées dans l'Union européenne.\ntransfers:\n- mechanism: other\n  text: 'Prestataire de modèle d''intelligence artificielle : les questions posées à Valo.IA et les données nécessaires\n    à la réponse sont traitées aux États-Unis, dans le cadre d''un transfert encadré.'\n- mechanism: SCC\n  text: les clauses contractuelles types de la Commission européenne\nsubprocessors:\n  url: null\n  text: Prestataires d'hébergement, de stockage et de diffusion , notamment Railway et Cloudflare, selon les services\n    utilisés\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app, web profile, or email to contact@valotcg.com\n  text: Depuis l'application mobile ValoTCG Connectez-vous à votre compte Ouvrez l'onglet « … » (Plus) ou accédez\n    à Profil Faites défiler jusqu'à Supprimer mon compte\nrights:\n- right: Access\n  text: Vous pouvez obtenir une copie de vos données personnelles\
  \ détenues par ValoTCG.\n- right: Rectification\n  text: Vous pouvez corriger des données inexactes ou incomplètes (email, pseudonyme, adresse de facturation).\n- right: Erasure\n  text: Vous pouvez demander la suppression de vos données personnelles (« droit à l'oubli »)\n- right: Restriction\n  text: Vous pouvez demander la limitation du traitement de vos données dans certains cas\n- right: Portability\n  text: Vous pouvez recevoir vos données dans un format structuré et lisible\n- right: Objection\n  text: Vous pouvez vous opposer au traitement de vos données pour motif légitime\n- right: Withdraw consent\n  text: Si un traitement est fondé sur votre consentement (OAuth Google, analytics futurs), vous pouvez le retirer\n    à tout moment\nsale_or_sharing:\n  stance: prohibited\n  text: Aucune donnée personnelle n'est cédée ou vendue à des tiers à des fins commerciales.\n"
source_yaml_url: https://artifacts.apis.io/valotcg/privacy/valotcg-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Valo.Data's own page on 2026-11-10.
synthetic: false
tags:
- Trading Card Games
- Pricing Data
- Vision
---
