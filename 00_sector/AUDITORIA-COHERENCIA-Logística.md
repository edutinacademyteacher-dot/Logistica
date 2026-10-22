# Auditoría de coherencia · Logística

| Campo | Valor |
| --- | --- |
| Sector | Logística |
| Inventario usado | `INVENTARIO-Logística.md` |
| Decisiones de la ronda de preguntas | Ver sección 5 |
| Revisada en AUDITOR | 2026-10-21 · `REVISION-AUDITORIA-COHERENCIA-Logística.md` y `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` |

## 1. Línea de tiempo del caso

Las semanas suponen que las fases 1 a 5 van seguidas (decisión 4) y se cuentan desde el inicio de la fase 1, igual que el «mes 5» (DD-7). Ya incluyen las fases corregidas en H1 a H4. Dentro de una fase, «→» indica una dependencia citada en una ficha o el orden de una ruta; los cursos separados por «·» no dependen entre sí.

| Momento | Qué pasa | Cursos, en el orden de la historia |
| --- | --- | --- |
| Fase 0 · Tronco común (antes de la semana 1; su duración no consta) | Se aprueba la política de IA y ningún documento de un cliente entra a una herramienta antes. Quedan el reporte semanal, la matriz de requisitos de los clientes, el análisis de un año del corredor y la matriz de riesgos. | TRC-01 → TRC-02 · TRC-03 · TRC-04 · TRC-05 |
| Fase 1 · Diagnóstico, caso y gobierno (semanas 1 a 6) | Diagnóstico con tres hallazgos. Hoja de ruta, caso de negocio del piloto y gobierno de los datos de clientes. | DIR-01 → DIR-02 · DIR-03 |
| Fase 2 · Datos e integraciones (semanas 7 a 14) | Integración con Cordillera y Andina, evaluación de seguridad y servidor MCP de solo lectura. | TIC-01 → TIC-04 → TIC-02 |
| Fase 3 · Torre de control y conductor conectado (semanas 15 a 22) | Aplicación del conductor, tablero de visibilidad con alertas y protocolo de excepciones. | TRA-04 → TCT-01 → TCT-02 |
| Fase 4 · Aduana y zona franca (semanas 23 a 34) | OEA, clasificación, expedientes, tratados, y operación e inventario de la zona franca. | ADU-01 → ADU-02 → ADU-04 · ADU-03; ADU-02 → ZFR-01 → ZFR-02 → ZFR-03 |
| Fase 5 · CEDI, transporte, última milla y nivel de servicio (semanas 35 a 50) | Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, ruteo, prueba de entrega, devoluciones, OTIF y modelo de datos. | CED-01 → CED-02 → CED-03 · CED-04; TRA-01 → TRA-02 → TRA-03; UMI-01 → UMI-02 → UMI-03; UMI-02 → TCT-03 → TIC-03 |
| Fase 6 · Carga, HSEQ y servicio (ventana que se abre en el mes 5 y no tiene fin) | Cotización, embarques, Incoterms, seguridad vial, cadena de frío, certificaciones y asistente de servicio. Cada curso ocurre cuando existen sus insumos. | CAR-03 → CAR-01 → CAR-02 (después de TCT-01) · HSQ-03 · HSQ-02 (desde el mes 5); HSQ-01 (después de TRA-01); COM-03 (después de UMI-03) |
| Fase 7 · Negocio y escala (continua; cada curso cuando existen sus insumos) | Costeo, facturación, soluciones, pricing, cuentas clave, formación, plan de cambio y nuevos servicios. | ADM-01 → COM-02 → ADM-02; DIR-04; ADM-01 y DIR-04 → COM-01; COM-02 y DIR-04 → COM-04; ADM-04 → ADM-03 (también después de HSQ-01) |

## 2. «Momento del caso» por ficha

Ninguna ficha tiene un campo de fase. La columna «¿Cambia?» compara con la tabla de fases de `02`.

| Código | Momento que declaraba la ficha | Momento que le corresponde | ¿Cambia? |
| --- | --- | --- | --- |
| TRC-01 | «Participan todos los roles antes de su primera fase del programa.» | Fase 0 · primer curso del tronco | No |
| TRC-02 | No consta | Fase 0 · después de TRC-01 | No |
| TRC-03 | No consta | Fase 0 · después de TRC-01 | No |
| TRC-04 | No consta | Fase 0 · después de TRC-01 | No |
| TRC-05 | No consta | Fase 0 · después de TRC-01 | No |
| DIR-01 | No consta | Fase 1 · primer curso | No |
| DIR-02 | No consta | Fase 1 · después de DIR-01 (inferido: valora el piloto que elige DIR-01) | No |
| DIR-03 | No consta | Fase 1 · sin dependencia dentro de la fase | No |
| ADM-03 | No consta | Fase 7 · después de ADM-04 y de HSQ-01 | Sí: de la fase 1 a la 7 (H4) |
| TIC-01 | No consta | Fase 2 · primer curso | No |
| TIC-04 | No consta | Fase 2 · después de TIC-01 | No |
| TIC-02 | No consta | Fase 2 · después de TIC-04 (orden de la ruta del arquitecto, H12); usa las integraciones de TIC-01 | No |
| TIC-03 | No consta | Fase 5 · después de TCT-03 | Sí: de la fase 2 a la 5 (H3) |
| TRA-04 | No consta | Fase 3 · antes de TCT-01 | Sí: de la fase 5 a la 3 (H1) |
| TCT-01 | No consta | Fase 3 · después de TRA-04 y de TIC-02 | No |
| TCT-02 | No consta | Fase 3 · después de TCT-01 | No |
| TCT-03 | No consta | Fase 5 · después de UMI-02 | Sí: de la fase 3 a la 5 (H2) |
| ADU-04 | No consta | Fase 4 · después de ADU-02 | No |
| ADU-01 | No consta | Fase 4 · primer curso | No |
| ADU-02 | No consta | Fase 4 · después de ADU-01 | No |
| ADU-03 | No consta | Fase 4 · después de ADU-01 | No |
| ZFR-01 | No consta | Fase 4 · después de ADU-02 | No |
| ZFR-02 | No consta | Fase 4 · después de ZFR-01 | No |
| ZFR-03 | No consta | Fase 4 · después de ZFR-02 | No |
| CED-01 | No consta | Fase 5 · primer curso de CEDI | No |
| CED-02 | No consta | Fase 5 · después de CED-01 | No |
| CED-03 | No consta | Fase 5 · después de CED-02 (orden de la ruta) | No |
| CED-04 | No consta | Fase 5 · sin dependencia dentro de la fase | No |
| TRA-01 | No consta | Fase 5 · primer curso de transporte | No |
| TRA-02 | No consta | Fase 5 · después de TRA-01 | No |
| TRA-03 | No consta | Fase 5 · después de TRA-02 | No |
| UMI-01 | No consta | Fase 5 · primer curso de última milla | No |
| UMI-02 | No consta | Fase 5 · después de UMI-01 | No |
| UMI-03 | No consta | Fase 5 · después de UMI-02 | No |
| CAR-03 | No consta | Fase 6 · desde el mes 5 · primer curso de carga | No |
| CAR-01 | No consta | Fase 6 · después de CAR-03 | No |
| CAR-02 | No consta | Fase 6 · después de CAR-01 y de TCT-01 | No |
| HSQ-03 | No consta | Fase 6 · desde el mes 5 | No |
| HSQ-02 | No consta | Fase 6 · desde el mes 5 | No |
| HSQ-01 | No consta | Fase 6 · después de TRA-01 | No |
| COM-03 | No consta | Fase 6 · después de UMI-03 y de TCT-02 | No |
| ADM-01 | No consta | Fase 7 · después de UMI-02 | No |
| COM-02 | No consta | Fase 7 · después de ADM-01 | No |
| ADM-02 | No consta | Fase 7 · después de COM-02 | No |
| DIR-04 | No consta | Fase 7 · sin dependencia | No |
| COM-01 | No consta | Fase 7 · después de ADM-01 y de DIR-04 | No |
| COM-04 | No consta | Fase 7 · después de COM-02 y de DIR-04 | No |
| ADM-04 | No consta | Fase 7 · sin dependencia | No |

