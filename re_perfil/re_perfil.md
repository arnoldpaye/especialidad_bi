# Clasificacion de la severidad/prioridad de errores de programacion

Implementar un modelo mediante mineria de datos para determinar la severidad de errores
de programacion en proyectos de codigo abierto.

## Introduccion
- El reporte de solucionado de errores es una fase importante en el desarrollo de software [1].
- La severidad de un error es el grado de impacto que un defecto tiene en el desarrollo u
operacion de un sistema o componente [1].
- Aunque existen pautas para asignar la severidad de un error, generalmente es un proceso manual
realizado por el reportador [2].
- Debido a los recursos limitados es importante determinar la prioridad de un error, ya que marcan
el orden en que seran solucionados [3].

## Referencia
- [1] Determining Bug Severity using Machine Learning Techniques, 2012
- [2] Predicting the severity of a reported bug, 2010
- [3] DRONE: Predicting Priority of Reported Bugs by Multi-factor Analysis, 2013
- [4] Predicting the Priority of a Reported Bug using Machine Learning Techniques and Cross Project Validation, 2012

## Descripcion de un error
- Titulo: [texto]
- Descripcion: [texto]
- Estado: {'enviado', 'abierto', 'solucionado', 'cerrado', 'rechazado'}
- Cantidad de comentario: [numerico]
- Cantidad de revisiones: [numerico]
- Cantidad de commits: [numerico]
- Prioridad: {'ninguna', 'baja', 'normal', 'alta', 'urgente'}
- Severidad: {'ninguna', 'trivial', 'menor', 'mayor', 'critica'}
- Fecha de creacion: [fecha]
- Fecha de apertura: [fecha]
- Reportador: [texto]
- Responsable: [texto]

## Notes
- Se considera como importancia a la combinacion entre prioridad y severidad