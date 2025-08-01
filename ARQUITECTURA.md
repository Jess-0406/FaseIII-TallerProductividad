# Arquitectura de la Aplicación

## Componentes principales

- **Frontend:** HTML, CSS y JavaScript (formulario de contacto).
- **Backend:** No aplica (por ahora es solo frontend).
- **Repositorio:** GitHub – https://github.com/Jess-0406/FaseIII-TallerProductividad
- **Control de versiones:** Git y GitHub, utilizando ramas (`develop`, `feature/...`, `master`)
- **Gestión de tareas:** Zube integrado con GitHub
- **Integración continua:** Travis CI configurado para validar el código

## Flujo de desarrollo

1. Las tareas se crean y gestionan en Zube.
2. Para cada tarea se crea un branch desde `develop`.
3. Se desarrolla la funcionalidad y se sube a GitHub.
4. Se abre un Pull Request hacia `develop`.
5. Travis CI ejecuta validación automática del código.
6. Al aprobarse, se hace merge a `develop`.
7. La rama `master` se reserva para la versión final estable (GA).



