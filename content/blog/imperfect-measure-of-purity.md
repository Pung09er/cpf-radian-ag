+++
title = 'An Imperfect Measure of Purity'
date = '2026-01-20'
draft = false
summary = 'Pure water is often described as a "perfect insulator" in the literature of chemistry and physics. Is this characterization accurate?'
tags = ['conductivity', 'dielectric', 'dipole moment', 'EMF', 'insulator', 'salinity', 'water']

[paige.pages]
disable_word_count = true
disable_reading_time = true
+++

<!--more-->

<div style="max-width: 800px; margin: 0 auto; padding: 0 1.5rem;">

<div style="float: left; width: 350px; margin-right: 1.5rem; margin-bottom: 3rem;">
<img src="/images/blog/imperfect-measure-of-purity/water-liquid-phase.jpg" alt="Liquid water drop" style="width: 350px; margin-bottom: 0;">
<p style="font-size: 0.85rem; font-style: italic; margin: 0; text-align: justify;">Water is a Protean, life-sustaining substance with no known replacement. Pure water is often described as a "perfect insulator" in the literature of chemistry and physics. Is this characterization accurate? We explore this question in the context of water's conductivity, a material property and fundamental measure of salinity.</p>
</div>

<p>When I joined the fledgling AMPLIFY Water Resiliency Initiative in 2021, one of the program's mandates was to evaluate the impact of rising salinity in soil, groundwater, and tidal flood zones in eastern North Carolina, a trend that has steadily increased over the past decades. Although I had extensive experience with soil moisture/groundwater monitoring systems for irrigation and drainage, I was not particularly well-versed in salinity beyond routine soil and water testing for crop health, troubleshooting, and the like. I soon realized that measuring salinity, when you go deep into the analytical weeds, is a complex topic shrouded by a profuse, sometimes befuddling vocabulary of formulae and expressions. But a journey always begins with a single step, so the Chinese proverb goes. With that in mind, let us resolutely dip our intellectual toes into the conceptual framework underlying salinity and proceed from there.</p>

<div style="clear:both; margin: 0; padding: 0;"></div>

<p>One of the fundamental expressions of salinity is siemens (S), an SI-derived unit of <em>electrical conductance</em> (G). Electrical conductance is the reciprocal of resistance, expressed as:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/conductance-equation-def.png" alt="Electrical conductance equation G = omega inverse or G = 1/omega" style="width: 150px; margin-bottom: 0;">
</div>

<p>Where Greek letter Omega Ω symbolizes resistance (R), the same quantity that is measured in an electrical circuit, expressed through Ohm's Law:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/ohms-law-relationship.png" alt="Ohm's Law V = I times R" style="width: 85px; margin-bottom: 0;">
</div>

<p>Ohm's law, in its original formulation, states that the current in Amperes (I) through a conductor is directly proportional to the voltage (potential difference) across it in Volts (V), provided the resistance in that conductor remains constant. A conductor has a conductance of 1 siemens when a potential difference of 1 volt produces a current of 1 ampere, yielding the fundamental relationship between units:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/siemens-relationship.png" alt="Siemens relationship 1S = 1/omega = 1 A/V" style="width: 110px; margin-bottom: 0;">
</div>

<p>To assess salinity, one must first measure its level, which is universally expressed in terms of electrical conductivity (κ) with units of siemens per centimeter (S/cm)<sup style="color: #E5BA66;">1</sup>.</p>

<p>Electrical conductivity, commonly abbreviated "EC" across the disciplines of environmental science, hydrology, and water quality, is a fundamental material property, arising from the motion of charged sub-atomic particles in an electromagnetic field<sup style="color: #E5BA66;">2</sup>. The force driving particle motion is the electric field, which is created when there's a difference in electrical potential (i.e., voltage) between two positions. The potential difference is called electromotive force (EMF).</p>

<p>In nature, there are various sources of EMF; perhaps the most visible and ubiquitous is light energy, whose photons drive photosynthesis to generate chemical energy in plants and electrical energy in photovoltaic systems. However, unlike the metallic conductors that connect our modern appliances to the power grid, where free electrons oscillate through a crystalline lattice of atomic cores, the conductivity of water operates through an entirely different mechanism. In water, electrical current primarily flows through dissolved charged particles called <em>ions</em>, including salts such as sodium chloride and calcium sulfate, as well as various omnipresent plant- and non-plant essential ions. The drift of these ions in response to an electric field establishes the property of electrical conductivity. As such, water is an <em>electrolytic</em> conductor rather than an <em>electronic</em> conductor, unlike a copper wire.</p>

<p>To frame this in agronomic terms, because water readily permeates the soil and may even saturate it at times, EC measures the concentration of salts in the soil water solution. In turn, agronomists use EC, along with pH, which measures acidity based on the concentration of hydrogen ions (H<sup>+</sup>), as critical indicators of productivity, or "health," of the soil, i.e., its capacity to sustain plant growth.</p>

