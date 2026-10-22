# Biblia del caso · Logística

<!-- Etapa A (encargo A2). Fuente única de la historia del sector: si un curso dice una cifra o un nombre distinto al de la Biblia, el curso está mal. Cada cifra lleva su fuente. Lo que no consta se escribe «No consta» y queda en la sección 9. Las decisiones de esta etapa están en la sección 10. -->

| Campo | Valor |
| --- | --- |
| Sector | Logística, transporte y comercio exterior |
| Responsable del sector | Carolina Barraza |
| Fuentes | `02_caso_referencia.md` · `01_principios.md` · `03_rutas_por_rol.md` (versiones con las correcciones de A1 aplicadas, según `00_REGISTRO_CAMBIOS.md`) · `AUDITORIA-COHERENCIA-Logística.md` (versión de cierre, sección 11) · `INVENTARIO-Logística.md` · fichas corregidas `LOG-*.md` |
| Decisiones de A2 | Paquete de aprobación del 2026-10-21 (DD-9 a DD-22, sin objeciones) y respuestas a P-ronda 1, 2 y 3 (sección 10) |
| Aprobada por | Carolina Barraza, responsable del sector · 2026-10-21 |
| Revisada por dirección pedagógica | Pendiente · antes del segundo curso del sector |

Forma de citar: `02` es el caso de referencia, `01` los principios, `03` las rutas, «Auditoría» la auditoría de coherencia de cierre y «LOG-XXX-nn» la ficha corregida de cada curso.

## 1. Aviso de ficción

Todas las empresas, personas, sistemas y datos de este caso son ficticios. Cualquier parecido con empresas o personas reales es coincidencia. El caso usa datos sintéticos (`02`: «Las empresas y cifras son ficticias, y el proyecto usa datos sintéticos.»). Este aviso se repite en toda pieza que use el caso.

Las normas que citan los cursos son las de Colombia, la jurisdicción de referencia del caso (P-ronda 2). Que las normas sean reales no hace reales a las empresas, las personas, los lugares ni los datos.

## 2. Las empresas del caso

### 2.1 Empresas con nombre

| Empresa | Qué hace | Papel en el caso | Fuente |
| --- | --- | --- | --- |
| TransAndes Logística | Operador logístico integral: tres CEDI, 400 camiones propios y de terceros, una agencia de aduanas, una zona franca y un equipo de carga internacional. Trabaja con márgenes estrechos. | Empresa del caso. Ejecuta el Programa Corredor Pacífico | `02`, «TransAndes Logística hoy» · `01`, «Caso de referencia» |
| Alimentos Cordillera | Fabrica galletas y las exporta a tres países. Es una de las cuentas más grandes de TransAndes: usa su carga internacional, sus CEDI y su transporte. | Cliente principal | `02` · ADU-03, Contexto · COM-04, Contexto |
| Vitalia | Medicamentos con cadena de frío, incluidos medicamentos controlados. Algunos productos que viajan con ellos (alcoholes y aerosoles) son mercancías peligrosas. Tiene su propia área de calidad, que decide sobre su producto. | Cliente principal | `02` · CED-03, HSQ-02 y TCT-02, Contexto |
| Distribuidora Andina | Distribuye a tenderos. Distribuye también productos de Cordillera. | Cliente principal | `02` · COM-04, Contexto |
| Altiplano Sur | Su concentrado se lleva al puerto. Exige carga cubierta. | Cliente principal | `02` · TRC-03, Contexto · TRA-01, clase 2.1 |

Los cuatro clientes principales «son los otros casos del catálogo» (`02`). Son cuatro, no cinco (Auditoría, decisión 7 y H7).

### 2.2 Actores sin nombre

Ninguno tiene nombre en las fuentes. Si un curso necesita nombrarlo, el nombre se crea como ficticio y entra a esta Biblia por pull request (DD-10).

| Actor | Papel | Fuente |
| --- | --- | --- |
| Transportadores terceros | Decenas, muchos propietarios de uno o dos vehículos. Se les paga por viaje. Las fuentes no coinciden sobre si su GPS y su telemetría están integrados: ver PEND-19 | TRA-02, Contexto · DIR-02, Contexto · PEND-19 |
| Tenderos | Miles de tiendas de barrio a las que TransAndes entrega cada día por cuenta de Andina | UMI-01, Contexto |
| Navieras y aerolíneas | Transportan las exportaciones e importaciones. Los hitos de las navieras llegan por integraciones aprobadas en TCT-01. No consta cómo llegan los hitos de las aerolíneas | CAR-01, CAR-02 · DD-4 |
| Farmacias | Devuelven medicamentos de Vitalia | UMI-03, Contexto |
| Cadena de farmacias | Abre una licitación de distribución nacional: cliente potencial de COM-01 | COM-01, Contexto |
| Usuario operador de la zona franca | Entidad ante la que se registra cada movimiento de la zona franca | ZFR-01, Contexto |
| Autoridades | Autoridad aduanera, autoridad sanitaria y autoridad de datos. Sus nombres no constan en las fuentes; cada curso cita la autoridad colombiana que corresponda y la verifica | ADU-01, ADU-02, ZFR-02, TIC-04 · P-ronda 2 |

## 3. Personas y órganos

### 3.1 Personas

Ningún documento nombra a una persona (Inventario 2.2: «`02` no nombra a ninguna persona: No consta ningún nombre propio»). Por eso esta sección registra roles. Nombre de cada rol: **No consta**.

| Rol | Empresa | Lo que decide o hace en el caso | Aparece desde | Fuente |
| --- | --- | --- | --- | --- |
| Gerente general | TransAndes | Miembro del comité del programa | Antes del programa | `02` · `01` |
| Gerente de operaciones | TransAndes | Miembro del comité del programa. Aprueba la política de IA (TRC-01) | Antes del programa | `02` · `01` |
| Gerente financiero | TransAndes | Miembro del comité del programa | Antes del programa | `02` · `01` |
| Analista de monitoreo | TransAndes | Decide la acción ante cada excepción y la comunicación al cliente | Antes del programa (la torre de control es un departamento) | `02`, tabla de 2027 · TCT-01 |
| Especialista en clasificación arancelaria | TransAndes | Clasifica y decide la clasificación definitiva | Antes del programa | `02`, tabla de 2027 · H34 |
| Declarante | TransAndes | Revisa, firma y transmite cada declaración | Antes del programa | `02` · ADU-02 |
| Auxiliar de aduanas | TransAndes | Prepara los expedientes para la firma del declarante | Antes del programa | `01` · ADU-02 |
| Director de aduanas | TransAndes | Mantiene los requisitos del Operador Económico Autorizado | Antes del programa | `01` · ADU-04 |
| Jefe de inventario de zona franca | TransAndes | Firma la conciliación con la autoridad | Antes del programa | `02` · `01` |
| Gerente de CEDI | TransAndes | Aprueba el layout y las reglas de ubicación | Antes del programa | `02` · CED-01 |
| Planeador de transporte | TransAndes | Aprueba las rutas | Antes del programa | `02` · TRA-01 |
| Jefe de tráfico | TransAndes | Asigna los viajes y decide cuando falla una verificación del vehículo | Antes del programa | `01` · TRA-04 |
| Coordinador de última milla | TransAndes | Ajusta el ruteo y revisa las novedades | Antes del programa | `02` · UMI-01, UMI-02 |
| Agente de servicio al cliente | TransAndes | Resuelve lo que el asistente escala | Antes del programa | `02`, tabla de 2027 |
| Coordinador HSEQ | TransAndes | Autoriza cada despacho de mercancías peligrosas | Antes del programa | `02` · HSQ-02 |
| Gerente comercial | TransAndes | Decide tarifas y ofertas | Antes del programa | `02` · COM-02 |
| Arquitecto de integraciones | TransAndes | Aprueba cada acceso a datos de clientes | Antes del programa | `02` · TIC-02 |
| Ejecutivo de cuenta de Cordillera | TransAndes | Maneja la relación con Cordillera; habla con compras | Antes del programa | COM-04, Contexto |
| Operarios, conductores y auxiliares | TransAndes y terceros | Toman sus cursos en el celular. Ninguno tiene ruta de salida | Antes del programa | `02` · `01` |
| Calidad de Vitalia | Vitalia | Decide qué se hace con el producto ante una excursión de temperatura y libera las devoluciones | Antes del programa | TCT-02, Contexto · UMI-03 |
| Equipo comercial de Cordillera | Alimentos Cordillera | Recibe la guía de Incoterms | Fase 6 (CAR-03) | CAR-03, Resultado |
| Profesor | Edutin | Construye el Programa Corredor Pacífico completo | — | `02` |

