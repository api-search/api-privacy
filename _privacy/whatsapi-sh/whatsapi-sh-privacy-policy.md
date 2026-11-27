---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Dados de conta: seu e-mail e seu nome, se você informar.'
  - category: financial
    text: Registros de cobrança, pela Stripe.
  - category: behavioral
    text: 'Contadores de medição: quantas mensagens, quando e por chave.'
  - category: communication
    text: 'Um log das mensagens que você envia: para quem foi cada uma, de qual número e se ela saiu.'
  deletion:
    route: account deletion
    text: Apagar sua conta remove suas chaves, seus números e o histórico de conversas deles, seus dados de uso e o log de mensagens.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: 'Para operar o serviço: login, envio, medição, cobrança e prevenção de abuso.'
  - purpose: respond to user requests
    text: Para te atender quando você pedir.
  - purpose: legal obligations
    text: E para cumprir obrigações legais.
  residency:
  - region: United States (us-east-1)
    text: entrega nossos e-mails a partir dos Estados Unidos (região us-east-1 da AWS)
  retention:
  - period: uma semana
    scope: Delivery logs
    text: 'Logs de entrega: cada evento que mandamos para o seu webhook e a resposta que veio, guardados por uma semana.'
  - period: null
    scope: Account data
    text: Guardamos seus dados enquanto sua conta estiver ativa, e apagamos os logs antigos periodicamente.
  rights:
  - right: access, correct, export, delete, object, restrict
    text: Pela LGPD e pelo GDPR, você pode acessar, corrigir, exportar ou apagar seus dados pessoais, e se opor ao tratamento ou restringi-lo.
  role:
    text: é a controladora dos dados descritos aqui
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nunca vendemos dados.
  subprocessors:
    text: Supabase, que hospeda nossas contas e o banco de dados.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: whatsapi-sh
provenance_date: '2026-11-10'
provider_name: whatsapi-sh
provider_slug: whatsapi-sh
slug: whatsapi-sh-privacy-policy
source_date: '2026-11-10'
source_filename: whatsapi-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://whatsapi.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: whatsapi-sh\naid: whatsapi-sh\nurl: https://whatsapi.sh/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: é a controladora dos dados descritos aqui\ndata_categories:\n- category: contact\n  text: 'Dados de conta: seu e-mail e seu nome, se você informar.'\n- category: financial\n  text: Registros de cobrança, pela Stripe.\n- category: behavioral\n  text: 'Contadores de medição: quantas mensagens, quando e por chave.'\n- category: communication\n  text: 'Um log das mensagens que você envia: para quem foi cada uma, de qual número e se ela saiu.'\npurposes:\n- purpose: operate the service\n\
  \  text: 'Para operar o serviço: login, envio, medição, cobrança e prevenção de abuso.'\n- purpose: respond to user requests\n  text: Para te atender quando você pedir.\n- purpose: legal obligations\n  text: E para cumprir obrigações legais.\nretention:\n- scope: Delivery logs\n  period: uma semana\n  text: 'Logs de entrega: cada evento que mandamos para o seu webhook e a resposta que veio, guardados por uma semana.'\n- scope: Account data\n  period: null\n  text: Guardamos seus dados enquanto sua conta estiver ativa, e apagamos os logs antigos periodicamente.\nresidency:\n- region: United States (us-east-1)\n  text: entrega nossos e-mails a partir dos Estados Unidos (região us-east-1 da AWS)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Supabase, que hospeda nossas contas e o banco de dados.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: Apagar sua conta remove suas chaves, seus números e o histórico de conversas deles, seus dados\
  \ de uso e\n    o log de mensagens.\nrights:\n- right: access, correct, export, delete, object, restrict\n  text: Pela LGPD e pelo GDPR, você pode acessar, corrigir, exportar ou apagar seus dados pessoais, e se opor ao\n    tratamento ou restringi-lo.\nsale_or_sharing:\n  stance: prohibited\n  text: Nunca vendemos dados.\n"
source_yaml_url: https://artifacts.apis.io/whatsapi-sh/privacy/whatsapi-sh-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from whatsapi-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- WhatsApp
- Developer Tools
---
