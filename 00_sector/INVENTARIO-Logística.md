# Inventario del sector · Logística

Etapa A, encargo A0. Copia las frases de los cuatro documentos del sector sin resumirlas ni interpretarlas. Es el índice de A1, A2 y A3: cuando se cite algo, se cita del documento original.

| Campo | Valor |
| --- | --- |
| Sector | Logística (título de `01_principios`: «Sector Logística, transporte y comercio exterior») |
| Documentos leídos | `01_principios` (282 líneas) · `02_caso_referencia` (121 líneas) · `03_rutas_por_rol` (492 líneas) · `04_fichas_cursos` (1628 líneas) |
| Fecha | 20 de octubre de 2026 |
| Responsable | No consta |
| Método | Lectura completa de los cuatro documentos. Las tablas de rutas, horas, campos, clases y menciones entre cursos se extrajeron además con un script y se contrastaron con la lectura. No se abrió ningún otro archivo del repositorio. |

Convenciones: «…» dentro de una cita indica que la frase sigue en el documento. «No consta» indica que se buscó y no está en los cuatro documentos. Las líneas citadas son las del archivo tal como está en el conocimiento del Proyecto.

## 1. Principios

`01_principios` no numera sus principios ni tiene una sección llamada «Principios»: las reglas están repartidas en sus secciones. Aquí se numeran en el orden en que aparecen. Columna «Marca»: **D** habla de datos, **H** de herramientas o de los límites de la IA, **N** del nivel o el formato del participante.

### 1.1 Reglas generales del sector

| ID | Principio, con la frase del documento | Marca | Tema | Sección del documento |
| --- | --- | --- | --- | --- |
| P1 | «Mismos principios, estructura y leyenda de la pestaña Principios y Tecnología (outsourcing); aquí el caso de referencia es un operador logístico integral con almacenamiento, transporte, aduanas, carga internacional y zona franca.» | — | pedagogía | Introducción (línea 3) |
| P2 | «La IA rinde primero donde hay mucho documento y mucha excepción: aduanas, torre de control y servicio al cliente.» | H | negocio | Departamentos y roles |
| P3 | «La transformación no elimina roles: cambia en qué emplea cada persona su tiempo.» | — | negocio | Roles antes y después de la transformación |
| P4 | «En el modelo nuevo, la IA prepara, clasifica y alerta, pero no firma declaraciones, no decide la clasificación arancelaria definitiva ni autoriza mercancías peligrosas; esas decisiones siguen siendo del especialista o el responsable autorizado.» | H | herramientas | Roles antes y después de la transformación |
| P5 | «Los datos de un cliente nunca se usan en beneficio de otro ni se muestran a otro, y el tiempo liberado de las personas no se cuenta como ahorro de nómina.» | D | datos · negocio | Roles antes y después de la transformación |
| P6 | «Algunas rutas agrupan roles que hacen el mismo recorrido de cursos, como el especialista en clasificación arancelaria y el declarante; aquí aparecen por separado porque su trabajo cambia de forma distinta.» | — | pedagogía | Roles antes y después de la transformación |
| P7 | «Las cifras salen de las fichas de los cursos de cada rol y se miden contra la línea base de la persona antes del curso.» | — | pedagogía | Roles antes y después de la transformación |
| P8 | «El profesor desarrolla un único proyecto para todo el sector: TransAndes Logística, operador ficticio, digitaliza el corredor que va del puerto a sus clientes, pasando por aduana, zona franca, CEDI y última milla.» | — | pedagogía | Caso de referencia: Programa Corredor Pacífico |
| P9 | «En logística rige una regla fija: la IA prepara, clasifica y propone, pero no firma declaraciones aduaneras, no decide la clasificación arancelaria definitiva ni autoriza el despacho de mercancías peligrosas; eso lo hace la persona responsable.» | H | herramientas | Caso de referencia: Programa Corredor Pacífico |
| P10 | «El proyecto de referencia usa datos sintéticos.» | D | datos | Caso de referencia: Programa Corredor Pacífico |
| P11 | «Cinco cursos de base cuyos proyectos son la fase 0 de todas las rutas.» | — | pedagogía | Tronco común del sector |
| P12 | «Para operarios y conductores se dictan en el celular, en bloques cortos.» | N | nivel | Tronco común del sector |
| P13 | «43 cursos de rol sobre el tronco común, cada uno con su proyecto de referencia dentro del Programa Corredor Pacífico.» | — | pedagogía | Cursos por departamento y rol |
| P14 | «Cada ruta es un macroproyecto dentro del Programa Corredor Pacífico, y sus cursos son las fases en el orden en que el programa las necesita.» | — | pedagogía | Rutas por rol y orden de despliegue |
| P15 | «La torre de control abre la ola 2: sin visibilidad del corredor, las mejoras de cada eslabón no se pueden medir.» | — | negocio | Rutas por rol y orden de despliegue |
| P16 | «Operarios, conductores y auxiliares tienen rutas de mayor especialización, no de salida: la meta es que cada persona atienda más carga con menos errores.» | N | nivel · negocio | Rutas por rol y orden de despliegue |
| P17 | «La fase 0 es el bloque del tronco común; los códigos omiten el prefijo LOG-.» | — | pedagogía | Rutas por rol y orden de despliegue |

La columna «Capa» de la tabla del tronco común también describe a quién va cada curso: TRC-01 «Todas»; TRC-02 «Dirección, líderes, equipos»; TRC-03 «Todas»; TRC-04 «Líderes, equipos»; TRC-05 «Líderes, aliado técnico» (marca N). Los cursos de rol no tienen columna «Capa»; tienen «Roles».

### 1.2 Reglas por rol (tabla «Roles antes y después de la transformación»)

La tabla tiene 39 roles. Para cada uno se copia la columna «Cómo trabajará después de la transformación» y, si la tiene, la meta «cero» de la columna «Potencial de productividad», que funciona como regla del rol.

