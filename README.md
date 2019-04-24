# Comunicacion de ventanas utilizando JavaFX y FXML
## José Ramón Jiménez Reyes

Proyecto eclipse en el que muestro cómo utilizar JavaFX y FXML para que desde una ventana se puedan lanzar otras y éstas se puedan comunicar entre ellas (más bien sus controladores).

El proyecto consta de una ventana principal con dos botones y un área de mensajes. Cada uno de los botones abre otra ventana de forma modal. Las dos ventanas que se pueden abrir son idénticas. Tienen un botón que saluda y un `ComboBox` que permite elegir dos opciones.

Cada una de las acciones que realizemos en las ventanas secundarias se reflejarán en el área de mensajes de la ventana principal.

Para ello, hemos pasado el área de mensajes a las ventanas secundarias (a sus controladores) para que puedan escribir en ella.

Espero os sea de utilidad.