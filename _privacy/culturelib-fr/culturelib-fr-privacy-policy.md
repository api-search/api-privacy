---
api_specs:
- filename: culturelib-fr-openapi-generated.yml
  format: yaml
  label: CultureLib Discover API
  slug: culturelib-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culturelib-fr/openapi/_ae-authored/culturelib-fr-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: adresse e-mail, nom et photo de profil si vous vous connectez avec Google
  - category: behavioral
    text: 'Statistiques d''usage : pages vues et interactions, mesurées via PostHog (hébergé dans l''Union européenne), pour améliorer le service.'
  - category: device
    text: 'Journaux techniques : adresse IP et user-agent, pour la sécurité, la limitation de débit et la mesure du trafic'
  - category: financial
    text: Nous ne stockons aucune donnée bancaire.
  - category: professional
    text: 'pour les salariés d''entreprises clientes : rattachement à votre employeur, solde de crédits et historique de réservations.'
  deletion:
    route: null
    text: Les données de compte sont conservées tant que le compte est actif, puis supprimées dans les 30 jours suivant sa clôture.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fournir le service (compte, favoris, réservations)
    text: 'Fournir le service (compte, favoris, réservations) : exécution du contrat.'
  - purpose: Sécurité et prévention des abus
    text: 'Sécurité et prévention des abus : intérêt légitime.'
  - purpose: Statistiques d'amélioration du produit
    text: 'Statistiques d''amélioration du produit : intérêt légitime.'
  - purpose: Communications liées à votre compte
    text: 'Communications liées à votre compte : exécution du contrat.'
  residency:
  - region: Europe
    text: Vos données sont hébergées en Europe
  retention:
  - period: 30 jours
    scope: Données de compte
    text: Les données de compte sont conservées tant que le compte est actif, puis supprimées dans les 30 jours suivant sa clôture.
  - period: 12 mois
    scope: Journaux techniques
    text: Les journaux techniques sont conservés au maximum 12 mois.
  rights:
  - right: access
    text: droits d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité sur vos données
  - right: complaint to supervisory authority
    text: Vous pouvez aussi introduire une réclamation auprès de la CNIL (cnil.fr).
  role:
    text: Responsable du traitement CultureLib, représentée par Thomas Balcinha.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nous ne vendons jamais vos données.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Supabase (base de données, AWS Londres, pays bénéficiant d'une décision d'adéquation RGPD)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CultureLib
provenance_date: '2026-11-09'
provider_name: CultureLib
provider_slug: culturelib-fr
slug: culturelib-fr-privacy-policy
source_date: '2026-11-09'
source_filename: culturelib-fr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.culturelib.fr/confidentialite
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CultureLib\naid: culturelib-fr\nurl: https://www.culturelib.fr/confidentialite\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Responsable du traitement CultureLib, représentée par Thomas Balcinha.\ndata_categories:\n- category: identifying\n  text: adresse e-mail, nom et photo de profil si vous vous connectez avec Google\n- category: behavioral\n  text: 'Statistiques d''usage : pages vues et interactions, mesurées via PostHog (hébergé dans l''Union européenne),\n    pour améliorer le service.'\n- category: device\n  text: 'Journaux techniques : adresse IP et user-agent, pour la sécurité, la\
  \ limitation de débit et la mesure du\n    trafic'\n- category: financial\n  text: Nous ne stockons aucune donnée bancaire.\n- category: professional\n  text: 'pour les salariés d''entreprises clientes : rattachement à votre employeur, solde de crédits et historique\n    de réservations.'\npurposes:\n- purpose: Fournir le service (compte, favoris, réservations)\n  text: 'Fournir le service (compte, favoris, réservations) : exécution du contrat.'\n- purpose: Sécurité et prévention des abus\n  text: 'Sécurité et prévention des abus : intérêt légitime.'\n- purpose: Statistiques d'amélioration du produit\n  text: 'Statistiques d''amélioration du produit : intérêt légitime.'\n- purpose: Communications liées à votre compte\n  text: 'Communications liées à votre compte : exécution du contrat.'\nretention:\n- scope: Données de compte\n  period: 30 jours\n  text: Les données de compte sont conservées tant que le compte est actif, puis supprimées dans les 30 jours suivant\n    sa clôture.\n- scope:\
  \ Journaux techniques\n  period: 12 mois\n  text: Les journaux techniques sont conservés au maximum 12 mois.\nresidency:\n- region: Europe\n  text: Vos données sont hébergées en Europe\ntransfers:\n- mechanism: adequacy\n  text: Supabase (base de données, AWS Londres, pays bénéficiant d'une décision d'adéquation RGPD)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Les données de compte sont conservées tant que le compte est actif, puis supprimées dans les 30 jours suivant\n    sa clôture.\nrights:\n- right: access\n  text: droits d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité sur vos données\n- right: complaint to supervisory authority\n  text: Vous pouvez aussi introduire une réclamation auprès de la CNIL (cnil.fr).\nsale_or_sharing:\n  stance: prohibited\n  text: Nous ne vendons jamais vos données.\n"
source_yaml_url: https://artifacts.apis.io/culturelib-fr/privacy/culturelib-fr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from CultureLib's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Culture
- Event
- Ticketing
- Employee Benefits
- France
- MCP
- Entertainment
---
