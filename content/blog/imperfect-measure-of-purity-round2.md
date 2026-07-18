+++
title = 'An Imperfect Measure of Purity—Round 2'
date = '2026-02-01'
draft = false
summary = 'More meditations on electrical conductivity and the imperfect concept of the perfect insulator.'
tags = ['conductivity', 'Grotthuss mechanism', 'pure water', 'resistivity', 'Water Resiliency']

[paige.pages]
disable_word_count = true
disable_reading_time = true
+++

{{< paige/figure float="start" >}}
<img src="/images/blog/imperfect-measure-of-purity-round2/water-molecule-image.png" alt="Water molecule auto-ionization" style="width: 350px;">
{{< /paige/figure >}}

<div style="padding-right: 2rem;">

<p>The electrical conductivity of "pure water" is determined by auto-ionization of water molecules and the dissolution of atmospheric CO<sub>2</sub> according to Henry's law, coupled with carbonate equilibria. The whole system balances on temperature and pressure.</p>

<p>In Round 1, we scrutinized the textbook claim that pure water is a perfect insulator. This statement is paradoxical and, as we countered, incorrect. By examining water's molecular structure, we established why water exhibits electrical conductivity, a universal material property and fundamental measure of salinity in water quality. In Round 2, we extend these observations to determine the theoretical minimum conductivity of pure water and explain why no definition of "pure water" yields exactly zero conductivity. Tighten your wigs, conquistadores, we're voyaging to the electrochemical headwaters in this round.</p>

</div>

<!--more-->

<div style="max-width: 800px; margin: 0 auto; padding: 0 1.5rem;">

<p>The meaning of "pure water" in the context of electrical conductivity has two definitions: a theoretical, idealized definition and a practical definition. The idealized definition, in its strictest sense, refers to water containing only H<sub>2</sub>O molecules and nothing else:</p>

<ul>
  <li>no dissolved gases (including CO<sub>2</sub>, O<sub>2</sub>, and N<sub>2</sub>)</li>
  <li>no dissolved ions (salts, acids, or bases)</li>
  <li>no particulate or organic contaminants</li>
</ul>

<p>This theoretical ideal is nearly impossible to achieve and sustain in the real world.</p>

<p>Then, there's "Ultrapure Water," often called Type I Water, referenced by <a href="https://cdn.standards.iteh.ai/samples/9169/c86dc332be2847eebd009b52ef8b00a5/ISO-3696-1987.pdf" target="_blank" rel="noopener">ISO 3696</a> and <a href="https://img.antpedia.com/standard/files/pdfs_ora/20200926/ASTM%20D1193-2006(2011)_8750.pdf" target="_blank" rel="noopener">ASTM D1193</a>, with the following specifications:</p>

<ul>
  <li>Conductivity: 0.055 µS/cm at 25°C</li>
  <li>Resistivity: 18.2 MΩ/cm at 25°C</li>
  <li>pH: 6.998 at 25°C</li>
  <li>Total Organic Carbon (TOC): &lt; 10 ppb (parts per billion)</li>
</ul>

<p>There's also Type II Deionized Water (DI Water) and Type III Distilled Water, produced by ion exchange resins and distillation, sometimes both, with the following characteristics:</p>

<ul>
  <li>Conductivity: 0.1-5 µS/cm at 25°C</li>
  <li>Resistivity: 2 MΩ/cm ≤ ρ ≤ 1.0 MΩ/cm at 25°C</li>
  <li>pH: 5.7–7.5 at 25°C</li>
  <li>TOC: Type II ≤50 ppb Type III: not specified</li>
</ul>

<p>Type II and Type III Waters are typically what's used for routine laboratory work, where purity specifications can be relaxed somewhat. "Pure" rainwater has no specification attached to it but may be considered free from atmospheric gases (CO<sub>2</sub>, O<sub>2</sub>, N<sub>2</sub>) and anthropogenic pollutants, at least the moment it condenses. However, the purity of rainwater degrades nearly instantaneously. Rainwater in equilibrium with atmospheric CO<sub>2</sub> (415 parts per million in 2025) has a pH of 5.6 and a conductivity of ~0.99 µS/cm at 25°C, as we shall validate.</p>

