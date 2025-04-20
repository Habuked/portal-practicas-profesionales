# Requisitos Funcionales y No Funcionales

## ✅ Requisitos Funcionales

Los requisitos funcionales describen las capacidades y comportamientos específicos que el sistema debe tener para cumplir con sus objetivos. En el contexto del proyecto y en relación al caso de estudio del sistema implementado por la Universidad del Magdalena, se identifican los siguientes:

### Funcionalidades Principales

- **Gestión de usuarios:** Registro, inicio de sesión y asignación de roles (estudiante, empresa, coordinador, administrador).
- **Gestión de perfiles:** Completar y editar información académica, profesional y empresarial.
- **Autenticación y control de acceso:** Cada usuario debe iniciar sesión con credenciales válidas, y solo acceder a funcionalidades permitidas según su rol.
- **Publicación de ofertas:** Las empresas crean y gestionan convocatorias con detalles del perfil requerido.
- **Postulación a prácticas:** Los estudiantes pueden postularse a ofertas y subir documentos.
- **Seguimiento del proceso:** Control de etapas: pre-práctica, práctica activa y cierre.
- **Gestión documental:** Subida, validación y descarga de documentos clave (convenios, informes, etc.).
- **Notificaciones automáticas:** Avisos a los usuarios sobre cambios, aprobaciones y vencimientos.
- **Reportes y estadísticas:** Generación de informes para evaluación institucional.

### Tabla de Requerimientos Funcionales

| Código  | Requerimiento Funcional                              |
|---------|-------------------------------------------------------|
| RF001   | Escoger el tipo de usuario.                           |
| RF002   | Identificar y registrar orden de trabajo.             |
| RF003   | Autenticar como administrador.                        |
| RF004   | Revisar postulaciones a tratar.                       |
| RF005   | Autenticar como estudiante.                           |
| RF006   | Escoger postulación práctica profesional.             |
| RF007   | Visualizar información de la empresa.                 |
| RF008   | Visualizar lista de postulaciones.                    |
| RF009   | Recibir notificación de postulaciones.                |
| RF010   | Buscar información de un usuario.                     |
| RF011   | Actualizar información de un usuario.                 |
| RF012   | Eliminar un usuario.                                  |
| RF013   | Registro administrador.                               |
| RF014   | Registro estudiante.                                  |
| RF015   | Registro empresa.                                     |
| RF016   | Registro Coordinador / Tutor.                         |

---

## 🔒 Requisitos No Funcionales

Los requisitos no funcionales determinan cómo debe comportarse el sistema y qué características de calidad debe tener para ser eficiente, usable y seguro:

- **Usabilidad:** Interfaz intuitiva y fácil de usar para todos los perfiles.
- **Seguridad:** Acceso por roles, cifrado de contraseñas y protección de datos.
- **Disponibilidad:** Acceso continuo (24/7), con mínimo 99% de tiempo activo.
- **Escalabilidad:** Capacidad de crecer sin afectar el rendimiento.
- **Rendimiento:** Respuesta rápida y soporte para múltiples usuarios simultáneamente.
- **Compatibilidad:** Funciona en distintos navegadores y dispositivos (responsive).
- **Mantenibilidad:** Código modular, documentado y fácil de actualizar.

---

## 🧭 Priorización de Requisitos Funcionales

| Prioridad         | Código  | Descripción                          |
|-------------------|---------|--------------------------------------|
| Must Have         | RF001   | Escoger el tipo de usuario.          |
| Must Have         | RF002   | Generar clave.                       |
| Must Have         | RF005   | Autenticar como estudiante.          |
| Must Have         | RF003   | Autenticar como empresa.             |
| Must Have         | RF016   | Autenticar como administrador.       |
| Must Have         | RF011   | Agendar prácticas profesionales.     |
| Should Have       | RF004   | Revisar postulaciones.               |
| Should Have       | RF006   | Escoger especialidad para prácticas. |
| Should Have       | RF007   | Visualizar información de la empresa.|
| Should Have       | RF008   | Escoger fecha para prácticas.        |
| Should Have       | RF010   | Comprobar disponibilidad de fechas.  |
| Could Have        | RF012   | Verificar prácticas vigentes.        |
| Could Have        | RF013   | Visualizar lista de prácticas.       |
| Could Have        | RF014   | Anular prácticas agendadas.          |
| Could Have        | RF015   | Recibir notificación de prácticas.   |
| Won't Have        | RF017   | Administrar usuarios.                |
| Won't Have        | RF018   | Buscar información de un usuario.    |
| Won't Have        | RF019   | Actualizar información de un usuario.|
| Won't Have        | RF020   | Eliminar un usuario.                 |

---

## 📌 Casos de Uso Principales

### 👩‍🎓 Estudiante

**Descripción:** Usuario que desea postularse a ofertas de prácticas profesionales.

**Interacciones:**

- Escoger el tipo de usuario.
- Generar clave.
- Autenticar como estudiante.
- Escoger especialidad y fecha para prácticas.
- Agendar prácticas profesionales.
- Verificar y visualizar prácticas vigentes.
- Anular prácticas.
- Recibir notificaciones.

---

### 🏢 Empresa u organización

**Descripción:** Usuario que publica ofertas de prácticas y revisa postulaciones.

**Interacciones:**

- Escoger tipo de usuario.
- Generar clave.
- Autenticarse como empresa.
- Publicar ofertas.
- Revisar postulaciones.
- Visualizar información de los postulantes.
- Comprobar disponibilidad.

---

### 🎓 Coordinador Académico o Tutor

**Descripción:** Usuario que supervisa y coordina las prácticas profesionales de los estudiantes.

**Interacciones:**

- Escoger tipo de usuario.
- Generar clave.
- Autenticarse como coordinador.
- Revisar y aprobar postulaciones.
- Supervisar progreso.
- Proporcionar retroalimentación.

---

### 🛠️ Administrador del sistema

**Descripción:** Usuario que gestiona y administra usuarios y datos del sistema.

**Interacciones:**

- Escoger tipo de usuario.
- Generar clave.
- Autenticarse como administrador.
- Administrar usuarios.
- Buscar, actualizar o eliminar información de usuarios.

---

**Autor:** Luis Ludena
