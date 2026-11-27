---
api_specs:
- filename: apurata-config-api-openapi.yml
  format: yaml
  label: Apurata Config API
  slug: apurata-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-config-api-openapi.yml
- filename: apurata-orders-api-openapi.yml
  format: yaml
  label: Apurata Orders API
  slug: apurata-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-orders-api-openapi.yml
- filename: apurata-refunds-api-openapi.yml
  format: yaml
  label: Apurata Refunds API
  slug: apurata-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-refunds-api-openapi.yml
- filename: apurata-widgets-api-openapi.yml
  format: yaml
  label: Apurata Widgets API
  slug: apurata-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apurata/openapi/apurata-widgets-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: datos personales, laborales, patrimoniales y referencias personales del Usuario
  - category: contact
    text: la información de contacto del prestatario
  - category: location
    text: información de desplazamiento y ubicación geográfica aunque la aplicación no este siendo utilizada
  - category: device
    text: información sobre el dispositivo de acceso del Usuario, sistema operativo
  - category: communication
    text: registro de mensajes de texto recibidos y enviados, los contactos privados y registro de llamadas del dispositivo del usuario
  - category: behavioral
    text: Cronología de accesos a la Página o aplicación (app)
  deletion:
    route: Solicitud por correo a julia+revocar@apurata.com
    text: dirigiéndose a julia+revocar@apurata.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Evaluación de perfiles crediticios
    text: A. Evaluación de perfiles crediticios de Usuarios
  - purpose: Validación de identidad
    text: B. Validación de Identidad e información proporcionada en el cuestionario
  - purpose: Requerimientos de pago
    text: E. Requerimientos de pago y/o cumplimiento de sus obligaciones en los préstamos
  - purpose: Marketing
    text: J. Para fines comerciales y publicitarios relacionados con los productos y servicios ofrecidos por Apurata.
  residency:
  - region: Estados Unidos, Brazil, Mexico, Alemania u otros países
    text: serán almacenados en servidores que pueden estar ubicados en Estados Unidos, Brazil, Mexico, Alemania u otros países
  retention:
  - period: 10 (diez) años
    scope: Datos personales del Usuario
    text: conservándolos por 10 (diez) años, o por el plazo mayor que exijan las normas legales y regulatorias aplicables
  rights:
  - right: Acceso
    text: Los Usuarios de Apurata tendrán derecho de acceder a sus datos personales recabados
  - right: Rectificación
    text: a hacer correcciones a los mismos en caso de ser estos inexactos o incompletos
  - right: Cancelación
    text: a eliminar sus datos cuando consideren que no son necesarios para alguna de las finalidades señaladas
  - right: Oposición
    text: a oponerse al uso/tratamiento de sus datos
  - right: Revocación del consentimiento
    text: revocar su consentimiento respecto al uso de sus datos personales
  role:
    text: Apurata actúa como responsable del tratamiento de estos datos
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: el Usuario autoriza la transferencia y el tratamiento de datos a la casa matriz de la sociedad comercial Apurata, ubicada en el exterior
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apurata
provenance_date: '2026-11-09'
provider_name: Apurata
provider_slug: apurata
slug: apurata-privacy-policy
source_date: '2026-11-09'
source_filename: apurata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apurata.com/blog/privacidad/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apurata\naid: apurata\nurl: https://apurata.com/blog/privacidad/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Apurata actúa como responsable del tratamiento de estos datos\ndata_categories:\n- category: identifying\n  text: datos personales, laborales, patrimoniales y referencias personales del Usuario\n- category: contact\n  text: la información de contacto del prestatario\n- category: location\n  text: información de desplazamiento y ubicación geográfica aunque la aplicación no este siendo utilizada\n- category: device\n  text: información sobre el dispositivo de acceso del Usuario, sistema\
  \ operativo\n- category: communication\n  text: registro de mensajes de texto recibidos y enviados, los contactos privados y registro de llamadas del dispositivo\n    del usuario\n- category: behavioral\n  text: Cronología de accesos a la Página o aplicación (app)\npurposes:\n- purpose: Evaluación de perfiles crediticios\n  text: A. Evaluación de perfiles crediticios de Usuarios\n- purpose: Validación de identidad\n  text: B. Validación de Identidad e información proporcionada en el cuestionario\n- purpose: Requerimientos de pago\n  text: E. Requerimientos de pago y/o cumplimiento de sus obligaciones en los préstamos\n- purpose: Marketing\n  text: J. Para fines comerciales y publicitarios relacionados con los productos y servicios ofrecidos por Apurata.\nretention:\n- scope: Datos personales del Usuario\n  period: 10 (diez) años\n  text: conservándolos por 10 (diez) años, o por el plazo mayor que exijan las normas legales y regulatorias aplicables\nresidency:\n- region: Estados Unidos,\
  \ Brazil, Mexico, Alemania u otros países\n  text: serán almacenados en servidores que pueden estar ubicados en Estados Unidos, Brazil, Mexico, Alemania u\n    otros países\ntransfers:\n- mechanism: other\n  text: el Usuario autoriza la transferencia y el tratamiento de datos a la casa matriz de la sociedad comercial\n    Apurata, ubicada en el exterior\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Solicitud por correo a julia+revocar@apurata.com\n  text: dirigiéndose a julia+revocar@apurata.com\nrights:\n- right: Acceso\n  text: Los Usuarios de Apurata tendrán derecho de acceder a sus datos personales recabados\n- right: Rectificación\n  text: a hacer correcciones a los mismos en caso de ser estos inexactos o incompletos\n- right: Cancelación\n  text: a eliminar sus datos cuando consideren que no son necesarios para alguna de las finalidades señaladas\n- right: Oposición\n  text: a oponerse al uso/tratamiento de sus\
  \ datos\n- right: Revocación del consentimiento\n  text: revocar su consentimiento respecto al uso de sus datos personales\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apurata/privacy/apurata-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Apurata's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Buy Now Pay Later
- Installment Payments
- Consumer Credit
- Payments
- E-Commerce
- Peru
- Latin America
---
