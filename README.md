# Introducción a la Ingeniería de Sistemas (INSI)

Repositorio general del curso Introducción a la Ingeniería de Sistemas, que agrupa —mediante submódulos de git— las actividades del curso.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para saber cómo aprovechar este repositorio, ver [Cómo usar este repositorio](#cómo-usar-este-repositorio).

## Estructura del proyecto

```
Introduccion-a-la-Ingenieria-de-Sistemas/
├── Tareas/
│   └── Impacto-tecnologico-INSI/     # Página interactiva sobre casas inteligentes
└── Proyectos/
    └── Sarase-INSI/                  # App informativa de salud para ciudades inteligentes
```

## Temas del curso

El curso es una introducción general a la carrera y a la disciplina de ingeniería de sistemas:

- Panorama de la ingeniería de sistemas y sus áreas de aplicación.
- Ciudades inteligentes y el impacto de la tecnología en la sociedad (casas inteligentes, servicios digitales).
- Fundamentos de construcción de páginas web: HTML, CSS y JavaScript básico.
- Trabajo en equipo aplicado al diseño de una solución tecnológica con enfoque social.

## Herramientas

- HTML5, CSS3, JavaScript
- Nicepage (plantillas web)

## Profesor

Oswaldo Castillo Navetty.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes (tareas y proyecto), organizados por carpetas. Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Introduccion-a-la-Ingenieria-de-Sistemas.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
