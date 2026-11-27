---
api_specs:
- filename: jurisign-account-api-openapi.yml
  format: yaml
  label: JuriSign Account API
  slug: jurisign-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-account-api-openapi.yml
- filename: jurisign-authentication-api-openapi.yml
  format: yaml
  label: JuriSign Authentication API
  slug: jurisign-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-authentication-api-openapi.yml
- filename: jurisign-bulk-api-openapi.yml
  format: yaml
  label: JuriSign Bulk API
  slug: jurisign-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-bulk-api-openapi.yml
- filename: jurisign-documents-api-openapi.yml
  format: yaml
  label: JuriSign Documents API
  slug: jurisign-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-documents-api-openapi.yml
- filename: jurisign-public-forms-api-openapi.yml
  format: yaml
  label: JuriSign Public Forms API
  slug: jurisign-public-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-public-forms-api-openapi.yml
- filename: jurisign-sign-requests-api-openapi.yml
  format: yaml
  label: JuriSign Sign Requests API
  slug: jurisign-sign-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-sign-requests-api-openapi.yml
- filename: jurisign-templates-api-openapi.yml
  format: yaml
  label: JuriSign Templates API
  slug: jurisign-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-templates-api-openapi.yml
- filename: jurisign-webhooks-api-openapi.yml
  format: yaml
  label: JuriSign Webhooks API
  slug: jurisign-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Données d''identification des signataires : nom, prénom, adresse de messagerie électronique, numéro de téléphone portable.'
  - category: contact
    text: 'Données d''identification du Client : nom, prénom, adresse de messagerie électronique, numéro de téléphone, dénomination sociale, adresse postale, numéro SIRET et numéro de TVA le cas échéant.'
  - category: device
    text: 'Données de connexion et d''usage : adresse IP, type de navigateur (user agent), horodatage des actions (consultation, signature, refus), journaux d''audit.'
  - category: biometric
    text: ainsi que des images de son visage pour le contrôle de présence réelle et la comparaison avec la photo de la pièce ( données biométriques ).
  - category: location
    text: 'Position et caractéristiques de l''appareil , lorsque le Client active cette option et que le signataire y consent expressément : coordonnées transmises par son appareil, précision annoncée'
  - category: financial
    text: 'Les données bancaires ne sont jamais collectées ni stockées par JuriSign : le paiement s''effectue sur une page hébergée par Stripe'
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Annexe de sous-traitance (article 28 RGPD)
    url: null
  purposes:
  - purpose: Exécution du service de signature électronique
    text: Exécution du service de signature électronique Exécution du contrat (art. 6.1.b RGPD)
  - purpose: Vérification d'identité par pièce d'identité
    text: Vérification de l'identité du signataire par pièce d'identité et comparaison du visage (option choisie par l'expéditeur)
  - purpose: Mesure d'audience et suivi des campagnes publicitaires
    text: Mesure d'audience et suivi des campagnes publicitaires Consentement (art. 6.1.a RGPD et art. 82 loi Informatique et Libertés)
  - purpose: Protection contre la fraude
    text: Protection contre la fraude et les inscriptions automatisées (reCAPTCHA) Intérêt légitime (art. 6.1.f RGPD)
  residency:
  - region: Union européenne
    text: L'hébergement des documents, des dossiers de preuve, des journaux d'audit et de l'ensemble de la base de données est assuré exclusivement dans l'Union européenne .
  retention:
  - period: trente (30) jours
    scope: Données de compte actif
    text: 'Données de compte actif : pendant toute la durée de la relation contractuelle, puis trente (30) jours après la clôture du compte.'
  - period: 5 ans
    scope: Documents signés
    text: 'Documents signés : 5 ans à compter de leur dépôt.'
  - period: un (1) mois au plus
    scope: Images et données de vérification d'identité chez Didit
    text: 'Images et données de la vérification d''identité chez Didit (pièce, visage) : un (1) mois au plus après la vérification, puis supprimées.'
  - period: 5 minutes par SMS et 10 minutes par e-mail
    scope: Codes OTP
    text: 'Codes OTP : valables 5 minutes par SMS et 10 minutes par e-mail.'
  - period: dix (10) ans
    scope: Données de facturation
    text: 'Données de facturation : dix (10) ans, conformément aux obligations comptables et fiscales.'
  rights:
  - right: Droit d'accès
    text: 'Droit d''accès : obtenir la confirmation du traitement de vos données et en recevoir une copie.'
  - right: Droit de rectification
    text: 'Droit de rectification : faire corriger les données inexactes ou incomplètes.'
  - right: Droit à l'effacement
    text: 'Droit à l''effacement : demander la suppression de vos données'
  - right: Droit à la portabilité
    text: 'Droit à la portabilité : recevoir vos données dans un format structuré et couramment utilisé.'
  - right: Droit d'opposition
    text: 'Droit d''opposition : vous opposer au traitement fondé sur l''intérêt légitime.'
  role:
    text: PCFRANCE agit en qualité de responsable de traitement .
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Sous-traitant Finalité Données concernées Localisation IONOS SARL Sarreguemines, France Hébergement de l'infrastructure et acheminement des courriels
    url: null
  transfers:
  - mechanism: SCC
    text: Ces transferts sont encadrés par les mécanismes prévus au chapitre V du RGPD, dont les clauses contractuelles types de la Commission européenne
  - mechanism: DPF
    text: et, le cas échéant, la décision d'adéquation relative au cadre de protection des données UE–États-Unis.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: JuriSign
provenance_date: '2026-11-09'
provider_name: JuriSign
provider_slug: jurisign
slug: jurisign-privacy-policy
source_date: '2026-11-09'
source_filename: jurisign-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.jurisign.fr/confidentialite
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: JuriSign\naid: jurisign\nurl: https://www.jurisign.fr/confidentialite\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: PCFRANCE agit en qualité de responsable de traitement .\ndata_categories:\n- category: identifying\n  text: 'Données d''identification des signataires : nom, prénom, adresse de messagerie électronique, numéro de\n    téléphone portable.'\n- category: contact\n  text: 'Données d''identification du Client : nom, prénom, adresse de messagerie électronique, numéro de téléphone,\n    dénomination sociale, adresse postale, numéro SIRET et numéro de TVA le cas échéant.'\n- category: device\n\
  \  text: 'Données de connexion et d''usage : adresse IP, type de navigateur (user agent), horodatage des actions\n    (consultation, signature, refus), journaux d''audit.'\n- category: biometric\n  text: ainsi que des images de son visage pour le contrôle de présence réelle et la comparaison avec la photo de\n    la pièce ( données biométriques ).\n- category: location\n  text: 'Position et caractéristiques de l''appareil , lorsque le Client active cette option et que le signataire\n    y consent expressément : coordonnées transmises par son appareil, précision annoncée'\n- category: financial\n  text: 'Les données bancaires ne sont jamais collectées ni stockées par JuriSign : le paiement s''effectue sur\n    une page hébergée par Stripe'\npurposes:\n- purpose: Exécution du service de signature électronique\n  text: Exécution du service de signature électronique Exécution du contrat (art. 6.1.b RGPD)\n- purpose: Vérification d'identité par pièce d'identité\n  text: Vérification de l'identité\
  \ du signataire par pièce d'identité et comparaison du visage (option choisie par\n    l'expéditeur)\n- purpose: Mesure d'audience et suivi des campagnes publicitaires\n  text: Mesure d'audience et suivi des campagnes publicitaires Consentement (art. 6.1.a RGPD et art. 82 loi Informatique\n    et Libertés)\n- purpose: Protection contre la fraude\n  text: Protection contre la fraude et les inscriptions automatisées (reCAPTCHA) Intérêt légitime (art. 6.1.f RGPD)\nretention:\n- scope: Données de compte actif\n  period: trente (30) jours\n  text: 'Données de compte actif : pendant toute la durée de la relation contractuelle, puis trente (30) jours après\n    la clôture du compte.'\n- scope: Documents signés\n  period: 5 ans\n  text: 'Documents signés : 5 ans à compter de leur dépôt.'\n- scope: Images et données de vérification d'identité chez Didit\n  period: un (1) mois au plus\n  text: 'Images et données de la vérification d''identité chez Didit (pièce, visage) : un (1) mois au plus après\n\
  \    la vérification, puis supprimées.'\n- scope: Codes OTP\n  period: 5 minutes par SMS et 10 minutes par e-mail\n  text: 'Codes OTP : valables 5 minutes par SMS et 10 minutes par e-mail.'\n- scope: Données de facturation\n  period: dix (10) ans\n  text: 'Données de facturation : dix (10) ans, conformément aux obligations comptables et fiscales.'\nresidency:\n- region: Union européenne\n  text: L'hébergement des documents, des dossiers de preuve, des journaux d'audit et de l'ensemble de la base de\n    données est assuré exclusivement dans l'Union européenne .\ntransfers:\n- mechanism: SCC\n  text: Ces transferts sont encadrés par les mécanismes prévus au chapitre V du RGPD, dont les clauses contractuelles\n    types de la Commission européenne\n- mechanism: DPF\n  text: et, le cas échéant, la décision d'adéquation relative au cadre de protection des données UE–États-Unis.\nsubprocessors:\n  url: null\n  text: Sous-traitant Finalité Données concernées Localisation IONOS SARL Sarreguemines,\
  \ France Hébergement de l'infrastructure\n    et acheminement des courriels\ndpa:\n  available: true\n  url: null\n  text: Annexe de sous-traitance (article 28 RGPD)\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Droit d'accès\n  text: 'Droit d''accès : obtenir la confirmation du traitement de vos données et en recevoir une copie.'\n- right: Droit de rectification\n  text: 'Droit de rectification : faire corriger les données inexactes ou incomplètes.'\n- right: Droit à l'effacement\n  text: 'Droit à l''effacement : demander la suppression de vos données'\n- right: Droit à la portabilité\n  text: 'Droit à la portabilité : recevoir vos données dans un format structuré et couramment utilisé.'\n- right: Droit d'opposition\n  text: 'Droit d''opposition : vous opposer au traitement fondé sur l''intérêt légitime.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jurisign/privacy/jurisign-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
summary_line: 26 quoted statements, read from JuriSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- eIDAS
- PDF
- Webhook
- OTP
- GDPR
- France
- Legal Tech
- Identity Verification
- Audit Trail
- data-residency-eu
---
