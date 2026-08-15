---
permalink: /
title: "Who am I"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="about-profile">

<p class="about-profile__intro">Greetings!! I'm a research scientist at CEA—French Atomic Energy and Alternative Energies Commission. My expertise includes high performance computing, finite element method, Boltzmann transport, and meshing. I hold a PhD in computational physics, a master's in computational fluid dynamics, and a bachelor's in aerospace engineering. In a nutshell, I'm the wizard of numbers and equations, blending science and technology to unlock the secrets of the universe.</p>

<section class="about-section" aria-labelledby="research-areas">
  <h2 id="research-areas">Areas of Research</h2>
  <ul class="about-topics">
    <li>Finite Element Methods</li>
    <li>Parallel computing</li>
    <li>Meshing</li>
    <li>Mesh Adaption</li>
    <li>Radiative transport</li>
    <li>Computational Fluid Dynamics</li>
  </ul>
</section>

<section class="about-section" aria-labelledby="research-codes">
  <h2 id="research-codes">Codes that I am developing</h2>
  <div class="software-list">
    <p><a href="https://www.salome-platform.org/">SALOME</a><span>Pre/post-processing scientific computing tool for CAD, meshing, visualization</span></p>
    <p><a href="https://github.com/arcaneframework/arcanefem">ArcaneFEM</a><span>Parallel FEM solver based on CPU-GPU parallelism</span></p>
    <p><a href="https://github.com/mohd-afeef-badri/psd">PSD</a><span>Massively parallel Solid/Structural/Seismic Dynamics FEM solver</span></p>
    <p><a href="https://github.com/mohd-afeef-badri/top-ii-vol">top-ii-vol</a><span>Massively parallel geophysics mesher-partitioner tool</span></p>
    <p><a href="https://github.com/mohd-afeef-badri/pdmt">PDMT</a><span>Parallel Dual Meshing Tool, is a polyhedral meshing/remsehing too</span></p>
    <p><a href="https://github.com/mohd-afeef-badri/medio">medio</a><span>library that facilitates input and output of mesh files for FreeFEM in the <code>med</code> format</span></p>
  </div>
</section>