## 3. Hallazgos

Estados finales: «Aplicada» con el archivo; «Rechazada» con la regla; «Etapa 0» con el curso; «Por aplicar» cuando la corrección está aprobada pero la versión de `01`, `02` o `03` que está en el Proyecto todavía no la tiene (comprobado el 2026-10-21).

| ID | Nivel | Hallazgo | Dónde (documento y frase exacta) | Corrección mínima propuesta | Estado final |
| --- | --- | --- | --- | --- | --- |
| H1 | Alta | TCT-01 (fase 3) usa en un laboratorio la aplicación de TRA-04, que el caso ubica en la fase 5. | `04` TCT-01, clase 1.1: «los registros de salida y llegada que los terceros hacen con la aplicación de TRA-04» · `02`, fila 5: «…predictivo, conductor, ruteo…» y «TRA-01 a TRA-04» | Decisión 5: TRA-04 pasa a la fase 3. En `02`, la fila 3 dice «Aplicación del conductor, visibilidad del corredor y protocolo de excepciones · TRA-04, TCT-01, TCT-02». La fila 5 quita «conductor» y dice «TRA-01 a TRA-03». Alternativa: mover TCT-01 a la fase 5, lo que dejaría la fase 3 sin torre de control. | Por aplicar · `02_caso_referencia`, tabla de fases |
| H2 | Alta | TCT-03 (fase 3) usa las pruebas de entrega de UMI-02 (fase 5). | `04` TCT-03, Datos del expediente: «pruebas de entrega de UMI-02» · clase 1.2: «con la hora de la prueba de entrega de UMI-02 y el GPS, el OTIF de Andina baja tres puntos» | TCT-03 pasa a la fase 5, después de UMI-02. En `02`, la fila 3 quita «y OTIF» (ver H1) y la fila 5 añade «OTIF» y «TCT-03». Alternativa: llevar UMI-01 y UMI-02 a la fase 3; mueve dos cursos y parte la última milla. | Por aplicar · `02_caso_referencia`, tabla de fases |
| H3 | Alta | TIC-03 (fase 2) usa las definiciones de OTIF de TCT-03 (fase 5 tras H2). | `04` TIC-03, Fuentes: «y las definiciones de OTIF de TCT-03» · clase 2.1: «una fórmula propia distinta de la de TCT-03» | TIC-03 pasa a la fase 5, después de TCT-03. En `02`, la fila 2 dice «Seguridad, integración con Cordillera y Andina y MCP · TIC-01, TIC-02, TIC-04». La fila 5 añade «modelo de datos» y «TIC-03». | Por aplicar · `02_caso_referencia`, tabla de fases |
| H4 | Alta | ADM-03 (fase 1) usa entregables de las fases 5, 6 y 7. | `04` ADM-03, Datos del programa: «Reglas de uso de datos de HSQ-01 y CED-02, aplicación del conductor de TRA-04 y módulos móviles de ADM-04.» · clase 2.2: «los módulos de ADM-04 en la inducción» | ADM-03 pasa a la fase 7, después de ADM-04 y de HSQ-01. En `02`, la fila 1 dice «Hoja de ruta, caso de negocio y gobierno de datos de clientes · DIR-01 a DIR-03». La fila 7 dice «…cuentas clave, formación, plan de cambio y nuevos servicios · ADM-01 a ADM-04, COM-01, COM-02, COM-04, DIR-04». Consecuencia: el caso no tiene plan de cambio hasta la fase 7. | Por aplicar · `02_caso_referencia`, tabla de fases |
| H5 | Alta | TIC-02 (fase 2) presenta como existente el asistente de servicio de COM-03 (fase 6). No se resuelve moviendo cursos, porque COM-03 usa el servidor de TIC-02 (decisión 8). | `04` TIC-02: «Lo usan la torre de control y el asistente de servicio.» · Resultado: «La torre de control y el asistente consultan en segundos lo que necesitan» · Contexto: «TCT-01 y COM-03 necesitan consultar» · clase 3.1, lectura: «cómo el asistente de COM-03 recibe» · clase 3.1, procedimiento: «que conectó el asistente de servicio con una cuenta con acceso a todos los clientes; cada sesión del asistente queda limitada al titular que se verificó» | «Lo usan la torre de control y lo usará el asistente de servicio.» · «La torre de control consulta en segundos lo que necesita, el servidor queda listo para el asistente de servicio, y…» · «TCT-01 y COM-03 van a necesitar consultar» · «cómo el asistente de COM-03 recibirá» · «que conectó la cuenta prevista para el asistente de servicio con acceso a todos los clientes; cada sesión del asistente quedará limitada al titular que se verifique» | Aplicada · LOG-TIC-02 |
| H6 | Alta | La hoja de ruta empieza por la torre de control y la aduana, pero en el caso las fases 3 y 4 van después de la fase 2 de datos e integraciones. | `04` DIR-01, Resultado: «La junta aprueba una hoja de ruta que empieza por la visibilidad del corredor y la aduana» | «La junta aprueba una hoja de ruta que empieza por los datos y las integraciones que necesitan la visibilidad del corredor y la aduana» | Aplicada · LOG-DIR-01 |
| H7 | Alta | El caso nombra cuatro clientes principales; TRC-03 dice cinco (decisión 7). | `04` TRC-03, Diseño: «El profesor trabaja con cinco clientes de TransAndes» · Unidad 3: «El proyecto se completa con la matriz de cinco clientes publicada.» · clase 3.2: «El profesor presenta la matriz de cinco clientes» | Cambiar «cinco» por «cuatro» en esas tres frases. No se tocan «cada participante con cinco de su empresa» ni la evidencia. | Aplicada · LOG-TRC-03 |
| H8 | Media | Con ADM-03 en la fase 7, su texto describe como futuro lo que ya existe. Depende de H4. | `04` ADM-03, Contexto: «Los operarios y conductores ven llegar la telemetría, los estándares de picking y la aplicación del conductor» · clase 1.1: «que usarán la aplicación de TRA-04 sin ser empleados» | «Los operarios y conductores ya trabajan con la telemetría, los estándares de picking y la aplicación del conductor» · «que usan la aplicación de TRA-04 sin ser empleados» | Aplicada · LOG-ADM-03 |
| H9 | Media | El contexto de TIC-03 contradice el OTIF unificado de TRC-02 (fase 0) y el tablero de TCT-03 (fase 5, anterior a TIC-03). | `04` TIC-03, Contexto: «Cada área de TransAndes tiene su hoja con su versión de los datos, y el informe mensual del comité toma una semana y termina en discusiones sobre qué cifra es la buena.» · TRC-02, Resultado: «con un OTIF que todos calculan igual» | «Fuera del reporte semanal y del tablero de OTIF, cada área de TransAndes mantiene su hoja con su versión de los datos, y el informe mensual…» | Aplicada · LOG-TIC-03 |
| H10 | Media | Ciclo dentro de la fase 3: TCT-02 usa la torre de TCT-01, y TCT-01 usa el protocolo de TCT-02 (decisión 8). | `04` TCT-01, clase 3.1: «el analista decide la acción y la comunicación con el protocolo de TCT-02» | «el analista decide la acción y la comunicación al cliente, que seguirá el protocolo de TCT-02» | Aplicada · LOG-TCT-01 |
| H11 | Media | La ruta pone ADM-03 antes de ADM-04, aunque ADM-03 usa ADM-04 (P14). | `03`: «Fase 1 · ADM-03 Gestión del cambio.» y «Fase 2 · ADM-04 Formación de operarios y conductores.» · `01`: «ADM-03 → ADM-04» | Intercambiar: «Fase 1 · ADM-04…» y «Fase 2 · ADM-03…» · en `01`, «ADM-04 → ADM-03» | Por aplicar · `03_rutas_por_rol` y `01_principios` |
| H12 | Media | La ruta pone TIC-04 antes de TIC-01, aunque TIC-04 inventaría las credenciales de las integraciones de TIC-01. | `03`: «Fase 1 · TIC-04…», «Fase 2 · TIC-01…» · `01`: «TIC-04 → TIC-01 → TIC-02» · `04` TIC-04, clase 1.1: «las credenciales de las integraciones con los clientes de TIC-01» | `03`: Fase 1 TIC-01, Fase 2 TIC-04, Fase 3 TIC-02 · `01`: «TIC-01 → TIC-04 → TIC-02» | Por aplicar · `03_rutas_por_rol` y `01_principios` |
| H13 | Media | La ruta pone TIC-03 antes de TCT-03, y su proyecto dice que el tablero de OTIF se construye sobre el modelo. Las fichas dicen lo contrario. | `03`: «Fase 1 · TIC-03…», «Fase 2 · TCT-03…» y «Une en un solo modelo los datos de almacén, transporte, aduana y facturación, y construye sobre él el tablero OTIF por cliente.» · `01`: «TIC-03 → TCT-03» | Intercambiar las fases · «Construye el tablero OTIF por cliente y une en un solo modelo los datos de almacén, transporte, aduana y facturación con esas definiciones.» · `01`: «TCT-03 → TIC-03» | Por aplicar · `03_rutas_por_rol` y `01_principios` |
| H14 | Media | La ruta pone CAR-01 antes de CAR-03, aunque CAR-01 usa la guía de CAR-03. | `03`: «Fase 1 · CAR-01…», «Fase 3 · CAR-03…» · `01`: «CAR-01 → CAR-02 → CAR-03» · `04` CAR-01: «Guía de Incoterms de CAR-03.» | `03`: Fase 1 CAR-03, Fase 2 CAR-01, Fase 3 CAR-02 · `01`: «CAR-03 → CAR-01 → CAR-02» | Por aplicar · `03_rutas_por_rol` y `01_principios` |
| H15 | Retirado | Pone a los aliados técnicos detrás de la torre de control, aunque los cursos de integraciones son de la fase 2 y TCT-01 los necesita (decisión 2). | `02`: «La torre de control abre la segunda ola, con los líderes de CEDI, transporte, aduanas, carga, zona franca, comercial y HSEQ, y dos aliados técnicos: integraciones y datos.» · `01`, diagrama: «B --> D[Aliados técnicos]» | `02`: «La torre de control abre la segunda ola, con los líderes de CEDI, transporte, aduanas, carga, zona franca, comercial y HSEQ. Los dos aliados técnicos, integraciones y datos, se forman cuando sus cursos ocurren en el programa.» · `01`: «A --> D[Aliados técnicos]» · **Retirado por HR9:** las olas ordenan a quién se le vende, no el orden de la historia (glosario, secciones 2 y 7.2). No se corrige. | Rechazada · glosario, secciones 2 y 7.2: las olas no fijan el momento de la historia (HR9, DD-1) |
| H16 | Retirado | «Piloto de 90 días» contradice la decisión 1: el piloto es el programa, y ninguna fase dura 90 días. | `01`, diagrama: «A[Ola 1<br/>Dirección · piloto 90 días]» | «A[Ola 1<br/>Dirección]» · **Retirado por HR9:** una duración del relato no es un límite de la línea de tiempo (regla R2). No se corrige. | Rechazada · regla R2: una duración del relato no limita la línea de tiempo (HR9, DD-1) |
| H17 | Media | Las fichas dan dos proporciones distintas de camiones de terceros, y ninguna consta en el caso. | `04` DIR-01, Contexto: «más de la mitad de los 400 camiones son de terceros sin integración» · DIR-01, clase 1.1: «más de la mitad de los camiones son de terceros sin integración» · DIR-02, Contexto: «la mitad de la flota son terceros a los que se paga por viaje» | Sin cifra hasta A2: «buena parte de los 400 camiones…», «buena parte de los camiones…», «buena parte de la flota son terceros…». Pendiente PEND-5. | Aplicada · LOG-DIR-01 y LOG-DIR-02 |
| H18 | Media | DIR-02 y su ruta dicen que el caso va a la junta, pero la evidencia, que no se cambia, dice comité financiero. | `03`: «Caso del piloto para la junta.» · `04` DIR-02, Objetivo general: «defiende el caso ante la junta» · clase 3.2, lectura: «Presentar a la junta.» | «Caso del piloto para el comité financiero.» · «defiende el caso ante el comité financiero» · «Presentar al comité financiero.» | Aplicada · LOG-DIR-02. Por aplicar · `03_rutas_por_rol` |
| H19 | Media | Formato móvil (P12 y C5): TRC-03 está en las rutas de operario, conductor y auxiliar, y no dice que se toma en el celular. | `04` TRC-03, Diseño: «12 h en 3 semanas, en 6 clases de 2 horas, con coordinadores de CEDI…» | «…en 6 clases de 2 horas, que operarios, conductores y auxiliares toman en el celular en bloques cortos, con coordinadores de CEDI…» | Aplicada · LOG-TRC-03 |
| H20 | Media | Lo mismo para HSQ-01, que está en la ruta del conductor. | `04` HSQ-01, Diseño: «12 h en 3 semanas, en 6 clases de 2 horas, con HSEQ…» | «…de 2 horas, que los conductores toman en el celular en bloques cortos, con HSEQ…» | Aplicada · LOG-HSQ-01 |
| H21 | Media | Lo mismo para UMI-03, que está en la ruta del auxiliar de entregas. | `04` UMI-03, Diseño: «8 h en 2 semanas, en 4 clases de 2 horas, con jefes de bodega…» | «…de 2 horas, que los auxiliares toman en el celular en bloques cortos, con jefes de bodega…» | Aplicada · LOG-UMI-03 |
| H22 | Retirado | «A todos» contradice 20 de las 26 rutas, que no llevan los cinco cursos del tronco. | `02`: «El tronco común (TRC-01 a TRC-05) se dicta a todos antes de su primera fase.» · `01`, P11: «Cinco cursos de base cuyos proyectos son la fase 0 de todas las rutas.» | `02`: «El tronco común se dicta antes de la primera fase de cada persona: TRC-01 a todos y los demás según la ruta de su rol.» · `01`: «Cinco cursos de base; cada ruta toma en su fase 0 los que su rol necesita, y TRC-01 está en todas.» · **Retirado por HR9:** el tronco común es suministro, no obligación (regla R1). No se corrige. | Rechazada · regla R1: el tronco común es suministro, no obligación (HR9, DD-1) |
| H23 | Media | Afirma una cadena que muchas rutas no cumplen. Por ejemplo, en HSQ-03 → HSQ-01 → HSQ-02 ningún curso usa el anterior. | `02`: «Está organizada por fases, y cada entregable que produce un curso es el insumo del siguiente en la ruta.» | «…y cada entregable que produce un curso queda como insumo de los cursos que lo usan después.» | Por aplicar · `02_caso_referencia` |
| H24 | Media | El diagrama del caso en `01` omite la fase 6 y llama a la fase 7 con otro nombre. | `01`: «E --> F[Nuevos servicios<br/>y clientes]» | Añadir «C --> G[Carga, HSEQ y servicio<br/>desde el mes 5]» y renombrar F como «Negocio<br/>y escala» | Por aplicar · `01_principios` |
| H25 | Media | Tres fichas hacen aprobar su entregable por la junta, pero en el caso la junta no consta: solo consta el comité del programa. | `04` DIR-01, DIR-03 y DIR-04: «aprobada por la junta» y «aprobado por la junta» · `02`: «Lo dirige un comité formado por el gerente general, el gerente de operaciones y el gerente financiero.» | Ninguna en la frase. DD-5: la Biblia registra una junta directiva, un comité financiero y un comité comercial, distintos del comité del programa. PEND-4 cerrado (HR8). | Sin cambio de texto · DD-5; la registra la Biblia (sección 11) |
| H26 | Baja | Lectura de UMI-02 que nombra un proceso que se construye después, en UMI-03. | `04` UMI-02, clase 2.1: «abrir la devolución de UMI-03» | «abrir la devolución» | Aplicada · LOG-UMI-02 |
| H27 | Media | ADU-04 necesita en su laboratorio el plan de ADU-01 y ADU-02, pero la ruta del director lo pone primero. | `04` ADU-04, clase 2.1: «queda como parcial con el plan de ADU-01 y ADU-02» · `03`: «Fase 1 · ADU-04 Operador Económico Autorizado.», «Fase 2 · ADU-01 Clasificación arancelaria asistida.», «Fase 3 · ADU-02 Declaraciones y documentación.» · `01`: «ADU-04 → ADU-01 → ADU-02» | En la fase 4, ADU-04 va después de ADU-02. En `03`: «Fase 1 · ADU-01 Clasificación arancelaria asistida. Propuestas con fundamento.», «Fase 2 · ADU-02 Declaraciones y documentación. Expedientes para su firma.», «Fase 3 · ADU-04 Operador Económico Autorizado. Requisitos con evidencia.» En `01`: «ADU-01 → ADU-02 → ADU-04». | Por aplicar · `03_rutas_por_rol` y `01_principios` |
| H28 | Baja | El ejemplo de P6 no existe: la ruta agrupa al especialista con el auxiliar, y ninguna ruta nombra al declarante. | `01`, P6: «como el especialista en clasificación arancelaria y el declarante; aquí aparecen por separado» | «como el especialista en clasificación arancelaria y el auxiliar de aduanas; aquí el especialista y el declarante aparecen por separado» | Por aplicar · `01_principios` |
| H29 | Media | Con H1 a H3, el nombre de la fase 3 no cubre la aplicación del conductor (TRA-04). El de la fase 5 no cubre el tablero de OTIF (TCT-03) ni el modelo de datos (TIC-03), que es la base de esa medición. | `02`, tabla de fases: «3. Torre de control» · «5. CEDI, transporte y última milla» | «3. Torre de control y conductor conectado» · «5. CEDI, transporte, última milla y nivel de servicio» | Por aplicar · `02_caso_referencia`, tabla de fases |
| H30 | Alta | COM-01 compromete un OTIF que no está demostrado: el 94% es la meta a 12 meses de `02`, no un resultado (P43, C7, regla y meta cero del propio curso). Sale de HR1. | `04` COM-01, clase 2.2: «TransAndes demuestra hoy entre 86% y 94%, y la oferta compromete 95% desde el cuarto mes con un plan de arranque» | «la oferta compromete el OTIF que TCT-03 demuestra para la operación, con un plan de arranque» (DD-2). La cifra se recrea como material del caso (R2) y la fija la etapa 0 de COM-01. | Aplicada · LOG-COM-01. Etapa 0 · COM-01: la cifra de OTIF que se compromete |
| H31 | Media | DIR-04 trata la logística farmacéutica como si TransAndes no guardara medicamentos, aunque CED-03, CED-04 y UMI-03, anteriores en la línea de tiempo, ya los guardan. Sale de HR2. | `04` DIR-04, Contexto: «la logística farmacéutica es una actividad regulada: exige habilitación sanitaria del almacén, un director técnico, cámaras con temperatura validada y un sistema de calidad.» | Después de «…y un sistema de calidad.» añadir: «TransAndes ya guarda medicamentos de Vitalia en un área habilitada, pero esa área no alcanza para el servicio nuevo.» (DD-3) | Aplicada · LOG-DIR-04 |
| H32 | Media | CAR-02 consulta por MCP los hitos de las navieras, pero el servidor de TIC-02 es «sobre el WMS, el TMS y el sistema aduanero», y las integraciones con navieras se aprueban en TCT-01. Sale de HR3. | `04` CAR-02, Herramientas: «el servidor de TIC-02 consulta los hitos que llegan de las integraciones con las navieras» | «el servidor de TIC-02 consulta en el TMS los hitos que llegan de las integraciones con las navieras aprobadas en TCT-01» (DD-4) | Aplicada · LOG-CAR-02 |
| H33 | Media | TIC-03 dice que no se pueden medir los tiempos por eslabón, aunque TRC-04 (fase 0) y TCT-03 (antes de TIC-03) ya los miden. Sale de HR4. | `04` TIC-03, Contexto: «Los sistemas guardan solo el estado actual de cada pedido, así que no se puede saber cuánto tardó en cada eslabón.» · clase 1.2: «con eso se miden los tiempos por eslabón que usa TCT-03» | «…así que cada análisis reconstruye por su cuenta cuánto tardó cada pedido en cada eslabón.» · «…y con eso se miden en un solo lugar los tiempos por eslabón que TRC-04 y TCT-03 calculaban por separado» | Aplicada · LOG-TIC-03 |
| H34 | Media | La tabla de componentes deja la clasificación al declarante, pero el especialista clasifica y el declarante firma (`02`, P4, P34, ADU-01). Sale de HR5. | `01` y `02`, tabla de componentes: «Expedientes completos y clasificación arancelaria asistida, con decisión del declarante» | «Expedientes completos para la firma del declarante y clasificación arancelaria asistida, con decisión del especialista», en `01` y en `02` | Por aplicar · `01_principios` y `02_caso_referencia` |
| H35 | Media | DIR-04 usa «piloto» para la prueba de un servicio nuevo. El glosario le da a «piloto» un solo sentido (sección 7.2). Sale de HR6. | `04` DIR-04, clase 4.1, lectura: «piloto con un cliente» · procedimiento: «antes del piloto con una línea de Vitalia» | «prueba con un cliente» · «antes de la prueba con una línea de Vitalia» | Aplicada · LOG-DIR-04 |

