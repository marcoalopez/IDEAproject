![](https://raw.githubusercontent.com/marcoalopez/IDEAproject/master/figures/header.webp)

Website by [Marco A. Lopez-Sanchez](https://marcoalopez.github.io/) - Last update: 2020/08/29

## The IDEA project at a glance

_The IDEA project stands for **I**n-situ **D**eformation **E**xperiments to study microstructure and texture evolution in **A**nisotropic crystalline materials. This is a research project attached to a [Marie Skłodowska-Curie “Clarín”-COFUND Action](http://www.clarinasturias.es/?lang=en) postdoctoral fellowship starting in 2018 and funded by different sources including European and French research projects. The main goal of the project is to rationalize the physical processes that occur at the microscale during recrystallization caused by crystal-plastic deformation and heating. Specifically, we are interested in how recrystallization (dynamic and static) affect the properties of polycrystalline materials and behaviour such as strain hardening/weakening or strain localization. Our approach involves tracking the evolution of microstructure, CPO, and strain field during recrystallization using in situ observations. We use two main techniques: electron backscatter diffraction (EBSD) and digital image correlation (DIC). The core team is based at Géosciences Montpellier (Université de Montpellier - CNRS) in France and is formed by [Andréa Tommasi](http://www.gm.univ-montp2.fr/PERSO/tommasi/deia-us.html) (supervisor), [Marco A. Lopez-Sanchez](https://marcoalopez.github.io/) (the recipient of the Clarín-COFUND fellowship), and Fabrice Barou (Geosciences Montpellier). We also collaborate with [Maurine Montagnat](http://www.ige-grenoble.fr/pages-personnelles/maurine-montagnat-rentier/) (IGE - Grenoble) and Romain Quey (Mines Saint-Etienne)._

[TOC]

## 1. Why the IDEA project?

Understanding how plate tectonics works remains a cornerstone of modern geology. Deformation on the lithosphere, the "rigid" outer layer of the Earth, mainly occurs in a localized fashion. Excepting for the first ~10 km where brittle deformation dominates mainly through faults, most of the lithosphere (~95 % in volume) deforms essentially through crystal plastic processes. This mode of deformation typically involves dislocation creep and the development of planar zones of intense deformation known as shear zones. Understanding how strain localises and preserves at different depths is key to explain how plate boundaries and major faults form and evolve, and ultimately how plate tectonics works. Yet, fundamental rock behaviour (strength) and the causes of strain localization remain poorly understood.

Rationalize the mechanical response to forces of deep rocks (i.e. in the plastic field) is a challenge for different reasons:

- Earth scientists do not have direct access (i.e. by drilling) to rocks deforming in the plastic field, normally involving rocks deeper than 10-15 km.
- Rock deformation experiments at high _P_ and _T_ are difficult to perform and always occurs at strain rates several orders of magnitude faster (<<10^-7^ *vs.* 10^-13^-10^-16^ s^-1^) and thus at higher stress levels than those operating in the deep Earth. This means that the laboratory-based flow laws have to be scaled with no guarantee that they are the same in nature. It is therefore necessary to know the basic principles of deformation in order to validate them.
- Rock behaviour during ductile deformation depends on several intrinsic (material) and extrinsic (environmental) factors, including temperature, water fugacity, crystallographic preferred orientation (CPO), dislocation content, or grain size. These variables commonly vary during the processes of deformation and heating that occur on Earth and show a degree of interdependence between them, which makes it difficult to separate their effects.

In the IDEA project, we are particularly interested in the study of **recrystallization (RX) processes**, either during the application of differential stresses (dynamic RX) or at hydrostatic conditions (static RX), as both processes are common in plastic shear zones. Recrystallization processes affect three key parameters controlling rock strength: dislocation content, grain boundary area per unit volume (by locally decreasing or increasing the grain size), and CPO. The study of recrystallization is also a subject of intense research across different scientific disciplines due to its broad interest. For example, recrystallization processes are of great industrial importance in the processing of metallic alloys as they control the mechanical properties and behaviour of a material.



## 2. Methods & Materials



### 2.1 Equipment

The _in situ_ experiments are carried out using the [CamScan X500FE CrystalProbe EBSD-SEM](http://www.gm.univ-montp2.fr/spip.php?article648&lang=en) at Géosciences Montpellier. This is an SEM-EBSD system specifically designed to host _in situ_ experiments. Besides, we use an in-house ceramic stage with three thermocouples attached for the annealing experiments and a tensile deformation stage [MT1000](https://newtec.fr/en/mt-1000/) provided by NewTec Scientific for the deformation experiments.

![SEM-EBSD](https://github.com/marcoalopez/IDEAproject/blob/master/figures/EBSD.jpg?raw=true)

![](https://github.com/marcoalopez/IDEAproject/blob/master/figures/AZ31_heating_stage.jpg?raw=true)
_Figure Caption. TODO_

![](https://github.com/marcoalopez/IDEAproject/blob/master/figures/def_stage.jpg?raw=true)
_Figure Caption. TODO_

### 2.2 Materials

We use three different materials: magnesium alloy AZ31, ice and olivine.

#### Magnesium

We use magnesium alloy AZ31 aggregates for the _in situ_ EBSD experiments as we need a material that easily undergoes crystal-plastic deformation and fast grain boundary mobility (during annealing) under low-_P_ and moderate _T_ conditions in an SEM-EBSD. Despite being an alloy, magnesium aggregates have been used as rock analogue [before]() since it shares several features with major rock-forming minerals due to its low crystal symmetry (hexagonal):

- highly anisotropic properties
- deform plastically by few slip systems (dominant basal slip system)
- prone to undergo dynamic recrystallization

Furthermore, magnesium alloys have attracted increasing attention in the last two decades due to their low mass density compared to other conventional metallic materials and good mechanical properties, making them candidates for the next generation of light-weight metallic materials.



#### Ice (Ih)

Similar to magnesium, (Ih) ice is an hexagonal crystal with strong anisotropic properties, easy basal slip, and prone to undergo dynamic recrystallization. Knowledge of the rheological properties of Ih ice is of great interest for the modelling of the flow of glaciers and polar ice sheets as well as for the understanding of the mechanical behaviour of materials deformed at temperatures close to the material melting point (i.e. as a model material). In our experiments, we used rectangular samples of 10 mm side of polycrystalline columnar ice (i.e. formed of parallel columnar grains with c-axis close to the observation surface) and we generate a random pattern on the sample surface to measure plastic strain during deformation using digital image correlation techniques. Sample were deformed in compression using an in house dead-weight rig  at -7 ºC, room pressure, and under constant uniaxial stress of 0.5 MPa.

![Ice experiments](https://github.com/marcoalopez/IDEAproject/blob/master/figures/IceExp_Grenoble.jpg?raw=true)
_Figure caption. TODO_

Our main goal with the ice experiments is to understand how strain localise (and delocalise) at grain scale  and how this phenomena is affected by local grain interactions. This issues have implications for the modelling of the deformed state of polycrystalline materials at the microstructural scale using continuum mechanics

#### Olivine

Olivine is the main mineral phase in the Earth’s mantle (~30-410 km) and thus a key mineral to understand lithosphere (the “rigid” outer layer of the Earth) deformation. In the IDEA project, we perform no olivine deformation experiments but we used all the EBSD data-treatment procedures developed within the frame of the project to reanalyse and reinterpret old datasets coming from unpublished olivine deformation experiments. More specifically, we used a dataset that comes from peridotite cylinders deformed in extension in a gas-medium apparatus at a confining pressures of 300 _MPa_ and *T* of 1200ºC directly cored from naturally deformed and undeformed peridotites. Our main goal is to understand how a common type of dynamic recrystallization, called _sub-grain rotation_, develops in olivine and what effects it has on the CPO and the rheology of the peridotites.

![]()



## 3. Publications

- Lopez-Sanchez MA, Tommasi A, Barou F, and Quey R (2020) Dislocation-driven recrystallization in AZ31B magnesium alloy imaged by quasi-in situ EBSD in annealing experiments. _Materials Characterization_ **165**:110382 https://doi.org/10.1016/j.matchar.2020.110382 // [get the PDF !](https://github.com/marcoalopez/marcoalopez.github.io/blob/master/docs/2020_MC_Lopez-Sanchez.pdf)

- Lopez-Sanchez MA (2020) Which average, how many grains, and how to estimate robust confidence intervals in unimodal grain size populations. _Journal of Structural Geology_ **135**:104042 https://doi.org/10.1016/j.jsg.2020.104042 / [get the PDF !](https://github.com/marcoalopez/marcoalopez.github.io/blob/master/docs/2020_JSG_SG_104042.pdf)  



### 3.1 Codes released

Available soon (with links to repositories)

### 3.2 Datasets & multimedia content

#### Data

EBSD datasets used in _Lopez-Sanchez et al. (2020) Materials Characterization 165:110382_
https://data.mendeley.com/datasets/ttvh2m9r9s/draft?a=f35092a2-3a42-4b19-a14a-8c25879e6316

#### Multimedia

Available soon

#### Links to talks

[In-situ annealing EBSD experiments in magnesium alloy AZ31B with variable deformation microstructures](https://www.youtube.com/watch?v=NgSFIaK2GgI) at Ecole de Physique des Houches (_GRD Recrystallization and Grain Growth meeting 2020_)

[Dynamic recrystallization by sub-grain rotation in olivine-rich rocks](https://www.youtube.com/watch?v=fijSePJ3dsA&list) at Ecole de Physique des Houches (_GRD Recrystallization and Grain Growth meeting 2020_)

## 4. Outreach and workshops

Workshop “**EBSD data treatment with MTEX**” at _GRD Recrystallization and Grain Growth workshop 2020_ at [Les Houches, School of Physics, France](https://www.houches-school-physics.com/program/program-2020/workshop-on-recrystallization-and-grain-growth-592227.kjsp?RH=1570781112691)



![footer](https://github.com/marcoalopez/IDEAproject/blob/master/figures/footer.jpg?raw=true)

---

Copyright © 2018-2020 Marco A. Lopez-Sanchez  

_Information presented on this website is provided without any express or implied warranty and may include technical inaccuracies or typing errors; the author reserve the right to modify or enhance the content of this website at any time without previous notice. This webpage is not liable for the content of external links._  

_Hosted on GitHub Pages — Website created with [Typora](https://typora.io/)_  