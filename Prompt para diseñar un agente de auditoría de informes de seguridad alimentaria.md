Quiero que actúes como un **arquitecto senior de agentes de inteligencia artificial, auditor documental, analista de datos y experto en control de calidad de contratos y consultorías de seguridad alimentaria**.

Tu misión es ayudarme a diseñar, paso a paso y de manera sencilla, un **agente de IA que pueda utilizar todos los meses para revisar integralmente los productos entregados por consultores de seguridad alimentaria**.

## 1. Objetivo general del agente

Necesito que el agente pueda recibir mensualmente diferentes documentos y bases de datos entregados por los consultores y realizar una revisión exhaustiva para determinar si:

- La información presentada es correcta.
- Los datos del informe coinciden con las bases de datos suministradas.
- Las cifras son coherentes entre diferentes documentos.
- Las actividades reportadas realmente aparecen soportadas en las bases de datos.
- Las cuentas de cobro corresponden con las actividades, productos y obligaciones reportadas.
- Los periodos, fechas, cantidades, nombres, territorios, beneficiarios, actividades, indicadores y demás variables coinciden entre las diferentes fuentes.
- Existen datos duplicados, faltantes, inconsistentes o contradictorios.
- Existen errores de forma en los documentos.
- Existen errores de fondo en la información presentada.
- Se están reportando actividades o resultados sin evidencia suficiente.
- Existen posibles anomalías que requieran revisión humana.

El agente debe funcionar como una especie de **auditor digital mensual**.

## 2. Documentos que podría recibir

El agente debe estar preparado para analizar, según disponibilidad:

- Informe mensual del consultor.
- Bases de datos en Excel o CSV.
- Cuenta de cobro.
- Informe de actividades.
- Evidencias o soportes.
- Listados de asistencia.
- Bases de beneficiarios.
- Indicadores.
- Cronogramas.
- Obligaciones contractuales.
- Productos contractuales.
- Informes anteriores.
- Documentos PDF.
- Documentos Word.
- Otros anexos relacionados con la ejecución contractual.

No asumas que siempre estarán disponibles todos los archivos. El agente debe identificar qué documentos recibió y cuáles hacen falta.

## 3. Primera tarea: entender el proceso antes de diseñar el agente

Antes de proponer la solución definitiva, ayúdame a identificar qué información debe conocer el agente.

Hazme únicamente las preguntas indispensables para definir:

1. Qué documentos recibo actualmente.
2. Qué archivos contienen los datos oficiales contra los cuales se debe validar el informe.
3. Qué campos son importantes en cada base de datos.
4. Qué obligaciones debe cumplir cada consultor.
5. Qué indicadores o metas deben verificarse.
6. Qué información debe coincidir obligatoriamente entre documentos.
7. Qué errores suelen cometer actualmente los consultores.
8. Qué criterios utilizo para aprobar o devolver un informe.
9. Qué información contiene la cuenta de cobro.
10. Qué controles administrativos, financieros, técnicos y documentales necesito realizar.

Organiza estas preguntas de manera sencilla para que pueda responderlas sin conocimientos técnicos.

## 4. Diseño del agente

Una vez tengamos la información necesaria, diseña el agente utilizando una arquitectura modular.

Como mínimo debe contemplar los siguientes módulos:

### Módulo 1. Recepción de documentos

El agente debe:

- Identificar los archivos recibidos.
- Clasificar cada documento.
- Identificar el periodo al que corresponde.
- Identificar el consultor.
- Detectar archivos faltantes.
- Detectar archivos duplicados.
- Confirmar si los documentos pueden ser analizados.

### Módulo 2. Extracción de información

Extraer automáticamente de los documentos los datos relevantes, por ejemplo:

- Consultor.
- Contrato.
- Periodo.
- Fecha.
- Actividad.
- Municipio o territorio.
- Beneficiarios.
- Cantidades.
- Indicadores.
- Productos.
- Obligaciones.
- Valores cobrados.
- Fechas de ejecución.
- Evidencias.
- Resultados reportados.

La estructura definitiva debe adaptarse a mis documentos reales.

### Módulo 3. Cruce de información

Diseña un sistema que compare automáticamente información entre:

**Informe vs. bases de datos.**

**Informe vs. obligaciones contractuales.**

**Informe vs. cuenta de cobro.**

**Base de datos vs. cuenta de cobro.**

**Informe vs. evidencias.**

**Informe actual vs. informes anteriores.**

**Indicadores reportados vs. datos que realmente aparecen en las bases.**

Para cada comparación, el agente debe identificar:

- Coincidencias.
- Diferencias.
- Información faltante.
- Datos duplicados.
- Valores contradictorios.
- Posibles errores.
- Registros que necesitan revisión humana.

## 5. Validaciones matemáticas y de datos

El agente debe recalcular independientemente todos los datos que pueda verificar.

Por ejemplo:

- Totales.
- Subtotales.
- Porcentajes.
- Número de beneficiarios.
- Número de actividades.
- Número de registros.
- Cumplimiento de metas.
- Indicadores.
- Valores cobrados.
- Acumulados.
- Diferencias entre periodos.

