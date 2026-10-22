# Ficha de producción · LOG-TRC-01 · IA generativa en logística y comercio exterior: uso seguro y datos de clientes

| Campo | Valor |
| --- | --- |
| Código | LOG-TRC-01 |
| Área y caso de referencia | Logística, transporte y comercio exterior · Programa Corredor Pacífico de TransAndes Logística (empresas y datos ficticios) |
| Departamento | Tronco común, todas las capas (`01`, tabla del tronco común: «Capa: Todas»). No consta un departamento único |
| Momento del caso | Fase 0 · primer curso del tronco común (Biblia 6.2). La ficha comercial no tiene este campo: ver divergencia 1 |
| Bloque de producción | 1 · primer curso que se produce en el sector (`ORDEN-PRODUCCION-Logística.md`: «Primer curso que se produce: LOG-TRC-01»; dependencias: «Ninguna») |
| Responsable del curso | Carolina Barraza |
| Proyecto de auditoría | `AUDITOR · Logística` (conversación nueva por unidad) |
| Tope de gasto del curso | Sin tope: dirección pedagógica autorizó el curso sin tope (P-E1-10 · DD-47). Se mantienen el margen libre antes de cada bloque y el registro del gasto real (`00`, punto 20) |
| Estado | E1 · mapa del curso (`mapa_LOG-TRC-01.md`), rúbrica (`rubrica_LOG-TRC-01.md`) y decisiones DD-23 a DD-47 aprobados por la responsable del curso el 2026-10-22. Siguiente: E2, orden de trabajo de la unidad 1 |
| Fecha | 2026-10-22 |

## 1. Rutas que incluyen el curso

LOG-TRC-01 está en la fase 0 de las 26 rutas y en todas es el primer curso. Nadie llega con cursos previos del sector. Por la regla R1, ninguna clase da por sabido lo que enseñan TRC-02 a TRC-05.

**Qué no se da por sabido (P-E0-1, opción A).** Ningún participante llega sabiendo qué es un dato personal, qué hace confidencial la información de un cliente, qué es información de seguridad de la carga ni quién firma o decide cada cosa. Las clases A parten de cero, empiezan por las prácticas actuales que describe la ficha («los analistas traducen facturas comerciales en herramientas públicas y los conductores mandan fotos de las guías por aplicaciones personales») y usan ejemplos de cada grupo de roles.

**Grupos de roles (P-E0-2 y P-E0-3).** Hay dos grupos:

- **Líderes y analistas.** Hacen la réplica como política de su área y trabajan en nivel completo, con Claude.
- **Operativos** (operario de bodega, conductor y auxiliar de entregas). Hacen la réplica como «reglas de mi puesto». Si no tienen cuenta, trabajan en nivel observado y hacen la actividad con una plantilla.

