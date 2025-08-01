
# ✅ Informe Final – Entrega del Proyecto

## 🎯 Nombre del proyecto
**Fase III – Taller de productividad basada en herramientas tecnológicas**

## 👩‍💻 Integrante responsable
**Jessica Gaytán Riv.** – [Jess-0406 en GitHub](https://github.com/Jess-0406)

---

## 🧩 Descripción general del trabajo realizado

Este proyecto consistió en aplicar herramientas tecnológicas modernas para gestionar un proyecto de desarrollo utilizando principios reales de productividad, tales como control de versiones, gestión de tareas, trabajo colaborativo y automatización mediante integración continua.

---

## 🔧 Herramientas utilizadas

| Herramienta     | Uso principal |
|-----------------|---------------|
| **Git y GitHub** | Control de versiones, branches, pull requests |
| **Zube**         | Gestión ágil de tareas (tarjetas, etiquetas, prioridades, milestones) |
| **Travis CI**    | Validación automática del repositorio (Integración Continua) |
| **Markdown**     | Documentación (`README.md`, `ARQUITECTURA.md`) |
| **Bash (Git Bash)** | Línea de comandos para control y configuración de Git |

---

## 📝 Actividades realizadas

### 1. ✅ Creación y configuración del repositorio en GitHub

- Se creó un repositorio público:  
  [`FaseIII-TallerProductividad`](https://github.com/Jess-0406/FaseIII-TallerProductividad)
- Se configuró el archivo `.gitignore` y el `README.md`.
- Se inicializó con ramas principales: `main` (para producción) y `develop` (para trabajo activo).

---

### 2. ✅ Integración de GitHub con Zube

- Se vinculó exitosamente el repositorio a [Zube.io](https://zube.io).
- Se organizaron **issues** y tarjetas desde GitHub que automáticamente aparecen en Zube.
- Se asignaron tareas a **milestones**: `Beta` y `GA`.

---

### 3. ✅ Gestión de tareas y etiquetado

- Se crearon tarjetas con prioridades y etiquetas (`documentación`, `formulario`, `arquitectura`, etc.).
- Se movieron a columnas del tablero de Zube conforme avanzaban (To Do → Doing → Review → Done).

---

### 4. ✅ Uso de ramas y trabajo con Pull Requests (PRs)

- Se trabajó siguiendo la convención de ramas por feature (`feature/nombre`), como:
  - `feature/contact-form`
  - `feature/arquitectura`
- Para cada funcionalidad, se creó:
  1. Un archivo (por ejemplo, `formulario.txt` y `ARQUITECTURA.md`)
  2. Un **commit**
  3. Un **push** hacia GitHub
  4. Un **Pull Request (PR)** hacia `develop`
- Se describieron los PRs y se referenciaron tareas de Zube con `#número`.

---

### 5. ✅ Configuración de Travis CI (Integración Continua)

- Se creó el archivo `.travis.yml` con una configuración básica para validar el estado del repositorio:
```yaml
language: generic

script:
  - echo "✅ Travis CI está funcionando correctamente."
```
- Se conectó Travis CI con GitHub y se verificó que el **build pasara exitosamente** cada vez que se subían cambios a una rama o se abría un PR.

---

### 6. ✅ Documentación de la arquitectura del proyecto

- Se creó el archivo `ARQUITECTURA.md` con una descripción detallada de:
  - Los componentes usados (Frontend, control de versiones, CI, gestión de tareas)
  - El flujo de desarrollo colaborativo
- Además, se generó y subió una **imagen digital con el diagrama visual de arquitectura**, representando el flujo de trabajo y herramientas conectadas.

---

## 🐞 Dificultades y errores enfrentados

Durante el desarrollo del proyecto se presentaron algunos problemas que se resolvieron exitosamente:

1. **Error de identidad en Git:**  
   Al realizar el primer `commit`, se mostró el mensaje:  
   `Author identity unknown`.  
   **Solución:** Se configuró el nombre y correo con `git config --global`.

2. **Confusión con ramas:**  
   Inicialmente se trató de hacer `checkout develop` fuera del repositorio, generando el error:  
   `fatal: not a git repository`.  
   **Solución:** Se accedió correctamente a la carpeta del proyecto.

3. **Travis CI no mostraba builds:**  
   Al principio aparecía el mensaje "No builds for this repository".  
   **Solución:** Se realizó un nuevo `commit` al archivo `.travis.yml` para activar el primer build.

4. **Edición con nano en Bash:**  
   Hubo confusión al guardar cambios usando el editor `nano`.  
   **Solución:** Se explicó cómo salir con `Ctrl + O` para guardar y `Ctrl + X` para salir.

---

## ✅ Resultado Final

El proyecto simula de forma realista el flujo de desarrollo colaborativo usando herramientas modernas y prácticas profesionales. Se logró:

- Automatizar el proceso de validación con Travis CI
- Organizar y visualizar tareas con Zube
- Crear ramas por feature, abrir PRs, y trabajar en un entorno de Git colaborativo
- Documentar adecuadamente el proceso y la arquitectura

---

## 🔗 Enlaces importantes

- **Repositorio GitHub:**  
  https://github.com/Jess-0406/FaseIII-TallerProductividad

- **Pull Requests:**  
  https://github.com/Jess-0406/FaseIII-TallerProductividad/pulls

- **Zube:**  
  https://zube.io (requiere cuenta vinculada)