<p>Note that, for all classifications of water, conductivity is non-zero. What ions, then, are present to establish conductivity even in Ultrapure Type I Water?</p>

<p>First, pure water is never a "perfect" insulator, even under stringent conditions, because water itself undergoes auto-dissociation (self-ionization):</p>

<p style="text-align: center;">H<sub>2</sub>O ⇌ H<sup>+</sup> + OH<sup>–</sup> (or more accurately: 2H<sub>2</sub>O ⇌ H<sub>3</sub>O<sup>+</sup> + OH<sup>–</sup>)</p>

<p>At 25°C, the equilibrium constant (K<sub>w</sub>) = 1.01 × 10<sup>-14</sup> mol/kg<sup>-2</sup> H<sub>2</sub>O (Marshall and Frank, 1981), giving:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/equilibrium-constant-eq.png" alt="Equilibrium constant equations" style="width: 350px;">
</div>

<p>In pure water, the ionic concentration due to auto-dissociation alone yields a pH of 7.0. We can check this:</p>

<p style="text-align: center;">pH = -log<sub>10</sub>[H<sup>+</sup>]</p>
<p style="text-align: center;">pH = -log<sub>10</sub>(1.0005 × 10<sup>-7</sup>)</p>
<p style="text-align: center;">pH = 6.998</p>

<p>This is within the measurement uncertainty, given that numerous experimental values for K<sub>w</sub> have been reported.</p>

<p>The H<sup>+</sup> and OH<sup>–</sup> ions mobilize via proton hopping (the Grotthuss mechanism), rather than via diffusion, which is the dominant mechanism for ion transport in solution.</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/grotthuss-mechanism-image.png" alt="Grotthuss mechanism diagram" style="width: 100%;">
</div>

<p>The Grotthuss mechanism describes how protons (H<sup>+</sup>) move through water not by physically diffusing through the liquid, but by sequential proton transfers along chains of hydrogen-bonded water molecules. Hydroxide ions (OH<sup>–</sup>) also move via a Grotthuss-like mechanism, but the process differs in important ways and has been more controversial to characterize.</p>

<p>We must now determine the ionic conductivity per charge (symbol: λ), representing the conductivity contribution of one equivalent of the ions H<sup>+</sup> and OH<sup>–</sup> at infinite dilution. This sounds scary, but fortunately, these values are readily available from published sources like the CRC Handbook (Rumble, 2025):</p>

<p style="text-align: center;">H<sup>+</sup> = 349.8 S/cm²/equivalent</p>
<p style="text-align: center;">OH<sup>–</sup> = 198.6 S/cm²/equivalent</p>

<p>Note that the units of ionic conductivity are siemens (S) per square centimeter (cm<sup>2</sup>) per equivalent. In chemistry, an "equivalent" represents the charge contribution of an ion; for example, H<sup>+</sup> has one equivalent (single charge, monovalent), Ca<sup>2+</sup> has two equivalents (2<sup>+</sup> charge, divalent), and so on. The conductivity of a solution is given by the total specific conductivity equation:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/conductivity-summation-eq.png" alt="Total specific conductivity equation" style="width: 350px;">
</div>

<p>Where:</p>
<ul>
  <li>κ = conductivity<sup style="color: #EE0000;">1</sup> (S/cm)</li>
  <li>λ°ᵢ = equivalent conductivity of ion "i" at infinite dilution (S/cm²/equivalent)</li>
  <li>cᵢ = concentration of ion "i" (equivalent/cm³)</li>
  <li>|zᵢ| = absolute value of the charge on ion "i"</li>
  <li>Sum is over all ions</li>
</ul>

<p>Recall that for pure water, only two ions are present. Hence, the electrical conductivity of pure water is given by:</p>

<p style="text-align: center;">κ = λ(H<sup>+</sup>) × [H<sup>+</sup>] + λ(OH<sup>–</sup>) × [OH<sup>–</sup>]</p>

