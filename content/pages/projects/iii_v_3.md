---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Effects of Multidimensional Defects on III-V Semiconductor Mechanics - Problem
  Set 3
uid: 8233726e-d8fe-061c-b415-6a97ebaf13a4
---

_(b) Why do Yonenaga, et al. \[[1](#ref)\] claim that understanding of dislocation dynamics is relevant to GaAsP studies (basic science and applications)? Please do not restate their arguments, but rather justify them through a more detailed analysis than they could consider in a paper intro._

An understanding of dislocation dynamics is extremely important for understanding the GaAsP system. First of all, it is very important to understand the dynamics of dislocations because they contribute to basic science and help verify theory.

From an engineering perspective, dislocation dynamics also pervade many aspects of GaAsP device processing and operation. Dislocations can act as electronic recombination sites for electrons and holes as well as short circuit channels. Thus, they must be minimized in the active regions of a GaAsP device. Device operation often results in a temperature increase, which activates diffusion processes. Dislocations which were not active at "normal" room temperatures, may all of a sudden be activated and climb at higher temperatures, under driving forces such as the stress fields from neighboring dislocations, leading to device degradation, as stated in Yonenaga, et al. \[[1](#ref)\] Understanding dislocations is also important during processing, as device processing often subjects materials to high temperatures and therefore activates diffusion processes such as climb.

Dislocations are also important for the substrate. If a GaAsP single crystal could be used as a substrate, dislocations are important because any dislocation that terminates on the substrate frontside surface will extend into epitaxially grown device regions and affect device operation. As the dislocation density also affects material strength, it is important to understand dislocation dynamics in order to engineer strong substrates that are resistant to mechanical deformation, especially bow. If GaAsP single crystals are not used (which is more often the case due to cost considerations and the difficulty in fabricating single crystal GaAsP) and a graded buffer on GaAs or Si is employed for the substrate, dislocation dynamics are just as critical. Lattice mismatch induces dislocations which, as mentioned, will affect device performance if they extend into the active region of the device.

_(c) Compare the observed GaP, GaAsP and GaAs critical shear stress (followed by a sharp drop in applied stress in Yonenaga's Fig. 1 \[[1](#ref)\]) to the corresponding theoretical shear strength of these materials, and discuss possible reasons for the relative discrepancies between theoretical and experimentally observed values among these three compounds._

There is a large discrepancy between the theoretical and experimental critical shear stresses. The shear moduli of GaAs and GaP are 32.85 GPa and 39.2 GPa, respectively. The theoretical critical shear stresses, approximately G/2 (or G/10 depending on the model used) are therefore 16.425 GPa (or 3.285 GPa) and 18.6 GPa (or 3.92 GPa) respectively. For GaAsP, which is an alloy of GaAs and GaP, we could expect an intermediate theoretical critical shear stress. Yonenaga, however, reports much lower critical shear stress, on the order of MPa for all three materials. The upper yield stresses are approximately 17.5 MPa, 12.5 MPa and 4 MPa for GaP, GaAsP and GaAs whereas the lower yield stresses are 11 MPa, 11.5 MPa and 3 MPa for the three materials. The discrepancy between the theoretical and actual critical shear stress can be attributed to dislocation motion. The theoretical shear stress assumes a perfect crystal and during shear, bonds along one atomic plane break and the atoms must overcome a potential barrier in order to align with and form bonds with the next row of atoms. However, in actuality, shear is caused by dislocation motion, which requires much less energy. Thus, the actual critical shear stress is orders of magnitude lower than the theoretical.

_(d) Given the stated impurity concentrations for the compounds considered by Yonenaga, et al. \[[1](#ref)\], determine the maximum (average) glide distance a dislocation would require to encounter a point defect._

Consider a volume, say V cm{{< sup "3" >}}, of the material.

Let the impurity concentration be x cm{{< sup "\-3" >}} .

Thus, the number of impurity atoms in the referred volume = V \* x

Assuming that the impurity atoms are homogeneously distributed in the crystal, studying the impurity distribution along a single dimension,

Considered Length = V{{< sup "(1/3)" >}}

Number of impurity atoms = (V \* x){{< sup "(1/3)" >}}

Average spacing between the impurity atoms along that length = (Considered Length) / (Number of impurity atoms) = x{{< sup "(-1/3)" >}} = L cms

For GaAs, with a Si impurity concentration of 10{{< sup "16" >}} cm{{< sup "\-3" >}}, L = 4.64 \* 10{{< sup "\-6" >}} cm

For GaP, with a S impurity concentration of 3.3\*10{{< sup "17" >}} cm{{< sup "\-3" >}}, L = 1.44 \* 10{{< sup "\-6" >}} cm

This is the maximum distance a dislocation needs to glide before encountering an impurity atom. Hence, the average distance a dislocation needs to glide before encountering an impurity atom = L/2.

It should be understood that we have assumed that in gliding through this distance, a dislocation does not encounter another dislocation first, that is, the average spacing between the dislocations is greater than L. However this can be easily seen from the fact that the density of the grown-in dislocations, in both GaAs and GaP, is about 10{{< sup "6" >}} cm{{< sup "\-2" >}} . From the definition of dislocation density, this is the number of dislocations per unit area. In other words, when you take a cross section of a plane perpendicular to dislocation length direction, then you see 10{{< sup "6" >}} dots uniformly distributed in that plane. So average spacing between two neighboring dislocations would be 1/(10{{< sup "6" >}} ){{< sup "0.5" >}} = (10){{< sup "\-3" >}} cm. Thus, the avg distance between to dislocations is orders of magnitude higher than the avg distance between 2 impurities. In all probability, a dislocation would encounter 2 impurities before it encounters another dislocation.

{{< anchor "ref" >}}{{< /anchor >}}Reference
--------------------------------------------

\[1\] Yonenaga, Ichiro, Koji Sumino, Gunzo Izawa, Hisao Watanabe, and Junji Matsui. "Mechanical Property and Dislocation Dynamics of GaAsP Alloy Semiconductor." _Journal of Materials Research_ 4 (March/April 1989): 361-365.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}} | {{% resource_link 4004d0a3-e09b-c1eb-db08-0be15d73640b "Problem Set 2" %}} | Problem Set 3 | {{% resource_link 3e7072d8-b2a1-1647-db86-2d7ac5cd83fa "Problem Set 5" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}