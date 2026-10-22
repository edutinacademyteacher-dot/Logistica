# Orden de producción · Logística

<!-- Etapa A (encargo A3). Un curso solo se puede producir cuando ya existen los entregables de los cursos de los que depende. Solo es dependencia lo que se usa en un laboratorio; cada dependencia cita la frase de la ficha. Las dependencias inferidas se marcan. -->

| Campo | Valor |
| --- | --- |
| Sector | Logística, transporte y comercio exterior |
| Etapa | A3 · Orden de producción |
| Fecha | 2026-10-21 |
| Fuentes | Fichas corregidas `LOG-*.md` (48) · `03_rutas_por_rol.md` corregido · `10_biblia_caso_Logística.md` · `AUDITORIA-COHERENCIA-Logística.md` (versión de cierre) · `00_REGISTRO_CAMBIOS.md` · `29_glosario_terminos.md` |
| Prioridad comercial | Ninguna ruta tiene prioridad comercial por ahora (respuesta del responsable del sector, 2026-10-21). Queda la consulta a dirección del catálogo (PEND-22) |
| Aprobado por | Carolina Barraza · 2026-10-21 |
| Revisado por dirección pedagógica | Pendiente · antes del segundo curso del sector |

Las empresas y los datos del caso son ficticios.

**Cómo leer este documento.** Un bloque dice qué se puede producir, no cuándo ocurre en la historia. Cada curso se escribe desde su «Momento del caso» (Biblia, sección 6.2), aunque se produzca antes que cursos que ocurren antes que él en el caso. Ola, bloque y fase son tres órdenes distintos (glosario, sección 7.2).

**Criterio de dependencia (DD-25).** Es dependencia lo que el laboratorio o la actividad trabaja: datos del expediente o del programa, una herramienta o fuente que «aporta», una «Regla del curso» que se aplica en el laboratorio o un procedimiento que opera sobre el entregable. Es contexto lo que solo aparece en una lectura o narra otro curso sin que el laboratorio lo use (glosario, sección 4; Auditoría, sección 7).

## 1. Dependencias

Una fila por relación que la ficha del curso declara. Los cursos sin ninguna mención a otro curso tienen una fila «Ninguna». Las frases se comprobaron una por una contra el texto de la ficha corregida.

