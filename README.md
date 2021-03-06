# Contenidos

Los contenidos se organizan según la semana del semestre en que nos encontremos, y según la semana que se destina para su estudio. Los contenidos se subirán en paquetes de una o varias semanas seguidas, pero para una semana dada, solo es necesario estudiar los contenidos de dicha semana, y no las semanas posteriores incluidas en el paquete.

Los contenidos se pondrán en práctica mediante actividades (formativas o sumativas). El contenido de las actividades es acumulativo, así que la materia vista en semanas anteriores también puede entrar en las actividades posteriores, pero tendrán foco sobre solo uno de los contenidos semanales.

La semana 0 corresponde a la primera semana de clases, en la cual no habrá una actividad de contenidos, sino que una actividad introductoria al formato del curso. La carpeta `semana 0` de todas formas contiene material de estudio que se asumirá conocido y se aplicará durante todo el curso, y específicamente se evaluará en la primera tarea del curso (`T0`), en lugar de en una actividad.

La numeración de semanas que siguen, respeta el orden temporal del calendario académico, por lo que las semanas 4 y 10 son saltadas debido a feriados nacionales. Además, a partir de la semana 7 se realizaron cambios para dar espacio a la Semana de Ajuste.

> **IMPORTANTE:** Debido a la contingencia, la pandemia del COVID-19, estos contenidos y su semana correspondiente se encuentran en constante revisión, por lo que les pedimos estar atentos y atentas a los medios de comunicación oficiales del curso en caso de cambios.

La siguiente tabla muestra la correspondencia de actividades y los contenidos semanales:

| Actividad | Tipo      | Semana de contenido | Contenido                           |
| --------- | --------- | ------------------- | ----------------------------------- |
| AF1       | Formativa | Semana 1            | Estructuras de datos _built-ins_    |
| AS1       | Sumativa  | Semana 2            | Programación orientada a objetos I  |
| AF2       | Formativa | Semana 3            | Programación orientada a objetos II |
| AF3       | Formativa | Semana 5            | Excepciones                         |
| AS2       | Sumativa  | Semana 6            | Iterables                           |
| -         | -         | Semana 7            | Semana de Ajuste                    |
| AS3       | Sumativa  | Semana 8            | _Threading_                         |
| AF4       | Formativa | Semana 9            | Interfaces gráficas I               |
| AF5       | Formativa | Semana 11           | Interfaces gráficas II              |
| AS4       | Sumativa  | Semana 12           | I/O y Serialización                 |
| AF6       | Formativa | Semana 13           | _Networking_                        |


Si tienes dudas sobre el contenido puedes abrir una issue [aquí](https://github.com/IIC2233/Syllabus/issues).

## Preguntas frecuentes

1. Yo abro los _notebooks_, hago cambios para ver como funcionan, y a la semana siguiente al hacer `git pull` me sale un error que dice "Your local changes to the following files would be overwritten by merge" ¿Qué puedo hacer?

   1. Siempre puedes clonar el repositorio otra vez, pero no es la idea. Lo que debes hacer es guardar tus cambios en alguna parte, hacer `pull`, y luego volver a aplicar tus cambios. Para eso coloca los siguientes comandos:

     ```bash
     git stash     # Guarda los cambios hechos en otra parte. Desaparecen del working directory.
     git pull      # El pull que queríamos hacer en un principio.
     git stash pop # Regresa los cambios hechos por ti al working directory.
     ```