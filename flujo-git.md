# 🔀 Planificación de Ramas y Flujo de Trabajo Colaborativo en GitHub

## Estrategia elegida: **Git Flow**

Se ha decidido trabajar con la estrategia **Git Flow**, adaptada al entorno del proyecto y al uso de GitHub. Esta metodología permite una organización clara y controlada del desarrollo mediante el uso de diferentes tipos de ramas.

---

## 🌱 Tipos de ramas

| Rama         | Propósito                                                                 |
|--------------|---------------------------------------------------------------------------|
| `main`       | Contiene el código estable listo para producción.                         |
| `dev`        | Rama principal de desarrollo. Aquí se integran las nuevas funcionalidades antes de pasar a producción. |
| `feature/*`  | Ramas creadas a partir de `dev` para nuevas funcionalidades o tareas específicas. |
| `release/*`  | Ramas creadas desde `dev` para preparar una nueva versión estable.     |
| `hotfix/*`   | Ramas creadas desde `main` para corregir errores urgentes en producción.   |

---

## 📌 Reglas de colaboración

- **Todo cambio debe pasar por un Pull Request** (PR).
- **Cada PR debe ser revisado por al menos 2 integrante** del equipo antes de ser aprobado.
- **Los nombres de las ramas deben ser claros y descriptivos**, usando el prefijo correspondiente:
  - `feature/nombre-de-actividad-nombreColaborador` ejemplo `feature/roles-javier`
  - `hotfix/bug-visual-footer`
  - `release/v1.0.0`

---

## 🚀 Flujo de trabajo básico

1. Crear una rama desde `dev`:  
   ```bash
   git checkout dev
   git pull
   git checkout -b feature/nombre-de-la-tarea-nombreColaborador
