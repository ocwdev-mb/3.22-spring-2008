---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Superelastic and Superplastic Alloys - Problem Set 3
uid: 930bd449-6d42-b095-aae2-1811720720e4
---

_(b) Taillard, et al. \[[1](#ref)\] summarize Bouvet, et al.'s \[[2](#ref)\] attempt at a yield surface for superelastic alloys; this is a modification of the von Mises equivalent stress and criterion that we have discussed. Restate this criterion and its components in terms of the symbols used in class._

von Mises
---------

von Mises' (maximum distortion energy) criterion is "when the effective stress, defined as

{{< resource "25450270-7cbc-569c-0deb-5dd65ae0077f" >}}

exceeds the uniaxial yield stress, then the material will plastically flow." The criterion was stated by von Mises without a physical interpretation, but it is now accepted that it demonstrates the critical value of the distortion (or shear) component of the deformation energy of a body. Based on this understanding, a body flows plastically in a complex state of stress when the distortional deformation energy is equal to the distortional deformation energy in uniaxial stress (tension or compression). This criterion is also known as the J{{< sub "2" >}} plasticity criterion because it is the second invariant of the stress deviator.

Mathematically, the yield function for the von Mises condition is written as

{{< resource "48fd5c13-09b9-30c7-bcd1-a2dde5b13de0" >}}

or alternatively,

{{< resource "44819c85-fbdd-ef37-d693-ba85f645ca77" >}}

where _k_ is a critical value. Substituting the value of J{{< sub "2" >}} into this equation, we obtain the von Mises yield criterion as a function of the principal stresses:

{{< resource "bd19b407-b09d-ed04-e4f5-9761506c385f" >}}

Or as a function of the stress tensor components

{{< resource "9132c086-2ad5-250f-6bd4-313ce9de2789" >}}

This equation defines the yield surface as a circular cylinder whose yield curve, or intersection with the deviatoric plane, is a circle with radius {{< resource "a16028a9-332d-1a36-d435-374a3ed5cbb9" >}}. This implies that the yield condition is independent of hydrostatic stresses, as is implied by the fact that it was derived from the deviatoric stress tensor.

In the case of uniaxial stress or simple tension, {{< resource "2cf1ec3d-c5fc-57e2-542e-6e1186e6092f" >}}, so the von Mises criterion becomes {{< resource "5d1b216d-73c7-6c7e-975a-becef89ebb95" >}}. Using this equation, which gives the relation between the uniaxial yield stress,{{< resource "0ed37138-01cc-f0ea-ac3d-5b1bd1e06fb3" >}}, and the pure shear yield stress, _k_, the von Mises criterion can also be expressed as a function of {{< resource "0ed37138-01cc-f0ea-ac3d-5b1bd1e06fb3" >}}:

{{< resource "6428d859-e000-4d5d-25bd-7dfd5765eae6" >}}

For this equation, the radius of the yield curve is {{< resource "73aa8706-bd6b-c865-d20d-c244d7646f79" >}}. The yield stress {{< resource "0ed37138-01cc-f0ea-ac3d-5b1bd1e06fb3" >}} is also called equivalent stress or von Mises stress, {{< resource "9bffe14c-0925-b6a9-2fb8-767b3c935adf" >}}, which is used to predict yielding of materials under triaxial loading from results of simple uniaxial tensile tests. Thus,

{{< resource "24d52d8a-11b3-0f04-cdb6-9afd80ec9dc4" >}}

where {{< resource "f7552f4b-b517-d2d1-5b4d-889146123d77" >}} are the components of the stress deviator tensor. Projected into the {{< resource "2cf1ec3d-c5fc-57e2-542e-6e1186e6092f" >}} plane, the von Mises criterion is shown in the figure below.

  
 

{{< resource "e9a3aa5e-dda9-ff63-8751-90236b9c7312" >}}

  
 

Projected into the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane, the Von Mises criterion is shown in the figure below.

  
 

{{< resource "4bd09543-d789-c330-f115-bf0862bc5364" >}}

  
 

Taillard
--------

The Taillard plasticity criterion was stated as:

{{< resource "4dca40b7-09d3-7413-1989-b27c39777f7e" >}}

where

{{< resource "d9c79c7f-58c4-8df1-1d60-83f659164955" >}}

{{< resource "df1c829c-ee83-0e03-1d4e-959176672ac8" >}}

and _a_ is a material constant that is determined empirically, and {{< resource "aa673c58-be3e-2b9f-cbba-aa4de6f669f7" >}} is the effective stress described in the section above. In order for the above criterion to be expressed in notation consistant with the course materials, the term {{< resource "3ad24337-47aa-e7d4-b4dc-4edd3bc1055d" >}} must be expanded in terms of the component scalars. First, the stress deviator is defined as:

{{< resource "f647e684-75b2-75bf-f38f-a330969448de" >}}

The determinant of that tensor is therefore:

{{< resource "4d4a052b-1ff6-cc9a-ebfc-63e621080818" >}}

Therefore, the Taillard condition can be expressed in expanded form by substituting the above expressions for {{< resource "aa673c58-be3e-2b9f-cbba-aa4de6f669f7" >}} and {{< resource "3ad24337-47aa-e7d4-b4dc-4edd3bc1055d" >}} back into the original three equations that define it. I will refrain from that trivial substitution because it would be quite cumbersome for both author and reader.

Note that the projection onto the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} plane results in the simplifications:

{{< resource "31e73183-9984-5b07-3f34-dfd28bf0e1da" >}}

{{< resource "1ef79cc8-1bf5-fc3a-412a-fe910a355e28" >}}

{{< resource "c4f21620-5cbd-9a06-f0c7-1d8fd63076c5" >}}

Note that the projection onto the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane results in the simplifications:

{{< resource "d079a6b7-f6a0-8696-0960-0b9ad0f4af9f" >}}

{{< resource "f5e1a3fa-482e-79b0-b4a5-db3c733ee232" >}}

{{< resource "a72e5d43-e2dd-746d-7f94-2d6b12d23db9" >}}

_(c) Taillard, et al.'s Fig. 1 and 2 \[1\] demonstrate the yield surface in biaxial tension/compression and torsion for xCu-yAl-cBe, respectively. They claim Fig. 3 shows a difference between this response and that of NiTi. Graph the biaxially stressed yield surface for NiTi._

An arbitrary state of stress on the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane can be uniquely transformed into a position on the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} plane. This can be seen on the Mohr's circle, in which any conceivable state of stress can necessarily has two points with a principal stress and zero shear stress. However, there are states of stress on the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} plane that do not produce states of stress that fall on the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane. This can be seen on a Mohr's circle in which both principal stresses have the same sign, as shown below. This clearly means that data presented in the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} can be transformed onto the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane if and only if {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} has a different sign from {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}}.

  
 

