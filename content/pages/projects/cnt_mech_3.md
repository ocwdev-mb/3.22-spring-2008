---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Carbon Nanotube Mechanics - Problem Set 3
uid: 9b78759d-a121-d57c-4c1b-bbb77f6f0a17
---

_(b) Pantano, et al. \[[1](#References)\] extensively model the elastic buckling instabilities of CNTs, and essentially find that computationally expensive MD and FEM simulations predict the same critical loads as Timoshenko's continuum elasticity theory for shells. In Pantano's model of cantilevered CNT bending, they completely neglect the possibility of plastic deformation at the fixed end of the CNT cantilever. However, if the stresses get high enough in the CNT "beam", plastic deformation will result. State the yield criteria / surface that you think best captures the onset of plastic deformation in a CNT (single or multiwalled; your choice), graph it as a yield surface under biaxial loading._

Modeling the CNT as a cantilevered beam the maximum stress at the support due to bending can be found:

{{< resource "1eeaed5d-403b-af18-dd68-e16dc0832853" >}}

where the moment, M = \[Force applied to the cantilever tip in the y-direction\] x \[Length of the nanotube\], and y is distance from the neutral axis. The area moment of inertia for a hollow tube is:

{{< resource "83d0f4dd-8eca-f0e2-c249-0553c6b27e30" >}}

where the D variables are the outer and inner diameter respectively. The highest stress occurs on the top and bottom surfaces of the tube (orthogonal to the direction of loading) at the support. When the stress in these regions reaches some critical value, bonds will be broken and the material will be irreversibly distorted. We propose a Tresca yield criteria to model this behavior. We are working under the assumption that graphene will respond similarly in tension and compression. Carbon nanotubes will not plastically deform, so instead of normalizing with respect to a yield stress, we will normalize with respect to tensile strength as experimentally determined in the literature. A range of values have been observed, but we will use the results from Yu, et al. who found an average tensile strength of roughly 45 GPa. \[[2](#References)\]

  
 

{{< resource "72a9cb4c-1d0a-f7fe-f17b-181a01e75e97" >}}

  
 

_(c) Determine the deflection required to induce plastic deformation under cantilevered point loading. Be sure to clearly state the assumed fixed-end boundary conditions, and cite primary sources for any required data._

The bending/buckling behavior of SWNTs can be solved accurately by numerical methods; to work by hand, we'll have to make a number of assumptions. We will take Pantano's effective modulus/effective thickness pair of 4.84 TPa and 0.075 nm, respectively \[[1](#References)\]. The bending stiffness is now calculable; as an example for this problem we'll choose an SWNT of R = 1 nm. Since the buckling behavior on the compressive side of the beam is beyond our ability to calculate, let's consider the tensile region. The tensile stress generally experienced by a beam is

{{< resource "b3100ac3-e05b-2ca6-3664-435efe709ef3" >}}

with a maximum at:

{{< resource "a0f7ca97-50b8-153a-946b-ab671d82cb89" >}}

We will get plastic deformation when this stress reaches the tensile yield stress. We can rearrange to see that yielding occurs when

{{< resource "238d12a0-0e99-486a-ffe8-6aeafa3a1634" >}}

This gives us information regarding the critical curvature to induce yielding.

Let us specify the cantilever loading boundary conditions for a beam with an end fixed at x = 0 as follows:

{{< resource "9d5c0309-2fce-7163-485b-38227b76d64a" >}}

These are the standard fixed-end boundary conditions. We need to find the deflection D which induces the yield stress in the beam, by finding the curvature generated by a specific displacement (specified for a general nanotube of length L, as D/L) of the free end. Working from the general case,

{{< resource "7d635d22-98c5-a825-ac86-c29372c4fdc6" >}}

Given our boundary condition on the first derivative of u with respect to x taken at x= 0, we can see that this constant B is zero. Integrating again,

{{< resource "7f554df5-f36e-21ee-1554-1759678cf97d" >}}

Given our boundary condition on u at x = 0, we see that this constant is also zero. Setting the stress equal to the yield stress and taking the value of c at R{{< sub "max" >}} to find the very earliest possible yield (minimum value of deflection), we get a minimum free-end deflection of

{{< resource "f6224d00-e08c-1a7c-e143-5e8580b6a41c" >}}

where L is the length of the nanotube between the free and fixed ends and R is its radius, with values of E and t (effective wall thickness) from Pantano, et al. \[[1](#References)\] as mentioned above, and using a minimum tensile yield strength of 11 GPa from Yu, et al. \[[2](#References)\] as referenced in Pantano, et al. \[[1](#References)\]. This is not an ideal yield stress value, as Yu, et al. focused on multiwall nanotubes; Yu, Files, Arepelli and Ruoff report breaking strengths for SWNTs between 13 and 52 GPa, with a mean of 30 \[[3](#References)\], and these values may be more appropriate.

_(d) Poncharal, et al. \[[4](#References)\] report the resonance of CNTs and demonstrate a frequency- and diameter-dependent response. Although this is structural resonance, it is similar in origin to the linear viscoelastic responses used to describe polymers. From this and other available sources, justify whether the CNT dynamics are best captured by a Maxwell, Kelvin-Voigt, or SLS model. Express the resonance of the CNTs in terms of the elements of the phenomenological spring/dashpot model you have chosen, keeping in mind that the elastic properties of the CNTs are well-known_.

We propose using a Kelvin-Voigt model to express the resonance of a carbon nanotube. This choice is justified because several groups have been able to model cantilevered beams using Kelvin-Voigt \[[5](#References)\], \[[6](#References)\], finding good agreement with the Bernoulli-Euler beam analysis technique, which was used successfully by Poncharal, et al. \[[4](#References)\] to study electromechanical resonance of CNTs.

In the case of Gurgoze, et al. \[[5](#References)\] the following physical model was chosen:

  
 

{{< resource "20f38e8a-2e8a-0bd6-3842-1713ba8e9268" >}}  
Courtesy Elsevier, Inc., [Science Direct](http://www.sciencedirect.com/). Used with permission.

  
 

Along with the corresponding phenomenological model:

  
 

{{< resource "f9639e35-215d-856b-55a2-1da269d769b7" >}}  
Courtesy Elsevier, Inc., [Science Direct](http://www.sciencedirect.com/). Used with permission.

  
 

The resulting eigenstate of the system according to the calculations of Gurgoze, et al. is given by:

{{< resource "6be6f97e-6f5e-dacf-c488-e10f27fc6ffa" >}}

Where d-bar is given by:

{{< resource "52d89b93-3f4f-c140-5d49-6e46cd19685d" >}}

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Pantano, A., Parks, D. M., and Boyce, M. C. "Mechanics of Deformation of Single- and Multi-wall Carbon Nanotubes." _Journal of the Mechanics and Physics of Solids_ 52 (2004): 789-821.

\[2\] Yu, M. F., Lourie, O., Dyer, M. J., Moloni, K., Kelly, T. F., and Ruoff, R. S. "Strength and Breaking Mechanism of Multiwalled Carbon Nanotubes Under Tensile Load." _Science_ 287 (2000): 637-640.

\[3\] Yu, M. F., Files, B. S., Arepalli, S., and Ruoff, R. S. "Tensile Loading of Ropes of Single Wall Carbon Nanotubes and their Mechanical Properties." _Physical Review Letters_ 84 (2000): 5552-5555.

\[4\] Poncharal, Philippe, Z. L. Wang, Daniel Ugarte, and Walt A. de Heer. "Electrostatic Deflections and Electromechanical Resonances of Carbon Nanotubes." _Science_ 283 (March 5, 1999): 1513-1516.

\[5\] Gurgoze, M., Dogruoglu, A. N., and Zeren, S. "On the Eigencharacteristics of a Cantilevered Visco-elastic Beam Carrying a Tip Mass and its Representation by a Spring-damper-mass System." _Journal of Sound and Vibration_ 301 (2007): 420-426.

\[6\] Mahmoodi, S., Jalili, N., and Khadem, S. "An Experimental Investigation of Nonlinear Vibration and Frequency Response Analysis of Cantilever Viscoelastic Beams." _Journal of Sound and Vibration_ 311 (2008): 1409-1419.

  
  
 

{{% resource_link "d2c4d382-2bf8-b124-ef19-84d129bb758e" "Plasticity and fracture of microelectronic thin films/lines   " %}}{{% resource_link "6bc9399e-31b7-554b-381b-94e738195a04" "Effects of multidimensional defects on III-V semiconductor mechanics   " %}}{{% resource_link "4240da7f-1fee-9884-d011-d970176515dd" "Defect nucleation in crystalline metals   " %}}{{% resource_link "25015f4f-2da1-f23e-6220-37f2a8145e3f" "Role of water in accelerated fracture of fiber optic glass   " %}}{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}} | {{% resource_link 9cb582dc-b511-d6b7-cc67-17acb8b18477 "Problem Set 2" %}} | Problem Set 3 | {{% resource_link "e97933af-2b2a-00db-39e2-f452c5ee0c46" "Problem Set 5   " %}}{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}