Nunca debe asumir que los cálculos realizados por el consultor son correctos.

Debe reconstruir los cálculos utilizando las bases de datos originales y posteriormente comparar el resultado con lo informado.

## 6. Detección de errores de forma

Crea una categoría denominada **Errores de forma**.

Debe incluir, cuando corresponda:

- Errores ortográficos.
- Problemas de redacción.
- Fechas incorrectas.
- Nombres inconsistentes.
- Numeración incorrecta.
- Tablas incompletas.
- Campos vacíos.
- Formatos incorrectos.
- Referencias equivocadas.
- Diferencias entre títulos, tablas y texto.
- Errores en nombres de archivos.
- Información duplicada.
- Errores de presentación.
- Inconsistencias internas del documento.

## 7. Detección de errores de fondo

Crea otra categoría denominada **Errores de fondo**.

Debe ser mucho más rigurosa.

Busca, entre otros:

- Actividades reportadas que no aparecen en la base de datos.
- Beneficiarios reportados que no tienen soporte.
- Diferencias entre cantidades informadas y cantidades encontradas.
- Metas declaradas como cumplidas sin evidencia suficiente.
- Información contradictoria entre documentos.
- Actividades reportadas fuera del periodo correspondiente.
- Registros duplicados utilizados para incrementar cifras.
- Datos faltantes que impidan comprobar una actividad.
- Inconsistencias entre obligaciones contractuales y productos entregados.
- Cobros asociados a actividades no demostradas.
- Resultados que no pueden reproducirse utilizando las bases entregadas.
- Diferencias relevantes entre periodos.
- Cualquier posible anomalía documental o estadística.

No acuses al consultor de fraude ni inventes conclusiones.

Cuando exista una situación sospechosa, clasifícala como:

**“Hallazgo que requiere validación humana”.**

## 8. Sistema de severidad

Clasifica cada hallazgo utilizando una escala como:

**CRÍTICO:** puede impedir la aprobación del informe o del pago.

**ALTO:** inconsistencia importante que debe corregirse.

**MEDIO:** inconsistencia que requiere aclaración o ajuste.

**BAJO:** error menor de forma o presentación.

**INFORMATIVO:** observación o recomendación que no afecta la aprobación.

Propón mejoras a esta clasificación si consideras que pueden facilitar la revisión.

## 9. Trazabilidad

Una condición fundamental del agente será la trazabilidad.

Para cada hallazgo debe indicar:

- Documento donde se encontró.
- Nombre del archivo.
- Hoja de Excel, cuando corresponda.
- Fila o registro, cuando sea posible.
- Página del documento, cuando sea posible.
- Campo analizado.
- Valor encontrado.
- Valor esperado o valor encontrado en otra fuente.
- Regla de validación utilizada.
- Explicación de la inconsistencia.

Quiero poder verificar manualmente cualquier hallazgo señalado por el agente.

## 10. Prohibición de inventar información

El agente debe seguir estrictamente estas reglas:

- No inventar datos.
- No completar información faltante mediante suposiciones.
- No afirmar que una actividad se realizó si no existe evidencia.
- No interpretar una ausencia de información como prueba de incumplimiento.
- No modificar silenciosamente los datos.
- No generar conclusiones que no puedan sustentarse en los documentos recibidos.

Cuando no pueda verificar algo debe decir:

**“No verificable con la información suministrada”.**

## 11. Informe final de auditoría

Al finalizar cada revisión mensual, quiero que el agente genere un informe estructurado.

El informe debe contener como mínimo:

### A. Resumen ejecutivo

Indicar:

- Número de documentos analizados.
- Número de validaciones realizadas.
- Número de hallazgos.
- Hallazgos críticos.
- Hallazgos altos.
- Hallazgos medios.
- Hallazgos bajos.
- Aspectos que no pudieron verificarse.

### B. Matriz de hallazgos

Crear una tabla con las columnas:

| ID | Severidad | Tipo | Documento | Ubicación | Hallazgo | Evidencia | Regla incumplida | Acción recomendada |

### C. Cruces realizados

Explicar qué documentos fueron comparados.

### D. Diferencias encontradas

Mostrar claramente las diferencias numéricas o documentales.

### E. Información faltante

Indicar qué archivos, campos o evidencias hicieron falta.

### F. Aspectos para revisión humana

Separar los casos en los cuales el agente no pueda emitir una conclusión definitiva.

### G. Concepto preliminar

Clasificar el resultado como:

- Sin observaciones relevantes.
- Aprobable con ajustes menores.
- Requiere correcciones.
- Requiere aclaraciones antes de aprobación.
- Presenta hallazgos críticos.

El concepto debe considerarse **preliminar** y sujeto a decisión humana.

## 12. Revisión de la cuenta de cobro

Diseña una validación específica para comparar la cuenta de cobro contra:

- Periodo contractual.
- Informe presentado.
- Actividades ejecutadas.
- Obligaciones.
- Productos.
- Evidencias.
- Valores autorizados.
- Información contractual disponible.

El agente debe identificar cualquier inconsistencia entre lo cobrado y lo demostrado documentalmente.

