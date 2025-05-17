### Documentación casos de Uso
## Portal de prácticas profesionales: Plataforma donde empresas publican ofertas de prácticas y estudiantes postulan. Incluye gestión de procesos, estados y documentos.
# Caso de uso #1

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Perfil completo<br>- Documentos cargados<br>- Ofertas disponibles        |
| **Poscondición**     | Postulación registrada y visible para la empresa                           |
| **Autor**            | Luis                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Enviar solicitudes a ofertas de prácticas profesionales.                  |
| **Resumen**          | El estudiante selecciona una oferta, revisa requisitos y envía su aplicación.<br>El sistema valida que cumpla con los criterios. |

---

# Caso de uso #2

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Módulo activo                                       |
| **Poscondición**     | Documentos almacenados y asociados al perfil                              |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Subir archivos requeridos (CV, certificados, etc.).                        |
| **Resumen**          | El estudiante selecciona archivos desde su dispositivo y los carga al sistema, que verifica formato y tamaño. |

---

# Caso de uso #3

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada                                                          |
| **Poscondición**     | Perfil actualizado con nueva información                                   |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Actualizar información personal/académica.                                 |
| **Resumen**          | Edición de datos personales, formación y habilidades.                      |

---

# Caso de uso #4

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Postulaciones existentes                            |
| **Poscondición**     | Estado de postulaciones visible                                            |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Consultar estado de postulaciones enviadas.                                |
| **Resumen**          | El sistema actualiza automáticamente los estados y notifica al estudiante sobre cambios en el estado de postulación, solicitudes de información adicional, invitaciones a entrevistas y resultados finales de selección. |

---

# Caso de uso #5

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Evaluaciones completadas                            |
| **Poscondición**     | Evaluaciones disponibles para consulta                                     |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Revisar evaluaciones de desempeño.                                         |
| **Resumen**          | El sistema permite al estudiante visualizar evaluaciones con confidencialidad, validación institucional, sincronización con el expediente académico y disponibilidad multiplataforma (web/móvil). |

---

# Caso de uso #6

| **Actor(es)**        | Estudiante                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Perfil completo                                     |
| **Poscondición**     | Documento generado para descarga                                           |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Generar informe o constancias-email.                                       |
| **Resumen**          | Incluye historial de documentos emitidos con fecha, tipo y destinatario. Los documentos quedan registrados en el expediente académico del estudiante. |

---

# Caso de uso #7

| **Actor(es)**        | Empresa                                                                     |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Postulaciones recibidas                             |
| **Poscondición**     | Estado actualizado en el sistema                                           |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Aprobar/rechazar postulaciones.                                            |
| **Resumen**          | El proceso incluye confirmación en dos pasos para cambios de estado definitivos (aprobación/rechazo final). Todos los cambios quedan registrados con marca de tiempo y usuario responsable. |

---

# Caso de uso #8

| **Actor(es)**        | Empresa                                                                     |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Permisos válidos                                    |
| **Poscondición**     | Oferta publicada/actualizada                                              |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Crear y editar ofertas de prácticas.                                       |
| **Resumen**          | La empresa accede al módulo de ofertas donde puede publicar nuevas ofertas, gestionar ofertas existentes y visualizar postulaciones. El sistema valida campos obligatorios y notifica a estudiantes cuando se publican nuevas ofertas. |

---

# Caso de uso #9

| **Actor(es)**        | Empresa                                                                     |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión iniciada<br>- Documentos cargados                                 |
| **Poscondición**     | Documentos marcados como válidos/inválidos                                 |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Verificar autenticidad de documentos.                                      |
| **Resumen**          | El representante de la empresa revisa documentos subidos por el estudiante (CV, certificados, identificación) y puede validar, rechazar o solicitar correcciones. |

---

# Caso de uso #10

| **Actor(es)**        | Todos los Usuarios                                                          |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Credenciales válidas (para login)<br>- Datos completos (para registro)    |
| **Poscondición**     | Usuario autenticado/registrado                                             |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Acceso al sistema.                                                         |
| **Resumen**          | Para inicio de sesión: el usuario ingresa credenciales y el sistema verifica su identidad. Para registro: nuevos usuarios completan un formulario con datos personales y documentos. Incluye recuperación de contraseña mediante email. |

---

# Caso de uso #11

| **Actor(es)**        | Sistema                                                                     |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Credenciales ingresadas                                                  |
| **Poscondición**     | Acceso concedido o denegado                                                |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Verificar identidad de usuarios.                                           |
| **Resumen**          | El sistema valida usuario/contraseña contra la base de datos y permite o niega el acceso. |

---

# Caso de uso #12

| **Actor(es)**        | Administrador                                                               |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión con permisos de administrador                                     |
| **Poscondición**     | Roles y permisos actualizados                                              |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Administrar privilegios del sistema.                                       |
| **Resumen**          | El administrador asigna/edita roles (estudiante, empresa, coordinador) y sus permisos. |

---

# Caso de uso #13

| **Actor(es)**        | Sistema                                                                     |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Usuario autenticado                                                      |
| **Poscondición**     | Acceso restringido según privilegios                                       |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Limitar funciones por tipo de usuario.                                     |
| **Resumen**          | El sistema redirige/filtra opciones de menú según el rol del usuario logueado. |

---

# Caso de uso #14

| **Actor(es)**        | Administrador                                                               |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión admin<br>- Parámetros definidos                                   |
| **Poscondición**     | Ajustes guardados en base de datos                                         |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Personalizar comportamiento del sistema.                                   |
| **Resumen**          | Configuración de plazos para postulaciones, formatos de documentos, etc.   |

---

# Caso de uso #15

| **Actor(es)**        | Administrador                                                               |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión admin<br>- Errores registrados                                    |
| **Poscondición**     | Problemas resueltos y sistema estable                                      |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Mantener estabilidad del sistema.                                          |
| **Resumen**          | Visualización de logs, diagnóstico y corrección de fallos técnicos.        |

---

# Caso de uso #16

| **Actor(es)**        | Administrador/Coordinador                                                   |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión con permisos<br>- Datos existentes                                |
| **Poscondición**     | Documento descargable (PDF/Excel)                                          |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Extraer información consolidada.                                           |
| **Resumen**          | Generación de reportes estadísticos: postulaciones por empresa, evaluaciones, etc. |

---

# Caso de uso #17

| **Actor(es)**        | Coordinador/Tutor                                                           |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Estudiante en práctica<br>- Datos de seguimiento                         |
| **Poscondición**     | Evaluación registrada y visible                                             |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Calificar progreso del estudiante.                                         |
| **Resumen**          | Ingreso de notas por competencias, observaciones y firma digital.           |

---

# Caso de uso #18

| **Actor(es)**        | Administrador                                                               |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Sesión admin<br>- Datos fiscales validados                               |
| **Poscondición**     | Empresa habilitada para publicar                                           |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Dar de alta nuevas empresas colaboradoras.                                 |
| **Resumen**          | Validación de RUC, datos de contacto y convenio institucional.             |

---

# Caso de uso #19

| **Actor(es)**        | Coordinador                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Precondición**     | - Práctica aprobada<br>- Tutores disponibles                               |
| **Poscondición**     | Tutor asignado y notificado                                                |
| **Autor**            | LUIS                                                                       |
| **Fecha**            | 29-abr-25                                                                 |
| **Versión**          | 1.0                                                                       |
| **Actualizado por**  | N/D                                                                        |
| **Fecha actualización** | --                                                                      |
| **Propósito**        | Designar supervisor académico.                                             |
| **Resumen**          | Vinculación de tutor-coordinador-estudiante según especialidad.            |
