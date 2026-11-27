---
api_specs:
- filename: checkmails-eu-bulk-api-openapi.yml
  format: yaml
  label: checkmails Bulk API
  slug: checkmails-eu-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-bulk-api-openapi.yml
- filename: checkmails-eu-jobs-api-openapi.yml
  format: yaml
  label: checkmails Jobs API
  slug: checkmails-eu-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-jobs-api-openapi.yml
- filename: checkmails-eu-verify-api-openapi.yml
  format: yaml
  label: checkmails Verify API
  slug: checkmails-eu-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-verify-api-openapi.yml
claim_count: 41
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Données de compte : adresse e-mail, nom, mot de passe (haché par bcrypt), identifiant Google si connexion via Google'
  - category: financial
    text: 'Données de paiement : identifiant client Mollie, plan souscrit, montants facturés, historique de transactions.'
  - category: contact
    text: 'Données de vérification (données de tiers) : adresses e-mail téléversées par nos clients, nom de domaine associé, statut SMTP retourné par le serveur destinataire'
  - category: device
    text: 'Données techniques et logs : adresse IP, user-agent, timestamps, endpoints appelés, codes HTTP, erreurs SMTP.'
  - category: communication
    text: 'Données de support : contenu des échanges lorsque vous nous contactez.'
  deletion:
    route: 'Self-service from the dashboard: GET /api/data-export and POST /api/account/delete for authenticated users; or email contact@checkmails.eu'
    text: Pour les utilisateurs authentifiés, exporter ou supprimer vos données directement depuis votre tableau de bord (endpoints GET /api/data-export et POST /api/account/delete ).
  dpa:
    available: true
    text: selon les termes de notre contrat de sous-traitance (DPA).
    url: null
  purposes:
  - purpose: Gestion de compte
    text: Inscription, authentification, gestion du profil
  - purpose: Paiement et facturation
    text: Encaissement, émission de factures, comptabilité
  - purpose: Vérification d'e-mails
    text: Tester la validité SMTP des adresses fournies par le client (RCPT TO sans envoi de mail)
  - purpose: Logs techniques
    text: Sécurité, anti-fraude, debug
  - purpose: Support client
    text: Réponse aux demandes, qualité de service
  - purpose: E-mails transactionnels
    text: Codes de vérification, réinitialisation de mot de passe, reçus
  - purpose: Cookies de session
    text: Maintien de la session authentifiée
  - purpose: Feedbacks utilisateurs
    text: Recueillir les retours via le bouton « Retour » pour analyser et améliorer le service
  - purpose: Web hosting, database and file storage
    source: https://checkmails.eu/subprocessors
    text: Scaleway SAS Hébergement web, base de données et stockage de fichiers France (Paris)
  - purpose: Payment and subscription processing
    source: https://checkmails.eu/subprocessors
    text: Mollie B.V. Traitement des paiements et des abonnements (prestataire de services de paiement)
  - purpose: Transactional e-mail
    source: https://checkmails.eu/subprocessors
    text: Scaleway TEM (e-mail transactionnel) Envoi des codes de vérification, des liens de réinitialisation et des reçus par e-mail France (Paris)
  - purpose: Egress proxies for domain verification
    source: https://checkmails.eu/subprocessors
    text: OVHcloud (OVH SAS) Hébergement des proxies de sortie (egress) pour la vérification des domaines à filtrage strict (iCloud, Outlook) France
  residency:
  - region: European Union
    text: 'Aucun transfert hors Union européenne n''est réalisé pour les données de vérification (T3) ni pour les données de paiement : notre prestataire de paiement Mollie B.V. est établi aux Pays-Bas (UE).'
  - region: France (Paris)
    source: https://checkmails.eu/subprocessors
    text: Scaleway SAS Hébergement web, base de données et stockage de fichiers France (Paris)
  - region: Netherlands (Amsterdam)
    source: https://checkmails.eu/subprocessors
    text: Mollie B.V. Traitement des paiements et des abonnements (prestataire de services de paiement) Pays-Bas (Amsterdam)
  retention:
  - period: immédiatement
    scope: Fichier source téléversé
    text: 'Fichier source téléversé : supprimé immédiatement après génération des résultats.'
  - period: 30 jours
    scope: Résultats de vérification
    text: 'Résultats de vérification (.xlsx, .pdf, .json) : 30 jours après la fin du traitement, puis suppression automatique.'
  - period: 3 ans après la dernière connexion en cas d'inactivité
    scope: Compte client actif
    text: 'Compte client actif : durée du contrat ; supprimé ou anonymisé 3 ans après la dernière connexion en cas d''inactivité.'
  - period: 10 ans
    scope: Données comptables
    text: 'Données comptables (factures, transactions) : 10 ans (article L.123-22 du Code de commerce).'
  - period: 6 mois maximum avec adresse IP en clair
    scope: Logs techniques
    text: 'Logs techniques : 6 mois maximum avec adresse IP en clair, anonymisés ensuite, supprimés à 12 mois.'
  - period: 30 jours
    scope: Sessions utilisateur
    text: 'Sessions utilisateur : 30 jours.'
  - period: 12 mois
    scope: Feedbacks utilisateurs
    text: 'Feedbacks utilisateurs (bouton « Retour ») : 12 mois à compter de la réception, pour analyse et amélioration du service.'
  - period: 3 ans
    scope: Données de prévention des abus
    text: Ces traces sont conservées jusqu'à 3 ans.
  rights:
  - right: Access
    text: 'Droit d''accès (art. 15) : obtenir copie des données vous concernant.'
  - right: Rectification
    text: 'Droit de rectification (art. 16) : corriger des données inexactes ou les compléter.'
  - right: Erasure
    text: 'Droit à l''effacement (art. 17) : faire supprimer vos données, sous réserve des obligations légales de conservation (notamment comptables).'
  - right: Restriction
    text: 'Droit à la limitation (art. 18) : demander la suspension d''un traitement.'
  - right: Portability
    text: 'Droit à la portabilité (art. 20) : recevoir vos données dans un format structuré et lisible par machine.'
  - right: Objection
    text: 'Droit d''opposition (art. 21) : vous opposer à un traitement fondé sur l''intérêt légitime.'
  - right: Complaint
    text: 'Droit de réclamation : introduire une plainte auprès de la CNIL ( www.cnil.fr/plaintes ).'
  - right: Objection to new subprocessor
    source: https://checkmails.eu/subprocessors
    text: les clients disposent d'un droit d'opposition motivé au recours à un nouveau sous-traitant ultérieur, à exercer dans les 30 jours suivant la notification de la modification.
  role:
    text: Le client est responsable de traitement ; sa base légale est typiquement l'intérêt légitime en B2B (art. 6.1.f). CheckMails.eu agit comme sous-traitant sur ses instructions documentees (art. 28).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Vos données ne sont jamais revendues ni partagées à des fins commerciales.
  subprocessors:
    text: La liste complète et à jour est publiée sur la page Sous-traitants .
    url: https://checkmails.eu/sous-traitants
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: checkmails
provenance_date: '2026-11-09'
provider_name: checkmails
provider_slug: checkmails-eu
slug: checkmails-eu-privacy-policy
source_date: '2026-11-09'
source_filename: checkmails-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://checkmails.eu/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: checkmails\naid: checkmails-eu\nurl: https://checkmails.eu/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://checkmails.eu/privacy\n  - https://checkmails.eu/subprocessors\nrole:\n  value: both\n  text: Le client est responsable de traitement ; sa base légale est typiquement l'intérêt légitime en B2B (art.\n    6.1.f). CheckMails.eu agit comme sous-traitant sur ses instructions documentees (art. 28).\ndata_categories:\n- category: identifying\n  text: 'Données de compte : adresse e-mail, nom, mot de passe (haché par bcrypt), identifiant Google si connexion\n    via Google'\n- category: financial\n\
  \  text: 'Données de paiement : identifiant client Mollie, plan souscrit, montants facturés, historique de transactions.'\n- category: contact\n  text: 'Données de vérification (données de tiers) : adresses e-mail téléversées par nos clients, nom de domaine\n    associé, statut SMTP retourné par le serveur destinataire'\n- category: device\n  text: 'Données techniques et logs : adresse IP, user-agent, timestamps, endpoints appelés, codes HTTP, erreurs\n    SMTP.'\n- category: communication\n  text: 'Données de support : contenu des échanges lorsque vous nous contactez.'\npurposes:\n- purpose: Gestion de compte\n  text: Inscription, authentification, gestion du profil\n- purpose: Paiement et facturation\n  text: Encaissement, émission de factures, comptabilité\n- purpose: Vérification d'e-mails\n  text: Tester la validité SMTP des adresses fournies par le client (RCPT TO sans envoi de mail)\n- purpose: Logs techniques\n  text: Sécurité, anti-fraude, debug\n- purpose: Support client\n  text:\
  \ Réponse aux demandes, qualité de service\n- purpose: E-mails transactionnels\n  text: Codes de vérification, réinitialisation de mot de passe, reçus\n- purpose: Cookies de session\n  text: Maintien de la session authentifiée\n- purpose: Feedbacks utilisateurs\n  text: Recueillir les retours via le bouton « Retour » pour analyser et améliorer le service\n- purpose: Web hosting, database and file storage\n  text: Scaleway SAS Hébergement web, base de données et stockage de fichiers France (Paris)\n  source: https://checkmails.eu/subprocessors\n- purpose: Payment and subscription processing\n  text: Mollie B.V. Traitement des paiements et des abonnements (prestataire de services de paiement)\n  source: https://checkmails.eu/subprocessors\n- purpose: Transactional e-mail\n  text: Scaleway TEM (e-mail transactionnel) Envoi des codes de vérification, des liens de réinitialisation et des\n    reçus par e-mail France (Paris)\n  source: https://checkmails.eu/subprocessors\n- purpose: Egress proxies\
  \ for domain verification\n  text: OVHcloud (OVH SAS) Hébergement des proxies de sortie (egress) pour la vérification des domaines à filtrage\n    strict (iCloud, Outlook) France\n  source: https://checkmails.eu/subprocessors\nretention:\n- scope: Fichier source téléversé\n  period: immédiatement\n  text: 'Fichier source téléversé : supprimé immédiatement après génération des résultats.'\n- scope: Résultats de vérification\n  period: 30 jours\n  text: 'Résultats de vérification (.xlsx, .pdf, .json) : 30 jours après la fin du traitement, puis suppression\n    automatique.'\n- scope: Compte client actif\n  period: 3 ans après la dernière connexion en cas d'inactivité\n  text: 'Compte client actif : durée du contrat ; supprimé ou anonymisé 3 ans après la dernière connexion en cas\n    d''inactivité.'\n- scope: Données comptables\n  period: 10 ans\n  text: 'Données comptables (factures, transactions) : 10 ans (article L.123-22 du Code de commerce).'\n- scope: Logs techniques\n  period: 6 mois\
  \ maximum avec adresse IP en clair\n  text: 'Logs techniques : 6 mois maximum avec adresse IP en clair, anonymisés ensuite, supprimés à 12 mois.'\n- scope: Sessions utilisateur\n  period: 30 jours\n  text: 'Sessions utilisateur : 30 jours.'\n- scope: Feedbacks utilisateurs\n  period: 12 mois\n  text: 'Feedbacks utilisateurs (bouton « Retour ») : 12 mois à compter de la réception, pour analyse et amélioration\n    du service.'\n- scope: Données de prévention des abus\n  period: 3 ans\n  text: Ces traces sont conservées jusqu'à 3 ans.\nresidency:\n- region: European Union\n  text: 'Aucun transfert hors Union européenne n''est réalisé pour les données de vérification (T3) ni pour les\n    données de paiement : notre prestataire de paiement Mollie B.V. est établi aux Pays-Bas (UE).'\n- region: France (Paris)\n  text: Scaleway SAS Hébergement web, base de données et stockage de fichiers France (Paris)\n  source: https://checkmails.eu/subprocessors\n- region: Netherlands (Amsterdam)\n  text:\
  \ Mollie B.V. Traitement des paiements et des abonnements (prestataire de services de paiement) Pays-Bas (Amsterdam)\n  source: https://checkmails.eu/subprocessors\ntransfers: []\nsubprocessors:\n  url: https://checkmails.eu/sous-traitants\n  text: La liste complète et à jour est publiée sur la page Sous-traitants .\ndpa:\n  available: true\n  url: null\n  text: selon les termes de notre contrat de sous-traitance (DPA).\ndeletion:\n  route: 'Self-service from the dashboard: GET /api/data-export and POST /api/account/delete for authenticated users;\n    or email contact@checkmails.eu'\n  text: Pour les utilisateurs authentifiés, exporter ou supprimer vos données directement depuis votre tableau de\n    bord (endpoints GET /api/data-export et POST /api/account/delete ).\nrights:\n- right: Access\n  text: 'Droit d''accès (art. 15) : obtenir copie des données vous concernant.'\n- right: Rectification\n  text: 'Droit de rectification (art. 16) : corriger des données inexactes ou les compléter.'\n\
  - right: Erasure\n  text: 'Droit à l''effacement (art. 17) : faire supprimer vos données, sous réserve des obligations légales de\n    conservation (notamment comptables).'\n- right: Restriction\n  text: 'Droit à la limitation (art. 18) : demander la suspension d''un traitement.'\n- right: Portability\n  text: 'Droit à la portabilité (art. 20) : recevoir vos données dans un format structuré et lisible par machine.'\n- right: Objection\n  text: 'Droit d''opposition (art. 21) : vous opposer à un traitement fondé sur l''intérêt légitime.'\n- right: Complaint\n  text: 'Droit de réclamation : introduire une plainte auprès de la CNIL ( www.cnil.fr/plaintes ).'\n- right: Objection to new subprocessor\n  text: les clients disposent d'un droit d'opposition motivé au recours à un nouveau sous-traitant ultérieur, à\n    exercer dans les 30 jours suivant la notification de la modification.\n  source: https://checkmails.eu/subprocessors\nsale_or_sharing:\n  stance: prohibited\n  text: Vos données ne\
  \ sont jamais revendues ni partagées à des fins commerciales.\n"
source_yaml_url: https://artifacts.apis.io/checkmails-eu/privacy/checkmails-eu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 41 quoted statements, read from checkmails's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- SMTP
- GDPR
- Data Quality
- European Union
- MCP
- Odoo
---