<p>The concentration must now be expressed as the number of equivalents per cubic centimeter (equivalent/cm<sup>3</sup>). Starting with moles per liter (mol/L), which is the more common expression of ion concentration, we determine that:</p>

<p style="text-align: center;">1 mol/L = 1 equivalent/L (for monovalent ions)</p>
<p style="text-align: center;">1 L = 1000 cm³</p>
<p style="text-align: center;">Therefore: 1 mol/L = 0.001 equivalent/cm³</p>

<p>Using this relationship, we can calculate c<sub>i</sub>, the concentration of H<sup>+</sup> and OH<sup>–</sup> ions in equivalents per cubic centimeter:</p>

<p style="text-align: center;">[H<sup>+</sup>] = 1.0351 × 10<sup>-7</sup> mol/L × 0.001 = 1.0351 × 10<sup>-10</sup> equivalent/cm³</p>
<p style="text-align: center;">[OH<sup>–</sup>] = 1.0351 × 10<sup>-7</sup> mol/L × 0.001 = 1.0351 × 10<sup>-10</sup> equivalent/cm³</p>

<p>Lastly, we find the sum of the products (λᵢ × cᵢ) in the conductivity equation:</p>

<p>From H<sup>+</sup>:</p>
<p style="text-align: center;">κ(H<sup>+</sup>) = 349.8 S/cm²/equivalent × 1.0351 × 10<sup>-10</sup> equivalent/cm³</p>
<p style="text-align: center;">κ(H<sup>+</sup>) = 3.6207 × 10<sup>-8</sup> S/cm</p>

<p>And from OH<sup>–</sup>:</p>
<p style="text-align: center;">κ(OH<sup>–</sup>) = 198.6 S·cm²/equivalent × 1.0351 × 10<sup>-10</sup> equivalent/cm³</p>
<p style="text-align: center;">κ(OH<sup>–</sup>) = 2.0557 × 10<sup>-8</sup> S/cm</p>

<p>Total conductivity is the sum of the individual conductivities:</p>
<p style="text-align: center;">κ = κ(H<sup>+</sup>) + κ(OH<sup>–</sup>)</p>
<p style="text-align: center;">κ = 3.6207 × 10<sup>-8</sup> + 2.0557 × 10<sup>-8</sup></p>
<p style="text-align: center;">κ = 5.6764 × 10<sup>-8</sup> S/cm</p>

<p>This yields the total conductivity in S/cm, whereas the specification for Type I "Ultrapure" Water is given in µS/cm. Since 1 S = 10<sup>6</sup> µS:</p>
<p style="text-align: center;">κ = 5.6764 × 10<sup>-8</sup> S/cm × 10<sup>6</sup></p>
<p style="text-align: center;"><strong>κ = 0.0568 µS/cm</strong></p>

<p>Conductivity of Type I Ultrapure Water = 0.057 µS/cm at 25°C (rounded to three significant digits).</p>

<p>The difference (&lt; 3%) is within the expected uncertainty for the ISO 3696 and ASTM D1193 specifications, 0.055 µS/cm. However, the conductivity of Type I Ultrapure Water is certainly not zero!</p>

<p>Type I Ultrapure Water also has a measurable resistivity (ρ), defined as the reciprocal of conductivity<sup style="color: #EE0000;">2</sup>:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/resistivity-eq.png" alt="Resistivity equation" style="width: 200px;">
</div>

<p style="text-align: center;">ρ = 1 / (5.6764 × 10<sup>-8</sup> S/cm)</p>
<p style="text-align: center;">ρ = 1.7617 × 10<sup>7</sup> Ω/cm</p>

<p>Since the specification for Type I Water is given in Megaohms per centimeter (MΩ/cm), the following conversion applies:</p>

<p style="text-align: center;">ρ = 1.7617 × 10<sup>7</sup> Ω/cm / 10<sup>6</sup></p>
<p style="text-align: center;">ρ = 17.62 MΩ/cm</p>

<p><strong>Resistivity of Type I Ultrapure Water = 17.62 MΩ/cm at 25°C.</strong></p>

