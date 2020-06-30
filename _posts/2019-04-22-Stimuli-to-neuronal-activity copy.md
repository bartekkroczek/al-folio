---
title: "Transduction of physical stimuli into neural activity."
categories:
  - psychophysics
tags:
  - psychophysics
---
Examples, cells and receptors, common themes.


# Introduction
## What is transduction?
Transduction is a process of conversion of physical or chemical stimuli into an electrical impulse.


<div class="l-body">
  <img class="img-fluid rounded z-depth-0"  src="{{site.baseurl}}/assets/img/2019-04-22/1.jpg" />
</div>


This process can be treated as a "magic box" converting **input** (physical or chemical phenomena) into **output** (neuronal electric activity) through **a series of molecular events**. We can think of such a system as an **[AD][ad] converter**.
So, before we dive into biochemical machinery, let's discuss what can come in and out of such a system.   

## Inputs 

### Electromagnetic wave 
The current scientific theory holds that [all particles exhibit a wave nature][quantum] and vice versa.
This Wave-particle duality means, that in some sense photon, and an electromagnetic wave is just a different representation of this same unity. This fact determines how photons can differ from each other because the electromagnetic wave can be described by its [amplitude, frequency, and phase][electro].

But how these quantities are related to visible light?
>[Light is an electromagnetic wave that can be seen by the typical human.][lightbook]

**"Can be seen"** refers to the frequency of a wave. A typical human eye will respond to wavelengths from about [400 to 700 nanometers][krotkie]. This corresponds to 405–790 THz. The exact frequency of a lightwave is [related to its color][lightbook]. 

Some colors (red, orange, yellow, green, blue, and violet) are described by only one frequency. They are called "monochromatic". 
Other, "polychromatic" colors are described by a bunch of frequencies. 

The amplitude of a light wave is [related to its **intensity**][lightbook] which is a wave's power density. This is an absolute value. Subjective light wave intensitive perceived by the average human eye is called **brightness**.


### Chemical Particles

Both Smell and taste are based (mostly) on sensations caused by chemicals. Fragrance particles are usually small (>200[Da][da]), volatile, and fat-soluble.  Humans distinguish only five flavors: sweet, salty, sour, bitter, and umami. However, the taste impression is also the structure and texture of the food, which draws mechano- and prioprio-receptors to work.

### Sound pressure

 Sound waves are **longitudinal** which means that particles in a medium (eg. air) are rhythmically compressed and decompressed. It's in contrast to **transverse** waves, where medium goes up and down (like waves on the water). Sound (unlike light) requires a medium, which affects the parameters of the wave itself. 

