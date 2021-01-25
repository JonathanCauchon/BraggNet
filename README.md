# BraggNet: Complex Photonic Integrated Circuit Reconstruction Using Deep Learning

We propose the use of a deep learning model to reconstruct the physical design of complex coupled-cavity systems from their spectral response. The model is demonstrated using silicon photonic grating-assisted, contra-directional couplers consisting of thousands of Bragg periods. The contra-directional couplers are modeled as coupled optical cavities, for which a transfer matrix model is used to generate a synthetic dataset comprising a strategic design parameter space. A modular approach is adopted to build a deep learning model made of 6 sub-models trained to make high-accuracy prior and posterior predictions on specific physical quantities. The free-form, architecture-independent model allows the user to include any geometries to the design parameter space simply by including them in the training dataset. Upon proper training, the model achieves 1.4% mean absolute error on device reconstruction and hence 
proves suitable for inverse design applications. To show the potential of the approach, a second dataset is generated to emulate the fabrication conditions of a nominal design hindered by fabrication imperfections. The model is then trained on this dataset and used to reconstruct fabricated devices from experimental measurements, showing promise for on-chip fabrication diagnosis.


More information to come soon.

<div style="text-align:center; width:50%;"><img src="https://github.com/JonathanCauchon/BraggNet/blob/main/Screen%20Shot%202021-01-25%20at%2011.11.10%20AM.png" /></div>
                                                                                                                              
                                                                                                                                
hi
