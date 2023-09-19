---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Defect Nucleation in Crystalline Metals - Problem Set 2
uid: 6ab0d9bf-3df7-cba9-3348-74c6c3b67d39
---

  
 

  
 

_(a) What is the average Young's elastic modulus of the Au nanopillar in Fig. 1A of Li \[[1](#ref)\]? From comparison of these data with E of Au reported in the literature, do you infer that elastic properties of Au are size-dependent down to these sample diameters?_

The average Young's elastic modulus of the Au nanopillar is the slope of the unloading curve which is equal to 48.5 GPa. The E of Au reported in literature is around 43 GPa along the direction which is the same direction in which the compression was done on the Au nanopillar. We conclude that the elastic modulus is not dependent on specimen size as it is a property that is related to the internal energy change associated with bond stretching or compression and thus does not depend on the size of the sample.

_(b) Derive the expression used several times by Li \[[1](#ref)\] relating the maximum shear stress generated within an indented material as a function of applied load, Young's elastic modulus, and indenter radius. You may wish to consult K. Johnson's Contact Mechanics \[[2](#ref)\]._

We are interested in modeling the maximum shear stress a material experiences when being indented. This is done by considering the elastic contact of two smooth surfaces. Among other things, we need to know how contact area changes with increased applied load. Contact mechanics allows us to do this so that we can also predict the deformation (stress, strain) in the region of the material affected by the contact.

We begin by describing the geometry of two surfaces being brought into contact. This allows us to define our problem in terms of critical variables.

Consider 2 surfaces in contact described by Eq. 1 and Eq. 2 below. Here, we assume that we have two smooth surfaces with surfaces which can be described by an equation which must be continuous up to the second derivative.

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
Surface 1:
{{< tdclose >}}
{{< tdopen >}}


{{< resource "9b3f1b8e-8cac-0b9e-8305-3988ba189c00" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Surface 2:
{{< tdclose >}}
{{< tdopen >}}


{{< resource "56de25e2-e6ff-b686-1bdd-ebe48d82ea62" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 2
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Therefore, the separation is _h = z{{< sub "1" >}} - z{{< sub "2" >}}_. However, this separation currently requires two different coordinate systems for its definition.

Switching to common set of axes: _x and y_

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "6ce23bdd-7312-301f-88cc-1b43403535ba" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 3
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Since these axes are arbitrary, we can pick them intelligently to make our description of the problem easier. Here, we choose our axes such that C = 0,

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "a246279f-82ee-059d-0161-732696c7e8d0" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 4
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

where _A and B_ are positive constant; _R' and R"_ are the principal relative radii of curvature.

We can get relations for A and B using geometrical considerations. This is done in Appendix 2 of \[[2](#ref)\], but omitted here for clarity.

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "5b09b089-b498-2ae8-3efa-add1fbc06525" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 5
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "29d54623-5290-905c-977b-96f38a8be4ee" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 6
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

where α is the angle between the axes of principal curvature of each surface (_x{{< sub "1" >}} and x{{< sub "2" >}}_)

We will now consider two surfaces of general shape, centered at _O_, deformed with a normal load _P_ applied (Figure 1).

  
 

Image removed due to copyright restrictions. Please see Fig. 4.2 in \[[2](#ref)\].

Figure 1 Schematic showing the geometry of the problem \[[2](#ref)\].

  
 

We now must utilize Hertzian contact theory to determine displacements, which then allow us to find strains and stresses. Hertzian theory makes some assumptions which must be declared at this juncture. It is assumed that each body can be regarded as an elastic half-space which is loaded over an elliptical area on its surface plane. This is done because well-developed solutions exist for solving boundary value problems for an elastic half-space. It is also assumed that the surfaces are continuous and non-conforming. The strains experienced by the half-space area small. These last two considerations are represented by the assumptions that the contact radius is much smaller than the radius of curvature of each body. Finally, it is assumed that the surfaces are frictionless.

During compression, distant points _T{{< sub "1" >}}_ and _T{{< sub "2" >}}_ move towards O by displacements _δ{{< sub "1" >}}_ and _δ{{< sub "2" >}}_.

Due to contact pressure, the surface of each body is displaced parallel to O in the z direction by _u{{< sub "z1" >}}_ and _u{{< sub "z2" >}}_ relative to _T{{< sub "1" >}}_ and _T{{< sub "2" >}}_.

Looking at points S{{< sub "1" >}} and S{{< sub "2" >}}, which are coincident within the elastic surface:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "56dc5b35-1b73-fa48-61e2-ed65470e4aaa" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 7
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

If we write _δ = δ{{< sub "1" >}} + δ{{< sub "2" >}}_ and use Eq. 6, we get elastic displacements:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "9dd73245-24ce-0962-26fb-9d61ad68acaa" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 8
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

At this point, we can consider the specific geometry of our problem of interest to simplify the equations which describe the evolutions of the contacting bodies.

For this situation, we are interested in the contact of two solids of revolution. A solid of revolution is a solid body which is obtained by revolving a plane figure about some axis.

_(R{{< sub "1" >}}' = R{{< sub "1" >}}" = R{{< sub "1" >}} ; R{{< sub "2" >}}' = R{{< sub "2" >}}" = R{{< sub "2" >}})_

Therefore: _A = B = ½(1/R{{< sub "1" >}} + 1/R{{< sub "2" >}})_

The circular symmetry of the problem means that the contact area will be circular (with a radius we will call _a_).

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "754aa97c-527d-2068-d20b-673df0b86584" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 9
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Where _(1/R) = (1/R{{< sub "1" >}} + 1/R{{< sub "2" >}})_ is the relative curvature.

A pressure distribution which gives displacements satisfying Eq. 9 is given in Johnson Section 3.4 \[[2](#ref)\]. This gives the stress resulting from an applied pressure over a circular area for an elastic half-space (Hertzian contact).

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "afb77d0e-777f-e5fb-6687-c3e60a48af5a" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 10
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

This pressure distribution gives the displacement:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "da75efcf-55ea-ff30-0790-8010b8b18085" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 11
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Since the pressure acting on the second body is equal to the first, we can write:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "e6d37148-b5e0-fe64-4ced-536e9f6468bb" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 12
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Substituting Eq. 11 into Eq. 9 for _u{{< sub "z1" >}}_ and _u{{< sub "z2" >}}_, we are left with:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "33ff1505-d53f-46e1-3721-c0dd585d8999" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 13
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Which give us the radius of circle contact, _a_, and the mutual approach of distant points, _δ_:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "38365527-4745-d5e1-d6f2-98f86a02f549" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 14
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "7b9bcda5-9634-e47d-d132-a2780839676e" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 15
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

The total load compressing the solids is:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "f09df7e1-1c0e-c2cf-5dc8-29447c258b0c" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 16
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

Substituting this into Eq. 14 and Eq. 15, we get:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "991ecd84-1c25-ec24-ccf5-821e3e937db2" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 17
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "a229ccce-d95b-0689-b5ce-b18c7e3bbbb2" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 18
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

We also get an equation for the maximum pressure, _p{{< sub "o" >}}_, if we compare our new expressions for _a_ and _δ_ with the old ones.

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "a4ec4379-1a8d-e6d2-ca2c-8994a1cf426f" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 19
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

We now have expressions for contact size, compression, and maximum pressure.

For this pressure distribution, the stresses beneath the surface along the z-axis are (refer to Johnson Section 3.4 \[[2](#ref)\]):

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "d9905bf3-3233-d977-fede-7732853e1484" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 20
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "72ab6a10-0c57-b31a-9a38-36ac3482e081" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 21
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

These are the principal stresses. Therefore, our principal shear stress is:

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "522df8e4-2db6-02c9-a4fc-1fc48db79289" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 22
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

We now plug in the values for our principal stresses to get an expression for the maximum shear.

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "ca2ac4db-b6bf-9fdd-7ae9-d28b5421e5a5" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 23
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

This principal shear stress is maximized at a depth of _z_ _\= 0.48 a (for ν = 0.3)_. This step was evaluated in Maple. Substitution gives us an expression for the maximum shear stress under an indenter.

  
 

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource "75bfe5e5-a777-8210-f448-51744cb22549" >}}


{{< tdclose >}}
{{< tdopen >}}
Eq. 24
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

  
 

P is the indentation load. R is the radius of curvature of the indenter tip. E\* is the effective elastic modulus.

This equation tells us that the maximum shear stress occurs below the contact surface and is equal to 0.31 times the maximum pressure. This can also be expressed in terms of variables which can be easily measured in an experimental situation. From this equation, we would expect critical plastic events to occur underneath the surface of an indented material.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Li, Ju. "The Mechanics and Physics of Defect Nucleation." _MRS Bulletin_ 32 (February 2007): 151-159.

\[2\] Johnson, K. L. _Contact Mechanics_. Cambridge, UK: Cambridge University Press, 2008. ISBN: 9780521347969.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}} | Problem Set 2 | {{% resource_link d45cc5b0-b455-db9c-d6d7-0a678a060851 "Problem Set 3" %}} | {{% resource_link 70049e7d-dc51-6444-051a-d2a4d929ff2d "Problem Set 5" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}