## 4. Causa común

Los hallazgos altos H1 a H4 vienen de la misma causa que en Tecnología. La tabla de fases de `02` reparte los cursos por departamento, y las fichas los encadenan por insumos. Cuando un departamento depende de otro que el caso pone después, la ficha cuenta la historia en otro momento.

Las rutas de H11 a H14 y H27 son la otra mitad de esa causa: ordenan los cursos para aprender, no según lo que cada curso usa.

La corrección de fondo deja la tabla de `02` así:

| Fase | Entregable principal | Cursos |
| --- | --- | --- |
| 1 | Hoja de ruta, caso de negocio y gobierno de datos de clientes | DIR-01 a DIR-03 |
| 2 | Seguridad, integración con Cordillera y Andina y MCP | TIC-01, TIC-02, TIC-04 |
| 3 | Aplicación del conductor, visibilidad del corredor y protocolo de excepciones | TRA-04, TCT-01, TCT-02 |
| 5 | Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, ruteo, prueba de entrega, devoluciones, OTIF y modelo de datos | CED-01 a CED-04, TRA-01 a TRA-03, UMI-01 a UMI-03, TCT-03, TIC-03 |
| 7 | Costeo, facturación, soluciones, pricing, cuentas clave, formación, plan de cambio y nuevos servicios | ADM-01 a ADM-04, COM-01, COM-02, COM-04, DIR-04 |