<p>While perusing scholarly works on the properties of water, one claim struck me as contrary to physical reality: "pure water is a perfect insulator that does not conduct electricity". This is an exact quote from a major reference. Yet, we are all too aware that, in the imperfect physical world, water and electricity do not mix. If you work around energized circuits, even the infinitesimal film of water is your nemesis. What, then, is meant by "pure water"? Is there ever a situation in which water and electricity could mingle without measurable conductivity?</p>

<p>The answer is no.</p>

<p>First, let's review the definitions, properties, and classifications of insulators and conductors. An insulator is simply a material that strongly resists the flow of electrical current. In contrast, a conductor allows electric charge (electrons or ions) to flow through it easily. They represent opposite ends of a spectrum, with most materials falling somewhere between these extremes. Note the wording "strongly resists" in the definition of insulator. There are no perfect insulators at room temperature, and no perfect conductors except under certain conditions (i.e., superconductors). Materials exist on a continuous spectrum from perfect conductors to perfect insulators:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/conductivity-scale.png" alt="Conductivity scale from perfect conductor to perfect insulator" style="width: 675px; margin-bottom: 0;">
</div>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/conductivity-classification-table1.png" alt="Conductivity classification table" style="width: 500px; margin-bottom: 0;">
</div>

<p style="margin-bottom: 0.25rem;">It should be noted that these classifications are relative rather than absolute. For example, tap water is classified as a "weak conductor", but this is only compared to metals. Tap water contains many dissolved ions and will readily conduct an electrical current, certainly enough to be dangerous, but its conductivity is weak compared to, say, metals. To put this distinction in better perspective, consider the following table comparing material conductivities relative to tap water:</p>

<div style="text-align: center; margin: 0.5rem 0 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/material-conductivity-ratio-tap-water-table2.png" alt="Material conductivity ratio relative to tap water table" style="width: 550px; margin-bottom: 0;">
</div>

<p>The key point is that the electrical conductivities of materials span many orders of magnitude. Tap water is approximately 1.2 billion times less conductive than copper, but approximately 12 to 14 orders of magnitude <em>more</em> conductive than wood, which is classified as an "insulator", but not perfect. Paradoxically, water may also be classified as a weak insulator. <em>Whether something is classified as a conductor or an insulator is always relative to the full spectrum of materials</em>. Without a reference, labels like "conductor" and "insulator" are ill-defined and uninformative.</p>

<p>So, what about the nature of water would motivate physics and chemistry authorities to describe it as a "perfect insulator"? To evaluate this claim, we must examine the atomic structure of an isolated water molecule. For our purposes, a simple cartoon will suffice:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/single-water-molecule.png" alt="Single water molecule diagram showing bond angle and partial charges" style="width: 350px; margin-bottom: 0;">
<p style="font-size: 0.85rem; font-style: italic; margin: 0; text-align: justify;">Characteristics of an isolated water molecule. δ+ and 2δ- represent the partial positive and negative charges on the proton (hydrogen) and oxygen. The bond angle reportedly ranges from 104.52° to 109.5° but is typically represented as 105°. Atomic distance is nanometers (nm), one billionth of a meter. <em>Image credit: R. Walters</em></p>
</div>

<p>There are two principal things to notice in the figure above. First, water has a bent molecular structure (105° H-O-H angle), which creates a permanent electric dipole moment. A dipole moment measures how unevenly electric charge is distributed in a molecule — essentially, how "lopsided" it is electrically (Debye). The oxygen atom, being highly electronegative, pulls electron density away from the hydrogen atoms, creating a partial negative charge (δ-) on oxygen and a partial positive charge (δ+) on hydrogen<sup style="color: #E5BA66;">3</sup>.</p>

<p style="margin-bottom: 0.25rem;">An analogy for this asymmetric molecular charge distribution is that if two children of equal weight sit at equal distances from the center of a seesaw, the seesaw balances perfectly (zero dipole moment). If a heavier child sits on one side, or children sit at different distances, the seesaw tilts (non-zero dipole moment). The more unbalanced the seesaw, the greater the "tipping" effect (larger dipole moment). In molecules, the 'weight' is electrical charge, and the "distance from center" is where those charges are located. Molecules have different dipole moments, or none, depending on the individual contributions of electronegativity differences, polar bonds, lone-pair electrons, and sympathetic geometry. Water has all of these in its atomic DNA.</p>

<div style="text-align: center; margin: 0.5rem 0 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/dipole-moment-comparison-table3.png" alt="Dipole moment comparison table for common molecules" style="width: 450px; margin-bottom: 0;">
</div>

<p>But why do permanent electric dipoles matter?</p>

<p>Molecular dipoles are important because they govern how molecules interact with electric fields. Water's high dielectric constant (~80) arises from the ability of polar water molecules to reorient in response to electric fields, such as those produced by dissolved ions. This molecular alignment screens electrostatic interactions between ions, reducing the effective field strength by ~80 and allowing ionic compounds to dissolve readily.</p>

