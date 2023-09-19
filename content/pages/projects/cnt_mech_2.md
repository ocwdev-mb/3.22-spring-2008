---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Carbon Nanotube Mechanics - Problem Set 2
uid: 9cb582dc-b511-d6b7-cc67-17acb8b18477
---

_(a) Pantano, et al. \[[1](#References)\] discuss several previously reported estimates of CNT elastic properties. Explain how the cited works in this review inferred the elastic properties of these CNTs from resonance of the structure (how did they do it, and how does resonance relate quantitatively to E?)._

Several different groups have performed experiments to determine elastic properties using vibration and resonance of the CNT structure:

Treacy, et al. (1996) \[[2](#References)\] used thermally induced vibration of cantilevered multi-walled nanotubes (MWNTs) in a TEM to determine a value of Young's modulus. Their technique involved placing MWNTs on the edge of TEM grid. With one end of the MWNT fixed on the edge of the TEM grid, the other end of the MWNT was free to move. Focusing the TEM on the free end of the tube was not possible because the tube was vibrating, due to thermal energy, in-and-out of the TEM focal plane. By measuring the width of the blurred tip, relative to the constrained end, the amplitude of the vibration could be inferred. The temperature of the MWNT was varied and a linear relationship was observed between temperature and mean-squared amplitude of the vibration. The Young's Modulus was determined from this information.

The vibration energy, W{{< sub "n" >}}, is the thermal energy in the system equal to **kT**, which obeys the Boltzmann distribution, and u{{< sub "n" >}} is the horizontal vibration amplitude of the tip.

{{< resource "d977fe17-4ce2-5bfa-ef1c-b63846b04446" >}}

The effective spring constant is given by

{{< resource "de125dc0-009a-8285-c4bc-e5ff7c98b023" >}}

where Y is the Young's Modulus, L is the tube length, a and b are the outer and inner diameters of the tube respectively, and the β term is related to the vibration mode of the MWNT, which is assumed to be analogous to that of a clamped cantilever. It is given by

{{< resource "6a203ee0-161a-7361-626f-e549b0a1345f" >}}

where ρ is the density of the CNT wall material. For CNTs at room temperature a frequency of 100 MHz can be expected. Using the above relations the Young's Modulus was inferred to be roughly 1.8 TPa on average.

Using the same technique as Treacy, Krishnan, et al. (1998) \[[3](#References)\] determined the Young's modulus to be between 0.9 and 1.7 TPa for a single-walled nanotube (SWNT).

Poncharal, et al. (1999) \[[4](#References)\] used a slightly different technique to infer the Young's modulus. This group mounted MWNTs on a specially designed TEM grid such that they could be biased. A grounded counter electrode was mounted within 20 um of the ends of the MWNTs. The application of a bias to the nanotubes caused a deflection towards to the grounded counterelectrode. By applying a time dependent oscillating voltage to the nanotubes, the resonance frequency could be found. The frequency was evident when large deflections were observed for relatively small voltages. Using essentially the same method and governing equation as in the previous two papers,

{{< resource "2e474c99-aab7-fc10-706f-0a736360f0d7" >}}

based on the assumption that nanotubes can be modeled as resonantly excited cantilever beams, allowed the calculation of Young's modulus. Poncharal, et al. confirmed previous measurements of modulus to be roughly 1 TPa.

_(b) On p. 795 \[[1](#References)\], the authors state that the CNT can be described with three elastic constants, but they also state that the wall material is isotropic. Isotropic materials require only 2 independent elastic constants, so demonstrate in terms of material and crystal symmetry why three are employed._

Two elastic constants are required for materials that are isotropic in space. The reference to the isotropic elastic properties of a two dimensional hexagonal structure as being isotropic indicates isotropy only in its two in-plane dimensions. Consider a graphene sheet: it is isotropic with respect to in-plane stretching and can be described fully with a stretching stiffness C and a Poisson's ratio v, the two constants we expect for an isotropic material.

The analogy between space isotropy and in-plane isotropy dissolves when we consider applying a load normal to the plane. In a spatially isotropic material, this can be viewed as an in-plane load on a different plane, identical to the first by spatial symmetry. In a two-dimensional sheet, however, an out-of-plane load causes a fundamentally different form of deformation. Consider the example of the graphene sheet: an in-plane load causes bond stretching and rotates bond angles in plane, increasing some and decreasing others. Now, consider a hexagonal junction in the form of a Y loaded out-of-plane: all bond angles are reduced. This unique deformation is governed by a separate elastic constant D, the flexural rigidity.

All three constants are required to describe a nanotube, a rolled graphene sheet. The in-plane or membrane stretching stiffness and the Poisson's ratio govern the behavior of the nanotube loaded axially, though this stiffness differs from the stiffness of the equivalent, unrolled sheet due to the change in geometry. The flexural rigidity governs the deflection of the nanotube. Unlike in the case of a spatially isotropic materially, it is not possible to describe this behavior in only two constants.

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Pantano, Antonio, David M. Parks, and Mary C. Boyce. "Mechanics of Deformation of Single- and Multi-wall Carbon Nanotubes." _Journal of the Mechanics and Physics of Solids_ 52 (April 2004): 789-821.

\[2\] Treacy, M. M. J., T. W. Ebbesen, and J. M. Gibson. "Exceptionally High Young's Modulus Observed for Individual Carbon Nanotubes." _Nature_ 381 (June 20, 1996): 678-680.

\[3\] Krishnan, A., E. Dujardin, T. W. Ebbesen, P. N. Yianilos, and M. M. Treacy. "Young's Modulus of Single-walled Nanotubes." _Physical Review B_ 58 (1998): 14013-14019.

\[4\] Poncharal, P., Z. L. Wang, D. Ugarte, and W. A. de Heer. "Electrostatic Deflections and Electromechanical Resonances of Carbon Nanotubes." _Science_ 283 (March 1999): 1513-1516.

  
  
 

{{% resource_link "d2c4d382-2bf8-b124-ef19-84d129bb758e" "Plasticity and fracture of microelectronic thin films/lines   " %}}{{% resource_link "6bc9399e-31b7-554b-381b-94e738195a04" "Effects of multidimensional defects on III-V semiconductor mechanics   " %}}{{% resource_link "4240da7f-1fee-9884-d011-d970176515dd" "Defect nucleation in crystalline metals   " %}}{{% resource_link "25015f4f-2da1-f23e-6220-37f2a8145e3f" "Role of water in accelerated fracture of fiber optic glass   " %}}{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}} | Problem Set 2 | {{% resource_link 9b78759d-a121-d57c-4c1b-bbb77f6f0a17 "Problem Set 3" %}} | {{% resource_link "e97933af-2b2a-00db-39e2-f452c5ee0c46" "Problem Set 5   " %}}{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}{{% resource_link "e97933af-2b2a-00db-39e2-f452c5ee0c46" "   " %}}{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}