<p>Again, the difference is within the expected uncertainty for the ISO 3696 and ASTM D1193 specifications, 18.24 MΩ/cm.</p>

<p>Next, let's examine what happens when Type I Ultrapure Water is exposed to atmospheric CO<sub>2</sub>. This will lean on <a href="https://en.wikipedia.org/wiki/Henry%27s_law" target="_blank" rel="noopener">Henry's law</a>, which quantifies the solubility of gas under pressure:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/henrys-law-eq.png" alt="Henry's law equation" style="width: 250px;">
</div>

<p>Where:</p>
<ul>
  <li>C = concentration of dissolved gas in a liquid (mol/L)</li>
  <li>K<sub>H</sub> is Henry's law constant of proportionality (Henry's law constant)</li>
  <li>P<sub>gas</sub> is the partial pressure of the gas (usually in atm)</li>
</ul>

<p>When CO<sub>2</sub> first dissolves in water, it forms carbonic acid:</p>

<p style="text-align: center;">CO<sub>2</sub>(aq) + H<sub>2</sub>O ⇌ H<sub>2</sub>CO<sub>3</sub> ⇌ H<sup>+</sup> + HCO<sub>3</sub><sup>–</sup></p>

<p>This is a multi-stage dissolution equilibrium, where CO<sub>2</sub>(aq) represents the dissolved carbon dioxide gas in water, i.e., molecules that have crossed the air-water interface but have not yet reacted chemically with water; H<sub>2</sub>CO<sub>3</sub> is the undissociated carbonic acid, which dissociates to release a proton (H<sup>+</sup>) and bicarbonate ion HCO<sub>3</sub><sup>–</sup>.</p>

<p>The complete system spans four carbon-containing species:</p>

<p style="text-align: center;">CO<sub>2</sub>(aq) ⇌ H<sub>2</sub>CO<sub>3</sub> ⇌ HCO<sub>3</sub><sup>–</sup> + H<sup>+</sup> ⇌ CO<sub>3</sub><sup>2–</sup> + 2H<sup>+</sup></p>

<p>The relative abundance of each depends strongly on pH.</p>

<p>For Henry's law calculations, we need the atmospheric concentration of CO<sub>2</sub> and its partial pressure. As of 2025, atmospheric CO<sub>2</sub> levels were reported at 415 ppm (parts per million). The partial pressure of CO<sub>2</sub> is given by:</p>

<p style="text-align: center;">pCO<sub>2</sub> = (415 ppm / 1,000,000) × 1 atm = 4.15×10<sup>-4</sup> atm</p>

<p>This is the partial pressure of CO<sub>2</sub> in the atmosphere <em>at sea level</em>.</p>

<p>For CO<sub>2</sub> at 25°C, K<sub>H</sub> ≈ 0.034 mol/(L/atm) (Plummer and Busenberg, 1982 and others).</p>

<p>This means that at 1 atm of pure CO<sub>2</sub>, 0.034 moles of CO<sub>2</sub> per liter of water would dissolve.</p>

<p>Using Henry's Law at 25°C:</p>

<p style="text-align: center;">[CO<sub>2</sub>(aq)] = K<sub>H</sub> × pCO<sub>2</sub></p>
<p style="text-align: center;">[CO<sub>2</sub>(aq)] = 0.034 mol/(L/atm) × 4.15×10<sup>-4</sup> atm = 1.41×10<sup>-5</sup> mol/L</p>

<p>This is the total dissolved CO<sub>2</sub> that would be in equilibrium with atmospheric CO<sub>2</sub>.</p>

<p>However, we want to calculate the conductivity of pure water in equilibrium with 415 ppm atmospheric CO<sub>2</sub>. For this, we need the equilibrium concentration of all ion species present in water when the dissolved CO<sub>2</sub> concentration is 1.41×10<sup>-5</sup> mol/L, per Henry's law. These would include H<sup>+</sup>, HCO<sub>3</sub><sup>–</sup>, OH<sup>–</sup>, CO<sub>3</sub><sup>2-</sup>. We can then utilize the conductivity equation to calculate κ.</p>

