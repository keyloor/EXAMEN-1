# SAVIA — examen N.º 1

Proyecto estático HTML + CSS. Abrir `index.html` en el navegador. No necesita dependencias.

El sitio incluye la página Inicio y las plantillas `pages/menu.html`, `pages/equipo.html` y `pages/eventos.html` con contenido central pendiente. Siga exclusivamente las especificaciones del examen para conocer el comportamiento esperado. No modifique el tema general ni sustituya el proyecto por otro.

## Diagnóstico de cinco incidencias

| N.º | Comportamiento observado                                | Causa técnica y ubicación                                                                                   | Corrección realizada                                                           | Prueba de verificación                                                        | Autor  |
| --- | ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ------ |
| 1   | Las cards en column                                     | El flex direction, en el css feature layout estaba en column envez de row.                                  | La dirección del flex la cambiamos a row.                                      | Guardamos y ejecutamos la vista de index.html                                 | Keylor |
| 2   | Redirecciona a otra página                              | El anchor redireccionaba a eventos.html                                                                     | Se cambio para que redireccione a menu.html                                    | Guardamos, ejecutamos y probamos el anchor                                    | Pablo  |
| 3   | Redireccionaba a # osea se mantenia en la misma sección | El href estaba redireccionando a # envez de a pages/menu.html                                               | Se cambio de # a pages/menu.html                                               | Guardamos, ejecutamos y probamos el btn nuevamente                            | Keylor |
| 4   | El color es rojo envez de dorado                        | En el css el #hero-action tenía un color distinto                                                           | Se cambio el color por #d7a45b que corresponde a la paleta                     | Guardamos y vimos el boton                                                    | Pablo  |
| 5   | Los links no se movían abajo del logo                   | No había un media que indicara que al llegar a ese ancho el flex direction cambiara a column, estaba en row | Se agrego un @media (max-width: 375px) que cambiara el flex direction a column | Guardamos, ejecutamos y inspeccionamos para ver si cambiaba al bajar el ancho | Keylor |

## Responsables de las funcionalidades

| Estudiante | Página asignada | Rama | Commits principales |
| ---------- | --------------- | ---- | ------------------- |
|            |                 |      |                     |

## Evidencias Git

| Funcionalidad/corrección | PR hacia develop | Revisor | Resultado de merge / conflicto si ocurrió |
| ------------------------ | ---------------- | ------- | ----------------------------------------- |
|                          |                  |         |                                           |

## Verificación final

Registrar las pruebas de funcionamiento a 1280 px y 375 px, enlaces y páginas.