| Curso | Depende de | Tipo | Frase de la ficha | ¿Inferida? |
| --- | --- | --- | --- | --- |
| TRC-01 | Ninguna | — | La ficha no cita a otro curso | — |
| TRC-02 | TRC-01 | usa en laboratorio | «Se usan según la política de TRC-01» (Herramientas y métodos, Exportaciones del WMS, el TMS y la facturación) | no |
| TRC-03 | Ninguna | — | La ficha no cita a otro curso | — |
| TRC-04 | Ninguna | — | La ficha no cita a otro curso | — |
| TRC-05 | Ninguna | — | La ficha no cita a otro curso | — |
| DIR-01 | Ninguna | — | La ficha no cita a otro curso | — |
| DIR-02 | DIR-01 | usa en laboratorio | Sin frase que la declare; «Caso de negocio del piloto del Corredor Pacífico» (Proyecto ampliado) | sí: la ficha no cita a DIR-01; valora el piloto que DIR-01 elige («elegir el piloto», LOG-DIR-01, Método). La Biblia, sección 6.2, ya la marcaba inferida. Se confirma en la etapa 0 de DIR-02 |
| DIR-03 | TRC-01 | contexto | «TRC-01 fijó las reglas de uso para cada persona» (Contexto) | no |
| DIR-04 | Ninguna | — | La ficha no cita a otro curso | — |
| TIC-01 | Ninguna | — | La ficha no cita a otro curso | — |
| TIC-04 | TRC-05 | usa en laboratorio | «Matriz de TRC-05 y marco de DIR-03. Aportan los riesgos físicos de la carga y el protocolo de notificación a los clientes» (Herramientas y métodos) | no |
| TIC-04 | DIR-03 | usa en laboratorio | «Matriz de TRC-05 y marco de DIR-03» (Herramientas y métodos) · «la notificación a los clientes según DIR-03» (clase 3.1, procedimiento) | no |
| TIC-04 | TIC-01 | usa en laboratorio | «las credenciales de las integraciones con los clientes de TIC-01» (clase 1.1, procedimiento) | no |
| TIC-02 | DIR-03 | usa en laboratorio | «liberar mercancía es una decisión de una persona autorizada, según DIR-03» (clase 2.1, procedimiento) | no |
| TIC-02 | TIC-01 | usa en laboratorio | «Integraciones de TIC-01. Aportan los datos de los clientes que el servidor consulta» (Herramientas y métodos) | no |
| TIC-02 | TCT-01 | lo usará después (no es dependencia) | «TCT-01 y COM-03 van a necesitar consultar el estado de los pedidos de todos los clientes» (Contexto) | no |
| TIC-02 | COM-03 | lo usará después (no es dependencia) | «TCT-01 y COM-03 van a necesitar consultar el estado de los pedidos de todos los clientes» (Contexto) · «cómo el asistente de COM-03 recibirá en cada sesión solo los pedidos del titular verificado» (clase 3.1, lectura) | no |
| TRA-04 | Ninguna | — | La ficha no cita a otro curso | — |
| TCT-01 | TRC-05 | usa en laboratorio | «las alertas de seguridad siguen el protocolo de TRC-05» (Regla del curso) | no |
| TCT-01 | TIC-02 | usa en laboratorio | «El servidor de solo lectura de TIC-02 entrega los datos del WMS, el TMS y la agencia de aduanas» (Herramientas y métodos, MCP) | no |
| TCT-01 | TRA-04 | usa en laboratorio | «los registros de salida y llegada que los terceros hacen con la aplicación de TRA-04» (clase 1.1, procedimiento) | no |
| TCT-01 | TCT-02 | lo usará después (no es dependencia) | «el analista decide la acción y la comunicación al cliente, que seguirá el protocolo de TCT-02» (clase 3.1, procedimiento) | no |
| TCT-02 | TCT-01 | usa en laboratorio | «Torre de control de TCT-01. Entrega las excepciones priorizadas con sus datos» (Herramientas y métodos) | no |
| ADU-01 | Ninguna | — | La ficha no cita a otro curso | — |
| ADU-02 | ADU-01 | usa en laboratorio | «Clasificaciones de ADU-01. Aportan la subpartida decidida por el especialista» (Herramientas y métodos) · «subpartida decidida en ADU-01» (clase 2.2, lectura) | no |
| ADU-04 | TRC-05 | usa en laboratorio | «Matriz de TRC-05. Aporta los controles de seguridad que ya están en marcha» (Herramientas y métodos) | no |
| ADU-04 | ADU-01 | usa en laboratorio | «queda como parcial con el plan de ADU-01 y ADU-02» (clase 2.1, procedimiento) | no |
| ADU-04 | ADU-02 | usa en laboratorio | «queda como parcial con el plan de ADU-01 y ADU-02» (clase 2.1, procedimiento) | no |
| ADU-03 | ADU-01 | usa en laboratorio | «clasificaciones de ADU-01» (Datos del expediente) | no |
| ZFR-01 | TRC-05 | usa en laboratorio | «un vehículo con el sello roto no ingresa y se activa el protocolo de TRC-05» (clase 1.2, procedimiento) | no |
| ZFR-01 | ADU-02 | usa en laboratorio | «esa salida exige la declaración de importación de ADU-02 con su levante antes de que el camión salga» (clase 2.1, procedimiento) | no |
| ZFR-02 | Ninguna | — | La ficha no cita a otro curso | — |
| ZFR-03 | Ninguna | — | La ficha no cita a otro curso | — |
| CED-01 | TRC-03 | usa en laboratorio | «capacidad de carga de los racks y matriz de requisitos de TRC-03» (Datos del expediente) | no |
| CED-02 | CED-01 | contexto | «ubicaciones de CED-01» (clase 3.1, lectura) | no |
| CED-03 | Ninguna | — | La ficha no cita a otro curso | — |
| CED-04 | TRC-03 | usa en laboratorio | «construido como skill sobre la matriz de requisitos de TRC-03» (Proyecto ampliado) · «Skills con la matriz de TRC-03. La skill responde solo desde la matriz vigente» (Herramientas y métodos) | no |
| CED-04 | TRC-05 | usa en laboratorio | «Controles de TRC-05. La verificación del sello y la cadena de frío son controles de seguridad que el asistente nunca flexibiliza» (Herramientas y métodos) | no |
| TRA-01 | TRC-03 | usa en laboratorio | «matriz de requisitos de TRC-03, parqueaderos seguros y restricciones viales» (Datos del expediente) · «tomadas de la matriz de TRC-03» (clase 2.1, lectura) | no |
| TRA-02 | Ninguna | — | La ficha no cita a otro curso | — |
| TRA-03 | Ninguna | — | La ficha no cita a otro curso | — |
| UMI-01 | Ninguna | — | La ficha no cita a otro curso | — |
| UMI-02 | UMI-01 | contexto | «las llegadas fuera de ventana vuelven al ruteo de UMI-01» (clase 2.1, procedimiento) | no |
| UMI-03 | TRC-03 | usa en laboratorio | «Matriz de requisitos de TRC-03. Aporta los criterios de cada cliente para devoluciones, reproceso y destrucción» (Herramientas y métodos) | no |
| TCT-03 | TCT-02 | usa en laboratorio | «causas registradas en TCT-02» (Datos del expediente) · «con el criterio de TCT-02, solo se excluyen los que no se podían evitar ni mitigar» (clase 2.1, procedimiento) | no |
| TCT-03 | UMI-02 | usa en laboratorio | «pruebas de entrega de UMI-02» (Datos del expediente) · «con la hora de la prueba de entrega de UMI-02 y el GPS, el OTIF de Andina baja tres puntos» (clase 1.2, procedimiento) | no |
| TIC-03 | TCT-03 | usa en laboratorio | «las definiciones de OTIF de TCT-03» (Herramientas y métodos, Fuentes) · «una fórmula propia distinta de la de TCT-03» (clase 2.1, procedimiento) | no |
| TIC-03 | TRC-04 | contexto | «los tiempos por eslabón que TRC-04 y TCT-03 calculaban por separado» (clase 1.2, procedimiento) | no |
| CAR-03 | Ninguna | — | La ficha no cita a otro curso | — |
| CAR-01 | CAR-03 | usa en laboratorio | «Guía de Incoterms de CAR-03. Define qué gastos van por cuenta del cliente y cuáles por cuenta de TransAndes en cada término» (Herramientas y métodos) · «los gastos según el Incoterm de CAR-03» (clase 2.1, procedimiento) | no |
| CAR-02 | TRC-05 | usa en laboratorio | «Controles de TRC-05. La verificación de cambios de consignatario por un canal conocido previene el fraude» (Herramientas y métodos) · «es una de las formas de fraude de TRC-05» (clase 1.2, procedimiento) | no |
| CAR-02 | TIC-02 | usa en laboratorio | «En la clase 2.1 el servidor de TIC-02 consulta en el TMS los hitos que llegan de las integraciones con las navieras aprobadas en TCT-01» (Herramientas y métodos, MCP) | no |
| CAR-02 | TCT-01 | usa en laboratorio | «En la clase 2.1 el servidor de TIC-02 consulta en el TMS los hitos que llegan de las integraciones con las navieras aprobadas en TCT-01» (Herramientas y métodos, MCP) | no |
| HSQ-03 | TRC-01 | usa en laboratorio | «lo que se liga a la política de TRC-01» (clase 2.2, procedimiento) | no |
| HSQ-02 | Ninguna | — | La ficha no cita a otro curso | — |
| HSQ-01 | TRA-01 | usa en laboratorio | «rutas de TRA-01, horas de conducción y accidentes del año» (Datos del expediente) · «aprobó una ruta de TRA-01 con 11 horas de conducción» (clase 2.2, procedimiento) | no |
| COM-03 | TRC-05 | usa en laboratorio | «el cambio escala a un agente, que lo verifica llamando al contacto registrado, como exige TRC-05» (clase 1.2, procedimiento) | no |
| COM-03 | TIC-02 | usa en laboratorio | «En la clase 2.1 el servidor de TIC-02 entrega el estado del pedido, solo al titular verificado» (Herramientas y métodos, MCP) | no |
| COM-03 | TCT-02 | usa en laboratorio | «Protocolo de TCT-02. Define qué se comunica ante una excepción y quién lo hace» (Herramientas y métodos) | no |
| COM-03 | UMI-03 | usa en laboratorio | «un reclamo va siempre a un agente, que abre el proceso de UMI-03» (clase 1.1, procedimiento) | no |
| ADM-01 | UMI-02 | usa en laboratorio | «las causas de novedades de UMI-02» (Datos del expediente) · «con las causas de UMI-02, un tercio se debió a llegadas fuera de ventana de TransAndes» (clase 2.2, procedimiento) | no |
| ADM-01 | COM-02 | lo usará después (no es dependencia) | «entregado a COM-02 para el pricing» (Proyecto ampliado) · «la entrega a COM-02 con sus supuestos» (Qué se construye) | no |
| COM-02 | ADM-01 | usa en laboratorio | «el costo por actividad de ADM-01» (Proyecto ampliado) · «Costeo de ADM-01. Aporta el costo por actividad» (Herramientas y métodos) | no |
| COM-02 | UMI-01 | contexto | «que se corrigen con UMI-01 y UMI-02» (clase 2.2, procedimiento) | no |
| COM-02 | UMI-02 | contexto | «que se corrigen con UMI-01 y UMI-02» (clase 2.2, procedimiento) | no |
| ADM-02 | UMI-02 | usa en laboratorio | «causas de novedades de UMI-02» (Herramientas y métodos, Datos del programa) · «con las causas de UMI-02, las que se debieron a llegadas fuera de ventana de TransAndes salen de la factura» (clase 1.2, procedimiento) | no |
| ADM-02 | COM-02 | usa en laboratorio | «Tarifas de COM-02» (Herramientas y métodos, Datos del programa) | no |
| COM-01 | DIR-03 | usa en laboratorio | Sin frase que la declare; «los casos de otros clientes se presentan solo anonimizados y con su consentimiento» (Regla del curso) | sí: la ficha no cita a DIR-03; la regla de consentimiento la fija DIR-03 (Auditoría, sección 7, «Datos de Vitalia en COM-01»). Se confirma en la etapa 0 de COM-01 |
| COM-01 | DIR-04 | usa en laboratorio | «la solución usa el área farmacéutica prevista en DIR-04, con su fecha de habilitación como condición» (clase 2.1, procedimiento) | no |
| COM-01 | CED-01 | usa en laboratorio | «Capacidad de los CEDI de CED-01, OTIF demostrado de TCT-03 y costos de ADM-01» (Herramientas y métodos, Datos del programa) | no |
| COM-01 | TCT-03 | usa en laboratorio | «Capacidad de los CEDI de CED-01, OTIF demostrado de TCT-03 y costos de ADM-01» (Herramientas y métodos, Datos del programa) · «la oferta compromete el OTIF que TCT-03 demuestra para la operación» (clase 2.2, procedimiento) | no |
| COM-01 | ADM-01 | usa en laboratorio | «Capacidad de los CEDI de CED-01, OTIF demostrado de TCT-03 y costos de ADM-01» (Herramientas y métodos, Datos del programa) | no |
| COM-04 | DIR-03 | usa en laboratorio | «El plan usa solo información del propio cliente y de TransAndes, según DIR-03» (Regla del curso) | no |
| COM-04 | DIR-04 | usa en laboratorio | «servicios nuevos de DIR-04» (Herramientas y métodos, Datos del programa) | no |
| COM-04 | ADU-03 | usa en laboratorio | «beneficios arancelarios de ADU-03» (Herramientas y métodos, Datos del programa) · «Quedan el aprovechamiento de los tratados de ADU-03» (clase 2.1, procedimiento) | no |
| COM-04 | TCT-03 | usa en laboratorio | «OTIF con la definición del contrato de TCT-03» (Herramientas y métodos, Datos del programa) · «con la definición del contrato de TCT-03, el OTIF es menor» (clase 1.2, procedimiento) | no |
| COM-04 | COM-02 | usa en laboratorio | «Margen por servicio de COM-02» (Herramientas y métodos, Datos del programa) · «con el margen de COM-02» (clase 1.1, procedimiento) | no |
| ADM-04 | Ninguna | — | La ficha no cita a otro curso | — |
| ADM-03 | TRA-04 | usa en laboratorio | «aplicación del conductor de TRA-04» (Herramientas y métodos, Datos del programa) · «que usan la aplicación de TRA-04 sin ser empleados» (clase 1.1, procedimiento) | no |
| ADM-03 | CED-02 | usa en laboratorio | «Reglas de uso de datos de HSQ-01 y CED-02» (Herramientas y métodos, Datos del programa) | no |
| ADM-03 | HSQ-01 | usa en laboratorio | «Reglas de uso de datos de HSQ-01 y CED-02» (Herramientas y métodos, Datos del programa) | no |
| ADM-03 | ADM-04 | usa en laboratorio | «módulos móviles de ADM-04» (Herramientas y métodos, Datos del programa) · «los módulos de ADM-04 en la inducción» (clase 2.2, procedimiento) | no |

