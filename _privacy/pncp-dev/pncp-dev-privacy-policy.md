---
api_specs:
- filename: pncp-dev-openapi-generated.yml
  format: yaml
  label: pncp-dev API
  slug: pncp-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pncp-dev/openapi/_ae-authored/pncp-dev-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: o seu e-mail (para o link de acesso e para a cobrança)
  - category: identifying
    text: as suas chaves de API (guardadas em hash, nunca em texto puro)
  - category: behavioral
    text: a contagem de chamadas que aplica a sua cota
  - category: financial
    text: Guardar registro de pagamento é obrigação legal.
  deletion:
    route: Apagar a conta
    text: Quando você apaga a conta, apagamos o e-mail, a senha, as chaves e a contagem, e ficamos só com o que a lei fiscal manda guardar sobre os pagamentos que já aconteceram.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service access and quota
    text: Guardar o seu e-mail, as suas chaves e a sua contagem de uso é execução do contrato
  - purpose: Login abuse prevention
    text: O limite de tentativas de login e o hash das chaves são legítimo interesse
  retention:
  - period: 15 minutos
    scope: Email access link and code
    text: O link e o código de acesso que chegam por e-mail valem 15 minutos e depois não valem mais nada.
  - period: 30 dias
    scope: Panel session
    text: A sessão do painel dura 30 dias, e sair encerra ela na hora.
  - period: enquanto a sua conta existir
    scope: Account data
    text: O resto fica enquanto a sua conta existir.
  rights:
  - right: Access, correction, deletion, portability
    text: A LGPD te dá o direito de confirmar se tratamos dados seus, de ver esses dados, de corrigir o que estiver errado, de pedir para apagar ou anonimizar, de levar os dados para outro lugar em formato aberto
  - right: Object to legitimate-interest processing
    text: de se opor a um uso que se apoie no legítimo interesse
  role:
    text: É ela a controladora dos dados descritos aqui.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: não vendemos nem repassamos as suas informações para marketing
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pncp-dev
provenance_date: '2026-11-10'
provider_name: pncp-dev
provider_slug: pncp-dev
slug: pncp-dev-privacy-policy
source_date: '2026-11-10'
source_filename: pncp-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pncp.dev/privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pncp-dev\naid: pncp-dev\nurl: https://pncp.dev/privacidade\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: É ela a controladora dos dados descritos aqui.\ndata_categories:\n- category: contact\n  text: o seu e-mail (para o link de acesso e para a cobrança)\n- category: identifying\n  text: as suas chaves de API (guardadas em hash, nunca em texto puro)\n- category: behavioral\n  text: a contagem de chamadas que aplica a sua cota\n- category: financial\n  text: Guardar registro de pagamento é obrigação legal.\npurposes:\n- purpose: Service access and quota\n  text: Guardar o seu e-mail, as suas\
  \ chaves e a sua contagem de uso é execução do contrato\n- purpose: Login abuse prevention\n  text: O limite de tentativas de login e o hash das chaves são legítimo interesse\nretention:\n- scope: Email access link and code\n  period: 15 minutos\n  text: O link e o código de acesso que chegam por e-mail valem 15 minutos e depois não valem mais nada.\n- scope: Panel session\n  period: 30 dias\n  text: A sessão do painel dura 30 dias, e sair encerra ela na hora.\n- scope: Account data\n  period: enquanto a sua conta existir\n  text: O resto fica enquanto a sua conta existir.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Apagar a conta\n  text: Quando você apaga a conta, apagamos o e-mail, a senha, as chaves e a contagem, e ficamos só com o que a\n    lei fiscal manda guardar sobre os pagamentos que já aconteceram.\nrights:\n- right: Access, correction, deletion, portability\n  text: A LGPD\
  \ te dá o direito de confirmar se tratamos dados seus, de ver esses dados, de corrigir o que estiver\n    errado, de pedir para apagar ou anonimizar, de levar os dados para outro lugar em formato aberto\n- right: Object to legitimate-interest processing\n  text: de se opor a um uso que se apoie no legítimo interesse\nsale_or_sharing:\n  stance: prohibited\n  text: não vendemos nem repassamos as suas informações para marketing\n"
source_yaml_url: https://artifacts.apis.io/pncp-dev/privacy/pncp-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from pncp-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Proxy
- Public Data
- Brazil
- Procurement
- Open Data
---
