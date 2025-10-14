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


preguntas de reflexión:
1. que aprendí?
   con la realización de este proyecto en pytho, que es un nuevo lenguaje de programación para mi, aprendi a pulir las pocas habilidades que tenia en
   programacion y la resolucion de problemas.
2. lo mas desafiante?
   la realizacion de la simulacion de revision ya que no me habia enfrentado a hacer algo similar sin embargo se logor por lo que estoy satisfecho con eso
3. que mejoraria?
   Aunque el sistema cumple con su propósito principal de gestionar cursos y notas de forma correcta, existen varias mejoras que podrían hacerlo más robusto, moderno y escalable. Algunas de ellas son:

Implementar almacenamiento permanente:
Actualmente los datos se pierden al cerrar el programa. Una mejora sería guardar y leer la información desde un archivo JSON o una base de datos SQLite, para conservar los registros de manera persistente.

Migrar a Programación Orientada a Objetos (POO):
Reestructurar el código en clases y objetos permitiría una mayor organización, reutilización y facilidad de mantenimiento del sistema.

Crear una interfaz gráfica (GUI):
Desarrollar una interfaz visual con Tkinter o PyQt haría el programa más intuitivo y atractivo para el usuario, eliminando la necesidad de escribir comandos en consola.

Agregar validaciones más completas:
Incluir manejo de errores con try-except y mensajes personalizados mejoraría la estabilidad del sistema y evitaría cierres inesperados.

Incorporar nuevas funcionalidades:
Como exportar reportes en PDF, calcular estadísticas avanzadas (máxima, mínima, promedio general) o mostrar gráficos de rendimiento con librerías como matplotlib.
