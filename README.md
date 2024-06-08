# Proyecto Final Robotica/Diseño
Este proyecto se realiza con el fin de implementar los conocimientos adquiridos en el proceso educativo universitario, realizando un robot que se pueda controlar entre 4 GDL (Grados de Libertad), o más y que este realice la acción requerida atraves de diferentes metodos como lo son:
- ROS2
- Arduino UNO
- Bluetooth

# Tabla de Contenido
[1. Resumen](#resumen)

[2. Introducción](#introducción)

[3. Objetivos](#objetivos)

[4. Justificación](#justificación)

[5. Marco Teórico](#marco-teórico)

[6. Revisión de la Literatura](#revisión-de-la-literatura)

[6. Cotización](#cotización)

[7. Diseño 2D y 3D](#diseño-2D-y-3D)

[8. Pruebas de Resistencia](#pruebas-de-resistencia)

[9. Construcción del Robot](#construcción-del-robot)

[10. Estrategia de Control](#estrategia-de-control)

[11. Programación del Robot en Arduino](#porgramación-del-robot-en-arduino)

[12. Programación del Robot en ROS2](#programación-del-robot-en-ros2)

[13. Entorno virtual del Robot](#entorno-virtual-del-robot)

[14. Calculos cinematicos (directo e inverso)](#calculos-cinematicos-directos-e-inversos)

[15. Resultados y Discusión](#resultados-y-discusión)

[16. Conclusiones](#conclusiones)

[17. Referencias](#referencias)

# Resumen


# Introducción
En el mundo de la robótica, la construcción de robots de 5 grados de libertad (5DOF) se ha convertido en un proyecto popular, tanto para aficionados como para profesionales. Este tipo de robots, capaces de realizar movimientos complejos gracias a sus articulaciones, ofrecen un sinfín de posibilidades en diversos campos. En este ensayo, abordaremos la creación de un robot 5DOF utilizando las herramientas de impresión 3D, Arduino y el lenguaje Python, explorando sus beneficios y aplicaciones potenciales.

La impresión 3D emerge como una tecnología clave en este proyecto. Permite crear piezas personalizadas de manera precisa y eficiente, adaptándose a los diseños específicos del robot y sus necesidades de movimiento. El uso de filamento PLA, un material biodegradable y versátil, contribuye a la sostenibilidad del proyecto.

Arduino, una plataforma de desarrollo de código abierto, juega un papel fundamental en el control del robot. Al programar la placa Arduino Uno junto con los codigos en lenguaje Python, se le da vida al robot, permitiéndole ejecutar movimientos predefinidos o responder a comandos en tiempo real. La simplicidad y flexibilidad de Python lo convierten en un lenguaje ideal para principiantes y expertos por igual.

La construcción de este robot 5DOF va más allá de la simple creación de una máquina. Implica un proceso de aprendizaje profundo en el que se conjugan conocimientos de robótica, mecánica, electrónica y programación. Cada etapa, desde el diseño 3D hasta la programación final, ofrece oportunidades para adquirir nuevas habilidades y comprender los principios fundamentales que rigen el funcionamiento de los robots.

Las aplicaciones de este robot 5DOF son diversas y prometedoras. En el ámbito educativo, puede servir como herramienta para enseñar conceptos de robótica y programación a estudiantes de todas las edades. En el campo de la investigación, puede ser utilizado para desarrollar nuevos algoritmos de control o probar diferentes diseños de robots. Incluso, en el ámbito del entretenimiento, puede convertirse en un robot de juguete o participar en competiciones de robótica. 
# Objetivos
Objetivo General

- Diseñar, construir y programar un brazo robótico que sea capaz de realizar tareas de manipulación y agarre de objetos en un entorno simulado y real. Para lograr esto, se emplean herramientas de diseño asistido por computadora (CAD) como solidworks para modelar cada componente del brazo, servomotores para el movimiento preciso de las articulaciones, y una tarjeta Arduino para el control y la comunicación con el software de ROS2. La simulación en ROS2 permite probar y validar los algoritmos de control y las trayectorias del brazo antes de implementarlos en el hardware real. Esta metodología reduce el riesgo de errores y daños en el prototipo físico, además de facilitar la optimización de los parámetros del sistema.

Objetivos Especificos 
 
- Crear un modelo detallado del brazo robótico en SolidWorks, incluyendo eslabones, juntas y el mecanismo de la pinza.
- Desarrollar y programar los algoritmos de cinemática directa e inversa para controlar el movimiento del brazo.
- Implementar el modelo del brazo en un entorno de simulación utilizando ROS2, y probar las capacidades de manipulación y agarre.
- Imprimir en 3D las piezas del brazo robótico, ensamblar el hardware y conectar los servomotores a la tarjeta Arduino.
- Programar la tarjeta Arduino para recibir comandos desde ROS2 y controlar los servomotores, y realizar pruebas funcionales para asegurar que el brazo opere según lo previsto.

# Justificación

# Marco Teórico

# Revisión de la Literatura

# Cotización

# Diseño 2D y 3D