<p>This is a multi-step procedure that employs a set of constants; exact values may vary by source. We employ the Plummer and Busenberg (1982) ones below.</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/plummer-busenberg-constants-table.png" alt="Plummer and Busenberg constants table" style="width: 500px;">
</div>

<p><strong>Step 1:</strong> Solve for the concentration of H<sup>+</sup>, HCO<sub>3</sub><sup>–</sup>, OH<sup>–</sup>, and CO<sub>3</sub><sup>2–</sup> ions.</p>

<p>For [H<sup>+</sup>], the hydrogen ion concentration for the charge balance in pure water with dissolved CO<sub>2</sub>, we observe that:</p>

<p style="text-align: center;">[H<sup>+</sup>] = [HCO<sub>3</sub><sup>–</sup>] + 2[CO<sub>3</sub><sup>2–</sup>] + [OH<sup>–</sup>]</p>

<p>At pH &lt; 8, [CO<sub>3</sub><sup>2–</sup>] and [OH<sup>–</sup>] are negligible, so:</p>

<p style="text-align: center;">[H<sup>+</sup>] ≈ [HCO<sub>3</sub><sup>–</sup>]</p>

<p>Since the given dissociation constant K<sub>w</sub> of pure water under auto-ionization is 1.00 × 10<sup>-14</sup> its pH is:</p>

<p style="text-align: center;">pH = −log<sub>10</sub>(1.00 × 10<sup>-14</sup>)</p>
<p style="text-align: center;">pH = 7.0</p>

<p>So, it's justified to set [H<sup>+</sup>] = [HCO<sub>3</sub><sup>–</sup>] in this system.</p>

<p>From the first dissociation equilibrium:</p>

<p style="text-align: center;">K<sub>1</sub> = [H<sup>+</sup>][HCO<sub>3</sub><sup>–</sup>] / [CO<sub>2</sub>(aq)]</p>

<p>Substituting [H<sup>+</sup>] = [HCO<sub>3</sub><sup>–</sup>]:</p>

<p style="text-align: center;">K<sub>1</sub> = [H<sup>+</sup>]² / [CO<sub>2</sub>(aq)]</p>
<p style="text-align: center;">[H<sup>+</sup>]² = K<sub>1</sub> × [CO<sub>2</sub>(aq)]</p>
<p style="text-align: center;">[H<sup>+</sup>]² = (4.47 × 10<sup>-7</sup>) × (1.407 × 10<sup>-5</sup>)</p>
<p style="text-align: center;">[H<sup>+</sup>]² = 6.29 × 10<sup>-12</sup></p>
<p style="text-align: center;">Solving for [H<sup>+</sup>] = √6.29 × 10<sup>-12</sup></p>
<p style="text-align: center;"><strong>[H<sup>+</sup>] = 2.51 × 10<sup>-6</sup> mol L<sup>-1</sup></strong></p>

<p>The pH of pure water in contact with atmospheric CO<sub>2</sub> is:</p>

<p style="text-align: center;">pH = −log<sub>10</sub>(2.51 × 10<sup>-6</sup>)</p>
<p style="text-align: center;">pH = 5.60</p>

<p>This is classified as mildly acidic. Water with a pH below or above this level must contain other acids or bases and would be considered impure.</p>

<p>The OH<sup>–</sup> concentration follows directly from:</p>

<p style="text-align: center;">K<sub>w</sub> = [H<sup>+</sup>] [OH<sup>–</sup>] = 1.00 × 10<sup>-14</sup> at 25°C</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/ion-concentrations-table.png" alt="Ion concentrations equation" style="width: 350px;">
</div>

<p>The answer 3.98 × 10<sup>-9</sup> mol/L is reasonable because the H<sup>+</sup> concentration is elevated above the neutral pH (10<sup>-7</sup> M) due to the formation of carbonic acid from dissolved CO<sub>2</sub>, which dissociates to release H<sup>+</sup> (protons). Since the water equilibrium constant K<sub>w</sub> remains fixed at 25°C, as [H<sup>+</sup>] increases, [OH<sup>–</sup>] must decrease proportionally.</p>

