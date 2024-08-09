##### Sección 1.

1.	¿Cuántos puertos tiene el microcontrolador ATMEGA328P?
El ATmega328P tiene 3 puertos principales: Port B, Port C y Port D.

2.	¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?
Un microcontrolador como el ATmega328P es un circuito integrado que ejecuta un programa y maneja entradas y salidas digitales y analógicas. La tarjeta de desarrollo Arduino es una placa que integra un microcontrolador (como el ATmega328P en la Arduino UNO) con un entorno de desarrollo fácil de usar, con conectores y componentes adicionales como reguladores de voltaje, osciladores y un puerto USB para programación.

3.	¿Cuántos volts entrega cada pin de los puertos?
Cada pin de los puertos del ATmega328P puede entregar 5 volts cuando está configurado como salida en estado alto.

4.	¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?
Cada pin puede entregar hasta 40 mA (milamperios), pero se recomienda no exceder los 20 mA para evitar dañar el microcontrolador.

5.	¿Qué es una localidad de memoria en el microcontrolador?
Una localidad de memoria es una dirección específica dentro de la memoria del microcontrolador donde se almacena un dato o instrucción.

6.	¿Cuál es la capacidad del microcontrolador para la memoria de programa?
El ATmega328P tiene una capacidad de 32 KB de memoria flash para el almacenamiento de programas.

7.	¿Cuál es la capacidad del microcontrolador para la memoria de datos?
El ATmega328P tiene 2 KB de SRAM para datos y 1 KB de EEPROM para almacenamiento de datos no volátiles.

8.	¿Cuál es la diferencia entre la arquitectura Harvard y Von Neumann?
En la arquitectura Harvard, la memoria para instrucciones y la memoria para datos están separadas, lo que permite que el procesador acceda a ambos simultáneamente. En la arquitectura Von Neumann, tanto las instrucciones como los datos se almacenan en la misma memoria y el procesador accede a uno u otro en momentos diferentes.

9.	¿De cuántos bits es el microcontrolador ATMEGA328P?
El microcontrolador ATmega328P es de 8 bits.

10.	¿De cuántos bits es el ADC del microcontrolador?
El ADC (convertidor analógico-digital) del ATmega328P es de 10 bits.

##### Sección 2

1.	Se requiere controlar un motor DC para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.
Falso. Un motor DC requiere más corriente de la que un pin de Arduino puede suministrar, por lo que se necesita un transistor o un driver de motor para controlarlo.

2.	Necesito conectar un LED a la tarjeta Arduino UNO ¿es necesario forzosamente poner una resistencia a tierra?
Cierto. Para limitar la corriente que pasa a través del LED y evitar que se queme, se debe utilizar una resistencia.

3.	Describe los comandos del git flow básico para subir archivos al repositorio de GIT.
Inicializa un repositorio con git init.
Añade archivos al área de preparación con git add ..
Crea un commit con git commit -m "mensaje del commit".
Conecta con un repositorio remoto con git remote add origin URL_DEL_REPOSITORIO.
Sube los archivos con git push origin master.

##### Sección 3
1.	¿Qué es una señal?
Una señal es una variación de una magnitud física que puede ser utilizada para transmitir información. Puede ser analógica o digital.

2.	¿Sería posible procesar una señal sin recurrir al muestreo?
No sería posible en sistemas digitales, ya que las señales analógicas deben ser muestreadas y digitalizadas para ser procesadas por un microcontrolador o un sistema digital.

3.	¿Por qué se debe muestrear una señal?
Se debe muestrear una señal para convertirla de una forma continua (analógica) a una forma discreta (digital) que pueda ser procesada por sistemas digitales.

4.	¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?
El tamaño de paso del microcontrolador se refiere a la resolución con la que puede manejar los datos. Un microcontrolador de 8 bits maneja datos en un rango de 0 a 255 en binario (00000000 a 11111111).

5.	¿Cuál crees que sea la diferencia entre lo análogo y lo digital?
Lo análogo es continuo, representa valores en un rango infinito, mientras que lo digital es discreto, representando valores específicos dentro de un conjunto finito.