### 1.1 Quién usará después el entregable de cada curso

Se obtiene invirtiendo las dependencias de la tabla anterior; la frase está en la fila del curso que lo usa. No son dependencias del curso de la izquierda.

| Curso | Lo usarán en su laboratorio | Cursos detenidos en total (directos e indirectos) |
| --- | --- | --- |
| TRC-05 | TIC-04, TCT-01, ADU-04, ZFR-01, CED-04, CAR-02, COM-03 | 12 |
| DIR-03 | TIC-04, TIC-02, COM-01, COM-04 | 10 |
| TIC-01 | TIC-04, TIC-02 | 10 |
| TRA-04 | TCT-01, ADM-03 | 9 |
| TRC-03 | CED-01, CED-04, TRA-01, UMI-03 | 8 |
| TIC-02 | TCT-01, CAR-02, COM-03 | 8 |
| TCT-01 | TCT-02, CAR-02 | 7 |
| UMI-02 | TCT-03, ADM-01, ADM-02 | 7 |
| TCT-02 | TCT-03, COM-03 | 5 |
| ADU-01 | ADU-02, ADU-04, ADU-03 | 5 |
| ADM-01 | COM-02, COM-01 | 4 |
| TCT-03 | TIC-03, COM-01, COM-04 | 3 |
| TRC-01 | TRC-02, HSQ-03 | 2 |
| DIR-04 | COM-01, COM-04 | 2 |
| ADU-02 | ADU-04, ZFR-01 | 2 |
| TRA-01 | HSQ-01 | 2 |
| COM-02 | ADM-02, COM-04 | 2 |
| DIR-01 | DIR-02 | 1 |
| ADU-03 | COM-04 | 1 |
| CED-01 | COM-01 | 1 |
| CED-02 | ADM-03 | 1 |
| UMI-03 | COM-03 | 1 |
| CAR-03 | CAR-01 | 1 |
| HSQ-01 | ADM-03 | 1 |
| ADM-04 | ADM-03 | 1 |
| TRC-02 | Ninguno | 0 |
| TRC-04 | Ninguno | 0 |
| DIR-02 | Ninguno | 0 |
| TIC-04 | Ninguno | 0 |
| ADU-04 | Ninguno | 0 |
| ZFR-01 | Ninguno | 0 |
| ZFR-02 | Ninguno | 0 |
| ZFR-03 | Ninguno | 0 |
| CED-03 | Ninguno | 0 |
| CED-04 | Ninguno | 0 |
| TRA-02 | Ninguno | 0 |
| TRA-03 | Ninguno | 0 |
| UMI-01 | Ninguno | 0 |
| TIC-03 | Ninguno | 0 |
| CAR-01 | Ninguno | 0 |
| CAR-02 | Ninguno | 0 |
| HSQ-03 | Ninguno | 0 |
| HSQ-02 | Ninguno | 0 |
| COM-03 | Ninguno | 0 |
| ADM-02 | Ninguno | 0 |
| COM-01 | Ninguno | 0 |
| COM-04 | Ninguno | 0 |
| ADM-03 | Ninguno | 0 |

