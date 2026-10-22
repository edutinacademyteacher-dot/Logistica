# Registro de cambios · Logística

| Campo | Valor |
| --- | --- |
| Sector | Logística |
| Etapa | A1 · Auditoría de coherencia |
| Fecha de cierre del registro | 2026-10-21 |
| Fuente de cada cambio | `AUDITORIA-COHERENCIA-Logística.md`, versión de cierre (hallazgos H1 a H35 y HR1 a HR16) |
| Cómo se comprobó | Cada archivo final se comparó con su original: el original contiene cada frase «Antes», el final contiene cada frase «Después», y al aplicar solo esas sustituciones al original se obtiene exactamente el archivo final |

Las empresas y los datos del caso son ficticios.

## 1. Resumen por archivo

| Archivo | Cambios | Hallazgos | Estado |
| --- | --- | --- | --- |
| `02_caso_referencia.md` | 7 | H1, H2, H3, H4, H23, H29, H34 | Versión final en el Proyecto |
| `01_principios.md` | 8 | H11, H12, H13, H14, H24, H27, H28, H34 | Versión final en el Proyecto |
| `03_rutas_por_rol.md` | 7 | H11, H12, H13, H14, H18, H27 | Versión final en el Proyecto |
| `LOG-TRC-03.md` | 4 | H7, H19 | Versión final en el Proyecto |
| `LOG-DIR-01.md` | 3 | H6, H17 | Versión final en el Proyecto |
| `LOG-DIR-02.md` | 3 | H17, H18 | Versión final en el Proyecto |
| `LOG-DIR-04.md` | 3 | H31, H35 | Versión final en el Proyecto |
| `LOG-TIC-02.md` | 5 | H5 | Versión final en el Proyecto |
| `LOG-TIC-03.md` | 3 | H9, H33 | Versión final en el Proyecto |
| `LOG-TCT-01.md` | 1 | H10 | Versión final en el Proyecto |
| `LOG-UMI-02.md` | 1 | H26 | Versión final en el Proyecto |
| `LOG-UMI-03.md` | 1 | H21 | Versión final en el Proyecto |
| `LOG-HSQ-01.md` | 1 | H20 | Versión final en el Proyecto |
| `LOG-ADM-03.md` | 2 | H8 | Versión final en el Proyecto |
| `LOG-COM-01.md` | 1 | H30 | Versión final en el Proyecto |
| `LOG-CAR-02.md` | 1 | H32 | Versión final en el Proyecto |

## 2. Cambios en detalle

### `02_caso_referencia.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H34 | Tabla de componentes, fila «Aduana ágil» | «Expedientes completos y clasificación arancelaria asistida, con decisión del declarante» | «Expedientes completos para la firma del declarante y clasificación arancelaria asistida, con decisión del especialista» |
| H4 | Tabla de fases, fila 1 | «Hoja de ruta, caso de negocio, gobierno de datos de clientes y plan de cambio \| DIR-01 a DIR-03, ADM-03» | «Hoja de ruta, caso de negocio y gobierno de datos de clientes \| DIR-01 a DIR-03» |
| H3 | Tabla de fases, fila 2 | «Seguridad, integración con Cordillera y Andina, MCP y modelo de datos \| TIC-01 a TIC-04» | «Seguridad, integración con Cordillera y Andina y MCP \| TIC-01, TIC-02, TIC-04» |
| H1, H2 y H29 | Tabla de fases, fila 3 | «3. Torre de control \| 8 semanas \| Visibilidad del corredor, protocolo de excepciones y OTIF \| TCT-01 a TCT-03» | «3. Torre de control y conductor conectado \| 8 semanas \| Aplicación del conductor, visibilidad del corredor y protocolo de excepciones \| TRA-04, TCT-01, TCT-02» |
| H1, H2, H3 y H29 | Tabla de fases, fila 5 | «5. CEDI, transporte y última milla \| 16 semanas \| Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, conductor, ruteo, prueba de entrega y devoluciones \| CED-01 a CED-04, TRA-01 a TRA-04, UMI-01 a UMI-03» | «5. CEDI, transporte, última milla y nivel de servicio \| 16 semanas \| Slotting, picking, inventario, asistente de bodega, rutas, flota, predictivo, ruteo, prueba de entrega, devoluciones, OTIF y modelo de datos \| CED-01 a CED-04, TRA-01 a TRA-03, UMI-01 a UMI-03, TCT-03, TIC-03» |
| H4 | Tabla de fases, fila 7 | «cuentas clave, formación y nuevos servicios \| ADM-01, ADM-02, ADM-04, COM-01, COM-02, COM-04, DIR-04» | «cuentas clave, formación, plan de cambio y nuevos servicios \| ADM-01 a ADM-04, COM-01, COM-02, COM-04, DIR-04» |
| H23 | «El expediente de referencia» | «cada entregable que produce un curso es el insumo del siguiente en la ruta.» | «cada entregable que produce un curso queda como insumo de los cursos que lo usan después.» |

