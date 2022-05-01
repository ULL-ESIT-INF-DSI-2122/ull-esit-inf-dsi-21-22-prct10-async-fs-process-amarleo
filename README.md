# Práctica 10: Sistema de ficheros y creación de procesos en Node.js

## Indice

- [Práctica 10: Sistema de ficheros y creación de procesos en Node.js](#práctica-10-sistema-de-ficheros-y-creación-de-procesos-en-nodejs)
  - [Indice](#indice)
  - [Introducción](#introducción)
  - [Tareas Previas](#tareas-previas)
  - [Ejercicios](#ejercicios)
    - [Ejercicio 1](#ejercicio-1)
    - [Ejercicio 2](#ejercicio-2)
    - [Ejercicio 3](#ejercicio-3)
    - [Ejercicio 4](#ejercicio-4)
  - [Conclusión](#conclusión)

## Introducción

El presente informe perteneciente a la décima práctidca de la asignatura de Desarrollo de Sistemas Informáticos, tiene como principales objetivos hacer uso de las APIs proporcionadas por Node.js con la intención de interactuar con el sistema de ficheros, así como para la creación de procesos.

## Tareas Previas

Como tareas previas se han leído y comprendido la documentación proporcionada en el enunciado:

- [API de callbacks Node.js para interacturar con el sistema de ficheros](https://nodejs.org/dist/latest-v18.x/docs/api/fs.html#callback-api)
- [API asíncrona de Node.js para crear procesos](https://nodejs.org/dist/latest-v18.x/docs/api/child_process.html#asynchronous-process-creation)

## Ejercicios

A continuación, se comenta el desarrollo llevado a cabo para cada uno de los ejercicios de esta práctica:

### Ejercicio 1

Antes de comenzar con la traza se intentará definir algunas funciones y objetos del código.

- **Access**: Se trata de una función la cuál permite comprobar los permisos que tiene un usuario sobre el fichero o el directorio especificado en la dirección pasada por parámetro. En la documentación de node JS aportada se recomienda no hacer uso de **fs.access()** antes de realizar una llamada a **fs.open()**, **fs.readFile()** o **fs.writeFile()**, dado que provoca una condición de carrera.

- **Constants**: Se trata de un objeto, cuyas propiedades describen ciertos indicadores que se usan con FileSystem de Nodejs. Existen varios tipos de constantes, como por ejemplo:

| Constant |                        Descripción                         |
| :------: | :--------------------------------------------------------: |
|   F_OK   | Indica la visibilidad del fichero en el proceso de llamada |
|   R_OK   |     Indica si el fichero se puede leer por el proceso.     |
|   W_OK   |   Indica si el fichero se puede escribir por el proceso.   |

A continuación, se comentará una traza de ejecución para el programa propuesto en este ejercicio, donde se indicará los pasos por los que pasan los diferentes procesos.

Durante la ejecución de este código pueden ocurrir diferentes situaciones. En concreto se encuentran las siguientes:

### Ejercicio 2

### Ejercicio 3

### Ejercicio 4

## Conclusión