| ID | Rol | Cómo trabajará después, con la frase del documento | Meta «cero» | Marca |
| --- | --- | --- | --- | --- |
| P18 | Gerente general | «Conduce el programa con una hoja de ruta en la que la IA no firma declaraciones ni autoriza mercancías peligrosas, y abre servicios nuevos, como la logística farmacéutica y de exportación.» | No consta | H |
| P19 | Gerente de operaciones | «Dirige una torre de control con visibilidad del corredor y alertas, gobierna el uso de los datos de cada cliente y mide el nivel de servicio con la definición de cada contrato.» | No consta | D |
| P20 | Gerente financiero | «Aprueba casos de negocio que miden el valor sin recortar personas y revisa la rentabilidad por cliente con el costo real de servirle.» | No consta | — |
| P21 | Analista de costos logísticos | «Costea cada pedido y cada cliente por actividades, sin cargarle los costos de fallas de TransAndes.» | «Costos de fallas propias cargados a un cliente: cero.» | — |
| P22 | Gerente de CEDI | «Rediseña el layout y las reglas de ubicación del WMS con Claude, sin juntar productos incompatibles ni sobrecargar los racks.» | «Reglas que juntan productos incompatibles o sobrecargan un nivel: cero.» | H |
| P23 | Jefe de bodega | «Fija estándares por operario y turno con datos del WMS, con suplementos por fatiga y por trabajo en cámara fría.» | «Estándares sin suplementos por fatiga o cámara fría: cero.» | — |
| P24 | Jefe de inventarios | «Programa conteos cíclicos por cliente y ajusta el inventario solo con reconteo y la aprobación que exige cada contrato.» | «Ajustes sin reconteo ni aprobación: cero.» | — |
| P25 | Operario de bodega | «Consulta en el celular un asistente con los requisitos vigentes de cada cliente, que escala toda carga con sello roto o excursión de temperatura.» | No consta | H · N |
| P26 | Planeador de transporte | «Planea la red nacional con consolidación de cargas y retornos, sin mezclar cargas incompatibles.» | «Consolidaciones con cargas incompatibles: cero.» | — |
| P27 | Jefe de tráfico | «Gestiona la flota con un tablero de costo por kilómetro y desempeño, y no asigna viajes a vehículos o conductores con documentos vencidos.» | «Viajes asignados con documentos o pólizas vencidos: cero.» | — |
| P28 | Jefe de mantenimiento de flota | «Anticipa las fallas con alertas desde la telemetría, con detención segura del vehículo ante una alerta crítica de frenos o llantas.» | «Alertas críticas sin detención segura: cero.» | H |
| P29 | Conductor de carga | «Reporta documentos y novedades desde el celular con el vehículo detenido, con su plan de seguridad vial personal.» | «Interacciones con la aplicación con el vehículo en movimiento: cero.» | H · N |
| P30 | Coordinador de última milla | «Rutea de forma dinámica, sin acumular efectivo por encima del límite de seguridad del vehículo.» | «Rutas que superan el límite de efectivo: cero.» | — |
| P31 | Conductor de última milla | «Registra la prueba de entrega y cada novedad en el momento, con su causa real.» | «Novedades atribuidas al cliente cuando la causa fue la llegada tarde: cero.» | N |
| P32 | Analista de logística inversa | «Clasifica cada devolución con su destino y reintegra los medicamentos solo con la liberación de calidad del cliente.» | «Medicamentos reintegrados sin liberación de calidad: cero.» | — |
| P33 | Analista de torre de control | «Atiende alertas de temperatura y desvío dentro del protocolo, y comunica cada excepción al cliente con hora confirmada y causa con evidencia.» | No consta | H |
| P34 | Especialista en clasificación arancelaria | «Recibe una propuesta de clasificación con su fundamento, decide y documenta la clasificación definitiva.» | No consta | H |
| P35 | Declarante de aduanas | «Revisa y firma expedientes preparados con los documentos completos y verificados.» | «Declaraciones transmitidas sin revisión y firma del declarante: cero.» | H |
| P36 | Especialista de comercio exterior | «Analiza con Claude los regímenes y tratados de cada exportación, y solo emite certificados de origen para productos que cumplen la regla.» | «Certificados de origen para productos que no cumplen la regla: cero.» | H |
| P37 | Director de aduanas | «Mantiene los requisitos del Operador Económico Autorizado con evidencia al día y la evaluación de seguridad vigente de cada asociado.» | «Asociados sin evaluación de seguridad vigente: cero.» | — |
| P38 | Ejecutivo de carga internacional | «Cotiza en minutos con un modelo de tarifas vigentes, con su vigencia y sus exclusiones declaradas.» | «Cotizaciones con tarifas vencidas: cero.» | H |
| P39 | Coordinador de embarques | «Sigue los embarques con los documentos al día y confirma cualquier cambio de consignatario por un canal verificado.» | «Cambios de datos críticos sin confirmación del cliente: cero.» | D |
| P40 | Gerente de carga internacional | «Recomienda el Incoterm con una guía por cliente que asigna al vendedor solo lo que puede cumplir.» | No consta | — |
| P41 | Gerente de zona franca | «Opera el ingreso y la salida con controles en el sistema y prepara servicios de valor agregado, como el acondicionamiento para Vitalia.» | «Salidas sin formulario autorizado: cero.» | H |
| P42 | Jefe de inventario de zona franca | «Concilia con la autoridad cada mes, con las diferencias explicadas y los ajustes por el procedimiento autorizado.» | «Ajustes sin el procedimiento autorizado: cero.» | — |
| P43 | Ingeniero de soluciones | «Diseña soluciones con Claude y compromete solo los niveles de servicio que la operación puede demostrar.» | «Niveles de servicio comprometidos sin evidencia: cero.» | H |
| P44 | Gerente comercial | «Ajusta las tarifas con la rentabilidad por cliente y dentro de la cláusula de revisión de cada contrato.» | «Ajustes fuera de la cláusula de revisión: cero.» | — |
| P45 | Gerente de cuenta clave | «Construye el plan anual de cada cuenta, como la de Cordillera, solo con información de ese cliente.» | «Planes que usan información de otro cliente: cero.» | D |
| P46 | Analista de servicio al cliente | «Supervisa un asistente que resuelve las consultas de pedidos a quien verificó ser su titular, y atiende los casos escalados.» | «Información de un pedido dada a quien no es su titular: cero.» | D · H |
| P47 | Coordinador de seguridad vial | «Analiza la telemetría por conductor y construye planes de mejora; las sanciones pasan siempre por revisión humana.» | «Sanciones aplicadas automáticamente desde la telemetría: cero.» | D · H |
| P48 | Coordinador de mercancías peligrosas y cadena de frío | «Aplica protocolos para Vitalia con monitoreo durante el envío, y autoriza cada despacho de mercancías peligrosas.» | «Despachos de mercancías peligrosas sin autorización: cero.» | H |
| P49 | Coordinador de calidad | «Mantiene una matriz de requisitos con evidencia real, revisada y aprobada.» | «Evidencias generadas sin que el hecho haya ocurrido: cero.» | — |
| P50 | Analista de facturación | «Factura conciliando cada cobro con la operación, sin cobrar al cliente reentregas causadas por fallas propias.» | No consta | — |
| P51 | Gerente de talento humano | «Acompaña el programa con un plan de cambio para CEDI y flota que explica qué datos se miden de cada persona y para qué.» | «Mensajes que omiten qué datos se miden y para qué: cero.» | D |
| P52 | Coordinador de formación | «Forma con una matriz de competencias y un módulo móvil, con certificación práctica para montacargas y mercancías peligrosas.» | «Personas asignadas sin certificación práctica vigente: cero.» | N |
| P53 | Arquitecto de integraciones | «Integra a los clientes por EDI y API, con cada pedido validado por el cliente.» | «Pedidos duplicados o alterados sin validación: cero.» | H |
| P54 | Desarrollador de integraciones | «Construye servidores MCP de solo lectura que solo devuelven datos de un cliente a quien está autorizado para él.» | «Datos de un cliente devueltos a quien no está autorizado: cero.» | D · H |
| P55 | Analista de datos | «Construye el modelo de datos del corredor y tableros por cliente que solo reciben los datos de ese cliente.» | «Tableros que reciben datos de otros clientes: cero.» | D |
| P56 | Oficial de seguridad de la información | «Evalúa los riesgos de los sistemas y revoca los accesos de personas retiradas o terceros el día de su salida.» | «Accesos vigentes después del día de salida: cero.» | D |

## 2. Caso de referencia

Fuente: `02_caso_referencia`, salvo donde se indica `01_principios`. El documento abre con: «Las empresas y cifras son ficticias, y el proyecto usa datos sintéticos.»

### 2.1 Fases del proyecto, en orden

Tabla de fases de la sección «El Programa Corredor Pacífico» de `02`:

| Fase | Nombre | Duración | Entregable principal, con la frase del documento | Cursos que producen la fase |
| --- | --- | --- | --- | --- |
| 1 | Diagnóstico, caso y gobierno | 6 semanas | «Hoja de ruta, caso de negocio, gobierno de datos de clientes y plan de cambio» | DIR-01 a DIR-03, ADM-03 |
| 2 | Datos e integraciones | 8 semanas | «Seguridad, integración con Cordillera y Andina, MCP y modelo de datos» | TIC-01 a TIC-04 |
| 3 | Torre de control | 8 semanas | «Visibilidad del corredor, protocolo de excepciones y OTIF» | TCT-01 a TCT-03 |
| 4 | Aduana y zona franca | 12 semanas | «OEA, clasificación, expedientes, tratados, operación e inventario de zona franca» | ADU-01 a ADU-04, ZFR-01 a ZFR-03 |
| 5 | CEDI, transporte y última milla | 16 semanas | «Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, conductor, ruteo, prueba de entrega y devoluciones» | CED-01 a CED-04, TRA-01 a TRA-04, UMI-01 a UMI-03 |
| 6 | Carga, HSEQ y servicio | Desde el mes 5 | «Cotización, embarques, Incoterms, seguridad vial, cadena de frío, certificaciones y asistente de servicio» | CAR-01 a CAR-03, HSQ-01 a HSQ-03, COM-03 |
| 7 | Negocio y escala | Continua | «Costeo, facturación, soluciones, pricing, cuentas clave, formación y nuevos servicios» | ADM-01, ADM-02, ADM-04, COM-01, COM-02, COM-04, DIR-04 |

Frases de `02` que ordenan el tiempo del caso:

- Antes de la fase 1: «El tronco común (TRC-01 a TRC-05) se dicta a todos antes de su primera fase.»
- Antes de la fase 1: «Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado.»
- Diagnóstico: «El diagnóstico que abre el programa tiene tres hallazgos: nadie ve el corredor completo, así que las excepciones se descubren cuando el cliente llama; la aduana pierde días por expedientes incompletos; y los datos de los clientes circulan sin control.»
- Olas: «Lo dirige un comité formado por el gerente general, el gerente de operaciones y el gerente financiero. La torre de control abre la segunda ola, con los líderes de CEDI, transporte, aduanas, carga, zona franca, comercial y HSEQ, y dos aliados técnicos: integraciones y datos.»
- Estado final: «En 2027, TransAndes avisa al cliente antes de que el cliente pregunte.»

Otras secuencias que dan los documentos, copiadas sin conciliar:

| Documento | Secuencia |
| --- | --- |
| `01`, diagrama de la sección «Caso de referencia: Programa Corredor Pacífico» | Diagnóstico → Datos e integraciones → Torre de control del corredor → Aduana y zona franca → CEDI, transporte y última milla → Nuevos servicios y clientes (seis pasos) |
| `01`, diagrama de la sección «Rutas por rol y orden de despliegue» | Ola 1 · Dirección · piloto 90 días → Ola 2 · Operación, comercio exterior y negocio → Ola 3 · Equipos; de la ola 2 salen también los Aliados técnicos, que llevan a la ola 3 |
| `02`, sección «El caso como eje del diseño instruccional» | Cinco momentos de cada curso: 1. Contexto (10%) · 2. Demostración (25%) · 3. Réplica con ajuste (25%) · 4. Réplica en la empresa (30%) · 5. Evaluación por evidencia (10%) |

