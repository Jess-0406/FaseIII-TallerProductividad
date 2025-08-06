# Fase III - Taller de Productividad
# 📘 Resumen Ejecutivo

Este proyecto forma parte del curso “Taller de productividad basada en herramientas tecnológicas”. Su objetivo fue aplicar herramientas tecnológicas modernas para gestionar un proyecto de desarrollo simulando un entorno real de trabajo colaborativo.

## 🛠️ Descripción

Se desarrolló una solución enfocada en integrar herramientas de productividad y colaboración como GitHub, Zube.io y Travis CI para simular un flujo de trabajo profesional con control de versiones, gestión de tareas y automatización de pruebas.

## ❗ Problema identificado

En entornos educativos o laborales donde se requiere trabajar en equipo, muchas veces se carece de un flujo estructurado para el desarrollo de software. La falta de organización, seguimiento y pruebas puede afectar la calidad y entrega del producto.

## ✅ Solución

El proyecto plantea una metodología estructurada basada en:

- Uso de ramas (`develop`, `main`, `feature/...`)
- Organización de tareas en Zube.io (integrado con GitHub)
- Automatización de validaciones básicas con Travis CI
- Arquitectura documentada y clara
- Documentación viva del proceso (README, issues, PRs)

## 🧱 Arquitectura

La arquitectura se compone de:

- **Repositorio GitHub**: Control de versiones, ramas, documentación, CI.
- **Zube.io**: Gestión de tareas ágiles (issues, milestones, boards).
- **Travis CI**: Integración continua con ejecución automática de pruebas.
- **Documentación**: Archivos `README.md`, `ARQUITECTURA.md` y otros recursos.

<img src="https://raw.githubusercontent.com/Jess-0406/FaseIII-TallerProductividad/main/arquitectura.png" alt="Arquitectura del Proyecto" width="600"/>

---

# 🗂️ Tabla de Contenidos

