---
api_specs:
- filename: audiomap-ai-ask-api-openapi.yml
  format: yaml
  label: AudioMap Ask API
  slug: audiomap-ai-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-ask-api-openapi.yml
- filename: audiomap-ai-content-api-openapi.yml
  format: yaml
  label: AudioMap Content API
  slug: audiomap-ai-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-content-api-openapi.yml
- filename: audiomap-ai-deliverables-api-openapi.yml
  format: yaml
  label: AudioMap Deliverables API
  slug: audiomap-ai-deliverables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-deliverables-api-openapi.yml
- filename: audiomap-ai-notes-api-openapi.yml
  format: yaml
  label: AudioMap Notes API
  slug: audiomap-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomap-ai/openapi/audiomap-ai-notes-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Cuenta y perfil : email, nombre y método de acceso.'
  - category: communication
    text: 'Audios y transcripciones : los archivos que subes y el texto que generamos a partir de ellos.'
  - category: behavioral
    text: 'Datos de uso : minutos consumidos, funciones utilizadas.'
  - category: biometric
    text: 'Perfiles de voz (solo si los activas): vectores de voz de los hablantes de tus grabaciones. Son datos biométricos.'
  - category: device
    text: Mapas de calor y grabación de sesión de las analíticas.
  deletion:
    route: Escribir a privacidad@audiomap.ai o eliminar la cuenta
    text: 'Supresión : solicitar la eliminación de tu cuenta y tus datos.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Transcribir audio y generar AI Notes y chat
    text: Transcribir tu audio y generar AI Notes y respuestas en el chat.
  - purpose: Gestionar suscripción y cuota
    text: Gestionar tu suscripción y el uso de cuota del plan.
  - purpose: Cumplimiento legal
    text: Cumplimiento legal cuando lo exija un requerimiento judicial fundado.
  residency:
  - region: Unión Europea
    text: 'Dónde se procesa : en nuestro propio servidor dentro de la Unión Europea. Ningún proveedor externo interviene en este tratamiento.'
  retention:
  - period: mientras tu cuenta esté activa y hayas dado consentimiento expreso
    scope: Audio original
    text: 'Audio original : mientras tu cuenta esté activa y hayas dado consentimiento expreso.'
  - period: 6 años tras el cierre de la cuenta
    scope: Registro de consentimientos
    text: 'Registro de consentimientos : 6 años tras el cierre de la cuenta (mínimo legal en España para registros contractuales).'
  - period: 7 días
    scope: Registro técnico de sesión (programa fundadores)
    text: el registro técnico de una sesión se guarda en nuestra propia base de datos y se borra a los 7 días.
  rights:
  - right: Acceso
    text: 'Acceso : obtener una copia de todos los datos personales que tenemos sobre ti.'
  - right: Rectificación
    text: 'Rectificación : corregir datos inexactos o incompletos.'
  - right: Supresión
    text: 'Supresión : solicitar la eliminación de tu cuenta y tus datos.'
  - right: Portabilidad
    text: 'Portabilidad : recibir tus datos en un formato legible por máquina.'
  - right: Oposición y limitación
    text: 'Oposición y limitación : restringir o paralizar ciertos usos de tus datos.'
  role:
    text: CODELABS STUDIO, S.L. (CIF B88708797), con domicilio social en Pasaje Federico García Lorca, 6, 3º E, 29130 Alhaurín de la Torre (Málaga), España, inscrita en el Registro Mercantil de Málaga, hoja MA-198508, inscripción 1ª, opera el servicio AudioMap y es responsable del tratamiento de tus datos personales.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: La lista autoritativa y siempre actualizada vive en /legal/subprocessors .
    url: /legal/subprocessors
  transfers:
  - mechanism: SCC
    text: la transferencia a este proveedor se apoya en las cláusulas contractuales tipo (Decisión de Ejecución (UE) 2021/914) incorporadas a su contrato de encargado del tratamiento (DPA).
  - mechanism: DPF
    text: Meta puede transferir estos datos fuera de la Unión Europea al amparo del Marco de Privacidad de Datos UE-EE. UU.; el detalle está en la política de cookies de Meta .
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AudioMap
provenance_date: '2026-11-09'
provider_name: AudioMap
provider_slug: audiomap-ai
slug: audiomap-ai-privacy-policy
source_date: '2026-11-09'
source_filename: audiomap-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://audiomap.ai/es/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AudioMap\naid: audiomap-ai\nurl: https://audiomap.ai/es/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CODELABS STUDIO, S.L. (CIF B88708797), con domicilio social en Pasaje Federico García Lorca, 6, 3º E, 29130\n    Alhaurín de la Torre (Málaga), España, inscrita en el Registro Mercantil de Málaga, hoja MA-198508, inscripción\n    1ª, opera el servicio AudioMap y es responsable del tratamiento de tus datos personales.\ndata_categories:\n- category: contact\n  text: 'Cuenta y perfil : email, nombre y método de acceso.'\n- category: communication\n  text: 'Audios y transcripciones :\
  \ los archivos que subes y el texto que generamos a partir de ellos.'\n- category: behavioral\n  text: 'Datos de uso : minutos consumidos, funciones utilizadas.'\n- category: biometric\n  text: 'Perfiles de voz (solo si los activas): vectores de voz de los hablantes de tus grabaciones. Son datos biométricos.'\n- category: device\n  text: Mapas de calor y grabación de sesión de las analíticas.\npurposes:\n- purpose: Transcribir audio y generar AI Notes y chat\n  text: Transcribir tu audio y generar AI Notes y respuestas en el chat.\n- purpose: Gestionar suscripción y cuota\n  text: Gestionar tu suscripción y el uso de cuota del plan.\n- purpose: Cumplimiento legal\n  text: Cumplimiento legal cuando lo exija un requerimiento judicial fundado.\nretention:\n- scope: Audio original\n  period: mientras tu cuenta esté activa y hayas dado consentimiento expreso\n  text: 'Audio original : mientras tu cuenta esté activa y hayas dado consentimiento expreso.'\n- scope: Registro de consentimientos\n\
  \  period: 6 años tras el cierre de la cuenta\n  text: 'Registro de consentimientos : 6 años tras el cierre de la cuenta (mínimo legal en España para registros\n    contractuales).'\n- scope: Registro técnico de sesión (programa fundadores)\n  period: 7 días\n  text: el registro técnico de una sesión se guarda en nuestra propia base de datos y se borra a los 7 días.\nresidency:\n- region: Unión Europea\n  text: 'Dónde se procesa : en nuestro propio servidor dentro de la Unión Europea. Ningún proveedor externo interviene\n    en este tratamiento.'\ntransfers:\n- mechanism: SCC\n  text: la transferencia a este proveedor se apoya en las cláusulas contractuales tipo (Decisión de Ejecución (UE)\n    2021/914) incorporadas a su contrato de encargado del tratamiento (DPA).\n- mechanism: DPF\n  text: Meta puede transferir estos datos fuera de la Unión Europea al amparo del Marco de Privacidad de Datos UE-EE.\n    UU.; el detalle está en la política de cookies de Meta .\nsubprocessors:\n  url:\
  \ /legal/subprocessors\n  text: La lista autoritativa y siempre actualizada vive en /legal/subprocessors .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Escribir a privacidad@audiomap.ai o eliminar la cuenta\n  text: 'Supresión : solicitar la eliminación de tu cuenta y tus datos.'\nrights:\n- right: Acceso\n  text: 'Acceso : obtener una copia de todos los datos personales que tenemos sobre ti.'\n- right: Rectificación\n  text: 'Rectificación : corregir datos inexactos o incompletos.'\n- right: Supresión\n  text: 'Supresión : solicitar la eliminación de tu cuenta y tus datos.'\n- right: Portabilidad\n  text: 'Portabilidad : recibir tus datos en un formato legible por máquina.'\n- right: Oposición y limitación\n  text: 'Oposición y limitación : restringir o paralizar ciertos usos de tus datos.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/audiomap-ai/privacy/audiomap-ai-privacy-policy.yml
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
summary_line: 22 quoted statements, read from AudioMap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Transcription
- Audio
- Meeting Notes
- Europe
---
