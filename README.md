# SAVIA — examen N.º 1

Proyecto estático HTML + CSS. Abrir `index.html` en el navegador. No necesita dependencias.

El sitio incluye la página Inicio y las plantillas `pages/menu.html`, `pages/equipo.html` y `pages/eventos.html` con contenido central pendiente. Siga exclusivamente las especificaciones del examen para conocer el comportamiento esperado. No modifique el tema general ni sustituya el proyecto por otro.

# Estudiantes

Keylor Barrantes Gómez - C5D024

Juan Pablo Jiménez Vargas - C5G323

## Diagnóstico de cinco incidencias

| N.º | Comportamiento observado                                | Causa técnica y ubicación                                                                                   | Corrección realizada                                                           | Prueba de verificación                                                        | Autor  |
| --- | ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ------ |
| 1   | Las cards en column                                     | El flex direction, en el css feature layout estaba en column envez de row.        ![alt text](images/errores/1.png)| La dirección del flex la cambiamos a row.                                     | Guardamos y ejecutamos la vista de index.html             ![alt text](images/evidencias/1.png)                    | Keylor |
| 2   | Redirecciona a otra página                              | El anchor redireccionaba a eventos.  html      ![alt text](images/errores/2.png)                                               | Se cambio para que redireccione a menu.html                                    | Guardamos, ejecutamos y probamos el anchor             ![alt text](images/evidencias/2.png)                       | Pablo  |
| 3   | Redireccionaba a # osea se mantenia en la misma sección | El href estaba redireccionando a # envez de a pages/menu. html           ![alt text](images/errores/3.png)                                    | Se cambio de # a pages/menu.html                                               | Guardamos, ejecutamos y probamos el btn nuevamente              ![alt text](images/evidencias/3.png)              | Keylor |
| 4   | El color es rojo envez de dorado                        | En el css el #hero-action tenía un color distinto        ![alt text](images/errores/4.png)                                                   | Se cambio el color por #d7a45b que corresponde a la paleta                     | Guardamos y vimos el boton                                 ![alt text](images/evidencias/4.png)                   | Pablo  |
| 5   | Los links no se movían abajo del logo                   | No había un media que indicara que al llegar a ese ancho el flex direction cambiara a column, estaba en row ![alt text](images/errores/5.png)| Se agrego un @media (max-width: 375px) que cambiara el flex direction a column | Guardamos, ejecutamos y inspeccionamos para ver si cambiaba al bajar el ancho ![alt text](images/evidencias/5.png) | Keylor |

## Responsables de las funcionalidades

| Estudiante | Página asignada                          | Rama   | Commits principales |
| ---------- | ---------------------------------------- | ------ | ------------------- |
| Pablo      | Carta interactiva: viaje de tres tiempos | pablo  |                     |
| Keylor     | Equipo: detrás de cada plato             | keylor |                     |

## Evidencias Git

| Funcionalidad/corrección | PR hacia develop | Revisor | Resultado de merge / conflicto si ocurrió |
| ------------------------ | ---------------- | ------- | ----------------------------------------- |
| Parte A: corrección de incidencias | [PR #1](https://github.com/keyloor/EXAMEN-1/pull/1) (autor: Pablo) | Keylor | Merge automático, sin conflictos |
| Feature 1: Menú | [PR #2](https://github.com/keyloor/EXAMEN-1/pull/2) (autor: Pablo) | Keylor | Merge automático, sin conflictos |
| Feature 2: Equipo | [PR #4](https://github.com/keyloor/EXAMEN-1/pull/4) (autor: Keylor) | Pablo | Merge automático, sin conflictos |

### Capturas del merge de los PR

PR #1, Parte A:

![Merge del PR #1](images/evidencias/pr-1-merge.png)

PR #2, Feature 1 (Menú):

![Merge del PR #2](images/evidencias/pr-2-merge.png)

## Verificación final

Registrar las pruebas de funcionamiento a 1280 px y 375 px, enlaces y páginas.
