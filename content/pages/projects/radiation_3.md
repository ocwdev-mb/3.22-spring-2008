---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Effects of Radiation on Mechanical Behavior of Crystalline Materials - Problem
  Set 3
uid: 065bdafc-ff95-dcc5-4d56-8854da744fe3
---

_(b) Garner, et al. \[[1](#Reference)\] claim that vacancies such as those induced by radiation damage produce an isotropic strain field. Prove that this is so, and explain whether this strain contribution is expected to contribute to plastic deformation via dislocation glide._

> "If microscopy is employed to measure swelling, the only major strain detected is that due to void formation, a process known to be completely isotropic in its distribution of strain." – Garner, et al.

Assuming a void is a spherical section of missing material, and assuming the void is not near any surface, there will be equal pressure from all sides from lattice atom repulsion in a cubic material. In the case of a single radiation-induced vacancy, it is likely that once the vacancy-interstitial pair is produced the interstitial easily diffuses away because the activation barrier for interstitial diffusion is much lower than that for vacancy diffusion. This leaves a vacancy in a (perfect) lattice. Each of its nearest neighbors is an equal distance away from the core of the vacancy, and therefore the lattice exerts equal pressure on the vacancy from all sides. This will strain the lattice isotropically in the direction of the vacancy.

As far as dislocation glide is concerned, one must look at the interactions of the stress fields produced by both the dislocation and the vacancy. A vacancy's stress field is isotropically tensile, because the nearest neighbors (and next and so on) will relax into the vacant site a bit, stretching the lattice locally. A vacancy in the path of a dislocation may impede its glide motion, because a vacancy interacting with a dislocation can reduce the overall energy of the system by being absorbed by the half plane, producing one atom's worth of dislocation climb. This correlates with experimental evidence of irradiation at low temperatures causing materials to become stiffer, for at a low temperature vacancies cannot easily diffuse from the sites in which they were created. This results in an increased fracture stress, implying that the motion of dislocations has been impeded.

_(c) Garner, et al. \[[1](#Reference)\] then discuss that ion bombardment at metal surfaces can lead to plastic deformation, e.g., via blistering bubbles of subsurface trapped gases. Treat such a blister as a spherical pressure vessel surrounded by your choice of metals discussed in the other two papers (this will set the mechanical properties of the material surrounding the gas bubble. Assume a subsurface bubble size of 0.5 micrometer radius, and determine the gas pressure required to initiate plastic deformation and consequent roughness for a bubble centered 1 micrometer beneath the initially flat surface._

Assumptions
-----------

Material around gas bubble can be modeled as a spherical pressure vessel. Outer radius of pressure vessel, r{{< sub "o" >}}, taken to be the center of gas bubble beneath the material surface

{{< resource "fb8c17b5-3fb4-49ad-60ba-b7b1b7ce50ae" >}}

Since _r/t_ \< 10, must use "thick wall pressure vessel theory

{{< resource "6ecb0a47-99b3-9574-7deb-4505907263f0" >}}

RVE: Radial and hoop stresses are the principal stresses

{{< resource "61989447-637a-38d5-3326-e9fdb5610bac" >}}

From von Mises yield criteria:

  
 

{{< resource "cd9c96e0-b1bc-fe5f-f105-0f6f5e7e05fa" >}}

{{< resource "b69e2d3e-ff1e-b15b-03d6-c4a76ea7dc61" >}}

{{< resource "33fe7896-aa6f-b294-d968-eb8b2379ac9b" >}}

{{< resource "e1a6b801-7236-bece-8b85-8274d2633ee7" >}}

{{< resource "ea2b8054-d1da-cac7-3140-40fdf0fe1a30" >}}

{{< resource "d1fe50b3-8d07-da8c-9673-b0e8e919786d" >}}

  
 

_(d) Others have noted the superposition of lateral stress that contributes to plastic yielding at the surface. Explain the source and expected contribution of lateral stress for this metal._

The lateral stress would have the effect of squeezing the FCC and BCC grains in the steel. This lateral stress is due to thermal expansion, and is hydrostatic everywhere except near the surface, where it is essentially a two dimensional stress. The grains will therefore expand in the direction normal to the surface, and Fig. 1 in Garner, et al. shows that the FCC austenite grains are strained more than the BCC ferrite grains.

In addition, lateral stresses arise from voids created by ion bombardment. These are often due to gas pressure or to gas-free void nucleation, and are isotropically distributed throughout the plane parallel to the surface assuming constant normal irradiation. All these lateral stresses would have the effect of squeezing all the grains from four of its six sides, and these lateral stresses will cause the grains to expand into the free surface.

Mathematically, if the bulk of a crystal experiences a hydrostatic stress S from a combination of thermal expansion, void creation, gas bubble formation, and other processes, than at the surface σ{{< sub "1" >}} = σ{{< sub "2" >}} = S, and σ{{< sub "3" >}} = 0. Therefore the lateral strain in the direction normal to the surface would be twice the Poisson's ratio times the hydrostatic stress in the crystal bulk.

{{< anchor "Reference" >}}{{< /anchor >}}Reference
--------------------------------------------------

\[1\] Garner, F. A., and D. S. Gelles. "Irradiation Creep Mechanisms: An Experimental Perspective." _Journal of Nuclear Materials_ 159 (1988): 286-309.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}} | {{% resource_link 0919f251-73fa-3bb8-24b6-200f1e8add7a "Problem Set 2" %}} | Problem Set 3 | {{% resource_link 1ffd3c1d-bf94-ae3e-1e22-3ec1fc1c3ba9 "Problem Set 5" %}}