{{< resource "3a1c2a38-2704-f090-12ce-03ec61b2c41e" >}}

  
 

Through Mohr's circle, Taillard's figures 2 and 3 can be transformed into the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} plane, and the data from the second quadrant of Taillard's figure 1 can be transformed onto the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane. All of this data was normalized by the uniaxial yield stress {{< resource "5c2fa307-aff6-fa46-1919-8f66b2df6b28" >}} so that it produced similar magnitudes for all materials and tested temperatures. The plot below shows the all three figures normalized and plotted in the {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}} plane. Interestingly, The NiTi data from figure 3 agrees quite well with the Cu-Al-Be data from figure 1, but the Cu-Al-Be data from figure 2 agrees with neither.

  
 

{{< resource "8981a577-0e9c-d577-7ab0-39377ae97cf9" >}}

  
 

To confirm that the transformations were done correctly, the same data (except for the Cu-Al-Be primary data, for reasons stated previously) was also normalized and plotted in the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} plane. Although the trend is less clear, it is still there; the NiTi data agrees better with the Cu-Al-Be data tested at 32°C than the Cu-Al-Be data tested at 60°C.

  
 

{{< resource "e081dca2-a8de-5b75-2c1c-4f7943db15b8" >}}

  
 

The change in yield surface between the two different temperatures for Cu-Al-Be could be explained if 60°C is above the A{{< sub "f" >}} temperature for Cu-Al-Be while 32°C is below the M{{< sub "f" >}} temperature for Cu-Al-Be and the testing temperature for the NiTi was below that materials M{{< sub "f" >}}. The changes between the two different temperatures of Cu-Al-Be would therefore represent two different phases of the material. This would indicate that the proposed yield surface would be appropriate for materials in their martensitic state but not for materials in their austenitic state. The agreement between the NiTi data and the Cu-Al-Be data taken at 32°C would indicate that the yield surface, when scaled properly, would characterize both the NiTi and Cu-Al-Be quite well.

