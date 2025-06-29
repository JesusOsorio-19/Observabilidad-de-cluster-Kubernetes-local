# Contribución de Jesus Diego Osorio Tello 

## Sprint 1

- 2025-06-25: Escribí `hooks/pre-commit` para realizar formato con black y chequeo de errores de lint con flake8 solo en archivos python, de esta manera los commits subidos al repositorio remoto seran limpios y los errores de lint disminuiran.

    >Commit: `feat(git-hooks): Añade hook pre-commit para validación de archivos python`

    Pull request grupal: Scripts de hooks #15

- 2025-06-25: Escribí `hooks/commit-msg` para que los mensajes de los commits sigan las convenciones.

    >Commit: `feat(git-hooks): Añade hook commit-msg para validación de commits siguiendo convenciones`

    Pull request grupal: Scripts de hooks #15

- 2025-06-25: Escribí `hooks/pre-push` para validar que no se puede realizar push directo a la rama main, valida que pasen los test que tengamos y por último verifica si hay diferencias entre el último commit y el anterior, y si no hay cambios muestra un mensaje informativo. 

  >Commit: `feat(hook): Añade pre-push que impide el push desde la rama main, ejecuta los test y valida que no haya cambios pendientes entre commits`

  Pull request grupal: Scripts de hooks #15

- 2025-06-25: Escribí `install_hooks.sh` que automatiza la instalación de los hooks que tenemos.

    >Commit: `feat(hook): Añade install que facilita la instalación de los hooks`

  Pull request grupal: Scripts de hooks #15 

- 2025-06-25: Escribí archivos de configuraciones iniciales.

    >Commit: `feat(bandit): Añade archivo para detectar vulnerabilidades de seguridad en código python
`

    >Commit: `feat(flake): Añade archivo para análisis de calidad de código python`

    >Commit: `feat(ignore): Añade documentación con archivos a ignorar al hacer push a nuestro repositorio remoto`

    >Commit: `feat(dependencias): Añade archivo con dependencias necesarias`

  Pull request grupal: Archivos de configuración inicial #14 

    
## Sprint 2 

- 2025-06-28: Reorganicé el directorio `scripts` en 2 sub-directorios, logs y metrics.

  > Commit: `fix(py): Actualiza log_collector.py y agrupa en carpetas`

  Pull request grupal: Implementación de metric_collector #21 
  
- 2025-06-28: Escribí el script `scripts/metric_collector/metric_collector.py` que se encarga de obtener métricas de Pods y Nodos en archivos .csv y .json. Añade también documentación de como instalar `metric_server` para poder usar `kubectl top`.

  > Commit: `feat(py): Añade metric_collector.py con documentación`

  Pull request grupal: Implementación de metric_collector #21