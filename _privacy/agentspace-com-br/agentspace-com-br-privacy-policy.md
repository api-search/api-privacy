---
api_specs:
- filename: agentspace-com-br-account-api-openapi.yml
  format: yaml
  label: AgentSpace Account API
  slug: agentspace-com-br-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-account-api-openapi.yml
- filename: agentspace-com-br-agent-api-openapi.yml
  format: yaml
  label: AgentSpace Agent API
  slug: agentspace-com-br-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-agent-api-openapi.yml
- filename: agentspace-com-br-billing-api-openapi.yml
  format: yaml
  label: AgentSpace Billing API
  slug: agentspace-com-br-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-billing-api-openapi.yml
- filename: agentspace-com-br-review-api-openapi.yml
  format: yaml
  label: AgentSpace Review API
  slug: agentspace-com-br-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentspace-com-br/openapi/agentspace-com-br-review-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Cadastro: nome de usuário, e-mail e senha.'
  - category: contact
    text: 'Suporte: o nome, o contato e as mensagens que você nos envia pelo suporte'
  - category: communication
    text: 'Suporte: o nome, o contato e as mensagens que você nos envia pelo suporte, e as nossas respostas, guardados para te atender.'
  - category: behavioral
    text: 'Uso: quando a conta foi criada, quando foi usada pela última vez, quando algo foi publicado pela primeira vez, quanto tempo de execução foi consumido, e quais páginas e serviços estão publicados.'
  - category: device
    text: 'Registros de acesso: a cada acesso ao serviço, a data e a hora, o endereço IP, o endereço acessado e, quando você está conectado, qual é a sua conta.'
  - category: financial
    text: 'Pagamento: identificadores de cliente e de assinatura na Stripe.'
  - category: other
    text: 'Conteúdo: os arquivos que você e os seus agentes colocam no seu espaço, e a saída das execuções de código.'
  deletion:
    route: Apagar a conta pelo painel; pedidos pelo e-mail de privacidade
    text: Quando você apaga a conta, tudo é removido na hora do sistema, e das cópias de segurança em até 14 dias
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Prestar o serviço contratado
    text: Prestar o serviço que você contratou — manter sua conta, guardar e publicar seu conteúdo, executar seu código e aplicar os limites do plano
  - purpose: Segurança e prevenção de abuso
    text: Segurança e prevenção de abuso — registros de acesso, limites de tentativas e investigação de denúncias
  - purpose: Entender o que funciona
    text: Entender o que funciona — de qual campanha vêm os cadastros e quantos chegam a publicar algo, em números agregados
  - purpose: Cobrança
    text: Cobrança — execução de contrato e cumprimento de obrigações fiscais.
  residency:
  - region: Canadá
    text: OVHcloud — onde ficam os servidores, localizados em Canadá.
  retention:
  - period: enquanto a conta existir
    scope: Conta e conteúdo
    text: 'Conta e conteúdo: enquanto a conta existir.'
  - period: até 14 dias
    scope: Cópias de segurança após exclusão da conta
    text: das cópias de segurança em até 14 dias
  - period: 6 meses
    scope: Registros de acesso
    text: 'Registros de acesso: 6 meses, como exige o art. 15 do Marco Civil da Internet, sob sigilo, e então apagados automaticamente.'
  - period: 6 horas
    scope: Rascunhos de publicação
    text: 'Rascunhos de publicação: 6 horas.'
  - period: pelo prazo exigido pela legislação fiscal
    scope: Registros de cobrança
    text: 'Registros de cobrança: pelo prazo exigido pela legislação fiscal.'
  rights:
  - right: Confirmação e acesso
    text: confirmar se tratamos seus dados e acessá-los
  - right: Correção
    text: corrigi-los
  - right: Anonimização, bloqueio ou eliminação
    text: pedir anonimização, bloqueio ou eliminação
  - right: Portabilidade
    text: levar seus dados para outro serviço
  - right: Informação sobre compartilhamento
    text: saber com quem os compartilhamos
  - right: Oposição
    text: se opor a um tratamento
  role:
    text: 57.143.095 INOVA SIMPLES (I.S.) (CNPJ 57.143.095/0001-10) é o controlador dos dados pessoais tratados no AgentSpace.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Não vendemos seus dados
  subprocessors:
    text: 'Somente com quem é necessário para o serviço funcionar: OVHcloud — onde ficam os servidores, localizados em Canadá. Cloudflare — rede, DNS, proteção e certificados: o tráfego do site passa por ela. Stripe — processamento de pagamentos. Google — quando você escolhe entrar com o Google, o login acontece lá.'
    url: null
  transfers:
  - mechanism: other
    text: Essa transferência é necessária para prestar o serviço que você contratou (art. 33, IX, da LGPD).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentSpace
