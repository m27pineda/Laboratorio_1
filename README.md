Este repositorio es utilizado para poder visualizar el laboratorio numero 1 de la materia de Inteligencia Artificial de la Universidad de Panamá

El archivo con extension sonic.py es la primera version que hemos utilizado. Actualizado con el nuevo archivo con extensión colaborar.py

Podremos ejecutar este último archivo, en nuestro IDLE de Python y observaremos una enorme matriz en la que podemos diferenciar

Podemos observar que si le damos a la tecla "UP" se nos activara la primera casilla del arreglo. Action [1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0] Reward 0.0

Podemos observar que si le damos a la tecla "DOWN" se nos activara la sexta casilla del arreglo. Action [0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0] Reward 0.0

Podemos observar que si le damos a la tecla "RIGTH" se nos activara la octava casilla del arreglo. Action [0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0] Reward 0.0

Podemos observar que si le damos a la tecla "LEFT" se nos activara la séptima casilla del arreglo. Action [0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0] Reward 0.0


Encontramos en el archivo sonic_controller.py el comando env = retro.make ('SonicTheHedgehog-Genesis', 'GreenHillZone.Act1', record = ".") el cual nos ayudara a guardar nuestros dataset, para ser vistos ejecutando sonic_playback.py
