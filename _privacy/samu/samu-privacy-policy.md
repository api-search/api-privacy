---
api_specs:
- filename: samu-meetings-api-openapi.yml
  format: yaml
  label: Samu Meetings API
  slug: samu-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-meetings-api-openapi.yml
- filename: samu-threads-api-openapi.yml
  format: yaml
  label: Samu Threads API
  slug: samu-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-threads-api-openapi.yml
- filename: samu-usuarios-api-openapi.yml
  format: yaml
  label: Samu Usuarios API
  slug: samu-usuarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/samu/openapi/samu-usuarios-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: datos de identificación personal
  - category: contact
    text: Información Básica de la Cuenta (nombre, dirección de correo electrónico y foto de perfil
  - category: communication
    text: Gmail en modo de solo lectura
  - category: behavioral
    text: Cookies y tecnologías similares en su sitio web para mejorar la experiencia del usuario, analizar el tráfico
  deletion:
    route: Email request to the privacy contact address
    text: El usuario o su organización pueden solicitar la eliminación de los datos ya sincronizados y de los tokens de acceso escribiendo a [email protected]
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve app features for Google user data
    text: SAMU.AI utiliza los datos de usuario de Google exclusivamente para proveer y mejorar las funcionalidades de la aplicación visibles para el usuario
  - purpose: Website cookies
    text: SAMU.AI utiliza cookies y tecnologías similares en su sitio web para mejorar la experiencia del usuario, analizar el tráfico y entender cómo interactúan los usuarios con nuestro contenido.
  retention:
  - period: 30 días
    scope: Google user data synced
    text: SAMU.AI los eliminará en un plazo máximo de 30 días, y de las copias de respaldo en un plazo máximo de 90 días.
  - period: 90 días
    scope: Backup copies of Google user data
    text: de las copias de respaldo en un plazo máximo de 90 días
  - period: null
    scope: Personal data generally
    text: Conservamos los datos personales únicamente durante el tiempo necesario para cumplir con las finalidades para las que fueron recolectados.
  rights:
  - right: Acceso
    text: Acceso (derecho a conocer qué datos personales tenemos)
  - right: Rectificación
    text: Rectificación (solicitar la actualización o corrección de datos incorrectos o incompletos)
  - right: Cancelación y Oposición
    text: Cancelación y Oposición (derecho a solicitar la eliminación o suspensión del tratamiento de sus datos)
  - right: Portabilidad
    text: Portabilidad (derecho a recibir los datos en un formato estructurado y de uso común)
  - right: Limitación del Tratamiento
    text: Limitación del Tratamiento (derecho a restringir el procesamiento de datos bajo ciertas circunstancias)
  role:
    text: SAMU.AI desempeña distintos roles en el tratamiento de los datos personales dependiendo de cómo se obtienen y procesan dichos datos.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: SAMU.AI no vende datos de usuario de Google
  subprocessors:
    text: proveedores de infraestructura en la nube que alojan las bases de datos, los índices de búsqueda y el almacenamiento de archivos de la aplicación
    url: null
  transfers:
  - mechanism: other
    text: SAMU.AI garantizará que cualquier transferencia de datos personales a terceros países se realice conforme a los niveles de protección requeridos, aplicando cláusulas contractuales o acuerdos
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Samu
provenance_date: '2026-11-10'
provider_name: Samu
provider_slug: samu
slug: samu-privacy-policy
source_date: '2026-11-10'
source_filename: samu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.samu.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Samu\naid: samu\nurl: https://www.samu.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: SAMU.AI desempeña distintos roles en el tratamiento de los datos personales dependiendo de cómo se obtienen\n    y procesan dichos datos.\ndata_categories:\n- category: identifying\n  text: datos de identificación personal\n- category: contact\n  text: Información Básica de la Cuenta (nombre, dirección de correo electrónico y foto de perfil\n- category: communication\n  text: Gmail en modo de solo lectura\n- category: behavioral\n  text: Cookies y tecnologías similares en su sitio web para mejorar la\
  \ experiencia del usuario, analizar el tráfico\npurposes:\n- purpose: Provide and improve app features for Google user data\n  text: SAMU.AI utiliza los datos de usuario de Google exclusivamente para proveer y mejorar las funcionalidades\n    de la aplicación visibles para el usuario\n- purpose: Website cookies\n  text: SAMU.AI utiliza cookies y tecnologías similares en su sitio web para mejorar la experiencia del usuario,\n    analizar el tráfico y entender cómo interactúan los usuarios con nuestro contenido.\nretention:\n- scope: Google user data synced\n  period: 30 días\n  text: SAMU.AI los eliminará en un plazo máximo de 30 días, y de las copias de respaldo en un plazo máximo de 90\n    días.\n- scope: Backup copies of Google user data\n  period: 90 días\n  text: de las copias de respaldo en un plazo máximo de 90 días\n- scope: Personal data generally\n  period: null\n  text: Conservamos los datos personales únicamente durante el tiempo necesario para cumplir con las finalidades\n\
  \    para las que fueron recolectados.\nresidency: []\ntransfers:\n- mechanism: other\n  text: SAMU.AI garantizará que cualquier transferencia de datos personales a terceros países se realice conforme\n    a los niveles de protección requeridos, aplicando cláusulas contractuales o acuerdos\nsubprocessors:\n  url: null\n  text: proveedores de infraestructura en la nube que alojan las bases de datos, los índices de búsqueda y el almacenamiento\n    de archivos de la aplicación\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to the privacy contact address\n  text: El usuario o su organización pueden solicitar la eliminación de los datos ya sincronizados y de los tokens\n    de acceso escribiendo a [email protected]\nrights:\n- right: Acceso\n  text: Acceso (derecho a conocer qué datos personales tenemos)\n- right: Rectificación\n  text: Rectificación (solicitar la actualización o corrección de datos incorrectos o incompletos)\n- right: Cancelación y\
  \ Oposición\n  text: Cancelación y Oposición (derecho a solicitar la eliminación o suspensión del tratamiento de sus datos)\n- right: Portabilidad\n  text: Portabilidad (derecho a recibir los datos en un formato estructurado y de uso común)\n- right: Limitación del Tratamiento\n  text: Limitación del Tratamiento (derecho a restringir el procesamiento de datos bajo ciertas circunstancias)\nsale_or_sharing:\n  stance: prohibited\n  text: SAMU.AI no vende datos de usuario de Google\n"
source_yaml_url: https://artifacts.apis.io/samu/privacy/samu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Samu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales
- Sales Intelligence
- Conversation Intelligence
- CRM
- Call Recording
- Analytics
- Latin America
- Transcription
- WhatsApp
- MCP
- Agent-Native
---
