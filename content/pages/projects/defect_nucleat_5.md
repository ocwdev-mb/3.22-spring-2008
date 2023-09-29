---
content_type: page
description: ''
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Defect Nucleation in Crystalline Metals - Problem Set 5
uid: 70049e7d-dc51-6444-051a-d2a4d929ff2d
---

_(b) The papers you have chosen focus on the initial stages of plastic deformation, or incipient plasticity, in ductile metals. Consider Fig. 9 in paper 3 \[[1](#ref)\], illustrating a dislocation loop passing through a single crystal of Al under indentation pressure. Consider a bulk metal vs. a thin film of the same material on a rigid substrate, explain how you would expect the load required to keep plastically deforming the material t a depth of 1 micron would differ._

The load required to plastically deform the thin film of Aluminum and the bulk metal at a depth of 1 micron below the free surface would differ considerably. The stress required in the case of the aluminum film would be much greater as compared to the bulk metal. This is because plastic deformation is facilitated by dislocation movement and it would be obstructed more in the thin film than in the bulk metal. This is attributed to the fact that when a stress is applied the dislocation loop would tend to move but would not be able to move easily as it would be repelled by the hard substrate as it has a higher modulus than aluminum so a higher stress is needed to move the dislocation loop close to the substrate.

The energy of a dislocation goes as (Gb{{< sup "2" >}})/2 so it would be more in the hard substrate and so also would be repelled by the hard substrate as the dislocation energy increases. We can also draw analogy to the fact that the dislocation would tend to be attracted to a free surface whose G = 0 because the dislocation energy becomes 0. Going on the same lines it would be repelled by a substrate whose G is greater than the G of the metal.

In the case of the bulk metal a dislocation finds itself in the vicinity of the bulk metal only at a depth of 1 micron so it would move with no additional resistance.

_(c) Compute the fracture stress of this Al according to the Griffith criterion, assuming an initial crack size at the resolution of the TEM used in Minor's indentation experiments \[[2](#ref)\]. Compare this to the published fracture strength of single crystal Al, and discuss._

Here we assume an initial crack the size of the resolution of the microscope used by Minor in this study \[[2](#ref)\]. From the NCEM website \[[3](#ref)\], we find the minimum point-to-point resolution of the JEOL 3010 to be 1.7 _Å_, which we set equal to a crack of width 2_a_. The surface energy of aluminum was found to be 0.057 eV _Å_{{< sup "2" >}} \[[4](#ref)\]. The Young's Modulus for aluminum is 68 GPa \[[5](#ref)\]. We now have all the necessary parameters to calculate the required fracture stress for a crack of this size.

{{< resource "b5730f86-e2fa-eee1-49b9-1ef1422eacc7" >}}

This is a very high fracture stress, being near the theoretical fracture stress given for aluminum in class (20 GPa). A molecular dynamics simulation of a single crystal of aluminum gives a yield stress of 2 GPa, corresponding to the initiation of a plastic event in the material \[[6](#ref)\]. No direct experimental data of fracture stress could be found, but it should be even lower than this due to the presence of preexisting defects such as cracks and pores. Prof. Van Vliet gave the fracture stress of aluminum to be 0.7 GPa in class.

The high fracture stress for a crack at the TEM resolution limit points tells us that this is not a very reasonable explanation for failure in this system. Either the theoretical shear stress will be reached and a dislocation will be initiated or preexisting macroscopic defects will propagate cracks within the material before a crack on the Angstrom level would propagate.

_(d) Delamination of films can also be treated as fracture, but this time at an interface between two dissimilar materials. Using Griffith again, compute the tensile stress required to delaminate an Al film from a Si substrate, if there is an initial blister at the film/substrate interface of width 1 micron. Then state whether you'd expect the film to first fracture due to opening of initial cracks within the film (of initial size stated in c), or to delaminate from the substrate when loaded in tension normal to the film/substrate interface._

Griffith's criterion: {{< resource "89e91c9d-0709-7f40-bd21-1f6a6fb2654c" >}}

Griffith's criterion considers crack propagation in single material. To apply Griffith's equation to thin film/substrate system, we need to consider both Al film and Si substrate.

1.  Surface energy: In the thin film case, the change of surface energy (Γ) because of the crack is the sum of increased surface energy of Al (γ{{< sub "Al" >}}) and Si (γ{{< sub "Si" >}}) and the decrease of interface energy (γ{{< sub "Al/Si" >}}) between thin film and substrate.
    
    {{< tableopen >}}
    {{< tropen >}}
    {{< tdopen >}}
    
    
    {{< resource "73880710-d1ab-fbc4-0eeb-1fe611f03105" >}}
    
    
    {{< tdclose >}}
    {{< tdopen >}}
    \= 8 N/m (from \[[5](#ref)\])
    {{< tdclose >}}
    
    {{< trclose >}}
    
    {{< tableclose >}}
    
    This value corresponds to 2γ in the Griffith's equation.
    
2.  Young's modulus: In a delamination problem, Young's modulus (_E_) should also be modified by using effective Young's modulus (_E{{< sub "eff" >}}_) since the release of elastic energy comes from both the thin film and substrate.
    
3.  The effective energy release rate is given in \[[7](#ref)\], {{< resource "2e528a90-2a38-f095-577a-d4498284e27a" >}}
    
    where D{{< sub "1" >}} is given as {{< resource "16714f33-2eef-92b1-18f5-47643ce91753" >}} and {{< resource "6ec00ba2-dac9-39b8-f632-ff33bad20081" >}} is the plane strain modulus for the film and substrate.
    
    {{< resource "5ae07792-6fa8-2464-0692-13b42acd2e35" >}} = 80 GPa. (_E{{< sub "f" >}}_ is 70 GPa and _ν{{< sub "f" >}}_ is 0.35)  
    {{< resource "ead25d63-9799-7b65-eb2b-763c3dc77bca" >}} = 141 GPa. (E\_s is 130 GPa and _ν_{{< sub "s" >}} is 0.28)  
    D{{< sub "1" >}} value for our Al/Si system is therefore -0.28.  
      
    {{< resource "755a08be-b374-9790-abc8-b9cb1829394f" >}}
    
4.  Combining 1) and 2), we can get the tensile stress required to delaminate an Al film on Si substrate with 1 µm blister,
    
    {{< resource "008c2722-8300-41cb-25d9-715976586cd9" >}}
    
5.  From problem (c), we know that the fracture stress for 0.17 nm crack is 21.5 GPa. Since the fracture stress for fracture is much higher than that for delamination, we would expect the film to delaminate first.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Van Vliet, Krystyn J., et al. "Quantifying the Early Stage of Plasticity Through Nanoscale Experiments and Simulations." _Physical Review_ B 67 (2003): 104105.

\[2\] Minor, Andrew M., et al. "A New View of the Onset of Plasticity During the Nanoindentation of Aluminum." _Nature Materials_ 5 (2006): 697-702.

\[3\] [National Center for Electron Microscopy](http://foundry.lbl.gov/facilities/ncem/).

\[4\] Needs, Richard J. "Calculations of the Surface Stress Tensor at Aluminum (111) and (110) Surfaces." _Physical Review Letters_ 58 (1987): 53-56.

\[5\] [MatWeb](http://www.matweb.com/).

\[6\] Yuan, Lin, et al. "Molecular Dynamics Simulation of Tensile Deformation of Nano-single Crystal Aluminum." _Journal of Materials Processing Technology_ 184 (2007): 1-5.

\[7\] Freund, L. B., and S. Suresh. "Delamination and Fracture." Chapter 4 in _Thin Film Materials_. New York, NY: Cambridge University Press, 2004. ISBN: 9780521822817.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}} | {{% resource_link 6ab0d9bf-3df7-cba9-3348-74c6c3b67d39 "Problem Set 2" %}} | {{% resource_link d45cc5b0-b455-db9c-d6d7-0a678a060851 "Problem Set 3" %}} | Problem Set 5  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}