# Apuntes Curso de Git/Github
## Clase 1
Em esta clase aprendimos a instalar Git, ademas de ver y conocer los primeros comandos basicos pasra poder crear un repositorio
## Clase 2
## Clase 3
En esta clase se dio las nociones basicas para comenzar con github, como crear un repositorio local, su respectiva sincronizacion en la nube; ademas de las diferentes caracteristicas de esta plataforma, como e;l perfil de usuario, repositorios publicos y otras caracteristicas mas.

Por otro lado, tambien se nos pidio comenzar con la actividad por grupos, siendo esta integrada por 3 o 4 integrantes donde se debera hacer un pequeno proyecto que no tendra mucha importancia, sin embargo es crucial realizar los diferente 'commits' con respecto al trabajo en equipo, colaboracion, aportes y en caso de que exista algun conflicto, este tambien debera ser documentado en un repoositorio el cual tenga un archivo "README.me"
#prueba
# Git Flow: Modelo de Ramificación para Proyectos de Software

## Introducción
- **Git Flow** es un modelo de ramificación establecido por Vincent Driessen.
- Proporciona una estructura organizada para el desarrollo de proyectos y la gestión de lanzamientos.

## Ramas Principales
- **Rama `main`**: Almacena el historial de lanzamientos oficiales.
- **Rama `develop`**: Sirve como rama de integración para características en desarrollo.

## Ramas de Soporte
- **Ramas `feature`**: Utilizadas para desarrollar nuevas características.
- **Ramas `release`**: Preparan una nueva versión del producto.
- **Ramas `hotfix`**: Permiten la corrección rápida de errores en producción.

## Ciclo de Vida del Desarrollo
1. **Inicio**: Se crea una rama `develop` desde `main`.
2. **Desarrollo de Características**: Se crean ramas `feature` desde `develop`.
3. **Preparación de Lanzamiento**: Las características se fusionan en `develop` y se crea una rama `release`.
4. **Lanzamiento**: La rama `release` se fusiona en `main` y `develop`.
5. **Mantenimiento**: Los errores críticos se corrigen en ramas `hotfix` y se fusionan en `main` y `develop`.

## Ventajas
- Estructura clara para el desarrollo y lanzamiento.
- Facilita la colaboración y reduce conflictos de fusión.
- Mejora la gestión de versiones y lanzamientos.

## Desventajas
- Puede ser complejo para proyectos pequeños o con lanzamientos continuos.
- Menos popular en comparación con flujos de trabajo basados en troncos[^1^][1].

## Conclusión
Git Flow es un marco de trabajo que, cuando se implementa correctamente, puede mejorar significativamente la eficiencia y claridad en la gestión de proyectos de software. Sin embargo, es importante evaluar si se adapta a las necesidades específicas del proyecto y del equipo.

#prueba2
#prueba3
#prueba4
