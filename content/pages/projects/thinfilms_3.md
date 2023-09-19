---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Plasticity and Fracture of Microelectronic Thin Films/Lines - Problem Set 3
uid: 1cc6e515-e08d-3ae8-5946-4bd60d338299
---

_(b) Nejhad, et al. \[[1](#ref)\] present an analysis of retained internal stresses, and an associated elastic analysis in Eq. (8). Justify the form of Eq. (8) in terms of crystal structure of the two film materials of interest, and the origin of the strain terms._

  
 

Image removed due to copyright restrictions. Please see Fig. 7 in \[[1](#ref)\].

  
 

Let us consider the two-film structure model above; we can refer to ZnO as material 1, and Si{{< sub "3" >}}N{{< sub "4" >}} as material 2.

{{< resource "f051e263-505f-6f39-b4a6-a95f9fe47aba" >}}

And as shown by the paper, we have the table below:

  
 

Table removed due to copyright restrictions. Please see Table 1 in \[[1](#ref)\].

  
 

We can separate the compliance matrix to two parts: the first one is related to the 1, 2, 3 dimension, and the other is related to the 4, 5, 6 dimension below:

For Si{{< sub "3" >}}N{{< sub "4" >}} as material 2,

{{< resource "00c9bebd-ea05-83de-e399-995fcaa36daf" >}}

For ZnO as material 1,

{{< resource "0495a885-d567-67fc-7abc-75ea973e6dc6" >}}

For the two-layer composite, we can predict that the matrix has the below form,

{{< resource "62838669-396d-3303-4cff-512241b150f3" >}}

Now we need to determine P, Q, J, L, K and M from the matrices of materials 1 and 2. Let us determine them one by one.

We set the volume fraction of material 1 as a and the volume fraction of material 2 as b.The equation is shown below,

{{< resource "245c5144-c056-27d4-999b-66996de075de" >}}

{{< resource "4896e52d-3672-be4d-bc93-5301aaa5d9fc" >}}

{{< resource "7629f159-7964-c8f4-5d1d-db0ec5042f8c" >}} = extrinsic strain = thermal strain in this work

{{< resource "8f9bd21e-be77-d557-fdb9-8b2f7ebd307e" >}} = intrinsic strain =

1.  dopants
2.  "atomic peening" which causes compressive stress
3.  microvoids which cause tensile stress
4.  gas entrapment which causes compressive stress
5.  shrinkage during process which causes tensile stress
6.  grain boundaries

_(c) After Eq. (10) \[[1](#ref)\], the authors state that there are so many contributors of intrinsic strain that it is difficult to consider them quantitatively. Rank-order the sources they list in terms of relative amount of stress contribution for this system, and justify your answer._

The contributors of intrinsic strain mentioned in the literature are:

1.  dopants
2.  "atomic peening" which causes compressive stress
3.  microvoids which cause tensile stress
4.  gas entrapment which causes compressive stress
5.  shrinkage during process which causes tensile stress
6.  grain boundaries

For this system, the Si{{< sub "3" >}}N{{< sub "4" >}} and ZnO films are deposited through PECVD.

Among the 6 contributors above;

1.  No dopants are introduced in the process of PECVD method, so this effect is very small.
2.  The "atomic peening" mechanism refers to the reflected neutral atoms bombarding the growing film at low sputtering pressures. The paper does not use sputtering method, so this effect is also small.
3.  Microvoids are caused by poor quality of film during process, which depends on the material, the environment, and the growth rate during PECVD.
4.  Since plasma (Ar, for example) is used in PECVD, it is very possible that gas will be entrapped in the film. Therefore this contribution is relatively significant.
5.  Shrinkage often happens in ceramics during sintering. There is no sintering in the process, so this contributor is small.
6.  For Si{{< sub "3" >}}N{{< sub "4" >}}, it is an amorphous film, so there are no grain boundaries. For ZnO, this effect is possible.

Integrating and rank-ordering all the effects, I get the conclusion below:

4 > 3 > 6 > 5 > 1 > 2

_(d) Determine the % of residual stress in terms of the tensile and compressive failure strength of these two film materials. In other words, how closely does the residual stress in films or lines approach the failure stress of the bulk forms of these same materials?_

Use the material properties give in Table I,

{{< resource "b59e55af-6bb0-984c-abf5-49aeaa53b667" >}}

Given that residual strain is 10{{< sup "\-12" >}}

Substituting S matrix and residual strain into the residual stress tensor equation given above, we have residual stress,

{{< resource "f9eed9e7-63c4-a27a-38f1-a0c928d823d8" >}}

Provided yield stress of silicon nitride and zinc oxide is 900 and 412 MPa respectively.

Therefore, the residual stress is very small compared to the yield stress of silicon nitride or zinc oxide.

{{< anchor "ref" >}}{{< /anchor >}}Reference
--------------------------------------------

\[1\] Ghasemi-Nejhad, Mehrdad N., Chiling Pan, and Hongwei Feng. "Intrinsic Strain Modeling and Residual Stress Analysis for Thin-Film Processing of Layered Structures." _Journal of Electronic Packaging_ 125 (March 2003): 4-17.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}} | {{% resource_link 18f53477-73f8-8b4d-a912-b104d6509167 "Problem Set 2" %}} | Problem Set 3 | {{% resource_link c085c269-53e4-62fe-e9b1-2c684b93cd85 "Problem Set 5" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}