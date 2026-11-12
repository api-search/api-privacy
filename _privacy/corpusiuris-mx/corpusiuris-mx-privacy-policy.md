---
api_specs:
- filename: corpusiuris-mx-agent-api-openapi.yml
  format: yaml
  label: Corpus Iuris Agent API
  slug: corpusiuris-mx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiuris-mx/openapi/corpusiuris-mx-agent-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identificación: nombre, correo electrónico y foto de perfil provistos por el proveedor de acceso (Google).'
  - category: contact
    text: Nombre completo, correo electrónico y número de WhatsApp
  - category: financial
    text: 'Facturación (solo si pide factura): RFC, razón social, régimen fiscal, uso de CFDI y domicilio fiscal.'
  - category: behavioral
    text: 'Uso del servicio: consultas, conversaciones con la inteligencia artificial, archivos que suba, plantillas, casos y notas.'
  - category: device
    text: dirección IP, fecha y hora de acceso, navegador, sistema operativo y registros técnicos
  deletion:
    route: in-app deletion of conversations and files
    text: Las conversaciones y archivos pueden borrarse en cualquier momento desde la propia aplicación.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: generate AI responses to queries
    text: Procesar sus consultas en el corpus jurídico y generar respuestas con inteligencia artificial.
  - purpose: advertising measurement
    text: Medir el desempeño de nuestras campañas publicitarias (Meta, Google, OpenAI)
  - purpose: newsletter (secondary, opt-out)
    text: Enviarle por correo el boletín semanal gratuito «Actualización legal»
  retention:
  - period: mientras esté activa
    scope: account
    text: 'Cuenta: mientras esté activa.'
  - period: cinco años
    scope: tax and operations data
    text: 'Datos fiscales y de operaciones: cinco años, conforme al artículo 30 del Código Fiscal de la Federación.'
  - period: hasta doce meses
    scope: free course registrations
    text: 'Inscripciones a cursos gratuitos: hasta doce meses después de la última edición del curso a la que se haya inscrito, salvo que antes solicite su cancelación.'
  rights:
  - right: access, rectification, cancellation, opposition
    text: Usted o su representante legal pueden ejercer en cualquier momento sus derechos de acceso, rectificación, cancelación y oposición
  - right: revocation of consent
    text: así como revocar su consentimiento
  - right: limitation of use and refusal of secondary purposes
    text: derechos ARCO, revocación del consentimiento, limitación del uso y negativa a finalidades secundarias
  role:
    text: El responsable del tratamiento de sus datos personales es el C. José Luis Aguado Ramos
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No vendemos ni cedemos sus datos.
  subprocessors:
    text: 'Google LLC / Google Cloud (EE. UU.): infraestructura, base de datos, autenticación, almacenamiento de archivos y analítica.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corpus Iuris
provenance_date: '2026-11-09'
provider_name: Corpus Iuris
provider_slug: corpusiuris-mx
slug: corpusiuris-mx-privacy-policy
source_date: '2026-11-09'
source_filename: corpusiuris-mx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corpusiuris.mx/privacidad
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corpus Iuris\naid: corpusiuris-mx\nurl: https://corpusiuris.mx/privacidad\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: El responsable del tratamiento de sus datos personales es el C. José Luis Aguado Ramos\ndata_categories:\n- category: identifying\n  text: 'Identificación: nombre, correo electrónico y foto de perfil provistos por el proveedor de acceso (Google).'\n- category: contact\n  text: Nombre completo, correo electrónico y número de WhatsApp\n- category: financial\n  text: 'Facturación (solo si pide factura): RFC, razón social, régimen fiscal, uso de CFDI y domicilio fiscal.'\n-\
  \ category: behavioral\n  text: 'Uso del servicio: consultas, conversaciones con la inteligencia artificial, archivos que suba, plantillas,\n    casos y notas.'\n- category: device\n  text: dirección IP, fecha y hora de acceso, navegador, sistema operativo y registros técnicos\npurposes:\n- purpose: generate AI responses to queries\n  text: Procesar sus consultas en el corpus jurídico y generar respuestas con inteligencia artificial.\n- purpose: advertising measurement\n  text: Medir el desempeño de nuestras campañas publicitarias (Meta, Google, OpenAI)\n- purpose: newsletter (secondary, opt-out)\n  text: Enviarle por correo el boletín semanal gratuito «Actualización legal»\nretention:\n- scope: account\n  period: mientras esté activa\n  text: 'Cuenta: mientras esté activa.'\n- scope: tax and operations data\n  period: cinco años\n  text: 'Datos fiscales y de operaciones: cinco años, conforme al artículo 30 del Código Fiscal de la Federación.'\n- scope: free course registrations\n  period:\
  \ hasta doce meses\n  text: 'Inscripciones a cursos gratuitos: hasta doce meses después de la última edición del curso a la que se haya\n    inscrito, salvo que antes solicite su cancelación.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Google LLC / Google Cloud (EE. UU.): infraestructura, base de datos, autenticación, almacenamiento de archivos\n    y analítica.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app deletion of conversations and files\n  text: Las conversaciones y archivos pueden borrarse en cualquier momento desde la propia aplicación.\nrights:\n- right: access, rectification, cancellation, opposition\n  text: Usted o su representante legal pueden ejercer en cualquier momento sus derechos de acceso, rectificación,\n    cancelación y oposición\n- right: revocation of consent\n  text: así como revocar su consentimiento\n- right: limitation of use and refusal of secondary purposes\n  text: derechos ARCO, revocación del\
  \ consentimiento, limitación del uso y negativa a finalidades secundarias\nsale_or_sharing:\n  stance: prohibited\n  text: No vendemos ni cedemos sus datos.\n"
source_yaml_url: https://artifacts.apis.io/corpusiuris-mx/privacy/corpusiuris-mx-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Corpus Iuris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Research
- Artificial Intelligence
- Mexico
- Jurisprudence
- MCP
- Search
---
