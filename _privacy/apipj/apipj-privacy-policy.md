---
api_specs:
- filename: apipj-billing-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Billing API
  slug: apipj-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-billing-api-openapi.yml
- filename: apipj-chaves-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Chaves API
  slug: apipj-chaves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-chaves-api-openapi.yml
- filename: apipj-consulta-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Consulta API
  slug: apipj-consulta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-consulta-api-openapi.yml
- filename: apipj-conta-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Conta API
  slug: apipj-conta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-conta-api-openapi.yml
- filename: apipj-interno-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Interno API
  slug: apipj-interno-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-interno-api-openapi.yml
- filename: apipj-p-blico-api-openapi.yml
  format: yaml
  label: apipj (MASTER BI TECNOLOGIA LTDA) Público API
  slug: apipj-p-blico-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apipj/openapi/apipj-p-blico-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: nome, e-mail, senha (quando você cria uma; guardada apenas como hash criptográfico, nunca em claro)
  - category: financial
    text: Pagamento identificadores de cliente, assinatura, sessão de pagamento e cobrança
  - category: identifying
    text: nome do sócio ou administrador, qualificação
  - category: behavioral
    text: Origem do cadastro por qual canal você chegou ao site antes de criar a conta
  - category: device
    text: hash do IP
  deletion:
    route: painel ou e-mail
    text: Ao pedir o encerramento (pelo painel ou por e-mail), revogamos as chaves, encerramos as sessões e cancelamos a assinatura na hora
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and API delivery
    text: Criar e manter sua conta, autenticar você, entregar a API, aplicar os limites e a cota do plano
  - purpose: Measurement and advertising with consent
    text: 'Medir a audiência do site: quantas visitas, de onde vêm'
  residency:
  - region: Brasil (AWS São Paulo)
    text: Nosso servidor fica no Brasil (AWS, região São Paulo).
  retention:
  - period: 6 meses
    scope: Registro de acesso
    text: Registro de acesso (data e hora, IP, endereço acessado, user-agent) 6 meses, depois eliminação
  - period: 30 dias
    scope: Planilhas geradas das listas
    text: Planilhas geradas das listas 30 dias após a geração entrega a quem pediu
  rights:
  - right: eliminação de dados tratados com consentimento
    text: (f) pedir a eliminação dos dados tratados com base no seu consentimento
  - right: revogação do consentimento
    text: (i) revogar o consentimento dado
  role:
    text: 'Controlador: MASTER BI TECNOLOGIA LTDA, CNPJ 35.659.589/0001-19'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Não vendemos os dados da sua conta, não os usamos para publicidade de terceiros e não fazemos perfilamento.
  subprocessors:
    text: Amazon Web Services (AWS) operador
    url: null
  transfers:
  - mechanism: SCC
    text: cláusulas-padrão contratuais aprovadas pela ANPD (Resolução CD/ANPD 19/2024)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apipj (MASTER BI TECNOLOGIA LTDA)
provenance_date: '2026-11-09'
provider_name: apipj (MASTER BI TECNOLOGIA LTDA)
provider_slug: apipj
slug: apipj-privacy-policy
source_date: '2026-11-09'
source_filename: apipj-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apipj.com.br/privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apipj (MASTER BI TECNOLOGIA LTDA)\naid: apipj\nurl: https://apipj.com.br/privacidade\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controlador: MASTER BI TECNOLOGIA LTDA, CNPJ 35.659.589/0001-19'\ndata_categories:\n- category: contact\n  text: nome, e-mail, senha (quando você cria uma; guardada apenas como hash criptográfico, nunca em claro)\n- category: financial\n  text: Pagamento identificadores de cliente, assinatura, sessão de pagamento e cobrança\n- category: identifying\n  text: nome do sócio ou administrador, qualificação\n- category: behavioral\n  text: Origem do cadastro por qual\
  \ canal você chegou ao site antes de criar a conta\n- category: device\n  text: hash do IP\npurposes:\n- purpose: Account and API delivery\n  text: Criar e manter sua conta, autenticar você, entregar a API, aplicar os limites e a cota do plano\n- purpose: Measurement and advertising with consent\n  text: 'Medir a audiência do site: quantas visitas, de onde vêm'\nretention:\n- scope: Registro de acesso\n  period: 6 meses\n  text: Registro de acesso (data e hora, IP, endereço acessado, user-agent) 6 meses, depois eliminação\n- scope: Planilhas geradas das listas\n  period: 30 dias\n  text: Planilhas geradas das listas 30 dias após a geração entrega a quem pediu\nresidency:\n- region: Brasil (AWS São Paulo)\n  text: Nosso servidor fica no Brasil (AWS, região São Paulo).\ntransfers:\n- mechanism: SCC\n  text: cláusulas-padrão contratuais aprovadas pela ANPD (Resolução CD/ANPD 19/2024)\nsubprocessors:\n  url: null\n  text: Amazon Web Services (AWS) operador\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: painel ou e-mail\n  text: Ao pedir o encerramento (pelo painel ou por e-mail), revogamos as chaves, encerramos as sessões e cancelamos\n    a assinatura na hora\nrights:\n- right: eliminação de dados tratados com consentimento\n  text: (f) pedir a eliminação dos dados tratados com base no seu consentimento\n- right: revogação do consentimento\n  text: (i) revogar o consentimento dado\nsale_or_sharing:\n  stance: prohibited\n  text: Não vendemos os dados da sua conta, não os usamos para publicidade de terceiros e não fazemos perfilamento.\n"
source_yaml_url: https://artifacts.apis.io/apipj/privacy/apipj-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from apipj (MASTER BI TECNOLOGIA LTDA)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Brazil
- CNPJ
- Registry
- Public APIs
---
