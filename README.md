# Proyecto Angular — Gestión de tareas y panel admin

Frontend en **Angular 13** que aplica componentes, rutas, formularios y **Angular Material** para flujos de **login**, **registro**, **tablero de tareas** y **administración** de usuarios y roles.

**Autora del repositorio:** [@Juli21v](https://github.com/Juli21v)

## Stack

- Angular 13
- Angular Material y CDK
- Angular Flex Layout
- RxJS, TypeScript

## Módulos funcionales

- **Home:** cabecera, pie, login y registro
- **Board:** componentes para guardar y listar tareas
- **Admin:** altas, bajas y modificaciones de usuarios y roles; listados

## Estructura del repositorio

```
Proyecto-angular/
└── frontend/
    ├── src/
    │   └── app/
    │       ├── home/       # header, footer, login, register
    │       ├── board/      # save-task, list-task
    │       └── admin/      # CRUD usuarios y roles
    ├── angular.json
    └── package.json
```

## Requisitos

- Node.js compatible con Angular 13
- Angular CLI ~13

## Instalación y desarrollo

```bash
cd frontend
npm install
ng serve
```

Compilación para producción:

```bash
ng build
```

## Nota

Este proyecto se apoya en un backend con API REST; para una demo completa, configura la URL del API en el frontend según tu entorno.
