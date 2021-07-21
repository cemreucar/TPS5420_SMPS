# TPS5420_SMPS

In this project, I designed a TPS5420 step-down converter using Altium Designer.

Here some information about TPS5420:

Features

•  Wide Input Voltage Range: 5.5 V to 36 V

•  Up to 2-A Continuous (3-A Peak) Output Current

•  High Efficiency up to 95% Enabled by 110-mΩ Integrated MOSFET Switch

•  Wide Output Voltage Range: Adjustable Down to 1.22 V with 1.5% Initial Accuracy

•  Internal Compensation Minimizes External Parts Count

•  Fixed 500-kHz Switching Frequency for Small Filter Size

•  Improved Line Regulation and Transient Response by
Input Voltage Feed Forward

•  System Protected by Over Current Limiting, Over Voltage
Protection and Thermal
Shutdown

• –40°C to 125°C Operating Junction

•  Temperature Range

•  Available in Small 8-Pin SOIC Package[1]

Description

The TPS5420 is a high-output-current PWM converter that integrates a low resistance high side N-channel MOSFET. Included on the substrate with the listed features is a high performance voltage error amplifier that provides tight voltage regulation accuracy under transient conditions; an undervoltage-lockout circuit to prevent start-up until the input voltage reaches 5.5 V; an internally set slow-start circuit to limit inrush currents; and a voltage feed-forward circuit to improve the transient response. Using the ENA pin, shutdown supply current is reduced to 18 µA typically. Other features include an active-high enable, overcurrent limiting, overvoltage protection and thermal shutdown. To reduce design complexity and external component count, the TPS5420 feedback loop is internally compensated.[2]

The schematic of the project:


![image](https://user-images.githubusercontent.com/59101099/126536713-484e972e-9911-4694-b1a2-987928047bd2.png)


The pcb of the project:



![image](https://user-images.githubusercontent.com/59101099/126536857-a59b668b-9970-4be1-955f-09e12420890d.png)







![image](https://user-images.githubusercontent.com/59101099/126537601-a71af159-2434-48ac-bc05-b0a788546dad.png)





You can find more information and datasheet of the project in here:

[1][2]https://www.ti.com/product/TPS5420?utm_source=google&utm_medium=cpc&utm_campaign=app-null-null-GPN_EN-cpc-pf-google-wwe&utm_content=TPS5420&ds_k=TPS5420&DCM=yes&gclid=CjwKCAjwi9-HBhACEiwAPzUhHNIzgCTU1DdgTSsThu4S4U56oIfcmMPudNVUgd2NqC-w40RY6FGKUxoCHq8QAvD_BwE&gclsrc=aw.ds


















