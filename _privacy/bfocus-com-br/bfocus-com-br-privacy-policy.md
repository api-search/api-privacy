---
api_specs:
- filename: bfocus-com-br-openapi.json
  format: json
  label: bFocus API
  slug: bfocus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bfocus-com-br/openapi/bfocus-com-br-openapi.json
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Conta: nome, e-mail, telefone (opcional), idioma preferido.'
  - category: device
    text: 'Uso: registros de auditoria (quem fez o quê e quando) e o IP de acesso, usado para segurança e limites de uso.'
  - category: other
    text: 'Conteúdo: tickets, projetos, tarefas, clientes e anexos que você cria.'
  deletion:
    route: request to company administrator or email
    text: Para excluir a conta e os dados pessoais, peça a quem administra o bFocus na sua empresa ou escreva para [email protected] informando o e-mail de acesso.
  dpa:
    available: true
    text: Provedores essenciais (DigitalOcean, Mailgun, Firebase e Stripe, este só para a cobrança) sob NDA + DPA.
    url: null
  purposes:
  - purpose: service provision
    text: Fornecer o serviço contratado (chamados, projetos e cadastro de clientes).
  - purpose: audit and security
    text: Auditoria e segurança (os registros ficam enquanto a conta existir).
  - purpose: ad measurement
    text: A finalidade é medir quais anúncios trazem gente interessada e mostrar o bFocus a quem procura algo parecido.
  residency:
  - region: United States (São Francisco, sfo3)
    text: Servidores DigitalOcean nos Estados Unidos, região de São Francisco (sfo3), com replicação.
  retention:
  - period: enquanto a conta existir
    scope: audit records
    text: Auditoria e segurança (os registros ficam enquanto a conta existir).
  - period: 90 dias
    scope: anonymous visitor record
    text: O registro é apagado em 90 dias.
  - period: uma hora
    scope: AI connector access
    text: 'Retenção: o acesso vale uma hora e se renova enquanto a conexão existir'
  rights:
  - right: access
    text: Solicitar acesso a todos os seus dados.
  - right: correction or deletion
    text: Solicitar correção ou exclusão.
  - right: portability
    text: Exportar os seus dados pessoais em formato aberto (JSON), mediante solicitação.
  - right: revoke consent
    text: Revogar consentimento a qualquer momento.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Não vendemos dados.
  subprocessors:
    text: Provedores essenciais (DigitalOcean, Mailgun, Firebase e Stripe, este só para a cobrança) sob NDA + DPA.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bFocus
provenance_date: '2026-11-09'
provider_name: bFocus
provider_slug: bfocus-com-br
slug: bfocus-com-br-privacy-policy
source_date: '2026-11-09'
source_filename: bfocus-com-br-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bfocus.com.br/privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bFocus\naid: bfocus-com-br\nurl: https://www.bfocus.com.br/privacidade\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Conta: nome, e-mail, telefone (opcional), idioma preferido.'\n- category: device\n  text: 'Uso: registros de auditoria (quem fez o quê e quando) e o IP de acesso, usado para segurança e limites\n    de uso.'\n- category: other\n  text: 'Conteúdo: tickets, projetos, tarefas, clientes e anexos que você cria.'\npurposes:\n- purpose: service provision\n  text: Fornecer o serviço contratado (chamados, projetos e cadastro de clientes).\n\
  - purpose: audit and security\n  text: Auditoria e segurança (os registros ficam enquanto a conta existir).\n- purpose: ad measurement\n  text: A finalidade é medir quais anúncios trazem gente interessada e mostrar o bFocus a quem procura algo parecido.\nretention:\n- scope: audit records\n  period: enquanto a conta existir\n  text: Auditoria e segurança (os registros ficam enquanto a conta existir).\n- scope: anonymous visitor record\n  period: 90 dias\n  text: O registro é apagado em 90 dias.\n- scope: AI connector access\n  period: uma hora\n  text: 'Retenção: o acesso vale uma hora e se renova enquanto a conexão existir'\nresidency:\n- region: United States (São Francisco, sfo3)\n  text: Servidores DigitalOcean nos Estados Unidos, região de São Francisco (sfo3), com replicação.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Provedores essenciais (DigitalOcean, Mailgun, Firebase e Stripe, este só para a cobrança) sob NDA + DPA.\ndpa:\n  available: true\n  url: null\n  text: Provedores\
  \ essenciais (DigitalOcean, Mailgun, Firebase e Stripe, este só para a cobrança) sob NDA + DPA.\ndeletion:\n  route: request to company administrator or email\n  text: Para excluir a conta e os dados pessoais, peça a quem administra o bFocus na sua empresa ou escreva para\n    [email protected] informando o e-mail de acesso.\nrights:\n- right: access\n  text: Solicitar acesso a todos os seus dados.\n- right: correction or deletion\n  text: Solicitar correção ou exclusão.\n- right: portability\n  text: Exportar os seus dados pessoais em formato aberto (JSON), mediante solicitação.\n- right: revoke consent\n  text: Revogar consentimento a qualquer momento.\nsale_or_sharing:\n  stance: prohibited\n  text: Não vendemos dados.\n"
source_yaml_url: https://artifacts.apis.io/bfocus-com-br/privacy/bfocus-com-br-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from bFocus's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Lead Management
- Customer Service
- Software-as-a-Service
- Brazil
---
