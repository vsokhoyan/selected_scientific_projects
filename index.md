# Selected Scientific and Machine Learning Projects

I am an Experimental Physicist and Machine Learning practitioner with more than 20 years of experience in quantitative scientific research. My work has ranged from designing new experimental approaches to investigate complex physical systems to developing and systematically evaluating modern Machine Learning methods in physics, medical imaging, computational biology and real-world Data Science.

A common thread throughout this work is the formulation of difficult quantitative problems in ways that allow competing mechanisms, models or explanations to be tested systematically. In recent years, I have increasingly applied this scientific methodology using modern Machine Learning and Deep Learning methods.

[Selected Scientific Research and Machine Learning](#selected-scientific-research-and-machine-learning) ·
[Machine Learning Projects](#machine-learning-projects) ·
[Experimental & Scientific Leadership](#experimental--scientific-leadership) ·
[Research Profiles](#research-profiles)

---

## Selected Scientific Research and Machine Learning

### Carl Zeiss Research Fellowship (Project Leader)

Proposed and led a new experimental approach using polarization observables to investigate possible in-medium modifications of baryon resonances in heavy nuclei at the University of Mainz. The central idea was to use beam-helicity asymmetries as a probe potentially less affected by final-state interactions than conventional unpolarized observables, allowing a cleaner investigation of changes in the underlying reaction dynamics.

**Main contributions:**

* Originated the experimental concept and developed the scientific case for the measurement
* Competitive fellowship proposal (€200k awarded by Carl-Zeiss-Stiftung)
* Independent project leadership
* Student and postdoc supervision
* Experimental campaign coordination at MAMI
* Data analysis and publication

**Outcome:** First measurements of beam-helicity asymmetries for π⁰η photoproduction on carbon, aluminum and lead, demonstrating the feasibility of this approach and opening a route for further studies of in-medium effects. First-author publications in Physics Letters B and Physical Review C.

**Links:**

* V. Sokhoyan, S. Prakhov, A. Fix et al., “Measurement of the beam-helicity asymmetry in photoproduction of π⁰η pairs on carbon, aluminum, and lead”, Phys. Lett. B 802, 135243 (2020), [Read on arXiv](https://arxiv.org/abs/1907.00232).
* V. Sokhoyan, S. Prakhov, A. Fix et al., “Study of the γp → π⁰ηp reaction with the A2 setup at MAMI”, Phys. Rev. C 97, 055212 (2018), [Read on arXiv](https://arxiv.org/abs/1803.00727).

---

### Machine Learning for Identification of Correlated Events in Nuclear Physics Experiments

Developed an event-by-event Machine Learning method for identifying time-correlated physical events in tagged-photon experiments as an alternative to conventional statistical background subtraction. The approach combines GEANT4-simulated signal events with experimentally measured background and was validated against established physics-analysis methods.

**Main contributions:**

* Reformulation of statistical background subtraction as an event-level Machine Learning classification problem
* Combination of simulated physical signal with experimentally measured background for model development
* Use of physically motivated event information for classification
* Quantitative validation against the established conventional analysis method

**Outcome:** The Machine Learning approach reproduced the results of the conventional physics analysis while enabling event-by-event identification of correlated events. Published in the Journal of Instrumentation (JINST).

**Link:**

* V. Sokhoyan, E. Mornacchi, “A new Machine Learning-based method for identification of time-correlated events at tagged photon facilities”, Journal of Instrumentation 18, P10007 (2023), [Read on arXiv](https://arxiv.org/abs/2307.04776).

---

### Proton Scalar Polarizabilities (George Washington University)

Developed and carried out an alternative experimental approach to constraining the proton scalar polarizabilities, fundamental quantities describing the response of the nucleon to electromagnetic fields, in research at George Washington University and the University of Mainz. The project used the beam asymmetry Σ₃ in Compton scattering as a complementary observable to conventional unpolarized cross-section measurements.

**Main contributions:**

* Development of the experimental and analysis approach using polarization information to constrain proton scalar polarizabilities
* Full experimental analysis and quantitative comparison with theoretical calculations
* Proposal development and successful defense at the Program Advisory Committee
* Physical interpretation and extraction of constraints on fundamental nucleon properties
* First-author publication

**Outcome:** First measurement of the beam asymmetry Σ₃ in proton Compton scattering below pion-production threshold, establishing an alternative experimental route for constraining the proton scalar polarizabilities.

**Link:**

* V. Sokhoyan, E.J. Downie, E. Mornacchi, J.A. McGovern, N. Krupina et al., “Determination of the scalar polarizabilities of the proton using beam asymmetry Σ₃ in Compton scattering”, Eur. Phys. J. A 53, 14 (2017), [Read on arXiv](https://arxiv.org/abs/1611.03769).

---

### Polarization Observables in Meson Photoproduction (PhD)

Investigation of the excitation spectrum and internal dynamics of the nucleon through double-meson photoproduction with the CBELSA/TAPS experiment at ELSA, University of Bonn. The work used polarization observables and multidimensional analysis of complex three-body final states to disentangle contributions from overlapping baryon resonances and competing sequential decay mechanisms.

**Main contributions:**

* First measurements of polarization observables in double-meson photoproduction, providing new sensitivity to the underlying reaction dynamics
* High-statistics multidimensional analysis of complex three-body final states
* Monte Carlo simulation of physical processes and detector response
* Quantitative comparison with partial-wave analyses to identify resonance contributions and decay pathways
* Multiple first-author publications

**Outcome:** The measurements provided new constraints on the nucleon excitation spectrum, contributed to the identification of previously unobserved resonance decay modes, and provided new information on the internal structure of excited baryon states. One resulting collaborative publication (Eur. Phys. J. A 51, 95 (2015)) was selected by the Particle Data Group (PDG) as the primary reference for properties of multiple baryon resonances.

**Links:**

* V. Sokhoyan, E. Gutz, H. van Pee et al., “Data on Is and Ic in γp → pπ⁰π⁰ reveal cascade decays of N(1900) via N(1520)π”, Phys. Lett. B 746, 127–131 (2015), [Read open access at PLB](https://www.sciencedirect.com/science/article/pii/S0370269315003299?via%3Dihub).
* V. Sokhoyan, E. Gutz, V. Crede, H. van Pee et al., “High-statistics study of the reaction γp → p2π⁰”, Eur. Phys. J. A 51, 95 (2015), [Read on arXiv](https://arxiv.org/abs/1507.02488).
* A. Thiel, V. Sokhoyan, E. Gutz, H. van Pee et al., “Three-body nature of N and Delta resonances from sequential decay chains”, Phys. Rev. Lett. 114, 091803 (2015), [Read on arXiv](https://arxiv.org/abs/1501.02094).

---

## Machine Learning Projects

### Medical AI

#### AMIA 2026 – Medical Image Analysis Challenge (3rd Place, June 2026)

Development of a solution for multi-class chest X-ray abnormality detection, achieving 3rd place on the private leaderboard among 200+ participants.

The project systematically investigates detector complementarity across architectures (RT-DETR, DINO), optimization strategies (ADAM, MuSGD), and cross-validation folds. The central finding is that selective evidence fusion, using independent detectors as supporting evidence rather than fusing all predictions, consistently outperforms conventional ensembling approaches.

**Main topics:**

* Object detection with transformer-based architectures (RT-DETR, DINO)
* Detector complementarity and confidence-based reranking
* Cross-fold consensus and donor selection
* VLM experiments for annotation refinement (MedGemma, Qwen)
* Distribution shift analysis and validation-to-leaderboard transfer

**Outcome:** 3rd place (private leaderboard). Comprehensive technical writeup published.

**Links:**

* [Technical writeup](https://vsokhoyan.github.io/ChestXRay_Multiclass_Detection/)

---

#### Parkinson's DaT SPECT (Nuclear Medicine Imaging) Classification Challenge *(Work in Progress)*

Development and systematic evaluation of Deep Learning methods for automated classification of dopamine transporter (DaT) SPECT scans into normal and pathological cases using a multicenter dataset collected across ten French hospitals. The project investigates custom 3D convolutional neural networks and pretrained medical vision foundation models, including MedSigLIP, using zero-shot inference, frozen feature extraction, parameter-efficient adaptation and supervised fine-tuning. The work focuses on controlled comparison of modelling approaches, transfer learning, augmentation strategies, generalization across heterogeneous imaging data, failure analysis and reproducible PyTorch-based experimentation.

The challenge is organized by the French Society of Nuclear Medicine (SFMN) in partnership with the Health Data Hub and GaelO as part of the France 2030 Health Data Challenges initiative. Final results and technical analysis will be published after completion of the project.

**Competition:** https://www.drivendata.org/competitions/311/dat-parkinsons-challenge/

---

### Computational Biology

#### CAFA-6 – Protein Function Prediction (March 2026)

Development of transformer-based methods for automatic protein function annotation using ProtT5-XL and ESM2 foundation models, including end-to-end fine-tuning and systematic benchmarking against fixed-embedding baselines.

A key methodological contribution is an information accretion-aware ensemble aggregation strategy, which uses different aggregation schemes for ontology regions depending on label specificity, addressing the challenge of rare-label signal preservation in hierarchical multi-label prediction.

**Main topics:**

* End-to-end transformer fine-tuning (ProtT5-XL 3B, ESM2)
* Fixed embedding baselines vs fine-tuned models
* Rare-label training dynamics and label-frequency analysis
* Information-accretion-aware ensemble aggregation
* GO-DAG propagation and ontology-consistent postprocessing
* Reference-guided prediction refinement

**Outcome:** Detailed methodological report published. Work in progress toward a scientific publication.

**Links:**

* [Technical writeup](https://vsokhoyan.github.io/CAFA6-ML/)

---

### Applied Machine Learning

#### Entity Resolution

Development and evaluation of Machine Learning methods for entity resolution under real-world data-quality conditions, including typographical variations, OCR distortions, missing information and inconsistent formatting.

The work combines neural similarity learning, transformer-based representations, classical Machine Learning and graph-based methods. A particular focus is placed on comparative model evaluation, error analysis, robustness under changing data conditions, and the development of reproducible Machine Learning workflows.

**Main topics:**

* Siamese neural networks for pairwise similarity learning
* Transformer-based approaches including Sentence-BERT (SBERT)
* Classical Machine Learning using engineered similarity features
* Graph-based entity resolution and clustering
* Model comparison, validation and error analysis
* Robustness to real-world data-quality and distribution effects
* Development of reproducible Machine Learning workflows for operational integration

**Outcome:** Development and validation of Machine Learning methods for integration into entity-resolution workflows.

---

## Experimental & Scientific Leadership

### Active Target TPC Development (PRES / A2 Collaboration)

Development and integration of active time-projection chamber systems for precision proton-radius and polarizability measurements at the University of Mainz.

**Main contributions:**

* Hardware coordination and interim spokesperson (PRES Collaboration on the German side at the University of Mainz)
* Monte Carlo (GEANT4) detector simulations for TPC integration with the Crystal Ball calorimeter
* Design, coordination and execution of multiple experimental campaigns

---

### Scientific Leadership within the A2 Collaboration

Scientific referee for the majority of publications of the A2 Collaboration at MAMI (2018–2023). Responsibilities included critical review of experimental analyses, assessment of systematic uncertainties and error propagation, reproducibility and consistency checks, and scientific quality assurance prior to publication.

---

# Research Profiles

* [Google Scholar – Publications & Citations](https://scholar.google.com/citations?user=7leLPVMAAAAJ&hl=de)
* [Scopus Author Profile (h-index: 26)](https://www.scopus.com/authid/detail.uri?authorId=23989342800)
* [Kaggle Competitions Profile](https://www.kaggle.com/vahesokhoyan)