Las fases 4 y 6 no cambian. Las duraciones de las fases tampoco. Los nombres de las fases 3 y 5 cambian según H29.

La revisión de AUDITOR añadió H30 a H35, con otra causa: frases que contradicen un principio o un curso anterior en la línea de tiempo (H30 a H34) y un uso de «piloto» fuera del glosario (H35). También retiró H15, H16 y H22, que el glosario explica.

**Ciclos (nota para A3).** Los ciclos TCT-01 ↔ TCT-02 y TIC-02 ↔ COM-03 se rompen con H10 y H5 (decisión 8). No hace falta que nadie produzca la parte que rompe el ciclo. El orden de producción será TCT-01 → TCT-02 y TIC-02 antes de COM-03.

## 5. Decisiones de la ronda de preguntas

| Pregunta | Opciones | Decisión del responsable | Razón | Fecha |
| --- | --- | --- | --- | --- |
| 1. ¿Qué es «el piloto»? | Programa · ola de 90 días · solo glosario | «El piloto», sin calificativo, es el Programa Corredor Pacífico | Frase de `01`: «TransAndes Logística… digitaliza el corredor que va del puerto a sus clientes…» | 2026-10-20 |
| 2. ¿Las olas son tiempo del caso? | Formación · tiempo del caso | Las olas son orden de formación; el momento sale de las fases | No consta | 2026-10-20 |
| 3. ¿Qué significa «fase»? | Pasos · glosario · renombrar fases del programa | En la ruta, «fase» es el paso, que puede tener varios cursos; las de `02` se escriben «fase N del programa». Confirmado. | No consta | 2026-10-20 |
| 4. ¿Cómo se ordenan las fases? | Ventanas · tabla estricta · calendario estricto | Fases 1 a 5 seguidas; la 6 y la 7 son ventanas; el tronco es la fase 0 | No consta | 2026-10-20 |
| 5. ¿Ficha o caso, ante una dependencia posterior? | Corregir la ficha · mover el curso · caso por caso | Si un curso necesita el entregable de un curso posterior, se mueve: no se avanza a un curso sin todos sus recursos. Vale también dentro de una fase. | No se puede avanzar a un curso si no se tienen todos los recursos necesarios | 2026-10-20 |
| 6. ¿Qué hacer con rutas fuera del orden de la historia? | Reordenar si hay dependencia · no tocar · reordenar todas | Reordenar solo si hay dependencia invertida | No consta | 2026-10-20 |
| 7. ¿Cinco clientes en TRC-03? | Quinto cliente · cuatro · cliente de COM-01 | Cuatro, solo en las frases sobre TransAndes; la evidencia del estudiante no cambia. Confirmado. | No consta | 2026-10-20 |
| 8. ¿Cómo se rompen los ciclos TCT-01 ↔ TCT-02 y TIC-02 ↔ COM-03? | (a) Corregir la frase · (b) Material provisional del caso · (c) Pasar esa parte al curso posterior | (a) Corregir la frase para que el laboratorio no dependa del otro curso | Lo que entrega cada laboratorio, el tablero y el control de acceso, no depende del elemento que falta | 2026-10-20 |