Wave frequency is described as **Note** (for example 261.625Hz is called "Middle C") and is perceived by humans in a range of [20-20'000Hz][ear]. Speech is in a range of [250-4000Hz][krotkie] which corresponds to the highest frequency resolution area for a human ear. 
 
 Amplitude(pressure) is rescaled and logarithmically transformed into [decibels][decib]. The threshold of hearing is set as **0dB**. Values above **130dB** [cause pain][ear].   

### Mechanical and thermal forces
[Touch][touch] is simply a mechanical pressure. Also, the concept of temperature is uncomplicated as well - it's an average of kinetic energy amount owned by particles coming into contact with the skin.


## Output (Neural coding) 
The signals processed in the central nervous system are digital. The problem is how to encode the signal without losing relevant information.

### Static and dynamic coding

Sensory fibers can be  **slow** and **fast** adapting.
Slow adaptive receptors are responsible for the perception of a stimulus that lasts a long time, acting evenly until its completion. The time window in which the neuron is excited corresponds to the duration of the stimulus, and the frequency carries information about its intensity. In turn, fast adapting receptors carry information about the change in the intensity (or the fact of appearance) of the stimulus.

#### How does it work?

In this example from [here][krotkie], three types of slow and fast adapting mechanoreceptors are exposed to the same stimulus.
* [Ruffini's bodies][rufini] - a slowly adaptive receptor, respond with a frequency proportional to stimuli intensity.
* [The Meissner corpuscles][tactile] adapt quickly and react only when the stimulus changes, at the same time coding the speed of skin deformation.
* [Pacini's corpuscles][pacini] are synthesized the fastest, resulting in the very fact that the stimulus is accelerated.


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/2.jpg" />
</div>


### Intensity coding

>[The intensity of stimuli is related to an average frequency of action potential firing][krotkie].

This relation is usually linear, but not always. For example, hearing hair mechanoreceptors have logarithmic characteristics that allow the reception of stimuli on a very wide scale. 


### Population coding

**Frequency modulation** is sometimes insufficient. Some information must be coded by the joint activities of many nerve cells. This is called [population coding][pop].

# Anatomy and biochemistry of senses 
It's time to open the magic box.

## Somatosensory system 
Touch is detected by **mechanoreceptors** - modified axonal terminations - depolarized by a stimulus. 
In Mechanoreceptors -under the influence of a stimulus- a change in the potential of the cell membrane occurs by increasing its permeability to one or several types of ions.


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/3.jpg" />

</div>

 *Picture from [here][skin]*

### Mechanoreceptors

Mechanoreceptors are divided in two ways. The first division concerns the adaptation speed, so we have receptors that adapt quickly and slowly. The second division (into type I and II) concerns the location and reception area. Type I are surface receptors with a small perceptive field, they are mainly used for shape detection and examples of them are **Meissner's**, and **Merkel's** corpuscles. Type II receptors with large perceptive fields are found in deep skin layers. They react to skin stretching, and examples of them are **Ruffini** and **Pacini** corpuscles.

### Thermoreceptors

Thermoreceptors are slow adaptive receptors, which makes them good detectors for rapid temperature changes, but bad thermometers. The spiking frequency of heat receptors increases with temperature. Similarly, cold receptors raise the operating frequency as the temperature decreases. 

### Nociceptors

There are two groups of **nociceptors**, i.e. pain receptors. First - a bare nerve ending, responsible for experiencing acute, prickly, well-localized pain typical for mechanical trauma. Second, **polymodal nociceptors** react to skin prickling, temperatures above 46°C, and chemicals released during tissue damage.

## Olfactory system

Olfactory signal transduction occurs in the [olfactory epithelium][olf] located in the upper part of the nasal cavity. Receptor cell dendrites called **olfactory cilia** form subgroups contain from six to twelve units, protruding from the surface of the **epithelial layer**. Only in mammals, about 1'000 types of fragrance receptors have been identified. Each odor substance can interact with two to six different types of receptors, resulting in nearly 10’000 distinct smells.


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/4.jpg" />

</div>

  Picture from [here][nasal].


### Smell Transduction

1. The fragrance molecule becomes bound to the receptor.
2. Increase in cAMP concentration.
3. Opening of non-specific cyclic nucleotide-gated cationic channels.
4. Intense ion (Na, K, Ca) flow.
5. Depolarization of olfactory cilia on the dendrite of the olfactory receptor neuron.
6. Release of an action potential on the axon hillock.
7. A digitalized signal is transmitted through the olfactory nerve. 


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/5.jpg" />
</div>

## Gustatory system

The taste is processed on the tongue. More specifically, attention should be paid to **lingual papillae** in which there are **taste buds**. At their tops, there are **flavor openings** that direct the particles to **microvilli**, where taste transduction occurs.


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/6.jpg" />

</div>

Picture from [here][tongue].

There are two categories of receptors. **Metabotropic** receptors are responsible for the impression of bitter, sweet, and umami.
In contrast, **ionotropic** receptors correspond to the sour and salty taste.


### Transduction

**Ionotropic** receptors can directly depolarize the cell. Sour taste (Single proton) is detected by blocking of potassium channels which prevents potassium ions from flowing to the outside. In turn, sodium ions found in salty foods are directly caught by epithelial sodium channels.

In **metabotropic** receptors depolarisation is indirect, it occurs through signaling cascade. Taste molecules are bound to matching receptors which triggers G-proteins to stimulate the release of phospholipase-C. This enzyme breaks [PIP2][pip2] particle bonds into secondary messenger IP3 and DAG. IP3 binds to calcium channels in **the endoplasmatic reticulum** which releases calcium into the cytosol. This fact triggers a couple of different mechanisms leading to cell depolarization. 


<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/7.jpg" />
</div>

When the cell begins to depolarize, it releases glutamate, which stimulates the afferent nerve. 

##  Visual system

The eye consists of three layers. 
1. **The Sclera**, which holds the shape of the eye
2. A **choroid** that prevents light from reflecting inside the eyeball
3. The inner layer is **the retina**, which is a component that receives visual stimuli.

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/8.jpg" />

</div>

*Picture from [here][eye]*

### Retina 

The retina is light-sensitive, the innermost layer of the eye. It consists of five types of neurons arranged in sub-layers.

The light must go through the entire thickness of (transparent) retina to reach **photoreceptors**, which are capable of **visual phototransduction**.

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/9.jpg" />

</div>

*Picture from [here][reti]*

There are two types of photoreceptors - rods and cones. Rod cells are approximately 20 times more numerous than the cones. The rods are also much more sensitive (about 1000 times) and are used in low-light condition, in a phenomenon called **scotopic vision**.

Cones are divided into three types differing in wavelength to which they are most sensitive. Usually (but imprecisely) we call them according to the colors that correspond to their highest sensitivity, i.e. blue, green, and red.  Color vision requires a comparison of the relative strength of outputs from all types of cones.

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/10.jpg" />

</div>

*Picture from [here][rodscons]*


The key element in the construction of the photoreceptor is a disk containing photopigment called **rhodopsin**.

**Rhodopsin** is a photosensitive dye consisting of the protein - opsin, which covalently binds to the cofactor 11-cis-retinal (retinene). Each type of photoreceptor contains its opsin type. The degradation of rhodopsin underlies the phototransduction process. 

### Phototransduction

1. The photon causes photoisomerization of the retinal from "cis" to "trans" form
2. A series of conformational changes in rhodopsin
3. Rhodopsin binds to the G-protein, transducin 
4. The above process is accompanied by the exchange of 5'-guanosine diphosphate for 5'-guazinodiphosphate
5. GTP-related transducin activates phosphodiesterase
6. cGMP hydrolysis to 5`-GMP
7. Reduction of cGMP concentration in the photoreceptor
8. Closing cationic channels

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/11.jpg" />
</div>

A single photon activates about 500 transducin molecules, closes hundreds of cationic channels, blocks the flow of a million sodium cations, and as a result, causes hyperpolarizations of around 1mV which is enormous reinforcement.

Finally, Metarodopsin II under the influence of vitamin A returns to the 11-cis form, joins back with opsin into a rhodopsin molecule ready for disintegration - this is the so-called **vision cycle**.

## Auditory system
The auditory canal is a passive antenna that transmits vibrations to the **eardrum**. The eardrum vibrations are transmitted through three auditory ossicles (malleus, incus, and stapes) into **perilymph** and then to the **cochlea window**.

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/12.jpg" />

</div>
 *Picture from [here][middleear]*

The cochlea is a spiral-shaped, 3.5 cm long cavity in the bony labyrinth. Sound pressure propagates through the cochlea, affecting **Corti’s organ** and setting **basilar membrane** in motion. This membrane is characterized by a constant change in width, mass, and stiffness, which results in “frequency sorting.” A place (on the basilar membrane) with maximum vibrations corresponds to the frequency of a soundwave.

<div class="l-body">
  <img class="img-fluid rounded z-depth-0" src="{{site.baseurl}}/assets/img/2019-04-22/13.jpg" />
      
</div>
Picture from [here][cochlea]

The Organ of Corti is built by two types of **hair cells** (named "hair" for their appearance): **inner hair cells** and **outer hair cells**. The main task of outer hair cells is to increase fluid movement in the cochlea. This phenomenon is called **cochlear amplification**, and increase hearing sensitivity.

Fluid pressure on the **internal hair cells** opens mechanosensitive ion channels and enables potassium ions from the endolymph to enter the hair cell. It heads to depolarisation which causes the release of glutamate which stimulates afferent nerve fibers.

# Conclusion

I started by comparing the transduction process to the operation principle of an analog-to-digital converter, but this was an oversimplification. 

First of all, most sensory impressions are multimodal. The taste impression is also affected by the smell, structure, or texture of the food. Music is not only what reaches the ear, but also vibrations perceptible on the skin. 

Moreover, transduction is not limited to simply transcoding the stimulus to digital form. In many cases, the logical processing of the stimulus begins long before the signal reaches the appropriate nerve for a given sense. 

The natural sciences teach that the need for over-ordering can make it difficult to understand processes that have been evolved, not designed.

# References
* *Sensory Transduction: How Our Senses Work* - YouTube. Retrieved June 30, 2020, from https://www.youtube.com/watch?v=pO2x4bsdK9w

* Longstaff, A. (2000). Neuroscience. Garland Science.


[skin]: https://aibolita.com/nervous-diseases/46995-somatosensory-receptors-mechanoreceptors.html
[nasal]: http://www.angelfire.com/journal/ldps/EssentialOils.htm
[tongue]: http://www.doi.org/10.1016/j.pnsc.2008.06.012
[corti]: http://www.cochlea.org/en/hearing/ear
[cochlea]: https://commons.wikimedia.org/wiki/File:Cochlea.svg
[middleear]: https://www.nidcd.nih.gov/health/otosclerosis
[rodscons]: https://anthonysaba.wikispaces.com/
[reti]: https://www.doi.org/10.1128/JVI.69.11.7087-7098.1995
[eye]: https://doi.org/10.1017/9781108565011.064
[olf]: https://en.wikipedia.org/wiki/Olfactory_epithelium
[pip2]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3496677/
[pacini]: https://link.springer.com/chapter/10.1007%2F978-1-4615-8699-9_15
[tactile]: https://en.wikipedia.org/wiki/Tactile_corpuscle
[rufini]: https://medical-dictionary.thefreedictionary.com/Ruffini+corpuscle
[ad]: https://en.wikipedia.org/wiki/Analog-to-digital_converter
[pop]: https://en.wikipedia.org/wiki/Neural_coding#Population_coding
[decib]: https://en.wikipedia.org/wiki/Decibel
[da]: https://en.wikipedia.org/wiki/Dalton_(unit)
[touch]: https://www.ncbi.nlm.nih.gov/books/NBK21661/
[ear]: http://hyperphysics.phy-astr.gsu.edu/hbase/Sound/earsens.html
[interf]:https://doi.org/10.1103/PhysRev.159.1084
[krotkie]: https://isbnsearch.org/isbn/9788301138059
[quantum]: https://en.wikipedia.org/wiki/Wave%E2%80%93particle_duality
[lightbook]: https://physics.info/light/
[amboss]: https://www.youtube.com/watch?v=pO2x4bsdK9w
[perception]: https://www.verywellmind.com/perception-and-the-perceptual-process-2795839
[electro]:https://byjus.com/physics/characteristics-of-em-waves/
