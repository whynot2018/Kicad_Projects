# Kicad_Projects

### 1.25-15V 0-350mA bench power supply 
https://danyk.cz/minizdroj2_en.html
![Alt text](/Bench_Power_Supply/minizdroj2.jpg "1.25-15V 0-350mA bench power supply ")
![alt text](https://raw.githubusercontent.com/whynot2018/Kicad_Projects/main/Bench_Power_Supply/minizdroj2.jpg?raw=true)

```
This is a simple linear bench DC voltage power supply with adjustable current limit. The output voltage can be set in the range of 1.25 to 15V and the current limitation 0 to 350mA. The voltage regulation uses well-known LM317 circuit. The current limiter uses a 0.3 ohm current sensing resistor (shunt). You can also use 0.27 or 0.33 ohm one. A 7812 circuit regulates the voltage for the OpAmp and also works as a voltage reference. The MC33171 OpAmp compares the shunt voltage to the voltage on the slider of the potentiometer. If the shunt voltage is higher, the OpAmp output will reduce the gate voltage of the MOSFET (FQP33N10) and thus limit the current. Current limiting mode is indicated by a red LED. In the power supply I used MYRRA 44268 transformer with 15V output voltage, 10VA power and 667mA maximum current. The output voltage at no load is approx. 18.3V. The bridge rectifier is made of SB340 or 1N5822 Schottky diodes to minimize the voltage drop. The 100k trimmer allows you to fine-tune the maximum adjustable current limit value, the 100 ohm trimmer the maximum adjustable output voltage. The LM317 circuit can be replaced with a compatible LM338 or LM350. It is also possible to use LM1084, LM1085 or LM1086, which have a lower dropout, but also a lower maximum input voltage (only 30V).
Warning! The device is powered from the mains. If constructed improperly, mains voltage can get to the output and cause an electric shock! It can also cause a fire. Capacitors can remain charged even after disconnected from mains. I do not guarantee the information provided. You do everything at your own risk. I take no responsibility for any damage. 
```