**Nota de método (HR11).** La ronda tuvo ocho preguntas y el glosario, sección 9.2, fija como máximo tres en la etapa A. Las preguntas 1, 2 y 3 las resolvía el glosario y la 7 una frase de `02`. No cambia ninguna decisión, porque todas coinciden con el glosario. Queda como nota para el próximo sector.

### Decisiones derivadas y operativas de la revisión

Vienen de `REVISION-AUDITORIA-COHERENCIA-Logística.md` (2026-10-21), que las numera DD-1 a DD-8. La revisión `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` no numera decisiones nuevas: sus correcciones están en la sección 10. Ninguna de las dos revisiones hizo preguntas del escalón 7.

| ID | Decisión | Escalón | Tipo | Fuente |
| --- | --- | --- | --- | --- |
| DD-1 | Se retiran H15, H16 y H22: lo que señalan lo explican el glosario y sus reglas de lectura | 1 | Derivada | R1, R2 y glosario, secciones 2 y 7.2 |
| DD-2 | El OTIF que COM-01 compromete no puede superar el que demuestra la operación. La cifra se toma de TCT-03 como material del caso | 3 | Derivada | P43 y C7 |
| DD-3 | TransAndes ya tiene habilitación sanitaria en el área donde hoy guarda los medicamentos de Vitalia. El servicio nuevo de DIR-04 necesita habilitar otra área | 4 | Derivada | DIR-04, Contexto; CED-03, UMI-03 y CED-04 |
| DD-4 | Las integraciones con las navieras se aprueban en TCT-01, y sus hitos llegan al TMS que lee el servidor de TIC-02. Cierra PEND-7 | 2 y 4 | Derivada | TCT-01, clase 1.2; TIC-02, Proyecto ampliado |
| DD-5 | La Biblia registra una junta directiva, un comité financiero y un comité comercial, distintos del comité del programa. No cambia ningún texto (reversible). Cierra PEND-4 | 5 | Derivada, reversible | `02`, «El Programa Corredor Pacífico»; DIR-01 a DIR-04, COM-01 y COM-04 |
| DD-6 | La fase 7 es una ventana y cada curso ocurre cuando existen sus insumos. Cierra PEND-2 | 2 | Derivada | Decisión 4 de esta auditoría |
| DD-7 | El «mes 5» se cuenta desde el inicio de la fase 1, igual que las semanas de la sección 1 | 6 | Operativa | Sección 1 de esta auditoría |
| DD-8 | Los pendientes se escriben PEND-n | 6 | Operativa | Glosario, sección 7.1 |