### 2.2 Empresas, personas y sistemas

**Empresas**

| Nombre | Tipo | Papel | Frase del documento |
| --- | --- | --- | --- |
| TransAndes Logística | Empresa | Operador del caso; ejecuta el Programa Corredor Pacífico | «TransAndes tiene tres CEDI, 400 camiones propios y de terceros, una agencia de aduanas, una zona franca y un equipo de carga internacional.» |
| Alimentos Cordillera | Empresa | Cliente principal de TransAndes | «Sus clientes principales son los otros casos del catálogo: … exporta galletas de Alimentos Cordillera …» |
| Vitalia | Empresa | Cliente principal de TransAndes | «Sus clientes principales son los otros casos del catálogo: … mueve medicamentos de Vitalia con cadena de frío …» |
| Distribuidora Andina | Empresa | Cliente principal de TransAndes | «Sus clientes principales son los otros casos del catálogo: … distribuye a los tenderos de Distribuidora Andina …» |
| Altiplano Sur | Empresa | Cliente principal de TransAndes | «Sus clientes principales son los otros casos del catálogo: … lleva el concentrado de Altiplano Sur al puerto …» |

**Personas.** `02` no nombra a ninguna persona: No consta ningún nombre propio. Aparecen roles:

| Rol | Tipo | Papel | Frase del documento |
| --- | --- | --- | --- |
| Gerente general, gerente de operaciones y gerente financiero | Persona (rol) | Comité que dirige el piloto | «Lo dirige un comité formado por el gerente general, el gerente de operaciones y el gerente financiero.» |
| Líderes de CEDI, transporte, aduanas, carga, zona franca, comercial y HSEQ | Persona (rol) | Segunda ola | «La torre de control abre la segunda ola, con los líderes de CEDI, transporte, aduanas, carga, zona franca, comercial y HSEQ, y dos aliados técnicos: integraciones y datos.» |
| Aliados técnicos de integraciones y de datos | Persona (rol) | Segunda ola | (misma frase) |
| Analista de monitoreo | Persona (rol) | Decide la acción en visibilidad | «El analista de monitoreo decide la acción» |
| Especialista y declarante | Persona (rol) | Clasifica y firma en aduana | «El especialista clasifica y el declarante firma» |
| Jefe de inventario | Persona (rol) | Firma en zona franca | «El jefe de inventario firma» |
| Gerente de CEDI | Persona (rol) | Aprueba en CEDI | «El gerente de CEDI aprueba» |
| Planeador | Persona (rol) | Aprueba en transporte | «El planeador aprueba» |
| Coordinador (última milla) | Persona (rol) | Ajusta | «El coordinador ajusta» |
| Agente (servicio) | Persona (rol) | Resuelve lo escalado | «El agente resuelve lo escalado» |
| Coordinador HSEQ | Persona (rol) | Autoriza mercancías peligrosas y frío | «El coordinador HSEQ autoriza» |
| Gerente comercial | Persona (rol) | Decide en comercial | «El gerente comercial decide» |
| Arquitecto | Persona (rol) | Aprueba cada acceso a datos de clientes | «El arquitecto aprueba cada acceso» |
| Profesor | Persona (rol) | Construye el programa y demuestra cada curso | «Antes de lanzar el catálogo, el profesor construye el Programa Corredor Pacífico completo.» |
| Participante o estudiante | Persona (rol) | Replica el procedimiento y mide su tarea | «Antes del curso, cada participante mide su tarea objetivo (un expediente, un ruteo, un conteo).» |
| Operarios, conductores y auxiliares | Persona (rol) | Formato móvil; sin ruta de salida | «Operarios, conductores y auxiliares atienden más carga con menos errores, y ninguno tiene ruta de salida.» |
| Tenderos | Persona (rol) | Destinatarios de Distribuidora Andina | «distribuye a los tenderos de Distribuidora Andina» |

**Unidades, sistemas y productos**

| Nombre | Tipo | Papel | Frase del documento |
| --- | --- | --- | --- |
| Programa Corredor Pacífico | Proyecto | Piloto que digitaliza el corredor | «El piloto digitaliza el corredor que va del puerto a los clientes, pasando por aduana, zona franca, CEDI y última milla.» |
| Tres CEDI, flota de 400 camiones, agencia de aduanas, zona franca, equipo de carga internacional | Unidades de TransAndes | Infraestructura de partida | «TransAndes tiene tres CEDI, 400 camiones propios y de terceros, una agencia de aduanas, una zona franca y un equipo de carga internacional.» |
| Torre de control | Componente del programa | Visibilidad del corredor | «Visibilidad del corredor con alertas de excepción» |
| Aduana ágil | Componente del programa | Expedientes y clasificación asistida | «Expedientes completos y clasificación arancelaria asistida, con decisión del declarante» |
| CEDI productivo | Componente del programa | Almacén | «Ubicaciones optimizadas, picking medido e inventario exacto» |
| Transporte optimizado | Componente del programa | Flota | «Rutas consolidadas, flota disponible y transportadores medidos» |
| Última milla | Componente del programa | Entregas a tenderos | «Ruteo diario y prueba de entrega a tenderos» |
| Servicio al cliente | Componente del programa | Asistente | «Asistente de seguimiento de pedidos con escalamiento» |
| WMS, TMS y aduana | Sistemas | Fuentes de la torre de control (diagrama de 2027) | nodo del diagrama `Datos de clientes,<br/>WMS, TMS y aduana` |
| MCP de solo lectura | Sistema (2027) | Acceso de la IA a datos de clientes | «Integraciones seguras y MCP de solo lectura» |
| Herramientas públicas | Situación actual | Donde hoy se copian documentos de clientes | «Sin reglas; documentos de clientes copiados a herramientas públicas» |
| Expediente de referencia | Material del profesor | Carpeta de datos sintéticos organizada por fases | «Una carpeta con datos sintéticos: un año de pedidos, tiempos y novedades del corredor, inventarios y movimientos de los tres CEDI, viajes y telemetría de la flota, entregas a tenderos, declaraciones aduaneras, documentos de embarque, registros de zona franca, contratos y tarifas de clientes, y conversaciones de servicio al cliente.» |
| Registros ante la autoridad | Documento externo | Base de la conciliación de zona franca | «Inventario conciliado con los registros ante la autoridad» |

### 2.3 Cifras

