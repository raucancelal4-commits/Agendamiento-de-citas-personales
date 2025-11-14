# FACULTAD DE CIENCIAS E INGENIERÍA  
## CARRERA DE INGENIERÍA DE SOFTWARE

---

## *TEMA:*  
### Agendamiento de citas personales

### *AUTOR:*  
- Aucancela Lascano Ronny Polivio  

### *ASIGNATURA:*  
Introducción a la Ingeniería de Software  

### *DOCENTE:*  
Guevara Serrano Jorge Dumar  

### *FECHA DE ENTREGA:*  
5 de noviembre del 2025  

### *PERIODO:*  
Agosto 2025 – Diciembre 2025  

*MILAGRO – ECUADOR*

---

# 1. Introducción

El soporte del software es una etapa crucial dentro del ciclo de vida de cualquier aplicación. Aunque un sistema esté completado, su funcionamiento necesita mantenerse, adaptarse y mejorar a medida que las demandas del usuario y el entorno tecnológico evolucionan.

Para el sistema de Programa de Citas Personales, el mantenimiento tiene como objetivo mejorar la facilidad de uso, la accesibilidad y la seguridad en la gestión de citas, garantizando que los usuarios puedan gestionar sus actividades de manera confiable.

Este análisis se fundamenta en los conceptos introducidos por Sommerville (2011) y Pressman (2010), quienes detallan los tipos de mantenimiento y las fases necesarias para asegurar la evolución y estabilidad del software.

---

# 2. Tipos de Mantenimiento de Software

Los tipos principales de mantenimiento que se pueden aplicar al sistema de programación de citas son:

### *Mantenimiento Correctivo*
Corrige problemas o fallas que afectan el funcionamiento del sistema.  
Ejemplo: resolver un inconveniente que impide el guardado de una cita o que hace que el calendario no muestre los eventos planeados.

### *Mantenimiento Adaptativo*
Permite que el sistema siga operando cuando hay cambios en el entorno tecnológico.  
Ejemplo: actualizar el sistema cuando sale una nueva versión de Android o Windows o mover el almacenamiento local a un servicio en la nube.

### *Mantenimiento Perfectivo*
Mejora y añade nuevas funcionalidades que optimizan la experiencia del usuario.  
Ejemplo: incorporar filtros de búsqueda, sincronización con Google Calendar o habilitar un modo oscuro.

### *Mantenimiento Preventivo*
Previene futuros problemas mediante limpieza, optimización o reorganización del código.  
Ejemplo: eliminar funciones duplicadas, reforzar la seguridad o implementar cifrado para proteger los datos personales.

---

# 3. Etapas del Proceso de Mantenimiento

### *De acuerdo con Sommerville:*
1. Identificación del cambio  
2. Análisis del impacto en el sistema  
3. Diseño y ajustes en el programa  
4. Pruebas del sistema  
5. Entrega y liberación del cambio  

### *De acuerdo con Pressman:*
1. Comprensión de la problemática o solicitud  
2. Evaluación de la petición de cambio  
3. Elaboración de la solución  
4. Implementación y pruebas  
5. Liberación al usuario  
6. Registro en el historial del mantenimiento  

---

# 4. Análisis del Caso: Programa de Citas Personales

El sistema de Agenda Personal cumple su función primordial, pero presenta tres áreas críticas que afectan su rendimiento y efectividad:

### *Situación 1: Inexistencia de sincronización entre dispositivos*
La aplicación guarda las citas de manera local.  
Impacto: pérdida completa de datos si el usuario cambia de teléfono o reinicia su dispositivo; no se permite acceso en múltiples plataformas.

### *Situación 2: Recordatorios poco personalizables*
Las alertas se envían con un tiempo de aviso fijo.  
Impacto: disminuye su funcionalidad como asistente personal, afectando la puntualidad y organización del usuario.

### *Situación 3: Inseguridad y falta de protección de datos*
La información carece de cifrado o autenticación.  
Impacto: riesgo de exposición de datos personales, pérdida de privacidad y falta de confianza en el sistema.

---

# 5. Beneficios esperados

La implementación de mejoras en el sistema de Agendamiento de Citas Personales permitirá obtener los siguientes beneficios:

- Mayor seguridad y protección de la información personal  
- Disponibilidad multiplataforma  
- Reducción del riesgo de pérdida de datos  
- Recordatorios más eficientes  
- Mejor organización del tiempo  
- Mayor satisfacción del usuario  
- Escalabilidad del sistema  

---

# 6. Ejemplo de estimación de costos de mantenimiento

A continuación, se presenta una estimación general de los costos asociados al mantenimiento del sistema de Agendamiento de Citas Personales:

| Tipo de mantenimiento | Frecuencia anual | Horas/Incidente | Costo/Hora | Costo total |
|-----------------------|------------------|------------------|------------|-------------|
| Correctivo            | 4                | 10               | $50        | $2.000      |
| Adaptativo            | 2                | 20               | $50        | $2.000      |
| Perfectivo            | 1                | 40               | $50        | $2.000      |
| Preventivo            | 1                | 15               | $50        | $750        |
| *Total estimado*    | —                | —                | —          | *$6,750*  |

---

# 7. Conclusión y recomendaciones

El análisis del sistema de Agendamiento de Citas Personales indica que el cuidado continuo es esencial para mantener la utilidad y confiabilidad de la aplicación. Las limitaciones identificadas subrayan la necesidad de aplicar las categorías de mantenimiento propuestas por Sommerville y Pressman, en especial el mantenimiento correctivo y preventivo.

La inclusión del componente de sincronización en la nube marca un avance importante, ya que salvaguarda los datos, mejora la disponibilidad y optimiza la experiencia del usuario.

### *Se recomienda:*
- Renovar periódicamente los sistemas de seguridad  
- Registrar cada modificación para minimizar gastos futuros  
- Realizar pruebas de regresión tras cada actualización  
- Seguir ampliando funcionalidades según las necesidades reales de los usuarios  

El mantenimiento no solo soluciona inconvenientes, sino que también facilita la evolución continua del sistema, asegurando su relevancia, seguridad y adaptabilidad a lo largo del tiempo.
