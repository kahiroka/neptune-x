# Neptune-X
An Implementation of Neptune-X: Network Interface Card for X680x0

# Overview
The logic consisted mainly of an address decoder and an ISA bus bridge, the former implemented using one GreekPAK (SLG46826V-DIP) and one 74ALS15, the latter using another GreenPak.

- neptune-x-adrdec.gp6: address decorder, a9-a8 buffer, reset inverter
- neptune-x-bridge.gp6: ISA bus bridge, irq inverter

The other parts (74ALS245, 74AHCT245) are tri-state bus buffers for address and data.

# TODO
- Adjust timing in 68030 mode

# Links
- Original Design  
  [Neptune-X Home Page](http://www.amy.hi-ho.ne.jp/shimada/neptune/)

- Implementation Example  
  [Applause's Neptune-X](https://applause.elfmimi.jp/neptune-x/)
