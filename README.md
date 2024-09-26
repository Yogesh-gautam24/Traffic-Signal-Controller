# Traffic-Signal-Controller
This is Verilog based basedFSM Model to control the Traffic Signal.
There are two roads 1)Country Road 2)Highway road  
The Highway road is given more priority because There is more traffic..So its signal is always Green .When any vehicle comes on country road Sensor sends a signal to controller which changes the lights implementing a Mealy FSM with Five states. 
The states are described as 
      highway   country sig
s0    Green       Red
s1    Yellow      Red 
s2    Red         Red
s3    Red         Green 
s4    Red         Yellow
