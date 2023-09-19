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
  Set 2
uid: 4004d0a3-e09b-c1eb-db08-0be15d73640b
---

_(a) Draw the crystal structure of GaAs, and a separate graphic which is the closest-packed plane and direction on that plane. Discuss the major differences in this structure, as compared to Si._

{{< resource "1e4cdc8e-2c64-516a-a872-8d3b7baaba13" >}}

GaAs Zinc-Blende Structure \[[1](#ref)\]

Image removed due to copyright restrictions.

Please see: [http://www-vrl.umich.edu/project2/miller/111plane.JPG](http://www-vrl.umich.edu/project2/miller/111plane.JPG)

GaAs closest packed direction and plane \[[2](#ref)\]

{{< resource "512d991d-2d77-2179-3978-898a4009c723" >}}

Silicon Diamond Structure \[[1](#ref)\]

The GaAs structure is a zincblende structure whose basis consists of two different atoms, gallium and arsenic. Silicon has a similar structure except that it has a one atom basis, which is Silicon. This implies the GaAs structure does not have inversion symmetry whereas the silicon structure does. In addition, in GaAs, "the electron clouds \[tend\] to shift towards the Arsenide atoms, and results in a dipole moment along the \[111\] axis" \[[3](#ref)\]; the material exhibits piezoelectric characteristic similar to quartz. The zinc blende structure also offers alternating (111) Gallium and Arsenic planes resulting in very different properties depending on the surface-terminating plane. The asymmetry also results in such properties as hardness, anisotropy, and different dislocation velocities. \[[3](#ref)\]

_(b) From the data provided in Hjort's Table 1 \[_[_3_](#ref)_\], determine the Poisson's ratio of GaAs, as compared to Si and AlAs. Discuss comparison of these predictions with experimentally reported values of ν, from open literature and databases such as matweb.com._

  
 

Image removed due to copyright restrictions. Please see Table 1 in \[[3](#ref)\].

  
 

The Poisson's ratio (ν) calculated (by taking the ratio -S{{< sub "12" >}}/S{{< sub "11" >}} , values of which are given in table 1) for GaAs, Si, and AlAs are respectively 0.3162, 0.2727, and 0.325. Thus we find that the Poisson's ratio for AlAs > GaAs > Si. From literature, the Poisson's ratio for bulk GaAs is 0.31 \[[4](#ref)\], for Si it ranges between 0.22 for bulk isotropic, and 0.27 for \<111> crystalline Si \[[4](#ref)\], and 0.328 for AlAs \[[5](#ref)\]. The calculated values are in close agreement with the values got from literature.

_(c) Hjort's Fig. 2 \[[3](#ref)\] seems to indicate a different number of independent elastic constants than your crystal structure in (a) would suggest; explain. (It's a simple explanation.)_

  
 

Image removed due to copyright restrictions. Please see Fig. 2 in \[[3](#ref)\].

  
 

As expected, the matrix in Fig. 2 shows three independent elastic constants, C{{< sub "11" >}}, C{{< sub "12" >}} and C{{< sub "44" >}} . However, this matrix has 9x9 elements because it also accounts for the interactions between the mechanical and electromagnetic fields. It displays the relationship between orientation, piezoelectricity, d, and dielectricity, ε and the corresponding responses: S{{< sup "E" >}} as the mechanical response to a mechanical force, d{{< sup "T" >}} as the mechanical response to an electric field, d as the electrical response to a mechanical force and finally ε{{< sup "S" >}} as the electrical response to an electrical field.

_(d) Based on your analysis of GaAs elastic anisotropy, explain (graphically and/or text) which film orientation you would aim to achieve to create GaAs films or wafers that would be maximally resistant to bending._

  
 

Image removed due to copyright restrictions. Please see Fig. 3a in \[[3](#ref)\].

  
 

To resist bending, we want to choose the orientation with the highest Young's elastic modulus. This is the \<111>, as can be seen in Fig. 3a and in our calculations, attached. ({{% resource_link b4aa4055-0246-fd1a-1fa9-5a66a41a1c36 "PDF" %}})

However, it is important to understand the exact orientation of this the (111) planes with respect to film-substrate interface, which would minimize bending. To do so let us first look at a bi-material strip as shown in the figure below. The two materials can be characterized by different elastic moduli, and thus will exhibit different strains under the same state of stress. This leads to the bending of the strip to incorporate this difference, as understood more clearly by the figure.

{{< resource "2b4698e5-0216-9141-54d7-d242d31df172" >}}

Effect of the introduction of stresses on a bi-material strip.

For a GaAs film on a substrate (of a different material, and thus different elastic modulus, usually much greater), the lattice-mismatch, or a change of environment temperature, etc., generates stresses oriented parallel to the plane of the interface, leading to bending of the thin film, as described above. Also, the elastic modulus of the substrates used, is generally greater than that of the thin film (for example, sapphire, a commonly adopted substrate, has a Young's Modulus of 400 GPa \[[6](#ref)\]). Thus, in order to resist bending, it is desired to have the generated stresses experience maximum stiffness. Hence, the (111) planes (greatest modulus) should be oriented such that the normal to these **planes** are parallel to the generated stresses (in the plane of the interface).

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] [Wikimedia Commons](http://commons.wikimedia.org/wiki/Main_Page).

\[2\] [Miller Indices in VRML](http://www-vrl.umich.edu/project2/miller/index.html).

\[3\] Hjort, Klas, Jan Soderkvist, and Jan-Ake Schweitz. "Gallium Arsenide as a Mechanical Material." _Journal of Micromechanics and Microengineering_ 4 (1994): 1-13.

\[4\] [MEMSnet](http://www.memsnet.org/jobs/).

\[5\] Leavitt, R. P., and F. J. Towner. "Determination of the Lattice Parameter and Poisson Ratio for AlAs via High-resolution x-ray-Diffraction Studies of Epitaxial Films." _Physical Review B_ 48 (1993): 9154-9157.

\[6\] Moody, N. R., et al. "Substrate Composition Effects on the Interfacial Fracture of Tantalum Nitride Films." _Journal of Materials Research_ 14 (June 1999): 2306-2313.

  
  
 

{{% resource_link d2c4d382-2bf8-b124-ef19-84d129bb758e "Plasticity and fracture of microelectronic thin films/lines" %}}  
{{% resource_link 6bc9399e-31b7-554b-381b-94e738195a04 "Effects of multidimensional defects on III-V semiconductor mechanics" %}} | Problem Set 2 | {{% resource_link 8233726e-d8fe-061c-b415-6a97ebaf13a4 "Problem Set 3" %}} | {{% resource_link 3e7072d8-b2a1-1647-db86-2d7ac5cd83fa "Problem Set 5" %}}  
{{% resource_link 4240da7f-1fee-9884-d011-d970176515dd "Defect nucleation in crystalline metals" %}}  
{{% resource_link 25015f4f-2da1-f23e-6220-37f2a8145e3f "Role of water in accelerated fracture of fiber optic glass" %}}  
{{% resource_link 346f07bc-3b08-58de-3e3b-aa79c2ae2dff "Carbon nanotube mechanics" %}}  
{{% resource_link dcc910e4-d520-5d4c-d99d-97436ce9b436 "Superelastic and superplastic alloys" %}}  
{{% resource_link 2bee5861-4835-4007-19c7-b55fc641dd04 "Mechanical behavior of a virus" %}}  
{{% resource_link fec2f6e3-d5f7-3aff-9e49-9fe0cd9ac6f0 "Effects of radiation on mechanical behavior of crystalline materials" %}}