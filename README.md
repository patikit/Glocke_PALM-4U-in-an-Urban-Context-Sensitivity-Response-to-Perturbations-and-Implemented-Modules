# Glocke PALM-4U in an Urban Context: Sensitivity Response to Perturbations and Implemented Modules

To study the the short-term atmospheric response of the large eddy simulation urban climate model PALM-4U to disturbances of model parameters in Berlin, we provide the p3d files used in our study.
Using as dynamic forcing WRF, we developed different scenarios for studying the sensitivity, which are: (i) the influence of a 5~K soil temperature change in the deepest soil layer (2.91 m) in conjunction with and without the implementation of the bulk cloud model (BCM) and (ii) the effect of entirely adjusted soil temperature profiles in order to emulate a temporally more advanced state of heat diffusion in the soil, again under clear-sky conditions and for an overcast day.

In our study we developed three Cases:

## A: Influence of soil temperature anomalies on atmospheric fluxes with activated Bulk Cloud Model (BCM)
    We simulate two scenarios:
       A Reference scenario
       A Heat scenario: Where the deepest soil layer at 2.91 m depth is elevated by 5 K.
    
    
## B: Influence of soil temperature anomalies on atmospheric fluxes with disabled BCM
    We simulate the same two scenarios as in Case A:
        A Reference scenario
        A Heat scenario
  
## C: Impact of an adjusted soil temperature profile compared to the unmodified heat scenario on atmospheric fluxes} 
    We compare the influence of an adjusted soil layer compared to the unaltered heat scenario (as in Case A and B). In the adjusted scenario the lowest soil layer is increased by 5 K as well, but additionally the overlying soil layers also experience a soil temperature increase. This means that the temperatures change proportionally with height and e.g., half of the temperature difference (2.5 K) occurs at half of the depth. This scenario aims to simulate heat that is already more distributed in the soil, which is in a real urban environment more realistic.
    This is be carried out with:
        BCM activated
        BCM deactivated
