
### Diagrama de Clases 
El diagrama de clases es una herramienta creada para mostrar el diseño de una aplicación orientada a objetos donde se presentan las clases y sus asociaciones de manera gráfica. En UML las clases se la representa con un rectángulo que posee tres divisiones, la primera contiene el título de la clase, la segunda donde se listan todos sus atributos y finalmente la tercera división contienen los métodos que esta clase realiza 
# Explicación del Diagrama:
1.	Usuario: Clase base con atributos comunes (autenticación, roles).
2.	Estudiante: Hereda de Usuario. Gestiona postulaciones, documentos y seguimiento.
3.	Empresa: Hereda de Usuario. Publica ofertas y valida documentos.
4.	Oferta: Entidad central para prácticas profesionales, con estados y publicación.
5.	Postulación: Relaciona Estudiante y Oferta, almacena documentos y estados.
6.	Documento: Adjunto a postulaciones (CV, cartas, certificados).
7.	Notificación: Envía alertas a usuarios sobre cambios de estado o postulaciones.
8.	Administrador: Gestiona reportes, errores y roles del sistema.
# Relaciones Clave:
•	Herencia: Usuario es padre de Estudiante, Empresa y Administrador/tutor 
•	Asociaciones:
o	Un estudiante puede tener múltiples postulaciones.
o	Una oferta recibe múltiples postulaciones.
o	Las postulaciones incluyen documentos.
o	Las empresas publican múltiples ofertas.
o	Un tutor supervisa a estudiante y realizar evaluación 

<br>

![image](https://github.com/user-attachments/assets/21cef384-a214-4c0a-b54a-8475ea2d946d)