## 2. Bloques

Un curso entra en el primer bloque en que ya existen todos sus insumos. Dentro del bloque 1 van primero los cursos del tronco común en el orden en que el caso los necesita (DD-27); el resto de cada bloque va ordenado por el número de cursos que libera (DD-31). Los cursos de un mismo bloque se pueden producir a la vez.

| Bloque | Cursos, en orden de producción | Qué los libera |
| --- | --- | --- |
| 1 | TRC-01 → TRC-05 → TRC-03 → TRC-04 → DIR-03 → TIC-01 → TRA-04 → UMI-02 → ADU-01 → DIR-04 → DIR-01 → CED-02 → CAR-03 → ADM-04 → ZFR-02 → ZFR-03 → CED-03 → TRA-02 → TRA-03 → UMI-01 → HSQ-02 (21) | Sin dependencias |
| 2 | TIC-02 · ADM-01 · ADU-02 · TRA-01 · ADU-03 · CED-01 · UMI-03 · TRC-02 · DIR-02 · TIC-04 · CED-04 · CAR-01 · HSQ-03 (13) | TRC-01 (bloque 1), TRC-03 (bloque 1), TRC-05 (bloque 1), DIR-01 (bloque 1), DIR-03 (bloque 1), TIC-01 (bloque 1), ADU-01 (bloque 1), UMI-02 (bloque 1), CAR-03 (bloque 1) |
| 3 | TCT-01 · COM-02 · HSQ-01 · ADU-04 · ZFR-01 (5) | TRC-05 (bloque 1), TRA-04 (bloque 1), ADU-01 (bloque 1), TIC-02 (bloque 2), ADU-02 (bloque 2), TRA-01 (bloque 2), ADM-01 (bloque 2) |
| 4 | TCT-02 · CAR-02 · ADM-02 · ADM-03 (4) | TRC-05 (bloque 1), TRA-04 (bloque 1), CED-02 (bloque 1), UMI-02 (bloque 1), ADM-04 (bloque 1), TIC-02 (bloque 2), TCT-01 (bloque 3), HSQ-01 (bloque 3), COM-02 (bloque 3) |
| 5 | TCT-03 · COM-03 (2) | TRC-05 (bloque 1), UMI-02 (bloque 1), TIC-02 (bloque 2), UMI-03 (bloque 2), TCT-02 (bloque 4) |
| 6 | TIC-03 · COM-01 · COM-04 (3) | DIR-03 (bloque 1), DIR-04 (bloque 1), ADU-03 (bloque 2), CED-01 (bloque 2), ADM-01 (bloque 2), COM-02 (bloque 3), TCT-03 (bloque 5) |