_(d) Contrast the Bouvet yield surface with the other non-asymmetric yield surfaces considered in PS3. Is this equivalent to one of them or different, and how? What is the atomistic origin of the asymmetry justifying the Bouvet yield criteria?_

The yield surface presented in the papers is merely the Von Mises yield surface modified by the scalar, g:

{{< resource "4dca40b7-09d3-7413-1989-b27c39777f7e" >}}

Therefore, the yield surface is the Von Mises yield surface when _g_\=1. This happens when _a_(1-_y_{{< sub "σ" >}})=1. However, _y_{{< sub "σ" >}} is a complex function of the stress state, so there is no single parameter that causes this yield surface to degenerate to the Von Mises condition.

The yield condition presented in the papers is a curve fit of the data. Therefore, plotting the normalized source data along with the Mises and Tresca yield conditions will highlight the differences. This comparison is shown in both the {{< resource "851b1563-538a-0ad1-01c1-7cb4d1da4b9e" >}} vs. {{< resource "e0f2dcf0-8d51-6fe0-2b03-ec4cd873a50d" >}} and {{< resource "df582cc3-f0f7-866b-84b3-c1f67da3cd3f" >}} vs. {{< resource "c5b5dbde-2d74-ff5f-f5f2-c459baaa9203" >}}.

  
 

{{< resource "b390af61-9946-d626-e3b4-05d0be8002d9" >}}

  
 

{{< resource "20dca6fb-d199-2d05-2a6a-24227b8be688" >}}

  
 

What these plots highlight is the considerable difference between the symmetrical yield conditions, which have similar behavior in the compression and tension regimes while the superlastic yield surfaces has considerably different behavior in compression (negative normal stresses).

What is the atomistic origin of the asymmetry justifying the Bouvet yield criteria? The asymmetry justifying the Bouvet yield criteria is caused by a different behavior in compression regime or in tension regime. There is a tension-compression asymmetry (or strength-differential effect) in the yield stress. Through the atomistic aspect, first of all, the different behavior in compression regime and in tension regime can be explained by atomistic bonding energy. Exceeding the Bouvet yield criteria means that the material starts yielding, that is, plastic deformation. And plastic deformation is related to bond breaking and proportional to bonding energy.

Image removed due to copyright restrictions. Please see Fig. 1 in Sleight, Arthur. "Materials Science: Zero-expansion Plan." _Nature_ 425 (October 16, 2003): 676-676.

Compression is the regime of r \< r{{< sub "0" >}} and tension is the regime of r > r{{< sub "0" >}}. They are obviously different by intuition.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Taillard, K. et al. "Phase Transformation Yield Surface of Anisotropic Shape Memory Alloys." _Materials Science and Engineering A_ 438-440 (2006): 436-440.

\[2\] Bouvet, Cristophe, Sylvain Calloch, and Christian Lexcellent. "A Phenomenological Model for Pseudoelasticity of Shape Memory Alloys Under Multiaxial Proportional and Nonproportional Loadings." _European Journal of Mechanics - A/Solids_ 23 (January/February 2004): 37-61.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}} | {{% resource_link 149fee27-7560-a343-acc4-9df953361eaf "Problem Set 2" %}} | Problem Set 3 | {{% resource_link a7a6f0d3-b0ba-b69f-bbe7-33bf6be6aa67 "Problem Set 5" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}