---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Plasticity and Fracture of Microelectronic Thin Films/Lines - Problem Set 2
uid: 18f53477-73f8-8b4d-a912-b104d6509167
---

_(a) Miller, et al. \[[1](#ref)\] noted the use of wafer curvature to infer stresses within thin films such as SOI. Derive the stress-curvature relationship given in Eq. 1, also known as the Stoney formula in the thin-film limit._

See the definitions of the symbols in Fig. 1, where l is the cantilever length. L is the arc length after bending, α is its corresponding center angle. θ is the angle between the original length and the bended length. R is the radius of the arch L. From the geometry

{{< resource "053635d9-935a-1621-4659-1bce93f194d8" >}}

Relations we know:

θ + β = π/2

2 β + α = π

thus α = 2θ

On the other hand, in the right-angle triangle l L δ

l{{< sup "2" >}} + δ{{< sup "2" >}} = L{{< sup "2" >}}

In the limitation that δ\<\<L, θ = δ/L

The length of the arch L corresponds to an center angle of α by

α = L/R

thus κ = 1/R = α/L = 2θ/L = 2δ/L{{< sup "2" >}} = 2δ/(l{{< sup "2" >}} + δ{{< sup "2" >}})

_(b) Graphically represent the structure of Si in SOI, at the unit cell and micrometer-scale level, and separately indicate the closest packed plane and direction in that plane for this structure._

At the unit cell scale level, Si has diamond structure. The unit cell is FCC, with Si atoms filling half the tetrahedron interstitial sites. The closest packed plane is {111}, and the closest packed direction in this plane is plane is \<110>.

{{< resource "dd25679f-3ce8-7eee-4e6e-c59184ad5cea" >}}

At micrometer-scale level, silicon thin film is single crystalline, with (100) oriented normal to the surface. SiO{{< sub "2" >}} is amorphous. The substrate can be single silicon wafer, sapphire, etc.

{{< resource "76bd708e-1e64-eba3-6df8-5ce7a138ddb2" >}}

_(c) During wafer bonding, blisters can occur at the wafer interfaces (Celler, Fig. 9 \[[2](#ref)\]). State the full tensorial stress state at the location of such a blister, and quantify the strains you would expect to correspond to this state in the adjacent Si._

Image removed due to copyright restrictions. Please see Fig. 9 in \[[2](#ref)\].

1\. We use a sphere to simulate the blister as in Fig. 1.

{{< resource "ececcfad-ebc7-9744-c96d-6b56ef505401" >}}

2\. The stress within the film equals σ.

3\. In the Smart Cut process, the thickness of the blister is relatively small compared to the radius of curvature of the blister. Therefore, we can use thin-wall approximation to approach this problem.

Stress:

  
 

{{< resource "33294c80-0656-30b1-dd2d-3ff727d09a08" >}}

  
 

From Fig. 2,

P = pressure in the blister

R = radius of curvature of the blister

t = film thickness

  
 

{{< resource "8d8cff3f-e321-e6d9-ef5b-0988febc1a39" >}}

  
 

4\. Radius of curvature of the blister:

  
 

{{< resource "4b1fda6a-8f69-e529-dd4d-901d24ce7f4d" >}}

  
 

From Fig. 3,

_a_ = radius of the circular base of the blister

_h_ = height at the center of the blister

  
 

{{< resource "d6b50158-cea3-a575-90e0-aec32bd11001" >}}

  
 

5\. Strain:

Before forming a blister, the profile of the film is along X{{< sub "L" >}}X{{< sub "R" >}} in Fig. 3. However, after forming a blister, the film profile is along X{{< sub "L" >}}X{{< sub "H" >}}X{{< sub "R" >}}. Therefore, the length of film along x or y direction is stretched from |X{{< sub "L" >}}X{{< sub "R" >}}| to |X{{< sub "L" >}}X{{< sub "H" >}}X{{< sub "R" >}}|. As a result, the strain along x or y direction is

  
 

{{< resource "e866e477-ccf5-8cbc-823c-94b9b90271b2" >}}

  
 

6\. Stress state:

{{< resource "5ec5b174-7a80-d054-208a-259e53e44c64" >}}

7\. Strain state:

{{< resource "981b96d6-27aa-7fe6-c5a5-5db3c37566aa" >}}

ν = Poisson's ratio of the film

E = elastic modulus of the film

For instance, a = 1000 nm; h = 40 nm; ν = 0.16 \[[3](#ref)\]

  
 

{{< resource "367ecb3a-ab46-c015-c85e-df36acafc6f5" >}}

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Miller, David C., Brad L. Boyce, Michael T. Dugger, Thomas E. Buchheit, and Ken Gall. "Characteristics of a Commercially Available Silicon-on-Insulator MEMS Materials." _Sensors and Actuators A_ 138 (2007): 130-144.

\[2\] Celler, G. K., and Sorin Cristoloveanu. "Frontiers of Silicon-on-Insulator." _Journal of Applied Physics_ 93 (May 1, 2003): 4955-4978.

\[3\] Piatkowska, A., G. Gawlik, and J. Jagielski. "AFM Studies of Hydrogen Implanted Silicon." _Applied Surface Science_ 141 (March 1999): 333-338.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}} | Problem Set 2 | {{% resource_link 1cc6e515-e08d-3ae8-5946-4bd60d338299 "Problem Set 3" %}} | {{% resource_link c085c269-53e4-62fe-e9b1-2c684b93cd85 "Problem Set 5" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}