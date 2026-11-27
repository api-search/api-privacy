---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nome e cognome, email, ruolo e permessi, reparto, metodo di autenticazione (password, SSO aziendale), preferenze di lingua e fuso.
  - category: contact
    text: denominazione o nome, partita IVA e codice fiscale, contatti, indirizzi, ruoli, note
  - category: professional
    text: Ragione sociale, partita IVA verificata tramite VIES, sede, referenti, il contratto firmato in fase di registrazione.
  - category: financial
    text: Piano, moduli attivi, consumi e stato dei pagamenti.
  - category: communication
    text: il testo dei messaggi inviati e ricevuti, con data e ora, stato di consegna e chi li ha scritti
  - category: behavioral
    text: 'Chi ha fatto cosa e quando: accessi, download, modifiche, chiamate degli assistenti AI.'
  - category: device
    text: Gli errori che l’app web e l’app per telefono incontrano, e i tempi di caricamento delle pagine dell’app web.
  deletion:
    route: email request to privacy address
    text: Le richieste vanno a [email protected] e ricevono risposta entro un mese.
  dpa:
    available: true
    text: Il cliente che vuole formalizzare con Archiva Srl l’accordo di nomina a responsabile del trattamento (art. 28 GDPR)
    url: null
  purposes:
  - purpose: contract performance
    text: Esecuzione del contratto (art. 6.1.b GDPR) — erogare il servizio, tenere l’archivio, inviare e ricevere la posta, emettere le fatture.
  - purpose: legal obligations
    text: Obblighi di legge (art. 6.1.c) — conservazione fiscale, conservazione a norma quando il modulo è attivo, contabilità.
  - purpose: legitimate interest
    text: Legittimo interesse (art. 6.1.f) — sicurezza della piattaforma, prevenzione degli abusi, log tecnici
  - purpose: consent for optional AI assistant
    text: l’attivazione di un assistente AI esterno, che il singolo utente autorizza da una schermata dedicata
  residency:
  - region: EU
    text: L’applicazione, il database e la posta girano su server virtuali privati (VPS) nell’Unione europea
  - region: non-EU possible (Cloudflare R2 file storage)
    text: i contenitori che li ospitano non sono vincolati alla giurisdizione dell’Unione europea
  - region: US
    text: Il contenuto dei documenti che l’AI del prodotto analizza è elaborato da OpenAI negli Stati Uniti
  retention:
  - period: 90 giorni
    scope: application diagnostics
    text: si cancella da sola dopo 90 giorni
  - period: 30 giorni
    scope: website session recordings
    text: Le registrazioni sono conservate per 30 giorni e poi cancellate automaticamente.
  - period: null
    scope: documents
    text: I documenti restano finché li tieni.
  - period: null
    scope: tax and accounting data
    text: I dati fiscali e contabili per il tempo imposto dalla legge italiana.
  rights:
  - right: access
    text: Puoi chiedere l’accesso ai tuoi dati
  - right: rectification or erasure
    text: la loro rettifica o cancellazione
  - right: restriction or objection
    text: la limitazione o l’opposizione al trattamento
  - right: portability
    text: la portabilità in un formato leggibile da una macchina (artt. 15–22 GDPR)
  - right: withdraw consent
    text: Puoi revocare in qualsiasi momento un consenso che hai dato
  - right: complaint to authority
    text: Resta sempre possibile proporre reclamo al Garante per la protezione dei dati personali
  role:
    text: Custodo è responsabile del trattamento ai sensi dell’art. 28 GDPR
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Questi sono tutti i fornitori che trattano dati per erogare Custodo. L’elenco è completo
    url: null
  transfers:
  - mechanism: DPF
    text: la decisione di adeguatezza UE-USA ( EU-U.S. Data Privacy Framework ) per i fornitori che vi aderiscono
  - mechanism: SCC
    text: le clausole contrattuali standard adottate dalla Commissione europea
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Custodo
provenance_date: '2026-11-09'
provider_name: Custodo
provider_slug: custodo-ai
slug: custodo-ai-privacy-policy
source_date: '2026-11-09'
source_filename: custodo-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://custodo.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Custodo\naid: custodo-ai\nurl: https://custodo.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Custodo è responsabile del trattamento ai sensi dell’art. 28 GDPR\ndata_categories:\n- category: identifying\n  text: Nome e cognome, email, ruolo e permessi, reparto, metodo di autenticazione (password, SSO aziendale), preferenze\n    di lingua e fuso.\n- category: contact\n  text: denominazione o nome, partita IVA e codice fiscale, contatti, indirizzi, ruoli, note\n- category: professional\n  text: Ragione sociale, partita IVA verificata tramite VIES, sede, referenti, il contratto firmato in\
  \ fase di registrazione.\n- category: financial\n  text: Piano, moduli attivi, consumi e stato dei pagamenti.\n- category: communication\n  text: il testo dei messaggi inviati e ricevuti, con data e ora, stato di consegna e chi li ha scritti\n- category: behavioral\n  text: 'Chi ha fatto cosa e quando: accessi, download, modifiche, chiamate degli assistenti AI.'\n- category: device\n  text: Gli errori che l’app web e l’app per telefono incontrano, e i tempi di caricamento delle pagine dell’app\n    web.\npurposes:\n- purpose: contract performance\n  text: Esecuzione del contratto (art. 6.1.b GDPR) — erogare il servizio, tenere l’archivio, inviare e ricevere\n    la posta, emettere le fatture.\n- purpose: legal obligations\n  text: Obblighi di legge (art. 6.1.c) — conservazione fiscale, conservazione a norma quando il modulo è attivo,\n    contabilità.\n- purpose: legitimate interest\n  text: Legittimo interesse (art. 6.1.f) — sicurezza della piattaforma, prevenzione degli abusi, log tecnici\n\
  - purpose: consent for optional AI assistant\n  text: l’attivazione di un assistente AI esterno, che il singolo utente autorizza da una schermata dedicata\nretention:\n- scope: application diagnostics\n  period: 90 giorni\n  text: si cancella da sola dopo 90 giorni\n- scope: website session recordings\n  period: 30 giorni\n  text: Le registrazioni sono conservate per 30 giorni e poi cancellate automaticamente.\n- scope: documents\n  period: null\n  text: I documenti restano finché li tieni.\n- scope: tax and accounting data\n  period: null\n  text: I dati fiscali e contabili per il tempo imposto dalla legge italiana.\nresidency:\n- region: EU\n  text: L’applicazione, il database e la posta girano su server virtuali privati (VPS) nell’Unione europea\n- region: non-EU possible (Cloudflare R2 file storage)\n  text: i contenitori che li ospitano non sono vincolati alla giurisdizione dell’Unione europea\n- region: US\n  text: Il contenuto dei documenti che l’AI del prodotto analizza è elaborato\
  \ da OpenAI negli Stati Uniti\ntransfers:\n- mechanism: DPF\n  text: la decisione di adeguatezza UE-USA ( EU-U.S. Data Privacy Framework ) per i fornitori che vi aderiscono\n- mechanism: SCC\n  text: le clausole contrattuali standard adottate dalla Commissione europea\nsubprocessors:\n  url: null\n  text: Questi sono tutti i fornitori che trattano dati per erogare Custodo. L’elenco è completo\ndpa:\n  available: true\n  url: null\n  text: Il cliente che vuole formalizzare con Archiva Srl l’accordo di nomina a responsabile del trattamento (art.\n    28 GDPR)\ndeletion:\n  route: email request to privacy address\n  text: Le richieste vanno a [email protected] e ricevono risposta entro un mese.\nrights:\n- right: access\n  text: Puoi chiedere l’accesso ai tuoi dati\n- right: rectification or erasure\n  text: la loro rettifica o cancellazione\n- right: restriction or objection\n  text: la limitazione o l’opposizione al trattamento\n- right: portability\n  text: la portabilità in un formato\
  \ leggibile da una macchina (artt. 15–22 GDPR)\n- right: withdraw consent\n  text: Puoi revocare in qualsiasi momento un consenso che hai dato\n- right: complaint to authority\n  text: Resta sempre possibile proporre reclamo al Garante per la protezione dei dati personali\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/custodo-ai/privacy/custodo-ai-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Custodo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document Management
- Business Management
- Small Business
- Digital Preservation
- E-Signature
- CRM
- Expense Management
- Time and Attendance
- AI Assistant
- MCP
- Italy
---
