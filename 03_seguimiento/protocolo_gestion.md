# Protocolo de gestión y monitoreo en GitHub

## 1. Unidad de trabajo y trazabilidad

El **README** explica el proyecto; cada **Issue** describe una actividad, riesgo o verificación; el **Project** permite administrar el trabajo de forma integrada. Los archivos de evidencia y los registros de decisión permiten auditar el avance.

Para cada actividad debe quedar claro: código, resultado verificable, responsable, prioridad, dependencia, periodo, estado, comentario de avance y evidencia.

## 2. Estados recomendados para el Project

| Estado | Regla de uso |
| --- | --- |
| Pendiente | Actividad registrada y aún sin ejecución |
| En curso | Trabajo iniciado; se registra qué se ha hecho |
| Bloqueada | Hay un impedimento identificable y una acción de desbloqueo |
| En revisión | Entregable disponible y a la espera de verificación |
| Finalizada | Criterio de cierre satisfecho y evidencia comprobada |

El estado **abierto/cerrado de GitHub Issues** no equivale a estos cinco estados. El estado detallado se administra en el campo **Status** del Project. Los nombres se pueden configurar según las opciones de la cuenta y el Project.

## 3. Campos recomendados para configurar el Project

| Campo | Tipo sugerido | Valores o uso |
| --- | --- | --- |
| Status | Selección única | Cinco estados de la tabla anterior |
| Prioridad | Selección única | Alta, Media, Baja |
| Componente | Selección única | Preparación, Movilización, Implementación, Seguimiento, Cierre, Riesgos, Control |
| Fecha de inicio | Fecha | Día de inicio acordado |
| Fecha objetivo | Fecha | Día límite acordado |

**Assignees** se gestiona desde cada Issue. Solo deben usarse cuentas con acceso real, no nombres escritos como si fueran asignaciones de GitHub.

## 4. Vistas

- **Tabla de gestión:** lista completa de Issues, responsables, prioridad, fechas, componente y estado.
- **Tablero de estados:** agrupado por Status para mover una actividad entre estados.
- **Cronograma / Roadmap:** representado con las fechas de inicio y objetivo acordadas.

Los Issues ya creados deben incorporarse al Project **existente** desde el panel lateral de cada Issue o mediante el menú de incorporación del Project. Crear Issues no los añade automáticamente.

## 5. Rutina semanal

1. Revisar actividades vencidas, próximas y bloqueadas.
2. Solicitar a cada responsable un avance concreto y enlazar evidencia.
3. Revisar dependencias antes de cambiar una fecha.
4. Registrar la decisión que altera alcance, secuencia o condiciones.
5. Verificar criterios de cierre y conservar trazabilidad.

## 6. Formato breve de comentario

**Corte:** AAAA-MM-DD  
**Avance comprobable:** qué se elaboró o revisó.  
**Dificultad / riesgo:** hecho observado, si existe.  
**Decisión / acción siguiente:** responsable y compromiso.  
**Evidencia:** enlace directo a documento o registro.

## 7. Cierre y reapertura

- Cambiar un Issue a **Finalizada** sin verificar el producto produce una apariencia engañosa de avance.
- Un Issue cerrado puede reabrirse si la evidencia falta, es inaccesible o incumple el criterio.
- El cumplimiento operativo no se deduce del número de comentarios ni del tiempo transcurrido.

**Autor:** Fabián A. Gamba-Sánchez.
