# Josephson Parametric Amplifier(JPA) Design
Flux driven josephson parametric amplifier design with Metal. It consists of resonator, SQUID, capacitor and a pumpline.  
Resonator is short-circuited to ground by dc-SQUID and capacitively coupled to the transmission line.  
I analyzed and simulated JPA with HFSS, Q3D. Including rendering and analyzing every process is indeed possible with metal
but due to the license issue with the Ansys Software at my lab, I disconnected the metal with ansys, proceeded the ananlysis and processed the results in ansys GUI. Finally, I got the results from renderer and completed.  

I am continuously [modifying](https://github.com/bicycle315/JPA-design/tree/main/Design%20Modification) my design. I wanted 4.18mm length resonator so i set the length 4.18 but did not care about the shape of it at my [First design.](https://github.com/bicycle315/JPA-design/blob/main/210818_JPA.ipynb)   The [Second design](https://github.com/bicycle315/JPA-design/blob/main/211004_JPA_SQUID%2CResonator%20Modification%20%2B%20HFSS%2CQ3D.ipynb) was modified after Metal added SQUIDLOOP. Before SQUIDLOOP I just left this place as a blank and draw a rectangle at HFSS GUI. Now, I put **squid design** and also changed the resonator shape to what i wanted by giving **jog**. My [third design](https://github.com/bicycle315/JPA-design/blob/main/Design%20Modification/211014_JPA_3_Launchpad%2BCap%2Bresonator%20modification.ipynb) is special in that it got tapered launchpad and capacitor. Finally 
I rendered the design into hfss,q3d and got the eigenfrequency,capacitance respectively. Using these results I got the external Quality factor.

