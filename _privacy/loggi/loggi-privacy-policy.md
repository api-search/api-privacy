---
api_specs:
- filename: loggi-detailsapi-api-openapi.yml
  format: yaml
  label: Loggi Details API
  slug: loggi-detailsapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-detailsapi-api-openapi.yml
- filename: loggi-dropofflocationsapi-api-openapi.yml
  format: yaml
  label: Loggi Dropoff Locations API
  slug: loggi-dropofflocationsapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-dropofflocationsapi-api-openapi.yml
- filename: loggi-integratorcompanyapi-api-openapi.yml
  format: yaml
  label: Loggi Integrator Company API
  slug: loggi-integratorcompanyapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-integratorcompanyapi-api-openapi.yml
- filename: loggi-labelapi-api-openapi.yml
  format: yaml
  label: Loggi Label API
  slug: loggi-labelapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-labelapi-api-openapi.yml
- filename: loggi-packagecancelapi-api-openapi.yml
  format: yaml
  label: Loggi Package Cancel API
  slug: loggi-packagecancelapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-packagecancelapi-api-openapi.yml
- filename: loggi-packageupdateapi-api-openapi.yml
  format: yaml
  label: Loggi Package Update API
  slug: loggi-packageupdateapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-packageupdateapi-api-openapi.yml
- filename: loggi-quotationapi-api-openapi.yml
  format: yaml
  label: Loggi Quotation API
  slug: loggi-quotationapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-quotationapi-api-openapi.yml
- filename: loggi-shipmentapi-api-openapi.yml
  format: yaml
  label: Loggi Shipment API
  slug: loggi-shipmentapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-shipmentapi-api-openapi.yml
- filename: loggi-trackingapi-api-openapi.yml
  format: yaml
  label: Loggi Tracking API
  slug: loggi-trackingapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-trackingapi-api-openapi.yml
