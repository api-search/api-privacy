---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: email, parola (stocată hash), număr de telefon (opțional, pentru OTP și WhatsApp), denumire firmă, CUI (opțional)
  - category: financial
    text: Paddle transmite Avizo confirmarea plății și datele de facturare necesare (email, țară, CUI pentru TVA inversat)
  - category: device
    text: adresă IP (pentru rate limiting și securitate)
  - category: behavioral
    text: timestamps acțiuni, tipuri de iteme create, statistici de utilizare agregate
  - category: professional
    text: datele angajaților sau terților introduse de clienții noștri (Tenants) în platformă
  deletion:
    route: ștergere imediată la cerere prin email
    text: ștergere imediată la cerere ( [email protected] )
  dpa:
    available: true
    text: Relația dintre Avizo și Tenants în calitate de Procesator este reglementată prin Acordul de Procesare a Datelor (DPA) — inclus automat la acceptarea Termenilor.
    url: null
  purposes:
  - purpose: furnizarea Serviciului (executarea contractului)
    text: 'Baza legală: executarea contractului (Art. 6(1)(b) GDPR)'
  - purpose: securitate și prevenirea fraudei
    text: 'Baza legală: interes legitim (Art. 6(1)(f) GDPR) — securitate și prevenirea fraudei.'
  - purpose: furnizarea Serviciului contractat (date Tenants)
    text: sunt prelucrate exclusiv în scopul furnizării Serviciului contractat, conform instrucțiunilor Tenantului-Operator
  residency:
  - region: EU (Germania)
    text: Hetzner Online GmbH Infrastructură cloud (VPS) UE (Germania)
  retention:
  - period: 30 de zile
    scope: date cont după anulare
    text: 'Date cont după anulare: 30 de zile de la sfârșitul ultimei perioade plătite, după care sunt șterse automat (job zilnic)'
  - period: 5 ani
    scope: date de facturare
    text: 'Date de facturare (pentru audit fiscal): 5 ani conform legislației fiscale RO'
  - period: 30 de zile
    scope: backup zilnic
    text: copie zilnică locală a bazei de date, păstrată 30 de zile
  - period: până la 6 luni
    scope: backup săptămânal criptat
    text: copie săptămânală criptată, în afara serverului, păstrată până la 6 luni
  rights:
  - right: Acces
    text: Acces — să soliciți o copie a datelor tale
  - right: Rectificare
    text: Rectificare — să corectezi date incorecte
  - right: Ștergere
    text: Ștergere — să ceri ștergerea datelor (cu excepția obligațiilor legale)
  - right: Portabilitate
    text: Portabilitate — să primești datele în format structurat (JSON/CSV)
  - right: Restricție
    text: Restricție — să limitezi procesarea în anumite situații
  - right: Opoziție
    text: Opoziție — față de procesarea bazată pe interes legitim
  - right: Retragerea consimțământului
    text: Retragerea consimțământului — oricând, pentru procesările bazate pe consimțământ
  - right: Plângere la autoritate
    text: Ai și dreptul de a depune plângere la ANSPDCP
  role:
    text: Avizo este OPERATOR pentru datele personale ale utilizatorilor proprii
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Avizo utilizează următorii sub-procesori pentru furnizarea Serviciului.
    url: null
  transfers:
  - mechanism: SCC
    text: Twilio, Inc. Trimitere SMS notificări SUA (SCC)
  - mechanism: SCC
    text: Sentry, Inc. Monitorizare erori (fără date personale) SUA (SCC)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Avizo
provenance_date: '2026-11-09'
provider_name: Avizo
provider_slug: avizo-ro
slug: avizo-ro-privacy-policy
source_date: '2026-11-09'
source_filename: avizo-ro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avizo.ro/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Avizo\naid: avizo-ro\nurl: https://avizo.ro/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Avizo este OPERATOR pentru datele personale ale utilizatorilor proprii\ndata_categories:\n- category: contact\n  text: email, parola (stocată hash), număr de telefon (opțional, pentru OTP și WhatsApp), denumire firmă, CUI (opțional)\n- category: financial\n  text: Paddle transmite Avizo confirmarea plății și datele de facturare necesare (email, țară, CUI pentru TVA inversat)\n- category: device\n  text: adresă IP (pentru rate limiting și securitate)\n- category: behavioral\n  text: timestamps\
  \ acțiuni, tipuri de iteme create, statistici de utilizare agregate\n- category: professional\n  text: datele angajaților sau terților introduse de clienții noștri (Tenants) în platformă\npurposes:\n- purpose: furnizarea Serviciului (executarea contractului)\n  text: 'Baza legală: executarea contractului (Art. 6(1)(b) GDPR)'\n- purpose: securitate și prevenirea fraudei\n  text: 'Baza legală: interes legitim (Art. 6(1)(f) GDPR) — securitate și prevenirea fraudei.'\n- purpose: furnizarea Serviciului contractat (date Tenants)\n  text: sunt prelucrate exclusiv în scopul furnizării Serviciului contractat, conform instrucțiunilor Tenantului-Operator\nretention:\n- scope: date cont după anulare\n  period: 30 de zile\n  text: 'Date cont după anulare: 30 de zile de la sfârșitul ultimei perioade plătite, după care sunt șterse automat\n    (job zilnic)'\n- scope: date de facturare\n  period: 5 ani\n  text: 'Date de facturare (pentru audit fiscal): 5 ani conform legislației fiscale RO'\n- scope: backup\
  \ zilnic\n  period: 30 de zile\n  text: copie zilnică locală a bazei de date, păstrată 30 de zile\n- scope: backup săptămânal criptat\n  period: până la 6 luni\n  text: copie săptămânală criptată, în afara serverului, păstrată până la 6 luni\nresidency:\n- region: EU (Germania)\n  text: Hetzner Online GmbH Infrastructură cloud (VPS) UE (Germania)\ntransfers:\n- mechanism: SCC\n  text: Twilio, Inc. Trimitere SMS notificări SUA (SCC)\n- mechanism: SCC\n  text: Sentry, Inc. Monitorizare erori (fără date personale) SUA (SCC)\nsubprocessors:\n  url: null\n  text: Avizo utilizează următorii sub-procesori pentru furnizarea Serviciului.\ndpa:\n  available: true\n  url: null\n  text: Relația dintre Avizo și Tenants în calitate de Procesator este reglementată prin Acordul de Procesare a\n    Datelor (DPA) — inclus automat la acceptarea Termenilor.\ndeletion:\n  route: ștergere imediată la cerere prin email\n  text: ștergere imediată la cerere ( [email protected] )\nrights:\n- right: Acces\n  text:\
  \ Acces — să soliciți o copie a datelor tale\n- right: Rectificare\n  text: Rectificare — să corectezi date incorecte\n- right: Ștergere\n  text: Ștergere — să ceri ștergerea datelor (cu excepția obligațiilor legale)\n- right: Portabilitate\n  text: Portabilitate — să primești datele în format structurat (JSON/CSV)\n- right: Restricție\n  text: Restricție — să limitezi procesarea în anumite situații\n- right: Opoziție\n  text: Opoziție — față de procesarea bazată pe interes legitim\n- right: Retragerea consimțământului\n  text: Retragerea consimțământului — oricând, pentru procesările bazate pe consimțământ\n- right: Plângere la autoritate\n  text: Ai și dreptul de a depune plângere la ANSPDCP\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avizo-ro/privacy/avizo-ro-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from Avizo's own page on 2026-11-09.
synthetic: false
tags:
- Alerts
- Compliance
- Document Management
- Romanian
- Automotive
---