| Cifra | Valor | Frase donde aparece | Sección |
| --- | --- | --- | --- |
| CEDI de TransAndes | 3 | «TransAndes tiene tres CEDI, 400 camiones propios y de terceros, una agencia de aduanas, una zona franca y un equipo de carga internacional.» | TransAndes Logística hoy |
| Camiones propios y de terceros | 400 | (misma frase) | TransAndes Logística hoy |
| Agencias de aduanas · zonas francas | 1 · 1 | (misma frase) | TransAndes Logística hoy |
| Clientes principales | 4 (enumerados) | «Sus clientes principales son los otros casos del catálogo: exporta galletas de Alimentos Cordillera, mueve medicamentos de Vitalia con cadena de frío, distribuye a los tenderos de Distribuidora Andina y lleva el concentrado de Altiplano Sur al puerto.» | TransAndes Logística hoy |
| OTIF del corredor, hoy | 86% | «Entregas completas y a tiempo (OTIF) del corredor \| 86%» | TransAndes Logística hoy (tabla) |
| Excepciones detectadas antes que el cliente, hoy | 30% | «Excepciones detectadas antes que el cliente \| 30%» | TransAndes Logística hoy (tabla) |
| Tiempo de nacionalización, hoy | 4 días | «Tiempo de nacionalización \| 4 días» | TransAndes Logística hoy (tabla) |
| Declaraciones aduaneras con correcciones, hoy | 9% | «Declaraciones aduaneras con correcciones \| 9%» | TransAndes Logística hoy (tabla) |
| Exactitud de inventario en los CEDI, hoy | 94% | «Exactitud de inventario en los CEDI \| 94%» | TransAndes Logística hoy (tabla) |
| Productividad de picking, hoy | Sin estándar | «Productividad de picking \| Sin estándar por operario» | TransAndes Logística hoy (tabla) |
| Kilómetros en vacío, hoy | 28% | «Kilómetros en vacío de la flota \| 28%» | TransAndes Logística hoy (tabla) |
| Entregas a tenderos con novedad, hoy | 12% | «Entregas a tenderos con novedad \| 12%» | TransAndes Logística hoy (tabla) |
| Llamadas preguntando por un pedido | 60% del total | «Llamadas al servicio al cliente preguntando por un pedido \| 60% del total» | TransAndes Logística hoy (tabla) |
| Uso de IA, hoy | Sin cifra | «Uso de IA \| Sin reglas; documentos de clientes copiados a herramientas públicas» | TransAndes Logística hoy (tabla) |
| Hallazgos del diagnóstico | 3 | «El diagnóstico que abre el programa tiene tres hallazgos: …» | TransAndes Logística hoy |
| Miembros del comité | 3 (enumerados) | «Lo dirige un comité formado por el gerente general, el gerente de operaciones y el gerente financiero.» | El Programa Corredor Pacífico |
| Aliados técnicos | 2 | «… y dos aliados técnicos: integraciones y datos.» | El Programa Corredor Pacífico |
| Componentes del programa | 6 (filas de la tabla) | Tabla «Componente \| Qué entrega» | El Programa Corredor Pacífico |
| Fases del programa | 7 (filas de la tabla) | Tabla «Fase del programa \| Duración \| Entregable principal \| Cursos que producen la fase» | El Programa Corredor Pacífico |
| Duración de las fases 1 a 5 | 6, 8, 8, 12 y 16 semanas | Columna «Duración» de la tabla de fases | El Programa Corredor Pacífico |
| Inicio de la fase 6 | Mes 5 | «Desde el mes 5» | El Programa Corredor Pacífico (tabla) |
| Año del modelo operativo | 2027 | «En 2027, TransAndes avisa al cliente antes de que el cliente pregunte.» | TransAndes 2027: cómo operará |
| Datos del expediente de referencia | Un año | «Una carpeta con datos sintéticos: un año de pedidos, tiempos y novedades del corredor, …» | El caso como eje del diseño instruccional |
| Momentos del modelo instruccional | 5 | «Todos los cursos siguen los mismos cinco momentos:» | El caso como eje del diseño instruccional |
| Peso de cada momento | 10%, 25%, 25%, 30%, 10% | Columna «Peso» de la tabla de momentos | El caso como eje del diseño instruccional |
| Horizonte de las metas | 12 meses | Encabezado «Meta a 12 meses» de la tabla de metas | Metas del programa |
| Meta OTIF | 86% → 94% | «OTIF del corredor \| 86% \| 94%» | Metas del programa |
| Meta excepciones anticipadas | 30% → 80% | «Excepciones detectadas antes que el cliente \| 30% \| 80%» | Metas del programa |
| Meta nacionalización | 4 días → 2 días | «Tiempo de nacionalización \| 4 días \| 2 días» | Metas del programa |
| Meta declaraciones con correcciones | 9% → 3% | «Declaraciones con correcciones \| 9% \| 3%» | Metas del programa |
| Meta exactitud de inventario | 94% → 99% | «Exactitud de inventario \| 94% \| 99%» | Metas del programa |
| Meta productividad de picking | +15% a +25% | «Productividad de picking \| Sin estándar \| +15% a +25% sobre la línea base» | Metas del programa |
| Meta kilómetros en vacío | 28% → 18% a 20% | «Kilómetros en vacío \| 28% \| 18% a 20%» | Metas del programa |
| Meta entregas con novedad | 12% → 6% | «Entregas a tenderos con novedad \| 12% \| 6%» | Metas del programa |
| Meta consultas resueltas por el asistente | Ninguna → 50% a 70% | «Consultas de pedidos resueltas por el asistente \| Ninguna \| 50% a 70%» | Metas del programa |
| Meta accidentes viales | −30% sobre la línea base del año | «Accidentes viales \| Línea base del año \| −30%» | Metas del programa |
| Meta documentos fuera de herramientas aprobadas | Frecuente → Cero | «Documentos de clientes fuera de herramientas aprobadas \| Frecuente \| Cero» | Metas del programa |
| Ejemplos de cómo se expresan los indicadores | −30% a −50% · de 86% a 94% | «Se expresan como reducción del tiempo o de la pérdida (por ejemplo, −30% a −50%) o como mejora de un indicador (por ejemplo, de 86% a 94%).» | Cómo leer los indicadores |

`01_principios` repite las cifras de TransAndes (tres CEDI, 400 camiones) con la misma frase, y la tabla «Roles antes y después» trae una cifra de productividad por rol: no se copian aquí porque son de `01`, no del caso; están en la columna «Potencial de productividad» de esa tabla.

### 2.4 Reglas que enuncia el caso

No las pide el encargo, pero A2 toma de aquí la regla de datos de la Biblia. Se numeran C1, C2… para no mezclarlas con los principios.

| ID | Frase de `02` | Marca | Sección |
| --- | --- | --- | --- |
| C1 | «Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado.» | D | El Programa Corredor Pacífico |
| C2 | «La IA arma expedientes, propone clasificaciones, rutas y ubicaciones, y detecta excepciones; la firma de cada declaración y cada decisión sobre mercancías peligrosas sigue siendo de la persona responsable.» | H | TransAndes 2027: cómo operará |
| C3 | «La regla del sector se mantiene en todo el modelo: la IA prepara, clasifica y propone, pero no firma declaraciones aduaneras, no decide la clasificación arancelaria definitiva ni autoriza el despacho de mercancías peligrosas.» | H | TransAndes 2027: cómo operará |
| C4 | «La réplica en la propia empresa usa datos anonimizados o autorizados por el cliente, según la política de TRC-01. Ningún entregable reemplaza la firma del declarante ni la autorización de HSEQ.» | D · H | El caso como eje del diseño instruccional (Datos de clientes) |
| C5 | «Para operarios, conductores y auxiliares, cada clase se dicta en el celular y en bloques cortos.» | N | El caso como eje del diseño instruccional (Formato móvil) |
| C6 | «Antes del curso, cada participante mide su tarea objetivo (un expediente, un ruteo, un conteo). Al terminar la réplica vuelve a medirla. La diferencia es el indicador de aceleración de su ficha.» | — | El caso como eje del diseño instruccional (La medición) |
| C7 | «Los porcentajes de las fichas y las rutas son metas de diseño, no promesas.» | — | Cómo leer los indicadores |
| C8 | «Un indicador sin línea base no se reporta.» | — | Cómo leer los indicadores |

## 3. Rutas por rol

Fuente: `03_rutas_por_rol`. La columna «Coincide con `01`» compara la secuencia con la tabla de la sección «Rutas por rol y orden de despliegue» de `01_principios`. `01` no da horas por ruta; las horas solo constan en `03`.

