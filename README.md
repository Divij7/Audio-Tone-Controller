# Audio-Tone-Controller

How to Use
Follow these steps to explore and simulate the Baxandall Tone Controller in LTspice:
Clone the Repository: Download or clone the project files to your local machine.
Open the Schematic: Launch LTspice and open the .asc file located in the /Simulations folder.
Run the Simulation:
To view the frequency response (Bode Plot), click the Run icon. The simulation is pre-configured with the command .ac dec 100 0.2 200k.
To test the time-domain behavior, the input is set to a 100 Hz sine wave with a 1V amplitude.
Toggle Audio Modes:
The circuit utilizes two switches (S 
1
​	
  and S 
2
​	
 ) to change the frequency response.
To change modes, right-click the Resistance value for R 
5
​	
  (Switch 1) or R 
4
​	
  (Switch 2).
Set the resistance to a very low value (e.g., 0.001Ω) to simulate ON or a very high value (e.g., 1GΩ) for OFF.
Analyze the Output: Click on the output node (the junction at R 
3
​	
 ) to view the shaped signal.
