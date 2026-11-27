---
api_specs:
- filename: university-of-navarra-harvesting-api-openapi.yml
  format: yaml
  label: University of Navarra Harvesting API
  slug: university-of-navarra-harvesting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-navarra/openapi/university-of-navarra-harvesting-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: la imagen de su DNI, la fotografía del interesado y sus datos identificativos se conservarán
  - category: contact
    text: los datos identificativos y de contacto, con la finalidad de mantener al interesado informado sobre productos o servicios similares
  - category: biometric
    text: Este tratamiento incluye el uso de técnicas biométricas para comparar una imagen facial (selfie) del interesado con su documento de identidad
  - category: communication
    text: podrá grabar las conversaciones con las personas que atienden la central telefónica
  deletion:
    route: Ejercicio del derecho de supresión por correo electrónico al DPO
    text: 'Cancelación del consentimiento y derecho de supresión: mediante los enlaces incluidos en las comunicaciones o por e-mail a dpo@unav.es'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Gestión de matrícula y expediente académico
    text: gestión de los procesos de matrícula, inscripción, administración y custodia del expediente académico
  - purpose: Envío de comunicaciones con consentimiento
    text: da su consentimiento a la Universidad de Navarra para que le envíe por medios postales o electrónicos comunicaciones relativas a sus actividades
  - purpose: Mejora de la calidad de atención telefónica
    text: con la finalidad de detectar deficiencias y oportunidades de mejora
  retention:
  - period: 1 año
    scope: Imágenes del documento de identidad y fotografía (enseñanzas propias)
    text: En el caso de que la matrícula no se complete, las imágenes del documento de identidad y la fotografía del interesado se eliminarán en el plazo máximo de 1 año.
  - period: 6 meses
    scope: Grabaciones de atención telefónica
    text: Las grabaciones se conservarán un máximo de 6 meses y serán suprimidas.
  - period: null
    scope: Datos identificativos y académicos (enseñanzas propias)
    text: Algunos datos se conservarán de forma indefinida, salvo que el interesado indique lo contrario
  rights:
  - right: Acceso
    text: Obtener confirmación sobre si en la Universidad de Navarra se están tratando datos personales que le conciernen o no
  - right: Rectificación
    text: Solicitar la RECTIFICACIÓN de aquellos que sean inexactos o incompletos.
  - right: Supresión
    text: Pedir la CANCELACIÓN o supresión de sus datos cuando legalmente se pueda
  - right: Limitación
    text: Solicitar en las circunstancias en las que la ley lo permite la LIMITACIÓN del tratamiento de sus datos
  - right: Oposición
    text: ejercitar su derecho de OPOSICIÓN al tratamiento de sus datos
  - right: Portabilidad
    text: En las circunstancias en que sea aplicable, solicitar la PORTABILIDAD de sus datos.
  - right: Retirar consentimiento
    text: retirar éste en el momento en que lo desee, sin que ello afecte a la legitimidad de los tratamientos ya realizados
  role:
    text: Sus datos son recogidos y serán tratados por la Universidad de Navarra
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Cuando así se indique en los formularios, la Universidad de Navarra podrá ceder sus datos de contacto a las siguientes entidades
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Intuit Inc. está sujeta a las obligaciones en materia de protección de datos personales europeas mediante Cláusulas Contractuales Tipo aprobadas por la Comisión Europea.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: University of Navarra
provenance_date: '2026-11-10'
provider_name: University of Navarra
provider_slug: university-of-navarra
slug: university-of-navarra-privacy-policy
source_date: '2026-11-10'
source_filename: university-of-navarra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.unav.edu/proteccion-de-datos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: University of Navarra\naid: university-of-navarra\nurl: https://www.unav.edu/proteccion-de-datos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Sus datos son recogidos y serán tratados por la Universidad de Navarra\ndata_categories:\n- category: identifying\n  text: la imagen de su DNI, la fotografía del interesado y sus datos identificativos se conservarán\n- category: contact\n  text: los datos identificativos y de contacto, con la finalidad de mantener al interesado informado sobre productos\n    o servicios similares\n- category: biometric\n  text: Este tratamiento incluye el uso de técnicas\
  \ biométricas para comparar una imagen facial (selfie) del interesado\n    con su documento de identidad\n- category: communication\n  text: podrá grabar las conversaciones con las personas que atienden la central telefónica\npurposes:\n- purpose: Gestión de matrícula y expediente académico\n  text: gestión de los procesos de matrícula, inscripción, administración y custodia del expediente académico\n- purpose: Envío de comunicaciones con consentimiento\n  text: da su consentimiento a la Universidad de Navarra para que le envíe por medios postales o electrónicos comunicaciones\n    relativas a sus actividades\n- purpose: Mejora de la calidad de atención telefónica\n  text: con la finalidad de detectar deficiencias y oportunidades de mejora\nretention:\n- scope: Imágenes del documento de identidad y fotografía (enseñanzas propias)\n  period: 1 año\n  text: En el caso de que la matrícula no se complete, las imágenes del documento de identidad y la fotografía del\n    interesado se eliminarán\
  \ en el plazo máximo de 1 año.\n- scope: Grabaciones de atención telefónica\n  period: 6 meses\n  text: Las grabaciones se conservarán un máximo de 6 meses y serán suprimidas.\n- scope: Datos identificativos y académicos (enseñanzas propias)\n  period: null\n  text: Algunos datos se conservarán de forma indefinida, salvo que el interesado indique lo contrario\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Intuit Inc. está sujeta a las obligaciones en materia de protección de datos personales europeas mediante\n    Cláusulas Contractuales Tipo aprobadas por la Comisión Europea.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ejercicio del derecho de supresión por correo electrónico al DPO\n  text: 'Cancelación del consentimiento y derecho de supresión: mediante los enlaces incluidos en las comunicaciones\n    o por e-mail a dpo@unav.es'\nrights:\n- right: Acceso\n  text: Obtener confirmación sobre si en la Universidad\
  \ de Navarra se están tratando datos personales que le conciernen\n    o no\n- right: Rectificación\n  text: Solicitar la RECTIFICACIÓN de aquellos que sean inexactos o incompletos.\n- right: Supresión\n  text: Pedir la CANCELACIÓN o supresión de sus datos cuando legalmente se pueda\n- right: Limitación\n  text: Solicitar en las circunstancias en las que la ley lo permite la LIMITACIÓN del tratamiento de sus datos\n- right: Oposición\n  text: ejercitar su derecho de OPOSICIÓN al tratamiento de sus datos\n- right: Portabilidad\n  text: En las circunstancias en que sea aplicable, solicitar la PORTABILIDAD de sus datos.\n- right: Retirar consentimiento\n  text: retirar éste en el momento en que lo desee, sin que ello afecte a la legitimidad de los tratamientos ya\n    realizados\nsale_or_sharing:\n  stance: conditional\n  text: Cuando así se indique en los formularios, la Universidad de Navarra podrá ceder sus datos de contacto a\n    las siguientes entidades\n"
source_yaml_url: https://artifacts.apis.io/university-of-navarra/privacy/university-of-navarra-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from University of Navarra's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Spain
- Private Research University
- Open Access
- Institutional Repository
- Scholarly Publishing
- OAI-PMH
- Identity Federation
- Library
---
