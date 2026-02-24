# Guía Oficial de Usuario: C&C Appointment Manager

¡Bienvenida al manual del Add-on de Carlota & Camila! Esta herramienta ha sido diseñada para automatizar, facilitar y agilizar tu trabajo diario al momento de agendar citas. Sigue este recorrido paso a paso para dominar el sistema rápido y fácil.

---

## 1. Conociendo el Add-on
Al abrir el complemento desde el panel derecho de Google Calendar, te encontrarás con el formulario principal vacío y listo para trabajar. Esta pantalla está diseñada para ser ultra-rápida e intuitiva. 

![Pantalla Principal](images/Screenshot%202026-02-23%20at%205.45.39%E2%80%AFp.m..png)

---

## 2. Selección de Técnica
El primer dato que debes confirmar es quién atenderá la cita. Al hacer clic en este menú, verás la lista de las técnicas (asociadas) disponibles. Asegúrate de seleccionar la correcta para el espacio en la agenda.

![Selección de Técnica](images/Screenshot%202026-02-23%20at%205.46.00%E2%80%AFp.m..png)

---

## 3. Selección y Gestión de Servicios
Esta es la parte fundamental de la cita. Las citas regulares en C&C se componen de uno o varios servicios requeridos por el cliente. Todo se basa en nuestro catálogo oficial.

