---
api_specs:
- filename: brl-accounts-api-openapi.yml
  format: yaml
  label: BRL Accounts API
  slug: brl-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-accounts-api-openapi.yml
- filename: brl-assets-api-openapi.yml
  format: yaml
  label: BRL Assets API
  slug: brl-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-assets-api-openapi.yml
- filename: brl-claims-api-openapi.yml
  format: yaml
  label: BRL Claims API
  slug: brl-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-claims-api-openapi.yml
- filename: brl-nft-transfers-api-openapi.yml
  format: yaml
  label: BRL Nft Transfers API
  slug: brl-nft-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-nft-transfers-api-openapi.yml
- filename: brl-orders-api-openapi.yml
  format: yaml
  label: BRL Orders API
  slug: brl-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-orders-api-openapi.yml
- filename: brl-quotes-api-openapi.yml
  format: yaml
  label: BRL Quotes API
  slug: brl-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-quotes-api-openapi.yml
- filename: brl-tax-exemption-api-openapi.yml
  format: yaml
  label: BRL Tax Exemption API
  slug: brl-tax-exemption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-tax-exemption-api-openapi.yml
- filename: brl-transfers-api-openapi.yml
  format: yaml
  label: BRL Transfers API
  slug: brl-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-transfers-api-openapi.yml
- filename: brl-wallets-api-openapi.yml
  format: yaml
  label: BRL Wallets API
  slug: brl-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-wallets-api-openapi.yml
- filename: brl-withdrawals-api-openapi.yml
  format: yaml
  label: BRL Withdrawals API
  slug: brl-withdrawals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-withdrawals-api-openapi.yml
