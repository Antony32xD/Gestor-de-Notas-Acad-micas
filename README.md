# Gestor-de-Notas-Acad-micas
Descripción del proyecto

Este programa en Python es un gestor interactivo de cursos y notas diseñado para estudiantes o profesores que quieran registrar, actualizar, consultar y administrar cursos y calificaciones de manera organizada.

Se enfoca en listas, pilas, colas y estructuras de control para simular operaciones reales de gestión académica, con una interfaz de menú clara y limpia en la terminal.

Funcionalidades principales

Registrar cursos y notas

Permite agregar uno o varios cursos a la lista de forma segura.

Valida que el nombre del curso no esté vacío ni repetido.

Valida que las notas estén en el rango de 0 a 100.

Mostrar cursos y notas

Lista todos los cursos registrados junto con sus notas.

Calcular promedio general

Calcula el promedio de todas las notas registradas.

Muestra las notas y el promedio con dos decimales.

Contar cursos aprobados y reprobados

Clasifica los cursos según si la nota es mayor o igual a 61 (aprobado) o menor (reprobado).

Búsqueda de cursos

Búsqueda lineal: busca un curso por nombre recorriendo la lista.

Búsqueda binaria: busca un curso en una lista previamente ordenada alfabéticamente.

Actualizar notas

Permite modificar la nota de un curso.

Registra los cambios en un historial de cambios (pila) para futuras consultas.

Eliminar cursos

Permite borrar un curso seleccionado por su índice.

Confirma la acción antes de eliminar.

Ordenamiento

Por nota: ordena los cursos de menor a mayor.

Por nombre: ordena los cursos alfabéticamente.

Simulación de cola de solicitudes de revisión

Permite agregar solicitudes de revisión de notas en una cola.

Atender solicitudes en orden (FIFO) y actualizar la nota.

Mostrar todas las solicitudes pendientes.

Historial de cambios

Almacena los cambios realizados sobre las notas usando una pila, mostrando los registros más recientes primero.

Salir del programa

Finaliza la ejecución del programa de manera ordenada.

Características técnicas:

Implementa listas para cursos y notas.

Implementa deque para la cola de revisiones.

Implementa pila mediante listas para el historial de cambios.

Utiliza funciones modulares para cada operación.

Uso de limpieza de terminal (cls en Windows y clear en Linux/Mac) para mantener la interfaz ordenada.

Manejo de errores con try/except para entradas inválidas.

Interfaz de menú interactivo que permite ejecutar múltiples operaciones en un bucle hasta decidir salir.

Uso del programa:

Ejecuta el script en Python.

Selecciona una opción del menú ingresando un número entre 1 y 13.

Sigue las instrucciones en pantalla según la opción seleccionada.

Para volver al menú después de cada acción, responde "s" cuando se pregunte si deseas realizar otra operación.

El programa terminará cuando respondas "n" o selecciones la opción 13.

Propósito del código:

Este programa está dirigido a estudiantes o docentes que desean gestionar sus cursos y notas de forma eficiente.
Además, sirve como un ejemplo educativo de cómo aplicar conceptos de programación como listas, pilas, colas, funciones, validación de datos y manejo de errores en Python, manteniendo una interfaz amigable y limpia.
