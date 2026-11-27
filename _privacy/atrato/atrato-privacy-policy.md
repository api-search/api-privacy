---
api_specs:
- filename: atrato-ecommerce-api-openapi.yml
  format: yaml
  label: Atrato Ecommerce API
  slug: atrato-ecommerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atrato/openapi/atrato-ecommerce-api-openapi.yml
- filename: atrato-integration-api-openapi.yml
  format: yaml
  label: Atrato Integration API
  slug: atrato-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atrato/openapi/atrato-integration-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Datos de Identificación: Nombre Completo Edad Estado Civil'
  - category: contact
    text: Datos de Contacto Teléfono Correo electrónico
  - category: financial
    text: Datos Económicos y Financieros Ingresos Gastos Dependientes
  - category: biometric
    text: 5. Datos Biométricos
  - category: professional
    text: 3. Datos de Laborales Nivel de Estudios Ocupación Tiempo Laborando
  deletion:
    route: Solicitud de Derecho de Cancelación por formulario o correo
    text: 'Derecho de Cancelación: Derecho a solicitar a ATRATO la eliminación, supresión o borrado de los Datos Personales del Titular'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Evaluación de perfil de riesgo y capacidad crediticia
    text: 4) Evaluación del perfil de riesgo y capacidad crediticia del Titular, así como la evaluación del riesgo inherente del Crédito.
  - purpose: Validación y verificación de datos
    text: 2) Validar y verificar los Datos Personales del Titular.
  - purpose: Envío de promociones y publicidad
    text: b) Envío de promociones y publicidad a favor del Titular, de nuevos productos y servicios que pudieran ser de su interés.
  rights:
  - right: Acceso
    text: 'Derecho de Acceso: Derecho a conocer qué Datos Personales están en posesión de ATRATO, para qué finalidad y las condiciones del Tratamiento'
  - right: Rectificación
    text: Derecho a solicitar la actualización, modificación y corrección de sus Datos Personales
  - right: Oposición
    text: Derecho que puede ejercer el Titular de los Datos Personales para que ATRATO suspenda su tratamiento
  - right: Revocación del consentimiento
    text: el Titular, en cualquier momento, podrá revocar su consentimiento para el tratamiento de sus Datos Personales
  role:
    text: ATRATO será el Responsable en términos de la Ley de Datos Personales
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: ATRATO podrá realizar transferencias nacionales o internacionales de los Datos Personales del Titular, sin requerir de su consentimiento previo
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atrato
provenance_date: '2026-11-09'
provider_name: Atrato
provider_slug: atrato
slug: atrato-privacy-policy
source_date: '2026-11-09'
source_filename: atrato-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://s3.us-west-2.amazonaws.com/cdn.atratopago.com/Aviso+de+Privacidad+Atrato+Technologies.+2026.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atrato\naid: atrato\nurl: https://s3.us-west-2.amazonaws.com/cdn.atratopago.com/Aviso+de+Privacidad+Atrato+Technologies.+2026.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ATRATO será el Responsable en términos de la Ley de Datos Personales\ndata_categories:\n- category: identifying\n  text: 'Datos de Identificación: Nombre Completo Edad Estado Civil'\n- category: contact\n  text: Datos de Contacto Teléfono Correo electrónico\n- category: financial\n  text: Datos Económicos y Financieros Ingresos Gastos Dependientes\n- category: biometric\n  text: 5. Datos Biométricos\n- category: professional\n\
  \  text: 3. Datos de Laborales Nivel de Estudios Ocupación Tiempo Laborando\npurposes:\n- purpose: Evaluación de perfil de riesgo y capacidad crediticia\n  text: 4) Evaluación del perfil de riesgo y capacidad crediticia del Titular, así como la evaluación del riesgo\n    inherente del Crédito.\n- purpose: Validación y verificación de datos\n  text: 2) Validar y verificar los Datos Personales del Titular.\n- purpose: Envío de promociones y publicidad\n  text: b) Envío de promociones y publicidad a favor del Titular, de nuevos productos y servicios que pudieran ser\n    de su interés.\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: ATRATO podrá realizar transferencias nacionales o internacionales de los Datos Personales del Titular, sin\n    requerir de su consentimiento previo\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Solicitud de Derecho de Cancelación por formulario o correo\n  text: 'Derecho\
  \ de Cancelación: Derecho a solicitar a ATRATO la eliminación, supresión o borrado de los Datos Personales\n    del Titular'\nrights:\n- right: Acceso\n  text: 'Derecho de Acceso: Derecho a conocer qué Datos Personales están en posesión de ATRATO, para qué finalidad\n    y las condiciones del Tratamiento'\n- right: Rectificación\n  text: Derecho a solicitar la actualización, modificación y corrección de sus Datos Personales\n- right: Oposición\n  text: Derecho que puede ejercer el Titular de los Datos Personales para que ATRATO suspenda su tratamiento\n- right: Revocación del consentimiento\n  text: el Titular, en cualquier momento, podrá revocar su consentimiento para el tratamiento de sus Datos Personales\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atrato/privacy/atrato-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- transfers
- deletion
- rights
summary_line: 15 quoted statements, read from Atrato's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Buy Now Pay Later
- Lending
- Mexico
- Point-of-Sale
- E-Commerce
---
