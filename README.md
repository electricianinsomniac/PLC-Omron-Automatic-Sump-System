# PLC-Omron-Automatic-Sump-System
PLC Omron Explanation of the automatic sump system by CX-Programer, CX-Designer, On CX-One;

## Project
How to program PLC with CX-Programmer 

- The initial condition of the tank is empty
- When the start is pressed, the pump fills the water in the tub
- When L lights up detecting the lowest water level, then the pump is in ON condition to fill water.
- When H lights up detects the water level reaches a high level, then the water pump will be OFF.
- When the water faucet is opened, the water in the tub will decrease so that H will die. water is reduced until L detects, so the pump will turn on
- When the water is full H will turn on again and the water pump will

Video: [Explanation about project PLC](https://youtu.be/Ltjh9YDgiBw) 

## Details
The Input and output of this project 
- Input
tombol : ON = I-0;
tombol : OFF = I-1;
Sensor low level : I-2;
Sensor High Level : I-3;
- Output:
Pompa : Q-0;
Indicator pompa ON : Q-1;
Indicator pompa OFF : Q-2;

![I/OTables](IO-Tables.PNG)
![P1](P1.jpg)
![D1](D1.jpg)
![A1](A1.jpg)

## Another PLC Project
Video: [PLC Omron Filling Of Bottles](https://github.com/electricianinsomniac/PLC-Omron-Filling-of-bottles-Automation)