## 6. Comprobaciones finales

- [x] Cada curso aparece una sola vez en la línea de tiempo: 48 cursos, 48 distintos, comprobado con un script.
- [ ] La fase de cada curso coincide en el caso, en la línea de tiempo y en su ficha: coincidirá cuando se apliquen H1 a H4 y se agregue el «Momento del caso» a las fichas.
- [ ] Ninguna ficha contradice un principio del sector: H19 a H21 y H30 están aplicados en las fichas; falta H34 en `01` y `02`. La revisión de AUDITOR encontró H30 (P43, C7) y H34 (P4, P34), que esta auditoría no había detectado.
- [ ] Todos los hallazgos altos tienen corrección aplicada: H5, H6, H7 y H30 están aplicados en las fichas; H1 a H4 faltan en `02`.

## 7. Observaciones que no son errores

- **«Torre de control» tiene dos sentidos.** Es un departamento que ya existe (`01` lo lista entre los 11 departamentos) y es el tablero que construye TCT-01 en la fase 3. Por eso TIC-02 puede conectar «un analista de la torre» en la fase 2. Va al glosario de A2.
- **Cifras de partida en cursos tardíos.** COM-03, TCT-03 y otras fichas citan las cifras de partida («60% de las llamadas», «86%»). El caso no da cifras intermedias, así que se mantienen como estado inicial hasta el curso que las mueve.
- **Rutas en orden distinto al de la historia, sin dependencia invertida.** Son CED-03 → CED-02, HSQ-03 → HSQ-01 → HSQ-02 y HSQ-01 → TRA-03. Por la decisión 6 no se tocan.
- **Insumos que la ruta no incluye.** El estudiante recibe como material del caso los insumos necesarios que su ruta no incluye; A3 lo registra. Para los del tronco común (TRC-03 y TRC-05) se aplica además la regla R1 (sección 9). La lista, ya con H11 a H14 y H27 aplicados (HR7):

| Ruta | Curso | Insumo que la ruta no incluye |
| --- | --- | --- |
| Gerente de operaciones | TCT-01 · TCT-03 | TIC-02, TRA-04, TRC-05 · UMI-02, TCT-02 |
| Gerente financiero | ADM-01 | UMI-02 |
| Jefe de torre de control | TCT-01 · TCT-03 | TIC-02, TRA-04 · UMI-02 |
| Coordinador de última milla | UMI-03 | TRC-03 |
| Gerente de carga internacional | CAR-02 | TIC-02, TCT-01, TRC-05 |
| Gerente de zona franca | ZFR-01 | ADU-02 |
| Gerente comercial | COM-01 · COM-04 | ADM-01, DIR-04, CED-01, TCT-03 · TCT-03, ADU-03, DIR-03, DIR-04 |
| Coordinador HSEQ | HSQ-01 | TRA-01 |
| Gestión humana y formación | ADM-03 | TRA-04, HSQ-01, CED-02 |
| Arquitecto, integrador | TIC-02 · TIC-04 | DIR-03 |
| Analista de datos | TCT-03 | UMI-02, TCT-02 |
| Operario de bodega | CED-04 | TRC-05 |
| Planeador, coordinador de flota | TRA-01 | TRC-03 |
| Conductor | HSQ-01 | TRA-01 |
| Analista de monitoreo | TCT-01 | TIC-02, TRA-04, TRC-05 |
| Pricing, coordinador internacional | CAR-01 · CAR-02 | CAR-03 · TIC-02, TCT-01, TRC-05 |
| Servicio al cliente, KAM | COM-03 · COM-04 | TIC-02, TCT-02, UMI-03, TRC-05 · COM-02, TCT-03, ADU-03, DIR-03, DIR-04 |
| Analista financiero, facturación | ADM-01 · ADM-02 | UMI-02 · COM-02, UMI-02 |
| Líder de seguridad vial | HSQ-01 | TRA-01 |

  No están en la lista las menciones que no entran al laboratorio, como «que se corrigen con UMI-01 y UMI-02» (COM-02), «ubicaciones de CED-01» (CED-02) o «vuelven al ruteo de UMI-01» (UMI-02): según el glosario, sección 4, son insumos de contexto.
- **«El piloto de su empresa».** En las réplicas de DIR-01 y DIR-02 es el mismo sentido, el proyecto piloto, aplicado a la empresa del participante. Los dos usos de DIR-04 sí son hallazgo (H35).
- **Datos de Vitalia en COM-01.** COM-01 usa el caso de Vitalia «anonimizado y con la autorización de Vitalia». P5 dice «nunca», pero DIR-03 fija la regla de consentimiento y COM-01 la cumple.
- **Revisión del director de aduanas.** Que el director revise las clasificaciones (evidencia de ADU-01) no contradice que el especialista decida y el declarante firme.
- **HSQ-02 y las alertas de la torre.** El contexto de HSQ-02 habla del análisis de registros después del viaje, que las alertas de TCT-01 no cubren.
- **Dos límites distintos en el glosario.** La sección 5 dice que la ronda de preguntas tiene «como máximo siete» y la sección 9.2, «como máximo tres» en la etapa A. HR11 aplica la 9.2, que es la regla específica de la etapa A.
- **Criterio de «necesario» (decisión 5).** Un entregable es necesario cuando entra al procedimiento del profesor, a la actividad del estudiante o a la evidencia. Si solo se nombra en una lectura o en el contexto, no lo es. Por ejemplo, DIR-01 menciona el asistente de servicio como un caso de uso que vendrá después.

## 8. Pendientes (No consta)

| ID | Qué no consta | Documentos | Estado |
| --- | --- | --- | --- |
| PEND-1 | Fecha de inicio del programa y duración de la fase 0 | `02` | Abierto. El «mes 5» se cuenta desde el inicio de la fase 1 (DD-7) |
| PEND-2 | Inicio de la fase 7 | `02` | Cerrado por DD-6 |
| PEND-3 | A qué comité se refieren las fichas que dicen «el comité» sin calificativo (TRC-02, TRC-04, TIC-03) | `04` | Abierto. Lo resuelve A2 al nombrar los órganos (escalón 6) |
| PEND-4 | Si TransAndes tiene una junta | `02`, `04` | Cerrado por DD-5 |
| PEND-5 | Proporción de camiones propios y de terceros | `02`, `04` | Abierto. Lo fija A2 (escalón 6) |
| PEND-6 | Si el «CEDI 2» y el «CEDI principal» son el mismo | `04` | Abierto. Lo fija A2 al numerar los CEDI (escalón 6) |
| PEND-7 | Con qué se integran las navieras de las que CAR-02 toma hitos | `04` | Cerrado por DD-4 |

