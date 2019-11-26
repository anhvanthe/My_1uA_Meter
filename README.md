# My 1uA Meter

License: MIT

An open source portable current measurement from 1uA to 20mA range

More information: https://anhvanthe.wordpress.com (my blog)


## Development

For test and development, the first version will be not portable anymore

### Block Diagram

![alt tag](docs/Block_Diagram.png)

### Analysis and Design

Because the input range is wide, from 1uA to 20mA is 20'000 times, even with powerful MCU or ADC, you can't not measure it directly. 
Of-course you need convert current to voltage before you took it to MCU/ADC. 

There are several methods for measure current, simply can classify to 2 methods
* Direct measurement: Shunt resistor based, Current Transformer, Rogowski Coil
* In-direct measurement: Hall Effect, Flux gate sensors, Magneto-resistive current sensor

We can, also classify to Isolated and Non-Isolated.

This project using Shunt resistor based method. It's a **legendary** method, simple, cheap and good
 enough. With suitable calibrate technique, we can archive accurate results.  

                         



 

