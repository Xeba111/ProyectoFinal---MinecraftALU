# Minecraft ALU

#### CMP-3004

#### Spring 2022

### Computer Organization

## Proyecto Final

Grupo compuesto por:

- Joel del Castillo
- Sebastián Mena
- Camila Zambrano

### Minecraft

Minecraft es un juego creado por Markus Persson, más conocido como Notch, y posteriormente desarrollado por Mojang Studios, para finalmente ser comprado en su totalidad por Microsoft en 2014. El juego tiene una estructura sandbox, donde el jugador es capáz de modificar el terreno mientras construye estructuras a su voluntad.

### Redstone y nuestro proyecto

Uno de los recursos disponibles en Minecraft es la Redstone. Este recurso que se obtiene en forma de 'polvo' es capáz de transmitir señales y darle poder a otros bloques que se encuentran el el juego. Funciona de manera similar al binario, donde un elemento solo puede tener dos valores, prendido o apagado.

![2c7b5cadb160bf879541e93cd4eeaaa7888f39e7_hq](https://user-images.githubusercontent.com/72953477/166343875-f7f1fbd3-086c-4adf-97fe-46ef28cb4c2f.jpg)

En base a este principio se pueden empezar a construir circuitos complejos que permiten automatizar procesos dentro del juego, así mismo como permiten simular circuitos del mundo real. Existen múltiples bloques dentro del juego que permiten la realización de estos procesos, sin embargo, éstos son muy básicos y ninguno de ellos tiene la complejidad de una compuerta lógica, por lo que construir circuitos dentro del juego es una tarea de bajo nivel y perfecta para un proyecto de esta materia.

![pack2733](https://user-images.githubusercontent.com/72953477/166343647-7469275a-2b7b-4127-80f6-f3422f2d7d4e.png)

Nuestro proyecto consiste en un **ALU de 16 bits** funcional en Minecraft. Todos los procesos que se realizan en un circuito dentro del juego son mecánicos. Cada cambio, comparación e interacción entre señales de redstone funciona a nivel de hardware (dentro del juego) por lo que mientrás más bits, sube proporcionalmente la complejidad del ALU.

## Boolean algebra

- Operations based on True and False values
- When electricity is flowing we'll call it True, otherwise False
- True and False can be represented as 1 and 0
- Three main operations
  - NOT
  - AND
  - OR

### NOT

![NOT0](./Images/NOT/NOTI.png)

## AND

### Theory

![AND00](./Images/AND/AND.png)

### Implementation

![AND00](./Images/AND/ANDI.png)

## OR

### Theory

![OR00](./Images/OR/OR.png)

### Implementation

![OR00](./Images/OR/ORI.png)

## XOR

### Theory

![XOR00](./Images/XOR/XOR.png)

### Implementation

![XOR00](./Images/XOR/XORI.png)

## HALF Adder

### Theory

![HALF](./Images/HALF/HALF.png)

### Implementation

![HALF](./Images/HALF/HALFI.png)

## FULL Adder

### Theory

![FULL](./Images/FULL/FULL.png)

### Implementation

![FULL](./Images/FULL/10.png)
![FULL](./Images/FULL/11.png)

## Adder SUBSTRACTER

### Theory

![SUBSTRACT](https://user-images.githubusercontent.com/72953477/166628898-ce48b125-a54e-4543-b40e-f13c571d35ed.jpeg)

## COMPACT Full Adder

![COMPACT](https://user-images.githubusercontent.com/72953477/166628992-962869aa-0221-4cba-b374-f7ada3e21cd8.jpeg)