La tabla «Roles antes y después de la transformación» de `01` lista los demás roles del sector y su potencial de productividad.

### 3.2 Órganos de decisión

| Órgano | Composición | Lo que aprueba en el caso | Fuente |
| --- | --- | --- | --- |
| Comité del programa | Gerente general, gerente de operaciones y gerente financiero | Dirige el piloto | `02`, «El Programa Corredor Pacífico» |
| Junta directiva | No consta | La hoja de ruta (DIR-01), el marco de gobierno de datos (DIR-03) y el portafolio de servicios nuevos (DIR-04) | DD-5 · DIR-01, DIR-03, DIR-04 |
| Comité financiero | No consta | El caso de negocio del piloto (DIR-02) | DD-5 · H18 · DIR-02 |
| Comité comercial | No consta | Las ofertas (COM-01) y los planes de cuenta (COM-04) | DD-5 · COM-01, COM-04 |
| Comité de operaciones | Las áreas de la operación; composición exacta no consta | Recibe el reporte semanal (TRC-02), el análisis del corredor (TRC-04) y el informe mensual (TIC-03) | DD-12 · TRC-04: «en el comité cada área mira hacia la última milla» |

«El comité», sin calificativo, en TRC-02, TRC-04 y TIC-03 es el comité de operaciones (DD-12).

## 4. Sistemas, productos y documentos del caso

### 4.1 Lo que existe antes del programa

Ningún sistema tiene marca ni nombre propio en las fuentes; se nombran por su función (DD-11).

| Nombre | Qué es | Existe desde | Fuente |
| --- | --- | --- | --- |
| Tres CEDI | CEDI 1 (el CEDI principal), CEDI 2 y un tercer CEDI. El CEDI 2 recibe alimentos y químicos de limpieza y se llena en diciembre con Andina; su turno de noche usaba una versión impresa vieja de un procedimiento. El uso del tercer CEDI no consta | Antes del programa | `02` · CED-01 · DIR-04 · TRC-03 · DD-13 |
| Cámara fría y área habilitada para medicamentos | La cámara fría está en los CEDI. TransAndes guarda los medicamentos de Vitalia en un área con habilitación sanitaria, que no alcanza para el servicio nuevo de DIR-04 | Antes del programa | CED-02 · DIR-04 · DD-3 |
| Flota | 400 camiones propios y de terceros | Antes del programa | `02` |
| Agencia de aduanas | Agencia propia de TransAndes. El año pasado tuvo una sanción | Antes del programa | `02` · ADU-04 |
| Zona franca | Guarda mercancía de varios clientes, extranjera y nacional | Antes del programa | `02` · ZFR-01 |
| Torre de control (departamento) | Departamento de la operación con jefe y analistas de monitoreo | Antes del programa | `01`, departamentos · Auditoría, sección 7 |
| WMS | Sistema del almacén: pedidos, despachos e inventario | Antes del programa | TRC-02, clase 1.1 · TIC-02 |
| TMS | Sistema de transporte: viajes, entregas y, desde TCT-01, hitos de las navieras | Antes del programa | TRC-02, clase 1.1 · DD-4 |
| Sistema aduanero | Sistema donde el declarante firma y transmite con su firma digital | Antes del programa | ADU-02 · TIC-02 |
| Facturación | Sistema de facturación de los servicios | Antes del programa | TRC-02 · TIC-03 |
| Telemetría de la flota propia | Eventos de velocidad, frenadas, horas y códigos de falla por marca | Antes del programa | HSQ-01 · TRA-03 |
| Plataformas de GPS de los transportadores | Plataformas de cada tercero. Hoy algunos analistas entran con claves que los terceros mandan por correo | Antes del programa | TCT-01, Contexto |
| Registradores de temperatura | Equipos que registran la temperatura de cada envío; algunos con la calibración vencida | Antes del programa | HSQ-02 · CED-04 |
| Certificaciones | Dos certificaciones del sistema de gestión, ISO 9001 y BASC (HSQ-03: «mantiene dos certificaciones»), y la de Operador Económico Autorizado (ADU-04, TRC-05) | Antes del programa | HSQ-03 · ADU-04 · TRC-05 |

### 4.2 Lo que produce el programa

El nombre del entregable sale de la columna «Proyecto de referencia» de `01`. El momento sale de la sección 6.

