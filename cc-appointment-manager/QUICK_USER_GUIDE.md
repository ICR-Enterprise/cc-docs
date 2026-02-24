# Guía de Usuario: C&C Appointment Manager

## Introducción
Esta barra lateral te ayuda a agendar citas rápidamente, asegurando que los datos del cliente estén correctos y que no haya empalmes de horario con las técnicas.

## Pasos para Agendar una Cita

### 1. Abrir el Complemento
En tu Google Calendar web, busca el icono de **"C&C"** en la barra lateral derecha y haz clic para abrir el panel.

### 2. Llenar Datos de la Cita
El panel te pedirá:
*   **Técnica**: ¿Quién atenderá? (Ej. Camila, Carlota).
*   **Servicio**: Descripción breve (Ej. "Gelish manos").
*   **Duración**: Tiempo estimado.
*   **Fecha y Hora**: Selecciona en el calendario emergente.

### 3. Datos del Cliente (¡Nuevo Sistema!)
Aquí puedes escribir los datos del cliente.
*   **Búsqueda Rápida**: Escribe el nombre o teléfono. Si el cliente ya existe, aparecerán sugerencias.
*   **Autofill**: Al seleccionar una sugerencia, el sistema llenará automáticamente teléfono y correo.
    *   🔒 **Candado Cerrado**: Significa que los datos están protegidos. El sistema "recordó" al cliente y no dejará que sobrescribas por error.
    *   🔓 **Candado Abierto**: Modo de edición libre.
    *   **Botón Limpiar (🧹)**: Si te equivocaste de cliente, pulsa este botón para borrar los campos y desbloquear el candado.

### 4. Validar y Crear
1.  Pulsa **"Validar horario"**. El sistema revisará si la hora está libre.
    *   ✅ "Validación exitosa": Todo bien.
    *   ⚠️ "Horario ocupado": Hay otra cita. El sistema te sugerirá el siguiente horario libre.
2.  Si todo está correcto, pulsa **"Crear cita"**.
    *   Se agendará en el calendario.
    *   Se guardará/actualizará al cliente en la base de datos automáticamente.

## Preguntas Frecuentes

**¿Por qué no puedo editar el nombre/teléfono?**
Probablemente el sistema detectó un cliente existente y activó el "Bloqueo de Seguridad" (🔒). Pulsa el botón "🧹 Borrar Datos" o cambia manualmente el interruptor del candado a "Desbloqueado" para editar.

**¿Qué hago si me dice "Horario ocupado"?**
Revisa el mensaje de error. A veces dice "Sugerido: Lun 12 Oct 10:00". Puedes cambiar la hora a esa sugerencia y volver a validar.

**¿Necesito guardar al cliente manualmente?**
No. Al pulsar "Crear cita", el sistema guarda automáticamente los datos nuevos del cliente en la base de datos.
