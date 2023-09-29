---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Mechanical Behavior of a Virus - Problem Set 5
uid: d5ac3e4c-e98f-a66d-535e-a241535e0491
---

_(b) One of the cool things about a virus is that after the prohead shoots in the genetic material into the host cell (say, a bacterium), the genetic material is replicated until there is so much pressure that the host cell fractures. Assuming this is an E. coli bacterium with an initial crack size equal to the width of the prohead, find the Griffith fracture strength of the E. coli. You'll have to assume some properties to do this, so cite and justify these._

Assumptions (from literature):

*   crack size, a = 70 nm \[[1](#References)\]  
      
     
*   Elastic modulus, E = 0.4 GPa \[[2](#References), [3](#References)\]  
      
     
*   Surface energy, γ = 52 mN/m \[[4](#References), [5](#References)\]  
      
     

Computation:

σ = (2Eγ/πa){{< sup "(1/2)" >}} = 13.8 MPa

_(c) Ivanovska, et al. \[[1](#References)\] says the virus capsids are tough, but we said in class that this is the strain energy density up to the point of fracture. Assuming the fracture strength of a virus is 3 times the computed yield strength from PS3, and that the virus deforms in a linear elastic-linear strain hardening plastic mode up to the point of fracture, compute the toughness U{{< sub "T" >}}. Discussion on p. 7604 of their paper is also helpful._

From PS3 we calculated the yield stress to be 2.2 MPA and thus we can assume the fracture stress to be 3 times this value or 6.6 MPA.

From the following figures, taken from Ivanovska, et al., we see that the prohead dimension along the axis of stress/strain is 38 nm (Fig. 1). From Fig. 3, we see that the total strain distance the AFM tip moved from contact to fracture to be 62 nm - 29 nm = 33 nm. Thus the strain experienced by the prohead at fracture (rupture) is 33 nm/38 nm = .85.

Applying these values and the assumption of linear elastic and linear strain hardening we get a stress/strain curve as shown below.

  
 

{{< resource "d4f962c4-e364-f1ae-fd83-6eb37a6ca21b" >}}  
Courtesy of National Academy of Sciences, USA. Used with permission.  
Source: Ivanovska, I. L., P. J. Pablo, B. Ibarra, G. Sgalari, F. C. MacKintosh, J. L. Carrascosa, C. F. Schmidt, and G. J. L. Wuite. "Bacteriophage capsids: Tough nanoshells with complex elastic properties." PNAS 101 (2004): 7600-7605. Copyright 2004 National Academy of Sciences, USA.

  
 

The toughness can be computed from the figure below by finding the area under the stress/strain curve.

1/2\*.29\*2.2 MPa + (.85 - .29)2.2 MPa + 1/2(.85 - .29)(6.6 MPa - 2.2 MPa) = **2.783 MPa**

  
 

{{< resource "5d1ef217-7210-c8e8-7c13-6cdd5c43cbd5" >}}

  
 

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Ivanovska, I. L., P. J. Pablo, B. Ibarra, G. Sgalari, F. C. MacKintosh, J. L. Carrascosa, C. F. Schmidt, and G. J. L. Wuite. "Bacteriophage Capsids: Tough Nanoshells with Complex Elastic Properties." _PNAS_ 101 (2004): 7600-7605.

\[2\] Ramos, Daniel, et al. "Measurement of the Mass and Rigidity of Adsorbates on a Microcantilever Sensor." _Sensors_ 7 (2007): 1834-1845.

\[3\] Yao, X., et al. "Thickness and Elasticity of Gram-Negative Murein Sacculi Measured by Atomic Force Microscopy." _Journal of Bacteriology_ 181 (November 1999): 6865-6875.

\[4\] Lopez-Montero, Ivan, et al. "High Fluidity and Soft Elasticity of the Inner Membrane of Escherischia coli Revealed by the Surface Rheology of Model Langmuir Monolayers." _Langmuir_ 24 (2008): 4065-4076.

\[5\] van Oss, C. J., A. Docoslis, and R. F. Giese. "Role of the Water-air Interface in Determining the Surface Tension of Aqueous Solutions of Sugars, Polysaccharides, Proteins, and Surfactants." _Contact Angle, Wettability, and Adhesion_ 2 (2002): 3-12.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}} | {{% resource_link 17fb7a5b-c938-5875-d1ff-a27e6dd55da8 "Problem Set 2" %}} | {{% resource_link 2c6ba9bb-3678-ab89-4fd2-c075358cc9c5 "Problem Set 3" %}} | Problem Set 5  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}