| Entregable | Lo produce | Existe desde | Fuente |
| --- | --- | --- | --- |
| Política de uso de IA de TransAndes | TRC-01 | Fase 0 | `01` |
| Reporte semanal del área (y del corredor) | TRC-02 | Fase 0 | `01` · TRC-02 |
| Procedimientos del corredor y matriz de requisitos de los cuatro clientes | TRC-03 | Fase 0 | `01` · H7 |
| Análisis de un año de pedidos, tiempos y novedades del corredor | TRC-04 | Fase 0 | `01` |
| Matriz de riesgos de seguridad del corredor | TRC-05 | Fase 0 | `01` |
| Hoja de ruta del Programa Corredor Pacífico | DIR-01 | Fase 1 | `01` |
| Caso de negocio del piloto | DIR-02 | Fase 1 | `01` · H18 |
| Marco de gobierno de datos de clientes, permisos y límites de la IA | DIR-03 | Fase 1 | `01` |
| Integración de pedidos con Cordillera y Andina (EDI y API) | TIC-01 | Fase 2 | `01` |
| Gestor de secretos con las credenciales de cada cliente | TIC-01 | Fase 2. No consta si existía antes | TIC-01 |
| Evaluación de riesgos y controles de acceso a datos de clientes | TIC-04 | Fase 2 | `01` |
| Servidor MCP de solo lectura sobre el WMS, el TMS y el sistema aduanero | TIC-02 | Fase 2 | `01` · H5 |
| Aplicación del conductor (documentos de viaje y reporte de novedades) | TRA-04 | Fase 3 | `01` · H1 |
| Tablero de visibilidad del corredor con alertas de excepción (la torre de control como producto) | TCT-01 | Fase 3 | `01` |
| Integraciones aprobadas con las navieras | TCT-01 | Fase 3 | DD-4 |
| Protocolo de excepciones con mensajes aprobados por cliente | TCT-02 | Fase 3 | `01` |
| Propuestas de clasificación arancelaria con fundamento | ADU-01 | Fase 4 | `01` |
| Expediente de importación completo para revisión y firma del declarante | ADU-02 | Fase 4 | `01` |
| Beneficios arancelarios para las exportaciones de Cordillera | ADU-03 | Fase 4 | `01` |
| Matriz de requisitos OEA con evidencia | ADU-04 | Fase 4 | `01` |
| Proceso de ingreso y salida de la zona franca con controles | ZFR-01 | Fase 4 | `01` |
| Conciliación del inventario de la zona franca con los registros ante la autoridad | ZFR-02 | Fase 4 | `01` |
| Propuesta de acondicionamiento para Vitalia | ZFR-03 | Fase 4 | `01` |
| Layout y reglas de ubicación (slotting) del CEDI principal | CED-01 | Fase 5 | `01` |
| Estándares de picking por operario y turno | CED-02 | Fase 5 | `01` |
| Programa de conteo cíclico y exactitud por cliente | CED-03 | Fase 5 | `01` |
| Asistente de bodega con requisitos de cada cliente | CED-04 | Fase 5 | `01` |
| Plan nacional de rutas con consolidación | TRA-01 | Fase 5 | `01` |
| Tablero de costo por kilómetro y desempeño de transportadores | TRA-02 | Fase 5 | `01` |
| Alertas de falla desde la telemetría | TRA-03 | Fase 5 | `01` |
| Ruteo diario de entregas a los tenderos de Andina | UMI-01 | Fase 5 | `01` |
| Flujo de prueba de entrega con novedades clasificadas | UMI-02 | Fase 5 | `01` |
| Proceso de devoluciones con clasificación y destino | UMI-03 | Fase 5 | `01` |
| Tablero OTIF por cliente con causas de incumplimiento | TCT-03 | Fase 5 | `01` · H2 |
| Modelo de datos del corredor con sus tableros | TIC-03 | Fase 5 | `01` · H3 |
| Guía de Incoterms aplicada a las exportaciones de Cordillera | CAR-03 | Fase 6 | `01` |
| Modelo de cotización marítima y aérea | CAR-01 | Fase 6 | `01` |
| Seguimiento de embarques con BL, AWB y documentos al día | CAR-02 | Fase 6 | `01` |
| Matriz de requisitos ISO 9001 y BASC con evidencia | HSQ-03 | Fase 6 | `01` |
| Protocolo de medicamentos de Vitalia con registros de temperatura | HSQ-02 | Fase 6 | `01` |
| Análisis de telemetría y plan de seguridad vial por conductor | HSQ-01 | Fase 6 | `01` |
| Asistente de seguimiento de pedidos con escalamiento (asistente de servicio) | COM-03 | Fase 6 | `01` · H5 |
| Costo por pedido y por cliente (costeo ABC) | ADM-01 | Fase 7 | `01` |
| Matriz de tarifas y margen por cliente y servicio | COM-02 | Fase 7 | `01` |
| Facturación con conciliación contra la operación | ADM-02 | Fase 7 | `01` |
| Portafolio de servicios nuevos (logística farmacéutica y de exportación) | DIR-04 | Fase 7 | `01` |
| Propuesta logística completa para un cliente nuevo | COM-01 | Fase 7 | `01` |
| Plan de cuenta de Alimentos Cordillera | COM-04 | Fase 7 | `01` |
| Matriz de competencias y plan de formación móvil | ADM-04 | Fase 7 | `01` |
| Plan de cambio para CEDI y flota | ADM-03 | Fase 7 | `01` · H4 |

### 4.3 Material del profesor

| Nombre | Qué es | Fuente |
| --- | --- | --- |
| Expediente de referencia | Carpeta de datos sintéticos organizada por fases: un año de pedidos, tiempos y novedades del corredor, inventarios y movimientos de los tres CEDI, viajes y telemetría de la flota, entregas a tenderos, declaraciones aduaneras, documentos de embarque, registros de zona franca, contratos y tarifas de clientes, y conversaciones de servicio al cliente. Guarda también las conversaciones con Claude del profesor | `02`, «El caso como eje del diseño instruccional» |

## 5. Cifras que se repiten

Cómo se leen (Auditoría 11.2 · `02`, «Cómo leer los indicadores»):

- Las cifras «hoy» describen el inicio del programa y se mantienen en las fichas hasta el curso que las mueve.
- Las metas son metas de diseño, no promesas ni resultados demostrados (C7).
- El caso no da valores intermedios. Cuando un curso los necesita, se recrean como material del caso y se marcan así (regla R2).
- Los resultados que una ficha anticipa en sus procedimientos no son cifras de esta Biblia: los fija el registro firmado del laboratorio (DD-16).

Cuando dos documentos dan cifras o lecturas distintas para el mismo dato, se ponen las dos y se marcan «Pendiente»: la Biblia no elige. Hay tres casos: el rango de temperatura de Vitalia (PEND-18), la integración de GPS y telemetría de los terceros (PEND-19) y el número de departamentos (PEND-20). Los indicadores de `02` y las aceleraciones de las 48 fichas, de `01` y de `03` coinciden entre sí.

### 5.1 La empresa y el programa