**El tronco común en el bloque 1 (DD-27).** TRC-01 va primero porque «Ningún documento de un cliente entra a una herramienta de IA antes de que TRC-01 esté aprobado» (`02`), y su entregable lo usan TRC-02 y HSQ-03. Sigue TRC-05, que el caso necesita desde la fase 2 (TIC-04) y del que dependen siete cursos. Después TRC-03, que se usa desde la fase 5 (CED-01, CED-04, TRA-01 y UMI-03). Al final TRC-04, que ningún laboratorio usa (TIC-03 solo lo nombra como contexto). TRC-02 no puede ir en el bloque 1: depende de TRC-01 y va en el bloque 2. Como ningún laboratorio usa su entregable, puede producirse en cualquier momento de ese bloque.

**Primer curso que se produce: LOG-TRC-01.** Está en las 26 rutas, no depende de nada y su política es la regla del caso para que cualquier documento de un cliente entre a una herramienta de IA.

**Si se descarta la dependencia inferida de DIR-02** (etapa 0 de DIR-02), DIR-02 pasa al bloque 1 y nada más cambia. La de COM-01 no cambia su bloque, porque DIR-03 está en el bloque 1.

## 3. Ciclos y cómo romperlos

Comprobación mecánica: el grafo de las dependencias de la sección 1 admite un orden completo de los 48 cursos, así que **no queda ningún ciclo activo**. Los dos ciclos que tenían las fichas originales se rompieron en A1 corrigiendo la frase (decisión 8 de la Auditoría): la parte que creaba el ciclo ya no la usa el laboratorio, y nadie tiene que producir material del caso para romperlos.

| Ciclo | Cursos | Cómo quedó roto | Propuesta si la etapa 0 lo reabre | Quién produce la parte que rompe el ciclo |
| --- | --- | --- | --- | --- |
| C1 | TCT-01 ↔ TCT-02 | H10: TCT-01 dice «el analista decide la acción y la comunicación al cliente, que seguirá el protocolo de TCT-02». El laboratorio de TCT-01 entrega el tablero y las alertas sin el protocolo. Orden: TCT-01 → TCT-02 | Si la etapa 0 de TCT-01 decide que su clase 3.1 necesita mensajes de excepción, producir primero, como material del caso, una versión provisional de los mensajes de un solo cliente, marcada «provisional hasta TCT-02», sin la skill ni el protocolo completo | Nadie por ahora. Si se reabre: el responsable del sector en A4 |
| C2 | TIC-02 ↔ COM-03 | H5: TIC-02 dice «TCT-01 y COM-03 van a necesitar consultar» y «cómo el asistente de COM-03 recibirá». El laboratorio de TIC-02 entrega el control de acceso con la cuenta prevista para el asistente. Orden: TIC-02 (bloque 2) antes de COM-03 (bloque 5) | Si la etapa 0 de TIC-02 necesita probar una sesión del asistente, producir como material del caso un cliente de prueba que simula una sesión verificada, sin construir el asistente | Nadie por ahora. Si se reabre: el responsable del sector en A4 |

Dos pares se nombran en las dos direcciones sin formar ciclo, porque una de las dos menciones es «lo usará después»: ADM-01 → COM-02 (ADM-01 dice «entregado a COM-02 para el pricing») y TIC-02 → TCT-01 (TIC-02 dice «TCT-01 y COM-03 van a necesitar consultar»).

## 4. Cuello de botella

**LOG-TRC-05** es el curso que más cursos detiene: 12 en total, 7 de forma directa (TIC-04, TCT-01, ADU-04, ZFR-01, CED-04, CAR-02, COM-03). Como está en el bloque 1 y no depende de nada, deja de ser un freno en cuanto se publica: por eso va segundo en el orden del sector, después de TRC-01.

| Curso | Bloque | Directos | Total detenidos |
| --- | --- | --- | --- |
| TRC-05 | 1 | 7 | 12 |
| DIR-03 | 1 | 4 | 10 |
| TIC-01 | 1 | 2 | 10 |
| TRA-04 | 1 | 2 | 9 |
| TRC-03 | 1 | 4 | 8 |
| TIC-02 | 2 | 3 | 8 |
| TCT-01 | 3 | 2 | 7 |
| UMI-02 | 1 | 3 | 7 |

**Cadena crítica.** La cadena más larga del sector tiene seis bloques seguidos: DIR-03 y TIC-01 → TIC-02 → TCT-01 → TCT-02 → TCT-03 → COM-01, COM-04 y TIC-03. TCT-03 necesita además UMI-02. Cualquier retraso en esta cadena retrasa las tres rutas que cierran en el bloque 6 y las dos del bloque 5. TIC-02 es el punto donde se estrecha: todo lo que viene después de la torre de control pasa por él.

