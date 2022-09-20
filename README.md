# git-practice

En la mayoría de nuestros proyectos se trabaja con 3 entornos:
 - Producción que es el que se publica a todo el mundo, 
 - Preproducción que es donde el cliente válida y 
 - Desarrollo que se refiere al entorno en nuestro equipo; por tanto desarrollo no es único; hay uno por cada miembro del equipo que desarrolla.
 
El ejercicio consiste en realizar las siguientes tareas; recuerda que debes leer la guía de git de TCK para ver y entender el flujo de trabajo.

## 1
Crear las ramas de **staging** para el entorno de pre e **integration** para controlar las puestas en producción.

## 2 corregir ortografía

Crea una rama **feature/** + el número de la tarea que vayas a acometer y un título descriptivo; en este caso podría ser por ejemplo **feature/2--fix-accents**

Arregla la página 2, ya que le faltan los acentos.

## 3 Crear una PR de la tarea 2

Crear una Pull Request de la tarea anterior y añadir a un revisor.

Las PR apuntarán a la rama de integración.

## 4 Terminar página 3

La página 3 esta incompleta hay que añadir el número de página al texto.

Proceder como marca el flujo de tck; crear la feature con su nombre corregir y publicar su PR.

## 5 Añadir una línea a cada una de las tres páginas

Añadir una línea con el texto que quieres en las páginas 1, 2 y 3

Proceder como marca el flujo de tck; crear la feature con su nombre corregir y publicar su PR.

## 6 Mergear en staging la tarea 2

Mergear en staging la tarea 2 para que la podamos revisar

## 7 Mergear en staging las tareas 3, 4 y 5

Mergear todo en staging para revisar las tareas.

## 8 Mover la página 3

Cambia el nombre de la página 3 por final.txt y crea una nueva página3.txt que se titule "Nueva página 3"

## 9 Cerrar PR'S

Mergear todas las PR's en el siguiente orden de aprobación: Tarea 8, Tarea 4, Tarea 3, Tarea 2, Tarea 5

Si hay conflictos se deben resolver; el proceso es mergear la rama de integración en la rama de la PR, corregir el conflicto y hacer push.

## 10 Poner en producción

Mergear **integration** en **master**