# Minecraft ALU

#### CMP-3004

#### Spring 2022

### Computer Organization

## Final Project

- Joel del Castillo
- Sebastián Mena
- Camila Zambrano

### Minecraft

Minecraft is a game created by Markus Persson, better known as Notch, and later developed by Mojang Studios, to finally be purchased in its entirety by Microsoft in 2014. The game has a sandbox structure, where the player is able to modify the terrain while building structures at will.

### Redstone and our project

One of the resources available in Minecraft is Redstone. This resource is obtained in the form of 'dust' and is capable of transmitting signals and giving power to other blocks found in the game. It works in a similar way to binary, where an element can only have two values, on or off.

![2c7b5cadb160bf879541e93cd4eeaaa7888f39e7_hq](https://user-images.githubusercontent.com/72953477/166343875-f7f1fbd3-086c-4adf-97fe-46ef28cb4c2f.jpg)

Based on this principle, complex circuits can be built to automate processes within the game, as well as to simulate real-world circuits. There are multiple blocks within the game that allow the realization of these processes, however, these are very basic and none of them have the complexity of a logic gate, so building circuits within the game is a low level task and perfect for a project of this subject.

![pack2733](https://user-images.githubusercontent.com/72953477/166343647-7469275a-2b7b-4127-80f6-f3422f2d7d4e.png)

Our project consists of a functional **16-bit ALU** in Minecraft. All the processes that are performed in an in-game circuit are mechanical. Every change, comparison and interaction between redstone signals works at the hardware level (in-game) so the more bits, the higher the complexity of the ALU.

## Boolean algebra

- Operations based on True and False values
- When electricity is flowing we'll call it True, otherwise False
- True and False can be represented as 1 and 0
- Three main operations
  - NOT
  - AND
  - OR

## NOT

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

## FULL Adder / Substractor 2bits

### Theory

![FULL](./Images/FULL/Adder-Substractor.png)

### Implementation

![FULL](./Images/FULL/Adder-SubstractorI.png)

## Compact full adder (4BITS)

### Implementation

![FULL](./Images/FULL/CompactAdder.png)

## ALU 16 BITS

### Theory

![ALU](./Images/ALU/ALU16bits.png)

### Implementation (without flags)

![ALU](./Images/ALU/ALUNoFLAGS.png)

### Implementation (complete)

![ALU](./Images/ALU/ALUC.png)
![ALU](./Images/ALU/ALUC1.png)
![ALU](./Images/ALU/ALUC2.png)