- filename: brl-crown-api-webhooks-api-openapi.yml
  format: yaml
  label: BRL Crown API & Webhooks API
  slug: brl-crown-api-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brl/openapi/brl-crown-api-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: nome completo, CPF ou CNPJ, data de nascimento, nacionalidade e endereço
  - category: biometric
    text: Coletamos selfie e dados de reconhecimento facial exclusivamente para fins de verificação de identidade e prevenção à fraude
  - category: financial
    text: informações bancárias para depósitos e saques em reais
  - category: location
    text: endereços de carteiras digitais (incluindo carteiras autocustodiadas) e identificadores on-chain
  - category: device
    text: endereço IP, identificadores de dispositivo e tipo de navegador
  - category: behavioral
    text: páginas visitadas e registros de autenticação
  deletion:
    route: e-mail to dpo@crown-brlv.com
    text: Para exercê-los, entre em contato pelo e-mail dpo@crown-brlv.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity verification and fraud prevention
    text: para fins de verificação de identidade e prevenção à fraude no processo de cadastro e autenticação
  - purpose: anti-money-laundering and sanctions screening
    text: Resolução BCB nº 44/2020; Lei nº 13.810/2019
  - purpose: security and analytics cookies
    text: analisar o tráfego da plataforma
  retention:
  - period: 10 anos
    scope: KYC/KYB/KYP and registration data
    text: Cadastro e KYC/KYB/KYP 10 anos após encerramento da relação
  - period: 10 anos
    scope: transaction records
    text: Registros de transações com ativos virtuais 10 anos
  - period: Período necessário à finalidade
    scope: biometric data
    text: Período necessário à finalidade; excluídos após encerramento do vínculo
  - period: 5 anos
    scope: authentication and security logs
    text: Logs de autenticação e segurança 5 anos
  - period: 24 meses
    scope: marketing data with consent
    text: Até revogação do consentimento ou 24 meses
  rights:
  - right: confirmation and access
    text: Confirmação e acesso Saber se tratamos seus dados e receber uma cópia deles.
  - right: correction
    text: Solicitar a correção de dados incompletos, inexatos ou desatualizados.
  - right: deletion
    text: Solicitar a exclusão de dados desnecessários ou tratados sem fundamento legal.
  - right: portability
    text: Receber seus dados em formato estruturado para transferi-los a outro provedor
  - right: revocation of consent
    text: Revogar qualquer consentimento concedido a qualquer momento, sem custo.
  - right: review of automated decisions
    text: Solicitar revisão humana de decisões tomadas exclusivamente por sistemas automatizados
  role:
    text: 'CONTROLLER: Crown Sociedade Prestadora de Ativos Virtuais Ltda. (CNPJ: 59.386.340/0001-45) (“Crown”)'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Compartilhamos seus dados somente quando estritamente necessário e sempre com base em fundamento legal.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: garantimos a adoção das Cláusulas-Padrão Contratuais (SCCs) aprovadas pela ANPD na Resolução CD/ANPD nº 19/2024
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BRL
provenance_date: '2026-11-09'
provider_name: BRL
provider_slug: brl
slug: brl-privacy-policy
source_date: '2026-11-09'
source_filename: brl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://d2bv8dtly8iz1m.cloudfront.net/crown/Crown_PT_Termo_de_Privacidade_27a36188f2.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BRL\naid: brl\nurl: https://d2bv8dtly8iz1m.cloudfront.net/crown/Crown_PT_Termo_de_Privacidade_27a36188f2.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'CONTROLLER: Crown Sociedade Prestadora de Ativos Virtuais Ltda. (CNPJ: 59.386.340/0001-45) (“Crown”)'\ndata_categories:\n- category: identifying\n  text: nome completo, CPF ou CNPJ, data de nascimento, nacionalidade e endereço\n- category: biometric\n  text: Coletamos selfie e dados de reconhecimento facial exclusivamente para fins de verificação de identidade\n    e prevenção à fraude\n- category: financial\n  text: informações bancárias\
  \ para depósitos e saques em reais\n- category: location\n  text: endereços de carteiras digitais (incluindo carteiras autocustodiadas) e identificadores on-chain\n- category: device\n  text: endereço IP, identificadores de dispositivo e tipo de navegador\n- category: behavioral\n  text: páginas visitadas e registros de autenticação\npurposes:\n- purpose: identity verification and fraud prevention\n  text: para fins de verificação de identidade e prevenção à fraude no processo de cadastro e autenticação\n- purpose: anti-money-laundering and sanctions screening\n  text: Resolução BCB nº 44/2020; Lei nº 13.810/2019\n- purpose: security and analytics cookies\n  text: analisar o tráfego da plataforma\nretention:\n- scope: KYC/KYB/KYP and registration data\n  period: 10 anos\n  text: Cadastro e KYC/KYB/KYP 10 anos após encerramento da relação\n- scope: transaction records\n  period: 10 anos\n  text: Registros de transações com ativos virtuais 10 anos\n- scope: biometric data\n  period: Período\
  \ necessário à finalidade\n  text: Período necessário à finalidade; excluídos após encerramento do vínculo\n- scope: authentication and security logs\n  period: 5 anos\n  text: Logs de autenticação e segurança 5 anos\n- scope: marketing data with consent\n  period: 24 meses\n  text: Até revogação do consentimento ou 24 meses\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: garantimos a adoção das Cláusulas-Padrão Contratuais (SCCs) aprovadas pela ANPD na Resolução CD/ANPD nº\n    19/2024\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: e-mail to dpo@crown-brlv.com\n  text: Para exercê-los, entre em contato pelo e-mail dpo@crown-brlv.com\nrights:\n- right: confirmation and access\n  text: Confirmação e acesso Saber se tratamos seus dados e receber uma cópia deles.\n- right: correction\n  text: Solicitar a correção de dados incompletos, inexatos ou desatualizados.\n- right: deletion\n  text: Solicitar a exclusão de dados\
  \ desnecessários ou tratados sem fundamento legal.\n- right: portability\n  text: Receber seus dados em formato estruturado para transferi-los a outro provedor\n- right: revocation of consent\n  text: Revogar qualquer consentimento concedido a qualquer momento, sem custo.\n- right: review of automated decisions\n  text: Solicitar revisão humana de decisões tomadas exclusivamente por sistemas automatizados\nsale_or_sharing:\n  stance: conditional\n  text: Compartilhamos seus dados somente quando estritamente necessário e sempre com base em fundamento legal.\n"
source_yaml_url: https://artifacts.apis.io/brl/privacy/brl-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BRL's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Stablecoins
- Payments
- Brazil
- Pix
- Fintech
- Blockchain
- Digital Assets
- Wallets
- Yield
- Stablecoin Issuance
---