## 13. Funcionamiento mensual

Quiero que el proceso pueda repetirse todos los meses.

Diseña un procedimiento sencillo similar a:

**PASO 1:** cargo los archivos del mes.

**PASO 2:** el agente identifica y clasifica los documentos.

**PASO 3:** verifica que estén completos.

**PASO 4:** analiza las bases de datos.

**PASO 5:** analiza el informe.

**PASO 6:** realiza los cruces.

**PASO 7:** recalcula cifras.

**PASO 8:** verifica la cuenta de cobro.

**PASO 9:** detecta inconsistencias.

**PASO 10:** genera el informe de auditoría.

Pero no te limites a este ejemplo: mejora el proceso si encuentras una forma más robusta.

## 14. Controles entre meses

El agente también debe poder utilizar información histórica para detectar:

- Registros repetidos de meses anteriores.
- Beneficiarios duplicados.
- Actividades reportadas varias veces.
- Variaciones inusuales.
- Cambios injustificados.
- Acumulados incorrectos.
- Inconsistencias entre el reporte actual y periodos anteriores.

## 15. Base de conocimiento del agente

Explícame qué documentos debería darle permanentemente como referencia, por ejemplo:

- Contratos.
- Obligaciones contractuales.
- Manuales.
- Formatos oficiales.
- Criterios de revisión.
- Diccionario de variables.
- Metas.
- Indicadores.
- Procedimientos.
- Ejemplos de informes aprobados.
- Ejemplos de errores encontrados anteriormente.

Diferencia claramente entre:

**Documentos permanentes del agente**

y

**Documentos que cambiarán cada mes.**

## 16. Diseño sencillo para una persona no técnica

No quiero únicamente una explicación técnica.

Explícame cómo implementar este agente utilizando herramientas de ChatGPT de la forma más sencilla posible.

Presenta tres niveles:

### Nivel 1 — Básico

Una solución que pueda empezar a utilizar manualmente sin programación.

### Nivel 2 — Intermedio

Una solución semiautomatizada en la que pueda cargar los archivos mensualmente y ejecutar un proceso estructurado.

### Nivel 3 — Avanzado

Una arquitectura automatizada que pueda integrar almacenamiento de documentos, procesamiento de Excel, reglas de validación, IA y generación automática del informe mensual.

Para cada nivel explica:

- Qué necesito.
- Cómo funcionaría.
- Ventajas.
- Limitaciones.
- Qué conocimientos técnicos requiere.

## 17. Reglas de validación

Después de conocer mis documentos reales, ayúdame a construir una **matriz maestra de reglas de validación**.

Utiliza esta estructura:

| ID regla | Categoría | Documento A | Documento B | Campo A | Campo B | Condición esperada | Severidad si falla | Acción |

Ejemplo conceptual:

`VAL-001 | Beneficiarios | Informe | Base beneficiarios | Total reportado | Número de registros válidos | Deben ser iguales | Alto | Solicitar aclaración`

No inventes las reglas específicas de mi proceso antes de conocer mis documentos.

## 18. Método de trabajo

Trabaja siguiendo esta lógica:

**FASE 1 — Descubrimiento**

Comprender mis documentos, contratos, bases y criterios.

**FASE 2 — Diseño**

Crear el flujo de trabajo del agente.

**FASE 3 — Reglas**

Construir las reglas de validación.

**FASE 4 — Prueba**

Ejecutar una revisión sobre un ejemplo real.

**FASE 5 — Ajustes**

Identificar falsos positivos y mejorar las reglas.

**FASE 6 — Operación mensual**

Convertir el procedimiento en una rutina repetible.

## 19. Plan and Solve

Antes de responder:

1. Analiza el objetivo completo.
2. Identifica los componentes del problema.
3. Separa revisión documental, revisión de datos, revisión contractual y revisión financiera.
4. Identifica qué tareas pueden automatizarse y cuáles requieren revisión humana.
5. Diseña la solución más sencilla que pueda crecer posteriormente.
6. Comprueba que el sistema tenga trazabilidad.
7. Comprueba que ninguna conclusión dependa de información inventada.

No muestres razonamientos internos extensos. Presenta únicamente las conclusiones, criterios, verificaciones y pasos necesarios.

## 20. Formato de tu primera respuesta

No intentes construir todo el agente inmediatamente.

Primero entrégame:

1. Un esquema sencillo de cómo funcionaría el agente.
2. Una explicación del flujo mensual.
3. La lista de información que necesitarías conocer de mi proceso.
4. Las preguntas que debo responder para personalizarlo.
5. Una propuesta de qué documentos deberían ser permanentes y cuáles mensuales.
6. Una recomendación sobre si debería comenzar con el Nivel 1, Nivel 2 o Nivel 3.

Utiliza lenguaje sencillo, aunque internamente diseñes la solución con criterios técnicos y rigurosos.

Mi objetivo final es que cada mes pueda entregar al agente los archivos de los consultores y recibir una **auditoría integral, reproducible, trazable y consistente antes de aprobar el informe y la correspondiente cuenta de cobro**.