| Ruta | Ola | Posición en la ruta | Cursos que el participante ya estudió | Grupo (P-E0-2 y P-E0-3) |
| --- | --- | --- | --- | --- |
| Gerente general | 1 | Fase 0 (TRC-01, 02) · 1.º de la ruta, que llega hasta la fase 3 | Ninguno | Líderes y analistas |
| Gerente de operaciones | 1 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gerente financiero | 1 | Fase 0 (TRC-01, 02) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Jefe de torre de control | 2 | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gerente de CEDI | 2 | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Jefe de transporte | 2 | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Coordinador de última milla | 2 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Director de aduanas | 2 | Fase 0 (TRC-01, 03, 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gerente de carga internacional | 2 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gerente de zona franca | 2 | Fase 0 (TRC-01, 03, 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gerente comercial | 2 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Coordinador HSEQ | 2 | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Gestión humana y formación | 2 | Fase 0 (TRC-01 a 03) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Arquitecto, integrador EDI y APIs | Aliado técnico | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Analista de datos | Aliado técnico | Fase 0 (TRC-01 a 05) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Jefe de bodega, analista de inventarios | 3 | Fase 0 (TRC-01, 03, 04) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Operario de bodega | 3 | Fase 0 (TRC-01, 03) · 1.º · fases 0 a 1 | Ninguno | Operativos |
| Planeador de rutas, coordinador de flota | 3 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Conductor | 3 | Fase 0 (TRC-01, 03) · 1.º · fases 0 a 2 | Ninguno | Operativos |
| Auxiliar de entregas | 3 | Fase 0 (TRC-01, 03) · 1.º · fases 0 a 2 | Ninguno | Operativos |
| Analista de monitoreo | 3 | Fase 0 (TRC-01, 03, 04) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Especialista en clasificación, auxiliar de aduanas | 3 | Fase 0 (TRC-01, 03) · 1.º · fases 0 a 3 | Ninguno | Líderes y analistas |
| Pricing, coordinador de operaciones internacionales | 3 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Servicio al cliente, KAM | 3 | Fase 0 (TRC-01, 02) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Analista financiero, facturación | 3 | Fase 0 (TRC-01, 02, 04) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |
| Líder de seguridad vial | 3 | Fase 0 (TRC-01, 05) · 1.º · fases 0 a 2 | Ninguno | Líderes y analistas |

Fuente: `03_rutas_por_rol.md` y `01`, tabla de rutas. Grupos: DD-20.

## 2. Entregable y tarea objetivo

- **Entregable del caso que produce el curso.** La política de uso de IA de TransAndes Logística, aprobada por el gerente de operaciones (Biblia 3.1 y 4.2: existe desde la fase 0). Tiene cinco piezas: la matriz de clasificación con ejemplos del corredor, las reglas por tipo de documento y de cliente, los canales aprobados para operarios y conductores, la lista de decisiones reservadas a personas responsables y la política con su versión para la agencia de aduanas. La versión para aduanas la construye el profesor en el laboratorio 2.1 (P-E0-7). El laboratorio 2.2 agrega, desde la política aprobada, las reglas del puesto del conductor (P-E1-4).
- **Dónde queda en el repositorio.** El repositorio del caso todavía no existe: lo crea este curso en la preparación de su material (E2). Según `27_estructura_carpetas.md`, los entregables de cada curso van en la carpeta de su fase del repositorio del caso, por pull request; para este curso, la carpeta de la fase 0. El nombre exacto de la carpeta se fija al crear el repositorio.
- **Tarea objetivo que mide el participante (P-E0-4, opción C).** Depende del grupo de roles:
  - **Líderes y analistas:** definir las reglas de uso de IA de su área. Es decir, clasificar la información que maneja y decidir, para cada tipo de documento, qué se puede hacer con IA, por qué canal y qué decisión es siempre de una persona responsable.
  - **Operativos:** manejar cada documento de cliente de su trabajo por un canal aprobado.
- **Cómo se mide en líderes y analistas: tiempo.** Unidad: minutos (DD-30).
  - **Línea base, en la unidad 1.** El participante mide cuánto tarda en clasificar sin IA un lote fijo de 6 tipos de documento de su área (P-E1-5). Trabaja solo con nombres de tipos de documento y descripciones, nunca con el contenido (DD-09). Inicio: abre la lista de tipos. Fin: cada tipo tiene su nivel y su justificación.
  - **Medición final, en la réplica (unidad 2).** El participante registra el tiempo de clasificar con IA ese mismo lote, que se compara con la línea base. Registra también el tiempo total de construir sus reglas, que pide la ficha «al cierre» (DD-16).
- **Cómo se mide en los operativos: conducta.** Unidad: documentos de cliente manejados por un canal no aprobado, sobre el total registrado.
  - **Línea base, en la unidad 1.** El participante registra, durante 3 jornadas de trabajo (P-E1-5), por qué canal manejó cada documento de cliente de su trabajo. Solo anota el tipo de documento y el canal, nunca el contenido (DD-09).
  - **Medición final, en la réplica (unidad 2).** Repite el mismo registro de 3 jornadas con sus «reglas de mi puesto» (DD-17). Esta medición no requiere IA, así que vale también para el nivel observado.
- **Forma de registrar.** Plantilla `08_linea_base_medicion.md`, sin modificarla, llenando sus campos marcados (mapa, sección 6). En los operativos, el campo «Tiempo» pasa a «documentos por canal no aprobado / total» (P-E1-6), aprobado por la responsable del curso el 2026-10-22 (P-E1-11).
- **Aceleración esperada según la ficha.** Tiempo para definir las reglas de IA de un área: −60% a −80%. Documentos de clientes fuera de herramientas aprobadas: meta cero. Las dos son metas de diseño, no resultados demostrados (Biblia 5).

## 3. Mapa de insumos

Ningún curso produce insumos para LOG-TRC-01: es el primero de la línea de tiempo (Biblia 6.2: «TRC-01 · Fase 0 · primer curso del tronco · Va después de: —») y su fila en el orden de producción dice «Ninguna». Todo el material es del caso, falta y se produce en la E2 de este curso, que crea el repositorio. El expediente de referencia (Biblia 4.3) incluye «contratos y tarifas de clientes», pero tampoco existe todavía.

**Compuerta de los laboratorios (P-E0-8 · DD-22).** Mientras el profesor construye la política, en la línea de tiempo todavía no está aprobada, y «Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado» (`02` · Biblia 7.2). Por eso los laboratorios y las actividades del curso trabajan solo con tipos de documento y sus descripciones (qué campos tiene cada tipo y de qué cliente es), nunca con el contenido de un documento de cliente, aunque sea sintético. Es la misma compuerta que DD-09 fija para la réplica.

| Insumo | Curso que lo produce | Ruta en el repositorio | Tipo | Estado |
| --- | --- | --- | --- | --- |
| Inventario de documentos del corredor por cliente: facturas comerciales, tarifas, volúmenes, destinatarios, base de tenderos, documentos aduaneros, rutas y horarios de cargas sensibles e información pública, por tipo de documento, con su descripción y sin contenido (laboratorio 1.1 · DD-22) | Ninguno. Lo produce LOG-TRC-01 en su E2 | No existe (repositorio por crear) | Material del caso | Falta · se produce como material del caso |
| Descripción del tipo «factura comercial» de cada cliente: qué campos tiene (proveedor, comprador, mercancía, precios, volúmenes) y de qué cliente es, sin facturas (laboratorios 1.1 y 2.1 · DD-22) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta · se produce como material del caso. Sin facturas, no depende de PEND-9 ni de PEND-10 |
| Descripción de la base de tenderos de Distribuidora Andina: qué campos tiene (nombre de la tienda, dirección, teléfono, pedidos), sin registros (laboratorio 1.1 · DD-22) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta · se produce como material del caso |
| Descripción de la programación de los despachos de medicamentos controlados de Vitalia: qué campos tiene (rutas, horarios, vehículos), sin rutas ni horarios (laboratorio 1.1 · DD-22) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta · se produce como material del caso. Ni reales (Biblia 7.2) ni sintéticos (DD-22) |
| Resumen de las obligaciones de confidencialidad y de uso de la información de los contratos de los cuatro clientes, redactado por TransAndes, sin el texto de los contratos (laboratorios 1.1 y 2.1 · DD-22) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta · se produce como material del caso |
| Plantilla de la matriz de clasificación: niveles, ejemplos por cliente, herramientas y canales permitidos, y responsable (lectura 1.1 y actividades) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta · se produce como material de la clase |
| Descripción de las prácticas actuales de TransAndes: traducción en herramientas públicas y fotos de guías por aplicaciones personales (laboratorio 2.1) | Ninguno. LOG-TRC-01, E2 | La fuente existe en el conocimiento del Proyecto: `LOG-TRC-01.md` (Contexto) y `10_biblia_caso_Logística` 5.2 («Uso de IA: sin reglas»). El extracto para el estudiante no existe | Material del caso | Fuente existe · el extracto falta y se produce en E2 |
| Roles y decisiones reservadas con su responsable: declarante, especialista en clasificación, coordinador HSEQ (laboratorio 1.2) | Ninguno. Extracto de la Biblia | La fuente existe en el conocimiento del Proyecto: `10_biblia_caso_Logística` 3.1 y 7.3. El extracto no existe | Material del caso | Fuente existe · el extracto falta y se produce en E2 |
| Información de la agencia de aduanas para la actividad de la unidad 1: tipos de documentos aduaneros, roles y la sanción del año pasado | Ninguno. Extracto de la Biblia | La fuente existe en el conocimiento del Proyecto: `10_biblia_caso_Logística` 3.1 y 4.1. El extracto no existe; los tipos de documentos aduaneros no constan en la Biblia y se crean como material del caso | Material del caso | Fuente existe en parte · el extracto falta y se produce en E2 |
| Política de ejemplo con el caso sembrado: permite al asistente enviar la declaración al sistema aduanero sin la firma del declarante (actividad de la unidad 1) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso, sembrado y declarado como tal; su manifiesto va fuera del material del estudiante | Falta · se produce como material del caso |
| Guion del comité simulado: quién pregunta (gerente de operaciones y un cliente) y la pregunta sobre las facturas (laboratorio 2.2), y la descripción del puesto del conductor para derivar sus reglas (P-E1-4) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta. Propuesta: un documento breve con los roles del comité (el gerente de operaciones, que aprueba según la Biblia 3.1, y un cliente), la pregunta que cita la ficha y los tipos de documento que maneja el conductor. Se produce en la tarea 2 de la E2, junto con el material de la clase 2.2. No consta si el comité lo simula Claude: se decide en E2. El mismo guion sirve al comité simulado del paquete de aprobación de la réplica (P-E1-1) |
| Lote fijo de 6 tipos de documento para la línea base y la medición final de líderes y analistas (sección 2) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta. Una plantilla de lista de 6 tipos de documento con descripción y sin contenido (DD-09), que cada participante llena con su área (P-E1-5). Se produce en E2 |
| Plantilla de registro de canales de 3 jornadas para la línea base y la medición final de los operativos (sección 2) | Ninguno. LOG-TRC-01, E2 | No existe | Material del caso | Falta. Una tabla de tipo de documento, canal usado y si el canal está aprobado, sin contenido de documentos (DD-09), usable en el celular, para 3 jornadas (P-E1-5). Se produce en E2 |
| Plantilla «reglas de mi puesto» para los operativos: documento → qué puedo hacer → canal → qué decisión no es mía y a quién escalo (actividad de la unidad 2, P-E0-2) | Ninguno. LOG-TRC-01, E4 | No existe | Material de la actividad | Falta. Se produce en la E4 de la unidad 2, con la estructura que decidió P-E0-2 y la forma que muestre el laboratorio 2.2 (P-E1-4) |
| Plantilla de política del curso para el nivel observado y el nivel reducido (sección 5) | Ninguno. LOG-TRC-01, E4 | No existe | Material de la actividad | Falta. Propuesta: se produce en la E4 de la unidad 2, con la estructura de la lectura 2.1 (alcance, clasificación, confidencialidad entre clientes, datos personales, herramientas y canales, decisiones reservadas, incidentes y sanciones) |
| Material del área de Transporte y despacho del corredor de TransAndes para la réplica de quien no tiene empresa, y del puesto de TransAndes igual al de cada operativo (DD-19 · P-E1-3) | Ninguno. LOG-TRC-01, E4 | No existe | Material del caso | Falta. Se produce en la E4 de la unidad 2, desde la Biblia (3.1, 4.1, 5 y 7), con tipos de documento propios del área que la política del profesor no detalla. Incluye el lote de 6 tipos del área y la lista de situaciones de 3 jornadas de cada puesto operativo para la medición (DD-40), y el guion del comité simulado del área (DD-41). Como la línea base es de la unidad 1, el lote y la lista se producen en la E2, con el resto del material de medición |
| Entregables de las clases anteriores del mismo curso (la matriz de 1.1 para 1.2, y así hasta 2.2) | LOG-TRC-01 (ENTREGAR registrado de cada clase) | No existe | Entregable del mismo curso | Se produce en E3; no es insumo de otro curso |

**Lo que la etapa A dejó abierto y este material necesita.** Con la compuerta de los laboratorios (DD-22), el curso no usa documentos con prefijos ni montos: PEND-9 (prefijos) y PEND-10 (moneda) ya no lo bloquean y siguen abiertos para el sector. PEND-11 (geografía ficticia) solo aplica si la matriz o la política de ejemplo nombran ciudades, puerto o tramos; en ese caso lo resuelve la E2 de este curso, que hace el trabajo de A4. Los hechos nuevos del caso que fija esta ficha (DD-07 y DD-18) entran a la Biblia por pull request.

## 4. Productos para otros cursos

| Producto | Cursos que lo consumen | Formato que necesitan |
| --- | --- | --- |
| Política de uso de IA de TransAndes, con la matriz de clasificación, los canales aprobados y las decisiones reservadas | Usan en laboratorio: TRC-02 («Se usan según la política de TRC-01», exportaciones del WMS, el TMS y la facturación) y HSQ-03 («lo que se liga a la política de TRC-01», clase 2.2). Como contexto: DIR-03 («TRC-01 fijó las reglas de uso para cada persona», orden, DD-25). TRC-03, TRC-04 y TRC-05 van después de TRC-01 en la historia, pero no lo usan (orden, DD-29) | No consta en las fichas de TRC-02 ni de HSQ-03. Propuesta: un archivo markdown por pieza, con nombres fijados en E2 |
| La misma política, como regla de datos del sector | Todos los cursos del sector que usan documentos de clientes en una herramienta de IA, y la compuerta de datos de todas las réplicas (Biblia 7.2: «Ningún documento de un cliente antes de que la política de TRC-01 esté aprobada» y «según la política de TRC-01») | El mismo archivo de la política |

## 5. Herramientas externas y clases de configuración

| Herramienta | Para qué la usa el curso | Clase de configuración | Nivel reducido | Nivel observado |
| --- | --- | --- | --- | --- |
| Proyectos de Claude, en el computador y en la app del celular | 1.1: reunir el inventario y clasificarlo · 1.2: definir las decisiones reservadas · 2.1: redactar la política · 2.2: comité simulado y reglas del puesto del conductor · actividades | «Configuración · Tu Proyecto de Claude para el curso, en el computador y en el celular», antes de las clases de la unidad 1 · 20 min (DD-25 · DD-33) | Cuenta personal de Claude (plan recomendado Pro, `00`), solo con el material del caso y nunca con documentos de la empresa. No consta una cuenta de formación de Edutin | Operativos sin cuenta (P-E0-3, opción B): siguen las clases B sobre los resultados del profesor (registros REG) y hacen la actividad con la plantilla del curso, sin IA |
| Docs (capacidad que nombra la ficha; la ficha no precisa el producto) | Alojar la política con su versión y su aprobación (2.1, 2.2 y réplica) | «Configuración · Docs para alojar la política con versión y aprobación», antes de las clases de la unidad 2 · 15 min (P-E1-7 · DD-25). El título y los pasos se ajustan cuando se precise el producto (pendiente 8) | El procesador de textos de su empresa, con historial de versiones | Plantilla de política del curso |
| Herramientas de IA que aprueba la empresa del participante | La réplica las nombra en la política de su área o en las reglas de su puesto (P-E0-3, como en la opción C). El curso no las opera | No lleva: el curso no las usa | No aplica | No aplica |

Los «contratos de los clientes» y la «matriz de clasificación» que la ficha lista entre las herramientas son material y método, no herramientas externas. Ver la sección 3.

## 6. Decisiones de catálogo aplicadas

- [x] Una unidad por semana. Duración total: 2 semanas (coincide con la ficha)
- [x] Subclase A de 30 min, subclase B de 60 min, actividad de 40 min (ninguna supera 60 min)
- [x] Una actividad por unidad. La última es la réplica en la empresa (divergencia 3)
- [x] Puntaje total del curso: 100 puntos (DD-04, reversible). Reparto: actividad 1, 25; actividad 2, 45; quices, 10 + 10; foros, 3 + 4 + 3 (DD-29)
- [x] Sin evaluación entre compañeros. Las actividades las califica un docente de Edutin Academy
- [x] Quiz de 5 preguntas por unidad (10 en total)
- [x] Foros: bienvenida en la unidad 1; discusión y despedida en la unidad 2
- [x] Video en la presentación del curso y en la introducción de cada unidad
- [x] El estudiante sin empresa hace la réplica con el caso: área de Transporte y despacho del corredor de TransAndes; los operativos, el puesto de TransAndes igual al suyo (P-E1-3)
- [x] Duración total: 538 min, unas 9 h (P-E1-7 · DD-33)

## 7. Registro de divergencias con la ficha comercial

| # | Elemento | La ficha comercial dice | La producción decide | Razón | Etapa | En ficha comercial |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Momento del caso | No tiene el campo | Fase 0 · primer curso del tronco común | Biblia 6.2 | 0 | No |
| 2 | Duración | «8 h en 2 semanas, en 4 clases de 2 horas» | 9 h (538 min) en 2 unidades de una semana. Por clase: A de 30 min y B de 60 min. Dos actividades de 40 min, 2 clases de configuración (20 y 15 min), 3 videos (13 min), 2 quices (20 min) y 3 foros (30 min). Ocho horas no caben con las duraciones del catálogo | Decisión de catálogo · P-E1-7 | 0 (cerrada en 1) | No |
| 3 | Actividades | Una por clase (4) | Una por unidad (2) | Decisión de catálogo | 0 | No |
| 4 | Actividad de la unidad 1 | «La información de su área» y «Las de su área» | Ajuste sobre el caso: clasificar la información y listar las decisiones reservadas de la agencia de aduanas de TransAndes, y revisar la política de ejemplo sembrada (el asistente envía la declaración sin la firma del declarante). Entrega su ajuste, el hallazgo y la línea base | Catálogo («las primeras aplican el procedimiento al caso con un ajuste») y P-E0-7, opción A · `00`, punto 16 | 0 y 1 | No |
| 5 | Clase 2.1 | La actividad es el ajuste para la agencia de aduanas con el caso sembrado. El procedimiento no menciona la versión para aduanas | El ajuste de aduanas pasa a la unidad 1. La versión de la política para la agencia de aduanas la construye el profesor en el laboratorio 2.1 | P-E0-7, opción A | 0 | No |
| 6 | Réplica | «Cada participante la de su área» | Dos niveles con los mismos criterios. Líderes y analistas: política de su área, sometida a aprobación. Operativos: «reglas de mi puesto» (documento → qué puedo hacer → canal → qué decisión no es mía y a quién escalo), revisadas por su jefe | P-E0-2, opción B · `03` llama a TRC-01 «Reglas de uso de IA» en esas rutas | 0 | No |
| 7 | Herramientas de la réplica | Proyectos de Claude y Docs | La réplica nombra las herramientas que aprueba la empresa del participante. Los operativos sin cuenta trabajan en nivel observado, con plantilla | P-E0-3 (opciones B y C) | 0 | No |
| 8 | Clases de configuración | No tiene | Dos: Proyecto de Claude (computador y celular) antes de la 1.1, y Docs antes de la 2.1 | `00`, punto 14 | 0 | No |
| 9 | Medición | «Presenta la política de su área y el tiempo que le tomó construirla» | Líderes y analistas: línea base en la unidad 1 (lote fijo de 6 tipos sin IA) y medición final con el mismo lote con IA, más el tiempo total de construcción. Operativos: registro de canales de 3 jornadas en la unidad 1; al cierre, las mismas situaciones con el canal que fijan sus reglas | P-E0-4, opción C · DD-16 · DD-17 · P-E1-5 · P-E1-9 · `00`, punto 16 | 0 y 1 | No |
| 10 | Evidencia final | «Política aprobada por el gerente de operaciones»; el estudiante la «somete a aprobación» | La aprobación del gerente de operaciones es del caso (TransAndes). El participante entrega un paquete de aprobación: constancia de envío a quien aprueba en su empresa (o de revisión del jefe) y respuestas a las preguntas de un comité simulado. La aprobación real no se exige ni se califica | Decisión de catálogo · P-E1-1 | 0 (cerrada en 1) | No |
| 11 | Evidencia final de los operativos | «Matriz de clasificación, decisiones reservadas, canales aprobados, política, registro de la sesión y tiempo de construcción medido», igual para todos | Una lista por grupo y nivel: líderes y analistas, política con sus piezas, paquete de aprobación, registro de la sesión y medición; operativos con cuenta, reglas de mi puesto, paquete de revisión, registro de la sesión y registro de canales; operativos en nivel observado, lo mismo sin registro de sesión | P-E0-2 (opción B) · P-E0-3 (opción B) · DD-27 | 0 (cerrada en 1) | No |
| 12 | Aceleración esperada | «Tiempo para definir las reglas de IA de un área: −60% a −80%. Documentos de clientes fuera de herramientas aprobadas: meta cero», sin distinguir roles | La meta de tiempo (−60% a −80%) se promete y se mide en líderes y analistas. En los operativos se promete y se mide la meta cero de documentos fuera de canales aprobados (DD-17). Cambia la promesa comercial para ese grupo | P-E0-4, opción C · DD-17 | 0 | No |
| 13 | Uso de los Proyectos de Claude | «En la clase 1.1 reúnen el inventario de documentos del corredor para clasificarlos; en la 2.1 ayudan a redactar la política» | Se usan en las cuatro clases B (1.1, 1.2, 2.1 y 2.2) y en las actividades de quien trabaja en nivel completo | Los cuatro procedimientos de la ficha se hacen «con Claude» o con su borrador (DD-05) | 0 | No |
| 14 | Contratos y matriz | Figuran en «Herramientas y métodos» | Son material y método, no herramientas externas: no llevan clase de configuración (sección 5) | `00`, punto 14: la clase de configuración es para herramientas externas | 0 | No |
| 15 | Material de los laboratorios | «El profesor clasifica con Claude la información»; los contratos «aportan las cláusulas» | Claude recibe solo tipos de documento y sus descripciones, sin contenido de documentos de clientes. Los contratos entran como un resumen de sus obligaciones redactado por TransAndes, no como texto | P-E0-8 · DD-22 · `02`: «Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado» | 0 | No |
| 16 | Clase 2.2 B | «Presentación a un comité simulado… registra la aprobación» | Además, el profesor deriva de la política aprobada las reglas del puesto del conductor, que son el modelo de la réplica de los operativos | P-E1-4 | 1 | No |
| 17 | Lectura 2.2 | «Cómo medir el tiempo que tomó construirla» | La forma de medir se enseña en la unidad 1 (actividad 1 y plantilla 08); la lectura 2.2 se queda con la comparación final y la rúbrica | DD-26 | 1 | No |
| 18 | Calificación | No la describe | Cuatro fallas devuelven la entrega de cualquiera de las dos actividades, con una reentrega: cruce entre clientes, delegación de una decisión reservada, exposición de información de seguridad o datos personales, y ruptura de la compuerta | P-E1-2 · DD-34 | 1 | No |
| 19 | Réplica sin empresa | No la describe | Área de Transporte y despacho del corredor de TransAndes; los operativos, el puesto de TransAndes igual al suyo | P-E1-3 | 1 | No |
| 20 | Títulos de las clases | Lecturas: «Contratos y confidencialidad» · «Firma, clasificación y mercancías peligrosas» · «Estructura de una política de IA» · «Presentarla a operaciones». Procedimientos: «Clasificación de la información del corredor» · «Decisiones reservadas» · «Política de TransAndes» · «Presentación a un comité simulado» | Clases A: «Contratos y confidencialidad: qué información de un cliente no puede llegar a otro» · «Firma, clasificación y mercancías peligrosas: lo que siempre decide una persona» · «Estructura de una política de IA que entiendan un analista y un conductor» · «Presentarla a operaciones: qué preguntan quien aprueba y los clientes». Clases B: «Clasificación de la información del corredor con Claude» · «Decisiones reservadas de TransAndes con Claude» · «Política de uso de IA de TransAndes con Claude» · «Comité simulado, aprobación y reglas del puesto del conductor» | DD-42 · P-E1-4 | 1 | No |

## 8. Errores guionizados de la ficha

Regla general: el error que se enseña es el que ocurrió, y manda la nota de ajustes. Si el error previsto no ocurre, se enseña el error real del registro. Si Claude acierta, el acierto se explica con el criterio que lo produjo. Si el error que faltó es central para el objetivo de la clase, se usa un caso sembrado declarado como tal, y nunca se fuerza ni se narra un error que no ocurrió (`00`, principio 6 · `13` n.º 3). El eje del curso es la confidencialidad entre clientes (P-E0-6). Los errores previstos de la clase 1.1 son errores de clasificación de tipos de documento: Claude nunca ve el contenido de un documento de cliente (DD-22).

| Clase | Error previsto en la ficha | Si no ocurre | Qué pasó en la ejecución |
| --- | --- | --- | --- |
| 1.1 · Datos de clientes | Claude deja las facturas comerciales de los clientes como internas (son confidenciales de cada cliente) | Error real o acierto explicado. Como toca el eje del curso (P-E0-6), si ninguna clasificación de confidencialidad entre clientes falla, la siembra se decide en E2 con la responsable del curso | Se completa en la etapa 3 |
| 1.1 · Datos de clientes | Claude no marca la base de tenderos (direcciones y teléfonos) como dato personal | Error real o acierto explicado | Se completa en la etapa 3 |
| 1.1 · Datos de clientes | Claude no marca los horarios de los despachos de medicamentos controlados de Vitalia como información de seguridad | Error real o acierto explicado | Se completa en la etapa 3 |
| 1.2 · Decisiones humanas | Claude propone que la IA apruebe la clasificación arancelaria cuando su confianza supere el 95% | Error real o acierto explicado. El patrón de delegar una decisión reservada se trabaja igual en la actividad de la unidad 1, con la política de ejemplo sembrada y declarada | Se completa en la etapa 3 |
| 2.1 · La política de la empresa | El borrador permite traducir facturas comerciales en un traductor público si no tienen precios | Error real o acierto explicado. El canal aprobado (DD-07) se enseña en cualquier caso como decisión de la política | Se completa en la etapa 3 |
| 2.1 · La política de la empresa | El borrador no dice nada de las fotos de guías que los conductores envían por aplicaciones personales | Error real o acierto explicado. El canal aprobado (DD-18) se enseña en cualquier caso | Se completa en la etapa 3 |
| 2.2 · Réplica y aprobación | La ficha no anticipa ningún error de Claude: un cliente pregunta si sus facturas pueden terminar en el análisis de otro cliente. Tampoco anticipa errores en las reglas del puesto del conductor (P-E1-4) | Se enseña lo que ocurra en el registro | Se completa en la etapa 3 |

## 9. Laboratorios y corridas

- **Tipo de laboratorio por clase práctica.** Proyecto de Claude en las cuatro clases B (1.1, 1.2, 2.1 y 2.2), más una validación por actividad (2) en el mismo entorno.
- **Identificadores de registro.** `REG-LOGTRC01-C<clase>-<n>` (DD-32).
- **Proyecto LAB.** `LAB · LOG-TRC-01`, por crear después del control 1 de la unidad 1, con el texto de configuración del estudiante y solo su material (`00` 5.5).
- **Modelo de los laboratorios.** El que el curso recomiende al estudiante, fijo en todo el curso. Opus 5.5 en esfuerzo medio, como en TEC-TRC-01 (DD-13, confirmada el 2026-10-22).
- **Gasto del curso.** Sin tope, por autorización de dirección pedagógica (P-E1-10 · DD-47). La tabla de laboratorios de la E2 (`00` 5.4) conserva su columna de costo estimado para que el gasto se pueda comparar, pero su suma no es un tope. Datos reales de referencia, de otros cursos:
  - Laboratorio por pieza: USD 2,60 a 11,31 (TEC-TRC-03).
  - Laboratorio 1 de TEC-TRC-04 (cuatro envíos, 12 min): USD 3,09.
  - Validación de tres actividades: USD 23,50 (TEC-TRC-03).
  - Corrida en frío: sin dato.

### Gasto real por unidad

| Unidad | Gasto real (de la nota de ajustes) | Acumulado del curso | % del tope (sin tope: P-E1-10) |
| --- | --- | --- | --- |
| 1 | Se llena al cerrar la unidad | — | — |
| 2 | Se llena al cerrar la unidad | — | — |

- **Laboratorio de cada clase práctica:** obligatorio, con registro firmado.
- **¿Lleva corrida en frío?** Sí (DD-12, confirmada por la responsable del curso el 2026-10-22).
- **Razón.** Es el primer curso del sector, está en las 26 rutas y los operarios y conductores lo toman en el celular, en bloques cortos, sin acompañamiento.
- **Quién la hace.** Claude, en un Proyecto limpio `FRÍO · LOG-TRC-01` que solo tiene el material publicado del curso.

## 10. Registro de decisiones

### 10.1 Respuestas de la especialista

| # | Fecha | Etapa | Pregunta | Decisión | Razón |
| --- | --- | --- | --- | --- | --- |
| P-E0-1 | 2026-10-22 | E0 | ¿Qué se da por sabido de datos personales, confidencialidad y decisiones firmadas? | A: nadie sabe nada. Las clases A parten de cero, desde las prácticas actuales, con ejemplos por grupo de roles | El curso es el primero de las 26 rutas y llega desde el gerente hasta el conductor. Si damos algo por sabido, se pierde a una parte del público. Además, la ficha muestra que hoy se exponen datos de clientes sin notarlo |
| P-E0-2 | 2026-10-22 | E0 | ¿Operario, conductor y auxiliar hacen la misma réplica que los líderes? | B: dos niveles con los mismos criterios. Política del área para líderes y analistas; «reglas de mi puesto» revisadas por su jefe para los operativos | Un operario, un conductor o un auxiliar no tiene un área a su cargo ni aprueba políticas. Lo que necesita es saber qué hacer con cada documento en su puesto, y eso sí lo puede aplicar desde el día siguiente |
| P-E0-3 | 2026-10-22 | E0 | ¿Con qué herramienta de IA llega cada grupo y cuál es el nivel por defecto? | B y C: líderes y analistas con Claude; operativos sin cuenta en nivel observado, con plantilla. La réplica nombra las herramientas que aprueba la empresa del participante | No todas las empresas dan una cuenta de IA a sus operativos, y cada empresa aprueba herramientas distintas. Si la réplica dependiera de Claude, no serviría para la empresa del participante |
| P-E0-4 | 2026-10-22 | E0 | ¿Qué tarea mide el participante en la línea base y en la medición final? | C: tiempo para líderes y analistas (lote fijo de tipos de documento, sin IA en la unidad 1 y con IA al cierre); conducta para los operativos (por qué canal manejan cada documento de cliente, en la unidad 1 y al cierre). Reemplaza la respuesta inicial (A) del mismo día | Adopta la recomendación de Claude: es coherente con la réplica en dos niveles (P-E0-2). Mide el tiempo donde el participante construye reglas con IA, y la meta cero de documentos fuera de canales aprobados donde el participante maneja documentos y puede no tener IA (P-E0-3) |
| P-E0-5 | 2026-10-22 | E0 | ¿Por qué canal envían los conductores (propios y terceros) las fotos de las guías en la fase 0? | A: mensajería con cuenta empresarial administrada por TransAndes, con reglas de retención | Los conductores, incluidos los terceros, ya mandan las fotos desde el celular. Una cuenta empresarial controla dónde quedan esas fotos sin obligarlos a cambiar de hábito, mientras llega la aplicación del conductor |
| P-E0-6 | 2026-10-22 | E0 | ¿Qué falla pesa más en las clases y en la compuerta de datos? | A: que la información de un cliente llegue a otro. Es el eje del curso. Que la delegación de decisiones reservadas y la exposición de información de seguridad sean fallas que invalidan la entrega se decide en E1 (cerrado por P-E1-2) | Un operador logístico atiende a clientes que compiten entre sí. Si la información de uno llega a otro, se pierde la confianza de los dos y se incumplen sus contratos |
| P-E0-7 | 2026-10-22 | E0 | ¿Sobre qué parte del caso hace el participante la actividad de la unidad 1? | A: el ajuste para la agencia de aduanas, con la política de ejemplo sembrada. La versión para aduanas la construye el profesor en la 2.1 | El caso de la agencia de aduanas obliga a aplicar la clasificación y las decisiones reservadas en un área con responsabilidad legal sobre cada declaración. Además, mantiene la unidad 2 dentro de los 40 minutos de la actividad |
| P-E0-8 | 2026-10-22 | E0 (revisión) | ¿Qué recibe Claude en los laboratorios, si en la historia la política todavía no está aprobada? | A: solo tipos de documento y descripciones, sin contenido de documentos de clientes, ni siquiera sintéticos | Es la única opción que no contradice la regla del caso («Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado»), enseña con el ejemplo lo mismo que el curso pide al participante y reduce el material que hay que producir. Las otras opciones obligaban a explicar una excepción en clase (B) o a cambiar una regla de la que dependen el orden de producción y las réplicas del sector (C) |
| P-E1-1 | 2026-10-22 | E1 | ¿Qué cuenta como «sometida a aprobación»? | A: paquete de aprobación. Constancia de envío a quien aprueba en su empresa (rol, fecha y canal, sin nombres) y respuestas a las preguntas de un comité simulado como el de la 2.2, incluida la de cruce entre clientes. La aprobación real no se exige ni se califica. Operativos: constancia de revisión del jefe | Adopta la recomendación de Claude: la entrega muestra que la política llegó a quien la aprueba y que el participante sabe defenderla, sin depender de plazos de terceros que no controla |
| P-E1-2 | 2026-10-22 | E1 | ¿Qué falla invalida la entrega? | A: cuatro fallas devuelven la entrega con una reentrega: cruce entre clientes, delegación de una decisión reservada, exposición de información de seguridad o datos personales, y ruptura de la compuerta | Adopta la recomendación de Claude: las cuatro contradicen la regla del propio curso; una política que las permite no se puede calificar como aceptable con puntos parciales |
| P-E1-3 | 2026-10-22 | E1 | ¿Qué área de TransAndes trabaja quien no tiene empresa (DD-19)? | A: Transporte y despacho del corredor. Los operativos sin empresa usan el puesto de TransAndes igual al suyo | Adopta la recomendación de Claude: toca los tres riesgos del curso (horarios de Vitalia, cargas de los cuatro clientes y datos de conductores terceros) y tiene decisiones reservadas de HSEQ y del jefe de tráfico |
| P-E1-4 | 2026-10-22 | E1 | ¿En qué clase se enseña a escribir «reglas de mi puesto»? | B: el laboratorio 2.2, después del comité, deriva de la política aprobada las reglas del puesto del conductor | Adopta la recomendación de Claude: sin un laboratorio que lo muestre, la actividad de los operativos pediría algo que no se enseñó; la 2.2 tiene espacio y produce así una pieza más del entregable |
| P-E1-5 | 2026-10-22 | E1 | ¿Tamaño del lote y periodo del registro de canales? | A: 6 tipos de documento (líderes y analistas) y 3 jornadas de trabajo (operativos) | Adopta la recomendación de Claude: la línea base de 6 tipos cabe con el ajuste de aduanas en los 40 minutos de la actividad 1, y 3 jornadas dan un registro con varios documentos sin alargar el curso. La duración por tipo no consta y se comprueba en E4 |
| P-E1-6 | 2026-10-22 | E1 | ¿Cómo usan los operativos la plantilla 08? | A: la misma plantilla; el campo «Tiempo» pasa a «documentos por canal no aprobado / total». Requiere el visto bueno de dirección pedagógica (cerrado por P-E1-11) | Adopta la recomendación de Claude: conserva una sola plantilla para sumar resultados por ruta y por empresa |
| P-E1-7 | 2026-10-22 | E1 | ¿Cuántas horas se prometen? | A: 9 h, con las dos clases de configuración. La ficha comercial se actualiza | Adopta la recomendación de Claude: con las duraciones del catálogo el curso suma 538 min; 8 h no caben aunque se quite una configuración |
| P-E1-8 | 2026-10-22 | E1 (revisión) | La actividad 1 es un ajuste sobre el caso y dos participantes podrían entregar lo mismo. ¿Se rediseña? | A: se mantiene y se registra la razón | El catálogo pide que las primeras actividades sean sobre el caso; la decisión propia está en los niveles y en la corrección; la actividad vale 25 de 100 puntos y lo que no se puede copiar está en la actividad 2 y en la línea base con datos propios. Agregar una decisión sobre el propio puesto pediría algo que la unidad 1 no practica, y las variantes multiplican el material y la validación |
| P-E1-9 | 2026-10-22 | E1 (revisión) | Las reglas de mi puesto se muestran en la clase 2.2 B y la entrega es esa misma semana: ¿cómo hacen los operativos la medición final? | A: aplican sus reglas a las mismas situaciones registradas en las 3 jornadas de la línea base | Mantiene el mismo inicio y fin que exige el criterio 7 y cabe en la semana; sigue la lógica de DD-40. Una sola jornada rompe la comparación, y entregar después del cierre depende de una regla de plataforma que no consta |
| P-E1-10 | 2026-10-22 | Paso 5 | ¿Qué tope de gasto tiene el curso? | Sin tope | Dirección pedagógica autorizó el curso sin tope de gasto. Se omite la comparación del paso 5; la estimación de referencia era USD 26 a 61 más la corrida en frío, sin dato |
| P-E1-11 | 2026-10-22 | E1 (cierre) | ¿Se aprueba que los operativos usen la plantilla 08 con «documentos por canal no aprobado / total» en el campo «Tiempo»? (pendiente 11) | Aprobado | Decisión de la responsable del curso al aprobar todas las decisiones pendientes. `00` pedía el visto bueno de dirección pedagógica porque la plantilla es única para el catálogo; queda registrado para su supervisión |

Las razones de P-E0-1 a P-E0-7 las redactó Claude a pedido de la especialista, a partir de los documentos del sector, y ella las adoptó como propias el 2026-10-22. En P-E1-1 a P-E1-7 la especialista eligió las opciones recomendadas por Claude («apruebo todo y me quedo con las opciones recomendadas», 2026-10-22); las razones son las de la recomendación. Lo mismo vale para P-E1-8 y P-E1-9 («me quedo con todo lo recomendado», 2026-10-22).

### 10.2 Decisiones derivadas y operativas de Claude

DD-01 a DD-15 se presentaron en el paquete de aprobación del 2026-10-22. La responsable del curso las confirmó todas el 2026-10-22, incluida la corrida en frío (DD-12). DD-23 a DD-30 se presentaron en el paquete de aprobación de la E1 y se aprobaron el 2026-10-22. DD-31 a DD-38 se derivan de esas respuestas al llenar el mapa, y DD-39 a DD-42 corrigen lo que encontró la revisión 1 del mapa. La responsable del curso aprobó DD-31 a DD-42 el 2026-10-22 («apruebo todas las decisiones»). DD-43 a DD-46 vienen de la revisión del mapa y DD-47 del gasto, todas aprobadas el 2026-10-22.

| ID | Decisión | Escalón · fuente |
| --- | --- | --- |
| DD-01 | Momento del caso: fase 0. No se citan como existentes la aplicación del conductor, el marco DIR-03, los procedimientos TRC-03 ni la matriz TRC-05 | 2 · Biblia 6.1 y 6.2 |
| DD-02 | Ninguna ruta trae cursos previos | 2 · `03` · R1 |
| DD-03 | 2 unidades y 2 actividades; quices, foros y videos según el catálogo | 2 · `00` |
| DD-04 | Puntaje total: 100. Reversible | 6 · `00` |
| DD-05 | 4 laboratorios de tipo Proyecto de Claude, más 2 validaciones | 2 · `00` 5.1 y 5.3 |
| DD-06 | 2 clases de configuración | 2 · `00`, punto 14 |
| DD-07 | Canal aprobado para traducir facturas: el Proyecto de Claude de TransAndes (plan Team). Entra a la Biblia por pull request. Reversible | 4 · ficha · `00` |
| DD-08 | El caso cita la norma colombiana. La réplica escribe «ley de protección de datos aplicable en su país, por confirmar con el área legal» | 2 · Biblia, P-ronda 2 · `00` 3.5 |
| DD-09 | Compuerta de la réplica: tipos de documento y descripciones, sin contenido real; clientes con seudónimo; nada de lo que lista la Biblia 7.2 | 2 y 5 · Biblia 7.2 (C4) |
| DD-10 | Todo insumo es material del caso y lo produce la E2 de este curso, que crea el repositorio | 2 · `00`, punto 3 |
| DD-11 | Los errores de la ficha son hipótesis; plan si no ocurren en la sección 8 | 2 · `00`, principio 6 · `13` n.º 3 |
| DD-12 | Corrida en frío: sí, con Claude en un Proyecto limpio. Es decisión de la responsable del curso (`00` 6.2) y la confirmó el 2026-10-22 | 7 · confirmada por la responsable |
| DD-13 | Modelo de los laboratorios: Opus 5.5 en esfuerzo medio, fijo en todo el curso | 2 · `00` 3.6 |
| DD-14 | Nombre del archivo y numeración de las decisiones | 6 |
| DD-15 | El tope de gasto lo fija dirección pedagógica. Aplicada: dirección pedagógica autorizó el curso sin tope (P-E1-10 · DD-47) | 2 · `00` 6.5 |
| DD-16 | En líderes y analistas, la medición final repite el mismo lote de la línea base (ahora con IA) para que el tiempo sea comparable, y registra aparte el tiempo total de construir las reglas, que pide la ficha. Reversible | 5 · P-E0-4 · ficha, «Al cierre» |
| DD-17 | Los operativos, tengan o no cuenta, miden conducta: por qué canal manejan cada documento de cliente, en la unidad 1 y al cierre. Como esa medición no requiere IA, sirve también al nivel observado, y su meta es la meta cero de la ficha. Reemplaza la versión anterior de DD-17 (2026-10-22), que los excluía de la aceleración. Reversible | 4 · P-E0-4 (opción C) · P-E0-3 · ficha, «Aceleración esperada» · modificada por DD-44 |
| DD-18 | Canal aprobado para las fotos de las guías en la fase 0: mensajería con cuenta empresarial administrada por TransAndes, con reglas de retención, también para los transportadores terceros. Entra a la Biblia por pull request | 2 · P-E0-5 · Biblia 2.2 (terceros) |
| DD-19 | Réplica de quien no tiene empresa: con el caso, sobre un área de TransAndes distinta de la agencia de aduanas. Fijada en E1: Transporte y despacho del corredor (P-E1-3) | 5 · `00`, «Estudiante sin empresa» |
| DD-20 | Grupo de operativos: operario de bodega, conductor y auxiliar de entregas. Los demás roles, incluidos los analistas, hacen la política de su área | 2 · Biblia 3.1 («Operarios, conductores y auxiliares») · `03` |
| DD-21 | La ficha agrega a la plantilla una columna «Grupo» en la sección 1 y las subsecciones 10.1 y 10.2, para registrar P-E0-2, P-E0-3 y las decisiones derivadas. No se quita ningún campo de la plantilla | 6 · operativo |
| DD-22 | Compuerta de los laboratorios: Claude recibe tipos de documento y descripciones, nunca el contenido de un documento de cliente. Las facturas, la base de tenderos y la programación de Vitalia entran como descripción de sus campos; los contratos, como un resumen de sus obligaciones redactado por TransAndes. Reemplaza el material sintético con contenido previsto en la versión anterior de la sección 3 | 2 · P-E0-8 · `02` · Biblia 7.2 |
| DD-23 | Escalera de objetivos: unidad 1 de Comprender a Evaluar (clasifica y evalúa la política sembrada); unidad 2 en Crear (política del área o reglas de mi puesto). Objetivo general de la ficha con verbo observable | 2 · ficha comercial · skill objetivos-bloom-business |
| DD-24 | Pieza del entregable por clase B: 1.1 matriz; 1.2 decisiones reservadas con responsable; 2.1 política con reglas por documento, canales y versión para aduanas; 2.2 registro de aprobación (y reglas del puesto del conductor, P-E1-4) | 2 · ficha, «Qué se construye» |
| DD-25 | Configuración del Proyecto de Claude antes de las clases de la unidad 1; configuración de Docs antes de las clases de la unidad 2 | 2 · DD-06 · `00`, punto 14 |
| DD-26 | La forma de medir se enseña en la unidad 1 (enunciado de la actividad 1 y plantilla 08); la lectura 2.2 conserva la comparación final y la rúbrica | 3 · `00`, punto 16 · skill evaluacion-por-resultado-business («nunca pidas algo que las clases no enseñaron») |
| DD-27 | Evidencia final por grupo y nivel: lista del mapa, sección 2 | 4 · P-E0-2, P-E0-3, P-E0-4 · DD-16, DD-17 |
| DD-28 | Una sola rúbrica para los dos formatos de la réplica, con descriptores que dicen qué se ve en una política y en unas reglas de puesto | 4 · P-E0-2 |
| DD-29 | Reparto de los 100 puntos: actividad 1, 25; actividad 2, 45; quices, 10 + 10; foros, bienvenida 3, discusión 4, despedida 3. Reversible | 6 · glosario 9.6 |
| DD-30 | Unidad de la línea base de líderes y analistas: minutos, en el campo marcado de la plantilla 08 | 6 · `08` |
| DD-31 | La rúbrica de la evidencia final tiene un séptimo criterio, «Paso a aprobación» (5 pts), para que el paquete de aprobación de P-E1-1 tenga su criterio observable. Pesos: 8, 8, 6, 7, 6, 5 y 5 = 45 | 4 · P-E1-1 · `05`, verificación («cada evidencia un criterio observable») |
| DD-32 | Identificadores de registro: `REG-LOGTRC01-C<clase>-<n>`, distintos de los de TEC-TRC-01 | 6 · `00`, «REG-<curso>-<clase>-<n>» |
| DD-33 | Duraciones fijadas: video de presentación 3 min; videos de introducción 5 min; configuración del Proyecto de Claude 20 min; configuración de Docs 15 min; quiz 10 min; foros 10 min. Total del curso: 538 min. Reversible | 6 · decisión operativa de E1: el catálogo (`00`) fija las clases A y B y las actividades, pero no la duración de videos, configuraciones, quices ni foros · aceptada por la responsable con P-E1-7 |
| DD-34 | Las cuatro fallas de P-E1-2 aplican a las dos actividades. La entrega se devuelve sin nota; si la reentrega mantiene la falla, la actividad vale 0. En la actividad 1, la falla 2 se refiere a las reglas que propone el participante, no a la política sembrada | 5 · P-E1-2 · P-E0-6. Reversible |
| DD-35 | Rúbrica de la actividad 1: clasificación de la agencia 7, decisiones reservadas 6, hallazgo 5, corrección 3, línea base 4 = 25 | 6 · DD-29 |
| DD-36 | El registro de canales de los operativos ocurre durante sus jornadas de trabajo y no se cuenta en las horas del curso | 4 · P-E1-5 · `00`, duración de la actividad (40 min) |
| DD-37 | Orden de las piezas de cada unidad: introducción, configuración, clases A, clases B, actividad, quiz y foro | 2 · `00`, etapa 5 |
| DD-38 | Consignas de los foros: bienvenida, qué documentos de clientes pasan por su trabajo y por qué canal; discusión, qué práctica cambia con su política y qué canal la reemplaza; despedida, qué regla va a aplicar primero y con qué rol la va a compartir; siempre sin nombres de clientes ni datos | 4 · `00`, encargo de la etapa 5 («sin datos confidenciales») · DD-09 |
| DD-39 | El criterio 3 de la réplica se comprueba contra la lista de canales y herramientas aprobados que trae la propia entrega, con el rol que los aprueba, y no contra lo que la empresa aprueba de verdad. El nivel 1 del criterio 5 se mide por el número de reglas incompletas | 3 · encargo de E1 («algo que un docente puede ver en la entrega sin preguntar nada») |
| DD-40 | Medición de quien no tiene empresa: líderes y analistas, el lote de 6 tipos del área de Transporte y despacho; operativos, una lista de situaciones de 3 jornadas del puesto de TransAndes (tipo de documento y momento, sin contenido), en la que anotan el canal que usarían, antes y después de sus reglas. Como es material común, la medición se califica solo por estar completa | 4 · `08` («lo que se califica es que esté completa») · P-E1-3 · P-E1-5 |
| DD-41 | Paquete de aprobación del nivel observado: las preguntas del comité vienen en la plantilla «reglas de mi puesto», tomadas del registro del laboratorio 2.2, y el participante las responde por escrito. Quien no tiene empresa entrega solo las respuestas al comité simulado del área | 4 · P-E1-1 · P-E0-3 |
| DD-42 | Títulos de las clases ampliados frente a la ficha comercial (divergencia 20). El nivel 4 de A2 remite a las decisiones reservadas del material de la agencia, con la firma y transmisión y la clasificación definitiva como mínimo (Biblia 7.3), porque los tipos de documentos aduaneros se crean en E2 | 6 · `00` («títulos claros») · Biblia 7.3 |
| DD-43 | Copiabilidad de la actividad 1 aceptada sin rediseño, con la razón registrada en el diagnóstico de la rúbrica | 1 · P-E1-8 |
| DD-44 | Medición final de los operativos: las mismas situaciones de la línea base, con el canal que fijan sus reglas; documentos por canal no aprobado / total. Modifica DD-17. La medición muestra si las reglas cubren cada situación, no el cambio en jornadas posteriores | 1 · P-E1-9 |
| DD-45 | El área de Transporte y despacho de TransAndes, que usa la réplica sin empresa, es un hecho nuevo del caso: entra a la Biblia por pull request antes de la E4 de la unidad 2. El puesto de la ruta se nombra «operario de bodega», como en `03` | 1 · Biblia, sección 3 · `03` |
| DD-46 | Verbos de la escalera: clase 2.2 A en Analizar («Relaciona»), porque las clases A sirven a Comprender o Analizar; clases 1.1 B y 1.2 B con «Aplica», y clase 2.2 B con «Formula» como verbo principal | 1 · skill objetivos-bloom-business |
| DD-47 | Consecuencias de no tener tope: la parte 6 de cada orden de trabajo («Cuánto puedes gastar») dice que no hay tope por autorización de dirección pedagógica; antes de cada bloque se comprueba que haya al menos USD 25 libres en el margen de la organización y, si no los hay, la ejecución se detiene; cada envío anota su costo real en el registro y el gasto de cada unidad se anota en el tablero del sector. El aviso del 75 % no aplica | 2 · P-E1-10 · `00`, punto 20 y 6.5 · `13`, error 9 |

## 11. Cierre de la ficha

| Rol | Nombre | Fecha | Observaciones |
| --- | --- | --- | --- |
| Responsable del curso | Carolina Barraza | Pendiente | Pendiente |
| Dirección pedagógica (supervisión) | Amparo | Pendiente | Sin detener el avance |

**Pendientes para cerrar la ficha**

1. Cerrado el 2026-10-22: dirección pedagógica autorizó el curso sin tope de gasto (P-E1-10 · DD-47).
2. Cerrado el 2026-10-22: razones de la especialista registradas en P-E0-1 a P-E0-7.
3. Cerrado el 2026-10-22: DD-01 a DD-15 y la corrida en frío (DD-12) confirmadas.
4. Cerrado el 2026-10-22: con P-E0-4 en la opción C desaparece la diferencia con P-E0-3; DD-16 y DD-17 quedan ajustadas a esa respuesta.
5. Cerrado el 2026-10-22: `08_linea_base_medicion.md`, `27_estructura_carpetas.md` y `ORDEN-PRODUCCION-Logística.md` están en el conocimiento del Proyecto.
6. PEND-11 (geografía ficticia): lo resuelve la E2 de este curso solo si el material nombra lugares. PEND-9 y PEND-10 ya no bloquean este curso (DD-22).
7. Pull request a la Biblia con DD-07, DD-18 y DD-45.
8. Precisar qué producto es «Docs» en la ficha comercial, para titular y escribir su clase de configuración (su duración y su lugar ya están fijos: DD-33).
9. Ruta del entregable: carpeta de la fase 0 del repositorio del caso (`27`). Su nombre exacto se fija al crear el repositorio en la E2.
10. Cerrado el 2026-10-22: compuerta de los laboratorios decidida en P-E0-8 (DD-22).
11. Cerrado el 2026-10-22: uso de la plantilla 08 por los operativos aprobado por la responsable del curso (P-E1-11).
12. Actualizar la ficha comercial con las divergencias 2, 10, 11 y 16 a 20 al publicar (E6).