| Cifra | Valor | Desde qué momento es cierta | Fuente | Estado |
| --- | --- | --- | --- | --- |
| CEDI | 3 | Antes del programa | `02`: «TransAndes tiene tres CEDI, 400 camiones propios y de terceros…» | Confirmada |
| Camiones propios y de terceros | 400 | Antes del programa | `02` (misma frase) · DIR-01, Contexto | Confirmada |
| Proporción de camiones propios y de terceros | No consta. Las fichas dicen «buena parte» son de terceros | — | DIR-01, DIR-02 · H17 | Pendiente (PEND-5) |
| Transportadores terceros | Decenas | Antes del programa | TRA-02: «trabaja con decenas de transportadores terceros» | Confirmada |
| Agencias de aduanas · zonas francas | 1 · 1 | Antes del programa | `02` | Confirmada |
| Clientes principales | 4 | Antes del programa | `02` · decisión 7 · H7 | Confirmada |
| Tenderos atendidos | Miles, cada día | Antes del programa | UMI-01: «TransAndes entrega cada día a miles de tenderos» | Confirmada |
| Personas a las que llega el programa | Cientos, por turnos, con rotación alta | Antes del programa | ADM-03, Contexto | Confirmada |
| Departamentos | Dos cifras: 11 en tres frentes, según el texto y el diagrama · 12, según las filas de la tabla, que incluye Dirección | Antes del programa | `01`: «El operador se organiza en 11 departamentos agrupados en tres frentes» · `01`, tabla «Departamento \| Roles» (12 filas) | Pendiente (PEND-20) |
| Miembros del comité del programa | 3 | Inicio del programa | `02` | Confirmada |
| Aliados técnicos | 2: integraciones y datos | Inicio del programa | `02` | Confirmada |
| Hallazgos del diagnóstico | 3: nadie ve el corredor completo; la aduana pierde días por expedientes incompletos; los datos de los clientes circulan sin control | Fase 1 | `02` | Confirmada |
| Componentes del programa | 6: torre de control, aduana ágil, CEDI productivo, transporte optimizado, última milla y servicio al cliente | Inicio del programa | `02` | Confirmada |
| Cursos del sector | 48: 5 del tronco común y 43 de rol | — | `01` | Confirmada |
| Rutas por rol | 26 | — | `01`, tabla de rutas | Confirmada |
| Países a los que exporta Cordillera | 3 | Antes del programa | ADU-03, Contexto | Confirmada |
| Regiones donde los tenderos pagan en efectivo al recibir | 2 | Antes del programa | UMI-01, Contexto · TRC-03, clase 2.1 | Confirmada |
| Rango de temperatura de Vitalia | Dos cifras: entre 2 y 8 grados para Vitalia, con registro continuo · por producto: varios entre 15 y 25 grados y dos congelados | Antes del programa | TRC-03, Contexto: «Vitalia exige entre 2 y 8 grados con registro continuo» · HSQ-02, clase 1.1 (procedimiento): «varios son de temperatura controlada entre 15 y 25 grados y dos son congelados» | Pendiente (PEND-18). La cifra de HSQ-02 está en un procedimiento y puede cambiar con su registro firmado (DD-16) |
| Sistemas que combina el reporte semanal | 3: WMS, TMS y facturación | Fase 0 | TRC-02, Contexto y clase 1.1 | Confirmada |

### 5.2 Indicadores: situación al inicio y meta a 12 meses

| Indicador | Al inicio | Meta a 12 meses | Fuente | Estado |
| --- | --- | --- | --- | --- |
| OTIF del corredor | 86% | 94% | `02` · TRC-02, TRC-04, TCT-03 | Confirmada. 94% es meta de diseño (DD-2) |
| Excepciones detectadas antes que el cliente | 30% | 80% | `02` · TCT-01 | Confirmada |
| Tiempo de nacionalización | 4 días | 2 días | `02` · ADU-02 | Confirmada |
| Declaraciones aduaneras con correcciones | 9% | 3% | `02` · ADU-01, ADU-04 | Confirmada |
| Exactitud de inventario en los CEDI | 94% | 99% | `02` · CED-03 | Confirmada |
| Productividad de picking | Sin estándar por operario | +15% a +25% sobre la línea base | `02` · CED-02 | Confirmada |
| Kilómetros en vacío | 28% | 18% a 20% | `02` · TRA-01 | Confirmada |
| Entregas a tenderos con novedad | 12% | 6% | `02` · UMI-01, UMI-02 | Confirmada |
| Llamadas al servicio al cliente que preguntan por un pedido | 60% del total | No consta | `02` · DIR-01, COM-03 | Confirmada |
| Consultas de pedidos resueltas por el asistente | Ninguna | 50% a 70% | `02` · COM-03 | Confirmada |
| Accidentes viales | Línea base del año | −30% | `02` · `01` · HSQ-01 | Confirmada |
| Documentos de clientes fuera de herramientas aprobadas | Frecuente | Cero | `02` · TRC-01 | Confirmada |
| Uso de IA | Sin reglas; documentos de clientes copiados a herramientas públicas | — | `02` | Confirmada |

### 5.3 Metas de los cursos que se repiten en varios documentos

Las demás aceleraciones de cada curso están en su ficha y coinciden con `01`.

| Cifra | Valor | Fuente | Estado |
| --- | --- | --- | --- |
| Casos de uso con retorno medido | Al menos 3 en 12 meses | `01` · DIR-01 | Confirmada |
| Ingresos de servicios nuevos | 10% a 15% del total en 24 meses | `01` · DIR-04 | Confirmada |
| Adopción del cambio | 70% en 90 días | `01` · ADM-03 | Confirmada. Los 90 días son duración del relato (R2) |
| Ingresos por cuenta clave | +10% a +15% en 12 meses | `01` · COM-04 | Confirmada |
| Excursiones de temperatura | −50% | `01` · HSQ-02 | Confirmada |

### 5.4 Calendario y estacionalidad

| Dato | Valor | Fuente | Estado |
| --- | --- | --- | --- |
| Duración de las fases 1 a 5 | 6, 8, 8, 12 y 16 semanas | `02`, tabla de fases | Confirmada |
| Inicio de la fase 6 | Mes 5, contado desde el inicio de la fase 1 | `02` · DD-7 | Confirmada |
| Fase 7 | Continua | `02` · DD-6 | Confirmada |
| Fecha de inicio del programa y duración de la fase 0 | No consta | `02` | Pendiente (PEND-1) |
| Año del modelo operativo | 2027 | `02`, «TransAndes 2027» | Confirmada. Su relación con la semana 1 no consta |
| Pico del año | Diciembre: personal temporal, CEDI 2 lleno con Andina, caída del OTIF de Andina | ADM-03 · DIR-04 · COM-01 · TCT-03 | Confirmada. Es estacionalidad del relato, no una fecha (DD-15) |
| Valle del año | Enero: el CEDI medio vacío | ADM-01, Contexto | Confirmada. Estacionalidad del relato |
| «Piloto de 90 días» | Diagrama de olas de `01` | `01` · R2 · H16 | Duración del relato: no limita la línea de tiempo |

## 6. Línea de tiempo y «Momento del caso» por curso

Las fases 1 a 5 van seguidas, y las semanas se cuentan desde el inicio de la fase 1. La fase 6 es una ventana que se abre en el mes 5 y la fase 7 es una ventana continua: en las dos, cada curso ocurre cuando existen sus insumos (decisión 4, DD-6, DD-7).

La regla de dependencias: ningún curso ocurre antes de que existan todos los entregables que usa en su laboratorio, su actividad o su evidencia (decisión 5).

### 6.1 Fases

