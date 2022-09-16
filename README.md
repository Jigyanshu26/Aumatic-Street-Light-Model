# Timer-Interrupt
Automatic street light control using LDR as the sensor and an LED as an example of street light. Performed a small simulation of an arduino board along with LDR and LED to simulate the automatic street light control in TinkerCAD. Checking the LDR value for gating (with a delay of 1 minute generated by timer). Then based on the LDR value, the LED should be turned ON or OFF.

**Components Used**:-


![](https://github.com/harshb910/Timer-Interrupt/blob/main/Component-list.jpg)



**Circuit Diagram**:-


![](https://github.com/harshb910/Timer-Interrupt/blob/main/Screenshot%202021-10-22%20010408.jpg)



**Circuit Description**:-


![](https://github.com/harshb910/Timer-Interrupt/blob/main/Circuit%20description.jpg)


1) LED + resistor(1Kohm) and bulb are connected in parallel at PIN 8.
2) A Photoresistor to sense light is used and connected at PIN A5.
3) A BUILT_IN LED which get ON and remain on if there is darkness else it toggle from ON to OFF.
4) During daytime (means light is falling on photoresistor) then we read value  less than 722(considered).
5) During night time (means there is darkness) then we read value more than 722(considered) from pin A5.
6) It start measuring time of 1 minutes when there is first darkness fall and if after the darkness persist then bulb and LED will get ON.
7) If light persist then LED and bulb will get OFF.




**During daytime Bulb gets ON**:-


![](https://github.com/harshb910/Timer-Interrupt/blob/main/TimerOn.jpeg)



**During night time bulb gets OFF**:-


![](https://github.com/harshb910/Timer-Interrupt/blob/main/TimerOFF.jpeg)