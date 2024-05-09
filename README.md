Este repositorio contiene los códigos para generar una aplicación simple en Flutter que simula lanzar una pirinola. 
Importa los paquetes necesarios para usar Flutter y la clase Random de la biblioteca estándar de Dart.
Se presenta un widget de estado (StatefulWidget) que representa la pirinola. No incluye un método build, 
ya que esto se maneja en la clase de estado interna. En su lugar, tiene un método createState que devuelve una instancia de _DiceRollerState, 
la clase de estado interna que maneja la lógica y la presentación de la pirinola.
La clase de estado interna es la de DiceRoller. 
Contiene dos variables de instancia: activeDiceImage, que no se utiliza en el código proporcionado, y currentDiceRoll, que almacena el valor de la pirinola actual. 
Tiene un método rollDice() que genera un nuevo número aleatorio entre 1 y 6 cada vez que se llama y actualiza el estado para reflejar el nuevo valor de la pirinola.
Construye y devuelve la interfaz de usuario del widget. Muestra una imagen de la pirinola correspondiente al valor actual de currentDiceRoll y un botón de texto para lanzar la pirinola. 
El botón está configurado para llamar al método rollDice() cuando se presiona.

En general, este código define un widget DiceRoller que muestra una imagen de una pirinola y un botón para lanzar la pirinola. 
Cuando se presiona el botón, se genera un nuevo valor aleatorio para la pirinola y se actualiza la interfaz de usuario para reflejar el nuevo valor.