<section class="about-section research-section" aria-labelledby="current-research">
  <h2 id="current-research">Current areas of research</h2>

  <article class="research-item">
    <h3>Polyhedral Meshing</h3>
    <div class="research-feature">
      <figure><img src="https://github.com/mohd-afeef-badri/pdmt/assets/52162083/bc7f98a6-7631-439d-934f-7daa49250721" alt="Polyhedral mesh"></figure>
      <p>Polyhedral meshing is gaining importance in modern computational simulations. It offers advantages in terms of accuracy, adaptability to complex geometries, efficiency in parallel computing, and improved convergence of numerical solvers. These benefits make polyhedral meshing a valuable tool in various scientific and engineering applications.</p>
    </div>
    <details>
      <summary>Load more</summary>
      <div class="research-gallery research-gallery--described">
        <figure><img src="https://github.com/mohd-afeef-badri/pdmt/assets/52162083/8ae5798d-5a4f-474d-ae39-c7207085f7bd" alt="Image 1"><figcaption>Text description for Image 1</figcaption></figure>
        <figure><img src="https://github.com/mohd-afeef-badri/pdmt/assets/52162083/03f0e8ae-75dd-4823-870b-4c65fab363fe" alt="Image 2"><figcaption>Text description for Image 2</figcaption></figure>
        <figure><img src="https://github.com/mohd-afeef-badri/pdmt/assets/52162083/9052499a-3993-425e-a111-2f94c4ca8798" alt="Image 3"><figcaption>Text description for Image 3</figcaption></figure>
      </div>
    </details>
  </article>

  <article class="research-item">
    <h3>Mesh Adaption</h3>
    <div class="research-feature research-feature--reverse">
      <figure><img src="/images/c8d84a25f315d4ff94a409a6ce96ddf80a568f01.png" alt="Mesh adaption"></figure>
      <p>Mesh adaptation is crucial in computational simulations as it enables the dynamic adjustment of the mesh based on evolving solution characteristics. By refining or coarsening the mesh in specific regions, mesh adaptation improves accuracy in critical areas, reducing computational costs by avoiding unnecessary refinement elsewhere. This is particularly important for capturing complex geometries, handling singularities, and optimizing element types, ensuring efficient and reliable simulations. Mesh adaptation in a nutshell helps in making simulations more robust in dynamic environments.</p>
    </div>
    <details>
      <summary>Load more</summary>
      <div class="research-gallery research-gallery--single">
        <img src="https://github.com/mohd-afeef-badri/pdmt/assets/52162083/8ae5798d-5a4f-474d-ae39-c7207085f7bd" alt="Image 1">
      </div>
    </details>
  </article>

  <article class="research-item">
    <h3>Finite Element Solver (CPU/GPU)</h3>
    <div class="research-feature">
      <figure><img src="https://user-images.githubusercontent.com/52162083/237443631-959988a3-1717-4449-b412-14cbd1582367.png" alt="Finite element solver"></figure>
      <p>A parallel FEM solver is indispensable in many computational simulations as it leverages the power of parallel processing to tackle complex and large problems more efficiently. By dividing the computational workload among multiple processors (CPU/GPU/Threads), parallel FEM solvers dramatically reduce simulation time for large-scale models. This is particularly crucial in fields such as structural mechanics, fluid dynamics, and electromagnetics, where simulations involve intricate geometries and intricate physical interactions.</p>
    </div>
    <details>
      <summary>Load more</summary>
      <div class="research-gallery research-gallery--single">
        <img src="https://user-images.githubusercontent.com/52162083/251469445-9237d686-2791-4852-b929-4d0c7e5f8df7.gif" alt="Finite element solver animation">
      </div>
    </details>
  </article>

  <article class="research-item">
    <h3>HPC for Fracture</h3>
    <div class="research-feature research-feature--reverse">
      <figure><img src="https://www.researchgate.net/profile/Giuseppe-Rastiello/publication/344688580/figure/fig6/AS:947232815730690@1602849310156/Large-scale-perforated-medium-test-domain-and-partitioned-mesh_W640.jpg" alt="Large-scale partitioned mesh"></figure>
      <p>HPC plays a vital role in advancing phase-field fracture FEM simulations. The intricate nature of fracture phenomena demands substantial computational resources for phase-field simulations due to fine meshing constrain. HPC enables the efficient handling of fine mesh refinements necessary for accurately tracking crack initiation and propagation. Not only this, HPC is also indispensable for enhancing the accuracy, efficiency, and scalability of phase-field fracture simulations, facilitating a deeper understanding of complex fracture mechanics in diverse materials.</p>
    </div>
  </article>

  <article class="research-item research-item--heading-only">
    <h3>FEM-Compliant parallel meshing-partitioning in Geophysics</h3>
  </article>
</section>

<section class="about-section research-section" aria-labelledby="past-research">
  <h2 id="past-research">Past areas of research</h2>

  <article class="research-item">
    <h3>Radiative transport in porous media</h3>
    <div class="research-gallery research-gallery--radiative">
      <img src="/images/al-full-img.png" alt="Radiative transport model">
      <img src="https://www.researchgate.net/publication/344284816/figure/fig3/AS:937040451489792@1600419261029/Heat-paths-of-conduction-compared-with-coupled-conduction-radiation_W640.jpg" alt="Heat paths of conduction and radiation">
    </div>
    <details>
      <summary>Load more</summary>
      <div class="research-gallery">
        <img src="https://www.researchgate.net/publication/344284816/figure/fig1/AS:937040006893569@1600419155709/Coupled-conduction-radiation-in-Kelvin-and-cubic-cell_W640.jpg" alt="Coupled conduction-radiation cells">
        <img src="https://www.researchgate.net/publication/344284816/figure/fig2/AS:937040245964802@1600419212628/Temperature-fields-for-coupled-condition-radiation-ceramic-samples_W640.jpg" alt="Temperature fields for ceramic samples">
        <img src="https://www.researchgate.net/publication/344284816/figure/fig5/AS:937041797861379@1600419582366/Temperature-comparison-for-SiC-ceramics-with-different-cell-structure_W640.jpg" alt="Temperature comparison for SiC ceramics">
      </div>
    </details>
  </article>

  <article class="research-item research-item--heading-only">
    <h3>Inverse problem for hypersonic flow</h3>
  </article>
</section>

</div>
