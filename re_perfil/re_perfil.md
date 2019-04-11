# Asignacion de prioridad de errores en proyectos de software mediatne tecnicas de mineria de datos

Implementar un modelo mediante mineria de datos para determinar la severidad de errores
de programacion en proyectos de codigo abierto.

## Introduccion
Con el objetivo de mejorar la productividad y la calidad de software se esta incrementando
el uso de tecnicas de mineria de datos en diversas areas del desarrollo de software [1].

El reporte de errores de programacion es una parte integral del desarrollo de software [2],
esta tarea es realizada por el encargado de calidad, el cual debe asignarle una prioridad.

La prioridad de un error de programacion establece la importancia y urgencia con la que debe ser
solucionado, lo cual es importante en la gestion y asignacion de recursos [3]. Si bien existen
pautas para la asignacion de prioridad, generalmente el reportador se basa en su experiencia y criterio [4].

El presente trabajo de especialidad pretende elaborar un modelo predictivo utilizando tecnicas de
mineria de datos para la asignacion de prioridad de reportes de errores en proyectos de desarrollo
de software.

## Referencia
- [1] Data Mining for Sofware Engineering, 2009
- [2] Determining Bug Severity using Machine Learning Techniques, 2012
- [3] Predicting the Priority of a Reported bug using Machine Learning Techniques and Cross Project Validation, 2012
- [4] Predicting the severity of a reported bug, 2010

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