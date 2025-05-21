---
layout: home
profile_picture:
  src: /assets/img/headshot_my.jpg
  alt: website picture
---

**MS student** • [University of Chinese Academy of Sciences]\\
*Advisor*: [Dr. Ying Hu]

I am a Ms student at the University of Chinese Academy of Sciences, advised by Ying Hu. My research focuses on developing computer vision models to extract crucial 3D information from 2D medical imaging, aiming to image-guided interventions, and surgical robotics.

<center>
  <a href="mailto:pj.jiang@siat.ac.cn">Email</a> •
  <a href="https://scholar.google.com/citations?user=uiUhoLwAAAAJ&hl=zh-CN">Google Scholar</a> •
  <a href="https://github.com/pj-jiang">GitHub</a>
</center>

## Research

<style>
  .image-text-block {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .image-text-block img {
    width: 175px;
    height: 175px;
    margin-right: 20px;
  }

  .image-text-block div {
    max-width: 600px;
  }

  .image-text-block p {
    margin: 0; /* Remove default paragraph margin */
  }

  .strong-title {
    font-weight: bold;
    display: inline; /* Keep title inline */
  }

  .author-list {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }

  .author-list a {
    margin-right: 0px;
  }

  .journal-year {
    color: #666;
    margin-bottom: 0; /* Remove space after the journal */
  }

  .links {
    margin-bottom: 10px; /* Remove space before the links */
  }
</style>


### Differentiable Rendering + Minimally Invasive Surgery

<div class="image-text-block">
  <img src="/assets/img/diffpose.gif" alt="pelvis.html">
  <div>
    <p><strong class="strong-title"><a href="https://arxiv.org/abs/2312.06358">Intraoperative 2D/3D Image Registration via Differentiable X-ray Rendering</a></strong></p>
    <p class="author-list">
      <b>Vivek Gopalakrishnan</b>,
      <a href="https://www.neeldey.com/">Neel Dey</a>,
      <a href="https://people.csail.mit.edu/polina">Polina Golland</a>
    </p>
    <p class="journal-year"><em>CVPR</em>, 2024</p>
    <div class="links">
      <a href="https://vivekg.dev/DiffPose">project page</a> / 
      <a href="https://github.com/eigenvivek/DiffPose">code</a> / 
      <a href="https://vivekg.dev/DiffPose/docs">docs</a> / 
      <a href="https://arxiv.org/abs/2312.06358">paper</a>
    </div>
    <p>We use X-ray renderering to develop <code>DiffPose</code>, a self-supervised framework for differentiable 2D/3D image registration that achieves sub-millimeter registration accuracy.</p>
  </div>
</div>

<div class="image-text-block">
  <img src="/assets/img/diffdrr.gif" alt="woowoowooooo">
  <div>
    <p><strong class="strong-title"><a href="https://arxiv.org/abs/2208.12737">Fast Auto-Differentiable Digitally Reconstructed Radiographs for Solving Inverse Problems in Intraoperative Imaging</a></strong></p>
    <p class="author-list">
      <b>Vivek Gopalakrishnan</b>,
      <a href="https://people.csail.mit.edu/polina">Polina Golland</a>
    </p>
    <p class="journal-year"><em>MICCAI Clinical Image-based Procedures Workshop</em>, 2022</p>
    <div class="links">
      <a href="https://github.com/eigenvivek/DiffDRR">code</a> / 
      <a href="https://vivekg.dev/DiffDRR">docs</a> / 
      <a href="https://arxiv.org/abs/2208.12737">paper</a>
    </div>
    <p>We present <code>DiffDRR</code>, a differentiable X-ray renderer that can be used to solve inverse problems in X-ray imaging with deep learning (e.g., registration or reconstruction).</p>
  </div>
</div>

<div class="image-text-block">
  <img src="/assets/img/xellar.gif" alt="zstacks">
  <div>
    <p><strong class="strong-title"><a href="https://github.com/eigenvivek/zlearn">Learning Interpretable Single-Cell Morphological Profiles from 3D Cell Painting Images</a></strong></p>
    <p class="author-list">
      <b>Vivek Gopalakrishnan</b>,
      <a href="https://www.linkedin.com/in/jingzhe-ma">Jingzhe Ma</a>,
      <a href="https://scholar.google.com/citations?user=0DsebPAAAAAJ">Zhiyong Xie</a>
    </p>
    <p class="journal-year"><em>CVPRW</em>, 2024</p>
    <p class="journal-year"><em>Society of Biomolecular Imaging and Informatics</em>, 2023 <b>(President's Innovation Award)</b></p>
    <div class="links">
      <a href="https://github.com/eigenvivek/zlearn">project page</a> /
      <a href="https://arxiv.org/abs/2403.17615">paper</a>
    </div>
    <p>Supervised deep learning models are used ubiquitously throughout image-based drug discovery. We discover a mechanism by which these models cheat and propose an interpretability metric to quantify the level of confounding.</p>
  </div>
</div>



<!-- ### Survival Analysis -->

<!-- My interests lie in the following areas in medicine and machine learning:

- **Neural fields** → spatiotemporal vessel reconstruction in neurosurgery
- **Differentiable rendering** → fast registration for intraoperative image guidance
- **Statistical graph theory** → biomarker discovery in network neuroscience
- **Matrix analysis** → no biomedical applications yet, but I do love a good eigenvalue property!

Before starting my PhD, I completed my BS/MS in Biomedical Engineering at Johns Hopkins University, where I worked with Dr. Joshua Vogelstein and Dr. Carey Priebe in the NeuroData Lab. My work is supported by a Neuroimaging Training Program Grant from the National Institute of Biomedical Imaging and Bioengineering. -->
