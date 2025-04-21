# Identificación de Actores y Funcionalidades

Para el correcto desarrollo del portal de prácticas profesionales, es fundamental identificar a los actores clave que intervienen en el proceso y definir con claridad las funcionalidades que cada uno debe cumplir dentro del sistema. 

Esta identificación permite establecer los flujos de interacción y las responsabilidades de cada perfil de usuario, garantizando un diseño estructurado y coherente con la realidad institucional.

---

## Actores del sistema y sus funcionalidades

| **Actor**                       | **Funcionalidades** |
|--------------------------------|----------------------|
| **Estudiante**                 | - Registro y edición del perfil personal y académico. <br> - Consulta y postulación a ofertas activas de prácticas. <br> - Carga de documentos (CV, carta de motivación, convenio, informes). <br> - Seguimiento del estado de cada postulación y práctica. <br> - Visualización de evaluaciones o retroalimentación. |
| **Empresa u organización**     | - Registro de datos institucionales y del área oferente. <br> - Publicación, edición y cierre de ofertas de prácticas. <br> - Consulta de postulantes y gestión de entrevistas. <br> - Validación de asistencia, informes y evaluación final. <br> - Emisión de cartas de aceptación. <br> - Cambio de estado del proceso (preseleccionado, entrevista, aceptado). |
| **Coordinador Académico / Tutor** | - Revisión de documentos cargados por los estudiantes. <br> - Validación de convenios firmados. <br> - Evaluación del desempeño del estudiante. <br> - Coordinación con tutores internos y externos. <br> - Reportes de avance y cierre académico de la práctica. |
| **Administrador del sistema**  | - Gestión de usuarios y roles (estudiantes, empresas, coordinadores). <br> - Configuración del sistema (ciclos de práctica, estados, documentos requeridos). <br> - Monitoreo del uso del sistema y solución de errores técnicos. <br> - Generación de estadísticas y reportes institucionales. |

> **Autor.** Luis Ludena, Jazmin Diaz, Javier Sanchez

---

## Funcionalidades del Sistema

| **Funcionalidad**                             | **Estudiante** | **Empresa** | **Administrador** |
|-----------------------------------------------|:--------------:|:-----------:|:-----------------:|
| Registro e inicio de sesión                   | ✅             | ✅          | ✅                |
| Crear y editar perfil                         | ✅             | ✅          | ✅                |
| Publicar ofertas de prácticas                 | ❌             | ✅          | ✅                |
| Postular a ofertas                            | ✅             | ❌          | ❌                |
| Gestión del estado del proceso de práctica    | ✅             | ✅          | ✅                |
| Carga de documentos (CV, cartas, informes)    | ✅             | ✅          | ✅                |
| Revisión y validación de documentos           | ❌             | ✅          | ✅                |
| Generación de reportes                        | ❌             | ❌          | ✅                |
| Notificaciones por correo o plataforma        | ✅             | ✅          | ✅                |

---

**Autor:** *Jazmin Diaz*