## 5. Rutas que se pueden lanzar primero

Una ruta queda completa cuando están producidos sus cursos y todos los insumos que esos cursos usan en el laboratorio, aunque vengan de otras rutas. La secuencia es la de `03` corregido. Los insumos de otras rutas son los que el estudiante recibe como material del caso (Auditoría, sección 7).

| Ruta | Ola | Cursos | Bloque en que queda completa | Cursos a producir en total | Insumos de otras rutas | Nota comercial |
| --- | --- | --- | --- | --- | --- | --- |
| Jefe de bodega, analista de inventarios | Ola 3 | TRC-01, TRC-03, TRC-04 ; CED-03 → CED-02 | 1 | 5 | Ninguno | Sin prioridad comercial (PEND-22) |
| Operario de bodega | Ola 3 | TRC-01, TRC-03 ; CED-04 | 2 | 4 | TRC-05 | Sin prioridad comercial (PEND-22) |
| Auxiliar de entregas | Ola 3 | TRC-01, TRC-03 ; UMI-02 → UMI-03 | 2 | 4 | Ninguno | Sin prioridad comercial (PEND-22) |
| Gerente general | Ola 1 | TRC-01, TRC-02 ; DIR-01 → DIR-02 → DIR-04 | 2 | 5 | Ninguno | Sin prioridad comercial (PEND-22) |
| Especialista en clasificación, auxiliar de aduanas | Ola 3 | TRC-01, TRC-03 ; ADU-01 → ADU-02 → ADU-03 | 2 | 5 | Ninguno | Sin prioridad comercial (PEND-22) |
| Planeador de rutas, coordinador de flota | Ola 3 | TRC-01, TRC-02, TRC-04 ; TRA-01 → TRA-02 | 2 | 6 | TRC-03 | Sin prioridad comercial (PEND-22) |
| Coordinador de última milla | Ola 2 | TRC-01, TRC-02, TRC-04 ; UMI-01 → UMI-02 → UMI-03 | 2 | 7 | TRC-03 | Sin prioridad comercial (PEND-22) |
| Gerente de CEDI | Ola 2 | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; CED-01 → CED-02 → CED-03 | 2 | 8 | Ninguno | Sin prioridad comercial (PEND-22) |
| Jefe de transporte | Ola 2 | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; TRA-01 → TRA-02 → TRA-03 | 2 | 8 | Ninguno | Sin prioridad comercial (PEND-22) |
| Arquitecto, integrador EDI y APIs | Aliados técnicos | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; TIC-01 → TIC-04 → TIC-02 | 2 | 9 | DIR-03 | Sin prioridad comercial (PEND-22) |
| Conductor | Ola 3 | TRC-01, TRC-03 ; TRA-04 → HSQ-01 | 3 | 5 | TRA-01 | Sin prioridad comercial (PEND-22) |
| Director de aduanas | Ola 2 | TRC-01, TRC-03, TRC-05 ; ADU-01 → ADU-02 → ADU-04 | 3 | 6 | Ninguno | Sin prioridad comercial (PEND-22) |
| Líder de seguridad vial | Ola 3 | TRC-01, TRC-05 ; HSQ-01 → TRA-03 | 3 | 6 | TRC-03, TRA-01 | Sin prioridad comercial (PEND-22) |
| Gerente financiero | Ola 1 | TRC-01, TRC-02 ; DIR-02 → ADM-01 → COM-02 | 3 | 7 | DIR-01, UMI-02 | Sin prioridad comercial (PEND-22) |
| Gerente de zona franca | Ola 2 | TRC-01, TRC-03, TRC-05 ; ZFR-01 → ZFR-02 → ZFR-03 | 3 | 8 | ADU-01, ADU-02 | Sin prioridad comercial (PEND-22) |
| Coordinador HSEQ | Ola 2 | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; HSQ-03 → HSQ-01 → HSQ-02 | 3 | 9 | TRA-01 | Sin prioridad comercial (PEND-22) |
| Analista financiero, facturación | Ola 3 | TRC-01, TRC-02, TRC-04 ; ADM-01 → ADM-02 | 4 | 7 | UMI-02, COM-02 | Sin prioridad comercial (PEND-22) |
| Gestión humana y formación | Ola 2 | TRC-01, TRC-02, TRC-03 ; ADM-04 → ADM-03 | 4 | 9 | TRA-04, CED-02, TRA-01, HSQ-01 | Sin prioridad comercial (PEND-22) |
| Analista de monitoreo | Ola 3 | TRC-01, TRC-03, TRC-04 ; TCT-01 → TCT-02 | 4 | 10 | TRC-05, DIR-03, TIC-01, TRA-04, TIC-02 | Sin prioridad comercial (PEND-22) |
| Gerente de carga internacional | Ola 2 | TRC-01, TRC-02, TRC-04 ; CAR-03 → CAR-01 → CAR-02 | 4 | 12 | TRC-05, DIR-03, TIC-01, TRA-04, TIC-02, TCT-01 | Sin prioridad comercial (PEND-22) |
| Pricing, coordinador de operaciones internacionales | Ola 3 | TRC-01, TRC-02, TRC-04 ; CAR-01 → CAR-02 | 4 | 12 | TRC-05, DIR-03, TIC-01, TRA-04, CAR-03, TIC-02, TCT-01 | Sin prioridad comercial (PEND-22) |
| Gerente de operaciones | Ola 1 | TRC-01, TRC-02, TRC-04 ; DIR-03 → TCT-01 → TCT-03 | 5 | 12 | TRC-05, TIC-01, TRA-04, UMI-02, TIC-02, TCT-02 | Sin prioridad comercial (PEND-22) |
| Jefe de torre de control | Ola 2 | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; TCT-01 → TCT-02 → TCT-03 | 5 | 13 | DIR-03, TIC-01, TRA-04, UMI-02, TIC-02 | Sin prioridad comercial (PEND-22) |
| Analista de datos | Aliados técnicos | TRC-01, TRC-02, TRC-03, TRC-04, TRC-05 ; TCT-03 → TIC-03 | 6 | 14 | DIR-03, TIC-01, TRA-04, UMI-02, TIC-02, TCT-01, TCT-02 | Sin prioridad comercial (PEND-22) |
| Servicio al cliente, KAM | Ola 3 | TRC-01, TRC-02 ; COM-03 → COM-04 | 6 | 20 | TRC-03, TRC-05, DIR-03, DIR-04, TIC-01, TRA-04, ADU-01, UMI-02, TIC-02, ADU-03, UMI-03, ADM-01, TCT-01, COM-02, TCT-02, TCT-03 | Sin prioridad comercial (PEND-22) |
| Gerente comercial | Ola 2 | TRC-01, TRC-02, TRC-04 ; COM-01 → COM-02 → COM-04 | 6 | 21 | TRC-03, TRC-05, DIR-03, DIR-04, TIC-01, TRA-04, ADU-01, UMI-02, TIC-02, ADU-03, CED-01, ADM-01, TCT-01, TCT-02, TCT-03 | Sin prioridad comercial (PEND-22) |

