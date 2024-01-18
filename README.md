# Analog-Design-of-LDO-with-PMOS-pass-device

This project discusses the design procedure of a conventional Low Dropout Voltage Regulator (LDO) circuit. The circuit consists of 2 stages, a 5-transistor operational transconductance amplifier (OTA) & a pass transistor, designed in 45nm CMOS technology. The circuit produces a regulated voltage of 0.9V using a reference voltage of 0.75V & a supply of 1.2V. 

![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/04c15b09-c090-4b91-b35d-f87cfd97c3be)
---------------------------------
### LDO Circuit Diagram
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/8fade7dd-4578-470d-aded-0730eb779a73)
---------------------------------
### LDO with RC compensation
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/779d58ed-b0b7-4045-a87f-d913e7117054)

---------------------------------
### Simulations
##### a) Monte Carlo - Offset Variation:
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/8552fb67-19e8-4355-987b-ec0791c3572e)
##### b) AC & STB - PSRR, PM, & Noise:
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/edb382bc-11f1-4707-9be3-1aa06c38bea6)
##### c) Noise:
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/21a15c60-3e29-4d39-8f61-4da8ecde4400)
##### d) Step-Load (Transient) VS AC/STB Sweep:
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/72178e32-9294-46df-beeb-e02bfb226804)

---------------------------------
### Results Summary
![image](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/assets/27668656/40321b3d-723c-4004-89f0-b245974f20e1)

---------------------------------
### Key References:
[1]	P. K. Hanumolu, "Low dropout regulators," 2015 IEEE Custom Integrated Circuits Conference (CICC), San Jose, CA, USA, 2015, pp. 1-37, doi: 10.1109/CICC.2015.7338435.</br></br>
[2]	T. Carusone, D. Jones, K. Martin, "Analog Integrated Circuit Design", 2nd Ed., Ch.7: Biasing, References & Regulators, John Wiley & Sons, Inc, 2012.</br></br>
[3]	B. Razavi, "The Low Dropout Regulator [A Circuit for All Seasons]," in IEEE Solid-State Circuits Magazine, vol. 11, no. 2, pp. 8-13, Spring 2019, doi: 10.1109/MSSC.2019.2910952.</br></br>

---------------------------------
### Project Links:
1) Report: [Project_Report_LDO.pdf](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/blob/main/Project_Report_LDO.pdf)
2) Testbench Details: [Testbenches_&_Results.pptx](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/blob/main/Testbenches_%26_Results.pptx)
3) Hand Analysis: [ldo_hand_analysis.pdf](https://github.com/muhammadaldacher/Analog-Design-of-LDO-with-PMOS-pass-device/blob/main/ldo_hand_analysis.pdf)
</br></br> >> Drive: https://drive.google.com/drive/folders/1lhqr3ftbG6R5mv5Qr27eAjxs_dBoFz7P?usp=drive_link
