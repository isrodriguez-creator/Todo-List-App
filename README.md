# Mini Lista de Tareas (To-Do List) — SCRUM aplicado

Proyecto Final — Unidad 4: Aplicación de metodología de desarrollo según tendencia
Materia: Metodología de Desarrollo de Software (DAWA-202)
Instituto Superior Tecnológico La Troncal (ISTLT)

## Descripción

Aplicación web sencilla de "Lista de Tareas" hecha con HTML, CSS y JavaScript puro (sin frameworks), desarrollada aplicando el ciclo completo de SCRUM: Product Backlog, Sprint Planning, Sprint, Daily Scrum, Sprint Review y Retrospective. Se usó Jira para la gestión del proyecto, GitHub para el control de versiones y GitHub Actions para integración continua (CI).

## Historias de usuario implementadas (Sprint 1)

| ID | Historia de Usuario | Prioridad | Puntos | Estado |
|----|---|---|---|---|
| HU-01 | Como usuario quiero agregar una nueva tarea para registrar pendientes. | Alta | 3 | LISTO |
| HU-02 | Como usuario quiero marcar una tarea como completada para ver mi progreso. | Alta | 2 | LISTO |
| HU-03 | Como usuario quiero eliminar una tarea para quitar pendientes ya no vigentes. | Alta | 2 | LISTO |

> HU-04 (editar tarea) y HU-05 (filtrar tareas) quedan pendientes para un futuro Sprint 2.

## Funcionalidades

- Agregar una nueva tarea
- Marcar una tarea como completada
- Eliminar una tarea

## Tecnologías y herramientas

- **Jira**: Product Backlog, Sprint 1, tablero SCRUM y burndown chart
- **GitHub**: repositorio y control de versiones
- **GitHub Actions**: integración continua (CI) — workflow `.github/workflows/ci.yml`
- **HTML / CSS / JavaScript**: desarrollo de la aplicación

## Capturas

### Tablero SCRUM (final del Sprint 1)
> _[<img width="1877" height="860" alt="Captura de pantalla 2026-08-19 131244" src="https://github.com/user-attachments/assets/37f5191e-d4a7-4be2-ac12-1c565434af69" />
"]_

### Burndown Chart
> _[<img width="1522" height="775" alt="WhatsApp Image 2026-08-19 at 13 05 48" src="https://github.com/user-attachments/assets/d22561ab-52d0-4480-a109-e6b4e3ba0704" />
]_

### Ejecución del pipeline de CI (GitHub Actions)
> _[<img width="1901" height="881" alt="image" src="https://github.com/user-attachments/assets/50f98484-1ec1-4d96-ba8c-74525d715de3" />


## Sprint Review

Checklist de revisión del incremento:

- [x] Las historias HU-01, HU-02 y HU-03 funcionan correctamente en el navegador
- [x] El código está subido a GitHub con commits por historia
- [x] El pipeline de integración continua (GitHub Actions) se ejecutó sin errores

## Sprint Retrospective

**Start** (empezar a hacer):
> _[habilidades del software]_

**Stop** (dejar de hacer):
> _[El paso 5 se me complico]_

**Continue** (seguir haciendo):
> _[Los sprint]_

## Cómo ejecutar el proyecto

1. Clona el repositorio: `git clone https://github.com/tu-usuario/todo-list-app.git`
2. Abre el archivo `index.html` en tu navegador (no requiere instalación ni servidor).

## Autor

susana— Desarrollo de Aplicaciones Web, Nivel 2, ISTLT
