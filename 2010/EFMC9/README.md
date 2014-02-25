## Reduced Order Models for control design using system identification

### AURÉLIEN HERVÉ, DENIS SIPP, PETER SCHMID, MANUEL SAMUELIDES *Euromech Fluid Mechanic Conference -- Sep, 13 2010*

## Abstract:
The design of efficient controllers for very large-scale fluid system requires the calculation of a reduced order model (ROM) that closely represents the input-output behavior of the full system. Such models are commonly derived from a Galerkin projection of the Navier-Stokes equations onto a specified basis, such as, e.g., a POD-basis. Using this technique, both the full flow state and the underlying model (Navier-Stokes equations) are required. In this study, two alternative methods of designing a ROM will be investigated, which are solely based on input/output informations from the system. The first approach consists of directly identifying a transfer function from a given actuator to a given sensor using both linear and nonlinear regression techniques (ARX, ARMAX, NARMAX, neural networks, etc.). The second approach consists of computing a POD basis and subsequently regressing its trajectory to identify the dynamics of the actuated system. Both strategies will be evaluated for flow over a backward-facing step. This flow configurarion is linearly stable but displays strong transient growth effects as upstream perturbations are amplified along the shear layer. Input noise is used to trigger the flow upstream. If the amplitude of the input noise is sufficiently small, the underlying dynamics can be described by a linear process, while for higher amplitudes, nonlinearities appear that have to be accounted for in the model. Nevertheless, issues related to the dimensionality and nonlinearity of the identification technique may be investigated separately. The figure below shows results from identifying the system dynamics using an ARMAX regression technique. More results will be presented and compared to those obtained from a classical Galerkin-POD projection approach.

## Download
[Download pdf](https://github.com/aherve/publications/raw/master/2010/EFMC9/EFMC9_herve.pdf)