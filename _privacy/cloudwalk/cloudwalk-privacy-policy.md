---
api_specs:
- filename: cloudwalk-checkout-links-api-openapi.yml
  format: yaml
  label: CloudWalk Checkout Links API
  slug: cloudwalk-checkout-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-checkout-links-api-openapi.yml
- filename: cloudwalk-infinitepay-checkout-api-api-openapi.yml
  format: yaml
  label: CloudWalk InfinitePay Checkout API
  slug: cloudwalk-infinitepay-checkout-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-infinitepay-checkout-api-api-openapi.yml
- filename: cloudwalk-payments-api-openapi.yml
  format: yaml
  label: CloudWalk Payments API
  slug: cloudwalk-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudwalk/openapi/cloudwalk-payments-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Dados cadastrais: Nome completo, data de nascimento, endereço residencial, nacionalidade, naturalidade, gênero, filiação, estado civil, profissão e números de identificação nacional (CPF, RG)'
  - category: contact
    text: 'Dados de contato: Número de telefone e endereço de e-mail'
  - category: biometric
    text: 'Dados biométricos: Foto facial para análise biométrica (dado pessoal sensível)'
  - category: financial
    text: 'Dados financeiros e transacionais: Número de agência e conta bancária, dados de cartão (número, nome, validade e código de segurança)'
  - category: location
    text: 'Dados de localização: Geolocalização aproximada e fuso horário'
  - category: device
    text: 'Dados de navegação: Data e hora de acesso, informações sobre o dispositivo utilizado, endereço IP e cookies ou tecnologias similares'
  - category: other
    text: 'Dados de histórico jurídico e de sanções: Mandados, ordens judiciais, listas de restrição, processos e histórico PEP (pessoa exposta politicamente)'
  - category: communication
    text: 'Dados de interação: Histórico de mensagens em nossos canais de atendimento (chat, e-mail, telefone)'
  - category: other
    text: 'Dados de conta Google: caso você opte por conectar sua Conta Google aos serviços da InfinitePay, poderemos acessar, conforme a funcionalidade ativada, informações do seu perfil, dados do Google Calendar e dados do Gmail'
  deletion:
    route: provider-initiated when data is no longer needed
    text: Assim que a manutenção dos seus dados deixar de ser necessária ou justificável, seus dados serão eliminados de forma segura ou quando possível anonimizados
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contract execution
    text: Possibilitar a prestação dos serviços contratados por você
  - purpose: legal or regulatory obligation
    text: Atender exigências legais e de órgãos que regulam a atuação de instituições financeiras e de pagamentos
  - purpose: fraud prevention and security
    text: Validar identidade, autenticar acessos, prevenir fraudes em transações
  - purpose: credit protection
    text: Realizar análises relacionadas à concessão de crédito
  - purpose: marketing with consent
    text: promover campanhas e atividades promocionais de marketing
  - purpose: legitimate interests
    text: Apoiar o funcionamento e o desenvolvimento das nossas atividades
  retention:
  - period: null
    scope: personal data generally
    text: A InfinitePay mantém seus dados pessoais apenas pelo tempo necessário para atender às finalidades descritas neste Aviso
  rights:
  - right: access
    text: Permite ao titular solicitar o acesso aos seus dados pessoais
  - right: deletion of data processed with consent
    text: Permite ao titular solicitar a exclusão dos seus dados pessoais sempre que o tratamento tiver como base o consentimento
  - right: portability
    text: Permite ao titular solicitar a portabilidade de seus dados pessoais para outro prestador de serviço
  - right: review of automated decisions
    text: Permite ao titular solicitar a revisão de decisões tomadas unicamente com base em tratamento automatizado de dados, quando estas afetarem seus interesses
  role:
    text: atua, em regra, como controladora dos dados pessoais que coleta
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Atualmente, as transferências são realizadas exclusivamente para os Estados Unidos da América (EUA)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CloudWalk
provenance_date: '2026-11-09'
provider_name: CloudWalk
provider_slug: cloudwalk
slug: cloudwalk-privacy-policy
source_date: '2026-11-09'
source_filename: cloudwalk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.infinitepay.io/legal/aviso-de-privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CloudWalk\naid: cloudwalk\nurl: https://www.infinitepay.io/legal/aviso-de-privacidade\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: atua, em regra, como controladora dos dados pessoais que coleta\ndata_categories:\n- category: identifying\n  text: 'Dados cadastrais: Nome completo, data de nascimento, endereço residencial, nacionalidade, naturalidade,\n    gênero, filiação, estado civil, profissão e números de identificação nacional (CPF, RG)'\n- category: contact\n  text: 'Dados de contato: Número de telefone e endereço de e-mail'\n- category: biometric\n  text: 'Dados biométricos: Foto facial\
  \ para análise biométrica (dado pessoal sensível)'\n- category: financial\n  text: 'Dados financeiros e transacionais: Número de agência e conta bancária, dados de cartão (número, nome, validade\n    e código de segurança)'\n- category: location\n  text: 'Dados de localização: Geolocalização aproximada e fuso horário'\n- category: device\n  text: 'Dados de navegação: Data e hora de acesso, informações sobre o dispositivo utilizado, endereço IP e cookies\n    ou tecnologias similares'\n- category: other\n  text: 'Dados de histórico jurídico e de sanções: Mandados, ordens judiciais, listas de restrição, processos e\n    histórico PEP (pessoa exposta politicamente)'\n- category: communication\n  text: 'Dados de interação: Histórico de mensagens em nossos canais de atendimento (chat, e-mail, telefone)'\n- category: other\n  text: 'Dados de conta Google: caso você opte por conectar sua Conta Google aos serviços da InfinitePay, poderemos\n    acessar, conforme a funcionalidade ativada, informações\
  \ do seu perfil, dados do Google Calendar e dados do Gmail'\npurposes:\n- purpose: contract execution\n  text: Possibilitar a prestação dos serviços contratados por você\n- purpose: legal or regulatory obligation\n  text: Atender exigências legais e de órgãos que regulam a atuação de instituições financeiras e de pagamentos\n- purpose: fraud prevention and security\n  text: Validar identidade, autenticar acessos, prevenir fraudes em transações\n- purpose: credit protection\n  text: Realizar análises relacionadas à concessão de crédito\n- purpose: marketing with consent\n  text: promover campanhas e atividades promocionais de marketing\n- purpose: legitimate interests\n  text: Apoiar o funcionamento e o desenvolvimento das nossas atividades\nretention:\n- scope: personal data generally\n  period: null\n  text: A InfinitePay mantém seus dados pessoais apenas pelo tempo necessário para atender às finalidades descritas\n    neste Aviso\nresidency: []\ntransfers:\n- mechanism: other\n  text:\
  \ Atualmente, as transferências são realizadas exclusivamente para os Estados Unidos da América (EUA)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: provider-initiated when data is no longer needed\n  text: Assim que a manutenção dos seus dados deixar de ser necessária ou justificável, seus dados serão eliminados\n    de forma segura ou quando possível anonimizados\nrights:\n- right: access\n  text: Permite ao titular solicitar o acesso aos seus dados pessoais\n- right: deletion of data processed with consent\n  text: Permite ao titular solicitar a exclusão dos seus dados pessoais sempre que o tratamento tiver como base\n    o consentimento\n- right: portability\n  text: Permite ao titular solicitar a portabilidade de seus dados pessoais para outro prestador de serviço\n- right: review of automated decisions\n  text: Permite ao titular solicitar a revisão de decisões tomadas unicamente com base em tratamento automatizado\n\
  \    de dados, quando estas afetarem seus interesses\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloudwalk/privacy/cloudwalk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 23 quoted statements, read from CloudWalk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Financial Services
- Fintech
- Checkout
- Point-of-Sale
- Acquiring
- Pix
- Brazil
- Banking
- Webhook
- Tap to Pay
---
