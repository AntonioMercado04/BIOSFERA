# BIOSFERA

# Nombre del proyecto
Biosfera

## Descripción
El objetivo es hacer que un sensor detecte cuando en la tierra falta agua y nos avise con un LED

## Objetivos de aprendizaje
Con esta práctica se busca que el estudiante aprenda a leer una señal analógica con un sensor de humedad del suelo conectado a un Arduino, entendiendo cómo el convertidor analógico-digital transforma un voltaje en valores de 0 a 1023. También se trabaja la calibración de un sensor real, usando las lecturas en seco y en mojado para convertirlas a un porcentaje con map() y constrain(), y se aplica lógica condicional para tomar decisiones automáticas, como encender un LED cuando la tierra necesita riego. Además, se practica el uso del Monitor Serie para visualizar y depurar datos. Todo esto se conecta con el tema de Desarrollo Sustentable, al mostrar cómo la tecnología permite monitorear el suelo y optimizar el uso del agua en el riego.

## Material utilizado
Enumera todos los componentes usados:
- Arduino Uno R3
- Protoboar
- Led
- Cables Dupont
- Resistencia 220 ohms
- Sensor de humedad en tierra
 

## Diagrama del circuito

<img src="Diagrama/diagramabiosfera.png" width="300">


## Código
[led13.ino](Codigo/Biosfera.ino.ino)



## Video del funcionamiento

[Readme](Video/readme.txt)

[Ver video en YouTube]([[https://www.youtube.com/watch?v=T5Aq7cRc-mU](https://www.youtube.com/shorts/h1X20o2cAu0)]([https://www.youtube.com/watch?v=r36q2z-AkHk&sttick=0](https://www.youtube.com/shorts/h1X20o2cAu0))

## Evidencias de armado

<img src="Diagrama/diagramabiosfera.png" width="300">

## Reporte
Incluye:
[Resultados.pdf](Resultados/Resultados.pdf)

## Conclusiones
Con esta práctica se comprobó que un Arduino, junto con un sensor de humedad económico, permite monitorear el estado del suelo de forma automática y confiable. Se comprendió que las lecturas del sensor no son valores absolutos, sino que dependen de la calibración: fue necesario medir el sensor en seco y en mojado y ajustar los valores VALOR_SECO y VALOR_MOJADO para obtener un porcentaje de humedad realista. También se observó la importancia de la depuración, ya que errores como una placa mal seleccionada, un puerto incorrecto o un carácter sobrante en el código impiden que el programa funcione, y un sensor desconectado puede interpretarse como tierra seca si no se valida la lectura. En conjunto, la práctica muestra que este tipo de sistemas puede aplicarse al riego eficiente, evitando el desperdicio de agua y regando solo cuando el suelo lo requiere, lo cual se relaciona directamente con los objetivos del Desarrollo Sustentable.

## Resultados
[Resultados.pdf](Resutados/Resultados.pdf)

Este documento contiene la descripción de la práctica, objetivos y procedimientos realizados.

- Reporte técnico estilo IEEE (PDF)
- Datos CSV (si aplica)
- Diagramas adicionales