| Fase | Qué pasa en el caso | Cursos que ocurren en este momento | Qué existe ya | Qué todavía no existe |
| --- | --- | --- | --- | --- |
| 0 · Tronco común (antes de la semana 1) | Se aprueba la política de IA. Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado | TRC-01 → TRC-02 · TRC-03 · TRC-04 · TRC-05 | Todo lo de 4.1 | Todos los entregables de 4.2 |
| 1 · Diagnóstico, caso y gobierno (semanas 1 a 6) | Diagnóstico con tres hallazgos. Hoja de ruta, caso de negocio del piloto y gobierno de los datos de clientes | DIR-01 → DIR-02 · DIR-03 | Lo anterior y los cinco entregables del tronco común | Integraciones, servidor MCP, tablero de la torre, aplicación del conductor |
| 2 · Datos e integraciones (semanas 7 a 14) | Integración con Cordillera y Andina, evaluación de seguridad y servidor MCP de solo lectura | TIC-01 → TIC-04 → TIC-02 | Lo anterior, la hoja de ruta, el caso de negocio y el marco de gobierno | Tablero de la torre, aplicación del conductor, asistente de servicio |
| 3 · Torre de control y conductor conectado (semanas 15 a 22) | Aplicación del conductor, tablero de visibilidad con alertas y protocolo de excepciones | TRA-04 → TCT-01 → TCT-02 | Lo anterior, las integraciones con Cordillera y Andina, la evaluación de riesgos y el servidor MCP | Tablero OTIF, prueba de entrega, modelo de datos, asistente de servicio |
| 4 · Aduana y zona franca (semanas 23 a 34) | OEA, clasificación, expedientes, tratados, y operación e inventario de la zona franca | ADU-01 → ADU-02 → ADU-04 · ADU-03; ADU-02 → ZFR-01 → ZFR-02 → ZFR-03 | Lo anterior, la aplicación del conductor, el tablero de la torre, las integraciones con navieras y el protocolo de excepciones | Entregables de CEDI, transporte y última milla, tablero OTIF, modelo de datos |
| 5 · CEDI, transporte, última milla y nivel de servicio (semanas 35 a 50) | Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, ruteo, prueba de entrega, devoluciones, OTIF y modelo de datos | CED-01 → CED-02 → CED-03 · CED-04; TRA-01 → TRA-02 → TRA-03; UMI-01 → UMI-02 → UMI-03; UMI-02 → TCT-03 → TIC-03 | Lo anterior y los entregables de aduana y zona franca | Costeo, tarifas, facturación conciliada, plan de cambio |
| 6 · Carga, HSEQ y servicio (ventana desde el mes 5) | Cotización, embarques, Incoterms, seguridad vial, cadena de frío, certificaciones y asistente de servicio | CAR-03 → CAR-01 → CAR-02 (después de TCT-01) · HSQ-03 · HSQ-02 (desde el mes 5); HSQ-01 (después de TRA-01); COM-03 (después de UMI-03 y de TCT-02) | Lo que exista cuando ocurre cada curso | El asistente de servicio, hasta COM-03 |
| 7 · Negocio y escala (continua) | Costeo, facturación, soluciones, pricing, cuentas clave, formación, plan de cambio y nuevos servicios | ADM-01 → COM-02 → ADM-02; DIR-04; ADM-01 y DIR-04 → COM-01; COM-02 y DIR-04 → COM-04; ADM-04 → ADM-03 (también después de HSQ-01) | Lo que exista cuando ocurre cada curso. El plan de cambio no existe hasta ADM-03 | — |

Fuente de la tabla: Auditoría, sección 1 · `02`, tabla de fases.

### 6.2 «Momento del caso» de cada curso

Ninguna ficha tenía campo de fase; el momento de cada curso es este (Auditoría, sección 2). La columna «Va después de» reúne tres cosas que la Auditoría no siempre separa: dependencias citadas en una ficha, orden de una ruta e inferencias. Las filas en las que se sabe que no es una dependencia citada lo dicen entre paréntesis. A3 confirma cada dependencia con la frase de la ficha (PEND-21).

| Código | Momento del caso | Va después de |
| --- | --- | --- |
| TRC-01 | Fase 0 · primer curso del tronco | — |
| TRC-02 | Fase 0 · después de TRC-01 | TRC-01 |
| TRC-03 | Fase 0 · después de TRC-01 | TRC-01 |
| TRC-04 | Fase 0 · después de TRC-01 | TRC-01 |
| TRC-05 | Fase 0 · después de TRC-01 | TRC-01 |
| DIR-01 | Fase 1 · primer curso | — |
| DIR-02 | Fase 1 · después de DIR-01 (inferido: valora el piloto que elige DIR-01) | DIR-01 (inferido) |
| DIR-03 | Fase 1 · sin dependencia dentro de la fase | — |
| TIC-01 | Fase 2 · primer curso | — |
| TIC-04 | Fase 2 · después de TIC-01 | TIC-01 |
| TIC-02 | Fase 2 · después de TIC-04; usa las integraciones de TIC-01 | TIC-04 (orden de la ruta) · TIC-01 · DIR-03 (la Auditoría no precisa si es insumo de TIC-02 o de TIC-04) |
| TRA-04 | Fase 3 · antes de TCT-01 | — |
| TCT-01 | Fase 3 · después de TRA-04 y de TIC-02 | TRA-04 · TIC-02 · TRC-05 |
| TCT-02 | Fase 3 · después de TCT-01 | TCT-01 |
| ADU-01 | Fase 4 · primer curso | — |
| ADU-02 | Fase 4 · después de ADU-01 | ADU-01 |
| ADU-04 | Fase 4 · después de ADU-02 | ADU-01 · ADU-02 |
| ADU-03 | Fase 4 · después de ADU-01 | ADU-01 (la Auditoría no dice si es dependencia citada u orden de la ruta) |
| ZFR-01 | Fase 4 · después de ADU-02 | ADU-02 |
| ZFR-02 | Fase 4 · después de ZFR-01 | ZFR-01 |
| ZFR-03 | Fase 4 · después de ZFR-02 | ZFR-02 |
| CED-01 | Fase 5 · primer curso de CEDI | — |
| CED-02 | Fase 5 · después de CED-01 | CED-01 |
| CED-03 | Fase 5 · después de CED-02 | CED-02 (orden de la ruta) |
| CED-04 | Fase 5 · sin dependencia dentro de la fase | TRC-05 |
| TRA-01 | Fase 5 · primer curso de transporte | TRC-03 |
| TRA-02 | Fase 5 · después de TRA-01 | TRA-01 |
| TRA-03 | Fase 5 · después de TRA-02 | TRA-02 |
| UMI-01 | Fase 5 · primer curso de última milla | — |
| UMI-02 | Fase 5 · después de UMI-01 | UMI-01 |
| UMI-03 | Fase 5 · después de UMI-02 | UMI-02 · TRC-03 |
| TCT-03 | Fase 5 · después de UMI-02 | UMI-02 · TCT-02 |
| TIC-03 | Fase 5 · después de TCT-03 | TCT-03 |
| CAR-03 | Fase 6 · desde el mes 5 · primer curso de carga | — |
| CAR-01 | Fase 6 · después de CAR-03 | CAR-03 |
| CAR-02 | Fase 6 · después de CAR-01 y de TCT-01 | CAR-01 · TCT-01 · TIC-02 · TRC-05 |
| HSQ-03 | Fase 6 · desde el mes 5 | — |
| HSQ-02 | Fase 6 · desde el mes 5 | — |
| HSQ-01 | Fase 6 · después de TRA-01 | TRA-01 |
| COM-03 | Fase 6 · después de UMI-03 y de TCT-02 | TIC-02 · TCT-02 · UMI-03 · TRC-05 |
| ADM-01 | Fase 7 · después de UMI-02 | UMI-02 |
| COM-02 | Fase 7 · después de ADM-01 | ADM-01 |
| ADM-02 | Fase 7 · después de COM-02 | COM-02 · UMI-02 |
| DIR-04 | Fase 7 · sin dependencia | — |
| COM-01 | Fase 7 · después de ADM-01 y de DIR-04 | ADM-01 · DIR-04 · CED-01 · TCT-03 |
| COM-04 | Fase 7 · después de COM-02 y de DIR-04 | COM-02 · DIR-04 · TCT-03 · ADU-03 · DIR-03 |
| ADM-04 | Fase 7 · sin dependencia | — |
| ADM-03 | Fase 7 · después de ADM-04 y de HSQ-01 | ADM-04 · HSQ-01 · TRA-04 · CED-02 |