<p>The concentration of ions in pure water in equilibrium with CO<sub>2</sub> is summarized by:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/ion-concentrations-table.png" alt="Ion concentrations table" style="width: 400px;">
</div>

<p><strong>Step 2:</strong> Solve for the molar ionic conductivity of H<sup>+</sup>, HCO<sub>3</sub><sup>–</sup>, OH<sup>–</sup>, and CO<sub>3</sub><sup>2–</sup>. For brevity, we use published values at infinite dilution (λ°, 25°C):</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/molar-ionic-conductivity-table.png" alt="Molar ionic conductivity table" style="width: 400px;">
</div>

<p><strong>Step 3:</strong> Solve for total EC using the conductivity equation:</p>

<p style="text-align: center;">EC = Σ (c<sub>i</sub> × λ<sub>i</sub>°)</p>

<p>Summary of the individual contribution of ions to conductivity, tabulated:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/individual-ion-contribution-table.png" alt="Individual ion contribution table" style="width: 500px;">
</div>

<p>At this point, all that remains is to sum up the individual contributions to obtain the total specific conductivity:</p>

<p style="text-align: center;">κ = 8.78 × 10<sup>-4</sup> + 1.12 × 10<sup>-4</sup> + 7.88 × 10<sup>-7</sup> + 6.49 × 10<sup>-9</sup></p>
<p style="text-align: center;">κ = 9.91 × 10<sup>-4</sup> S/cm</p>

<p>Then convert to µS/cm:</p>

<p style="text-align: center;">κ = 9.91 × 10<sup>-4</sup> S/cm × 10<sup>6</sup> µS/S</p>
<p style="text-align: center;"><strong>κ = 0.99 µS/cm</strong></p>

<p>The fractional contribution breakdown is:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/fractional-contribution-table.png" alt="Fractional contribution table" style="width: 400px;">
</div>

<p>Summary of pure water chemistry in a closed and open system at 25°C:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/chemistry-closed-open-table.png" alt="Closed and open system summary table" style="width: 350px;">
</div>

<p>This shows, definitively, that exposure to atmospheric CO<sub>2</sub> (415 ppm) in an open system <em>increases</em> the conductivity of pure water by ~17.4×. In effect, rising CO<sub>2</sub> levels are salting <em>and</em> acidifying the Earth:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/Chart-1.png" alt="pH and EC vs CO2 concentration chart" style="width: 650px;">
<p style="font-size: 0.9rem; margin-top: 0.5rem;">Relationship between pH and EC of pure water in equilibrium with varying atmospheric CO<sub>2</sub> concentrations. The first scientifically rigorous, monthly average measurement of atmospheric CO<sub>2</sub> was 315 ppm, conducted by Charles Keeling in 1958 at Mauna Loa Observatory in Hawaii.</p>
</div>

<p>All the calculations we have done so far have been at a fixed temperature of 25°C and a pressure of 1 atm (sea level) to keep things simple. However, temperature and pressure are not constant across the Earth. The solubility of CO<sub>2</sub> gas in water is modulated by temperature and pressure according to Henry's law:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/Chart-2.png" alt="Dissolved CO2 dependence on pCO2" style="width: 550px;">
<p style="font-size: 0.9rem; margin-top: 0.5rem;">Henry's law predicts significantly more dissolved CO<sub>2</sub> at 0°C than at 50°C for a given partial pressure. This is because gas solubility in liquids is an exothermic process: as you add thermal energy (heat), you give the dissolved gas molecules enough kinetic energy to overcome the attractive forces of the water molecules and escape back into the atmosphere.</p>
</div>

<p>Which, in turn, influence pH and κ (EC), but in vastly different ways:</p>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/Chart-3.png" alt="pH dependence on pCO2" style="width: 550px;">
</div>

