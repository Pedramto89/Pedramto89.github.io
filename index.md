---
layout: default
title: Home
description: "Pedram Torabian - Bioinformatics & Machine Learning Researcher"
head:
  - |
    <link rel="icon" type="image/png" sizes="32x32" href="/assets/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/assets/favicon-16x16.png">
    <link rel="shortcut icon" href="/assets/favicon.ico">
    <style>
      /* Timeline container */
      .timeline {
        position: relative;
        max-width: 800px;
        margin: 40px auto;
        padding: 20px 0;
      }

      /* The vertical line */
      .timeline::after {
        content: '';
        position: absolute;
        width: 6px;
        background-color: #ddd;
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -3px;
      }

      /* Container for each timeline item */
      .timeline-item {
        padding: 20px 30px;
        position: relative;
        background-color: inherit;
        width: 50%;
      }

      /* Positioning left and right */
      .timeline-item.left {
        left: 0;
      }

      .timeline-item.right {
        left: 50%;
      }

      /* Content box */
      .timeline-content {
        padding: 20px;
        background-color: #f9f9f9;
        position: relative;
        border-radius: 6px;
      }

      /* Circles on the timeline */
      .timeline-item::after {
        content: '';
        position: absolute;
        width: 20px;
        height: 20px;
        right: -10px;
        background-color: white;
        border: 4px solid #FF9F55;
        top: 30px;
        border-radius: 50%;
        z-index: 1;
      }

      .timeline-item.right::after {
        left: -10px;
      }

      /* Responsive adjustments */
      @media screen and (max-width: 600px) {
        .timeline::after {
          left: 31px;
        }

        .timeline-item {
          width: 100%;
          padding-left: 70px;
          padding-right: 25px;
        }

        .timeline-item.left, .timeline-item.right {
          left: 0;
        }

        .timeline-item::after {
          left: 15px;
        }
      }
    </style>
