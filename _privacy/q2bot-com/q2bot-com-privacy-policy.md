---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: other
    text: Identificador de la tienda ( store id ) y token de acceso provisto por Tiendanube.
  - category: communication
    text: Información del número de WhatsApp Business vinculado y de las plantillas configuradas.
  - category: other
    text: Datos de pedidos, clientes y productos enviados por los webhooks habilitados en la tienda.
  deletion:
    route: store/redact webhook from Tiendanube
    text: al recibirlo, eliminamos o anonimizamos los datos personales asociados a esa tienda.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: send WhatsApp notifications
    text: Enviar notificaciones por WhatsApp a los clientes finales según los eventos configurados por la tienda.
  - purpose: operation, support and diagnostics
    text: Permitir la operación, soporte y diagnóstico de la Aplicación.
  - purpose: legal and platform compliance
    text: Cumplir con obligaciones legales y con los requisitos de la plataforma Tiendanube.
  retention:
  - period: mientras la Aplicación esté instalada
    scope: while app is installed
    text: Los datos asociados a una tienda se conservan mientras la Aplicación esté instalada.
  - period: 48 horas
    scope: after uninstall via store/redact webhook
    text: Tiendanube envía un webhook store/redact 48 horas después
  rights:
  - right: access, rectification and deletion
    text: Los clientes finales de la tienda pueden ejercer los derechos de acceso, rectificación y eliminación de sus datos.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No vendemos, alquilamos ni compartimos los datos con terceros con fines comerciales.
  subprocessors:
    text: No se utilizan proveedores adicionales de procesamiento de datos.
    url: null
  transfers:
  - mechanism: other
    text: Los datos se transmiten a la API oficial de WhatsApp Business / Meta únicamente con el fin de entregar los mensajes configurados por la tienda.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: q2bot-com
provenance_date: '2026-11-10'
provider_name: q2bot-com
provider_slug: q2bot-com
slug: q2bot-com-privacy-policy
source_date: '2026-11-10'
source_filename: q2bot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://q2bot.com/tns/tiendanube/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: q2bot-com\naid: q2bot-com\nurl: https://q2bot.com/tns/tiendanube/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: Identificador de la tienda ( store id ) y token de acceso provisto por Tiendanube.\n- category: communication\n  text: Información del número de WhatsApp Business vinculado y de las plantillas configuradas.\n- category: other\n  text: Datos de pedidos, clientes y productos enviados por los webhooks habilitados en la tienda.\npurposes:\n- purpose: send WhatsApp notifications\n  text: Enviar notificaciones por WhatsApp a\
  \ los clientes finales según los eventos configurados por la tienda.\n- purpose: operation, support and diagnostics\n  text: Permitir la operación, soporte y diagnóstico de la Aplicación.\n- purpose: legal and platform compliance\n  text: Cumplir con obligaciones legales y con los requisitos de la plataforma Tiendanube.\nretention:\n- scope: while app is installed\n  period: mientras la Aplicación esté instalada\n  text: Los datos asociados a una tienda se conservan mientras la Aplicación esté instalada.\n- scope: after uninstall via store/redact webhook\n  period: 48 horas\n  text: Tiendanube envía un webhook store/redact 48 horas después\nresidency: []\ntransfers:\n- mechanism: other\n  text: Los datos se transmiten a la API oficial de WhatsApp Business / Meta únicamente con el fin de entregar los\n    mensajes configurados por la tienda.\nsubprocessors:\n  url: null\n  text: No se utilizan proveedores adicionales de procesamiento de datos.\ndpa:\n  available: null\n  url: null\n  text:\
  \ null\ndeletion:\n  route: store/redact webhook from Tiendanube\n  text: al recibirlo, eliminamos o anonimizamos los datos personales asociados a esa tienda.\nrights:\n- right: access, rectification and deletion\n  text: Los clientes finales de la tienda pueden ejercer los derechos de acceso, rectificación y eliminación de\n    sus datos.\nsale_or_sharing:\n  stance: prohibited\n  text: No vendemos, alquilamos ni compartimos los datos con terceros con fines comerciales.\n"
source_yaml_url: https://artifacts.apis.io/q2bot-com/privacy/q2bot-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from q2bot-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- WhatsApp
- Artificial Intelligence
- Automation
- Tienda Nube
---
