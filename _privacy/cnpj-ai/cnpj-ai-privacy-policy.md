---
api_specs:
- filename: cnpj-ai-cat-logo-api-openapi.yml
  format: yaml
  label: cnpj.ai Catálogo API
  slug: cnpj-ai-cat-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-cat-logo-api-openapi.yml
- filename: cnpj-ai-consulta-de-cnpj-api-openapi.yml
  format: yaml
  label: cnpj.ai Consulta de CNPJ API
  slug: cnpj-ai-consulta-de-cnpj-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-consulta-de-cnpj-api-openapi.yml
- filename: cnpj-ai-empresas-api-openapi.yml
  format: yaml
  label: cnpj.ai Empresas API
  slug: cnpj-ai-empresas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-api-openapi.yml
- filename: cnpj-ai-empresas-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai empresas — fontes API
  slug: cnpj-ai-empresas-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-empresas-fontes-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-api-openapi.yml
  format: yaml
  label: cnpj.ai Estabelecimentos API
  slug: cnpj-ai-estabelecimentos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-api-openapi.yml
- filename: cnpj-ai-estabelecimentos-fontes-api-openapi.yml
  format: yaml
  label: cnpj.ai estabelecimentos — fontes API
  slug: cnpj-ai-estabelecimentos-fontes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnpj-ai/openapi/cnpj-ai-estabelecimentos-fontes-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nomes de sócios e administradores são dados pessoais tornados públicos pela própria Receita Federal
  - category: contact
    text: Ao entrar, coletamos e-mail, nome (quando o login é feito com Google) e o método de login utilizado.
  - category: device
    text: endereço IP e cabeçalhos da requisição ficam em logs do servidor e da rede de distribuição
  - category: behavioral
    text: páginas visitadas, cliques e interações, coletados por ferramentas de análise e de medição de anúncios
  - category: communication
    text: guardamos perguntas, respostas, consultas executadas e consumo do modelo no Supabase, associados à sua conta
  - category: communication
    text: 'Telegram: ao usar @cnpjai_bot, recebemos seu identificador no Telegram, username e mensagens. Não solicitamos telefone.'
  - category: contact
    text: Recebemos seu telefone ou identificador da Meta e o nome do perfil.
  deletion:
    route: Pedido de exclusão da conta ou uso de /desvincular no bot; pedidos ao e-mail de contato
    text: Ao pedir a exclusão da conta, os dados de conta são apagados e as associações de análise à sua identidade são desfeitas.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: manter o site funcionando e autenticar conta
    text: Os dados são usados exclusivamente para manter o site funcionando e autenticar sua conta, entender como o produto é usado e melhorá-lo, aplicar limites de uso e proteger o serviço contra abuso, e medir campanhas de divulgação.
  - purpose: análise de uso e medição de anúncios
    text: medir campanhas de divulgação
  residency:
  - region: União Europeia
    text: Hetzner , hospedagem do site e do banco de dados, em servidores na União Europeia.
  - region: Estados Unidos
    text: Alguns desses operadores processam dados fora do Brasil, em especial nos Estados Unidos e na União Europeia
  retention:
  - period: enquanto a conta existir
    scope: conta
    text: Dados de conta ficam guardados enquanto a conta existir.
  - period: 90 dias
    scope: histórico de consumo MCP
    text: é apagado após 90 dias
  - period: 90 dias
    scope: chamadas da API pública v1
    text: registros de chamadas são apagados após 90 dias
  - period: até 90 dias
    scope: última pergunta antes do vínculo no Telegram
    text: Antes de vincular, guardamos apenas sua última pergunta por até 90 dias para retomá-la após o login.
  - period: no máximo sete dias
    scope: fila técnica Telegram
    text: A fila técnica guarda o conteúdo até o processamento (no máximo sete dias)
  rights:
  - right: confirmação e acesso
    text: você pode confirmar a existência de tratamento, acessar seus dados, corrigir dados incompletos ou desatualizados
  - right: eliminação
    text: pedir a eliminação de dados pessoais tratados com base no seu consentimento
  - right: revogação do consentimento
    text: revogar o consentimento a qualquer momento
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Não vendemos dados pessoais.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: com salvaguardas contratuais de proteção de dados
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cnpj.ai
provenance_date: '2026-11-09'
provider_name: cnpj.ai
provider_slug: cnpj-ai
slug: cnpj-ai-privacy-policy
source_date: '2026-11-09'
source_filename: cnpj-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cnpj.ai/privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cnpj.ai\naid: cnpj-ai\nurl: https://cnpj.ai/privacidade\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Nomes de sócios e administradores são dados pessoais tornados públicos pela própria Receita Federal\n- category: contact\n  text: Ao entrar, coletamos e-mail, nome (quando o login é feito com Google) e o método de login utilizado.\n- category: device\n  text: endereço IP e cabeçalhos da requisição ficam em logs do servidor e da rede de distribuição\n- category: behavioral\n  text: páginas visitadas, cliques e interações, coletados por\
  \ ferramentas de análise e de medição de anúncios\n- category: communication\n  text: guardamos perguntas, respostas, consultas executadas e consumo do modelo no Supabase, associados à sua conta\n- category: communication\n  text: 'Telegram: ao usar @cnpjai_bot, recebemos seu identificador no Telegram, username e mensagens. Não solicitamos\n    telefone.'\n- category: contact\n  text: Recebemos seu telefone ou identificador da Meta e o nome do perfil.\npurposes:\n- purpose: manter o site funcionando e autenticar conta\n  text: Os dados são usados exclusivamente para manter o site funcionando e autenticar sua conta, entender como\n    o produto é usado e melhorá-lo, aplicar limites de uso e proteger o serviço contra abuso, e medir campanhas\n    de divulgação.\n- purpose: análise de uso e medição de anúncios\n  text: medir campanhas de divulgação\nretention:\n- scope: conta\n  period: enquanto a conta existir\n  text: Dados de conta ficam guardados enquanto a conta existir.\n- scope: histórico\
  \ de consumo MCP\n  period: 90 dias\n  text: é apagado após 90 dias\n- scope: chamadas da API pública v1\n  period: 90 dias\n  text: registros de chamadas são apagados após 90 dias\n- scope: última pergunta antes do vínculo no Telegram\n  period: até 90 dias\n  text: Antes de vincular, guardamos apenas sua última pergunta por até 90 dias para retomá-la após o login.\n- scope: fila técnica Telegram\n  period: no máximo sete dias\n  text: A fila técnica guarda o conteúdo até o processamento (no máximo sete dias)\nresidency:\n- region: União Europeia\n  text: Hetzner , hospedagem do site e do banco de dados, em servidores na União Europeia.\n- region: Estados Unidos\n  text: Alguns desses operadores processam dados fora do Brasil, em especial nos Estados Unidos e na União Europeia\ntransfers:\n- mechanism: other\n  text: com salvaguardas contratuais de proteção de dados\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Pedido\
  \ de exclusão da conta ou uso de /desvincular no bot; pedidos ao e-mail de contato\n  text: Ao pedir a exclusão da conta, os dados de conta são apagados e as associações de análise à sua identidade\n    são desfeitas.\nrights:\n- right: confirmação e acesso\n  text: você pode confirmar a existência de tratamento, acessar seus dados, corrigir dados incompletos ou desatualizados\n- right: eliminação\n  text: pedir a eliminação de dados pessoais tratados com base no seu consentimento\n- right: revogação do consentimento\n  text: revogar o consentimento a qualquer momento\nsale_or_sharing:\n  stance: prohibited\n  text: Não vendemos dados pessoais.\n"
source_yaml_url: https://artifacts.apis.io/cnpj-ai/privacy/cnpj-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from cnpj.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Brazil
- CNPJ
- Open Data
- Public Records
- Business Registry
- Compliance
- MCP
---