- filename: loggi-oauth2token-api-openapi.yml
  format: yaml
  label: Loggi O Auth2 Token API
  slug: loggi-oauth2token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loggi/openapi/loggi-oauth2token-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nome completo; Assinatura; Data de nascimento; Nacionalidade
  - category: contact
    text: Endereço de e-mail
  - category: financial
    text: Informações bancárias e financeiras, incluindo dados de cartão de crédito
  - category: location
    text: Dados de geolocalização durante a utilização do Aplicativo
  - category: device
    text: Informações técnicas, como seu endereço de IP, identificação de dispositivo, dados de localização (baseados no seu IP), informações sobre cookies
  - category: behavioral
    text: Para avaliar os comportamentos de navegação e o perfil dos Clientes por meio cookies próprios
  - category: communication
    text: Comunicação, verbal ou escrita, mantida entre o Cliente e a Loggi.
  deletion:
    route: Solicitação pelo canal de direitos do titular
    text: Apagamento ou anonimização dos dados pessoais tratados com base no seu consentimento, exceto quando a lei autorizar a manutenção destes dados por outro fundamento
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Prestação dos serviços
    text: Para permitir a prestação dos serviços oferecidos pela Loggi, realização de cadastro, viabilização de transações, permissão e viabilidade de execução de contratos
  - purpose: Marketing and advertising
    text: Para fins de marketing e publicidade dos serviços da Loggi, incluindo publicidade direcionada conforme perfil de comportamento, consumo e/ou localização
  - purpose: Fraud prevention
    text: Para a realização de atividades de prevenção contra fraude e atividades ilícitas, incluindo medidas para proteção da Loggi, de Clientes e/ou de terceiros
  residency:
  - region: Brazil or abroad
    text: A Loggi poderá armazenar ou tratar dados pessoais por meio de provedores de serviços de computação em nuvem e outros fornecedores que possuam infraestrutura localizada no Brasil ou no exterior.
  rights:
  - right: Acesso
    text: Acesso aos dados pessoais
  - right: Correção
    text: Correção de dados pessoais incompletos, inexatos ou desatualizados
  - right: Portabilidade
    text: Portabilidade dos dados pessoais para outro fornecedor de um serviço ou produto, sujeito à regulamentação da autoridade nacional
  - right: Revogação do consentimento
    text: Revogação seu consentimento, quando o tratamento tenha sido feito com base no consentimento do titular.
  role:
    text: De maneira geral, a Loggi é o controlador dos dados pessoais e toma as decisões de tratamento de dados pessoais nos termos do presente Aviso de Privacidade.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Sempre que houver transferência internacional de dados pessoais, a Loggi adotará as medidas contratuais, técnicas e organizacionais necessárias para garantir a proteção dos dados
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Loggi
provenance_date: '2026-11-09'
provider_name: Loggi
provider_slug: loggi
slug: loggi-privacy-policy
source_date: '2026-11-09'
source_filename: loggi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.loggi.com/aviso-privacidade-clientes/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Loggi\naid: loggi\nurl: https://www.loggi.com/aviso-privacidade-clientes/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: De maneira geral, a Loggi é o controlador dos dados pessoais e toma as decisões de tratamento de dados pessoais\n    nos termos do presente Aviso de Privacidade.\ndata_categories:\n- category: identifying\n  text: Nome completo; Assinatura; Data de nascimento; Nacionalidade\n- category: contact\n  text: Endereço de e-mail\n- category: financial\n  text: Informações bancárias e financeiras, incluindo dados de cartão de crédito\n- category: location\n  text: Dados de geolocalização\
  \ durante a utilização do Aplicativo\n- category: device\n  text: Informações técnicas, como seu endereço de IP, identificação de dispositivo, dados de localização (baseados\n    no seu IP), informações sobre cookies\n- category: behavioral\n  text: Para avaliar os comportamentos de navegação e o perfil dos Clientes por meio cookies próprios\n- category: communication\n  text: Comunicação, verbal ou escrita, mantida entre o Cliente e a Loggi.\npurposes:\n- purpose: Prestação dos serviços\n  text: Para permitir a prestação dos serviços oferecidos pela Loggi, realização de cadastro, viabilização de transações,\n    permissão e viabilidade de execução de contratos\n- purpose: Marketing and advertising\n  text: Para fins de marketing e publicidade dos serviços da Loggi, incluindo publicidade direcionada conforme perfil\n    de comportamento, consumo e/ou localização\n- purpose: Fraud prevention\n  text: Para a realização de atividades de prevenção contra fraude e atividades ilícitas, incluindo\
  \ medidas para\n    proteção da Loggi, de Clientes e/ou de terceiros\nretention: []\nresidency:\n- region: Brazil or abroad\n  text: A Loggi poderá armazenar ou tratar dados pessoais por meio de provedores de serviços de computação em nuvem\n    e outros fornecedores que possuam infraestrutura localizada no Brasil ou no exterior.\ntransfers:\n- mechanism: other\n  text: Sempre que houver transferência internacional de dados pessoais, a Loggi adotará as medidas contratuais,\n    técnicas e organizacionais necessárias para garantir a proteção dos dados\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Solicitação pelo canal de direitos do titular\n  text: Apagamento ou anonimização dos dados pessoais tratados com base no seu consentimento, exceto quando a lei\n    autorizar a manutenção destes dados por outro fundamento\nrights:\n- right: Acesso\n  text: Acesso aos dados pessoais\n- right: Correção\n  text: Correção de dados\
  \ pessoais incompletos, inexatos ou desatualizados\n- right: Portabilidade\n  text: Portabilidade dos dados pessoais para outro fornecedor de um serviço ou produto, sujeito à regulamentação\n    da autoridade nacional\n- right: Revogação do consentimento\n  text: Revogação seu consentimento, quando o tratamento tenha sido feito com base no consentimento do titular.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loggi/privacy/loggi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Loggi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Last Mile Delivery
- Freight
- Tracking
- Brazil
---