| # | Ola o grupo | Rol | Macroproyecto | Secuencia de cursos (fase 0 → fases 1 a n) | Horas | Línea en `03` | Coincide con `01` |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Ola 1 · Dirección | Gerente general | Programa aprobado con nuevos servicios | TRC-01, TRC-02 ; DIR-01 → DIR-02 → DIR-04 | 60 h | 7 | Sí |
| 2 | Ola 1 · Dirección | Gerente de operaciones | Corredor visible y medido | TRC-01, TRC-02, TRC-04 ; DIR-03 → TCT-01 → TCT-03 | 76 h | 26 | Sí |
| 3 | Ola 1 · Dirección | Gerente financiero | Costo y margen por cliente conocidos | TRC-01, TRC-02 ; DIR-02 → ADM-01 → COM-02 | 56 h | 45 | Sí |
| 4 | Ola 2 · Líderes de operación, comercio exterior y negocio | Jefe de torre de control | Cada excepción detectada y comunicada a tiempo | TRC-01 a 05 ; TCT-01 → TCT-02 → TCT-03 | 100 h | 66 | Sí |
| 5 | Ola 2 · Líderes de operación, comercio exterior y negocio | Gerente de CEDI | CEDI productivo y exacto | TRC-01 a 05 ; CED-01 → CED-02 → CED-03 | 96 h | 85 | Sí |
| 6 | Ola 2 · Líderes de operación, comercio exterior y negocio | Jefe de transporte | Flota rentable y disponible | TRC-01 a 05 ; TRA-01 → TRA-02 → TRA-03 | 100 h | 104 | Sí |
| 7 | Ola 2 · Líderes de operación, comercio exterior y negocio | Coordinador de última milla | Entregas a tenderos sin novedades | TRC-01, TRC-02, TRC-04 ; UMI-01 → UMI-02 → UMI-03 | 64 h | 123 | Sí |
| 8 | Ola 2 · Líderes de operación, comercio exterior y negocio | Director de aduanas | Aduana ágil y cumplida | TRC-01, TRC-03, TRC-05 ; ADU-04 → ADU-01 → ADU-02 | 72 h | 142 | Sí |
| 9 | Ola 2 · Líderes de operación, comercio exterior y negocio | Gerente de carga internacional | Exportaciones de Cordillera coordinadas puerta a puerta | TRC-01, TRC-02, TRC-04 ; CAR-01 → CAR-02 → CAR-03 | 64 h | 161 | Sí |
| 10 | Ola 2 · Líderes de operación, comercio exterior y negocio | Gerente de zona franca | Zona franca con inventario conciliado y servicios nuevos | TRC-01, TRC-03, TRC-05 ; ZFR-01 → ZFR-02 → ZFR-03 | 64 h | 180 | Sí |
| 11 | Ola 2 · Líderes de operación, comercio exterior y negocio | Gerente comercial | Cuentas rentables y nuevos clientes | TRC-01, TRC-02, TRC-04 ; COM-01 → COM-02 → COM-04 | 68 h | 199 | Sí |
| 12 | Ola 2 · Líderes de operación, comercio exterior y negocio | Coordinador HSEQ | Operación segura, certificada y con cadena de frío | TRC-01 a 05 ; HSQ-03 → HSQ-01 → HSQ-02 | 92 h | 218 | Sí |
| 13 | Ola 2 · Líderes de operación, comercio exterior y negocio | Gestión humana y formación | Operarios y conductores preparados | TRC-01, TRC-02, TRC-03 ; ADM-03 → ADM-04 | 52 h | 237 | Sí |
| 14 | Aliados técnicos | Arquitecto, integrador EDI y APIs | Clientes y sistemas conectados de forma segura | TRC-01 a 05 ; TIC-04 → TIC-01 → TIC-02 | 108 h | 257 | Sí |
| 15 | Aliados técnicos | Analista de datos | Datos del corredor en un solo modelo | TRC-01 a 05 ; TIC-03 → TCT-03 | 84 h | 276 | Sí |
| 16 | Ola 3 · Equipos | Jefe de bodega, analista de inventarios | Inventario exacto y picking productivo | TRC-01, TRC-03, TRC-04 ; CED-03 → CED-02 | 56 h | 296 | Sí |
| 17 | Ola 3 · Equipos | Operario de bodega | Trabajo con los requisitos de cada cliente a la mano | TRC-01, TRC-03 ; CED-04 | 28 h | 314 | Sí |
| 18 | Ola 3 · Equipos | Planeador de rutas, coordinador de flota | Rutas consolidadas y transportadores medidos | TRC-01, TRC-02, TRC-04 ; TRA-01 → TRA-02 | 60 h | 331 | Sí |
| 19 | Ola 3 · Equipos | Conductor | Viajes documentados y conducción segura | TRC-01, TRC-03 ; TRA-04 → HSQ-01 | 40 h | 349 | Sí |
| 20 | Ola 3 · Equipos | Auxiliar de entregas | Entregas probadas y devoluciones ordenadas | TRC-01, TRC-03 ; UMI-02 → UMI-03 | 36 h | 367 | Sí |
| 21 | Ola 3 · Equipos | Analista de monitoreo | Alertas atendidas y clientes informados | TRC-01, TRC-03, TRC-04 ; TCT-01 → TCT-02 | 64 h | 385 | Sí |
| 22 | Ola 3 · Equipos | Especialista en clasificación, auxiliar de aduanas | Expedientes aduaneros completos y bien clasificados | TRC-01, TRC-03 ; ADU-01 → ADU-02 → ADU-03 | 60 h | 403 | Sí |
| 23 | Ola 3 · Equipos | Pricing, coordinador de operaciones internacionales | Embarques cotizados y seguidos | TRC-01, TRC-02, TRC-04 ; CAR-01 → CAR-02 | 56 h | 422 | Sí |
| 24 | Ola 3 · Equipos | Servicio al cliente, KAM | Clientes atendidos al instante y cuentas que crecen | TRC-01, TRC-02 ; COM-03 → COM-04 | 48 h | 440 | Sí |
| 25 | Ola 3 · Equipos | Analista financiero, facturación | Del costo a la factura sin diferencias | TRC-01, TRC-02, TRC-04 ; ADM-01 → ADM-02 | 56 h | 458 | Sí |
| 26 | Ola 3 · Equipos | Líder de seguridad vial | Seguridad vial basada en datos | TRC-01, TRC-05 ; HSQ-01 → TRA-03 | 48 h | 476 | Sí |

## 4. Fichas de cursos

Fuente: `04_fichas_cursos`. Su introducción dice: «Cada ficha amplía un curso del catálogo con cinco campos: proyecto ampliado, herramientas y métodos, objetivos de estudio, diseño instruccional y aceleración esperada.» y agrega la «Estructura del curso» en unidades y clases. Esos seis elementos son la lista contra la que se cuentan los campos faltantes.

Cómo leer las columnas:

- **Horas**: copiadas del campo «Diseño instruccional».
- **Fase o momento que declara**: lo que dice la propia ficha. Ninguna ficha tiene un campo de fase o «Momento del caso»; según `00_metodologia`, ese campo lo asigna A1.
- **Entregable**: el inicio del «Proyecto ampliado» (con «…» cuando sigue) y la evidencia del «Diseño instruccional».
- **Cursos que menciona**: toda mención a otro código, con su frase y dónde está. Es un listado, no un juicio de dependencia: A3 decide cuáles se usan en un laboratorio. Cuando la frase dice que el curso entrega algo a otro, se indica.
- **Campos que le faltan**: contra los seis elementos. Se informa aparte el subcampo «Regla del curso», que tienen 41 de las 48 fichas dentro de «Herramientas y métodos».