---
# Table of Contents
- [About Me](#about-me)
- [My Journey](#my-journey)
- [Technical Skills](#technical-skills)
- [Education](#education)
- [Professional Experience](#professional-experience)
- [Awards & Achievements](#awards-achievements)
- [Featured Projects](#featured-projects)
- [GitHub Stats](#github-stats)
- [Get in Touch](#get-in-touch)

## 👋 Welcome to My GitHub Pages!

### About Me

Hello! I am **Pedram Torabian**, a passionate researcher and data scientist with a strong background in bioinformatics, genomics, and machine learning. I leverage my expertise in R, Python, bash and high-performance computing to analyze complex biological data. My work focuses on spatial transcriptomics (ST), single-cell RNA sequencing (scRNA-seq), and deploying machine learning techniques to uncover insights in cancer research and other genetic disorders.

## 🌱 My Journey
My scientific journey began as a wet lab researcher, where I earned my **Master of Human Genetics** with expertise in genetic engineering, population genetics, and biostatistics. This foundation in experimental biology proved invaluable as I advanced to the **Medical Science Program-Cancer Biology Specialization** at the **University of Calgary**, where I pioneered research in pancreatic ductal adenocarcinoma (PDAC) tumor microenvironment.

At the **Arnie Charbonneau Cancer Institute**, We were among the first researchers to implement spatial transcriptomics (Nature Method of the Year, 2020) in PDAC studies using Visium 10X Genomics technology. This groundbreaking work required mastery of both experimental techniques and advanced computational methods, including single-cell RNA-seq analysis, bulk RNA-seq, protein-protein interaction mapping, and computational functional assessment through ssGSEA.

My unique strength lies in bridging wet and dry lab expertise, allowing me to approach biological problems with comprehensive insight. I have successfully applied both supervised and unsupervised machine learning algorithms to analyze complex biological datasets. Through leading multiple experimental and computational projects, I have developed strong leadership skills that complement my technical expertise. This dual perspective - combining hands-on laboratory experience with computational proficiency - enables me to drive innovative solutions in modern biological research.

## 📅 Professional Timeline

<div class="timeline">

  <div class="timeline-item left">
    <div class="timeline-content">
      <h3>Master of Human Genetics</h3>
      <h4>Iran University</h4>
      <p>September 2013 – February 2016</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="timeline-content">
      <h3>Master of Medical Science</h3>
      <h4>University of Calgary</h4>
      <p>July 2020 – October 2024</p>
    </div>
  </div>

  <div class="timeline-item left">
    <div class="timeline-content">
      <h3>Razavi Hospital</h3>
      <h4>Research Assistant</h4>
      <p>November 2016 – October 2019</p>
    </div>
  </div>

  <div class="timeline-item right">
    <div class="timeline-content">
      <h3>Cancer Institute</h3>
      <h4>Research Assistant</h4>
      <p>July 2020 – Present</p>
    </div>
  </div>

  <div class="timeline-item left">
    <div class="timeline-content">
      <h3>Amii</h3>
      <h4>Content Development Support - Educational Product</h4>
      <p>April 2024 – June 2024</p>
    </div>
  </div>

</div>

## 💻 Skills Overview

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🛠️ Technical Skills

- **Programming Languages:** R, Python, Bash, Git
- **Data Analysis:** Spatial Transcriptomics, Single-cell RNA-seq, Bulk RNA-seq
- **Machine Learning:** Supervised & Unsupervised Techniques, XGBoost
- **Statistical Analysis:** Kruskal-Wallis Test, Mann-Whitney U Test, ANOVA
- **Bioinformatics Tools:** Seurat, CellPhoneDB, CellChat, DESeq2, Monocle3, ssGSEA, GSVA
- **High-Performance Computing:** Slurm for managing compute jobs on HPC clusters

## 🎓 Education

- **Master of Medical Science**
  - University of Calgary
  - July 2020 – October 2024
  - GPA: 3.7/4.0
  - **Key Courses:** Intro Bioinformatics Resources, Advanced Bioinformatics, Tumor Microenvironment Dynamics, Intro Biostat Methods, Applied Genomics, Tumor Immunology and Therapy

- **Master of Human Genetics**
  - Iran University
  - September 2013 – February 2016
  - GPA: 3.5/4.0
  - **Key Courses:** Genetics Engineering, Advanced Topics in Human Genetics, Population Genetics

## 💼 Professional Experience

- **Content Development Support - Educational Product**
  - Alberta Machine Intelligence Institute (Amii)
  - April 2024 – June 2024
  - Created educational content for the "Using AI in Biology & Life Sciences" MOOC, enhancing the learning experience for students and professionals.

- **Research Assistant**
  - Arnie Charbonneau Cancer Institute, University of Calgary
  - July 2020 – Present
  - *Responsibilities:*
    - Machine Learning Classifier Development
    - Statistical Analysis
    - Single-Cell Analysis
    - Data Integration
    - Bulk RNA-seq Deconvolution

- **Research Assistant**
  - Razavi Hospital, Iran
  - November 2016 – October 2019
  - *Responsibilities:*
    - Led genetic projects
    - Authored comprehensive reviews
    - Investigated medical conditions

- **Molecular Biologist and Stem Cell Intern**
  - November 2011 – May 2012
  - *Responsibilities:*
    - Mastered laboratory techniques in molecular biology and stem cell biology

## 🏆 Awards & Achievements

- **Griffith University Postgraduate Research Scholarship (GUPRS)**
  - Awarded $28,092 AUD – December 2019

- **Top 2% Ranking**
  - Among participants in the national master's level entrance exam – September 2013

- **Top 1% Ranking**
  - Nationwide in the Iran national entrance exam – September 2008

## 📂 Featured Projects

<details>
<summary><strong>Machine Learning Classifier for Spatial Transcriptomics</strong></summary>

- Technologies used: R, Python, XGBoost, Seurat
- Key achievements:
  - Developed a robust machine learning classifier in R and Python
  - Accurately predicted cell identities based on gene expression profiles
  - Integrated Seurat for comprehensive data analysis
</details>

<details>
<summary><strong>Single-Cell RNA-seq Data Integration</strong></summary>

- Technologies used: R, Seurat
- Key achievements:
  - Led analysis of 30 GB of single-cell RNA-seq data from ten samples
  - Identified cell type-specific marker genes
  - Created comprehensive marker gene list for diverse cellular populations
</details>

<details>
<summary><strong>Computational Deconvolution of Bulk RNA-seq Data</strong></summary>

- Technologies used: R, Deconvolution algorithms
- Key achievements:
  - Applied four computational deconvolution methods to TCGA data
  - Uncovered gene expression variations related to stromal levels
  - Provided insights into cancer progression mechanisms
</details>

## 📈 GitHub Stats

![Pedram's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Pedramto89&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Pedramto89&layout=compact&theme=radical)

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Pedramto89.Pedramto89)

## 📫 Get in Touch

I'm always open to discussing innovative research, collaborations, or new opportunities. Feel free to reach out via:

- [LinkedIn](https://www.linkedin.com/in/pedram-torabian)
- [Email](mailto:pedram.torabian@ucalgary.ca)
- [GitHub](https://github.com/Pedramto89)
