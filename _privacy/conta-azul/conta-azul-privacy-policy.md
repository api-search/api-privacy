---
api_specs:
- filename: conta-azul-categorias-api-openapi.yml
  format: yaml
  label: Conta Azul Categorias API
  slug: conta-azul-categorias-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-categorias-api-openapi.yml
- filename: conta-azul-centro-de-custo-api-openapi.yml
  format: yaml
  label: Conta Azul Centro De Custo API
  slug: conta-azul-centro-de-custo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-centro-de-custo-api-openapi.yml
- filename: conta-azul-conta-financeira-api-openapi.yml
  format: yaml
  label: Conta Azul Conta Financeira API
  slug: conta-azul-conta-financeira-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-conta-financeira-api-openapi.yml
- filename: conta-azul-contratos-api-openapi.yml
  format: yaml
  label: Conta Azul Contratos API
  slug: conta-azul-contratos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-contratos-api-openapi.yml
- filename: conta-azul-financeiro-api-openapi.yml
  format: yaml
  label: Conta Azul Financeiro API
  slug: conta-azul-financeiro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-financeiro-api-openapi.yml
- filename: conta-azul-orcamentos-api-openapi.yml
  format: yaml
  label: Conta Azul Orcamentos API
  slug: conta-azul-orcamentos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-orcamentos-api-openapi.yml
- filename: conta-azul-produto-api-openapi.yml
  format: yaml
  label: Conta Azul Produto API
  slug: conta-azul-produto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-produto-api-openapi.yml
- filename: conta-azul-protocolo-api-openapi.yml
  format: yaml
  label: Conta Azul Protocolo API
  slug: conta-azul-protocolo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-protocolo-api-openapi.yml
- filename: conta-azul-venda-api-openapi.yml
  format: yaml
  label: Conta Azul Venda API
  slug: conta-azul-venda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conta-azul/openapi/conta-azul-venda-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nome Imagem/Selfie CPF (quando clientes pessoa física)
  - category: financial
    text: Dados de cartão de crédito
  - category: financial
    text: Dados bancários
  deletion:
    route: Request to the data subject's consent-based erasure right
    text: Eliminação dos Dados Pessoais tratados com seu consentimento
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identification and qualification of the data subject
    text: Identificação e qualificação de Titular
  - purpose: Operate, protect and improve services
    text: Operar, proteger, realizar testes de funcionalidade, manutenção e melhorias contínuas nos serviços
  - purpose: Marketing messages
    text: Enviar mensagens (e-mails, WhatsApp) com conteúdo informativo/publicitário sobre os serviços Conta Azul
  retention:
  - period: 90 dias
    scope: CCTV images
    text: As imagens captadas são armazenadas pelo prazo de 90 dias
  - period: null
    scope: General personal data
    text: pelo tempo que forem necessários para o cumprimento de suas finalidades
  rights:
  - right: Access
    text: Acesso aos seus Dados Pessoais tratados pela Conta Azul
  - right: Correction
    text: Correção de dados incompletos, inexatos ou desatualizados
  - right: Portability
    text: Portabilidade dos dados a outro fornecedor de serviço ou produto, observados os segredos comercial e industrial
  role:
    text: a Conta Azul exercerá a condição de Operadora de Dados
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Para execução dos serviços a Conta Azul poderá compartilhar dados dos Titulares com prestadores de serviço terceirizados
    url: null
  transfers:
  - mechanism: other
    text: A Conta Azul, em regra, não realiza transferências internacionais de dados pessoais.
  - mechanism: other
    text: adotando as medidas e salvaguardas adequadas previstas, sempre que aplicável
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Conta Azul
provenance_date: '2026-11-09'
provider_name: Conta Azul
provider_slug: conta-azul
slug: conta-azul-privacy-policy
source_date: '2026-11-09'
source_filename: conta-azul-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://contaazul.com/termos/privacidade/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Conta Azul\naid: conta-azul\nurl: https://contaazul.com/termos/privacidade/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: a Conta Azul exercerá a condição de Operadora de Dados\ndata_categories:\n- category: identifying\n  text: Nome Imagem/Selfie CPF (quando clientes pessoa física)\n- category: financial\n  text: Dados de cartão de crédito\n- category: financial\n  text: Dados bancários\npurposes:\n- purpose: Identification and qualification of the data subject\n  text: Identificação e qualificação de Titular\n- purpose: Operate, protect and improve services\n  text: Operar, proteger, realizar\
  \ testes de funcionalidade, manutenção e melhorias contínuas nos serviços\n- purpose: Marketing messages\n  text: Enviar mensagens (e-mails, WhatsApp) com conteúdo informativo/publicitário sobre os serviços Conta Azul\nretention:\n- scope: CCTV images\n  period: 90 dias\n  text: As imagens captadas são armazenadas pelo prazo de 90 dias\n- scope: General personal data\n  period: null\n  text: pelo tempo que forem necessários para o cumprimento de suas finalidades\nresidency: []\ntransfers:\n- mechanism: other\n  text: A Conta Azul, em regra, não realiza transferências internacionais de dados pessoais.\n- mechanism: other\n  text: adotando as medidas e salvaguardas adequadas previstas, sempre que aplicável\nsubprocessors:\n  url: null\n  text: Para execução dos serviços a Conta Azul poderá compartilhar dados dos Titulares com prestadores de serviço\n    terceirizados\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the data subject's consent-based erasure\
  \ right\n  text: Eliminação dos Dados Pessoais tratados com seu consentimento\nrights:\n- right: Access\n  text: Acesso aos seus Dados Pessoais tratados pela Conta Azul\n- right: Correction\n  text: Correção de dados incompletos, inexatos ou desatualizados\n- right: Portability\n  text: Portabilidade dos dados a outro fornecedor de serviço ou produto, observados os segredos comercial e industrial\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conta-azul/privacy/conta-azul-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from Conta Azul's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- ERP
- Brazil
- Small Business
- Financial Management
- Invoicing
- Payments
---