### `01_principios.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H28 | P6 | «como el especialista en clasificación arancelaria y el declarante; aquí aparecen por separado» | «como el especialista en clasificación arancelaria y el auxiliar de aduanas; aquí el especialista y el declarante aparecen por separado» |
| H34 | Tabla de componentes, fila «Aduana ágil» | «Expedientes completos y clasificación arancelaria asistida, con decisión del declarante» | «Expedientes completos para la firma del declarante y clasificación arancelaria asistida, con decisión del especialista» |
| H24 | Diagrama del caso | `E --> F[Nuevos servicios<br/>y clientes]` | `E --> F[Negocio<br/>y escala]` · `C --> G[Carga, HSEQ y servicio<br/>desde el mes 5]` |
| H27 | Tabla de rutas, director de aduanas | «ADU-04 → ADU-01 → ADU-02» | «ADU-01 → ADU-02 → ADU-04» |
| H14 | Tabla de rutas, gerente de carga internacional | «CAR-01 → CAR-02 → CAR-03» | «CAR-03 → CAR-01 → CAR-02» |
| H11 | Tabla de rutas, gestión humana y formación | «ADM-03 → ADM-04» | «ADM-04 → ADM-03» |
| H12 | Tabla de rutas, arquitecto | «TIC-04 → TIC-01 → TIC-02» | «TIC-01 → TIC-04 → TIC-02» |
| H13 | Tabla de rutas, analista de datos | «TIC-03 → TCT-03» | «TCT-03 → TIC-03» |

### `03_rutas_por_rol.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H18 | Ruta del gerente general, fase 2 | «Caso del piloto para la junta.» | «Caso del piloto para el comité financiero.» |
| H27 | Ruta del director de aduanas | «Fase 1 · ADU-04 … · Fase 2 · ADU-01 … · Fase 3 · ADU-02 …» | «Fase 1 · ADU-01 … · Fase 2 · ADU-02 … · Fase 3 · ADU-04 …» |
| H14 | Ruta del gerente de carga internacional | «Fase 1 · CAR-01 … · Fase 2 · CAR-02 … · Fase 3 · CAR-03 …» | «Fase 1 · CAR-03 … · Fase 2 · CAR-01 … · Fase 3 · CAR-02 …» |
| H11 | Ruta de gestión humana y formación | «Fase 1 · ADM-03 … · Fase 2 · ADM-04 …» | «Fase 1 · ADM-04 … · Fase 2 · ADM-03 …» |
| H12 | Ruta del arquitecto | «Fase 1 · TIC-04 … · Fase 2 · TIC-01 …» | «Fase 1 · TIC-01 … · Fase 2 · TIC-04 …» |
| H13 | Ruta del analista de datos | «Fase 1 · TIC-03 … · Fase 2 · TCT-03 …» | «Fase 1 · TCT-03 … · Fase 2 · TIC-03 …» |
| H13 | Ruta del analista de datos, proyecto ampliado | «Une en un solo modelo los datos de almacén, transporte, aduana y facturación, y construye sobre él el tablero OTIF por cliente.» | «Construye el tablero OTIF por cliente y une en un solo modelo los datos de almacén, transporte, aduana y facturación con esas definiciones.» |

En las rutas reordenadas, cada curso conserva su línea completa; solo cambian su número de fase y su posición.

### `LOG-TRC-03.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H19 | Diseño instruccional | «en 6 clases de 2 horas, con coordinadores de CEDI» | «en 6 clases de 2 horas, que operarios, conductores y auxiliares toman en el celular en bloques cortos, con coordinadores de CEDI» |
| H7 | Diseño instruccional | «El profesor trabaja con cinco clientes de TransAndes» | «El profesor trabaja con cuatro clientes de TransAndes» |
| H7 | Unidad 3 | «El proyecto se completa con la matriz de cinco clientes publicada.» | «El proyecto se completa con la matriz de cuatro clientes publicada.» |
| H7 | Clase 3.2, procedimiento | «El profesor presenta la matriz de cinco clientes» | «El profesor presenta la matriz de cuatro clientes» |

