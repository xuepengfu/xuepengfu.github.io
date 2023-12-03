---
layout: page
title: Numerical Studies
description: Numerical Studies about VIV/FSI
img: 
importance: 1
category: Numerical
---
# Frequency capture phenomenon of tandem cylinders undergoing VIV

### Background
A unique frequency capture phenomenon was discovered in a VIV experiment with tandem cylinders with different diameters. The dominant vibration frequency of downstream cylinder with small diameter ($$f_{SC}$$) is the same with that of upstream cylinder with large diameter ($$f_{LC}$$), although their intrinsic frequencies are not identical. This phenomenon is critical to the frequency model used in the engineering VIV prediction of in multi-cylinders systems. 

### Contribution
Mechanism study on the phenomenon were carried out, and the result reveals that the phenomenon is induced by the excitation force induced by the upstream riser wake. In this year we will carry out a more comprehensive experimental study of the mechanism in a towing tank with PIV and DNS numerical study. We hope to clarify the conditions under which this phenomenon occurs and propose the multi-cylinder response frequency model.

### Reference

1. **Fu, X.**, Fu, S.\*, Zhang, M., Han, Z., Ren, H., Xu, Y., & Zhao, B. (2022). Frequency capture phenomenon in tandem cylinders with different diameters undergoing flow-induced vibration. *Physics of Fluids*, 34(8), 085120.
2. **Fu, X.**, Xu, Y.\*, Zhang, M., Ren, H., Zhao, B., & Fu, S. (2020). Numerical simulation of vortex-induced vibration of two tandem cylinders with different diameters under uniform Flow. In *International Conference on Offshore Mechanics and Arctic Engineering*, 84409, V008T08A034a.
3. Zhao, B., Zhang, M.\*, Fu, S., **Fu, X.**, Ren, H., & Xu, Y. (2023). Drag coefficients of double unequal-diameter flexible cylinders in tandem undergoing vortex/wake-induced vibrations. *Ocean Engineering*, 270, 113642.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fresim.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sketch of Frequency capture phenomenon of tandem cylinders undergoing VIV.
</div>



<h1 style="margin-top: 80px;">Data-driven RANS turbulence model</h1>

### Background
The ultimate goal of this research is to develop a data-driven turbulence model capable of accurately simulating VIV of slender structures for engineering applications.

### Contribution
I have implemented a turbulence model based on the tensor invariance of the flow field that preserves Galilean invariance based on previous studies. Compared to the classic RANS turbulence model ($$k-\omega$$), the data-driven turbulence model does provide better Reynolds stress and flow field prediction results for steady flows. I am working on expanding the approach to simulate unsteady flow around cylinder.

### Reference
1. **Fu, X.**, Fu, S.\*, Liu, C., Zhang, M. Data-driven approach for modeling Reynolds stress tensor with invariance preservation. (arXiv: 2303.17178)



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/turmodel.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sketch of data-driven RANS turbulence model.
</div>


<h1 style="margin-top: 80px;">2D <em>vs.</em> 3D CFD simulation of bluff cylinder VIV</h1>

### Background
This is a preliminary investigation of the strip method based flexible cylinder VIV prediction research. I want to figure out if the three dimensional (3D) CFD simulation has significant effect on the prediction of bluff cylinder VIV compared with two dimensional (2D) simulation.

### Contribution
The influence of 3D simulation was quantified by correlation coefficient. The results reveal that the 2D and 3D numerical simulation results are close to the experimental results in response amplitude, frequency, hydrodynamic and phase difference. 2D simulation predicts poorly in some multi-frequency components of phase difference. However, the 2D simulation results are accurate enough, hence the 2D strip method is used to predict the VIV of flexible risers.

Related results are being prepared.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2d3d.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sketch of 2D <em>vs.</em> 3D CFD simulation of bluff cylinder VIV.
</div>


<h1 style="margin-top: 80px;">Strip method based flexible cylinder VIV prediction</h1>

### Background
This study is aimed to establish a framework for prediction for flexible cylinder VIV. The data-driven turbulence model will be implemented in this framework to enhance the prediction acurracy. The ultimate goal is to realize the demand of industry for VIV simulation. 

### Contribution
The 2D RANS model is used to simulate the flow field, and the 3D FEM is applied for solid field, specifically 3D beam model, simulation. The hydrodynamic forces obtained from flow field will be transmitted with the displacement of the solid field to realize the simulation of flexible cylinder VIV. We have conducted VIV experiments with various background currents and various configurations of slender structures. These extensive experimental data will be used as the foundation for verification and modification of the prediction model. 

Related results are being prepared.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/stripviv.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sketch of strip method based flexible cylinder VIV prediction..
</div>
