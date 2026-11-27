---
api_specs:
- filename: culqi-cards-api-openapi.yml
  format: yaml
  label: Culqi Cards API
  slug: culqi-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-cards-api-openapi.yml
- filename: culqi-charges-api-openapi.yml
  format: yaml
  label: Culqi Charges API
  slug: culqi-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-charges-api-openapi.yml
- filename: culqi-customers-api-openapi.yml
  format: yaml
  label: Culqi Customers API
  slug: culqi-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-customers-api-openapi.yml
- filename: culqi-events-api-openapi.yml
  format: yaml
  label: Culqi Events API
  slug: culqi-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-events-api-openapi.yml
- filename: culqi-iins-api-openapi.yml
  format: yaml
  label: Culqi Iins API
  slug: culqi-iins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-iins-api-openapi.yml
- filename: culqi-orders-api-openapi.yml
  format: yaml
  label: Culqi Orders API
  slug: culqi-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-orders-api-openapi.yml
- filename: culqi-plans-api-openapi.yml
  format: yaml
  label: Culqi Plans API
  slug: culqi-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-plans-api-openapi.yml
- filename: culqi-refunds-api-openapi.yml
  format: yaml
  label: Culqi Refunds API
  slug: culqi-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-refunds-api-openapi.yml
- filename: culqi-subscriptions-api-openapi.yml
  format: yaml
  label: Culqi Subscriptions API
  slug: culqi-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-subscriptions-api-openapi.yml
- filename: culqi-tokens-api-openapi.yml
  format: yaml
  label: Culqi Tokens API
  slug: culqi-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-tokens-api-openapi.yml
- filename: culqi-transfers-api-openapi.yml
  format: yaml
  label: Culqi Transfers API
  slug: culqi-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-transfers-api-openapi.yml
- filename: culqi-3-ds-api-openapi.yml
  format: yaml
  label: Culqi 3 DS API
  slug: culqi-3-ds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/culqi/openapi/culqi-3-ds-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nombre, dirección de correo electrónico, información de contacto físico, fecha de nacimiento
  - category: financial
    text: datos financieros, como el número de tarjeta de crédito o cuenta bancaria, código de verificación, dirección de facturación
  - category: biometric
    text: Almacenaremos y trataremos tus datos biométricos faciales y dactilares
  - category: device
    text: el modelo y Sistema operativo del dispositivo móvil usado y la versión del navegador
  - category: communication
    text: Discusiones, conversaciones y correspondencia con comercios afiliados
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services requested
    text: Proporcionar los servicios y la atención que el Titular de Datos Personales solicite.
  - purpose: prevent illegal activities
    text: Impedir actividades potencialmente prohibidas o ilegales
  - purpose: personalize and improve service
    text: Personalizar, cuantificar y mejorar el Servicio.
  - purpose: marketing
    text: realizar acciones de marketing segmentado, actualizaciones de servicios y ofertas promocionales
  residency:
  - region: United States
    text: La información personal se almacena en los servidores de la Empresa ubicados en Estados Unidos.
  retention:
  - period: 10 años
    scope: registered client data
    text: serán almacenados por 10 años después de terminada la relación contractual
  - period: veinticuatro (24) meses
    scope: closed accounts
    text: Conservaremos la información personal de las cuentas cerradas durante un periodo de veinticuatro (24) meses
  rights:
  - right: access, rectification, cancellation, revocation, opposition
    text: Puedes ejercer tus derechos de acceso, rectificación, cancelación, revocación y oposición al tratamiento de tus datos personales, presentando tu solicitud a cumplimiento@culqi.com
  - right: complaint to authority
    text: En caso tu pedido no haya sido atendido puedes presentar una reclamación ante la Autoridad Nacional de Protección de Datos Personales
  role:
    text: la Empresa utilizará diversos encargados de tratamiento, ubicados en el Perú y en el extranjero
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Proveedores de servicios con los que la Empresa ha suscrito un contrato asociado a sus operaciones comerciales
  subprocessors:
    text: cuya identidad, ubicación y finalidad de tratamiento aceptas haber tenido a tu disposición al ingresar al siguiente enlace
    url: https://culqi.com/static/files/subsidiarias_proveedores.pdf
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Culqi
provenance_date: '2026-11-09'
provider_name: Culqi
provider_slug: culqi
slug: culqi-privacy-policy
source_date: '2026-11-09'
source_filename: culqi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://culqi.com/politicas-de-privacidad/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Culqi\naid: culqi\nurl: https://culqi.com/politicas-de-privacidad/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: la Empresa utilizará diversos encargados de tratamiento, ubicados en el Perú y en el extranjero\ndata_categories:\n- category: identifying\n  text: Nombre, dirección de correo electrónico, información de contacto físico, fecha de nacimiento\n- category: financial\n  text: datos financieros, como el número de tarjeta de crédito o cuenta bancaria, código de verificación, dirección\n    de facturación\n- category: biometric\n  text: Almacenaremos y trataremos tus\
  \ datos biométricos faciales y dactilares\n- category: device\n  text: el modelo y Sistema operativo del dispositivo móvil usado y la versión del navegador\n- category: communication\n  text: Discusiones, conversaciones y correspondencia con comercios afiliados\npurposes:\n- purpose: provide services requested\n  text: Proporcionar los servicios y la atención que el Titular de Datos Personales solicite.\n- purpose: prevent illegal activities\n  text: Impedir actividades potencialmente prohibidas o ilegales\n- purpose: personalize and improve service\n  text: Personalizar, cuantificar y mejorar el Servicio.\n- purpose: marketing\n  text: realizar acciones de marketing segmentado, actualizaciones de servicios y ofertas promocionales\nretention:\n- scope: registered client data\n  period: 10 años\n  text: serán almacenados por 10 años después de terminada la relación contractual\n- scope: closed accounts\n  period: veinticuatro (24) meses\n  text: Conservaremos la información personal de\
  \ las cuentas cerradas durante un periodo de veinticuatro (24) meses\nresidency:\n- region: United States\n  text: La información personal se almacena en los servidores de la Empresa ubicados en Estados Unidos.\ntransfers: []\nsubprocessors:\n  url: https://culqi.com/static/files/subsidiarias_proveedores.pdf\n  text: cuya identidad, ubicación y finalidad de tratamiento aceptas haber tenido a tu disposición al ingresar al\n    siguiente enlace\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, rectification, cancellation, revocation, opposition\n  text: Puedes ejercer tus derechos de acceso, rectificación, cancelación, revocación y oposición al tratamiento\n    de tus datos personales, presentando tu solicitud a cumplimiento@culqi.com\n- right: complaint to authority\n  text: En caso tu pedido no haya sido atendido puedes presentar una reclamación ante la Autoridad Nacional de Protección\n    de Datos Personales\nsale_or_sharing:\n\
  \  stance: conditional\n  text: Proveedores de servicios con los que la Empresa ha suscrito un contrato asociado a sus operaciones comerciales\n"
source_yaml_url: https://artifacts.apis.io/culqi/privacy/culqi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Culqi's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- Peru
- Latin America
- Cards
- Yape
---