| Código | Título | Horas | Fase o momento que declara | Entregable | Cursos que menciona, con la frase y dónde | Campos que le faltan |
| --- | --- | --- | --- | --- | --- | --- |
| LOG-TRC-01 | IA generativa en logística y comercio exterior: uso seguro y datos de clientes | 8 h (4 clases de 2 h en 2 semanas) | «Participan todos los roles antes de su primera fase del programa.» (Diseño instruccional) | «Política de uso de IA de TransAndes Logística, aprobada por el gerente de operaciones …» · Evidencia: «política aprobada por el gerente de operaciones.» | Ninguno | Ninguno |
| LOG-TRC-02 | Productividad con Claude en Excel, PowerPoint y correo | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Reporte semanal del corredor de TransAndes …» · Evidencia: «tres reportes semanales desde datos reales.» | TRC-01: «Se usan según la política de TRC-01.» (Herramientas y métodos) | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-TRC-03 | Procedimientos y requisitos de clientes como documentación viva | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Procedimientos del corredor de TransAndes y matriz de requisitos por cliente …» · Evidencia: «matriz de requisitos de cinco clientes publicada.» | Ninguno | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-TRC-04 | Análisis de datos logísticos para no analistas | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Análisis de un año de pedidos, tiempos y novedades del corredor de TransAndes …» · Evidencia: «análisis presentado con tres acciones aprobadas.» | Ninguno | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-TRC-05 | Gestión de riesgos en la cadena de suministro (BASC y OEA) | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Matriz de riesgos de seguridad del corredor de TransAndes …» · Evidencia: «matriz aprobada por HSEQ.» | Ninguno | Ninguno |
| LOG-DIR-01 | Estrategia de transformación digital e IA en logística | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Hoja de ruta del Programa Corredor Pacífico, aprobada por la junta …» · Evidencia: «hoja de ruta aprobada por la junta.» | Ninguno | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-DIR-02 | Caso de negocio de la IA en operaciones logísticas | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Caso de negocio del piloto del Corredor Pacífico, aprobado por el comité financiero …» · Evidencia: «caso aprobado por el comité financiero.» | Ninguno | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-DIR-03 | Gobierno de IA y datos compartidos con clientes | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Marco de gobierno de la IA y de los datos que los clientes comparten …» · Evidencia: «marco aprobado por la junta.» | TRC-01: «TRC-01 fijó las reglas de uso para cada persona.» (Contexto) | Ninguno |
| LOG-DIR-04 | Nuevos servicios logísticos y expansión | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Portafolio de servicios nuevos de TransAndes …» · Evidencia: «portafolio aprobado por la junta.» | Ninguno | Ninguno |
| LOG-CED-01 | Operación de centros de distribución y WMS | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Layout y reglas de ubicación del CEDI principal de TransAndes por frecuencia de picking, volumen, afinidad de un periodo representativo y requisitos de cada cliente …» · Evidencia: «reglas aprobadas y simuladas sobre un mes de pedidos.» | TRC-03: «matriz de requisitos de TRC-03» (Herramientas y métodos, Datos del expediente) | Ninguno |
| LOG-CED-02 | Productividad de almacén y picking | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Estándares de picking de TransAndes por tipo de pedido y zona …» · Evidencia: «estándares en uso con un mes de medición.» | CED-01: «ubicaciones de CED-01» (clase 3.1, lectura) | Ninguno |
| LOG-CED-03 | Control de inventarios y exactitud | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Programa de conteo cíclico de los CEDI de TransAndes por criticidad …» · Evidencia: «programa en uso con un mes de conteos.» | Ninguno | Ninguno |
| LOG-CED-04 | Asistente de bodega para operarios | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Asistente de bodega en el celular construido como skill sobre la matriz de requisitos de TRC-03 …» · Evidencia: «veinte consultas simuladas evaluadas.» | TRC-03: «construido como skill sobre la matriz de requisitos de TRC-03» (Proyecto ampliado); «Skills con la matriz de TRC-03.» (Herramientas y métodos) · TRC-05: «Controles de TRC-05.» (Herramientas y métodos) | Ninguno |
| LOG-TRA-01 | Planeación y optimización de rutas de carga | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Plan nacional de rutas de TransAndes …» · Evidencia: «plan de un mes comparado con el real.» | TRC-03: «matriz de requisitos de TRC-03» (Datos del expediente); «tomadas de la matriz de TRC-03» (clase 2.1, lectura) | Ninguno |
| LOG-TRA-02 | Gestión de flota propia y tercerizada | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Tablero de la flota propia y tercerizada de TransAndes …» · Evidencia: «tablero en uso con un mes de datos.» | Ninguno | Ninguno |
| LOG-TRA-03 | Mantenimiento predictivo de flota | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Alertas de falla de los camiones propios de TransAndes desde la telemetría …» · Evidencia: «alertas validadas con un trimestre de fallas.» | Ninguno | Ninguno |
| LOG-TRA-04 | Conductor conectado: documentos y novedades | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Aplicación en el celular para los conductores de TransAndes, propios y terceros …» · Evidencia: «diez viajes simulados con novedades reportadas.» | Ninguno | Ninguno |
| LOG-UMI-01 | Ruteo dinámico de última milla | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Ruteo diario de las entregas a los tenderos de Distribuidora Andina …» · Evidencia: «ruteo de dos semanas comparado con el actual.» | Ninguno | Ninguno |
| LOG-UMI-02 | Prueba de entrega y gestión de novedades | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Flujo de prueba de entrega en el celular …» · Evidencia: «cincuenta entregas simuladas con novedades clasificadas.» | UMI-03: «abrir la devolución de UMI-03» (clase 2.1, lectura) · UMI-01: «vuelven al ruteo de UMI-01» (clase 2.1, procedimiento) | Ninguno |
| LOG-UMI-03 | Logística inversa y devoluciones | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Proceso de devoluciones de TransAndes …» · Evidencia: «un mes de devoluciones procesadas.» | TRC-03: «Matriz de requisitos de TRC-03.» (Herramientas y métodos) | Ninguno |
| LOG-TCT-01 | Torre de control logística con IA | 20 h (8 clases de 2,5 h en 5 semanas) | No consta | «Torre de control del Corredor Pacífico …» · Evidencia: «tablero en uso durante un mes con excepciones registradas.» | TIC-02: «el servidor MCP de solo lectura de TIC-02» (Proyecto ampliado); «El servidor de solo lectura de TIC-02 entrega los datos del WMS, el TMS y la agencia de aduanas» (Herramientas y métodos, MCP) · TRC-05: «las alertas de seguridad siguen el protocolo de TRC-05» (Regla del curso) · TRA-04: «la aplicación de TRA-04» (clase 1.1, procedimiento) · TCT-02: «con el protocolo de TCT-02» (clase 3.1, procedimiento) | Ninguno |
| LOG-TCT-02 | Gestión de excepciones y comunicación al cliente | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Protocolo de excepciones de TransAndes por tipo y por cliente …» · Evidencia: «treinta excepciones simuladas gestionadas.» | TCT-01: «Torre de control de TCT-01.» (Herramientas y métodos) | Ninguno |
| LOG-TCT-03 | Indicadores de nivel de servicio (OTIF) | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Tablero de OTIF de TransAndes por cliente, servicio y eslabón …» · Evidencia: «tablero en uso con plan de mejora.» | UMI-02: «pruebas de entrega de UMI-02» (Datos del expediente); «la hora de la prueba de entrega de UMI-02» (clase 1.2, procedimiento) · TCT-02: «causas registradas en TCT-02» (Datos del expediente); «con el criterio de TCT-02» (clase 2.1, procedimiento) | Ninguno |
| LOG-ADU-01 | Clasificación arancelaria asistida por IA | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Propuestas de clasificación arancelaria de las mercancías del corredor …» · Evidencia: «treinta clasificaciones revisadas por el director de aduanas.» | Ninguno | Ninguno |
| LOG-ADU-02 | Declaraciones y documentación aduanera | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Expediente de importación completo …» · Evidencia: «veinte expedientes revisados por el director de aduanas.» | ADU-01: «Clasificaciones de ADU-01.» (Herramientas y métodos); «subpartida decidida en ADU-01» (clase 2.2, lectura) | Ninguno |
| LOG-ADU-03 | Regímenes aduaneros y tratados de libre comercio | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Análisis de los beneficios arancelarios para las exportaciones de galletas de Alimentos Cordillera …» · Evidencia: «análisis verificado por el director de aduanas.» | ADU-01: «clasificaciones de ADU-01» (Datos del expediente) | Ninguno |
| LOG-ADU-04 | Operador Económico Autorizado y cumplimiento aduanero | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Matriz de requisitos del Operador Económico Autorizado de TransAndes construida desde la norma aduanera del país …» · Evidencia: «matriz aprobada con plan de cierre.» | TRC-05: «Matriz de TRC-05.» (Herramientas y métodos) · ADU-01 y ADU-02: «queda como parcial con el plan de ADU-01 y ADU-02» (clase 2.1, procedimiento) | Ninguno de los seis. Sin subcampo «Regla del curso» |
| LOG-CAR-01 | Cotización y pricing de carga internacional | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Modelo de cotización de carga internacional de TransAndes, marítima y aérea …» · Evidencia: «veinte cotizaciones con el modelo.» | CAR-03: «Guía de Incoterms de CAR-03.» (Herramientas y métodos); «los gastos según el Incoterm de CAR-03» (clase 2.1, procedimiento) | Ninguno |
| LOG-CAR-02 | Coordinación de embarques y documentos de transporte | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Seguimiento de los embarques de TransAndes de punta a punta …» · Evidencia: «diez embarques simulados coordinados.» | TIC-02: «el servidor de TIC-02 consulta los hitos» (Herramientas y métodos, MCP) · TRC-05: «Controles de TRC-05.» (Herramientas y métodos); «es una de las formas de fraude de TRC-05» (clase 1.2, procedimiento) | Ninguno |
| LOG-CAR-03 | Incoterms y gestión de riesgos del embarque | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Guía de Incoterms vigentes aplicada a las exportaciones de Alimentos Cordillera …» · Evidencia: «guía aprobada por el gerente de carga.» | Ninguno | Ninguno |
| LOG-ZFR-01 | Operación de zona franca y depósitos | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Proceso de ingreso y salida de mercancía de la zona franca de TransAndes …» · Evidencia: «proceso aprobado por el gerente de zona franca.» | TRC-05: «se activa el protocolo de TRC-05» (clase 1.2, procedimiento) · ADU-02: «la declaración de importación de ADU-02 con su levante» (clase 2.1, procedimiento) | Ninguno |
| LOG-ZFR-02 | Inventarios bajo control aduanero | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Conciliación mensual del inventario físico de la zona franca …» · Evidencia: «tres conciliaciones mensuales.» | Ninguno | Ninguno |
| LOG-ZFR-03 | Servicios de valor agregado | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Propuesta de acondicionamiento de producto para Vitalia dentro de la zona franca …» · Evidencia: «propuesta presentada al cliente.» | Ninguno | Ninguno |
| LOG-COM-01 | Diseño de soluciones logísticas y licitaciones | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Respuesta de TransAndes a la licitación de un cliente nuevo …» · Evidencia: «propuesta presentada al comité comercial.» | CED-01, TCT-03 y ADM-01: «Capacidad de los CEDI de CED-01, OTIF demostrado de TCT-03 y costos de ADM-01.» (Herramientas y métodos, Datos del programa) · DIR-04: «el área farmacéutica prevista en DIR-04» (clase 2.1, procedimiento) | Ninguno |
| LOG-COM-02 | Pricing y rentabilidad por cliente | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Matriz de tarifas y margen de TransAndes por cliente y servicio …» · Evidencia: «análisis aprobado por el gerente financiero.» | ADM-01: «el costo por actividad de ADM-01» (Proyecto ampliado); «Costeo de ADM-01.» (Herramientas y métodos); «Desde ADM-01.» (clase 1.2, lectura) · UMI-01 y UMI-02: «que se corrigen con UMI-01 y UMI-02» (clase 2.2, procedimiento) | Ninguno |
| LOG-COM-03 | Servicio al cliente con agentes de IA | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Asistente de seguimiento de pedidos de TransAndes que verifica que quien pregunta es el titular del pedido, consulta el estado por el servidor MCP de solo lectura, responde …» · Evidencia: «asistente evaluado con cien conversaciones.» | TIC-02: «el servidor de TIC-02 entrega el estado del pedido» (Herramientas y métodos, MCP) · TCT-02: «Protocolo de TCT-02.» (Herramientas y métodos) · UMI-03: «abre el proceso de UMI-03» (clase 1.1, procedimiento) · TRC-05: «como exige TRC-05» (clase 1.2, procedimiento) | Ninguno |
| LOG-COM-04 | Gestión de cuentas clave (KAM) | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Plan de cuenta de Alimentos Cordillera …» · Evidencia: «plan de cuenta presentado al comité comercial.» | COM-02, TCT-03, ADU-03 y DIR-04: «Margen por servicio de COM-02, OTIF con la definición del contrato de TCT-03, beneficios arancelarios de ADU-03 y servicios nuevos de DIR-04.» (Herramientas y métodos, Datos del programa); los tres primeros vuelven en las clases 1.1, 1.2 y 2.1 (procedimiento) · DIR-03: «según DIR-03» (Regla del curso) | Ninguno |
| LOG-HSQ-01 | Seguridad vial y gestión de conductores | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Plan de seguridad vial de TransAndes …» · Evidencia: «plan en uso con un mes de seguimiento.» | TRA-01: «control de la fatiga con las rutas de TRA-01» (Proyecto ampliado); «rutas de TRA-01» (Datos del expediente); «aprobó una ruta de TRA-01 con 11 horas de conducción» (clase 2.2, procedimiento) | Ninguno |
| LOG-HSQ-02 | Mercancías peligrosas y cadena de frío | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Protocolo de transporte de los medicamentos de Vitalia …» · Evidencia: «protocolo aprobado con un mes de registros.» | Ninguno | Ninguno |
| LOG-HSQ-03 | Sistemas de gestión y certificaciones (ISO 9001, BASC) | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Matriz de requisitos de ISO 9001 y BASC de TransAndes que relaciona los requisitos comunes sin perder los propios de cada norma …» · Evidencia: «matriz aprobada con plan de cierre.» | TRC-01: «lo que se liga a la política de TRC-01» (clase 2.2, procedimiento) | Ninguno |
| LOG-ADM-01 | Costeo logístico (ABC) | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Costo por pedido y por cliente de TransAndes …» · Evidencia: «costeo aprobado por el gerente financiero.» | UMI-02: «las causas de novedades de UMI-02» (Datos del expediente); «con las causas de UMI-02» (clase 2.2, procedimiento) · COM-02, como destino: «entregado a COM-02 para el pricing» (Proyecto ampliado); «la entrega a COM-02 con sus supuestos» (Qué se construye); «Entrega a COM-02.» (clase 3.1, lectura) | Ninguno |
| LOG-ADM-02 | Facturación y conciliación con clientes | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Facturación mensual de los servicios de TransAndes conciliada contra la operación …» · Evidencia: «un mes de facturación conciliada.» | COM-02 y UMI-02: «Tarifas de COM-02, movimientos del WMS, viajes del TMS, pruebas de entrega y causas de novedades de UMI-02.» (Herramientas y métodos, Datos del programa); UMI-02: «con las causas de UMI-02» (clase 1.2, procedimiento) | Ninguno |
| LOG-ADM-03 | Gestión del cambio en operaciones logísticas | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Plan de cambio para los CEDI y la flota de TransAndes …» · Evidencia: «plan aprobado y primera medición de adopción.» | HSQ-01, CED-02, TRA-04 y ADM-04: «Reglas de uso de datos de HSQ-01 y CED-02, aplicación del conductor de TRA-04 y módulos móviles de ADM-04.» (Herramientas y métodos, Datos del programa); TRA-04 en la clase 1.1 y ADM-04 en la clase 2.2 (procedimiento) | Ninguno |
| LOG-ADM-04 | Formación de operarios y conductores | 8 h (4 clases de 2 h en 2 semanas) | No consta | «Matriz de competencias de los operarios, auxiliares y conductores de TransAndes por puesto …» · Evidencia: «matriz en uso con un módulo móvil.» | Ninguno | Ninguno |
| LOG-TIC-01 | Integración con clientes (EDI y APIs) | 20 h (8 clases de 2,5 h en 5 semanas) | No consta | «Integración de pedidos, avisos de despacho y estados …» · Evidencia: «integración en ambiente de pruebas con dos clientes.» | Ninguno | Ninguno |
| LOG-TIC-02 | Servidores MCP para sistemas logísticos | 20 h (8 clases de 2,5 h en 5 semanas) | No consta | «Servidor MCP de solo lectura sobre el WMS, el TMS y el sistema aduanero de TransAndes, en el que el servidor decide de qué clientes puede ver datos cada usuario a partir de su identidad y nunca a partir de lo que pide el modelo …» · Evidencia: «servidor usado por la torre de control con registro de consultas.» | TCT-01 y COM-03, como usuarios: «TCT-01 y COM-03 necesitan consultar el estado de los pedidos de todos los clientes» (Contexto); COM-03: «el asistente de COM-03» (clase 3.1, lectura) · TIC-01: «Integraciones de TIC-01.» (Herramientas y métodos) · DIR-03: «según DIR-03» (clase 2.1, procedimiento) | Ninguno |
| LOG-TIC-03 | Analítica logística y tableros | 16 h (8 clases de 2 h en 4 semanas) | No consta | «Modelo de datos del corredor de TransAndes …» · Evidencia: «modelo y tableros en uso por el comité.» | TCT-03: «las definiciones de OTIF de TCT-03» (Herramientas y métodos, Fuentes); vuelve en las clases 1.2 y 2.1 (procedimiento) | Ninguno |
| LOG-TIC-04 | Ciberseguridad y protección de datos de carga | 12 h (6 clases de 2 h en 3 semanas) | No consta | «Evaluación de riesgos y controles sobre los datos de clientes y de carga de TransAndes …» · Evidencia: «evaluación aprobada por la gerencia.» | TRC-05 y DIR-03: «Matriz de TRC-05 y marco de DIR-03.» (Herramientas y métodos); DIR-03: «según DIR-03» (clase 3.1, procedimiento) · TIC-01: «las credenciales de las integraciones con los clientes de TIC-01» (clase 1.1, procedimiento) | Ninguno |

