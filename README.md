# Simple-driver-board
This is a simple driver board to interface directly with Huebner inverter. It is compatible with both Rev. 1 or Rev. 2.
Driver chips are Infineon Eice 1EDI60I12 and DCDCs are Murata MGJ2D051505SC. I used full 14p connector to interface so there would be no possibility of wire crossing. 
Each Eice chip has two outputs with two 1W resistors to dissipate current to gates. There is also possibility to connect inverted input, but i disabled it by wireing this to GND.