La columna «Va después de» se construyó con la sección 2 y la lista de insumos de la sección 7 de la Auditoría. El orden de producción definitivo, con cada frase de ficha, es el encargo A3.

### 6.3 Hechos fijos de la línea de tiempo

| Hecho | Fuente |
| --- | --- |
| Los entregables del tronco común existen desde el inicio de la fase 1. Cada participante hace solo los cursos del tronco que pide su ruta; TRC-01 está en todas | Decisión 4 · regla R1 |
| Las olas ordenan a quién se forma y se vende primero; no fijan el momento de ningún curso | Decisión 2 · glosario 7.2 |
| La torre de control existe como departamento antes del programa; el tablero con alertas existe desde TCT-01 (fase 3) | Auditoría, sección 7 |
| El asistente de servicio existe desde COM-03 (fase 6). TIC-02 (fase 2) deja el servidor listo para él | H5 |
| Las integraciones con navieras se aprueban en TCT-01, y sus hitos llegan al TMS que lee el servidor de TIC-02 | DD-4 · H32 |
| El plan de cambio ocurre en la fase 7 (ADM-03), cuando operarios y conductores ya trabajan con la telemetría, los estándares de picking y la aplicación del conductor | H4 · H8 |
| La hoja de ruta empieza por los datos y las integraciones que necesitan la visibilidad del corredor y la aduana | H6 · DIR-01 |
| Ninguna oferta compromete un OTIF mayor que el que demuestra la operación (TCT-03). La cifra que compromete COM-01 la fija su etapa 0 | DD-2 · H30 |
| El servicio nuevo de logística farmacéutica de DIR-04 necesita habilitar otra área, porque la habilitada no alcanza | DD-3 · H31 |
| Fuera del reporte semanal y del tablero de OTIF, cada área mantiene su hoja con su versión de los datos hasta TIC-03 | H9 · TIC-03 |

## 7. Regla de datos del sector

**Jurisdicción de referencia: Colombia** (P-ronda 2). Las normas que citan los cursos (aduana, zona franca, tratados, transporte, protección de datos, regulación sanitaria) son las colombianas vigentes, y cada curso las cita y las verifica en su fuente. Ninguna fuente del Proyecto nombra normas concretas, así que esta Biblia no las enumera.

**La geografía es ficticia.** Ciudades, puerto, barrios y tramos tienen nombres inventados y coordenadas sintéticas que no corresponden a lugares reales. Los nombres los crea A4 y entran a esta Biblia por pull request (PEND-11).

Todo el material se marca como datos ficticios, y los datos de un periodo del relato se recrean con la nota que pide la regla R2.

### 7.1 Rangos reservados

Formato realista con un prefijo reservado por tipo (P-ronda 1). A4 comprueba que ningún prefijo esté asignado a algo real antes de generar el material (PEND-9).

| Tipo de dato | Rango reservado o forma sintética | Ejemplo de formato (no es un dato del caso) | Fuente |
| --- | --- | --- | --- |
| Documento de identidad (incluidos conductores) | Empieza por 999 | 999 123 456 | Regla común del catálogo (DD-20) |
| Licencia de conducción | Número que empieza por 999 | 999 123 457 | P-ronda 1 |
| Teléfono | Empieza por 555 | 555 010 2030 | Regla común del catálogo |
| Correo | Dominio `ejemplo.test` | coordinador.ruta@ejemplo.test | Regla común del catálogo |
| Identificación tributaria de las empresas del caso | Empieza por 999, con su dígito de verificación | 999 123 456-1 | P-ronda 1 |
| Placa de vehículo | Formato del país con las letras iniciales ZZ | ZZA 123 | P-ronda 1 |
| Remesa, manifiesto, guía y número de pedido | Prefijo TA-999- | TA-999-004512 | P-ronda 1 |
| Contenedor | Código de propietario ZZZU, número que empieza por 999 y su dígito de control | ZZZU 999001 7 | P-ronda 1 · el dígito de control lo calculó Claude y no consta en las fuentes; A4 lo verifica |
| Sello | Prefijo SL999 | SL999 0457 | P-ronda 1 |
| BL | Prefijo TAL999 | TAL999 000321 | P-ronda 1 |
| AWB | Prefijo de aerolínea reservado: no consta en las fuentes; A4 verifica qué prefijo está libre | Pendiente | P-ronda 1 · PEND-8 |
| Operarios, conductores y auxiliares (reales o sintéticos) en una herramienta de IA | Código seudónimo, sin nombre, documento, placa ni teléfono. La tabla que une el código con la persona queda fuera de la herramienta | OP-0042 · CD-0117 · AX-0008 | P-ronda 3 · formato de los códigos: DD-24 |
| Tenderos y sus tiendas | Nombre de tienda ficticio, dirección en la geografía ficticia, teléfono 555 | Tienda La Esquina Azul · 555 010 7788 | P-ronda 2 · regla común |
| Coordenadas y ubicación | Coordenadas sintéticas que no corresponden a lugares reales | Pendiente del formato que fije A4 | P-ronda 2 |
| Subpartidas arancelarias | Códigos reales de la nomenclatura colombiana vigente. Son información pública, no datos de personas ni de clientes | — | DD-23 |
| Montos, tarifas y costos | Sintéticos. La moneda no consta | — | PEND-10 |

### 7.2 Nunca entra a una herramienta de IA

| Lo que nunca entra | Fuente |
| --- | --- |
| Ningún documento de un cliente antes de que la política de TRC-01 esté aprobada | `02` (C1) |
| Documentos de clientes en herramientas no aprobadas | `02` · TRC-01, Regla del curso |
| Los datos de un cliente para usarlos en beneficio de otro o mostrarlos a otro. Un caso de otro cliente solo se presenta anonimizado y con su consentimiento | `01` · DIR-03 · COM-01 · Auditoría 11.1 |
| Credenciales, claves y contraseñas, incluidas las de las plataformas de los transportadores | TCT-01, Regla del curso · TIC-01 |
| Datos personales reales de tenderos y destinatarios (nombre, dirección, teléfono) | TRC-01, clase 1.1 |
| Datos identificables de trabajadores reales (nombre, documento, placa, teléfono, ubicación). Solo entran con código seudónimo | P-ronda 3 |
| Rutas, horarios e itinerarios reales de cargas sensibles, como los medicamentos controlados | TRC-01, Contexto · TIC-04 |
| En la réplica en la empresa: cualquier dato de un cliente que no esté anonimizado o autorizado por ese cliente, según la política de TRC-01 | `02` (C4) |

