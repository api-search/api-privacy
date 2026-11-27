---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identité : civilité, prénom, nom (collectés à la réservation).'
  - category: contact
    text: 'Coordonnées : email, téléphone (recommandé pour les rappels SMS).'
  - category: financial
    text: DIKOO ne stocke aucun numéro de carte bancaire ; seul l'identifiant Stripe de la transaction est conservé pour la facturation.
  - category: health
    text: Lorsque la consultation révèle des données sensibles (par exemple sur votre santé), ce consentement vaut consentement explicite au sens de l'article 9.2.a du RGPD.
  deletion:
    route: Suppression depuis la page de la consultation ou sur demande
    text: Vous pouvez la supprimer à tout moment depuis la page de la consultation
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Gérer votre compte et l'authentification
    text: Gérer votre compte et l'authentification.
  - purpose: Réserver et gérer les consultations
    text: Réserver et gérer les Consultations (calendrier, salle visio, paiement).
  - purpose: Notifications
    text: Vous envoyer les notifications nécessaires (confirmation, rappels J-1 et H-1 par email et SMS, annulation, demande de retour).
  - purpose: Facturation et comptabilité
    text: Émettre les factures et tenir la comptabilité légale (côté Avocat).
  - purpose: Prévention de la fraude
    text: Détecter et prévenir les fraudes (paiement, abus).
  residency:
  - region: Francfort, Allemagne (UE)
    text: Fonctions exécutées à Francfort (Allemagne)
  retention:
  - period: 90 jours
    scope: Transcription de consultation (Premium)
    text: 'Durée de conservation : 90 jours à compter de l''accord, puis effacement automatique par un traitement quotidien'
  - period: 90 jours glissants
    scope: Données de parcours utilisateur
    text: 'Durée de conservation : 90 jours glissants (puis purge automatique).'
  - period: 1 an après la date du rendez-vous
    scope: Vérification des rendez-vous visio
    text: 'Durée de conservation : 1 an après la date du rendez-vous, puis effacement automatique'
  - period: 3 ans après le rendez-vous
    scope: Absences et contestations
    text: 'Durées de conservation : métadonnées de présence et réponses, 1 an après le rendez-vous ; absences et contestations, 3 ans après le rendez-vous.'
  - period: null
    scope: Pré-inscription futurs avocats
    text: 'Durée de conservation : 30 jours sans confirmation de l''adresse, 18 mois au plus sans rapprochement, puis suppression automatique'
  rights:
  - right: Droits RGPD
    text: Vos droits (RGPD)
  - right: Réclamation CNIL
    text: Réclamation CNIL
  - right: Opposition
    text: 'Opposition : lien « Ne plus recevoir ces e-mails » ou support@dikoo.fr.'
  role:
    text: DIKOO agit comme responsable du traitement pour les données de fonctionnement de la plateforme (comptes, facturation, métadonnées de rendez-vous, statistiques)
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Transferts hors UE : Daily.co et Deepgram sont situés aux États-Unis ; les transferts sont encadrés par les clauses contractuelles types de la Commission européenne (article 46 du RGPD).'
  - mechanism: DPF
    text: Data Privacy Framework UE–États-Unis et SCC
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DIKOO
provenance_date: '2026-11-09'
provider_name: DIKOO
provider_slug: dikoo-fr
slug: dikoo-fr-privacy-policy
source_date: '2026-11-09'
source_filename: dikoo-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.dikoo.fr/confidentialite
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DIKOO\naid: dikoo-fr\nurl: https://www.dikoo.fr/confidentialite\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: DIKOO agit comme responsable du traitement pour les données de fonctionnement de la plateforme (comptes,\n    facturation, métadonnées de rendez-vous, statistiques)\ndata_categories:\n- category: identifying\n  text: 'Identité : civilité, prénom, nom (collectés à la réservation).'\n- category: contact\n  text: 'Coordonnées : email, téléphone (recommandé pour les rappels SMS).'\n- category: financial\n  text: DIKOO ne stocke aucun numéro de carte bancaire ; seul l'identifiant\
  \ Stripe de la transaction est conservé\n    pour la facturation.\n- category: health\n  text: Lorsque la consultation révèle des données sensibles (par exemple sur votre santé), ce consentement vaut\n    consentement explicite au sens de l'article 9.2.a du RGPD.\npurposes:\n- purpose: Gérer votre compte et l'authentification\n  text: Gérer votre compte et l'authentification.\n- purpose: Réserver et gérer les consultations\n  text: Réserver et gérer les Consultations (calendrier, salle visio, paiement).\n- purpose: Notifications\n  text: Vous envoyer les notifications nécessaires (confirmation, rappels J-1 et H-1 par email et SMS, annulation,\n    demande de retour).\n- purpose: Facturation et comptabilité\n  text: Émettre les factures et tenir la comptabilité légale (côté Avocat).\n- purpose: Prévention de la fraude\n  text: Détecter et prévenir les fraudes (paiement, abus).\nretention:\n- scope: Transcription de consultation (Premium)\n  period: 90 jours\n  text: 'Durée de conservation\
  \ : 90 jours à compter de l''accord, puis effacement automatique par un traitement\n    quotidien'\n- scope: Données de parcours utilisateur\n  period: 90 jours glissants\n  text: 'Durée de conservation : 90 jours glissants (puis purge automatique).'\n- scope: Vérification des rendez-vous visio\n  period: 1 an après la date du rendez-vous\n  text: 'Durée de conservation : 1 an après la date du rendez-vous, puis effacement automatique'\n- scope: Absences et contestations\n  period: 3 ans après le rendez-vous\n  text: 'Durées de conservation : métadonnées de présence et réponses, 1 an après le rendez-vous ; absences et contestations,\n    3 ans après le rendez-vous.'\n- scope: Pré-inscription futurs avocats\n  period: null\n  text: 'Durée de conservation : 30 jours sans confirmation de l''adresse, 18 mois au plus sans rapprochement, puis\n    suppression automatique'\nresidency:\n- region: Francfort, Allemagne (UE)\n  text: Fonctions exécutées à Francfort (Allemagne)\ntransfers:\n- mechanism:\
  \ SCC\n  text: 'Transferts hors UE : Daily.co et Deepgram sont situés aux États-Unis ; les transferts sont encadrés par\n    les clauses contractuelles types de la Commission européenne (article 46 du RGPD).'\n- mechanism: DPF\n  text: Data Privacy Framework UE–États-Unis et SCC\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Suppression depuis la page de la consultation ou sur demande\n  text: Vous pouvez la supprimer à tout moment depuis la page de la consultation\nrights:\n- right: Droits RGPD\n  text: Vos droits (RGPD)\n- right: Réclamation CNIL\n  text: Réclamation CNIL\n- right: Opposition\n  text: 'Opposition : lien « Ne plus recevoir ces e-mails » ou support@dikoo.fr.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dikoo-fr/privacy/dikoo-fr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from DIKOO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Lawyers
- Legal Directory
- Appointment Booking
- Legal Tech
- MCP
- Artificial Intelligence
- France
---