<p>Secondly, the polarity (separation of charge) of water molecules makes them mutually attractive (cohesive), a property resulting from hydrogen bonding. This same polarity also enables water to interact with (adhere to) other polar substances and ions. Polar water molecules can surround and stabilize dissolved ions through hydration shells, allowing the ions to separate and move freely. When ions are dissolved in water, these mobile charged ions make the solution electrically conductive, though "pure water" itself is a poor conductor.</p>

<p>Hydrogen bonds form when the partially positive hydrogen of one water molecule is attracted to the partially negative oxygen of another. The electrostatic force in hydrogen bonding is weak compared to covalent bonding, but relatively strong when the O-H bond from one molecule is oriented toward a nearby oxygen atom, with the three atoms (O-H-O) positioned approximately linearly.</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity/walter-molecules.png" alt="Three water molecules showing hydrogen bonds" style="width: 450px; margin-bottom: 0;">
<p style="font-size: 0.85rem; font-style: italic; margin: 0; text-align: justify;">Water molecules interact with one another via weak hydrogen bonds. One water molecule can participate in four hydrogen bonds with other water molecules. This force of attraction between molecules, combined with the high density of molecules due to their small size, produces strong cohesion, which is responsible for water's liquid nature at standard pressure (1 atm) and at ambient temperatures 0° to 100°C. <em>Image credit: R. Walters</em></p>
</div>

<p>The fact that water is a liquid at room temperature further enhances ion mobility. The alignment (polarization) of dipoles in an electric field is also responsible for water's excellent dielectric properties, enabling the storage of electrical energy. This is the principle underlying capacitors in modern water-based dielectric sensors, in which the dielectric constant of the system varies with the frequency of the electromagnetic field, enabling accurate measurement of environmental conditions.</p>

<p>The term "perfect insulator" (or "ideal dielectric") specifically means zero conductivity: all applied voltage drops across the material with no steady-state current. In practice, water's behavior depends on exposure to electromagnetic frequencies, as well as on temperature and purity. At low frequencies (DC-1 GHz), water conducts electricity due to the presence of ionic species. Even "Ultrapure Water" has some conductivity, as we shall quantitatively determine later. At high frequencies (MHz-GHz range), water behaves more like a dielectric, as ionic conduction becomes less significant and dipole rotation dominates. Dissolved ions dramatically increase conductivity, making typical water a relatively poor insulator.</p>

<p>Free water generally experiences low-intensity, low-frequency electromagnetic fields (e.g., Earth's electric field, infrared and visible light) in which dipole rotation is possible, but direct effects on conductivity are minimal. Water bound within the soil is also subject to multiple electric-field effects, both natural and those generated by root metabolism (ion-pumping effect) and by the soil matrix itself. These field effects are modulated by soil water content, which, in turn, defines the upper and lower limits of conductivity. This is a very complex and important topic in soil science and agronomy beyond the scope of this piece.</p>

<p>So, what is the theoretical minimum conductivity (or resistivity) of "pure water" described as a "perfect insulator"? I'll tackle that subject in Round 2, because we have journeyed herein far enough through the thickets and unpruned foliage of molecular behavior.</p>

<p>The key takeaway is that evidence from well-characterized atomic properties of water suggests that it's not a "perfect insulator" at all, but a <em>relatively</em> weak one under anything resembling non-theoretical, idealized conditions. Water's high dielectric constant is sometimes confused with insulating ability. A high dielectric constant means strong polarization, not necessarily poor conduction (or good insulation).</p>

<p>Bottom line, it's not okay to drop that hair dryer in the bathtub to see what happens, regardless of what textbook theory dictates is true.</p>

<hr>

<p><strong>Footnotes</strong></p>

<p><sup style="color: #E5BA66;">1</sup> Centimeter (cm) is the standardized unit of distance, typically with electrodes on opposite faces 1 cm apart, with conductance measured across those faces. Since conductance and resistance are reciprocals, an example is a 12-gauge wire with a given resistance per unit length (resistivity: ohms per meter), a concept familiar to electricians. Material engineers often express conductivity in Siemens per meter, so be careful!</p>

<p><sup style="color: #E5BA66;">2</sup> Conductance (symbol: G) extends beyond its electrical context. The concept applies broadly to any system where flow is proportional to a driving force. Analogous uses in other agronomic/engineering domains would include thermal, hydraulic, and stomatal conductance.</p>

<p><sup style="color: #E5BA66;">3</sup> There are no positive movable charges in atoms or molecules. When we write about or symbolize a "positive charge", it is implied that there's a deficit of electrons at a certain location, not a movement of positive charges (protons) to that location.</p>

<hr>

<p><em>Disclaimer: Links to digital content in this blog are for the reader's information only, not an endorsement of that content.</em></p>

</div>