# AGENTS.md

Aplicación móvil para visualizar la información en tiempo real de los autobuses urbanos de Vitoria-Gasteiz.

## Estructura del repositorio

Este repositorio raíz es intencionalmente casi vacío: solo contiene el `README.md` y este `AGENTS.md`. **Todo el contenido está ignorado a propósito** mediante `.gitignore`.

El trabajo real se encuentra en subdirectorios, cada uno de los cuales es un **repositorio Git independiente**. Esta es una decisión de diseño del proyecto.

| Subdirectorio  | Repositorio Git propio | Propósito                                                    |
|----------------|------------------------|--------------------------------------------------------------|
| `ios/`         | Sí                     | Código fuente de la aplicación para iOS                      |
| `pruebas-gtfs/`| Sí                     | Prueba de concepto de procesado de información GTFS en Swift |
| `docs/`        | Sí                     | Documentación y diagramas                                    |
| `temp/`        | No                     | Directorio local para pruebas y ficheros temporales          |

## Instrucciones para agentes

- **No crear commits en este repositorio raíz** salvo para modificar `README.md` o `AGENTS.md`.
- Para trabajar en el código, entrar en el subdirectorio correspondiente (`ios/`, `pruebas-gtfs/`, etc.) y operar sobre su repositorio Git propio.
- No generar ni modificar ficheros fuera de los subdirectorios indicados.

## Formatos y tecnologías a utilizar

- Diagramas: PlantUML
- Documentación general: Markdown
- Scripting genérico: Bash
- Utilidades para procesado de datos durante el desarrollo: Python
