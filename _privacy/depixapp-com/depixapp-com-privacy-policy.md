---
api_specs:
- filename: depixapp-com-account-api-openapi.yml
  format: yaml
  label: DePix App Account API
  slug: depixapp-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-account-api-openapi.yml
- filename: depixapp-com-agents-api-openapi.yml
  format: yaml
  label: DePix App Agents API
  slug: depixapp-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-agents-api-openapi.yml
- filename: depixapp-com-checkouts-api-openapi.yml
  format: yaml
  label: DePix App Checkouts API
  slug: depixapp-com-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-checkouts-api-openapi.yml
- filename: depixapp-com-merchant-api-openapi.yml
  format: yaml
  label: DePix App Merchant API
  slug: depixapp-com-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-merchant-api-openapi.yml
- filename: depixapp-com-meta-api-openapi.yml
  format: yaml
  label: DePix App Meta API
  slug: depixapp-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-meta-api-openapi.yml
- filename: depixapp-com-pay-api-openapi.yml
  format: yaml
  label: DePix App Pay API
  slug: depixapp-com-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-pay-api-openapi.yml
- filename: depixapp-com-products-api-openapi.yml
  format: yaml
  label: DePix App Products API
  slug: depixapp-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-products-api-openapi.yml
- filename: depixapp-com-public-api-openapi.yml
  format: yaml
  label: DePix App Public API
  slug: depixapp-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-public-api-openapi.yml
