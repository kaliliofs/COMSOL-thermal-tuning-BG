# COMSOL-thermal-tuning-BG

This project aims to simulate the thermal tuning, through a voltage source, on a Bragg grating.
The chip was fabricated in Advanced Micro Foundry (AMF) as a part from the active workshop sponsered by University of British Coloumbia and CMC Microsystems Canada. 

The project also contains tilted structure of the heater, i.e., to create a chired Bragg gratings. 

The change in temperature you get from COMSOL multiphysics simulation can be plugged into MATLAB to extract the change in the effective index (using Transfer Matrix Method TMM), 
please refer to Lukas Chrostowski book (Silicon Photonics Design: From Devices to Systems) for more information. 

The change in temperature along the Bragg grating can also be implemented in Charge or MODE (Lumerical Ansys software) to accurately calculate the effective refractive index. 
Then the neff matrix can be plugged in MATLAB using TMM to get the response of the Bragg (Transmission and Reflection) 

The MATLAB code also calculates the group delay for the chipred Bragg structure. 



"knowledge that others benefited from"