**Las que se pueden lanzar primero.** Con el orden por bloques y sin prioridad comercial:

- **Bloque 1:** Jefe de bodega, analista de inventarios.
- **Bloque 2:** Operario de bodega; Auxiliar de entregas; Gerente general; Especialista en clasificación, auxiliar de aduanas; Planeador de rutas, coordinador de flota; Coordinador de última milla; Gerente de CEDI; Jefe de transporte; Arquitecto, integrador EDI y APIs.
- **Bloque 3:** Conductor; Director de aduanas; Líder de seguridad vial; Gerente financiero; Gerente de zona franca; Coordinador HSEQ.
- **Bloque 4:** Analista financiero, facturación; Gestión humana y formación; Analista de monitoreo; Gerente de carga internacional; Pricing, coordinador de operaciones internacionales.
- **Bloque 5:** Gerente de operaciones; Jefe de torre de control.
- **Bloque 6:** Analista de datos; Servicio al cliente, KAM; Gerente comercial.

La ruta del jefe de bodega es la única que queda completa en el bloque 1. En el bloque 2 se suman nueve rutas, entre ellas la del gerente general, la única de la ola 1 que no espera a otra ruta. Las del gerente comercial, el analista de datos y servicio al cliente cierran en el bloque 6, porque dependen de la cadena crítica.

**Si dirección del catálogo da prioridad a una ruta** (PEND-22), sus insumos de otras rutas son los de la columna «Insumos de otras rutas», y se adelantan dentro de su bloque sin cambiar de bloque. Para la ola 1 completa serían TRC-05, TIC-01, TRA-04, UMI-02, TIC-02 y TCT-02 (17 cursos, completa en el bloque 5); para el gerente general y el gerente financiero, solo UMI-02 (8 cursos, completa en el bloque 3).

## 6. Reparto inicial (si el sector tiene varias personas)

No consta cuántas personas producen el sector (DD-30), así que el reparto se propone por ramas, sin nombres. Cada rama construye solo sus entregables; lo que recibe de otra rama lo usa cuando ya está publicado, nunca en construcción. Con una sola persona, se sigue el orden de la sección 2.

| Rama | Cursos, en orden | Lo que recibe de otra rama | Por qué es independiente de las otras |
| --- | --- | --- | --- |
| Rama 1 · Gobierno, datos y torre (cadena crítica) | TRC-01 → TRC-05 → TRC-02 → HSQ-03 → DIR-03 → TIC-01 → TIC-02 → TIC-04 → TRA-04 → TCT-01 → TCT-02 → TCT-03 → TIC-03 → COM-03 | UMI-02 para TCT-03; UMI-03 para COM-03 | Ningún entregable de la rama lo construye otra rama; los que recibe se publican antes de que la rama los necesite |
| Rama 2 · CEDI, transporte y última milla | TRC-03 → UMI-02 → UMI-01 → UMI-03 → TRC-04 → CED-02 → CED-03 → CED-01 → CED-04 → TRA-01 → TRA-02 → TRA-03 → HSQ-01 → HSQ-02 → ADM-04 → ADM-03 | TRC-05 para CED-04; TRA-04 para ADM-03 | Ningún entregable de la rama lo construye otra rama; los que recibe se publican antes de que la rama los necesite |
| Rama 3 · Aduana, carga y negocio | ADU-01 → ADU-02 → ADU-03 → ADU-04 → ZFR-02 → ZFR-03 → ZFR-01 → CAR-03 → CAR-01 → CAR-02 → DIR-01 → DIR-02 → DIR-04 → ADM-01 → COM-02 → ADM-02 → COM-01 → COM-04 | TRC-05 para ADU-04, ZFR-01, CAR-02; DIR-03 para COM-01, COM-04; UMI-02 para ADM-01, ADM-02; TIC-02 para CAR-02; CED-01 para COM-01; TCT-01 para CAR-02; TCT-03 para COM-01, COM-04 | Ningún entregable de la rama lo construye otra rama; los que recibe se publican antes de que la rama los necesite |

La rama 1 lleva la cadena crítica y el primer curso del sector. TRC-03 y TRC-05 conviene publicarlos en las primeras semanas, porque las otras dos ramas los esperan.

