# Historias de usuario

Formato: Como / Quiero / Para + Criterios de aceptación + Prioridad + Estimación.
La estimación (puntos de historia) la define el equipo en la reunión de planificación.

---

## US-01 — Registro de usuario
**Como** afiliado nuevo
**Quiero** registrarme en la app con mis datos básicos
**Para** poder utilizar la plataforma

### Criterios de aceptación
- El usuario debe ingresar nombre completo.
- Debe ingresar correo electrónico.
- Debe ingresar contraseña.
- El sistema debe validar que los datos no estén vacíos.
- El usuario debe recibir confirmación del registro.

**Prioridad:** Alta
**Estimación:** [Por definir]

---

## US-02 — Inicio de sesión
**Como** afiliado registrado
**Quiero** iniciar sesión con mi usuario y contraseña
**Para** acceder a mi cuenta de forma segura

### Criterios de aceptación
- El sistema debe validar usuario y contraseña.
- Debe mostrar mensaje de error si las credenciales son incorrectas.
- Debe redirigir al inicio de la app tras un login exitoso.

**Prioridad:** Alta
**Estimación:** [Por definir]

---

## US-03 — Recuperar contraseña
**Como** afiliado
**Quiero** recuperar mi contraseña si la olvido
**Para** no perder el acceso a mi cuenta

### Criterios de aceptación
- El sistema debe permitir solicitar recuperación con el correo registrado.
- Debe enviarse un enlace o código de verificación.
- El usuario debe poder definir una nueva contraseña.

**Prioridad:** Alta
**Estimación:** [Por definir]

---

## US-04 — Actualizar datos personales
**Como** afiliado
**Quiero** actualizar mis datos personales
**Para** mantener mi información de contacto correcta

### Criterios de aceptación
- El usuario debe poder editar nombre, teléfono y correo.
- El sistema debe validar el formato de los datos ingresados.
- Debe confirmarse el guardado exitoso de los cambios.

**Prioridad:** Alta
**Estimación:** [Por definir]

---

## US-05 — Buscar especialidad o médico
**Como** afiliado
**Quiero** buscar por especialidad o médico
**Para** encontrar la atención que necesito

### Criterios de aceptación
- El usuario puede buscar por nombre de especialidad.
- El usuario puede buscar por nombre de médico.
- Los resultados muestran disponibilidad de citas.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-06 — Agendar cita médica
**Como** afiliado
**Quiero** agendar una cita médica
**Para** recibir atención sin ir presencialmente a la EPS

### Criterios de aceptación
- El usuario debe seleccionar especialidad, médico y horario disponible.
- El sistema debe confirmar la cita agendada.
- Debe evitarse doble agendamiento en el mismo horario.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-07 — Reprogramar cita
**Como** afiliado
**Quiero** reprogramar una cita ya agendada
**Para** ajustarla si surge un imprevisto

### Criterios de aceptación
- El usuario debe poder ver sus citas activas.
- Debe poder elegir un nuevo horario disponible.
- El sistema debe actualizar la cita sin duplicarla.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-08 — Cancelar cita
**Como** afiliado
**Quiero** cancelar una cita
**Para** liberar el cupo si ya no la necesito

### Criterios de aceptación
- El usuario debe poder cancelar desde el listado de citas.
- El sistema debe pedir confirmación antes de cancelar.
- El cupo cancelado debe quedar disponible para otros afiliados.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-09 — Ver historial de citas
**Como** afiliado
**Quiero** ver el historial de mis citas
**Para** llevar seguimiento de mi atención médica

### Criterios de aceptación
- El usuario debe ver citas pasadas y futuras.
- Debe poder filtrar por fecha o especialidad.
- Cada registro debe mostrar estado (completada, cancelada, pendiente).

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-10 — Descargar certificado
**Como** afiliado
**Quiero** descargar certificados
**Para** presentarlos donde los necesite sin trámite presencial

### Criterios de aceptación
- El usuario debe poder seleccionar el tipo de certificado.
- El sistema debe generar el documento en formato descargable (PDF).
- El certificado debe incluir los datos del afiliado.

**Prioridad:** Media-alta
**Estimación:** [Por definir]

---

## US-11 — Solicitar autorizaciones
**Como** afiliado
**Quiero** solicitar autorizaciones desde la app
**Para** agilizar mis trámites médicos

### Criterios de aceptación
- El usuario debe poder cargar la orden médica.
- El sistema debe registrar la solicitud con un número de radicado.
- El usuario debe recibir confirmación de la solicitud.

**Prioridad:** Media-alta
**Estimación:** [Por definir]

---

## US-12 — Recibir notificaciones
**Como** afiliado
**Quiero** recibir notificaciones
**Para** no olvidar mis citas ni el estado de mis trámites

### Criterios de aceptación
- El sistema debe enviar notificación antes de cada cita.
- Debe notificar cambios de estado en autorizaciones o trámites.
- El usuario debe poder ver el historial de notificaciones.

**Prioridad:** Media-alta
**Estimación:** [Por definir]

---

## US-13 — Consultar autorizaciones
**Como** afiliado
**Quiero** consultar el estado de mis autorizaciones
**Para** saber si ya puedo continuar con mi trámite

### Criterios de aceptación
- El usuario debe ver el estado actual (pendiente, aprobada, rechazada).
- Debe poder ver la fecha de radicación.
- El sistema debe mostrar el motivo si fue rechazada.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-14 — Consultar resultados de exámenes
**Como** afiliado
**Quiero** consultar mis resultados de exámenes
**Para** conocerlos sin tener que ir a la sede

### Criterios de aceptación
- El usuario debe ver el listado de exámenes realizados.
- Debe poder abrir o descargar el resultado.
- Solo debe poder ver sus propios resultados.

**Prioridad:** Media
**Estimación:** [Por definir]

---

## US-15 — Consultar historia médica
**Como** afiliado
**Quiero** consultar mi historia médica
**Para** tener acceso a mis antecedentes y diagnósticos

### Criterios de aceptación
- El usuario debe ver un resumen de su historia médica.
- La información debe mostrarse ordenada cronológicamente.
- El acceso debe estar protegido y ser solo para el propio afiliado.

**Prioridad:** Media
**Estimación:** [Por definir]
