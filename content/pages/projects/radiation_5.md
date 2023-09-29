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
  Set 5
uid: 1ffd3c1d-bf94-ae3e-1e22-3ec1fc1c3ba9
---

_(b) Aldo's Fig. 3 \[[1](#Reference)\] shows relation between effective creep stress and creep strain. Which of the materials/conditions considered exhibit a linear viscoelastic type creep response under this temperature and radiation dosage?_

  
 

{{< resource "101ab719-f4ed-fe49-e7ff-dd8da057cf89" >}}

Courtesy of Elsevier, Inc., [Science Direct](http://www.sciencedirect.com/). Used with permission.

  
 

Without seeing the unloading data, we have no way of knowing whether these materials are elastic-plastic or linear-visco-elastic. However, assuming that deviation from linear elasticity in the above figure is indeed viscoelastic behaviour then it is clear from the plot that mainly the JLF-1 and JLF-1 MN(b) materials exhibit LVE behavior, as these are the only materials that deformed quickly under a certain stress and therefore would have any hysteresis under their stress/strain curves. The F82H IEA sample might also exhibit some LVE behavior to a small extent, but it's difficult to tell.

_(c) The authors \[[1](#Reference)\] give a creep model in Eq. 3. Restate this in terms of a steady state creep rate, and determine the creep mechanism in terms of those we have discussed in class. Which of the models we discussed best captures the trend observed by the authors? Assuming the appropriate energy barrier and diffusivity for your mechanism of choice, would you predict final creep strains comparable to the ones they measure at these stresses (where creep strain = strain rate\*time)?_

Restating the authors' creep model in Eq. 3 as a steady state creep rate requires one to take a time derivative of both sides, so de/dt = 1.15(√(2)/3)\*(dD/dt)/D{{< sub "o" >}}

Since the change in diameter would be due to a radial stress, it should be linearly proportional to that hoop stress. This leads to a strain rate linearly proportional to the imposed hoop stress, and therefore it is a diffusional creep mechanism. Finally, these steels are quenched & tempered Ferritic/Martensitic steels, so the grain size is likely to be very small, and Coble Creep is therefore the dominant creep mechanism.

_(d) The authors \[[1](#Reference)\] state the following: "The HFIR irradiated specimens may have a larger Burgers vector anisotropy because they were exposed at higher stress levels and lower irradiation temperatures than the FFTF irradiated specimens. Detailed investigation of these microstructures following irradiation will be performed in future studies."_

_What do they mean by "Burgers vector anisotropy"? And did they yet report any follow up work that correlate the microstructure of these steels with the observed creep phenomena?_

By "Burgers Vector Anisotropy" the authors mean a larger variance in observed Burgers vector. At a lower irradiation temperature, less of the created defects would be able to diffuse away because there is less thermal energy available to overcome the activation energy barrier. This results in more imperfections in the lattice structure and therefore more variations in the Burgers vector, assuming it's defined in the usual way of traveling a fixed distance along a path in 4 directions about a dislocation. The more vacancies and oddball atoms about near the dislocation, the more likely this path will result in a distance other than the average Burgers vector.

As yet, we have found no further reports by these authors correlating the microstructure of these steels with the observed creep phenomena.

{{< anchor "Reference" >}}{{< /anchor >}}Reference
--------------------------------------------------

\[1\] Ando, M., et al. "Creep Behavior of Reduced Activation Ferritic/Martensitic Steels Irradiated at 573 and 773 K at up to 5 dpa." _Journal of Nuclear Materials_ 367-370 (2007): 122-126.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}} | {{% resource_link 0919f251-73fa-3bb8-24b6-200f1e8add7a "Problem Set 2" %}} | {{% resource_link 065bdafc-ff95-dcc5-4d56-8854da744fe3 "Problem Set 3" %}} | Problem Set 5