### 7.3 Decisiones que la IA nunca toma

La IA prepara, clasifica y propone. No firma declaraciones aduaneras, no decide la clasificación arancelaria definitiva y no autoriza el despacho de mercancías peligrosas. Ningún entregable reemplaza la firma del declarante ni la autorización de HSEQ. Fuente: `02` (C2, C3, C4) · `01`.

## 8. Glosario: términos con un solo sentido en el caso

Los términos generales del catálogo están en `29_glosario_terminos.md`. Esta sección solo registra los del sector (DD-22) y, si un término de aquí contradice el glosario general, manda esta sección para Logística.

| Término | Sentido en el caso | No confundir con | Fuente |
| --- | --- | --- | --- |
| Piloto · Programa Corredor Pacífico | «El piloto», sin calificativo, es el Programa Corredor Pacífico: TransAndes digitaliza el corredor que va del puerto a sus clientes, pasando por aduana, zona franca, CEDI y última milla | Una prueba; el «piloto de su empresa» en las réplicas, que es el mismo sentido aplicado a la empresa del participante | Decisión 1 · Auditoría 11.1 y 7 |
| Prueba | La prueba de un servicio o un sistema dentro del caso, por ejemplo con una línea de Vitalia | El piloto | H35 · glosario 7.2 |
| Prueba de entrega | Término compuesto: la evidencia de que una entrega se hizo (foto, ubicación, firma) | Prueba de un servicio | `02`, componente «Última milla» · UMI-02 · DD-17 |
| Fase del programa | Una de las fases 0 a 7 de la sección 6. Se escribe «fase N del programa» | Fase de una ruta | Decisión 3 |
| Fase de una ruta | El paso de una ruta, con uno o varios cursos. La fase 0 de una ruta es el tronco común | Fase del programa | Decisión 3 · `03` |
| Ola | Orden de formación y de venta (ola 1 dirección, ola 2 operación, comercio exterior y negocio, ola 3 equipos, y aliados técnicos). No es tiempo del caso | Fase del programa | Decisión 2 · `01` |
| Tronco común | TRC-01 a TRC-05. Sus entregables existen desde el inicio de la fase 1 | Cursos obligatorios para todos | Regla R1 |
| Torre de control | Dos sentidos: el departamento que existe antes del programa, y el tablero con alertas que construye TCT-01 en la fase 3. Cuando se habla del producto se escribe «el tablero de la torre» | — | Auditoría, sección 7 |
| Comité del programa | Gerente general, gerente de operaciones y gerente financiero. Dirige el piloto | Los demás comités | `02` |
| Comité de operaciones | Las áreas de la operación. Recibe el reporte semanal, el análisis del corredor y el informe mensual. «El comité» sin calificativo en TRC-02, TRC-04 y TIC-03 | Comité del programa | DD-12 |
| Junta directiva · comité financiero · comité comercial | Órganos distintos del comité del programa (sección 3.2) | Comité del programa | DD-5 |
| OTIF del corredor | Entregas completas y a tiempo de todo el corredor, con la definición interna unificada en TRC-02. Es el 86% del inicio | OTIF por contrato | `02` · TRC-02 · DD-19 |
| OTIF por contrato | El OTIF de un cliente con la definición de su contrato: Andina cuenta la entrega al tendero dentro de su ventana; Vitalia exige además temperatura en rango todo el viaje; Cordillera mide la llegada al puerto antes del cierre del buque | OTIF del corredor | TCT-03 · DD-19 |
| Excepción | Desviación del plan que detecta la torre (demora, faltante, temperatura, desvío o detención) y que gestiona el analista de monitoreo | Novedad | TCT-01 · TCT-02 |
| Novedad | Lo que reporta el conductor o el auxiliar sobre un viaje o una entrega (cliente ausente, rechazo, incidente) | Excepción | TRA-04 · UMI-02 |
| Excursión de temperatura | Salida del rango de temperatura de un producto, medida por máximo, mínimo y duración, no por el promedio del viaje | — | HSQ-02 |
| Hito | Cada evento registrado de un pedido en el corredor: documentos listos, arribo, levante, zona franca, CEDI, despacho, en ruta y entrega | — | TCT-01, clase 1.1 |
| Eslabón | Cada tramo del corredor donde un pedido puede atrasarse: aduana, zona franca, CEDI, transporte y última milla | — | TRC-04 · TCT-03 · TIC-03 |
| Ventana | El rango horario acordado con el cliente para entregar | — | TRC-03 · UMI-02 |
| Transportador tercero | Transportador que no es de TransAndes, al que se paga por viaje | Conductor propio | TRA-02 · DIR-02 |
| Tendero | El dueño de una tienda a la que se entrega por cuenta de Distribuidora Andina | Cliente principal | `02` · UMI-01 |
| Asistente de bodega | El asistente de CED-04, que responde a los operarios con los requisitos de cada cliente | Asistente de servicio | CED-04 · DD-18 |
| Asistente de servicio | El asistente de seguimiento de pedidos de COM-03. «El asistente» sin calificativo en TIC-02 | Asistente de bodega | COM-03 · TIC-02 · DD-18 |
| Aplicación del conductor | La aplicación de TRA-04 para documentos de viaje y novedades; la usan también los terceros | — | TRA-04 · ADM-03 |
| Servidor MCP | El servidor de solo lectura de TIC-02 sobre el WMS, el TMS y el sistema aduanero | — | TIC-02 |
| Integración aprobada | Conexión con un sistema externo aprobada por el arquitecto. No incluye claves compartidas ni extracción de páginas web | — | TCT-01, clase 1.2 |
| CEDI principal · CEDI 1 | El mismo CEDI, el que trabaja CED-01 | CEDI 2 | DD-13 |
| CEDI 2 | Otro CEDI: recibe alimentos y químicos de limpieza y se llena en diciembre con Andina | CEDI principal | DD-13 · DIR-04 |
| Especialista · declarante · auxiliar de aduanas | El especialista clasifica y decide la clasificación definitiva; el declarante revisa, firma y transmite; el auxiliar prepara el expediente | — | `02` · H34 · ADU-02 |
| Expediente aduanero | Los documentos de una importación o exportación para la firma del declarante | Expediente de referencia | ADU-02 |
| Expediente de referencia | La carpeta de datos sintéticos del profesor (sección 4.3) | Expediente aduanero | `02` |
| Usuario operador | La entidad ante la que se registra cada movimiento de la zona franca | TransAndes | ZFR-01 |
| Liberación de calidad | La decisión de la calidad de un cliente (Vitalia) sobre su producto antes de reintegrarlo o usarlo | — | UMI-03 · TCT-02 |
| Situación al inicio · meta de diseño | Cifra del inicio del programa · meta a 12 meses que no es resultado demostrado | Resultado | `02` · C7 · Auditoría 11.2 |

