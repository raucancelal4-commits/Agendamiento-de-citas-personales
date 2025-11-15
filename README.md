# Sistema de Agendamiento de Citas Personales

## Descripción del caso
El Sistema de Agendamiento de Citas Personales es una aplicación digital que permite registrar, organizar y visualizar citas con fecha, hora y descripción. Su objetivo es ofrecer una herramienta práctica y accesible para que los usuarios puedan administrar de manera eficiente sus compromisos diarios, evitando olvidos y mejorando su organización personal.

Es ideal para estudiantes, trabajadores y cualquier persona que desee mantener un control sencillo, ordenado y digital de sus actividades.

---

## Objetivos
- Desarrollar una aplicación funcional para gestionar citas personales.
- Aplicar principios de ingeniería de software: requerimientos, pruebas y mantenimiento.
- Elaborar un Documento de Requerimientos de Software (DRS).
- Implementar procesos de mejora basados en mantenimiento del software.
- Documentar el proyecto correctamente usando un formato claro y estructurado.

---

## Requisitos principales

### Requisitos funcionales
- Permitir registrar nuevas citas con fecha, hora y descripción.
- Mostrar la lista de citas organizadas cronológicamente.
- Editar la información de una cita previamente registrada.
- Eliminar citas de la lista de registros.
- Enviar una notificación o recordatorio antes de la hora programada.

### Requerimientos no funcionales
- Interfaz intuitiva y fácil de usar.
- Operaciones rápidas (menos de 2 segundos por acción).
- Compatibilidad multiplataforma (Windows y Android).
- Diseño simple con retroalimentación visual.

---

## Tabla de pruebas

| Caso de prueba | Entrada | Resultado esperado | Validación |
|----------------|---------|--------------------|------------|
| **CP1 – Registrar cita** | Fecha: 21/10/2025, Hora: 10:00, “Cita odontológica” | Cita registrada correctamente | ✅ Correcto |
| **CP2 – Editar cita** | Cambiar “10:00” a “12:30” | Cita actualizada | ✅ Correcto |
| **CP3 – Eliminar cita** | “Cita odontológica” | Cita eliminada de la lista | ✅ Correcto |
| **CP4 – Consultar citas del día** | Fecha actual | Mostrar citas del día | ✅ Correcto |
| **CP5 – Recordatorio** | Cita 10:00 | Notificación a las 9:50 | ✅ Correcto |

---

## Tipo de mantenimiento propuesto

### Nuestro Perfectivo
Este mantenimiento se centra en mejorar la experiencia del usuario y ampliar las funciones del sistema sin alterar su propósito principal.

### Mejoras implementadas o sugeridas
- Personalización del tiempo de recordatorios.
- Integración con almacenamiento en la nube para evitar pérdida de datos.
- Filtros de búsqueda para localizar citas rápidamente.
- Sincronización con calendarios externos (Google Calendar).

Estas mejoras aumentan notablemente la usabilidad, escalabilidad y valor del software, haciéndolo más completo y confiable para el usuario.

---

## Reflexión sobre el control de versiones

El control de versiones permite llevar un registro detallado de los cambios realizados en el proyecto, evitando la pérdida de información y permitiendo trabajar de forma organizada. Es fundamental en la ingeniería de software porque:

- Facilita la colaboración entre desarrolladores.
- Permite revertir errores mediante versiones anteriores.
- Mantiene un historial claro de avances.
- Mejora la trazabilidad y control del código.

### Tipos de sistemas de control de versiones

#### Sistemas locales
Cada desarrollador registra los cambios solo en su equipo.
- **Ventajas:** rápidos y simples.
- **Desventajas:** poca colaboración, riesgo de pérdida de datos.

#### Sistemas centralizados
Un servidor almacena el repositorio completo.
- **Ventajas:** control central y seguridad.
- **Desventajas:** dependen del servidor.
- **Ejemplo:** SVN.

#### Sistemas distribuidos
Cada usuario posee una copia completa del repositorio, incluido su historial.
- **Ventajas:** trabajo sin conexión, rapidez, flexibilidad.
- **Ejemplo:** Git.

### Elementos y operaciones básicas en Git
- **Repositorio:** almacén del historial completo del proyecto.
- **Copia de trabajo:** versión local donde se realizan cambios.
- **Confirmar (commit):** guarda los cambios con un mensaje.
- **Registro (log):** muestra el historial de modificaciones.
- **Pagar (checkout):** cambia entre versiones o ramas.
- **Push / Pull:** sincroniza cambios entre repositorios.
- **Rama (branch):** permite desarrollo paralelo de nuevas funciones.

### GitHub en el proyecto
GitHub fue útil para:
- Centralizar los documentos y versiones del sistema.
- Subir commits descriptivos en cada entrega.
- Visualizar y comparar versiones (como DRS_v1 y DRS_v2).
- Documentar en Markdown, mejorando legibilidad y colaboración.

El uso de GitHub aseguró un control de versiones ordenado, colaborativo y trazable durante todo el desarrollo del software.

---

## Autor
**Ronny Aucancela**
