![](https://raw.githubusercontent.com/marcoalopez/IDEAproject/master/figures/header.jpg)

_Website by [Marco A. Lopez-Sanchez](https://marcoalopez.github.io/) - Last update: 2021/05/10_

**The IDEA project at a glance**

_The IDEA project stands for **I**n-situ **D**eformation **E**xperiments to study microstructure and texture evolution in **A**nisotropic crystalline materials. This is a research project attached to a [Marie Skłodowska-Curie “Clarín”-COFUND Action](http://www.clarinasturias.es/?lang=en) postdoctoral fellowship starting in 2018 and funded by different sources including European and French research projects. The main goal of the project is to rationalize the physical processes that occur at the microscale during crystal-plastic deformation and heating. Specifically, we are interested in how recrystallization (dynamic and static) affect the properties of polycrystalline materials such as strain hardening/weakening, the crystal preferred orientation (CPO) and strain localization. Our approach involves tracking the evolution of microstructure, CPO, and strain field during recrystallization using in situ observations. We use two main techniques: electron backscatter diffraction (EBSD) and digital image correlation (DIC). The core team is based at Géosciences Montpellier (Université de Montpellier - CNRS) in France and consist of [Andréa Tommasi](http://www.gm.univ-montp2.fr/PERSO/tommasi/deia-us.html) (supervisor), [Marco A. Lopez-Sanchez](https://marcoalopez.github.io/) (the recipient of the Clarín-COFUND fellowship), and Fabrice Barou (Geosciences Montpellier). We also collaborate with [David Mainprice](http://www.gm.univ-montp2.fr/PERSO/mainprice/) (GM Montpellier), [Maurine Montagnat](http://www.ige-grenoble.fr/pages-personnelles/maurine-montagnat-rentier/) (IGE - Grenoble) and Romain Quey (Mines Saint-Etienne)._

[TOC]

## 1. Why the IDEA project?

Understanding how plate tectonics works remains a cornerstone of modern geology. Deformation on the lithosphere, the "rigid" outer layer of the Earth, mainly occurs in a localized fashion. Excepting for the first ~10 km where deformation occurs primarily through brittle faults, most of the lithosphere (~95 % in volume) deforms essentially through crystal-plastic processes. This mode of deformation typically involves the development of planar zones of intense deformation known as shear zones and dislocation creep processes. Understanding how strain localises and preserves at different depths is key to explain how plate boundaries and major faults form and evolve, and ultimately how plate tectonics works. Yet, fundamental rock behaviour (strength) and the causes of strain localization remain poorly understood.

Rationalize the mechanical response to forces at great depths (i.e. within the plastic field) is a challenge for several reasons:

- Earth scientists do not have direct access (i.e. by drilling) to rocks deforming in the plastic field, usually involving rocks deeper than 10-15 km. Fortunately, orogenic processes bring these rocks to the earth's surface, many of which locally preserve the original microstructure and CPO.
- Rock deformation experiments at high _P_ and _T_ are challenging to conduct and always occur at strain rates many orders of magnitude faster (<<10^-7^ s^-1^) than in nature (10^-13^-10^-16^ s^-1^). The latter also implies that we need to use higher stresses or temperatures than those operating at specific depths in the lithosphere. As a result, flow laws estimated in the laboratory have to be scaled up by many orders of magnitude with no guarantee that the parameters obtained are correct. It is therefore necessary to understand the basic principles of plastic deformation to validate them.
- Rock behaviour during ductile deformation depends on many intrinsic (materials) and extrinsic (environmental) factors, including temperature, water fugacity, crystallographic preferred orientation, dislocation content, or grain size. In turn, these factors vary during the deformation and heating that shape the planet Earth and may show a strong degree of interdependence between them, making it difficult to separate their effects.

Here, we are particularly interested in the study of **recrystallization (RX) processes**, either during the application of differential stresses (dynamic RX) or under hydrostatic conditions (static RX), as both processes are very common in nature. Recrystallization processes affect three key parameters controlling rock strength: dislocation content, grain boundary area per unit volume (by locally decreasing or increasing the grain size), and CPO. The study of recrystallization is also a subject of intense research across different scientific disciplines due to its broad interest. For example, recrystallization processes are of great industrial importance in the processing of metallic alloys as they control the mechanical properties and behaviour of a material.



## 2. Equipment

### 2.1 _In situ_ deformation experiments using Electron Backscatter Diffraction

We conduct extension deformation experiments with in-situ monitoring using the [CamScan X500FE CrystalProbe EBSD-SEM](http://www.gm.univ-montp2.fr/spip.php?article648&lang=en) at Géosciences Montpellier, an electron microscopy with an Electron Backscatter Diffraction (EBSD) system specifically designed to host such experiments (Fig. 1). The vacuum chamber of this SEM-EBSD is designed to hold different types of devices. In our case, an in-house ceramic stage for the heating experiments and a [MT1000](https://newtec.fr/en/mt-1000/) tensile deformation stage provided by NewTec Scientific for the extension deformation experiments.



![](https://github.com/marcoalopez/IDEAproject/blob/master/figures/GM_insitu_facilities.jpg?raw=true)  _Figure 1. At left the CamScan X500FE CrystalProbe, an SEM-EBSD system specifically designed for the measurement of crystal orientation while conducting in situ experiments. Note that the column of the microscope is tilted 70 degrees to keep the samples horizontal. Upper right, this is the in house ceramic stage (made by Fabrice Barou) used in the annealing experiments. The image was taken during a heating-cooling test with a sample of magnesium alloy AZ31, note the thermocouples attached to different parts of the device. Lower right, the MT1000 deformation stage with a sample in place._



### 2.2 Digital image correlation (ice experiments)

During the IDEA project, we carried out several creep experiments on ice using random patterns on its surface to measure plastic deformation using image correlation methods (Fig. 2). These experiments were carried out at the [Institut des Géosciences de l’Environnement](https://www.ige-grenoble.fr/) in Grenoble in collaboration with Dr. Maurine Montagnat. Samples (see details in the Materials section below) were deformed in unconfined compression using an in-house dead-weight rig at -7 ºC (0.97 $T_m$, where  $T_m$is the melting temperature of $Ih$ ice) under constant uniaxial stress of 0.5 MPa up to 9 % (Fig. 2).



![Ice experiments](https://github.com/marcoalopez/IDEAproject/blob/master/figures/IceExp_Grenoble.jpg?raw=true)  _Figure 2. **Left**: set-up for the uniaxial compression creep ice test. Upper left, the full set-up with the creep rig in the background, and the camera equipment for the digital image correlation in the foreground. Lower left a close view of the ice sample within the creep rig. Note the random speckle on the surface of the sample to track displacements. **Center**: Thin sections using polarised light before (top) and after (bottom) the creep experiment (in this case a failed one). Note the recrystallisation at the grain boundaries and the heterogeneous plastic deformation. **Left**: That's me in the cold room making an ice sample with the milling machine._



**Hardware**: For the digital image acquisition, we used a Nikon D850 digital camera with a 45.7 Mp CMOS sensor (size of 35.9 x 23.9 mm  with pixel area of 18.84 μm^2^) and a high-performance low-distortion Tamron SP Macro 1:1 lens (focal length of 180 mm, maximum aperture of f/3.5). Digital images were taken with the following setting: manually focused with an aperture of f/11 (~16.4 mm for a 180 mm) and an ISO sensitivity of 64 generating time exposures of ~1/10 s at the cold room light conditions; the light source used was two neon lamps with light diffusers (Fig. 3). Images were saved as Nikon RAW (.NEF) files with a 12-bit depth.

**Image sequence**: We took 30 images before starting the deformation experiment and then every 10 minutes with the lens vibration reduction mode enabled during the creep experiment (see Figure 3 for general set-up).

**RAW image data treatment**: Images were converted from NEF (RAW) to TIFF using the dcraw v9.27 photo decoder and in-house Python codes using the ac hoc camera white balance and the Adaptive Homogeneity-Directed (AHD) interpolation for [demosaicing](https://en.wikipedia.org/wiki/Demosaicing) the images (which is the recommended interpolation mode for this camera model). After this, they were cropped (to the region of interest) and converted from RGB to 8-bit TIFF grayscale format using the Python Image Library (Pillow).

**Digital image correlation (DIC)**: We used the free and open-source [Digital Image Correlation Engine (DICe)](https://github.com/dicengine/dice) from [Sandia National Laboratories](https://www.sandia.gov/) to compute the full-field displacements and strains from sequences of digital images.

**DIC data-treatment**: All data obtained by the DICe tool was treated and plotted using in-house Python codes that will be released at the time of publication as free and open-source [Jupyter Notebooks](https://jupyter.org/).



## 3. Materials

We use three different materials: magnesium alloy AZ31, ice $Ih$, and olivine.

#### Magnesium

We use commercial-purity AZ31 magnesium alloy (~96% Mg, ~3% Al, ~1% Zn) for the _in situ_ EBSD experiments as we need a material that easily undergoes dynamic recrystallization under low-_P_ and moderate _T_ conditions operating in an SEM-EBSD chamber. Despite being an alloy, magnesium aggregates have been used as rock analogue [before](https://doi.org/10.1016/0031-9201(85)90131-1) since it shares several features with major rock-forming minerals due to its low crystal symmetry (hexagonal):

- highly anisotropic properties
- deform plastically by few slip systems (dominant basal slip system)
- prone to undergo dynamic recrystallization

Furthermore, magnesium alloys have attracted increasing attention in the last two decades due to their low mass density compared to other conventional metallic materials and good mechanical properties, making them candidates for the next generation of light-weight metallic materials. We have used two types of AZ31 alloy samples, small cubes of 10x10x8 mm for the annealing experiments (Fig. 3), and dog-bone specimens for the tensile tests.



![](https://github.com/marcoalopez/IDEAproject/blob/master/figures/AZ31_example.jpg?raw=true)  _Figure 3. AZ31 magnesium alloy samples used in the IDEA project. Upper left, AZ31 specimens of 10x10x8 mm before and after deformation in a channel-die compression device (i.e. plane strain) used for the annealing experiments. Upper right, dog-bone specimens used for the tensile tests. Lower, crystal preferred orientation (left) and microstructure (right) of the as-received magnesium alloy used for the annealing experiments. Note the intense basal texture with the c-axis maximum above eight multiples of a uniform distribution. The apparent mean grain size is ~9 μm (mode ~5 μm), and most grains had an internal misorientation spread lower than 1%._



#### Ice $I_h$

Similar to magnesium, [ice $I_h$](https://en.wikipedia.org/wiki/Ice_Ih) is a hexagonal crystal with strong anisotropic properties, easy basal slip (non-basal slip is about 60 times larger), and prone to undergo dynamic recrystallization. Knowledge of the rheological properties of ice $I_h$ is of great interest for the modelling of the flow of glaciers and polar ice sheets but also for the understanding of the mechanical behaviour of materials deformed at temperatures close to the material melting point (i.e. as a model material). In our experiments, we used rectangular samples of 10x10x1.5 cm side of polycrystalline columnar ice (i.e. formed of parallel columnar grains with c-axis close to the observation surface) with speckle random patterns on the sample surface (Fig. 2). 

Our main goal with the ice creep experiments is to understand how strain localise and/or delocalised at grain scale, how this phenomenon is affected by local grain interactions, and how the concentration of local deformation relates to the development of dynamic recrystallization. These issues have implications for the modelling of the deformed state of polycrystalline materials at the microstructural scale using continuum mechanics.



#### Olivine

Olivine is the main mineral phase in the lithospheric Earth’s mantle and thus a key mineral to understand lithosphere deformation. In the IDEA project, we perform no olivine deformation experiments but we used all the EBSD data-treatment procedures developed within the frame of the project to reanalyse and reinterpret old datasets coming from unpublished olivine extension deformation experiments. More specifically, we used a dataset that comes from olivine-rich cylinders cored from natural peridotites deformed in extension in a gas-medium apparatus at a confining pressure of 300 _MPa_ and *T* of 1200ºC. Our main goal is to understand how a common type of dynamic recrystallization, called [sub-grain rotation](https://en.wikipedia.org/wiki/Subgrain_rotation_recrystallization), develops in olivine and what effects it has on the CPO and the rheology of peridotites.

![](https://raw.githubusercontent.com/marcoalopez/IDEAproject/master/figures/Olivine.webp)  _Figure 4. TODO..._


## 4. Publications

Lopez-Sanchez MA, Tommasi A, Barou F, and Quey R (2020) Dislocation-driven recrystallization in AZ31B magnesium alloy imaged by quasi-in situ EBSD in annealing experiments. _Materials Characterization_ **165**:110382 https://doi.org/10.1016/j.matchar.2020.110382

>**Plain language summary**: When heating a polycrystalline material, known as annealing, new grains nucleate and grow in a process called _static recrystallization_. This changes the microstructure and texture of the aggregate modifying its properties (e.g. its mechanical -strength- and seismic properties). Since this is a process that greatly modifies the properties of the material it affects and is very common in the Earth's lithosphere and in industry, its study is of wide interest. Despite this, it is not clear which factors other than temperature control the growth process the most, the usual suspects being the disappearance of grain boundary surfaces with unfavourable (high-energy) configurations or the energy stored in the form of dislocations (a crystallographic defect within a crystal structure induced during deformation) in the aggregate. To study this, we deformed several magnesium alloy specimens under different conditions to generate different microstructures and textures. Then, we led a series of _in situ_ EBSD heating experiments at the same temperature to demonstrate that the local accumulation of dislocations is an important factor controlling the growth of new grains in highly deformed polycrystalline materials. We established new microstructural proxies based on EBSD data to demonstrate this effect. Grab the PDF [here](https://github.com/marcoalopez/marcoalopez.github.io/blob/master/docs/2020_MC_Lopez-Sanchez.pdf) if you're interested!

Lopez-Sanchez MA, Tommasi A, Ben Ismail W, Barou F. (2021) Dynamic recrystallization by subgrain rotation in olivine revealed by electron backscatter diffraction. _Tectonophysics, in press_. [Grab the preprint here](https://eartharxiv.org/repository/view/1973/)

> **Plain language summary**: Dynamic recrystallization involves the creation or migration of grain boundaries during plastic deformation to form new grains with low lattice distortion and smaller size than the host material modifying the rock properties. Here, we study a type of dynamic recrystallisation called subgrain rotation that is widespread in the lithosphere. Moreover, we do so in olivine, a mineral that makes up most of the lithosphere and the upper convective mantle. Understanding this is key for determining how lithospheric rocks respond to deformation from the microscale up to very large scales (hundreds of km). Using advanced electron backscatter diffraction methods on several samples deformed in the laboratory at high temperatures (1200ºC) and pressures (300 MPa), we described how and where the so-called “subgrain cells” (the precursor of the new recrystallized grains) form at micrometric scales. We also record a sharp change in the properties of these "subgrain boundaries" once they become grain boundaries. Based on our dataset, we discard an earlier hypothesis on the causes of this change and propose an alternative hypothesis to explain it.

Ben Ismail W, Tommasi A, Lopez-Sanchez MA, Barou F, Rutter EH, Demouchy S. Deformation of upper mantle rocks with contrasting initial fabrics in axial extension. _submitted to Tectonophysics_. [Grab the preprint here](http://arxiv.org/abs/2101.03362)

Lopez-Sanchez MA (2020) Which average, how many grains, and how to estimate robust confidence intervals in unimodal grain size populations. _Journal of Structural Geology_ **135**:104042 https://doi.org/10.1016/j.jsg.2020.104042   

> **Plain language summary:** The average grain size and the grain size populations are some of the most used features to study the microstructure of rocks and in particular recrystallization. This paper provides guidelines for determining average grain sizes and confidence intervals from grain size populations. Using computer simulations and resampling techniques, we found that the geometric mean and the confidence intervals for the geometric mean provide the best balance between efficiency and robustness (being the median the best alternative) in recrystallized grain size populations. [Grab the PDF here if you're interested!](https://github.com/marcoalopez/marcoalopez.github.io/blob/master/docs/2020_JSG_SG_104042.pdf).

**Yet to come**: _DIC deformation experiments on ice and magnesium alloys_

### 4.1 Codes released

[Jupyter4DICe](https://github.com/marcoalopez/Jupyter4DICe) :  A series of [Jupyter notebooks](https://jupyter.org/) written in Python for post-processing digital image correlation (DIC) data obtained with the free open-source digital image correlation tool [DICe](https://github.com/dicengine/dice). (not yet finished!)



### 4.2 Datasets & multimedia content

#### Datasets

EBSD datasets used in _Lopez-Sanchez et al. (2020) Materials Characterization 165:110382_
https://data.mendeley.com/datasets/ttvh2m9r9s/draft?a=f35092a2-3a42-4b19-a14a-8c25879e6316

#### Multimedia

Videos of the experiments available soon

#### Links to talks

[In-situ annealing EBSD experiments in magnesium alloy AZ31B with variable deformation microstructures](https://www.youtube.com/watch?v=NgSFIaK2GgI) at Ecole de Physique des Houches (_GRD Recrystallization and Grain Growth meeting 2020_)

[Dynamic recrystallization by sub-grain rotation in olivine-rich rocks](https://www.youtube.com/watch?v=fijSePJ3dsA&list) at Ecole de Physique des Houches (_GRD Recrystallization and Grain Growth meeting 2020_)

## 5. Outreach and workshops

Workshop “**EBSD data treatment with MTEX**” at _GRD Recrystallization and Grain Growth workshop 2020_ at [Les Houches, School of Physics, France](https://www.houches-school-physics.com/program/program-2020/workshop-on-recrystallization-and-grain-growth-592227.kjsp?RH=1570781112691)



![footer](https://github.com/marcoalopez/IDEAproject/blob/master/figures/footer.jpg?raw=true)

---

Copyright © 2018-2021 Marco A. Lopez-Sanchez  

_Information presented on this website is provided without any express or implied warranty and may include technical inaccuracies or typing errors; the author reserve the right to modify or enhance the content of this website at any time without previous notice. This webpage is not liable for the content of external links._  

_Hosted on GitHub Pages — Website created with [Typora](https://typora.io/)_  