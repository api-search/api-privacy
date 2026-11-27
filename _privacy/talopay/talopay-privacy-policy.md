---
api_specs:
- filename: talopay-openapi-generated.yml
  format: yaml
  label: Talo Pay API
  slug: talopay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talopay/openapi/_ae-authored/talopay-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Razón social, CUIT, nombre y DNI de representantes legales
  - category: contact
    text: información de contacto (correo electrónico, teléfono, domicilio)
  - category: financial
    text: datos de cuentas bancarias para la liquidación de fondos
  - category: location
    text: Datos de ubicación del dispositivo para fines de prevención de fraude y análisis de riesgo.
  - category: device
    text: Dirección IP, tipo y versión del navegador y sistema operativo del dispositivo utilizado para realizar la transacción, identificadores únicos de dispositivo.
  - category: behavioral
    text: Detalles de las operaciones de pago, como monto, moneda, fecha y hora, origen, producto o servicio adquirido, historial de transacciones, reclamos y devoluciones.
  deletion:
    route: Automatic deletion or anonymization at end of retention period
    text: Una vez que el período de conservación aplicable ha finalizado y ya no existe una obligación legal para mantenerla, su información personal será eliminada de forma segura y permanente de nuestros sistemas o será anonimizada de manera irreversible para que ya no pueda ser asociada a usted. Este proceso es automático y no requiere una solicitud por parte del usuario.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Proveer nuestros Servicios
    text: Procesar, validar, y confirmar transacciones de pago.
  - purpose: Prevención de fraude
    text: Desarrollar y entrenar modelos de detección y prevención de fraude y delitos relacionados.
  - purpose: Cumplimiento legal
    text: Cumplir con normativas de Prevención de Lavado de Activos y Financiamiento del Terrorismo (PLD/FT), incluyendo procesos de "Conozca a su Cliente" (KYC).
  - purpose: Mejora del servicio
    text: Realizar estudios internos y estadísticos sobre intereses y comportamientos de uso para mejorar nuestra Solución y desarrollar nuevas funcionalidades
  retention:
  - period: null
    scope: Información personal
    text: Conservamos su información personal solo durante el tiempo estrictamente necesario para cumplir con las finalidades para las que fue recopilada y para atender nuestras obligaciones legales y regulatorias.
  - period: hasta 10 años
    scope: Facturas y registros fiscales
    text: que pueden requerir conservar facturas y registros por hasta 10 años
  rights:
  - right: Acceso
    text: Acceder a la información que tenemos sobre usted.
  - right: Rectificación
    text: Rectificar sus datos si son inexactos o incompletos.
  - right: Supresión
    text: Suprimir ("Derecho al olvido") sus datos cuando ya no sean necesarios para los fines para los que fueron recogidos, siempre que no exista una obligación legal de conservarlos.
  - right: Portabilidad
    text: Solicitar la portabilidad de sus datos.
  - right: Oposición o limitación
    text: Oponerse al tratamiento de sus datos o solicitar la limitación de su tratamiento en los casos permitidos por la ley.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No vendemos ni comercializamos su información personal.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: mediante la firma de cláusulas contractuales o el uso de otros mecanismos permitidos por la normativa vigente
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Talo Pay
provenance_date: '2026-11-10'
provider_name: Talo Pay
provider_slug: talopay
slug: talopay-privacy-policy
source_date: '2026-11-10'
source_filename: talopay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://talopay.com/ar/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Talo Pay\naid: talopay\nurl: https://talopay.com/ar/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Razón social, CUIT, nombre y DNI de representantes legales\n- category: contact\n  text: información de contacto (correo electrónico, teléfono, domicilio)\n- category: financial\n  text: datos de cuentas bancarias para la liquidación de fondos\n- category: location\n  text: Datos de ubicación del dispositivo para fines de prevención de fraude y análisis de riesgo.\n- category: device\n  text: Dirección IP, tipo y versión del\
  \ navegador y sistema operativo del dispositivo utilizado para realizar la\n    transacción, identificadores únicos de dispositivo.\n- category: behavioral\n  text: Detalles de las operaciones de pago, como monto, moneda, fecha y hora, origen, producto o servicio adquirido,\n    historial de transacciones, reclamos y devoluciones.\npurposes:\n- purpose: Proveer nuestros Servicios\n  text: Procesar, validar, y confirmar transacciones de pago.\n- purpose: Prevención de fraude\n  text: Desarrollar y entrenar modelos de detección y prevención de fraude y delitos relacionados.\n- purpose: Cumplimiento legal\n  text: Cumplir con normativas de Prevención de Lavado de Activos y Financiamiento del Terrorismo (PLD/FT), incluyendo\n    procesos de \"Conozca a su Cliente\" (KYC).\n- purpose: Mejora del servicio\n  text: Realizar estudios internos y estadísticos sobre intereses y comportamientos de uso para mejorar nuestra\n    Solución y desarrollar nuevas funcionalidades\nretention:\n- scope: Información\
  \ personal\n  period: null\n  text: Conservamos su información personal solo durante el tiempo estrictamente necesario para cumplir con las\n    finalidades para las que fue recopilada y para atender nuestras obligaciones legales y regulatorias.\n- scope: Facturas y registros fiscales\n  period: hasta 10 años\n  text: que pueden requerir conservar facturas y registros por hasta 10 años\nresidency: []\ntransfers:\n- mechanism: other\n  text: mediante la firma de cláusulas contractuales o el uso de otros mecanismos permitidos por la normativa vigente\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Automatic deletion or anonymization at end of retention period\n  text: Una vez que el período de conservación aplicable ha finalizado y ya no existe una obligación legal para\n    mantenerla, su información personal será eliminada de forma segura y permanente de nuestros sistemas o será\n    anonimizada de manera irreversible\
  \ para que ya no pueda ser asociada a usted. Este proceso es automático y no\n    requiere una solicitud por parte del usuario.\nrights:\n- right: Acceso\n  text: Acceder a la información que tenemos sobre usted.\n- right: Rectificación\n  text: Rectificar sus datos si son inexactos o incompletos.\n- right: Supresión\n  text: Suprimir (\"Derecho al olvido\") sus datos cuando ya no sean necesarios para los fines para los que fueron\n    recogidos, siempre que no exista una obligación legal de conservarlos.\n- right: Portabilidad\n  text: Solicitar la portabilidad de sus datos.\n- right: Oposición o limitación\n  text: Oponerse al tratamiento de sus datos o solicitar la limitación de su tratamiento en los casos permitidos\n    por la ley.\nsale_or_sharing:\n  stance: prohibited\n  text: No vendemos ni comercializamos su información personal.\n"
source_yaml_url: https://artifacts.apis.io/talopay/privacy/talopay-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Talo Pay's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Payments
- Argentina
- E-Commerce
- Bank Transfers
---
