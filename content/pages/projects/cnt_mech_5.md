---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Carbon Nanotube Mechanics - Problem Set 5
uid: e97933af-2b2a-00db-39e2-f452c5ee0c46
---

_(b) The papers you have chosen discuss the elastic properties of CNTs. Of course, the applications people are excited about are related to the high tensile strength of these organic fibers. We know they'll easily buckle in compression, and it's hard to think of apps that would benefit from that. Read the 2 papers cited by Pantano, et al. \[[1](#References)\] that discuss nanotube fracture to review this concept._

_Then compute the number of carbon bonds that must be broken to achieve tensile fracture of a single CNT (not a multiwall)._

Let's consider the case of a zigzag nanotube, as Belytschko, et al. \[[2](#References)\] discuss. In this case, fracture occurs around the circumference, when a circumferential set of bonds aligned axially with the tube are broken. Consider a sheet of graphite, specifically a set of parallel bonds. The equilibrium bond spacing given by Zhang, et al. \[[3](#References)\] is 0.1315 nm, and all bond angles are 120 degrees. Simple geometry is sufficient to determine the normal spacing between perpendicular bonds as \[0.1315\*√(3)\] nm, or, generally, \[bond length\*√(3)\]. The circumference of a nanotube of diameter d is simply π\*d, and we can divide this by the bond spacing to approximate the number of bonds along (and perpendicular to) the circumference that must be broken.

{{< resource "68846d03-70b9-375f-ff50-a19fdfe828f3" >}}

Note that r is the equilibrium bond spacing.

_It \[elastic energy stored at fracture\] should be the number of carbon bonds transversing the fracture plane, multiplied by the carbon-carbon bond strength, but is it?_

First, consider the general elastic energy stored per unit volume, and the simply transformed total elastic energy stored. (We are implicitly assuming there is no plasticity aside from fracture.)

{{< resource "99afab33-be55-8c03-dcf2-0f547c70ab4e" >}}

The modeling values of Belytschko, et al. will be used throughout. For stress purposes, the effective area over which the stress is applied is taken as the circumference of the nanotube multiplied by a value h, a wall thickness, which Belytschko, et al. take to be the interlayer separation of graphite h = 0.34 nm, and which is given as a standard value for this sort of calculation. Morse potential simulations \[[2](#References)\] give a failure strain of 15.7%, or a failure stress of 93.5 GPa. For the other constants, E = 1.16 TPa, A{{< sub "0" >}} = circumference\*h, L{{< sub "0" >}} = r = 0.1315 nm = equilibrium bond spacing. While the first bond fails before the fracture strain is reached, we will take the failure strain to be the strain at which the first bond breaks, and assume the difference is minimal since no plasticity is expected. Next, consider the number of atomic bonds over which this energy is distributed, given in Eq. 1 for a zigzag nanotube. Once a single bond is broken, fracture follows readily at little additional displacement \[[2](#References)\]. The expression simplifies as follows; note that the result does not depend on the nanotube size.

{{< resource "3acac1f0-f446-6c71-59b9-d65522bf9aa9" >}}

Using the previously given values, the energy applied to each bond at fracture strain is 0.91 eV; the dissociation energy for a single bond is given as 5.62 eV \[[2](#References)\]. Though this is within the expected order of magnitude, fracture is observed at a significantly lower energy investment than calculated, and Belytschko, et al. note that fracture has been observed experimentally at stresses significantly lower than even these simulations. It is worthy of mention that in the simulations of Belytschko, et al. one bond was weakened by 10%, guaranteeing the site of fracture nucleation, but this is not at all sufficient to explain this discrepancy. Using the Brenner rather than the Morse results in \[[2](#References)\] gives a result of 2.89 eV per atom, which is still significantly off.

These results can be extended to armchair or chiral nanotubes by appropriate modification of the function giving the number of bonds broken; Zhang, et al. \[[3](#References)\] show in Fig. 6 that fracture proceeds by the stretching and breaking of axial or semi-axial bonds, rotating the fracture surface about an axis normal to the tube such that it becomes angular/ellipsoidal.

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Pantano, Antonio, David M. Parks, and Mary C. Boyce. "Mechanics of Deformation of Single- and Multi-wall Carbon Nanotubes." _Journal of the Mechanics and Physics of Solids_ 52 (April 2004): 789-821.

\[2\] Belytschko, T., S. P. Xiao, G. C. Schatz, and R. S. Ruoff. "Atomistic Simulations of Nanotube Fracture." _Physical Review B_ 65 (2002): 235430.

\[3\] Zhang, P., Y. Huang, H. Gao, and K. C. Hwang. "Fracture Nucleation in Single-Wall Carbon Nanotubes Under Tension: A Continuum Analysis Incorporating Interatomic Potentials." _Transactions of the ASME_ 69 (2002): 454-458.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}} | {{% resource_link 9cb582dc-b511-d6b7-cc67-17acb8b18477 "Problem Set 2" %}} | {{% resource_link 9b78759d-a121-d57c-4c1b-bbb77f6f0a17 "Problem Set 3" %}} | Problem Set 5  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}