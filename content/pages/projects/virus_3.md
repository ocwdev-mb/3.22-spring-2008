---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Mechanical Behavior of a Virus - Problem Set 3
uid: 2c6ba9bb-3678-ab89-4fd2-c075358cc9c5
---

_(b) Considering Ivanovska, et al.'s Fig. 1E \[[1](#References)\] rendering of a bacteriophage prohead "shell", compute the stress required to initiate plastic deformation if the prohead were considered to be a short cylindrical shell under uniaxial compression._

Ivanovska, et al. \[[1](#References)\] states on p. 7604 of the manuscript that proheads responded linearly to indentation forces up to approximately 2.8 nN. Define this as F{{< sub "yield" >}}. From this, we can calculate the stress required to initiate plastic deformation, σ{{< sub "y" >}}, based on the cross-sectional area A. In other words, we're given F{{< sub "yield" >}} = 2.8 nN; and σ{{< sub "y" >}} = F{{< sub "yield" >}}/A.

**Finding cross-sectional area A:** The manuscript states that the cantilever used was OMCL-RC800PSA from Olympus. Based on the manufacturer specifications \[[2](#References)\], the probe is a sharpened pyramidal tip, but we'll approximate it as a cone here with a tip radius **r = 15 nm, tip angle θ = 45°, tip height h = 2.9 μm** (Fig. 1). Because the prohead and cantilever are of comparable sizes, we cannot model the prohead surface area being acted upon as a flat plane. Thus we cannot simply take the tip area to be our cross sectional area. Our actual cross-sectional area is the projected contact area (shaded region in Fig. 1). Therefore, using cone geometry, we can find A via **A = π**(r{{< sub "1" >}}){{< sup "2" >}}, where r{{< sub "1" >}} is as indicated in Fig. 3. To calculate this, we need to know the strain at yield point, which is provided by the manuscript (pg. 7604): **strain{{< sub "yield" >}} = maximum linear displacement = 12 nm**. Using trigonometry, we're able to find the following value: **r{{< sub "1" >}} = 19.97 nm**. Therefore, **A** = **1252.2 nm{{< sup "2" >}}**.

{{< resource "9a4e9fcc-2fef-81c2-3314-e25592f1c30d" >}}

Fig. 1. Cantilever Probe Tip. Dimensions based on manufacturer specifications of OMCL-RC800PSA from Olympus. Tip is approximated as a cone with tip radius r, tip height h and tip angle theta. Shaded region indicates cross sectional area used for yield stress calculation.

**Finding σ{{< sub "y" >}}: σ{{< sub "y" >}} = 2.8 nN / (1252.2 nm{{< sup "2" >}}) = 2.2 MPa**

_(c) These authors \[[1](#References)\] state that imaging of the proheads in contact mode atomic force microscopy (AFM) allows for the study of prohead deformation under "uniaxial pressure." This is incorrect at several levels. Develop a brief, justified objection to this claim, considering the design of the experiment in detail._

The authors used scanning force microscopy (SFM) to image the proheads under different maximal loading forces and **assumed** this to be "**uniaxial pressure**". However, given the imaging modality rasters an AFM tip, with a contact region of approximately 5 nm, across the virus prohead, which itself has an inherent curvature, the applied force is clearly not uniaxial, see figure below. Along the curvature of the virus prohead the applied force is resolved into various components. Also, the size of AFM tips (\< 20 nm) are on the order of the size of a prohead and thus cannot be considered as a point load when forces are applied to the prohead.

{{< resource "63a7fbfe-5663-cd17-bffe-4867dbbe45e5" >}}

_(d) These authors also claim that the mechanical testing of such proheads enables prediction of the elastic properties of the bacteriophage, by recourse to nonlinear elastic bucking of shells. Based on the data they present in this paper and known continuum mechanical analysis of shell elasticity, is this claim justified? Timoshenko \[[5](#References)\] is an excellent resource on mechanical analysis of shells._

The authors do nanoindentaion of the bacteriophage φ 29 shells and then model the shells using a continuum approach, assuming it is homogeneous and a thin shell. However, as we know the shell's microstructure is inhomogeneous and they even admitted there is a bimodal distribution of elastic moduli. Also, the authors considered the shells as spherical thin shells, assuming h/R = 0.1. In order to be regraded as flat plates (thin shells), the shells may have the thickness (h) which is less than one hundredth of the least radius (R) of curvature \[[3](#References)\]. This means that the nonlinearity of the shells can be reduced to the solvable linear shells \[[4](#References)\]. If the ratio of the thickness to the radius is comparable to the one tenth like this case, the shells may be considered as the moderately thick shells. In thick shells, the interaction due to bending term and stretching term cannot be evaded. Therefore, their claim would not be justified.

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Ivanovska, I. L., P. J. Pablo, B. Ibarra, G. Sgalari, F. C. MacKintosh, J. L. Carrascosa, C. F. Schmidt, and G. J. L. Wuite. "Bacteriophage Capsids: Tough Nanoshells with Complex Elastic Properties." _PNAS_ 101 (2004): 7600-7605.

\[2\] [Micro Cantilever](http://probe.olympus-global.com/en/spec/).

\[3\] Cox, H. L. _The Buckling of Cylindrical Plates and Shells_. New York, NY: Pergamon, 1963, pp. 71-72.

\[4\] Gould, Phillip L. _Analysis of Shells and Plates_. Upper Saddle River, NJ: Prentice Hall, 1998, pp. 461-463. ISBN: 9780133749502.

\[5\] Timoshenko, S., and S. Woinowsky-Krieger. _Theory of Plates and Shells_ . New York, NY: McGraw-Hill, 1959.

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Roleof water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}} | {{% resource_link 17fb7a5b-c938-5875-d1ff-a27e6dd55da8 "Problem Set 2" %}} | Problem Set 3 | {{% resource_link d5ac3e4c-e98f-a66d-535e-a241535e0491 "Problem Set 5" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}