provenance_date: '2026-11-09'
provider_name: AgentSpace
provider_slug: agentspace-com-br
slug: agentspace-com-br-privacy-policy
source_date: '2026-11-09'
source_filename: agentspace-com-br-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentspace.com.br/privacidade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentSpace\naid: agentspace-com-br\nurl: https://agentspace.com.br/privacidade\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 57.143.095 INOVA SIMPLES (I.S.) (CNPJ 57.143.095/0001-10) é o controlador dos dados pessoais tratados no\n    AgentSpace.\ndata_categories:\n- category: identifying\n  text: 'Cadastro: nome de usuário, e-mail e senha.'\n- category: contact\n  text: 'Suporte: o nome, o contato e as mensagens que você nos envia pelo suporte'\n- category: communication\n  text: 'Suporte: o nome, o contato e as mensagens que você nos envia pelo suporte, e as nossas respostas, guardados\n\
  \    para te atender.'\n- category: behavioral\n  text: 'Uso: quando a conta foi criada, quando foi usada pela última vez, quando algo foi publicado pela primeira\n    vez, quanto tempo de execução foi consumido, e quais páginas e serviços estão publicados.'\n- category: device\n  text: 'Registros de acesso: a cada acesso ao serviço, a data e a hora, o endereço IP, o endereço acessado e, quando\n    você está conectado, qual é a sua conta.'\n- category: financial\n  text: 'Pagamento: identificadores de cliente e de assinatura na Stripe.'\n- category: other\n  text: 'Conteúdo: os arquivos que você e os seus agentes colocam no seu espaço, e a saída das execuções de código.'\npurposes:\n- purpose: Prestar o serviço contratado\n  text: Prestar o serviço que você contratou — manter sua conta, guardar e publicar seu conteúdo, executar seu código\n    e aplicar os limites do plano\n- purpose: Segurança e prevenção de abuso\n  text: Segurança e prevenção de abuso — registros de acesso, limites\
  \ de tentativas e investigação de denúncias\n- purpose: Entender o que funciona\n  text: Entender o que funciona — de qual campanha vêm os cadastros e quantos chegam a publicar algo, em números\n    agregados\n- purpose: Cobrança\n  text: Cobrança — execução de contrato e cumprimento de obrigações fiscais.\nretention:\n- scope: Conta e conteúdo\n  period: enquanto a conta existir\n  text: 'Conta e conteúdo: enquanto a conta existir.'\n- scope: Cópias de segurança após exclusão da conta\n  period: até 14 dias\n  text: das cópias de segurança em até 14 dias\n- scope: Registros de acesso\n  period: 6 meses\n  text: 'Registros de acesso: 6 meses, como exige o art. 15 do Marco Civil da Internet, sob sigilo, e então apagados\n    automaticamente.'\n- scope: Rascunhos de publicação\n  period: 6 horas\n  text: 'Rascunhos de publicação: 6 horas.'\n- scope: Registros de cobrança\n  period: pelo prazo exigido pela legislação fiscal\n  text: 'Registros de cobrança: pelo prazo exigido pela legislação\
  \ fiscal.'\nresidency:\n- region: Canadá\n  text: OVHcloud — onde ficam os servidores, localizados em Canadá.\ntransfers:\n- mechanism: other\n  text: Essa transferência é necessária para prestar o serviço que você contratou (art. 33, IX, da LGPD).\nsubprocessors:\n  url: null\n  text: 'Somente com quem é necessário para o serviço funcionar: OVHcloud — onde ficam os servidores, localizados\n    em Canadá. Cloudflare — rede, DNS, proteção e certificados: o tráfego do site passa por ela. Stripe — processamento\n    de pagamentos. Google — quando você escolhe entrar com o Google, o login acontece lá.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Apagar a conta pelo painel; pedidos pelo e-mail de privacidade\n  text: Quando você apaga a conta, tudo é removido na hora do sistema, e das cópias de segurança em até 14 dias\nrights:\n- right: Confirmação e acesso\n  text: confirmar se tratamos seus dados e acessá-los\n- right: Correção\n  text: corrigi-los\n- right:\
  \ Anonimização, bloqueio ou eliminação\n  text: pedir anonimização, bloqueio ou eliminação\n- right: Portabilidade\n  text: levar seus dados para outro serviço\n- right: Informação sobre compartilhamento\n  text: saber com quem os compartilhamos\n- right: Oposição\n  text: se opor a um tratamento\nsale_or_sharing:\n  stance: prohibited\n  text: Não vendemos seus dados\n"
source_yaml_url: https://artifacts.apis.io/agentspace-com-br/privacy/agentspace-com-br-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AgentSpace's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Workspace
- Sandbox
- Hosting
---