Comprobaciones de estructura hechas sobre las 48 fichas, sin hallazgos: el número de filas de la tabla «Estructura del curso» es igual al número de clases del «Diseño instruccional»; clases por horas por clase da las horas declaradas; las unidades de «Objetivos de estudio» son las mismas y en el mismo orden que las de la tabla; ninguna celda de lectura, procedimiento o actividad está vacía; y cada tabla cierra con «Evidencia final». Los títulos de las 48 fichas son idénticos a los de las tablas de cursos de `01_principios`.

## 5. Comprobaciones (sin corregir nada)

| Comprobación | Método | Resultado |
| --- | --- | --- |
| Cursos que aparecen en una ruta y no tienen ficha | Se expandieron las 26 secuencias de `03` («TRC-01 a 05» como TRC-01…TRC-05) y se compararon con los 48 encabezados «### LOG-…» de `04` | Ninguno |
| Fichas que no aparecen en ninguna ruta | La misma comparación en sentido inverso | Ninguna: los 48 cursos aparecen en al menos una ruta |
| Insumos citados en una ficha que no corresponden a ningún curso | Se buscaron en las 48 fichas todos los códigos con la forma XXX-00 o LOG-XXX-00 y se compararon con los 48 códigos | Ninguno: las 87 menciones remiten a cursos con ficha. No se buscaron menciones sin código (por ejemplo, «la torre de control» sin decir TCT-01) |

Cruces adicionales, también sin hallazgos: las 26 secuencias de `03` son iguales a las de `01`; las horas de cada ruta en `03` son iguales a la suma de las horas de sus fichas; los 48 títulos coinciden entre `01` y `04`; la tabla de fases de `02` asigna cada uno de los 43 cursos de rol a una sola fase y no deja ninguno fuera.

## 6. Propuesta de separación de fichas

Propuesta, sin ejecutar todavía:

