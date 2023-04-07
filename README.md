

# Three Phase Controlled Inverter using PWM Technique

Working on Hardware project Basically Inverter is used to Convert DC Current to AC Current.
# Features

* Here we are working on 3-Phase because efficieny and power output increases. 
* But with controlled Inverter we can control the output DC Voltage because MOSFET as a switch can used to differ the output voltage by adjusting the pulse duration given to MOSFET from Arduino.

# Key Tools Used
* ARDUINO UNO
* MATLAB(Simulink) 
* Electrical Equipment like Transformer ,MOSFET, Diode Bridge Rectifier etc.
* DC Supply


# Key Accomplishment
* Improving my skills to deal the electrical equipment with the MATLAB Software.
* Came to know how to burn MATLAB Simulink in Arduino UNO.

# Screenshots

* MATLAB CIRCUIT DESIGN
![image](https://user-images.githubusercontent.com/112017748/190848443-cc0029a5-e216-4cc0-91e4-745159b75df7.png)


*  Hardware Design & Implementation

*  Block Diagram of Single Phase Inverter
*  The hardware implementation for the following circuits below is discussed in detail.
![image](https://user-images.githubusercontent.com/112017748/230600337-0cc51137-7dc8-4d53-a990-fcda459df49a.png)



* Pulse Card 

![image](https://user-images.githubusercontent.com/112017748/230600461-180b0da3-9291-4988-b094-3a33bcb0b2f5.png)


* HARDWARE OUTPUT
* ![image](https://user-images.githubusercontent.com/112017748/230600298-9846f129-6b6e-4ead-b0ac-b4c93fbe2025.png)
* Pulse Given to Opposite Driver circuit
![image](https://user-images.githubusercontent.com/112017748/230599694-068572e7-2d34-4e36-a60a-38068552bcfe.png)
* Pulses Given to Two Adjacent Driver Circuit 
![image](https://user-images.githubusercontent.com/112017748/230599717-4ddf3a9f-b4f8-4a12-b9fb-d36aa8fd6a23.png)
* Line To Phase Output(In Star Connected Load)
![image](https://user-images.githubusercontent.com/112017748/230599733-940bf4c9-a423-47d1-b392-92d601358057.png)
* Line to Line Output (In Star Connected Load)
![image](https://user-images.githubusercontent.com/112017748/230599747-c62b83f6-56ba-4924-8a0f-1a5d8494ca4d.png)

# Progress

Till now we have completed the First phase of this Project

* In phase 1 Do all the simulation on the MATLAB and Properly analys the result.

* In phase 2 we are going to implement Every individual circuit(e.g Bridge Circuit, MOSFET Gate Driver etc) and check the output of individual circuit.

* In phase 3 we Make the connection between ARDUINO UNO, MATLAB , and the Hardware Circuit that we implement.