1. [Resumen Ejecutivo](#resumen-ejecutivo)
2. [Requerimientos](#requerimientos)
3. [Instalación](#instalación)
4. [Configuración](#configuración)
5. [Uso](#uso)
6. [Contribución](#contribución)
7. [Roadmap](#roadmap)
8. [Video de Demostración](#video-de-demostración)
9. [Acceso al Producto](#acceso-al-producto)
10. [Actividad en GitHub](#actividad-en-github)

---
## 📦 Requerimientos

Para poder ejecutar este proyecto correctamente, es necesario contar con los siguientes elementos instalados y configurados en el sistema:

### 🧰 Lenguajes y tecnologías

- **Java JDK** versión 11 o superior
- **Git** para control de versiones
- **Git Bash** (o terminal compatible con Bash)
- **Travis CI** (solo conexión con GitHub, no requiere instalación local)

### 📚 Dependencias del sistema

- Sistema operativo: Windows 10 o superior (recomendado)
- Acceso a internet para conexión con Travis CI y GitHub

### 🧱 Herramientas utilizadas

| Herramienta   | Uso principal                                     |
|---------------|---------------------------------------------------|
| Git + GitHub  | Control de versiones, ramas, pull requests        |
| Zube.io       | Gestión ágil de tareas (tarjetas, etiquetas, etc.)|
| Travis CI     | Integración continua (CI)                         |
| README.md     | Documentación del proyecto                        |
| Git Bash      | Terminal para ejecutar comandos de Git            |

> Nota: No se requiere un entorno de ejecución complejo ya que este proyecto está centrado en la gestión de flujo de trabajo y documentación.

## 🔧 Instalación
### a. ¿Cómo instalar el ambiente de desarrollo?

1. Instala las siguientes herramientas si aún no las tienes:
   - ✅ [Java JDK 11+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
   - ✅ [Git](https://git-scm.com/)
   - ✅ [Git Bash](https://gitforwindows.org/) o terminal compatible con Bash
   - ✅ Navegador web para acceso a GitHub, Zube.io y Travis CI

2. Clona el repositorio del proyecto:
   ```bash
   git clone https://github.com/Jess-0406/FaseIII-TallerProductividad.git
   cd FaseIII-TallerProductividad
   git checkout develop

3. Accede a las herramientas necesarias:
        Zube.io → autenticación con tu cuenta de GitHub
        Travis CI → sincronizado automáticamente con el repositorio GitHub

b. ¿Cómo ejecutar pruebas manualmente?
    Este proyecto no tiene pruebas automatizadas de software, pero sí pruebas de flujo de trabajo.

Para validar el correcto funcionamiento del proyecto:
    Crea un Issue en GitHub o en Zube.io y vincúlalo a una tarea.
    Realiza un commit en la rama feature/... y verifica que Travis CI inicie el proceso de validación.
    Abre un Pull Request hacia la rama develop.
    Verifica en Travis CI que la integración se haya completado sin errores.
    Confirma que la documentación en README.md y los enlaces funcionen correctamente.

c. ¿Cómo implementar la solución en producción en un ambiente local o en la nube como Heroku?
Este proyecto no requiere despliegue en un servidor porque su enfoque está en la documentación y simulación de flujo de trabajo.

Sin embargo, puedes hacer lo siguiente:
    📄 Publicar la documentación en GitHub Pages (opcional)
    📚 O bien, usar ReadTheDocs.io para mostrar documentación estilo profesional
    
## ⚙️ Configuración
## 🧩 Configuración del producto

Este proyecto no contiene archivos ejecutables, pero sigue una estructura organizada basada en control de versiones y flujo de trabajo colaborativo:
    main: Rama principal con versión estable.
    develop: Rama de desarrollo activo.
    feature/*: Ramas para nuevas funcionalidades.
    README.md: Archivo de documentación principal.
    .travis.yml: Archivo (opcional) para Travis CI que define las validaciones automáticas.

    Si aún no se ha creado el archivo .travis.yml, puede ser generado posteriormente como parte de la automatización CI.

## ⚙️ Configuración de los requerimientos
A continuación, se indican los pasos para configurar correctamente las herramientas necesarias:

    Git: Configurar nombre y correo del usuario:
git config --global user.name "Tu Nombre"
git config --global user.email "tucorreo@ejemplo.com"

Java JDK 11+: Validar que está correctamente instalado:
    java -version

    Travis CI: Debe estar conectado con tu cuenta de GitHub. No requiere instalación local, pero sí estar activado desde su sitio web.
    Se recomienda verificar que las credenciales y configuraciones estén activas antes de realizar pruebas o integraciones.

## 🧑‍💻 Uso
## 📘 Guía para usuarios finales
Este proyecto no es una aplicación ejecutable tradicional, sin embargo, los usuarios finales pueden consultar y navegar los distintos recursos para entender cómo se estructura y gestiona un proyecto utilizando herramientas colaborativas.

Los usuarios pueden:
    Explorar la documentación en el archivo README.md.
    Consultar el historial y estructura de ramas (main, develop, feature/...).
    Revisar los issues y tareas dentro de Zube.io.
    Visualizar los pull requests y su integración con Travis CI.
    No se requiere instalación local para visualizar el contenido del proyecto.

## 🛠️ Guía para administradores del proyecto
Los administradores deben supervisar y asegurar el correcto funcionamiento del flujo de trabajo definido. Para ello, deben realizar las siguientes acciones:

    1.Revisar tareas e issues:
        Desde el tablero de Zube.io
        O directamente en la sección de Issues del repositorio en GitHub.

    2.Gestionar ramas y Pull Requests:
        Asegurar que todo cambio provenga de una rama feature/....
        Aprobar y hacer merge solo después de pasar revisiones y validaciones.

    3.Verificar Travis CI:
        Confirmar que Travis CI ejecuta correctamente los procesos automáticos al realizar push o PR.
        Corregir cualquier error de integración.

    4.Mantener la documentación actualizada:
        Validar que el archivo README.md esté actualizado con cada nueva funcionalidad.
        Incluir referencias o enlaces a la Wiki si se utiliza.

## 🤝 Contribución
## 📌 Guía para contribuir al proyecto
Este proyecto está abierto a mejoras en su documentación, organización de tareas o procesos de integración continua. Si deseas contribuir, sigue estos pasos:

## 1.Clona el repositorio:
    git clone https://github.com/Jess-0406/FaseIII-TallerProductividad.git

## 2.Crea una nueva rama para tu funcionalidad o mejora:
git checkout -b feature/tu-nombre-de-rama

## 3.Realiza tus cambios y haz commit:
git add .
git commit -m "Descripción breve del cambio realizado"

## 4.Sube tu rama al repositorio remoto:
    git push origin feature/tu-nombre-de-rama

## 5.Abre un Pull Request desde GitHub:
        Describe brevemente el objetivo del cambio.
        Relaciona el PR con un issue si aplica.

## 6.Espera la revisión del Pull Request y aprobación del merge.

## 📋 Buenas prácticas
    Usa nombres descriptivos para tus ramas: feature/nombre, fix/nombre, etc.
    Mantén tu rama actualizada con develop si estás trabajando en paralelo.
    Escribe mensajes de commit claros y concisos.
    Si modificas documentación, verifica que no haya errores de formato Markdown.

## 🗺️ Roadmap
A continuación, se detallan las posibles mejoras y funcionalidades futuras que podrían implementarse en este proyecto para fortalecer su valor educativo y práctico:

## 🔮 Funcionalidades futuras
    Incorporar plantillas reutilizables para documentación (README.md, CONTRIBUTING.md, etc.).
    Agregar un archivo .travis.yml completamente funcional para validar formatos y convenciones.
    Crear una Wiki técnica con ejemplos paso a paso de:
        Creación de ramas
        Uso de Zube.io
        Flujo de trabajo colaborativo

    Incluir un módulo adicional para automatizar reportes desde GitHub (por ejemplo, usando GitHub Actions).
    Expandir el proyecto a una aplicación simple (Java o Web) para que Travis CI valide código funcional.
    Publicar la documentación en GitHub Pages o ReadTheDocs.io para facilitar su consulta externa.

## 💡 Ideas adicionales
    Implementar un sistema de retroalimentación para los colaboradores del repositorio.
    Agregar etiquetas automáticas en los Pull Requests con base en su tipo (feature, bugfix, docs, etc.).
    Este roadmap es abierto. Si deseas proponer ideas nuevas, crea un Issue en el repositorio y participa con un Pull Request.

## 🎥 Video de Demostración
A continuación, se presenta un video donde se muestran los principales componentes del proyecto, cumpliendo con los requerimientos establecidos:
    Explicación de la estructura del repositorio
    Flujo de trabajo utilizando ramas, issues y pull requests
    Uso de Zube.io para la gestión de tareas
    Revisión de Travis CI (si aplica)
    Recorrido por la documentación del proyecto

## 🔗 Ver video de demostración
    Reemplaza el enlace con la URL de tu video en YouTube, Google Drive, OneDrive o la plataforma institucional.

## 🌐 Acceso al Producto
El proyecto no es una aplicación ejecutable, pero puedes acceder a toda su estructura, documentación y flujo de trabajo en el siguiente repositorio:

## 🔗 Repositorio en GitHub:
https://github.com/Jess-0406/FaseIII-TallerProductividad
