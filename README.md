# McCabe Thiele Method


[<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white" />](https://github.com/koroshkorosh1) 
[<img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />](https://github.com/koroshkorosh1) 
[<img alt="Pandas" src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />](https://github.com/koroshkorosh1) 
[<img alt="Numpy" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />](https://github.com/koroshkorosh1) 
[<img alt="Plotly" src="https://img.shields.io/badge/Matplotlib -239120?style=for-the-badge&logo=plotly&logoColor=white" />](https://github.com/koroshkorosh1) 

### **McCabe-Thiele Method**
<p class="text-justify">The method was first published by Warren L. McCabe and Ernest Thiele in 1925, and is a graphical procedure of determining the number of trays within a distillation collumn. The Murphree tray efficiency modifies the equilibrium curve of the two components in order to better account for non-idealities.</p>

### **Current implimentation**
The current implementation presented here allows for a Murphree efficiency to be applied to the classical McCabe-Thiele plot. Whilst it is relatively easy online to find McCabe-Thiele 'calculators', there are few that have implementations accounting for the Murphree plate efficiency. 

![image](https://s22.picofile.com/file/8447853292/Web_capture_26_2_2022_225328_drive_google_com.jpeg)

### **Limitations**
* The molar heats of vaporization of the feed components are equal
* For every mole of liquid vaporized, a mole of vapor is condensed
* Heat effects such as heats of solution are negligible

![image](https://s23.picofile.com/file/8447853792/Screenshot_2022_02_26_232853.png)

 We have already developed the McCabe-Thiele Graphical Method for cascades. The sameequations we used for the ```operating lines```, ```q-line```, and ```equilibrium curve``` can be used to solve for the compositions in each stage algebraically.

![image](https://s23.picofile.com/file/8449046084/chemecube_logo_wide_2_1_.png)
<br />
[](../../../../file/8447853792/Screenshot_2022_02_26_232853.png)