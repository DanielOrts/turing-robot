# Turing Robot. El sparring de la OSHWDem
La estrategia del diseño de este robot ha sido la de utilizar los componentes más baratos e incorporar todo el material reciclado posible. Y cumpliendo reglamento de la competición de Combate de la OSHWDem que se celebra cada año en la Coruña. Básicamente esto ha supuesto que el peso esté por debajo de una libra, en nuestro caso 450gr. Tener elementos de seguridad como desconexión de la bateria y desactivación del arma si se pierde la conexión con el control remoto o se corta la alimentación.

<img src="https://github.com/DanielOrts/turing-robot/blob/master/images/Turing-Robot_front_mini.JPG" width="250" align="right" />

## Diseño
Nos hemos basado en un chasis de aluminio con soporte para cuatro motores de 6V sobre-alimentados a 8V y con reductora. El arma incorporada es un ariete inverso con un solo disparo. Utilizando un solenoide como elemento de retención. El mando a distancia ha tenido que ser modificado para sustuir el botón de un canal por uno 'siempre pulsado'.

<img src="https://github.com/DanielOrts/turing-robot/blob/master/images/Turing-Robot_control_mini.JPG" width="250" align="right" />
El la tracción de las ruedas es 2 a 2. Sin diferencial. Los que produce un movimiento del tipo cadena de oruga.

## How to
La conectividad es simple. Los dos canales de las palancas de dirección se conectan a pares. Uno a las ruedas derechas y otro a las izquierdas. Inviertiendo la polaridad:

<img src="https://github.com/DanielOrts/turing-robot/blob/master/images/Turing-Robot_back_mini.JPG" width="250" align="right" />tiene
Como las ruedas van a ser el primer elemento que va a recibir los golpes del atacante. He añadido al eje un separador de 4 arandelas a fin de que no se acequen al chasis. Además, el eje está pegado y el interior de las gomas rellenado de pegamente.

La placa base del robot es el receptor de radiofrecuencia. Donde he conectado y soldado los cables que van a los motores y al solenoide.

<img src="https://github.com/DanielOrts/turing-robot/blob/master/Turing-Robot_Sketch_bb.png" width="500" align="right" />

### Componentes
El transmisor de radiofrecuencia tiene la siguientes características:

|   |   |
|---|---|
|Canales|7|
|Frequency|2.4GHz.|
|Codificada|Si|
|Alimentación|6-12V DC|

- **Chasis** : De aluminio con los motores montados. [AliExpress](https://www.aliexpress.com/item/32901509996.html)
- **Control remoto** : Mando emisor más placa receptora. [AliExpress](https://www.aliexpress.com/item/32893229546.html)
- **Arite** : Reciclado. Parte de la hoja de una sierra de madera.
- **Solenoide** : Reciclado. Pieza extraida de una fotocopiadora.
- **Bateria** : Reciclada. Original de un avión de radiocontrol Falcon.

### Agradecimientos:
- [Victor Gómez (FabLab Mallorca)](http://fablabmallorca.com/)

