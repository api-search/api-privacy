---
claim_count: 8
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 'Para estatística guardamos contagens agregadas por hora: endpoint chamado, domínio do site de origem, tipo de cliente'
  - category: contact
    text: Quem escreve para dev@moradas.dev partilha o seu endereço de e-mail; usamo-lo apenas para responder.
  - category: other
    text: As mensagens enviadas (morada em falta, sugestão) são guardadas com uma impressão digital criptográfica truncada do endereço IP
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: statistics
    text: Para estatística guardamos contagens agregadas por hora
  - purpose: abuse containment
    text: serve só para conter abuso e não permite reconstruir o IP
  - purpose: correct and improve data
    text: Usamos as mensagens apenas para corrigir e melhorar os dados.
  retention:
  - period: null
    scope: search text
    text: Não é guardado nem associado a uma pessoa.
  - period: uma hora
    scope: repeat request counts
    text: são contados em memória durante uma hora
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: moradas-dev
provenance_date: '2026-11-10'
provider_name: moradas-dev
provider_slug: moradas-dev
slug: moradas-dev-privacy-policy
source_date: '2026-11-10'
source_filename: moradas-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://moradas.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: moradas-dev\naid: moradas-dev\nurl: https://moradas.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: 'Para estatística guardamos contagens agregadas por hora: endpoint chamado, domínio do site de origem, tipo\n    de cliente'\n- category: contact\n  text: Quem escreve para dev@moradas.dev partilha o seu endereço de e-mail; usamo-lo apenas para responder.\n- category: other\n  text: As mensagens enviadas (morada em falta, sugestão) são guardadas com uma impressão digital criptográfica\n    truncada do endereço IP\npurposes:\n-\
  \ purpose: statistics\n  text: Para estatística guardamos contagens agregadas por hora\n- purpose: abuse containment\n  text: serve só para conter abuso e não permite reconstruir o IP\n- purpose: correct and improve data\n  text: Usamos as mensagens apenas para corrigir e melhorar os dados.\nretention:\n- scope: search text\n  period: null\n  text: Não é guardado nem associado a uma pessoa.\n- scope: repeat request counts\n  period: uma hora\n  text: são contados em memória durante uma hora\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moradas-dev/privacy/moradas-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 8 quoted statements, read from moradas-dev's own page on 2026-11-10.
synthetic: false
tags:
- Address
- Portugal
- Autocomplete
- OpenAPI
- Free
---
