# Configuración del GitHub Project | Conecta Biblioteca

Trabajar en el **Project ya creado para este repositorio**. Evitar abrir un segundo Project para las mismas actividades.

## 1. Incorporar los Issues existentes

1. Abrir el Project.
2. En la última fila de la vista de tabla, seleccionar **+ → Add item from repository** (Agregar elemento desde repositorio).
3. Elegir `FGambaS/conecta-biblioteca`.
4. Seleccionar los Issues del **#1 al #15** y agregarlos. Comprobar que DOC-01 (#15), ya cerrado, también figure en el tablero.
5. Verificar en un Issue, en el panel **Projects**, que se muestre el Project correspondiente.

También se pueden seleccionar Issues en bloque desde la lista del repositorio y elegir **Projects**. Una vez incorporados, no volver a crear los mismos Issues desde el tablero.

## 2. Configurar campos

| Campo | Tipo | Valores |
| --- | --- | --- |
| Status | Selección única | Pendiente, En curso, Bloqueada, En revisión, Finalizada |
| Prioridad | Selección única | Alta, Media, Baja |
| Componente | Selección única | Preparación, Movilización, Implementación, Seguimiento, Cierre, Riesgos, Control |
| Fecha inicio | Fecha | Fecha acordada por el equipo |
| Fecha objetivo | Fecha | Fecha de compromiso acordada |

El nombre exacto y la disponibilidad de los campos pueden variar según los permisos y la configuración del Project. **Assignees** proviene de los Issues y requiere usuarios colaboradores autorizados.

## 3. Vistas recomendadas

- **Tabla de gestión:** presentar título, responsable, Status, Prioridad, Componente, Fecha inicio y Fecha objetivo. Ordenar por prioridad o fecha.
- **Tablero de control:** diseño Board y columnas agrupadas por **Status**; debe permitir mover una tarjeta de una columna a otra.
- **Cronograma:** diseño Roadmap con las fechas de inicio y objetivo. Sin fechas acordadas, esta vista no representa un calendario válido.

## 4. Estado de referencia para practicar

Los valores siguientes **orientan la configuración**. No significan que el campo ya haya sido modificado.

| Issue | Estado propuesto | Prioridad | Motivo |
| --- | --- | --- | --- |
| #1 ACT-01 | En revisión | Alta | Plan redactado, requiere aprobación |
| #2 ACT-02 | Bloqueada | Alta | Cerrada previamente sin evidencia, reabierta |
| #3 ACT-03 | Pendiente | Alta | Espera línea base de planeación |
| #4 ACT-04 | Pendiente | Alta | Depende de caracterización |
| #5 ACT-05 | Bloqueada | Alta | Depende de ACT-02 |
| #6 ACT-06 | Pendiente | Alta | Requiere sedes |
| #7 ACT-07 | Pendiente | Media | Requiere plan formativo y sedes |
| #8 ACT-08 | Pendiente | Alta | Requiere preparación |
| #9 ACT-09 | Pendiente | Alta | Requiere primer ciclo |
| #10 ACT-10 | Pendiente | Alta | Monitoreo operativo aún sin jornadas |
| #11 ACT-11 | Pendiente | Media | Depende de ejecución y seguimiento |
| #12 ACT-12 | Pendiente | Media | Depende de informe final |
| #13 RIES-01 | En curso | Alta | Riesgo identificado; mitigación por validar |
| #14 VER-01 | En curso | Alta | Auditoría inicial comenzada |
| #15 DOC-01 | Finalizada | Media | Estructura del repositorio comprobada |

## 5. Demostración del circuito completo

1. Abrir #2 y mostrar comentario de revisión y reapertura.
2. Revisar #5 y cómo su dependencia de #2 condiciona la planificación.
3. Abrir #15 y comprobar sus enlaces de evidencia y su estado cerrado.
4. En el tablero, trasladar #14 de **En curso** a **En revisión** únicamente cuando exista un informe de auditoría para revisar.
5. En la tabla, ordenar por Prioridad y filtrar por responsable.
6. En Roadmap, mostrar qué ocurre cuando la fecha de una tarea dependiente se posterga.
7. Regresar al Issue y registrar avance, decisión, responsable y enlace al producto.

**Regla fundamental:** mover una tarjeta no sustituye un producto ni una verificación.

**Autor:** Fabián A. Gamba-Sánchez.
