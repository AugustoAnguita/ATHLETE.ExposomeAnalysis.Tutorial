# **Exposome research analytics: An Hands-on Data Analysis Tutorial."**  

<img src="figures/2_ATHLETE_logo_subtitle_color.png" alt="ISGlobal logo" width="350"/>  
<img src="figures/exposoma.png" alt="ISGlobal 

**Alan Domínguez**, Predoctoral Researcher at the Barcelona Institute for Global Health (ISGlobal).  

**Augusto Anguita-Ruiz**, Junior Leader Researcher at the Barcelona Institute for Global Health (ISGlobal).

**Juan Ramón Gonzalez**, Associate Professor at the Barcelona Institute for Global Health (ISGlobal).

**Xavier Basagaña**, Associate Professor at the Barcelona Institute for Global Health (ISGlobal).

The exposome, described as "the totality of human environmental exposures from conception onwards," recognizes that individuals are simultaneously exposed to multiple different environmental factors, adopting a holistic approach for the discovery of etiological factors of disease. The main advantage of the exposome approach over more traditional ones—“one exposure, one disease or health outcome”—is that it provides a framework for the study of multiple environmental risks (urban, chemical, lifestyle, social, etc...) and their combined effects on health.

The **objective** of this session is to offer an **introduction to the different statistical approaches** necessary to address the main questions of **exposome research**. Every exposome analysis should consist on two main tasks (descriptive analysis, and association analysis):

**1. Descriptive Analysis:**  
In the first part of the session, the concept of descriptive analysis in exposomics will be addressed, through which the first conclusions about the data are drawn. Among other objectives, descriptive analysis aims to identify possible outliers, confounding factors, or variables that require transformations prior to analysis. At the same time, descriptive analysis allows a preliminary comparison of the experimental groups under study, the examination of the existing patterns of correlation among exposure factors, and the identification of grouping phenomena in the data (both at the level of individuals and of features). All of these are essential steps to choose the most appropriate subsequent statistical approach.

Some of the contents we will review in this section:  
* **Visualization of the distribution and concentration of exposome variables.**  
* **Correlation between exposures.**  
* **Principal Component Analysis (PCA) applied to exposome variables.**

**2. Association Analysis:**  
Association analysis aims to identify possible environmental exposure factors associated with different health parameters. In this section of the session, different holistic analytical approaches focused on the study of the effects of multiple exposure factors and their mixtures on health will be presented. This includes mainly models such as ExWAS (Exposome-Wide Association Analysis), or others for the study of interactions or non-linearity phenomena (e.g., Bayesian Kernel Machine Regression). An introduction will also be presented to clustering methods or exposure mixture methods (e.g., Weighted Quantile Sum Regression). During their study, concepts of great importance in exposome analysis will be introduced, such as feature selection or multiple testing correction.

Some of the contents we will review in this section:  

* **Exposure Wide Association Analysis (ExWas)**  
* **Methods for variable selection (Stepwise, Elastic net, DSA)**  
* **Weighted quantile sum regression**  
* **Clustering**  
* **Bayesian Kernel Machine Regression**

For this practical tutorial, we will use data from the HELIX exposome study. The HELIX study is a collaborative project between six longitudinal, population-based birth cohort studies from six European countries (France, Greece, Lithuania, Norway, Spain and the UK).

<img src=‘figures/HELIX.png’ alt=‘HELIX logo’ width=‘500’/> 

**Note:** The data provided in this introductory course were simulated from the HELIX sub-cohort data. Details of the HELIX project and the origin of the data collected can be found in the following publication: [BMJ Open - HELIX](https://bmjopen.bmj.com/content/8/9/e021311) and on the [project website](https://www.projecthelix.eu/es).

# Repository Guide

The repository contains the following documents:

**1.- exposome_tutorial.ipynb:** It contains the notebook for the practical tutorial with the code needed to perform the data analysis in exposome projects.

**data:** This folder contains the **codebook** and the **datasets** that will be used during the session.

* The **exposoma data (n = 1301)** that we will use are contained in a **Rdata** file, which includes the following files:
  1. `phenotype` (results).
  2. `exposome` (exposome).
  3. `covariates` (covariates).
  4. `codebook`.