1. Un archivo por ficha en `00_sector/fichas/{{código}}.md`, con las líneas exactas del original: desde el encabezado «### LOG-…» hasta la última línea con texto antes del siguiente encabezado. No se cambia ni una letra, tampoco el nivel del encabezado («###»), para que una comparación con el original dé cero diferencias.
2. Un archivo `00_sector/fichas/_introduccion.md` con las líneas 1 a 5 (título y los dos párrafos de introducción). Esos párrafos definen los cinco campos y la estructura de clases que valen para todas las fichas; si no se guardan, se pierden al eliminar `04_fichas_cursos` del conocimiento en A1.
3. Los 12 encabezados de departamento («## Tronco común», «## Dirección»…) no van dentro de ninguna ficha; quedan en `_introduccion.md` como índice, con la tabla de abajo.
4. Comprobación al entregar: al unir `_introduccion.md`, los encabezados de departamento y las 48 fichas en el orden de la tabla, el resultado es idéntico al original. Ya probé que los rangos de abajo cubren todas las líneas de `04` salvo la introducción, los encabezados de departamento y las líneas en blanco entre secciones.

| Código | Archivo | Departamento | Líneas en `04_fichas_cursos` |
| --- | --- | --- | --- |
| LOG-TRC-01 | `00_sector/fichas/LOG-TRC-01.md` | Tronco común | 9 a 38 |
| LOG-TRC-02 | `00_sector/fichas/LOG-TRC-02.md` | Tronco común | 40 a 71 |
| LOG-TRC-03 | `00_sector/fichas/LOG-TRC-03.md` | Tronco común | 73 a 104 |
| LOG-TRC-04 | `00_sector/fichas/LOG-TRC-04.md` | Tronco común | 106 a 136 |
| LOG-TRC-05 | `00_sector/fichas/LOG-TRC-05.md` | Tronco común | 138 a 169 |
| LOG-DIR-01 | `00_sector/fichas/LOG-DIR-01.md` | Dirección | 173 a 205 |
| LOG-DIR-02 | `00_sector/fichas/LOG-DIR-02.md` | Dirección | 207 a 238 |
| LOG-DIR-03 | `00_sector/fichas/LOG-DIR-03.md` | Dirección | 240 a 271 |
| LOG-DIR-04 | `00_sector/fichas/LOG-DIR-04.md` | Dirección | 273 a 308 |
| LOG-CED-01 | `00_sector/fichas/LOG-CED-01.md` | Almacenamiento y CEDI | 312 a 347 |
| LOG-CED-02 | `00_sector/fichas/LOG-CED-02.md` | Almacenamiento y CEDI | 349 a 380 |
| LOG-CED-03 | `00_sector/fichas/LOG-CED-03.md` | Almacenamiento y CEDI | 382 a 413 |
| LOG-CED-04 | `00_sector/fichas/LOG-CED-04.md` | Almacenamiento y CEDI | 415 a 443 |
| LOG-TRA-01 | `00_sector/fichas/LOG-TRA-01.md` | Transporte y flota | 447 a 482 |
| LOG-TRA-02 | `00_sector/fichas/LOG-TRA-02.md` | Transporte y flota | 484 a 515 |
| LOG-TRA-03 | `00_sector/fichas/LOG-TRA-03.md` | Transporte y flota | 517 a 551 |
| LOG-TRA-04 | `00_sector/fichas/LOG-TRA-04.md` | Transporte y flota | 553 a 580 |
| LOG-UMI-01 | `00_sector/fichas/LOG-UMI-01.md` | Última milla | 584 a 618 |
| LOG-UMI-02 | `00_sector/fichas/LOG-UMI-02.md` | Última milla | 620 a 648 |
| LOG-UMI-03 | `00_sector/fichas/LOG-UMI-03.md` | Última milla | 650 a 678 |
| LOG-TCT-01 | `00_sector/fichas/LOG-TCT-01.md` | Torre de control | 682 a 716 |
| LOG-TCT-02 | `00_sector/fichas/LOG-TCT-02.md` | Torre de control | 718 a 749 |
| LOG-TCT-03 | `00_sector/fichas/LOG-TCT-03.md` | Torre de control | 751 a 782 |
| LOG-ADU-01 | `00_sector/fichas/LOG-ADU-01.md` | Agencia de aduanas | 786 a 820 |
| LOG-ADU-02 | `00_sector/fichas/LOG-ADU-02.md` | Agencia de aduanas | 822 a 853 |
| LOG-ADU-03 | `00_sector/fichas/LOG-ADU-03.md` | Agencia de aduanas | 855 a 885 |
| LOG-ADU-04 | `00_sector/fichas/LOG-ADU-04.md` | Agencia de aduanas | 887 a 918 |
| LOG-CAR-01 | `00_sector/fichas/LOG-CAR-01.md` | Carga internacional | 922 a 953 |
| LOG-CAR-02 | `00_sector/fichas/LOG-CAR-02.md` | Carga internacional | 955 a 986 |
| LOG-CAR-03 | `00_sector/fichas/LOG-CAR-03.md` | Carga internacional | 988 a 1016 |
| LOG-ZFR-01 | `00_sector/fichas/LOG-ZFR-01.md` | Zona franca | 1020 a 1051 |
| LOG-ZFR-02 | `00_sector/fichas/LOG-ZFR-02.md` | Zona franca | 1053 a 1084 |
| LOG-ZFR-03 | `00_sector/fichas/LOG-ZFR-03.md` | Zona franca | 1086 a 1114 |
| LOG-COM-01 | `00_sector/fichas/LOG-COM-01.md` | Comercial y servicio | 1118 a 1150 |
| LOG-COM-02 | `00_sector/fichas/LOG-COM-02.md` | Comercial y servicio | 1152 a 1183 |
| LOG-COM-03 | `00_sector/fichas/LOG-COM-03.md` | Comercial y servicio | 1185 a 1219 |
| LOG-COM-04 | `00_sector/fichas/LOG-COM-04.md` | Comercial y servicio | 1221 a 1252 |
| LOG-HSQ-01 | `00_sector/fichas/LOG-HSQ-01.md` | HSEQ y seguridad vial | 1256 a 1287 |
| LOG-HSQ-02 | `00_sector/fichas/LOG-HSQ-02.md` | HSEQ y seguridad vial | 1289 a 1320 |
| LOG-HSQ-03 | `00_sector/fichas/LOG-HSQ-03.md` | HSEQ y seguridad vial | 1322 a 1353 |
| LOG-ADM-01 | `00_sector/fichas/LOG-ADM-01.md` | Finanzas y talento | 1357 a 1388 |
| LOG-ADM-02 | `00_sector/fichas/LOG-ADM-02.md` | Finanzas y talento | 1390 a 1420 |
| LOG-ADM-03 | `00_sector/fichas/LOG-ADM-03.md` | Finanzas y talento | 1422 a 1453 |
| LOG-ADM-04 | `00_sector/fichas/LOG-ADM-04.md` | Finanzas y talento | 1455 a 1483 |
| LOG-TIC-01 | `00_sector/fichas/LOG-TIC-01.md` | TI y datos | 1487 a 1521 |
| LOG-TIC-02 | `00_sector/fichas/LOG-TIC-02.md` | TI y datos | 1523 a 1557 |
| LOG-TIC-03 | `00_sector/fichas/LOG-TIC-03.md` | TI y datos | 1559 a 1594 |
| LOG-TIC-04 | `00_sector/fichas/LOG-TIC-04.md` | TI y datos | 1596 a 1628 |
| Introducción | `00_sector/fichas/_introduccion.md` | — | 1 a 5, más los 12 encabezados de departamento |

## 7. Lo que no consta

- **El contenido de la «pestaña Principios» y de la de Tecnología** que cita P1: No consta en los cuatro documentos. `01` remite a ella para los principios, la estructura y la leyenda comunes.
- **Nombres de personas del caso**: No consta en `02` ni en `01`. Solo hay roles.
- **Fase o «Momento del caso» de cada curso en su ficha**: No consta en 47 fichas; TRC-01 dice «antes de su primera fase del programa». La fase de cada curso de rol solo consta en la tabla de fases de `02` (sección 2.1).
- **Responsable del sector**: No consta en los cuatro documentos.
- **Duración total del programa, fecha de inicio y fin de la fase 7**: No consta. La fase 6 empieza «Desde el mes 5» y la 7 es «Continua».
- **Horas por ruta en `01`**: No consta; solo `03` las da.
- **País del caso, moneda y normativa aduanera aplicable**: No consta. `02` dice que los indicadores varían con «la normativa aduanera de cada país» y `01` nombra el corredor «del Pacífico», sin país.
- **Rangos reservados para datos sintéticos del sector** (placas, guías, documentos de conductores): No consta en los cuatro documentos. Según `00_metodologia`, se deciden en la ronda de A2.
- **Sistemas con nombre propio** (un WMS, un TMS o un sistema aduanero concretos): No consta. Los documentos los nombran solo por tipo.

Observaciones para A1, copiadas sin conciliar (este inventario no las resuelve):

- `01` dibuja el caso en seis pasos y `02` lo divide en siete fases (sección 2.1).
- `02` dice que el tronco común TRC-01 a TRC-05 «se dicta a todos antes de su primera fase»; en `03`, 20 de las 26 rutas tienen en la fase 0 menos de los cinco cursos del tronco.
- P6 dice que el especialista en clasificación arancelaria y el declarante comparten recorrido; la ruta de `03` se llama «Especialista en clasificación, auxiliar de aduanas» y ninguna ruta nombra al declarante.
- Varios roles de la tabla «Roles antes y después» de `01` no figuran con ese nombre en el título de ninguna ruta de `03` (lista en la sección 7.1).
- Algunas menciones entre cursos apuntan a un curso que la tabla de fases de `02` ubica en una fase posterior (por ejemplo, TCT-01, fase 3, menciona la aplicación de TRA-04, fase 5).

### 7.1 Roles de la tabla «Roles antes y después» cuyo nombre no aparece literal en el título de una ruta

Comparación de texto exacto, sin decidir equivalencias: «Conductor de carga» no aparece aunque exista la ruta «Conductor». Son 27 de los 39 roles:

Analista de costos logísticos, Jefe de inventarios, Planeador de transporte, Jefe de tráfico, Jefe de mantenimiento de flota, Conductor de carga, Conductor de última milla, Analista de logística inversa, Analista de torre de control, Especialista en clasificación arancelaria, Declarante de aduanas, Especialista de comercio exterior, Ejecutivo de carga internacional, Coordinador de embarques, Jefe de inventario de zona franca, Ingeniero de soluciones, Gerente de cuenta clave, Analista de servicio al cliente, Coordinador de seguridad vial, Coordinador de mercancías peligrosas y cadena de frío, Coordinador de calidad, Analista de facturación, Gerente de talento humano, Coordinador de formación, Arquitecto de integraciones, Desarrollador de integraciones, Oficial de seguridad de la información.