- filename: depixapp-com-support-api-openapi.yml
  format: yaml
  label: DePix App Support API
  slug: depixapp-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/depixapp-com/openapi/depixapp-com-support-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Cadastro: nome, endereço de e-mail, contato de WhatsApp, nome de usuário e senha (armazenada apenas de forma cifrada/hash).'
  - category: financial
    text: valores, datas, identificadores e status das operações
  - category: device
    text: endereço IP, identificador de dispositivo, tipo de navegador e dados de acesso e de log
  - category: location
    text: endereços públicos da Liquid Network (endereços de depósito e de carteira)
  - category: communication
    text: 'Suporte: o conteúdo das mensagens que você nos envia.'
  deletion:
    route: pedido de exclusão pelo canal da Seção 3
    text: Atendido o pedido de exclusão ("direito ao esquecimento"), eliminamos ou anonimizamos os dados sob nosso controle, ressalvadas as hipóteses de guarda obrigatória
  dpa:
    available: null
    text: incluindo cláusulas de proteção de dados previstas em seus contratos/DPAs
    url: null
  purposes:
  - purpose: cadastro e autenticação
    text: viabilizar o cadastro e a autenticação
  - purpose: execução e conciliação de operações
    text: executar e conciliar as operações
  - purpose: prevenção a fraudes
    text: prevenir fraudes e garantir a segurança
  - purpose: cumprimento de obrigações legais
    text: cumprir obrigações legais e regulatórias (diretamente ou por meio dos Parceiros)
  - purpose: comunicações de marketing
    text: mediante consentimento, enviar comunicações
  residency:
  - region: Brasil e Estados Unidos
    text: Parte dos provedores de infraestrutura pode tratar dados fora do Brasil — por exemplo, hospedagem e funções (Vercel), banco de dados (Turso) e telemetria agregada (Upstash), tipicamente em servidores nos Estados Unidos
  retention:
  - period: 5 anos
    scope: dados de cadastro
    text: enquanto a conta estiver ativa e por até 5 anos após o encerramento
  - period: 6 meses
    scope: registros de acesso (logs)
    text: 'registros de acesso (logs): no mínimo 6 meses'
  - period: até a revogação
    scope: dados tratados com consentimento
    text: 'dados tratados com consentimento: até a revogação'
  rights:
  - right: acesso
    text: acesso; correção
  - right: portabilidade
    text: portabilidade
  - right: oposição a tratamento fundado em legítimo interesse
    text: oposição a tratamento fundado em legítimo interesse (art. 18, §2º)
  - right: revogação do consentimento
    text: revogação do consentimento
  role:
    text: O DePix App é o controlador dos dados descritos na Seção 5; os Parceiros são controladores independentes dos dados que coletam diretamente.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Não vendemos seus dados pessoais.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: baseamo-nos nas garantias contratuais oferecidas por esses provedores (incluindo cláusulas de proteção de dados previstas em seus contratos/DPAs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DePix App
provenance_date: '2026-11-09'
provider_name: DePix App
provider_slug: depixapp-com
slug: depixapp-com-privacy-policy
source_date: '2026-11-09'
source_filename: depixapp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://depixapp.com/privacidade/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DePix App\naid: depixapp-com\nurl: https://depixapp.com/privacidade/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: O DePix App é o controlador dos dados descritos na Seção 5; os Parceiros são controladores independentes\n    dos dados que coletam diretamente.\ndata_categories:\n- category: identifying\n  text: 'Cadastro: nome, endereço de e-mail, contato de WhatsApp, nome de usuário e senha (armazenada apenas de\n    forma cifrada/hash).'\n- category: financial\n  text: valores, datas, identificadores e status das operações\n- category: device\n  text: endereço IP, identificador de dispositivo,\
  \ tipo de navegador e dados de acesso e de log\n- category: location\n  text: endereços públicos da Liquid Network (endereços de depósito e de carteira)\n- category: communication\n  text: 'Suporte: o conteúdo das mensagens que você nos envia.'\npurposes:\n- purpose: cadastro e autenticação\n  text: viabilizar o cadastro e a autenticação\n- purpose: execução e conciliação de operações\n  text: executar e conciliar as operações\n- purpose: prevenção a fraudes\n  text: prevenir fraudes e garantir a segurança\n- purpose: cumprimento de obrigações legais\n  text: cumprir obrigações legais e regulatórias (diretamente ou por meio dos Parceiros)\n- purpose: comunicações de marketing\n  text: mediante consentimento, enviar comunicações\nretention:\n- scope: dados de cadastro\n  period: 5 anos\n  text: enquanto a conta estiver ativa e por até 5 anos após o encerramento\n- scope: registros de acesso (logs)\n  period: 6 meses\n  text: 'registros de acesso (logs): no mínimo 6 meses'\n- scope: dados\
  \ tratados com consentimento\n  period: até a revogação\n  text: 'dados tratados com consentimento: até a revogação'\nresidency:\n- region: Brasil e Estados Unidos\n  text: Parte dos provedores de infraestrutura pode tratar dados fora do Brasil — por exemplo, hospedagem e funções\n    (Vercel), banco de dados (Turso) e telemetria agregada (Upstash), tipicamente em servidores nos Estados Unidos\ntransfers:\n- mechanism: other\n  text: baseamo-nos nas garantias contratuais oferecidas por esses provedores (incluindo cláusulas de proteção de\n    dados previstas em seus contratos/DPAs)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: incluindo cláusulas de proteção de dados previstas em seus contratos/DPAs\ndeletion:\n  route: pedido de exclusão pelo canal da Seção 3\n  text: Atendido o pedido de exclusão (\"direito ao esquecimento\"), eliminamos ou anonimizamos os dados sob nosso\n    controle, ressalvadas as hipóteses de guarda obrigatória\nrights:\n\
  - right: acesso\n  text: acesso; correção\n- right: portabilidade\n  text: portabilidade\n- right: oposição a tratamento fundado em legítimo interesse\n  text: oposição a tratamento fundado em legítimo interesse (art. 18, §2º)\n- right: revogação do consentimento\n  text: revogação do consentimento\nsale_or_sharing:\n  stance: prohibited\n  text: Não vendemos seus dados pessoais.\n"
source_yaml_url: https://artifacts.apis.io/depixapp-com/privacy/depixapp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from DePix App's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Pix
- Stablecoins
- Cryptocurrency
- Bitcoin
- Liquid Network
- Brazil
- MCP
---