## 7. Decisiones de A3

Presentadas en el paquete de aprobación del 2026-10-21. Aprobadas por Carolina Barraza el 2026-10-21, al aprobar el orden.

| ID | Decisión | Escalón | Fuente |
| --- | --- | --- | --- |
| DD-25 | Criterio de dependencia: datos del expediente o del programa, herramienta o fuente que «aporta», «Regla del curso» aplicada en el laboratorio o procedimiento que opera sobre el entregable. Son contexto CED-02 ← CED-01, UMI-02 ← UMI-01, COM-02 ← UMI-01 y UMI-02, TIC-03 ← TRC-04 y DIR-03 ← TRC-01 | 1 | Glosario, sección 4 · Auditoría, sección 7 |
| DD-26 | Las dependencias inferidas cuentan para el orden y se confirman en la etapa 0 del curso: DIR-02 ← DIR-01 y COM-01 ← DIR-03 | 4 | Regla de oro · Biblia, sección 6.2 · Auditoría, sección 7 |
| DD-27 | Orden del tronco común en el bloque 1: TRC-01 → TRC-05 → TRC-03 → TRC-04. TRC-02 va en el bloque 2 | 2 y 6 | `02` · fichas |
| DD-28 | ADU-04 depende de ADU-01 y ADU-02 en su laboratorio | 2 | H27 · LOG-ADU-04, clase 2.1 |
| DD-29 | Cierra PEND-21. No son dependencias citadas: TRC-03, TRC-04 y TRC-05 ← TRC-01; TIC-02 ← TIC-04; CED-02 ← CED-01; CED-03 ← CED-02; TRA-02 ← TRA-01; TRA-03 ← TRA-02; UMI-02 ← UMI-01; UMI-03 ← UMI-02; ZFR-02 ← ZFR-01; ZFR-03 ← ZFR-02; CAR-02 ← CAR-01. Siguen siendo orden de la historia o de la ruta. DIR-03 es insumo de TIC-02 y de TIC-04 | 2 | Fichas · Biblia, sección 6.2 |
| DD-30 | No consta cuántas personas producen el sector; el reparto se propone por ramas sin nombres | 6 | — |
| DD-31 | Dentro de cada bloque, salvo el tronco común del bloque 1, los cursos se ordenan por el número de cursos que liberan; en empate, por el orden del caso | 6 | Sin prioridad comercial (P-ronda 1) |
| P-ronda 1 | Ninguna ruta tiene prioridad comercial por ahora. Se consulta a dirección del catálogo (PEND-22) | 7 | Responsable del sector, 2026-10-21 |

## 8. Pendientes

| ID | Qué no consta o está abierto | Quién decide | Estado |
| --- | --- | --- | --- |
| PEND-21 | Qué filas de la Biblia, sección 6.2, son dependencias citadas | A3 | Cerrado por DD-29. La Biblia debe actualizar la columna «Va después de» |
| PEND-22 | Si alguna ruta debe salir antes por razones comerciales | Dirección del catálogo | Abierto. Mientras tanto, orden por bloques sin prioridad |
| PEND-23 | Confirmar la dependencia inferida DIR-02 ← DIR-01 | Etapa 0 de DIR-02 | Abierto |
| PEND-24 | Confirmar la dependencia inferida COM-01 ← DIR-03 | Etapa 0 de COM-01 | Abierto |

**Consulta para dirección del catálogo (PEND-22).**

```text
Tipo: promesa comercial.
Qué necesitamos decidir: si alguna ruta de Logística debe quedar lista antes de lo que da el orden de producción.
Por qué importa: si una ruta sale antes, hay que producir primero cursos de otras rutas que esa ruta usa como insumo.
Opciones:
  A) Ninguna: se produce por bloques. Primero queda lista la ruta del jefe de bodega (bloque 1) y después nueve rutas, entre ellas la del gerente general (bloque 2).
  B) Ola 1 completa: 17 cursos, lista en el bloque 5. Hay que producir antes TRC-05, TIC-01, TRA-04, UMI-02, TIC-02 y TCT-02.
  C) Ola 1 en dos tiempos: gerente general y gerente financiero, 8 cursos, listos en el bloque 3 (solo adelanta UMI-02); el gerente de operaciones, en el bloque 5.
  D) Otra ruta: se calculan sus insumos.
Recomendación del responsable del sector en A3: C, porque las olas dicen que primero se vende a Dirección y dos de sus tres rutas no esperan la cadena más larga del sector.
Si no responde: se mantiene A.
```

## 9. Comprobaciones mecánicas

- Cada curso aparece una sola vez en la tabla de bloques: 48 cursos, 48 distintos, en seis bloques (21, 13, 5, 4, 2, 3).
- Cada dependencia cita su frase: 54 dependencias de laboratorio, 6 de contexto y 4 de «lo usará después». Cada frase se buscó por script en su ficha corregida y está literal, sin las marcas de negrita. Cuando la frase es la explicación de una viñeta, se cita con la etiqueta de la viñeta, que nombra al curso.
- Ningún curso queda en un bloque anterior al de un insumo suyo, y el grafo admite un orden completo: no hay ciclos activos.
- Las 26 rutas de `03` corregido están en la sección 5, con las mismas secuencias.
- Cada curso está en una sola rama de la sección 6.

**No pude comprobar.** Las menciones a otro curso sin su código (por ejemplo, «el servidor MCP» sin decir TIC-02) solo se revisaron donde la ficha ya cita el curso o donde la Biblia o la Auditoría señalaban una relación; el inventario A0 tampoco las buscó. Las dos dependencias inferidas salen de esa revisión.
