---
layout: page
title: Research
icon: fas fa-flask
order: 2
---

<style>
.research-project {
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(260px, 0.8fr);
  gap: 2rem;
  align-items: start;
  margin: 1.5rem 0 2.5rem;
}

.research-project-images-left {
  grid-template-columns: minmax(260px, 0.8fr) minmax(0, 1fr);
}

.research-text {
  min-width: 0;
}

.research-images {
  min-width: 0;
}

.research-images figure {
  margin: 0 0 1.5rem;
}

.research-images img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 360px;
  object-fit: contain;
  margin: 0 auto;
}

.research-images figcaption {
  margin-top: 0.5rem;
  font-size: 0.85rem;
  line-height: 1.4;
  text-align: center;
}

@media (max-width: 768px) {
  .research-project,
  .research-project-images-left {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .research-text {
    order: 1;
  }

  .research-images {
    order: 2;
  }

  .research-images img {
    max-height: 400px;
  }
}
</style>

## 1. Thermochemical Evolution of Continental Lithosphere (PhD)

- **Duration:** January 2026 to present
- **With:** Dr. Ajay Kumar

Details coming soon. Sorry. 

---

## 2. Global Moho Compilation and Thermodynamic Datasets (Project Assistant)

<div class="research-project research-project-images-left">

  <div class="research-images">

<figure>
  <img src="/assets/img/research/global_moho.png"
       alt="Global crustal thickness compiled from receiver function studies and Crust1.0">
  <figcaption>
    Global crustal thickness compiled from receiver-function studies and Crust1.0, gridded using spline interpolation.
  </figcaption>
</figure>

  </div>

  <div class="research-text">

<p>
  <strong>Duration:</strong> August 2024 to July 2025<br>
  <strong>With:</strong> Dr. Ajay Kumar
</p>

<p>
  I have developed thermodynamic datasets using <em>Perple_X</em> to support conversion of seismic tomographic velocities into temperature estimates for the crust and shallow mantle. The datasets include <strong>Vp, Vs, and density</strong> for temperatures of 273–1573 K and pressures up to 15 GPa.
</p>

<p>
  A compilation of the global crustal thickness from receiver-function studies and <em>Crust1.0</em> were done. Using <em>Fatiando a Terra</em>'s <em>Verde</em> spline interpolation, I generated a high-resolution gridded global Moho-depth dataset for integration with Python, GMT, and other computational workflows.
</p>

<p>
  <em>
    For references or access to the grid file, please contact me through the
    <a href="/contact/">Contact</a> page. Additional details and the corresponding
    GitHub repository will be added as the project webpage develops.
  </em>
</p>

  </div>

</div>

---

## 3. Effect of Hydration on the Iron Spin Crossover in Bridgmanite (MS Project)

<div class="research-project">

  <div class="research-text">

    <p>
      <strong>Advisor:</strong> Dr. Gaurav Shukla, Department of Earth Sciences, IISER Kolkata, India<br>
      <strong>Duration:</strong> 2023–2024
    </p>

    <p>
      Bridgmanite is the most abundant mineral in the Earth's lower mantle, and the spin crossover of iron in Fe<sup>3+</sup>-bearing bridgmanite is a key factor affecting the compressibility, sound velocity, and thermal structure of the system.
    </p>

    <p>
      The phase transition in anhydrous bridgmanite is a well-established phenomenon, but relatively little is known about what happens in hydrous systems. Here, I calculated the equations of state of Fe(III)-bearing hydrous bridgmanite to study its structural and elastic properties in the lower mantle using first-principles density functional theory (<em>ab initio</em> DFT).
    </p>

  </div>

  <div class="research-images">

    <figure>
      <img src="/assets/img/research/ms_project.png"
           alt="Low spin fractionation in hydrous bridgmanite">

      <figcaption>
        Low spin fractionation: as observed due to the transition from high spin to low spin at the phase transition pressure.
      </figcaption>
    </figure>

  </div>

</div>

---

## 4. Crustal Evolution of Different Archean Cratons Using Receiver Function Analysis Implementing H-K Stacking and Joint Inversion (Semester Project)

<div class="research-project research-project-images-left">

  <div class="research-images">

    <figure>
      <img src="/assets/img/research/seismology-1.png"
           alt="Moho depth at the Guapure Craton in South America">

      <figcaption>
        Moho depth at the Guapure Craton in South America. Top: Joint Inversion. Right: Zhu-Kanamori H-K stacking.
      </figcaption>
    </figure>

    <figure>
      <img src="/assets/img/research/seismology-2.png"
           alt="Receiver function analysis of Archean cratons">
    </figure>

  </div>

  <div class="research-text">

    <p>
      <strong>Advisor:</strong> Dr. Kajaljyoti Borah, Department of Earth Sciences, IISER Kolkata, India<br>
      <strong>Duration:</strong> 2022–2023
    </p>

    <p>
      I studied the crustal evolution of different Archean cratons using receiver function analysis. I used conventional P-RFs for modeling these receiver functions with H-K stacking and Joint Inversion.
    </p>

    <p>
      I used surface-wave dispersion data (global dispersion data collected from GMD52) together with receiver functions to construct forward models and establish a better understanding of crustal depth–velocity structure. This global optimization provided constraints on the Moho in different cratons.
    </p>

    <p>
      Linking the Moho discontinuity with its depth and velocity structure emphasized the similarities and differences in crustal structure globally, contributing to our understanding of lithospheric formation and evolution on a global scale.
    </p>

  </div>

</div>

---

## 5. Studies on GNSS Pseudorange and Carrier Phase Residuals for Data Quality and Antenna Location Assessment (Internship)

<div class="research-project">

  <div class="research-text">

    <p>
      <strong>Advisor:</strong> Dr. Anindya Bose,
      <a href="https://bugnss.in/" target="_blank" rel="noopener noreferrer">GNSS Lab</a>,
      Department of Physics, The University of Burdwan, India<br>
      <strong>Duration:</strong> 2019 &amp; 2021
    </p>

    <p>
      In 2019, I worked on Precise Point Positioning (PPP) using GNSS pseudorange and carrier-phase residuals. At first, I studied GNSS pseudorange and carrier-phase residuals for data quality and antenna location assessment. I also compared the data quality between one high-cost (JAVAD) and one low-cost receiver (u-blox F9P).
    </p>

    <p>
      In 2021, the work was associated with an ongoing project entitled
      <em>“Applicability of Compact GNSS Modules in Real Time Improvement of Position Accuracy for Test Range Applications”</em>,
      sponsored by DRDO Integrated Test Range (ITR), Chandipur, Balasore.
    </p>

    <p>
      I compared GNSS Precise Point Positioning using data collected simultaneously from four different receivers (two high-cost and two low-cost) and compared their performance using different online processing platforms on three different occasions: Rapid (instantaneously), 3-day delay, and 15-day delay.
    </p>

  </div>

  <div class="research-images">

    <figure>
      <img src="/assets/img/research/gnss.png"
           alt="u-blox F9P satellite receiver">

      <figcaption>
        u-blox F9P satellite receiver.
      </figcaption>
    </figure>

  </div>

</div>