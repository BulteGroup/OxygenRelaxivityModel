# A simplified empirical model to estimate oxygen relaxivity at different magnetic field strengths

Emma Bluemke, Eleanor Stride, Daniel Bulte

Institute of Biomedical Engineering, Department of Engineering Sciences, University of Oxford, UK

Questions? Raise an issue here on GitHub

![](r1Oximage.png)

### Abstract
Researchers have investigated using the paramagnetic relaxivity effect of oxygen on longitudinal relaxation as a means of inferring oxygenation levels for applications ranging from cancer therapy to seawater analysis. The relationship between PO<sub>2</sub> and R1 is linear and reproducible, and the constant of proportionality represents the relaxivity of oxygen, or r1<sub>Ox</sub>, in that material. However, there is considerable variability in the values of r1<sub>Ox</sub> reported, and they have been shown to vary by field strength and temperature. Therefore, we have provided an empirical model for estimating the relaxivity of oxygen in water, saline, plasma and vitreous fluids, accounting for magnetic field strength and temperature. 

The model agrees well (R<sup>2</sup>=0.93) with the data gathered from literature, ranging from 0.011-8.45T and 21-40°C. This provides a useful resource for researchers seeking to quantify PO<sub>2</sub> in simple fluids in their studies, such as water and saline phantoms, or bodily fluids such as vitreous fluids, cerebrospinal fluids, and amniotic fluids.

### About this notebook
The relaxivity values collected were from experiments performed over a timespan of five decades with a huge variation in experimental equipment and temperature measurement techniques. In addition, the values have often been extracted from original plots, some hand-drawn, which is a source of error, and converted from the various original units to s<sup>-1</sup>/mmHg, which can be another source of error. Experimental measurement of r1<sub>Ox</sub> can be difficult even within a relatively simple system such as water because the measurement accuracy depends on the proper selection of acquisition protocols and parameters (i.e. repetition and inversion times).

These limitations are a large source of potential error in the accuracy of this model, which could be solved by the NMR community producing new, modern measurements of r1Ox at a range of field strengths and temperatures. As a future direction of this work, we have hosted the open-source model code and current r1<sub>Ox</sub> measurements here on GitHub and invite the NMR community to share new r1<sub>Ox</sub> measurement results and re-fit the model to improve accuracy. In particular, we welcome future researchers to perform measurements in plasma or vitreous fluids at different field strengths and temperatures and re-fit this model. 
