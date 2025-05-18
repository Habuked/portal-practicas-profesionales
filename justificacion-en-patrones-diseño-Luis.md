# Justificación de Patrones de Diseño

## 1. Introducción

El *Portal de Prácticas Profesionales* es una plataforma digital diseñada para conectar empresas y estudiantes, facilitando la publicación de ofertas de prácticas, la petición a estas y la gestión integral de documentos en procesos asociados.

Dada la complejidad de integrar múltiples subsistemas (autenticación, documentos, notificaciones) y garantizar escalabilidad, mantenibilidad y seguridad, se emplearon **patrones de diseño estructurales**. Estos permiten organizar componentes y relaciones entre objetos de manera eficiente, resolviendo problemas recurrentes en arquitecturas de software.

## 2. Objetivos

- Detallar la implementación de patrones estructurales en el portal.
- Demostrar cómo estos patrones resuelven retos técnicos específicos.
- Evaluar su impacto en escalabilidad, seguridad y mantenibilidad.

## 3. Metodología

Se realizó un análisis de requisitos funcionales y no funcionales del portal, identificando los siguientes desafíos:

- **Integración heterogénea**: Compatibilidad con múltiples proveedores de almacenamiento de documentos.
- **Gestión de flujos complejos**: Procesos de postulación con etapas jerárquicas.
- **Control de acceso**: Restricciones para descarga de documentos sensibles.
- **Optimización de recursos**: Reducción de redundancias en plantillas y mensajes.

Los patrones estructurales se seleccionaron mediante un enfoque basado en casos de uso y validación técnica.

### Desarrollo Detallado de Patrones Estructurales

#### Adapter (Adaptador)

- Propósito: Convertir interfaces compatibles.
- Aplicación: Integración de APIs de Google Drive y OneDrive.
- Beneficio: Extensible a nuevos servicios.

#### Composite (Compuesto)

- Propósito: Tratar objetos individuales y composiciones de forma uniforme.
- Aplicación: Modelado de procesos de postulación con etapas simples y compuestas.
- Beneficio: Simplifica la gestión de flujos anidados.

#### Facade (Fachada)

- Propósito: Centralizar operaciones complejas.
- Aplicación:
  - Autenticación.
  - Validación de documentos.
  - Notificaciones por correo.
- Beneficio: Reduce la complejidad para usuarios y desarrolladores.

#### Proxy

- Propósito: Controlar el acceso a un objeto.
- Aplicación:
  - Verifica permisos antes de permitir descargas.
  - Seguridad: evita accesos no autorizados.
  - Optimización: carga bajo demanda de documentos grandes.

#### Flyweight (Peso Ligero)

- Propósito: Compartir datos comunes para reducir memoria.
- Aplicación: Reutilización de plantillas de documentos.
- Beneficio: Reduce el uso de memoria.

#### Bridge (Puente)

- Propósito: Desacoplar la abstracción de la implementación.
- Aplicación: Separar la lógica de las gestiones.
- Beneficio: Facilita cambios sin afectar ambas partes.

## 4. Diseño

El diseño traduce los requisitos en una representación del software que permite conocer la arquitectura, funcionalidad y calidad antes de codificar.

Es necesario sintetizar metodologías, herramientas y procedimientos de la ingeniería del software para lograr un producto de calidad.

### Características del software

- Atractivo
- Interactivo
- Fácil de usar y entendible

### Herramientas utilizadas

- Visual Studio Code
- Lucidchart, PlantUML, PlantText (para diagramas UML)
- Navegador web

> El software estará documentado para facilitar modificaciones y adaptaciones.

## 5. Propiedades Estructurales

> Este aspecto define los componentes de un sistema y cómo interactúan.

### Ejemplos

#### Postulación a una Oferta

- **Facade**: Inicia el proceso.
- **Adapter**: Valida documentos.
- **Composite**: Ejecuta etapas de validación.
- **Proxy**: Garantiza permisos para adjuntar documentos.

#### Descarga de Documentos

- **Proxy**: Verifica permisos del usuario.
- **Flyweight**: Reutiliza plantillas de descarga.

### Beneficios Generales

- Escalabilidad
- Mantenibilidad
- Seguridad
- Eficiencia

## 6. Herramientas y Tecnologías Utilizadas

### Figma

Prototipado colaborativo, con posibilidad de insertar prototipos y presentaciones.

### GitHub Actions

Automatización de despliegues continuos.

### Servicios Web

Tecnología que usa estándares y protocolos para el intercambio de datos entre aplicaciones a través de la red, permitiendo la interoperabilidad entre lenguajes.

## 7. Documentación

### Técnicas para documentar componentes

- Diagramas de casos de uso
- Diagramas de clases
- Diagramas de actividades
- Diagramas de secuencias
- Diagramas de componentes
- Diagramas de despliegue
- Diagramas de estados

### Importancia de los Diagramas de Arquitectura

Los diagramas de arquitectura representan visualmente los componentes de un sistema de software, mostrando funciones, ejecuciones e interacciones. Facilitan la toma de decisiones y mejoran la comprensión de estructuras complejas.