# kipu-bank

El contrato kipu-bank es una simulación de un banco en la que el usuario podra crear una boveda personal en la que podra depositar wei y retirarlos.

Instrucciones de despliegue:
El contarto nos permite crear una boveda personal, de esta manera podremos ingresar o retirar wei.
Al desplegarlo podremos establecer el limite que el contrato podrá aceptar y cuánto podra retirar.
Para desplegarlo no se necesita tener algún valor en el wei ni un limite en especifo del gas.

Como interactuar con el contrato:
1-Una vez desplegado el contrato, pondremos el valor en wei que queremos depositar y al desplegar el contrato utilizando el boton "deposit" depositaremos el wei, este mismo ya hace la comprobación de la existencia de una boveda personal y los guarda en la misma. Podremos repetir está acción las veces que querramos mientras no pasemos el limite que el contrato puede guardar.
2-Para ver el limite que el contrato puede guardar podremos usar el boton "bankCap" que nos mostrara esto mismo.
2.1-Para ver cuanto está guardando el contrato en general podremos usar "totalBanked".
2.2-Al copiar la dirección del contrato y colocarlo en la barra desplegable continua al boton de nombre "getBalance" y posteriormente clickeandolo podrmeos saber cuanto tenemos depositado en nuesta boveda.
2.3-Con "depositCount" podremos saber cuantos depositos hemos podido hacer.
3-Para poder extraer podremos usar la barra continua al boton "withdraw", mientras no nos pasemos del valor limite por extracción o lo que tenemos guardado en la boveda podremos extraer cuanto querramos.
3.1-Para saber el limite por extracción usaremos el boton "withdrawalLimit".
3.2-Para saber cuantas extracciones se han realizado podremos usar el botón "withdrawalCount".
