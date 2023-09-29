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
  Set 2
uid: 0919f251-73fa-3bb8-24b6-200f1e8add7a
---

_(a) Jitsukawa, et al. \[[1](#References)\] summarizes steel's mechanical properties by starting with tensile yield and fracture strength. Elastic behavior is not mentioned. Explain why there is no extensive database on the variation in elastic properties of steel as a function of composition, processing, or radiation exposure._

There is no extensive database on the variation in elastic properties of steel as a function of composition, processing, or radiation exposure because these values vary very little inside different classifications of steels, as can be seen in the following graph:

{{< resource "eb535bd0-ea6b-893b-9f3f-0edf997e8ff8" >}}

Data compiled from \[[2](#References)\].

The yellow bars represent the variation of the Young's Modulus in each category, while the red and blue lines show the minima and maxima in each category. As one can see, there isn't much variation across the entire gamut of steels, with the notable exception of tool steels, though these are rarely used for large structural components such as nuclear pressure vessels due to their low ductility.

The fact that elastic properties do not vary much is because properties such as the Young's Modulus is primarily as a result of the interatomic potential, U(r) and equilibrium atomic separation, r{{< sub "0" >}} :

{{< resource "3551d016-15b7-84f1-f55e-a06516ff03c4" >}}

Equation for the Young's Modulus from material covered in class.

These shall not vary much for different steels due to the fact that they are majority-iron based alloys with relatively small percentages of carbon and other alloying elements. Tool steels tend to have much larger carbon concentrations as well as significant amounts of Mo and W to obtain the desired hardness and hence have the greatest variation in Young's Modulus.

On the contrary other properties such as the yield stress and ultimate tensile strength DO vary significantly and are due to differences in composition and processing. For example 308 Stainless Steel has a yield stress of 205 MPa when fully annealed, yet this is increased by a factor 8 to a yield stress of 1660 MPa when quenched. \[[2](#References)\]

_(b) Given that you know linear elastic behavior (expected of alloys like steel) is terminated at the start of plastic/permanent deformation, regraph Jitsukawa's Fig. 1 \[[1](#References)\] in terms of yield strain as a function of operating temperature. You could consider Fig. 8 as a representative source of elastic deformation data, or glean the other papers/literature._

Fig. 2 below is a plot of yield strain as a function of temperature:

{{< resource "aec0af8c-6f88-1a43-44f9-95c5a813adfd" >}}

Data to create this graph taken from Fig.'s 1 and 8 of S. Jitsukawa, et al. \[[1](#References)\]. Radiation levels for the irradiated specimen were 0.32 dpa at 300C.

In order to explain why irradiated steel would have a higher yield strain than unirradiated steel (counter-intuitive, isn't it?) one must look at the energy required for dislocations motion. In a non-irradiated crystal, one must only apply enough stress to overcome lattice friction, or at least lattice friction with a smaller number of vacancies, interstitials and voids. The entire lattice can elastically and uniformly deform only so much before dislocations get moving. In an irradiated material, there are more radiation-induced defects to pin dislocations, and therefore one must continue to apply stress until the dislocations can be unpinned. This results in more elastic deformation of the lattice required to get to the strain where dislocations will begin to move.

_(c) Based on Matthews & Finnis' \[[3](#References)\] speculation about where vacancy clusters and damage cascades occur within the crystal structure (Fig. 1), graphically represent the location and orientation of such vacancy clusters in steel. Here, you can assume a simpler alloy than the one discussed in Jitsukawa \[[1](#References)\], Fe containing a (thermodynamic) equilibrium concentration of carbon and a supersaturation of vacancies._

First of all, assume that the steel is BCC iron with a normal amount of carbon atoms on octahedral interstitial site at a low concentration - typically around 0.5% for a medium carbon steel. Normally it is very difficult to form vacancies on the Fe lattice, but radiation can knock just about any atom off its lattice site, so we assume a supersaturation of Fe vacancies. In addition, there would likely be a large number of vacancies from the steel having been quenched, since the equilibrium number of vacancies at a given temperature is given by (C{{< sub "v" >}} = n\*e{{< sup "(-Q/RT)" >}}, where Q is the activation energy and T is the temperature. Since Q does not change, and the concentration (C{{< sub "v" >}} ) is frozen in place at a higher T, there are many more vacancies than usual.

We have learned from 3.21 that forming an interstitial is more difficult than forming a vacancy. However, once an interstitial is formed, it tends to diffuse much faster than a vacancy. Furthermore the high amount of radiation present in a reactor would eliminate that barrier, so a damage cascade from a fast neutron (for example) will include a number of vacancies and interstitials. The interstitials will tend to diffuse away, while the vacancies are more likely to stay put as well as become trapped by other vacancies, forming voids in regions of high vacancy concentration, as shown in Fig. 1 of Matthews & Finnis, et al. \[[3](#References)\]

In the voids, there could be as many as two vacancies per unit cell, as a BCC unit cell contains two full atoms. In vacancy rich regions not encompassed by voids, there could be any number of vacancies per unit cell (below two), where the vacancy concentration drops with distance away from any vacancy-rich core.

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Jitsukawa, S., et al. "Recent Results of the Reduced Activation Ferritic/Martensitic Steel Development." _Journal of Nuclear Materials_ 329-333 (2004): 39-46.

\[2\] [MatWeb](http://www.matweb.com/).

\[3\] Matthews, J. R., and M. W. Finnis. "Irradiation Creep Models - An Overview." _Journal of Nuclear Materials_ 159 (1988): 257-285.

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}} | Problem Set 2 | {{% resource_link 065bdafc-ff95-dcc5-4d56-8854da744fe3 "Problem Set 3" %}} | {{% resource_link 1ffd3c1d-bf94-ae3e-1e22-3ec1fc1c3ba9 "Problem Set 5" %}}