### `LOG-DIR-01.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H6 | Resultado | «una hoja de ruta que empieza por la visibilidad del corredor y la aduana» | «una hoja de ruta que empieza por los datos y las integraciones que necesitan la visibilidad del corredor y la aduana» |
| H17 | Contexto | «más de la mitad de los 400 camiones son de terceros sin integración» | «buena parte de los 400 camiones son de terceros sin integración» |
| H17 | Clase 1.1 | «más de la mitad de los camiones son de terceros sin integración» | «buena parte de los camiones son de terceros sin integración» |

### `LOG-DIR-02.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H17 | Contexto | «la mitad de la flota son terceros a los que se paga por viaje» | «buena parte de la flota son terceros a los que se paga por viaje» |
| H18 | Objetivo general | «defiende el caso ante la junta» | «defiende el caso ante el comité financiero» |
| H18 | Clase 3.2, lectura | «**Presentar a la junta.**» | «**Presentar al comité financiero.**» |

### `LOG-DIR-04.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H31 | Contexto | «y un sistema de calidad.» | «y un sistema de calidad. TransAndes ya guarda medicamentos de Vitalia en un área habilitada, pero esa área no alcanza para el servicio nuevo.» |
| H35 | Clase 4.1, lectura | «piloto con un cliente» | «prueba con un cliente» |
| H35 | Clase 4.1, procedimiento | «antes del piloto con una línea de Vitalia» | «antes de la prueba con una línea de Vitalia» |

### `LOG-TIC-02.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H5 | Proyecto ampliado | «Lo usan la torre de control y el asistente de servicio.» | «Lo usan la torre de control y lo usará el asistente de servicio.» |
| H5 | Resultado | «La torre de control y el asistente consultan en segundos lo que necesitan, y» | «La torre de control consulta en segundos lo que necesita, el servidor queda listo para el asistente de servicio, y» |
| H5 | Contexto | «TCT-01 y COM-03 necesitan consultar» | «TCT-01 y COM-03 van a necesitar consultar» |
| H5 | Clase 3.1, lectura | «cómo el asistente de COM-03 recibe» | «cómo el asistente de COM-03 recibirá» |
| H5 | Clase 3.1, procedimiento | «que conectó el asistente de servicio con una cuenta con acceso a todos los clientes; cada sesión del asistente queda limitada al titular que se verificó» | «que conectó la cuenta prevista para el asistente de servicio con acceso a todos los clientes; cada sesión del asistente quedará limitada al titular que se verifique» |

### `LOG-TIC-03.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H9 | Contexto | «Cada área de TransAndes tiene su hoja con su versión de los datos, y el informe mensual» | «Fuera del reporte semanal y del tablero de OTIF, cada área de TransAndes mantiene su hoja con su versión de los datos, y el informe mensual» |
| H33 | Contexto | «así que no se puede saber cuánto tardó en cada eslabón.» | «así que cada análisis reconstruye por su cuenta cuánto tardó cada pedido en cada eslabón.» |
| H33 | Clase 1.2, procedimiento | «con eso se miden los tiempos por eslabón que usa TCT-03» | «con eso se miden en un solo lugar los tiempos por eslabón que TRC-04 y TCT-03 calculaban por separado» |

### `LOG-TCT-01.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H10 | Clase 3.1, procedimiento | «el analista decide la acción y la comunicación con el protocolo de TCT-02» | «el analista decide la acción y la comunicación al cliente, que seguirá el protocolo de TCT-02» |

### `LOG-UMI-02.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H26 | Clase 2.1, lectura | «abrir la devolución de UMI-03» | «abrir la devolución» |

### `LOG-UMI-03.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H21 | Diseño instruccional | «en 4 clases de 2 horas, con jefes de bodega» | «en 4 clases de 2 horas, que los auxiliares toman en el celular en bloques cortos, con jefes de bodega» |

### `LOG-HSQ-01.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H20 | Diseño instruccional | «en 6 clases de 2 horas, con HSEQ» | «en 6 clases de 2 horas, que los conductores toman en el celular en bloques cortos, con HSEQ» |

### `LOG-ADM-03.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H8 | Contexto | «Los operarios y conductores ven llegar la telemetría» | «Los operarios y conductores ya trabajan con la telemetría» |
| H8 | Clase 1.1, procedimiento | «que usarán la aplicación de TRA-04 sin ser empleados» | «que usan la aplicación de TRA-04 sin ser empleados» |