<div style="text-align: center; margin: 1.5rem 0;">
<img src="/images/blog/imperfect-measure-of-purity-round2/Chart-4.png" alt="EC dependence on pCO2" style="width: 550px;">
</div>

<p>This may portray an overly complex picture of EC for those uninitiated in the chemistry brotherhood, but the key point is this: The universality of EC stems from the fundamental physics wherein all materials contain charged particles (electrons, ions), and under an applied electric field, there's always some mechanism, however inefficient, for charge transport. Whether it's free electrons in metals, electron-hole pairs in semiconductors, self-ionizing proton hopping (Grotthuss mechanism), or ionic diffusion in electrolytes and even solids, conductivity is never truly zero.</p>

<p>Theoretically, for the electrical conductivity of water to be exactly zero, the "perfect insulator", you would need to achieve a state of <strong>absolute hermetic purity</strong> and <strong>absolute inhibition of auto-ionization</strong> at <strong>absolute zero</strong> (-273.15°C) temperature. At this temperature, molecular motion stops, and the energy required for auto-ionization is no longer available. Such conditions are virtually impossible to meet in a physical laboratory.</p>

<p>In short, water is a "universal solvent" that effectively generates its own conductors. You can get close to zero, but the laws of thermodynamics and the nature of the H<sub>2</sub>O molecule itself ensure there is always a tiny "hum" of electricity possible.</p>

<hr>

<p><strong>Footnotes</strong></p>

<p><sup style="color: #EE0000;">1</sup> In chemistry and electrochemistry, the lowercase Greek letter kappa (κ) symbolizes the conductivity of aqueous (water-based) systems. In physics and electrical engineering, the symbol σ (sigma) denotes electrical conductivity. In practice, scientists in either field often bypass Greek notation and use the acronym "EC" for electrical conductivity. Herein, we utilize kappa and EC interchangeably, formally and informally, as the case dictates.</p>

<p><sup style="color: #EE0000;">2</sup> Any material with measurable conductivity also has reciprocal resistivity, including the soil on which crops are grown and buildings are stabilized. Measuring soil resistivity is critical for grounding electrical infrastructure and for corrosion assessment (pipelines, tanks, foundations, and rebar steel). Measurement methods for soil resistivity differ from those for salinity conductivity.</p>

<hr>

<p><strong>Further Diggings</strong></p>

<p>Rumble, J.R., Ed. <em>CRC Handbook of Chemistry and Physics</em>, 106th ed.; CRC Press: Boca Raton, FL, 2025. ISBN 978-1032655666.</p>

<p>Marshall, W.L. and Franck, E.U. (1981). Ion product of water substance, 0-1000°C, 1-10,000 bars. New international formulation and its background. <em>J. Phys. Chem. Ref. Data</em>, 10(2), 295-304. <a href="https://doi.org/10.1063/1.555643" target="_blank" rel="noopener">DOI: 10.1063/1.555643</a></p>

<p>Plummer, L.N. and Busenberg, E. (1982). The solubilities of calcite, aragonite, and vaterite in CO<sub>2</sub>-H<sub>2</sub>O solutions between 0 and 90°C, and an evaluation of the aqueous model for the system CaCO<sub>3</sub>-CO<sub>2</sub>-H<sub>2</sub>O. <em>Geochimica et Cosmochimica Acta</em>, 46(6), 1011-1040. <a href="https://doi.org/10.1016/0016-7037(82)90056-4" target="_blank" rel="noopener">DOI: 10.1016/0016-7037(82)90056-4</a></p>

<p>Seinfeld, J.H. and Pandis, S.N. (2006). <em>Atmospheric Chemistry and Physics: From Air Pollution to Climate Change</em>, 2nd ed. John Wiley &amp; Sons, Hoboken, NJ.</p>

<p>Stumm, W. and Morgan, J.J. (1996). <em>Aquatic Chemistry: Chemical Equilibria and Rates in Natural Waters</em>, 3rd ed. John Wiley &amp; Sons, New York.</p>

<hr>

<p><em>Disclaimer: Links to digital content in this blog are for the reader's information only, not an endorsement of that content.</em></p>

</div>