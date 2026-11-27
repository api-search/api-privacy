---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'dados de identidade e documento: CPF, data de nascimento, nome civil, situação cadastral'
  - category: biometric
    text: 'dados biométricos e prova de vida: selfie, vídeo ou frames, face match, liveness'
  - category: location
    text: 'dados de localização e de endereço: o CEP e o endereço informados (como rua, bairro, cidade e estado)'
  - category: device
    text: dados técnicos do aparelho e do aplicativo
  - category: other
    text: antecedentes criminais (esfera federal e estadual)
  - category: communication
    text: 'dados de comunicação: mensagens de chat, áudios, imagens, anexos'
  deletion:
    route: account deletion; privacy channels
    text: A exclusão da conta encerra definitivamente o acesso e implica banimento permanente
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: criar e manter contas
    text: criar, autenticar e manter contas
  - purpose: validar identidade
    text: validar identidade de famílias e babás
  - purpose: marketing
    text: enviar comunicações de produto, conteúdo educativo, novidades, ofertas, pesquisas, reengajamento e marketing relacionado à Babá Certa para usuários cadastrados
  - purpose: divulgação e medição
    text: divulgar a Babá Certa, inclusive com anúncios personalizados em outras plataformas
  - purpose: obrigações legais
    text: cumprir obrigações legais, regulatórias, fiscais e exercer direitos em processos administrativos ou judiciais.
  residency:
  - region: Brasil
    text: A infraestrutura primária e o banco de dados da Babá Certa ficam no Brasil (Google Cloud, região southamerica-east1).
  retention:
  - period: até 24 meses
    scope: telemetria de diagnóstico
    text: em regra, até 24 meses, inclusive no export para o Google BigQuery (seção 11)
  - period: até 24 meses
    scope: endereço de IP de acesso
    text: Esse endereço de IP é conservado por até 24 meses a partir do último acesso
  - period: até 10 anos
    scope: dados de identificação e verificação de famílias e babás
    text: em regra, por até 10 anos após o encerramento da relação
  rights:
  - right: confirmação, acesso, correção, eliminação, portabilidade
    text: Você pode solicitar confirmação de tratamento, acesso, correção, informação sobre compartilhamento, anonimização, bloqueio, eliminação, portabilidade
  - right: oposição e revogação
    text: oposição a tratamento por legítimo interesse, descadastro de marketing, revogação de consentimento e revisão de decisões automatizadas
  role:
    text: A Volke Ideias Digitais Ltda. é a controladora dos dados pessoais tratados para operação da Babá Certa.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Twilio — envio de SMS (código de verificação por telefone)
    url: null
  transfers:
  - mechanism: SCC
    text: Com cláusulas contratuais padrão aprovadas pela ANPD (Resolução CD/ANPD nº 19/2024)
  - mechanism: other
    text: Com base no consentimento específico da titular para a verificação e na necessidade de execução da verificação contratada (LGPD, art. 33, VIII e IX)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Babá Certa
provenance_date: '2026-11-09'
provider_name: Babá Certa
provider_slug: babacerta-com-br
slug: babacerta-com-br-privacy-policy
source_date: '2026-11-09'
source_filename: babacerta-com-br-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://babacerta.com.br/politica-privacidade/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Babá Certa\naid: babacerta-com-br\nurl: https://babacerta.com.br/politica-privacidade/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: A Volke Ideias Digitais Ltda. é a controladora dos dados pessoais tratados para operação da Babá Certa.\ndata_categories:\n- category: identifying\n  text: 'dados de identidade e documento: CPF, data de nascimento, nome civil, situação cadastral'\n- category: biometric\n  text: 'dados biométricos e prova de vida: selfie, vídeo ou frames, face match, liveness'\n- category: location\n  text: 'dados de localização e de endereço: o CEP e o endereço informados (como\
  \ rua, bairro, cidade e estado)'\n- category: device\n  text: dados técnicos do aparelho e do aplicativo\n- category: other\n  text: antecedentes criminais (esfera federal e estadual)\n- category: communication\n  text: 'dados de comunicação: mensagens de chat, áudios, imagens, anexos'\npurposes:\n- purpose: criar e manter contas\n  text: criar, autenticar e manter contas\n- purpose: validar identidade\n  text: validar identidade de famílias e babás\n- purpose: marketing\n  text: enviar comunicações de produto, conteúdo educativo, novidades, ofertas, pesquisas, reengajamento e marketing\n    relacionado à Babá Certa para usuários cadastrados\n- purpose: divulgação e medição\n  text: divulgar a Babá Certa, inclusive com anúncios personalizados em outras plataformas\n- purpose: obrigações legais\n  text: cumprir obrigações legais, regulatórias, fiscais e exercer direitos em processos administrativos ou judiciais.\nretention:\n- scope: telemetria de diagnóstico\n  period: até 24 meses\n \
  \ text: em regra, até 24 meses, inclusive no export para o Google BigQuery (seção 11)\n- scope: endereço de IP de acesso\n  period: até 24 meses\n  text: Esse endereço de IP é conservado por até 24 meses a partir do último acesso\n- scope: dados de identificação e verificação de famílias e babás\n  period: até 10 anos\n  text: em regra, por até 10 anos após o encerramento da relação\nresidency:\n- region: Brasil\n  text: A infraestrutura primária e o banco de dados da Babá Certa ficam no Brasil (Google Cloud, região southamerica-east1).\ntransfers:\n- mechanism: SCC\n  text: Com cláusulas contratuais padrão aprovadas pela ANPD (Resolução CD/ANPD nº 19/2024)\n- mechanism: other\n  text: Com base no consentimento específico da titular para a verificação e na necessidade de execução da verificação\n    contratada (LGPD, art. 33, VIII e IX)\nsubprocessors:\n  url: null\n  text: Twilio — envio de SMS (código de verificação por telefone)\ndpa:\n  available: null\n  url: null\n  text: null\n\
  deletion:\n  route: account deletion; privacy channels\n  text: A exclusão da conta encerra definitivamente o acesso e implica banimento permanente\nrights:\n- right: confirmação, acesso, correção, eliminação, portabilidade\n  text: Você pode solicitar confirmação de tratamento, acesso, correção, informação sobre compartilhamento, anonimização,\n    bloqueio, eliminação, portabilidade\n- right: oposição e revogação\n  text: oposição a tratamento por legítimo interesse, descadastro de marketing, revogação de consentimento e revisão\n    de decisões automatizadas\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/babacerta-com-br/privacy/babacerta-com-br-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Babá Certa's own page on 2026-11-09.
synthetic: false
tags:
- Babysitting
- Marketplace
- Verification
- Brazil
- Childcare
---
