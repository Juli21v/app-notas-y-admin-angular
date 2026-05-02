# App con Angular Material — tareas y administración

Frontend en **Angular 13** con **Angular Material** para **login**, **registro**, **tablero de tareas** y **administración** de usuarios y roles. Buen ejemplo de SPA estructurada con módulos y rutas.

**Autora:** [@Juli21v](https://github.com/Juli21v)

## Por qué destaca en el portafolio

Muestra **SPA “tipo producto”**: formularios, listas, paneles admin y estética Material sin mezclar con el código del backend en el mismo repo — encaja bien como **pin** junto al repo full stack.

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

Este proyecto se apoya en un **backend REST** (por ejemplo el tablero full stack u otro API en el mismo puerto). La URL base está en `frontend/src/environments/environment.ts` → **`APP_URL`** (debe incluir `http://` y terminar en `/`). **Corregido:** antes faltaban los dos puntos en `http://`.