### `LOG-COM-01.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H30 | Clase 2.2, procedimiento | «TransAndes demuestra hoy entre 86% y 94%, y la oferta compromete 95% desde el cuarto mes con un plan de arranque» | «la oferta compromete el OTIF que TCT-03 demuestra para la operación, con un plan de arranque» |

### `LOG-CAR-02.md`

| Hallazgo | Dónde | Antes | Después |
| --- | --- | --- | --- |
| H32 | Herramientas y métodos, MCP | «el servidor de TIC-02 consulta los hitos que llegan de las integraciones con las navieras» | «el servidor de TIC-02 consulta en el TMS los hitos que llegan de las integraciones con las navieras aprobadas en TCT-01» |

## 3. Hallazgos que no cambiaron ningún texto

| Hallazgo | Por qué | Fuente |
| --- | --- | --- |
| H15 | Rechazado: las olas no fijan el momento de la historia | Glosario, secciones 2 y 7.2 · HR9 · DD-1 |
| H16 | Rechazado: una duración del relato no limita la línea de tiempo | Regla R2 · HR9 · DD-1 |
| H22 | Rechazado: el tronco común es suministro, no obligación | Regla R1 · HR9 · DD-1 |
| H25 | Sin cambio de texto: la Biblia registra la junta directiva, el comité financiero y el comité comercial | DD-5 |
| HR16 | La propia revisión indica que no cambia nada | `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` |

## 4. Fichas sin cambios

Las otras 35 fichas no tienen correcciones: LOG-TRC-01, LOG-TRC-02, LOG-TRC-04, LOG-TRC-05, LOG-DIR-03, LOG-TIC-01, LOG-TIC-04, LOG-TRA-01, LOG-TRA-02, LOG-TRA-03, LOG-TRA-04, LOG-TCT-02, LOG-TCT-03, LOG-ADU-01, LOG-ADU-02, LOG-ADU-03, LOG-ADU-04, LOG-ZFR-01, LOG-ZFR-02, LOG-ZFR-03, LOG-CED-01, LOG-CED-02, LOG-CED-03, LOG-CED-04, LOG-UMI-01, LOG-CAR-01, LOG-CAR-03, LOG-HSQ-02, LOG-HSQ-03, LOG-COM-02, LOG-COM-03, LOG-COM-04, LOG-ADM-01, LOG-ADM-02 y LOG-ADM-04.

Cuatro de ellas cambian de fase en la tabla de `02` (TRA-04, TCT-03, TIC-03 y ADM-03), pero su texto no cambia.

## 5. Documentos nuevos

| Archivo | Qué es | Versiones |
| --- | --- | --- |
| `AUDITORIA-COHERENCIA-Logística.md` | Auditoría de coherencia del sector | Entrega inicial con H1 a H29 · revisión 1 (HR1 a HR11, H30 a H35) · revisión 2 (HR12 a HR16) · versión de cierre con el estado final de cada hallazgo y la sección «Para la Biblia» |
| `REVISION-AUDITORIA-COHERENCIA-Logística.md` | Primera revisión de AUDITOR (2026-10-21) | Entrada; no se modifica |
| `REVISION-2-AUDITORIA-COHERENCIA-Logística.md` | Segunda revisión de AUDITOR (2026-10-21) | Entrada; no se modifica |
| `ORIGINAL-…md` | Texto anterior a la auditoría de `01`, `02`, `03` y de once fichas, para la comparación de AUDITOR | No van al Proyecto PROD ni al LAB |

## 6. Archivos que salieron del Proyecto

| Archivo | Qué pasó |
| --- | --- |
| `04_fichas_cursos.md` | Ya no está en el Proyecto: sus fichas están separadas en los 48 archivos `LOG-…md`. No consta quién lo retiró ni cuándo |
| `LOG-TRA-03(1).md` | Duplicado idéntico de `LOG-TRA-03.md`. Lo borró el responsable (HR15) |

## 7. Lo que no consta

- **Originales de `01`, `02` y `03`.** Se reconstruyeron deshaciendo las correcciones sobre la versión final. La reconstrucción es exacta: cada frase corregida aparece una sola vez, al volver a corregirla se obtiene el archivo final, y conserva el número de líneas del original (282, 121 y 492).
- **Originales de COM-01 y CAR-02.** No se guardaron. Para este registro se obtuvieron deshaciendo H30 y H32 sobre la versión final.
- **Las 35 fichas sin cambios.** No se pudieron comparar con `04_fichas_cursos.md`, porque ese archivo ya no está en el Proyecto.
