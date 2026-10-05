# Estrategia de validación

El proyecto usa gates para separar una arquitectura plausible de un sistema demostrado.

## Áreas de validación

### Recursos de software

Comprobar que los recursos necesarios del MCU pueden coexistir y que la configuración puede reproducirse y compilarse de forma consistente.

**Estado:** validación ejecutada para una configuración primaria; quedan dependencias abiertas antes del cierre global.

### Adquisición y timing físicos

Comprobar estabilidad, coherencia y comportamiento temporal con hardware real.

**Estado:** pendiente.

### Alimentación e integración

Medir consumo, secuencias de arranque, interacción entre subsistemas y comportamiento ante cambios de estado.

**Estado:** pendiente.

### Carga concurrente

Medir CPU, memoria y throughput mientras las funciones representativas operan simultáneamente.

**Estado:** pendiente.

### Desempeño del sistema

Las métricas de desempeño se medirán únicamente cuando exista una implementación experimental adecuada. Los objetivos internos no se publican como resultados.

## Criterio de avance

El diseño de hardware no se congela solo porque una arquitectura parezca razonable. Si una validación cambia una decisión importante, esa decisión se reabre antes de avanzar.
