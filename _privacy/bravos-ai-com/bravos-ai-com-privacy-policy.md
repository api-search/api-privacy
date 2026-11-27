---
api_specs:
- filename: bravos-ai-com-openapi-generated.yml
  format: yaml
  label: Bravos AI API
  slug: bravos-ai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bravos-ai-com/openapi/_ae-authored/bravos-ai-com-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Información de cuenta: Nombre, email, contraseña (encriptada con bcrypt)'
  - category: contact
    text: 'Datos de contacto que el propio visitante facilita: los del formulario de captación que configures (nombre, correo, teléfono, país y campos adicionales)'
  - category: financial
    text: 'Información de facturación: Procesada por Stripe (no almacenamos datos de tarjetas)'
  - category: behavioral
    text: 'Datos de uso: Páginas visitadas, funciones utilizadas, tiempo de uso'
  - category: device
    text: 'Datos técnicos: Dirección IP, navegador, sistema operativo'
  - category: communication
    text: Mensajes de la conversación
  - category: communication
    text: 'Mensajes: texto, imágenes, audios y documentos que intercambian usuarios finales con el chatbot'
  deletion:
    route: Solicitud por correo electrónico al responsable
    text: Puedes solicitar la eliminación inmediata escribiéndonos
  dpa:
    available: true
    text: Acuerdo de Tratamiento de Datos (DPA)
    url: null
  purposes:
  - purpose: Proporcionar el servicio
    text: Proporcionar y mantener el servicio de Bravos AI
  - purpose: Procesar pagos
    text: Procesar pagos y gestionar suscripciones
  - purpose: Mejora del servicio
    text: Mejorar y optimizar nuestros servicios
  - purpose: Marketing con consentimiento
    text: Enviarte comunicaciones de marketing (solo con tu consentimiento)
  residency:
  - region: Unión Europea (Alemania)
    text: Los mensajes se almacenan cifrados en nuestros servidores en la UE (Hetzner, Alemania).
  - region: Irlanda
    text: Los archivos de audio se almacenan en Amazon S3, en la región de Irlanda, también dentro de la Unión Europea.
  retention:
  - period: 30 días
    scope: Datos de cuenta
    text: Mientras tu cuenta esté activa + 30 días tras cancelación
  - period: 10 años
    scope: Datos de facturación
    text: 'Datos de facturación: 10 años (requisito legal fiscal)'
  - period: 90 días
    scope: Conversaciones del widget
    text: 'Conversaciones del widget: 90 días de inactividad (se eliminan automáticamente)'
  - period: 24 horas
    scope: Archivos multimedia del widget
    text: 'Archivos multimedia del widget: 24 horas (se eliminan automáticamente)'
  - period: 90 días
    scope: Logs técnicos
    text: 'Logs técnicos: 90 días'
  rights:
  - right: Acceso
    text: 'Acceso: Solicitar una copia de tus datos personales'
  - right: Supresión
    text: 'Supresión: Solicitar la eliminación de tus datos ("derecho al olvido")'
  - right: Portabilidad
    text: 'Portabilidad: Recibir tus datos en formato estructurado'
  - right: Oposición
    text: 'Oposición: Oponerte al procesamiento de tus datos'
  role:
    text: Bravos AI actúa como encargado del tratamiento (procesador).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: No vendemos tus datos personales.
  subprocessors:
    text: 'Sub-procesadores: Proveedor Propósito Ubicación Garantías OpenAI, LLC'
    url: null
  transfers:
  - mechanism: SCC
    text: Utilizamos Cláusulas Contractuales Tipo (SCCs) aprobadas por la Comisión Europea
  - mechanism: DPF
    text: Verificamos la participación en el EU-US Data Privacy Framework cuando aplique
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bravos AI
provenance_date: '2026-11-09'
provider_name: Bravos AI
provider_slug: bravos-ai-com
slug: bravos-ai-com-privacy-policy
source_date: '2026-11-09'
source_filename: bravos-ai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bravos-ai.com/legal/privacidad
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bravos AI\naid: bravos-ai-com\nurl: https://bravos-ai.com/legal/privacidad\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Bravos AI actúa como encargado del tratamiento (procesador).\ndata_categories:\n- category: identifying\n  text: 'Información de cuenta: Nombre, email, contraseña (encriptada con bcrypt)'\n- category: contact\n  text: 'Datos de contacto que el propio visitante facilita: los del formulario de captación que configures (nombre,\n    correo, teléfono, país y campos adicionales)'\n- category: financial\n  text: 'Información de facturación: Procesada por Stripe (no almacenamos datos\
  \ de tarjetas)'\n- category: behavioral\n  text: 'Datos de uso: Páginas visitadas, funciones utilizadas, tiempo de uso'\n- category: device\n  text: 'Datos técnicos: Dirección IP, navegador, sistema operativo'\n- category: communication\n  text: Mensajes de la conversación\n- category: communication\n  text: 'Mensajes: texto, imágenes, audios y documentos que intercambian usuarios finales con el chatbot'\npurposes:\n- purpose: Proporcionar el servicio\n  text: Proporcionar y mantener el servicio de Bravos AI\n- purpose: Procesar pagos\n  text: Procesar pagos y gestionar suscripciones\n- purpose: Mejora del servicio\n  text: Mejorar y optimizar nuestros servicios\n- purpose: Marketing con consentimiento\n  text: Enviarte comunicaciones de marketing (solo con tu consentimiento)\nretention:\n- scope: Datos de cuenta\n  period: 30 días\n  text: Mientras tu cuenta esté activa + 30 días tras cancelación\n- scope: Datos de facturación\n  period: 10 años\n  text: 'Datos de facturación: 10 años\
  \ (requisito legal fiscal)'\n- scope: Conversaciones del widget\n  period: 90 días\n  text: 'Conversaciones del widget: 90 días de inactividad (se eliminan automáticamente)'\n- scope: Archivos multimedia del widget\n  period: 24 horas\n  text: 'Archivos multimedia del widget: 24 horas (se eliminan automáticamente)'\n- scope: Logs técnicos\n  period: 90 días\n  text: 'Logs técnicos: 90 días'\nresidency:\n- region: Unión Europea (Alemania)\n  text: Los mensajes se almacenan cifrados en nuestros servidores en la UE (Hetzner, Alemania).\n- region: Irlanda\n  text: Los archivos de audio se almacenan en Amazon S3, en la región de Irlanda, también dentro de la Unión Europea.\ntransfers:\n- mechanism: SCC\n  text: Utilizamos Cláusulas Contractuales Tipo (SCCs) aprobadas por la Comisión Europea\n- mechanism: DPF\n  text: Verificamos la participación en el EU-US Data Privacy Framework cuando aplique\nsubprocessors:\n  url: null\n  text: 'Sub-procesadores: Proveedor Propósito Ubicación Garantías\
  \ OpenAI, LLC'\ndpa:\n  available: true\n  url: null\n  text: Acuerdo de Tratamiento de Datos (DPA)\ndeletion:\n  route: Solicitud por correo electrónico al responsable\n  text: Puedes solicitar la eliminación inmediata escribiéndonos\nrights:\n- right: Acceso\n  text: 'Acceso: Solicitar una copia de tus datos personales'\n- right: Supresión\n  text: 'Supresión: Solicitar la eliminación de tus datos (\"derecho al olvido\")'\n- right: Portabilidad\n  text: 'Portabilidad: Recibir tus datos en formato estructurado'\n- right: Oposición\n  text: 'Oposición: Oponerte al procesamiento de tus datos'\nsale_or_sharing:\n  stance: prohibited\n  text: No vendemos tus datos personales.\n"
source_yaml_url: https://artifacts.apis.io/bravos-ai-com/privacy/bravos-ai-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Bravos AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Customer Service
- E-Commerce
- Spanish
---