### 📋 Catálogo Oficial de Servicios *(Actualizado)*
A continuación se muestra el listado base de servicios. Puedes consultar o editar el catálogo en vivo desde su base de datos oficial:  
🔗 **[Ver Catálogo Oficial en Google Sheets](https://docs.google.com/spreadsheets/d/1rs0jA3W67Dr7r3ieuAY0G9-LzBw9Ranz0fhYAXmd7BU/edit?usp=sharing)**

| Código Corto | Nombre del Servicio | Descripción Adicional | Precio Base |
| :--- | :--- | :--- | :--- |
| `ACR_BASIC_L20` | Acrílico liso hasta el #2 | | $350.00 |
| `ACR_DESIGN_L20` | Acrílico c/diseño hasta el #2 | | $420.00 |
| `ACR_BASIC_L25TO40` | Acrílico liso del 2 ½ al 4 | | $380.00 |
| `ACR_DESIGN_L25TO40`| Acrílico c/diseño del 2 ½ al 4 | | $450.00 |
| `ACR_BASIC_L45TO60` | Acrílico liso del 4 ½ al 6 | | $480.00 |
| `ACR_DESIGN_L45TO60`| Acrílico c/diseño del 4 ½ al 6 | | $590.00 |
| `ACR_BBOOMER_L20` | Acrílico BabyBoomer hasta el #2 | Acrílico con técnica babyboomer hasta el #2 | $390.00 |
| `ACR_BBOOMER_L25TO40`| Acrílico BabyBoomer del 2 ½ al 4 | Acrílico con técnica babyboomer del 2 ½ al 4 | $420.00 |
| `ACR_BBOOMER_L45TO60`| Acrílico BabyBoomer del 4 ½ al 6 | Acrílico con técnica babyboomer del 4 ½ al 6 | $460.00 |
| `FILLIN_BBOOMER_L45TO60`| Retoque BabyBoomer | Fill-in: Cuando se rellena el crecimiento de uña acrílica o gel. | $300.00 |
| `OVERLAY_ACR_BASIC_L2`| Baño de acrílico liso | | $350.00 |
| `OVERLAY_ACR_DESIGN_L2`| Baño de acrílico c/diseño | | $400.00 |
| `OVERLAY_ACR_BASIC_L25TO40`| Baño de acrílico liso del 2 ½ al 4 | | |
| `OVERLAY_ACR_DESIGN_L25TO40`| Baño de acrílico c/diseño del 2 ½ al 4 | | |
| `OVERLAY_ACR_BASIC_L45TO60`| Baño de acrílico liso del 4 ½ al 6 | | |
| `OVERLAY_ACR_DESIGN_L45TO60`| Baño de acrílico c/diseño del 4 ½ al 6 | | |
| `FILLIN_BASIC_L2` | Retoque liso hasta el #2 | Fill-in: Cuando se rellena el crecimiento de uña acrílica o gel. | $300.00 |
| `FILLIN_DESIGN_L2` | Retoque c/diseño hasta el #2 | | $330.00 |
| `FILLIN_BASIC_L25TO40`| Retoque liso del 2 ½ al 4 | | $360.00 |
| `FILLIN_DESIGN_L25TO40`| Retoque c/diseño del 2 ½ al 4 | | $430.00 |
| `FILLIN_BASIC_L45TO60`| Retoque liso del 4 ½ al 6 | | $390.00 |
| `FILLIN_DESIGN_L45TO60`| Retoque c/diseño del 4 ½ al 6 | | $530.00 |
| `GELISH_1T` | Gel/Gelish un tono | | $140.00 |
| `GELISH_FRENCH` | Frances/French | | $160.00 |
| `GELISH_DESIGN_2N` | Gel/Gelish c/diseño (dos uñas por mano)| Sólo se contempla el diseño hasta en dos uñas por mano | $200.00 |
| `RUBBER_TRT` | Rubber o tratamiento | | $100.00 |
| `FILLIN_RUBBER_WO_GELISH`| Retoque de rubber sin gel/gelish | | $80.00 |
| `RM_GELISH` | Retiro de gel/gelish | | $40.00 |
| `RM_ACR` | Retiro de acrílico | | $90.00 |
| `SPA_MANICURA` | Manicura | | $200.00 |
| `SPA_MANICURA_RUSSIAN`| Manicura Rusa | | $100.00 |
| `RM_CUT` | Retiro de cutícula | | $50.00 |
| `SPA_PEDICURA` | Pedicura | | $330.00 |
| `SPA_PEDICURA_W_GELISH`| Pedicura con gel | | $470.00 |
| `GELISH_TOE` | Gel/Gelish en pies | | $140.00 |
| `RM_GELISH_TOE` | Retiro de gel/gelish en pies | | $40.00 |
| `ACR_TOE` | Acripie (Aplicación de acrílico en pies)| | $300.00 |
| `ACR_TOE_FILLIN` | Retoque de acrílico en pies | | $250.00 |
| `EXT_FX` | Efectos | | $10.00 |
| `EXT_3D` | 3D | | $30.00 |
| `EXT_SUGGAR_FX` | Efecto azúcar | | $30.00 |
| `EXT_REL` | Relieve | | $35.00 |
| `EXT_XTAL` | Cristales | El costo depende del tamaño del cristal | $2.00 |
| `EXT_CHARM` | Aplicaciones | | $15.00 |
| `SERV_MISC` | Otros / Servicio Especial | | $0.00 |

<br>

**Búsqueda Inteligente (Predictiva):** El campo de servicio en el formulario actuará como un buscador inteligente y predictivo. Al escribir al menos 3 letras, el sistema buscará en toda la base de datos (mostrada arriba) y te sugerirá las opciones correctas sin tener que memorizar un código.

![Búsqueda de Servicio](images/Screenshot%202026-02-23%20at%205.46.34%E2%80%AFp.m..png)

### 3.1 Agregar el Primer Servicio
Una vez que encuentres y selecciones el servicio, haz clic en el botón azul **"Agregar Servicio"**. Esto lo añadirá a la "canasta" de la cita.

![Agregar Servicio](images/Screenshot%202026-02-23%20at%205.46.52%E2%80%AFp.m..png)
![Servicio Agregado](images/Screenshot%202026-02-23%20at%205.47.11%E2%80%AFp.m..png)

### 3.2 Agregando Múltiples Servicios
Una clienta puede querer uñas de acrílico y adicionalmente un pedicure. Simplemente **repite el proceso**: busca el segundo servicio y vuelve a presionar "Agregar Servicio". Añade tantos servicios como la cita lo requiera (el tipo de cita se configura de acuerdo al total de los servicios seleccionados del catálogo C&C).

![Múltiples Servicios 2](images/Screenshot%202026-02-23%20at%205.47.54%E2%80%AFp.m..png)

### 3.3 Botón Borrar
Si te equivocaste al seleccionar o el cliente cambia de parecer al teléfono, no te preocupes, usa el botón de **borrar** (el icono del bote de basura junto al servicio) para eliminarlo instantáneamente sin perder el resto del formulario.

![Botón Borrar Servicio](images/Screenshot%202026-02-23%20at%205.48.08%E2%80%AFp.m..png)

### 3.4 Servicios Fuera de Catálogo ("Otros / Servicio Especial")
Lo ideal, correcto e importante, es añadir siempre todos y únicamente los servicios oficiales del catálogo. Sin embargo, si surge la necesidad por una solicitud muy particular que **no esté en el catálogo**, debes:
1. Buscar y seleccionar el rubro llamado **"Otros / Servicio Especial"**.
2. Desplazarte hacia abajo en el formulario al área de **"Comentarios adicionales"** y hacer uso de ahí para describir detalladamente de qué trata la variación, petición extra o particularidad acordada con la clienta, para que el equipo logre captar la esencia médica o técnica solicitada.

![Campo Comentarios Vacío](images/Screenshot%202026-02-23%20at%205.49.30%E2%80%AFp.m..png)
![Campo Comentarios Lleno](images/Screenshot%202026-02-23%20at%205.49.45%E2%80%AFp.m..png)

---

## 4. Selección de Fecha, Hora y Cliente

### Fecha y Hora
Desplázate hacia abajo y selecciona con un clic la fecha deseada en el pequeño calendario emergente. Después, busca la hora de inicio solicitada.

![Despliegue de Fecha](images/Screenshot%202026-02-23%20at%205.48.20%E2%80%AFp.m..png)
![Selección de Hora](images/Screenshot%202026-02-23%20at%205.48.33%E2%80%AFp.m..png)

### Selección del Cliente (Flujo de Búsqueda de 2 Niveles)
Para facilitar y acelerar la captura de datos de las clientas recurrentes, contamos con una agenda pre-construida de clientes. Existen diferentes formas de encontrar si un cliente ya existe:

**Nivel 1: Lista Desplegable (Caché Rápido)**
Primero, escribe unas letras del nombre o número en el menú desplegable superior del cliente. Esto realiza una búsqueda predictiva ultrarrápida (en memoria caché local). 
1. Si el cliente aparece en la lista de sugerencias, simplemente dale clic de la lista que se despliega.
2. Esto auto-completará su información principal bloqueando los campos para evitar errores con los candados.

![Buscador Predictivo Caché](images/Screenshot%202026-02-23%20at%205.48.48%E2%80%AFp.m..png)
![Cliente Seleccionado Rápidamente](images/Screenshot%202026-02-23%20at%205.48.58%E2%80%AFp.m..png)

**Nivel 2: Búsqueda Forzada en Base de Datos**
Si en el paso anterior el desplegable arroja "Cero coincidencias" o no te da sugerencias (lo que puede ocurrir si la caché de los clientes recientes no alcanzó a actualizarse), puedes realizar una búsqueda profunda forzada (Búsqueda por Token):
1. Escribe palabras clave (*tokens*) de búsqueda en los cuadros libres (ya sea su nombre, el apellido, los dígitos de su teléfono o parte de su correo electrónico).
2. Oprime presencialmente el botón azul **"Buscar"**.
3. **Si el sistema te devuelve la información pre-llenada**, confírmala y listo.
4. **Si tras oprimir Buscar no trajiste ningún resultado**, entonces es indudablemente un **Cliente Nuevo**. Deberás proceder a capturar todos sus datos manualmente para crearle su ficha.

![Búsqueda Forzada en Base de Datos](images/Screenshot%202026-02-23%20at%205.49.13%E2%80%AFp.m..png)

### 💡 Speech / Guion de Asistencia: Solicitar Datos Personales
Suele haber resistencia en ofrecer datos como el correo, así que utiliza este guion inteligente y cordial para lograr resultados impecables:

> **Petición Inicial:** *"¡Hola hermosa/excelente! Para amarrarte ese espacio en la agenda y además asegurarnos de enviarte todos los detalles y el recordatorio a tu WhatsApp ahorita mismo, ¿me podrías compartir tu número de celular y tu nombre completo por favor?"*
> 
> **Petición del Correo Electrónico:** *"¡Mil gracias! Y ya por último para completar tu ficha como clienta y enviarte tu comprobante ¿Me compartes tu correo electrónico?"*
> 
> **Si el cliente duda o se niega (Manejo de Objeción):** *"No te preocupes, prometemos que en C&C mandamos cero spam. Éste es tu correo de seguridad, nos ayuda a garantizar plenamente que tu cita está ligada a ti, es buenísimo para activar nuestro protocolo de recordatorios oficiales, ¡y te asegura poder recibir notificaciones de beneficios y regalos futuros de Carlota & Camila!"*

---

## 5. Validar y Crear la Cita
Una vez con la información técnica, hora, cliente (y notas especiales de ser el caso) listas, irás directamente oprimir botones de comando final:

1. **Verificar Horario (Validar):** Una regla indispensable nos dicta que no puedes empalmar a una técnica. Al oprimir *"Validar"*, el sistema confirmará analizando toda la Base de Datos que realmente esa técnica no tenga cita alguna cruzándose. *Ojo: siempre puedes visualizar los espacios abiertos revisando gráficamente el calendario en el fondo.*
2. **Crear Cita:** Tras una validación existosa, pulsa sobre el botón vibrante *"Crear"*. Oprimirlo asegurará y "sembrará" el bloque oficial en el calendario.

![Botones de Validación y Creación](images/Screenshot%202026-02-23%20at%205.49.20%E2%80%AFp.m..png)

---

## 6. Ventana de Confirmación ("Success")
Inmediatamente tras la creación, ingresarás a una interfaz muy visual de éxito. Esta ventana "Success" amigable consta estructuralmente de un resumen veloz visual del éxito:
* Confirmación textual superior ("Cita creada exitosamente").
* Un bloque central con el Resumen directo.
* Los botones azules automáticos de envíos para la plataforma de WhatsApp.
* Los campos grises de Respaldo al final.

![Ventana Success General](images/Screenshot%202026-02-23%20at%205.50.06%E2%80%AFp.m..png)
![Resumen Detallado Success](images/Screenshot%202026-02-23%20at%205.50.20%E2%80%AFp.m..png)

---

## 7. Botones Automáticos de Notificación WhatsApp
Esta genialidad de los botones en la ventana de Success activará automáticamente la ventana a WhatsApp precargando la información e instrucción lista con tan solo tener que presionar la flecha de enviar. El orden metódico deberá ser impecable:

![Botones WhatsApp Listos](images/Screenshot%202026-02-23%20at%205.50.22%E2%80%AFp.m..png)

### 7.1 "Enviar Ticket de Cita" (El Resumen Veloz)
Toca el **botón 1**. Esto hará brincar automáticamente al chat (es posible que te pregunte cómo deseas abrirlo):
![Apertura WhatsApp](images/Screenshot%202026-02-23%20at%205.51.01%E2%80%AFp.m..png)
![Conectando WhatsApp](images/Screenshot%202026-02-23%20at%205.51.09%E2%80%AFp.m..png)

Este primer mensaje es intencionalmente muy corto, preciso y va directo al grano comunicando **fecha, hora y servicio**. Su función vital es facilitar que la usuaria lo lea vertical y asertivamente rápido, lo que aumenta altamente la probabilidad de recibir confirmación, o lo contrario, si hay un error humano en el día/hora seleccionada, lo detecte de inmediato al ver la placa.
Envíalo inmediatamente:
![Mensaje Ticket Cargado](images/Screenshot%202026-02-23%20at%205.51.16%E2%80%AFp.m..png)
![Mensaje Ticket Enviado](images/Screenshot%202026-02-23%20at%205.51.38%E2%80%AFp.m..png)

### 7.2 "Enviar Bienvenida y Ubicación" (El Formal)
**Instrucción Fundamental:** Una vez que lograste verificar el envío anterior y sobre todo observar que cayeron las **dos palomitas** de entrega (si se colorean azules significa "leído", ¡muchísimo mejor!), debes proceder de inmediato al dar toque firme al **botón 2**.

Este contendrá el clásico mensaje decorativo dándole toda la formal Bienvenida de la marca Carlota & Camila, agradecimiento por confiar, y lo más solicitado y útil de forma práctica: un enlace preciso a las ubicaciones del salón (Google Maps).
![Mensaje Bienvenida Cargado](images/Screenshot%202026-02-23%20at%205.52.02%E2%80%AFp.m..png)
![Mensaje Bienvenida Enviado](images/Screenshot%202026-02-23%20at%205.52.15%E2%80%AFp.m..png)

*(Importante: Tras finalizar y enviar exitosamente aquellos textos automatizados, puedes simplemente cerrar esas pestañas auxiliares de WhatsApp para mantener en orden y despejada tu área principal).*

---

## 8. Mensajes de Respaldo por Falla Técnica
En el área inferior de la misma ventana de éxito existen recuadros identificados como **Mensajes Alternativos de Respaldo**.
Sabemos que entre computadoras particulares, configuraciones del navegador o bloqueadores de pop-ups integrados, algún botón automatizado de WhatsApp en muy escasas ocasiones podría fallar y ni siquiera abrir o no arrastrar el texto. 
Esa es la principal intención de contar y ver la caja de textos fijos en frente: 
Si te falla la apertura, simplemente haz clic allí, copias el texto completo, te mudas directamente hacia tu propia ventana de WhatsApp Web y lo pegas manualmente sobre la pestaña del cliente respectivo para ser enviado, logrando que el flujo sea siempre de absoluta fiabilidad y nula espera técnica.

![Mensajes de apoyo con textos manuales listos](images/Screenshot%202026-02-23%20at%205.50.34%E2%80%AFp.m..png)

---

## 9. Terminación: Botón Regresar (Alistando Siguiente Cita)
Tras emitir ambos mensajes por WhatsApp y quedar completamente servida la cita, dale clic a tu ventanita formal al botón final que reza **"Regresar al Formulario"**.
Esto hará su trabajo terminando la memoria visual y limpiando tu formulario en blanco de inicio de etapa uno, permitiendo dejarlo plenamente reactivado de inmediato predispuesto hacia la recepción de aquel que viene luego.

![Botón Regresar Formulario](images/Screenshot%202026-02-23%20at%205.52.29%E2%80%AFp.m..png)
*(O su equivalente botón gris final)*
![Botón Regresar Formulario Inferior](images/Screenshot%202026-02-23%20at%205.50.40%E2%80%AFp.m..png)

![Formulario Restablecido y Limpio](images/Screenshot%202026-02-23%20at%205.45.39%E2%80%AFp.m..png)

---
*Fin de la guía oficial. C&C Team.*
