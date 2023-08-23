# Autobalancing Robot 
## _Diseño de controladores para sistemas de proceso mediante criterios de estabilidad relativa/absoluta_

Objetivo: Diseñar algoritmos de control para sistemas de proceso mediante criterios de estabilidad absoluta/relativa.

## Materials
- Gyroscope accelerometer MPU-60505
- Two geared motors
- Arduino One
- H bridge
- Protoboard
- Two batteries of 9V
- Structure

## Control system
_Explanation of the control system_
Automatic control PID:
El controlador PID es un algoritmo de control ampliamente utilizado en de control de procesos. 
Consiste en tres componentes principales: la ganancia proporcional (P), la ganancia integral (I) y la ganancia derivativa (D). 

Kp = Ganancia proporcional: es la diferencia entre la posición deseada y la posición medida del robot.
Ki = Tiempo integral: es la suma acumulativa de los errores pasados.
Kd = Tiempo derivado: es la tasa de cambio actual del error

Los valores de Kp, Ti y Td deben ajustarse experimentalmente para obtener un rendimiento
óptimo del controlador en función de las características específicas del robot y del entorno.

## Values ​​used for PID control

- Setpoint = 175.6
- Proporcional Gain = 500
- Derivative Gain = 5.0
- Integral Gain = 460

## Conexion diagram
diagrama de conexiones para los motorreductores y giroscopio MPU-60505

[![Conexion-diagram.jpg](https://i.postimg.cc/3Rc2r6gP/Conexion-diagram.jpg)](https://postimg.cc/47pYBW25)

## Structural design
_El robot autoestable se compone de un cuerpo principal que alberga el controlador y los
sensores, y un conjunto de ruedas que le permiten desplazarse y mantener el equilibrio. La
elección de las ruedas o patas depende del diseño específico del robot y del entorno en el
que se utilice._
- First Prototype structural
- [![Prototype-Mark1.png](https://i.postimg.cc/d1TKpc33/Prototype-Mark1.png)](https://postimg.cc/r0cbRbS2)

- Final Prototype
- [![prototype-2.jpg](https://i.postimg.cc/2ScMYj1G/prototype-2.jpg)](https://postimg.cc/VJtDB8B0)