## 9. Pendientes

| ID | Qué no consta o está en conflicto | Documentos | Quién decide | Estado |
| --- | --- | --- | --- | --- |
| PEND-1 | Fecha de inicio del programa y duración de la fase 0 | `02` | Responsable del sector | Abierto. Mientras tanto, semanas relativas (DD-15) |
| PEND-2 | Inicio de la fase 7 | `02` | — | Cerrado por DD-6 |
| PEND-3 | A qué comité se refieren TRC-02, TRC-04 y TIC-03 | Fichas | — | Cerrado por DD-12 (comité de operaciones) |
| PEND-4 | Si TransAndes tiene una junta | `02`, fichas | — | Cerrado por DD-5 |
| PEND-5 | Proporción de camiones propios y de terceros | `02`, DIR-01, DIR-02 | Etapa 0 de DIR-02 | Abierto |
| PEND-6 | Si el CEDI 2 y el CEDI principal son el mismo | Fichas | — | Cerrado por DD-13 (son distintos) |
| PEND-7 | Con qué se integran las navieras | CAR-02 | — | Cerrado por DD-4 |
| PEND-8 | Prefijo reservado de los AWB | P-ronda 1 | A4 | Abierto |
| PEND-9 | Comprobar que los prefijos ZZ, ZZZU, TA-999-, SL999 y TAL999 no estén asignados a nada real | P-ronda 1 | A4 | Abierto |
| PEND-10 | Moneda del caso | Ninguna fuente | Responsable del sector o A4 | Abierto |
| PEND-11 | Nombres ficticios de ciudades, puerto, barrios y tramos, y formato de las coordenadas sintéticas | P-ronda 2 | A4 | Abierto |
| PEND-12 | Uso del tercer CEDI | `02` | A4 o el curso que lo necesite | Abierto |
| PEND-13 | Nombres de personas | Ninguna fuente | El curso que lo necesite, por pull request a esta Biblia | Abierto (DD-10) |
| PEND-14 | Si los otros casos del catálogo (Cordillera, Vitalia, Andina, Altiplano Sur) ya fijaron un país; si lo hicieron, debe ser Colombia | No consta en el Proyecto | Dirección pedagógica | Abierto |
| PEND-15 | La cifra de OTIF que compromete COM-01 | COM-01 · H30 | Etapa 0 de COM-01 | Abierto |
| PEND-16 | Cómo explican CED-04, TCT-01, CAR-02, COM-03, TRA-01 y UMI-03 el insumo del tronco común que la ruta de algún participante no incluye | Auditoría, sección 9 · R1 | Etapa 0 de cada curso | Abierto |
| PEND-17 | Composición de la junta directiva, el comité financiero, el comité comercial y el comité de operaciones | DD-5 · DD-12 | El curso que lo necesite | Abierto |
| PEND-18 | Rango de temperatura de Vitalia: «entre 2 y 8 grados» (TRC-03, Contexto) frente a «varios son de temperatura controlada entre 15 y 25 grados y dos son congelados» (HSQ-02, clase 1.1) | TRC-03 · HSQ-02 | Responsable del sector | Abierto |
| PEND-19 | Integración de los terceros: «los terceros no tienen telemetría integrada» (TRA-03, Contexto) frente a «Telemetría de la flota propia y de los terceros integrados» (HSQ-01, Datos del expediente) y «los transportadores terceros que no tienen GPS integrado» (TCT-01, clase 1.1) | TRA-03 · HSQ-01 · TCT-01 | Responsable del sector | Abierto |
| PEND-20 | Número de departamentos: 11 según el texto y el diagrama de `01`, 12 según las filas de su tabla (incluye Dirección) | `01` | Responsable del sector | Abierto |
| PEND-21 | Qué filas de la columna «Va después de» (sección 6.2) son dependencias citadas en una ficha y cuáles son orden de una ruta o inferencia; si DIR-03 es insumo de TIC-02, de TIC-04 o de ambos | Auditoría, secciones 1, 2 y 7 | A3 | Abierto |

## 10. Decisiones de A2

Las decisiones DD-1 a DD-8 están en la sección 5 de la Auditoría y siguen vigentes.

| ID | Decisión | Escalón | Fuente |
| --- | --- | --- | --- |
| DD-9 | La línea de tiempo y el «Momento del caso» salen de las secciones 1 y 2 de la Auditoría, que coinciden con `02` corregido | 2 | Auditoría · registro de cambios |
| DD-10 | Ninguna persona tiene nombre; se registran roles. Un nombre nuevo entra por pull request | 2 | Inventario 2.2 |
| DD-11 | Los sistemas se nombran por su función | 2 | TIC-02, TIC-03, TRC-02, TCT-01, TIC-01, HSQ-02 |
| DD-12 | «El comité» sin calificativo es el comité de operaciones. Reversible | 6 | TRC-04 · `02` |
| DD-13 | CEDI principal = CEDI 1; el CEDI 2 es otro. Reversible | 6 | CED-01 · DIR-04 · TRC-03 · COM-01 |
| DD-14 | La proporción de camiones queda sin cifra hasta la etapa 0 de DIR-02 | 2 | H17 · glosario 9.1 |
| DD-15 | Sin fecha de inicio; diciembre y enero son estacionalidad del relato | 1 | Regla R2 |
| DD-16 | Los resultados anticipados en los procedimientos de las fichas no son cifras de la Biblia | 2 | Errores conocidos n.º 3 |
| DD-17 | «Prueba de entrega» es término compuesto y no contradice H35 | 2 | `02` |
| DD-18 | Asistente de bodega y asistente de servicio son dos productos | 2 | TIC-02 |
| DD-19 | OTIF del corredor y OTIF por contrato | 2 | TRC-02 · TCT-03 |
| DD-20 | Se aplican los rangos comunes del catálogo | 2 | `00_metodologia` |
| DD-21 | Lista de lo que nunca entra a una herramienta de IA, según las fuentes | 2 y 3 | `02` · `01` · fichas |
| DD-22 | Los términos del sector van en la sección 8 de esta Biblia | 6 | Encargo A2 |
| DD-23 | Las subpartidas arancelarias usan la nomenclatura colombiana real, porque ADU-01 enseña a clasificar contra la nomenclatura nacional y es información pública | 4 | P-ronda 2 · ADU-01, clase 3.1 |
| DD-24 | Formato de los códigos seudónimos: OP- para operarios, CD- para conductores y AX- para auxiliares, con cuatro cifras | 6 | P-ronda 3 |
| P-ronda 1 | Formato realista con prefijo reservado por tipo (sección 7.1) | 7 | Responsable del sector, 2026-10-21 |
| P-ronda 2 | Jurisdicción de referencia para las normas: Colombia. Geografía ficticia con coordenadas sintéticas | 7 | Responsable del sector, 2026-10-21 |
| P-ronda 3 | Datos de trabajadores en una herramienta de IA: siempre con código seudónimo | 7 | Responsable del sector, 2026-10-21 |