## 9. Lo que queda para la etapa 0 de cada curso

- **COM-01:** la cifra de OTIF que la clase 2.2 enseña a comprometer (H30, DD-2).
- **CED-04, TCT-01, CAR-02, COM-03, TRA-01 y UMI-03:** usan un entregable del tronco común que la ruta de algún participante no incluye (regla R1). Su etapa 0 decide si el curso lo explica en la clase de configuración o en una clase A.

## 10. Revisión de AUDITOR (2026-10-21)

| ID | Nivel | Tipo | Hallazgo de la revisión | Archivo de la revisión | Estado final |
| --- | --- | --- | --- | --- | --- |
| HR1 | Alta | Coherencia | COM-01 compromete un OTIF que no está demostrado | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada como H30 · LOG-COM-01. Etapa 0 · COM-01: la cifra de OTIF |
| HR2 | Media | Coherencia | DIR-04 trata la logística farmacéutica como si TransAndes no guardara medicamentos | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada como H31 · LOG-DIR-04 |
| HR3 | Media | Coherencia | CAR-02 consulta por MCP datos que el servidor de TIC-02 no cubre | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada como H32 · LOG-CAR-02. Cierra PEND-7 (DD-4) |
| HR4 | Media | Coherencia | TIC-03 dice que no se pueden medir los tiempos por eslabón | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada como H33 · LOG-TIC-03 |
| HR5 | Media | Coherencia | `01` y `02` dejan la clasificación al declarante | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | H34 · Por aplicar · `01_principios` y `02_caso_referencia` |
| HR6 | Media | Contenido | La auditoría acepta un uso de «piloto» que el glosario no admite | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada como H35 · LOG-DIR-04, y en esta auditoría, sección 7 |
| HR7 | Media | Coherencia | La lista de insumos que la ruta no incluye está incompleta | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, sección 7. Etapa 0 · CED-04, TCT-01, CAR-02, COM-03, TRA-01 y UMI-03 (sección 9) |
| HR8 | Media | Coherencia | La auditoría trata distinto a la junta y a los demás comités | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, H25 y DD-5. PEND-4 cerrado |
| HR9 | Media | Contenido | Tres hallazgos de la auditoría van contra el glosario | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría: H15, H16 y H22 rechazados (DD-1) |
| HR10 | Baja | Formato | Nombre de los pendientes | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría: PEND-1 a PEND-7 (DD-8) |
| HR11 | Baja | Método | La ronda de preguntas excede el máximo | `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, sección 5: nota de método |
| HR12 | Media | Coherencia | La auditoría dice que DIR-04 no está en el Proyecto, pero sí está | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · LOG-DIR-04 (H31 y H35) y esta auditoría, sección 10: se borró el párrafo «Falta una ficha» |
| HR13 | Media | Coherencia | H32 crea una dependencia de CAR-02 con TCT-01 que la línea de tiempo no registra | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, secciones 1, 2 y 7 |
| HR14 | Media | Coherencia | El encabezado da por resueltos hallazgos que siguen abiertos | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, encabezado. En la versión de cierre, «Revisada en AUDITOR» lleva la fecha y los archivos de la revisión, y el estado de cada hallazgo está en las secciones 3 y 10 |
| HR15 | Baja | Formato | Nombre del archivo duplicado | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Aplicada · esta auditoría, sección 10. `LOG-TRA-03(1).md` ya no está en el Proyecto |
| HR16 | Baja | Contenido | La comprobación de principios cuenta H34 como pendiente, pero no H31 | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Rechazada · la propia revisión indica que no cambia nada |

**Lo que las revisiones no pudieron comprobar y ahora consta:**
- Las diez fichas corregidas con H1 a H29 que están en el Proyecto son idénticas, byte a byte, a las que entregué. Esas diez se compararon palabra por palabra con su texto en `04_fichas_cursos.md` al corregirlas: solo cambian las frases de los hallazgos. Las otras 38 no se pueden comparar, porque `04_fichas_cursos.md` ya no está en el Proyecto.
- `LOG-TRA-03.md` y `LOG-TRA-03(1).md` son idénticos byte a byte. En la copia de trabajo, `LOG-TRA-03(1).md` aparece como `LOG-TRA-03_1_.md`. Se puede borrar `LOG-TRA-03(1).md` del Proyecto.

## 11. Para la Biblia

Lo que A2 debe registrar en `10_biblia_caso`. Mientras las correcciones de `01`, `02` y `03` estén «Por aplicar», la Biblia toma la tabla de fases y el orden de los cursos de esta auditoría, no de la versión actual de esos documentos.

### 11.1 Decisiones que afectan el caso

| Tema | Lo que queda en el caso | Fuente |
| --- | --- | --- |
| El piloto | «El piloto», sin calificativo, es el Programa Corredor Pacífico: TransAndes Logística digitaliza el corredor que va del puerto a sus clientes, pasando por aduana, zona franca, CEDI y última milla. La prueba de un servicio nuevo se llama «prueba», nunca «piloto». | Decisión 1 · H35 · glosario, sección 7.2 |
| Quién dirige | El comité del programa, formado por el gerente general, el gerente de operaciones y el gerente financiero. Existen además una junta directiva, un comité financiero y un comité comercial, distintos del comité del programa. El caso de negocio del piloto (DIR-02) lo aprueba el comité financiero. | `02` · DD-5 · H18 |
| Clientes principales | Cuatro: Alimentos Cordillera, Vitalia, Distribuidora Andina y Altiplano Sur. | `02` · decisión 7 · H7 |
| Fases del programa | Fase 0 · Tronco común (TRC-01 a TRC-05). Fase 1 · Diagnóstico, caso y gobierno: hoja de ruta, caso de negocio y gobierno de datos de clientes (DIR-01 a DIR-03). Fase 2 · Datos e integraciones: seguridad, integración con Cordillera y Andina y MCP (TIC-01, TIC-02, TIC-04). Fase 3 · Torre de control y conductor conectado: aplicación del conductor, visibilidad del corredor y protocolo de excepciones (TRA-04, TCT-01, TCT-02). Fase 4 · Aduana y zona franca: OEA, clasificación, expedientes, tratados, operación e inventario de zona franca (ADU-01 a ADU-04, ZFR-01 a ZFR-03). Fase 5 · CEDI, transporte, última milla y nivel de servicio: slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, ruteo, prueba de entrega, devoluciones, OTIF y modelo de datos (CED-01 a CED-04, TRA-01 a TRA-03, UMI-01 a UMI-03, TCT-03, TIC-03). Fase 6 · Carga, HSEQ y servicio: cotización, embarques, Incoterms, seguridad vial, cadena de frío, certificaciones y asistente de servicio (CAR-01 a CAR-03, HSQ-01 a HSQ-03, COM-03). Fase 7 · Negocio y escala: costeo, facturación, soluciones, pricing, cuentas clave, formación, plan de cambio y nuevos servicios (ADM-01 a ADM-04, COM-01, COM-02, COM-04, DIR-04). | `02` · H1 a H4 · H29 · sección 4 |
| Calendario | La fase 0 ocurre antes de la semana 1. Las fases 1 a 5 van seguidas: semanas 1 a 6, 7 a 14, 15 a 22, 23 a 34 y 35 a 50. La fase 6 es una ventana que se abre en el mes 5, contado desde el inicio de la fase 1. La fase 7 es una ventana continua. En las fases 6 y 7, cada curso ocurre cuando existen sus insumos. | Decisión 4 · DD-6 · DD-7 · sección 1 |
| Momento de cada curso | El de la sección 2, en el orden de la sección 1. | Secciones 1 y 2 |
| Regla de dependencias | Ningún curso ocurre antes de que existan todos los entregables que usa en su laboratorio, su actividad o su evidencia. Los ciclos TCT-01 ↔ TCT-02 y TIC-02 ↔ COM-03 se rompen corrigiendo la frase: TCT-01 va antes de TCT-02, y TIC-02 antes de COM-03. | Decisiones 5 y 8 · H5 · H10 |
| Olas | Ordenan a quién se forma y se vende primero. No fijan el momento de ningún curso en la historia. | Decisión 2 · glosario, secciones 2 y 7.2 |
| Tronco común | Sus entregables existen en el caso desde el inicio de la fase 1. Cada participante hace solo los cursos del tronco que pide su ruta; TRC-01 está en todas. | Decisión 4 · regla R1 |
| Plan de cambio | Ocurre en la fase 7 (ADM-03), cuando los operarios y conductores ya trabajan con la telemetría, los estándares de picking y la aplicación del conductor. | H4 · H8 |
| Aduana | El especialista clasifica y decide la clasificación definitiva; el declarante firma. | `02`, tabla de 2027 · H34 |
| Integraciones con navieras | Se aprueban en TCT-01; sus hitos llegan al TMS, que lee el servidor MCP de TIC-02. | DD-4 · H32 |
| Asistente de servicio | Existe desde COM-03, en la fase 6. TIC-02, en la fase 2, deja el servidor listo para él. | H5 |
| Habilitación sanitaria | TransAndes ya guarda medicamentos de Vitalia en un área habilitada. El servicio nuevo de logística farmacéutica de DIR-04 necesita habilitar otra área. | DD-3 · H31 |
| Compromisos de servicio | Ninguna oferta compromete un OTIF mayor que el que demuestra la operación (TCT-03). | DD-2 · H30 |
| Datos de un cliente para otro | Los casos de otros clientes se presentan solo anonimizados y con su consentimiento. | Sección 7 · COM-01 · DIR-03 |

### 11.2 Cifras y su lectura

| Cifra | Valor | Lectura | Fuente |
| --- | --- | --- | --- |
| OTIF del corredor | 86% hoy · meta 94% a 12 meses | 86% es la situación al inicio del programa. 94% es una meta de diseño, no un resultado demostrado. | `02` · C7 · DD-2 |
| Excepciones detectadas antes que el cliente | 30% · meta 80% | Situación al inicio · meta de diseño | `02` |
| Tiempo de nacionalización | 4 días · meta 2 días | Situación al inicio · meta de diseño | `02` |
| Declaraciones con correcciones | 9% · meta 3% | Situación al inicio · meta de diseño | `02` |
| Exactitud de inventario en los CEDI | 94% · meta 99% | Situación al inicio · meta de diseño | `02` |
| Productividad de picking | Sin estándar · meta +15% a +25% sobre la línea base | Situación al inicio · meta de diseño | `02` |
| Kilómetros en vacío | 28% · meta 18% a 20% | Situación al inicio · meta de diseño | `02` |
| Entregas a tenderos con novedad | 12% · meta 6% | Situación al inicio · meta de diseño | `02` |
| Llamadas al servicio al cliente preguntando por un pedido | 60% del total | Situación al inicio | `02` |
| Consultas de pedidos resueltas por el asistente | Ninguna · meta 50% a 70% | Situación al inicio · meta de diseño | `02` |
| Accidentes viales | Línea base del año · meta −30% | Meta de diseño | `02` |
| Documentos de clientes fuera de herramientas aprobadas | Frecuente · meta cero | Situación al inicio · meta | `02` |
| Flota | 400 camiones propios y de terceros | La proporción entre propios y terceros no consta; las fichas no dan cifra (H17) | `02` · PEND-5 |
| CEDI | Tres | La relación entre «CEDI principal» y «CEDI 2» no consta | `02` · PEND-6 |
| Clientes principales | Cuatro | Ver 11.1 | `02` · decisión 7 |
| Duración de las fases | 6, 8, 8, 12 y 16 semanas; la fase 6 desde el mes 5; la fase 7 continua | Ver «Calendario» en 11.1 | `02` · DD-7 |
| «Piloto de 90 días» | Diagrama de olas de `01` | Duración del relato: es contexto, no un límite de la línea de tiempo | Regla R2 · H16 |

**Cómo se leen todas las cifras de la tabla:**
- Las cifras «hoy» describen el inicio del programa y se mantienen en las fichas hasta el curso que las mueve.
- El caso no da valores intermedios. Cuando un curso los necesita, se recrean como material del caso y se marcan así (regla R2).

### 11.3 Términos propios del sector

| Término | Sentido en este sector | Fuente |
| --- | --- | --- |
| Programa Corredor Pacífico | El proyecto piloto del sector. Ver 11.1 | `02` · decisión 1 |
| Fase del programa | Una de las fases 0 a 7 de 11.1. Se escribe «fase N del programa» | Decisión 3 |
| Fase de una ruta | El paso de una ruta. Puede tener uno o varios cursos; la fase 0 es el tronco común | Decisión 3 · `03` |
| Torre de control | Dos sentidos: el departamento que ya existe antes del programa, y el tablero con alertas que construye TCT-01 en la fase 3 | Sección 7 · `01` |
| Prueba | La prueba de un servicio o sistema dentro del caso (por ejemplo, con una línea de Vitalia) | H35 · glosario, sección 7.2 |
| Comité del programa | Gerente general, gerente de operaciones y gerente financiero; dirige el piloto | `02` |
| Junta directiva, comité financiero, comité comercial | Órganos distintos del comité del programa | DD-5 |
| «El comité», sin calificativo | No consta a cuál se refiere | PEND-3 |
| CEDI principal, CEDI 2 | No consta si son el mismo | PEND-6 |
| OTIF | Entregas completas y a tiempo del corredor | `02` |

### 11.4 Pendientes que siguen abiertos

| ID | Qué no consta | Quién lo resuelve |
| --- | --- | --- |
| PEND-1 | Fecha de inicio del programa y duración de la fase 0 | A2 |
| PEND-3 | A qué comité se refieren TRC-02, TRC-04 y TIC-03 cuando dicen «el comité» | A2, al nombrar los órganos (escalón 6) |
| PEND-5 | Proporción de camiones propios y de terceros | A2 (escalón 6) |
| PEND-6 | Si el «CEDI 2» y el «CEDI principal» son el mismo | A2, al numerar los CEDI (escalón 6) |
