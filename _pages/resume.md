---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /cv
---

My resume can be downloaded [here](http://smphd.com/files/resume_ECV.pdf).

# Experience

## Graduate Researcher -- May 2018 to Present

### *McGill University, Montréal, Canada*

- **Characterize** temperature and pressure effects on the interfacial tension and energy of interfaces in sII gas hydrates. Generated ~10 TB of simulation data across all projects; largest systems ~38,500 atoms; production runs spanning hundreds of nanoseconds and hundreds of core-years on DRAC clusters.
- **Utilize** machine learning to identify trends and patterns in large datasets, classify structures, and recognize clustering.
- **Model** structures and local organizations present near and far from gas hydrate interfaces.
- **Develop** processing pipelines using NumPy, pandas, NumExpr, multiprocessing, and scikit-learn on HPC clusters.
- **Implement** computational, analytical, and theoretical modeling of crystalline properties and interfacial processes and phenomena of gas hydrates using high performance computing clusters.
- **Maintain** `lammpslib` (v1.0.6), a Python package for the Materials Modeling Research Group, installable via pip from GitHub. Contains 5 submodules (~20 Python files): bootstrapping (statistical resampling, hydrogen bond analysis), interfacial (simulation box generation), performance (thermodynamic analysis, convergence testing, transport properties, RMSD, radius of gyration, hydrogen bond lifetime/probability/visualization), scriptediting (LAMMPS input script templating and generation), and scrub_output (HPC log parsing).

## Scientific Systems Administrator -- January 2021 to Present

### *McGill University, Montréal, Canada*

- **Manage** compute infrastructure of the Materials Modeling Research Group (Olympus cluster): 1 login node, 2 compute nodes (AMD Ryzen Threadripper PRO 3995WX 64c/128t, 512 GB RAM, NVIDIA RTX 3090 Ti GPU).
- **Install**, **configure**, and **maintain**:
  - Debian login and compute nodes, including all memory, CPU, GPU, power supply, and storage operation, and part replacement as required.
  - Slurm Workload Manager for job scheduling, resource management, and node failure tolerance.
  - CERN Virtual Machine File system on all nodes for software and data distribution and management, including configuring alien cache and proxy servers where appropriate.
  - MATLAB, COMSOL, COMSOL License Manager implementations, custom software installations for benchmarking.
  - LDAP user authentication for centralized services across all cluster related devices and consistent user and group permissions from hot data to cold backup.
  - DHCP and DNS servers to automatically assign and maintain consistent lists of nodes, IP addresses, internal and external hosts, and sites.
  - Network hardware on server rack and on desk for integration, node communication, and data management and transfer.
  - 3-2-1 backup policy for all research data on a pre-defined schedule, with cron-based health checks and email alerts for backup verification, node failure, and disk space monitoring.
  - Gitea Docker implementation offsite and remotely accessed for repository version control.
- **Integrate** and **communicate** with university IT staff and institutional policies regarding hardware, external access, and internal networking address assignment and service management.
- **Make** recommendations to research supervisor on hardware and software upgrades taking into account cost, procurement policies, and installation and configuration time.
- **Provide** technical support for all researchers and collaborators using the computational system.
- **Troubleshoot** all failed jobs, hardware issues, performance bottlenecks, and software conflicts at all times for all users cluster-wide.
- **Train** lab members in data policies, cluster usage, and interactions with local and Digital Research Alliance of Canada clusters.

## Lab Manager -- January 2021 to Present

### *McGill University, Montréal, Canada*

- **Manage** all lab software licenses and cloud computing credit grants on Digital Research Alliance of Canada resources, including VASP license user management (onboarding/offboarding), MATLAB, and COMSOL.
- **Guide** lab members on compiling VASP using EasyBuild recipes and custom CMake/Makefile configurations on DRAC and local clusters.
- **Oversee** and **coordinate** all hardware (desktops, components) and software procurement processes, including adherence to institutional rules and regulations.
- **Maintain** records for funding agencies and institutional compliance.
- **Assist** principal investigators with grant proposals by preparing computational time records, financial budgets, specific and detailed core-year justifications, and collecting and combining project information from lab members.
- **Principal author** of Digital Research Alliance of Canada (DRAC) resource allocation competition grants for both supervisors (2021--2028), securing cloud and cluster compute resources estimated at ~$500k CAD in total allocated value.
- **Consulted** on NSERC Discovery Grant application, advising on digital twin framing and in-house hardware utilization strategy to justify procurement of dedicated compute infrastructure.
- **Prepare** expense reports for seminars and lab activities, including receiving and processing invoices to facilitate payment of vendors in a timely manner.
- **Schedule** all weekly meetings between principal investigator and researchers.
- **Schedule** all weekly group seminars, producing attendance lists, and noting all required informations for funding agencies.

## Graduate Teaching Assistant -- September 2018 to April 2026

### *McGill University, Montréal, Canada*

- Grade assignments and exams, lead tutorial sessions, deliver ad-hoc lectures, supervise lab sessions, hold office hours, and invigilate exams for courses in the Chemical Engineering Department at the undergraduate and graduate level.
- Provide tutorial and office-hour support in both English and French upon student request.
- 13 total TA assignments across 6 distinct courses, with some courses taught multiple semesters.
- Undergraduate:
  - CHEE 315: Fluid Mechanics (Fall 2018, Fall 2019, Fall 2021)
  - CHEE 351: Heat and Mass Transfer (Winter 2019, Winter 2020)
  - CHEE 400: Principles of Sustainable Energy Conversion (Fall 2022, Fall 2023, Fall 2024)
  - CHEE 440: Process Modelling (Winter 2022, Winter 2023, Winter 2024) -- lectured and tutored on PDE derivation, Laplace transforms, series solutions, dimensional analysis
- Graduate:
  - CHEE 662: Computational Methods (Summer 2025) -- FEM, finite differences, spectral methods, bifurcation theory, continuation methods, all in MATLAB
  - CHEE 611: Heat and Mass Transfer (Winter 2026)

# Education

## Doctor of Philosophy (Ph.D.), Chemical Engineering -- January 2021 to April 2026

### *McGill University, Montréal, Canada*

- **Thesis:** Multiscale Characterization of Gas Hydrates: Interfacial and Structural Aspects
- Employing high performance molecular dynamics for interfacial systems in gas hydrate engineering applications, and density functional theory for solid crystalline gas hydrate systems.
- Doctoral Research Scholarship: Fonds de recherche du Québec – Nature et technologies
- McGill Engineering Doctoral Award
- Relevant Coursework: Heat and Mass Transfer (CHEE 611), Foundations of Fluid Mechanics (CHEE 631, incl. CFD with COMSOL), Process Dynamics and Control (CHEE 672, incl. Simulink)

## Master of Engineering (M.Eng.), Chemical Engineering -- May 2018 to April 2020

### *McGill University, Montréal, Canada*

- **Thesis:** Thermal Properties of Gas Hydrates Using Density Functional Theory
- Predicted thermal properties of sI gas hydrates from first principles using Density Functional Theory.
- McGill Engineering Undergraduate Student Master's Award
- Relevant Coursework: Graduate Thermodynamics (CHEE 621), Graduate Computational Methods (CHEE 662), Quantum Materials (MIME 658, Mining and Materials Engineering)

## Ph.D. Program Milestones

- CHEE 795: Ph.D. Thesis Proposal (completed)
- CHEE 796: Ph.D. Proposal Defence (completed)
- CHEE 797: Ph.D. Seminar (completed)
- CHEE 687: Research Skills & Ethics (completed during M.Eng.)
- CHEE 681: Laboratory Safety 1 (completed during M.Eng.)
- CHEE 682: Laboratory Safety 2 (completed during M.Eng.)
- Ph.D. Final Seminar (completed)
- Ph.D. Thesis Defence (completed)

## Bachelor of Engineering (B.Eng.), Chemical Engineering -- September 2014 to April 2018

### *McGill University, Montréal, Canada*

# Collaborations

## Universidad Nacional Autónoma de México (UNAM)

- Ongoing research collaboration with Prof. Edtson Emilio Herrera-Valencia, Facultad de Estudios Superiores Zaragoza.
- Provided Spanish-language technical consultation on molecular dynamics during joint virtual conferences and supervisor presentations.
- Multiple in-person visits by Prof. Herrera-Valencia to McGill.

# Service & Leadership

## Undergraduate Research Supervision -- 2019 to 2025

### *McGill University, Montréal, Canada*

- Supervised 6 undergraduate summer research students over multiple years, guiding them on DFT simulation setup, geometric analysis, and cluster usage.
- Two of those students are now pursuing doctoral degrees.
- Co-authored conference paper with undergraduate student.

## Ph.D. Proposal Defence Committee -- Student Member

### *McGill University, Montréal, Canada*

- Served as student member on a labmate's CHEE 796 Ph.D. Proposal Defence examination committee.

## Workshop Facilitator -- 2022

### *McGill University, Montréal, Canada*

- Designed and delivered hands-on workshop for MMRG group members on connecting to the Olympus cluster: SSH key pair generation, SSH configuration, and remote development with VS Code over SSH.

## Local Contact, McGill-ETH Zurich Synergia Symposium -- August 2022

### *McGill University, Montréal, Canada*

- Served as local contact and logistics coordinator for a one-day international research symposium between McGill (Prof. Alejandro Rey) and ETH Zurich (Prof. Raffaele Mezzenga) on biological cholesteric phases under confinement.
- Managed venue setup, reception dinner coordination, and on-site support for in-person and virtual participants.

## Chemical Engineering Graduate Students Society (ChEGSS) Councilor -- 2018 to 2022

### *McGill University, Montréal, Canada*

- Served as general councilor for 3 academic years (2018/19, 2019/20, 2021/22), assisting with departmental events and graduate student activities.

## Professional Development

- Mathematics of Multiscale and Multiphysics Phenomena in Materials Science -- June 16 to June 21, 2024
  - Banff International Research Station for Mathematical Innovation and Discovery, Banff, Canada
  - [Homepage](https://www.birs.ca/events/2024/5-day-workshops/24w5159)
- Computational Materials North Workshop -- August 03 to August 04, 2023
  - Queen's University, Kingston, Canada
  - [Homepage](https://sites.google.com/view/cmnworkshop/home)
- Moving ions with VASP (Vienna Ab initio Simulation Package) for the advanced user -- November 13 to November 17, 2023
  - Virtual
- HPC Python -- June 2022
  - Virtual via Compute Ontario Summer School
- DAT112: Neural Network Programming -- April 2022
  - Virtual via SciNet HPC Consortium
  - Six-week course: neural network concepts, theory, and techniques using Python 3.9 and Keras framework
- HPC133: Introduction to GPU Programming -- April 2022
  - Virtual via SciNet HPC Consortium
  - Overview of GPUs in supercomputing, GPU programming frameworks, accelerating scientific computing with GPUs (Python/C++)
- SCMP271: Advanced Linux Command Line -- February 2022
  - Virtual via SciNet HPC Consortium
  - Advanced Linux commands for productivity on HPC systems
- Advanced materials for energy storage and conversion summer school -- July 05 to July 09, 2021
  - Virtual via Université de Bordeaux
  - Topics: Thermal energy storage, PEM fuel cells and electrolysis, photocatalysis for solar fuels, photovoltaic systems, supercapacitors, battery technologies, hydrogen storage and metal hydrides, battery recycling, industrial energy systems
  - Capstone group project with short presentation
  - Prize: Quebec Centre for Advanced Materials Participation Grant
- Applied Data Science with Python Specialization -- Fall 2020
  - University of Michigan via Coursera
  - [Introduction to Data Science in Python](https://www.coursera.org/verify/8CQRKUWVQAJY), [Applied Plotting, Charting & Data Representation in Python](https://www.coursera.org/verify/ZK77RD83EUFK), [Applied Machine Learning in Python](https://www.coursera.org/verify/5KCGZEYEAQUX), [Applied Text Mining in Python](https://www.coursera.org/verify/8KMZ62PYNSQG)
- Python for Everybody Specialization -- Fall 2020
  - University of Michigan via Coursera
  - [Programming for Everybody](https://www.coursera.org/verify/AVMGG4DAN5SQ), [Python Data Structures](https://www.coursera.org/verify/SUZRSZKMRQE8), [Using Python to Access Web Data](https://www.coursera.org/verify/WWP9KGQCCVYW), [Using Databases with Python](https://www.coursera.org/account/accomplishments/verify/9XAQNGSX2B68), [Capstone: Retrieving, Processing, and Visualizing Data with Python](https://www.coursera.org/verify/VN6L5R5FDA7W)

# Technical Skills

## Languages

English (**Native**), French (**Native**), Spanish (**Native**)

## Tools

MATLAB, Simulink, Python, Bash, SQL, Excel, PowerPoint, LaTeX, COMSOL, LabVIEW.

## Operating Systems

NixOS, Nix (nix-shell for reproducible dev environments), Home Manager, Debian, Ubuntu, Microsoft Windows, MacOS.

## Data Science

NumPy, NumExpr, Multiprocessing Package, Pandas, Scikit-learn, Matplotlib, SciPy, Refactoring for Parallel Execution, Statistical Analysis, Data Cleaning, Error Propagation Analysis.

## Numerical & Computational Methods

Galerkin Finite Elements, Finite Differences, Collocation, Spectral Methods, Method of Weighted Residuals, Gaussian Quadrature, Newton-Raphson Iteration, Implicit/Explicit Time Integration, Predictor-Corrector Methods, Bifurcation Theory (Turning Points, Hopf Bifurcations), Arc-Length Continuation (Keller's Method), Mesh Refinement (Adaptive/Moving), Petrov-Galerkin Upwinding, Isoparametric Mapping, Lagrange Interpolation, PID Control (LabVIEW).

## Analytical Methods

PDE Derivation from Conservation Laws, Laplace Transforms, Series Solutions, Dimensional Analysis and Scaling, Classification of PDEs by Characteristics.

## Artificial Intelligence

Classifiers, Regression, Support Vector Machine, Text Mining, Neural Network Programming.

## Materials Modeling

Large Atomic/Molecular Modeling Software Package (LAMMPS), Vienna Ab Initio Simulation Package (VASP), Phonopy, MDAnalysis, OVITO, VMD, Moltemplate, Packmol, LCAO and Plane-Wave Basis Set Methods, Elastic Constant and Mechanical Property Calculation (Young's Modulus, Bulk Modulus, Shear Modulus via DFT), Phonon-Based Thermal Property Calculation (Heat Capacity, Thermal Expansion, Gruneisen Parameter), Kirkwood-Buff / Pressure Tensor Method (Interfacial Tension), Radial Distribution Functions, Density Profiles, Order Parameter Calculation, Equilibrium MD (NPT/NVT), Exploratory Non-Equilibrium MD (Electric Field, Electrocrystallization), Jupyter Notebooks, MATLAB Live Scripts (.mlx).

## High Performance Computing

Installation/Maintenance of Slurm Scheduler, CERN Virtual Machine File System, Ethernet and InfiniBand Network Configuration, CPU/GPU Performance Tuning, Cloud and Edge Compute, Parallel Workflow Optimization, Source Compilation and MPI Library Benchmarking (OpenMPI, Intel MPI), GPU Support Testing, EasyBuild, CMake/Makefile Configuration.

## Containerization

Docker, Docker Compose, Docker Compose Networking, Self-Hosted Home Server (containerized services, private DNS routing, custom domain and email).

## Version Control

Git (branching, merging, conflict resolution), Self-Hosted Gitea.

## Computer Networking

Nginx Proxy Manager, HTTPS/SSL Provisioning, Traffic Routing, DHCP Server, DNS Server, Custom Domains, Mail Routing, LDAP User Authentication.

## Force Fields & Interatomic Potentials

TIP4P/Ice, OPLS-AA, EPM2, TraPPE, Zhang CO2 Potential.

## Technical Writing

Technical Literature Review and Synthesis, Grant Writing (Digital Research Alliance of Canada Resource Allocation Competitions -- principal author; NSERC Discovery Grant -- consultant/contributor), Review Paper Authorship.

# Awards & Achievements

**Training Mobility Grant/Award - Quebec Center for Advanced Materials (QCAM):** October 2025

**Doctoral Research Scholarship - Fonds de recherche du Québec – Nature et technologies:** June 2022 to December 2025

**Graduate Research Enhanced and Travel Award:** October 2025

**Canadian Association for Computational Science and Engineering Travel Award for the 16th World Congress on Computational Mechanics:** July 2024

**Graduate Research Enhancement and Travel Award:** July 2024

**Presentation Excellence Award - Concordia University Center for Research in Molecular Modeling Research Symposium:** May 2024

**Prize for Best Use of Language (French) - Oral Session - 8th Advanced Materials Annual Meeting of the Quebec Center for Advanced Materials:** May 2024

**McGill Engineering Doctoral Award:** January 2021 to December 2023

**Graduate Research Enhancement and Travel Award:** June 2023

**Graduate Research Enhancement and Travel Award:** December 2022

**McGill Engineering Undergraduate Student Master's Award:** May 2018 to April 2020

**Outstanding Presentation Award (Masters) - Chemical Engineering Research Day:** November 2019

**Tomlinson Engagement Award for Mentoring: CHEE 314 - Fluid Mechanics:** September 2017

**James McGill Entrance Scholarship:** September 2014 to April 2015

**LeClaire Manufacturing Achievement Scholarship:** July 2014

# Publications

- **Mathews, S.**; Zhu, X.; Guerra, A.; Servio, P.; Rey, A. Atomistic Modeling of Methane and Carbon Dioxide Structure I Gas Hydrates under Pressure: Guest Effects and Properties. Journal of Chemical Theory and Computation 2026, 22, 6, 3114–3124. [10.1021/acs.jctc.5c01868](https://doi.org/10.1021/acs.jctc.5c01868).
- Guerra, A.; Wang, Z.; **Mathews, S.**; Rey, A. D.; France, K. D. Periodic Feature Characterization in Nanostructured Surfaces and Emulsions. Langmuir 2025, 41, 37, 25230–25241. [10.1021/acs.langmuir.5c02320](https://doi.org/10.1021/acs.langmuir.5c02320).
- **Mathews, S.**; Zhu, X.; Guerra, A.; Servio, P.; Rey, A. Geometric Characterizations of Non-Uniform Structure I Methane Hydrate Behaviors Under Pressure. Crystals 2025, 15 (6), 518. [10.3390/cryst15060518](https://doi.org/10.3390/cryst15060518).
- **Mathews, S.**; Servio, P.; Rey, A. Multiscale Interfacial Structure and Organization of sII Gas Hydrate Interfaces Using Molecular Dynamics. Nanomaterials 2025, 15 (6), 464. [10.3390/nano15060464](https://doi.org/10.3390/nano15060464).
- **Mathews, S.**; Xu, Z.; Servio, P.; Rey, A. Geometric Modeling of Gas Hydrate Structural Properties and Guest-Host Interactions. In Proceedings of the 16th World Congress on Computational Mechanics and 4th Pan American Congress on Computational Mechanics; Scipedia: Vancouver, Canada, 2024. [10.23967/wccm.2024.097](https://doi.org/10.23967/wccm.2024.097)
- **Mathews, S.**; Guerra, A.; Servio, P.; Rey, A. Molecular Dynamics Characterization of the Interfacial Structure and Forces of the Methane-Ethane sII Gas Hydrate Interface. Colloid and Interface Science Communications 2024, 62, 100800. [10.1016/j.colcom.2024.100800](https://doi.org/10.1016/j.colcom.2024.100800).
- Guerra, A.; **Mathews, S.**; Su, J. T.; Marić, M.; Servio, P.; Rey, A. D. Molecular Dynamics Predictions of Transport Properties for Carbon Dioxide Hydrates under Pre-Nucleation Conditions Using TIP4P/Ice Water and EPM2, TraPPE, and Zhang Carbon Dioxide Potentials. Journal of Molecular Liquids 2023, 379, 121674. [10.1016/j.molliq.2023.121674](https://doi.org/10.1016/j.molliq.2023.121674).
- Guerra, A.; **Mathews, S.**; Marić, M.; Servio, P.; Rey, A. D. All-Atom Molecular Dynamics of Pure Water–Methane Gas Hydrate Systems under Pre-Nucleation Conditions: A Direct Comparison between Experiments and Simulations of Transport Properties for the Tip4p/Ice Water Model. Molecules 2022, 27 (15), 5019. [10.3390/molecules27155019](https://doi.org/10.3390/molecules27155019).
- **Mathews, S.**; Daghash, S.; Rey, A.; Servio, P. Recent Advances in Density Functional Theory and Molecular Dynamics Simulation of Mechanical, Interfacial, and Thermal Properties of Natural Gas Hydrates in Canada. The Canadian Journal of Chemical Engineering 2022, 100 (9), 2557–2571. [10.1002/cjce.24516](https://doi.org/10.1002/cjce.24516).
- Guerra, A.; **Mathews, S.**; Marić, M.; Rey, A. D.; Servio, P. An Integrated Experimental and Computational Platform to Explore Gas Hydrate Promotion, Inhibition, Rheology, and Mechanical Properties at McGill University: A Review. Energies 2022, 15 (15), 5532. [10.3390/en15155532](https://doi.org/10.3390/en15155532).
- **Mathews, S. L.**; Servio, P. D.; Rey, A. D. Heat Capacity, Thermal Expansion Coefficient, and Grüneisen Parameter of CH₄, CO₂, and C₂H₆ Hydrates and Ice Iₕ via Density Functional Theory and Phonon Calculations. Crystal Growth & Design 2020, 20 (9), 5947–5955. [10.1021/acs.cgd.0c00630](https://doi.org/10.1021/acs.cgd.0c00630).

# Presentations & Conferences

**Note:** Presentations delivered in English unless otherwise noted. One full talk delivered in French (QCAM 2024). Fielded audience questions in Spanish during collaborator presentations with UNAM (Facultad de Estudios Superiores Zaragoza, Universidad Nacional Autónoma de México).

## 2025

- International Bio-Inspiration N.I.C.E. Winter Event -- December 09 to December 11, 2025 -- Nice, France
  - Gas hydrate interfacial structures and processes for nanostructure characterization and application to green energy storage
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.nice-conference.com/general-event/)
  - **Prize: Training Mobility Grant/Award - Quebec Center for Advanced Materials (QCAM)**
- CHEM 634: Seminar in Advanced Materials Invited Speaker -- November 07, 2025 -- McGill University, Montréal, Canada
  - Gas hydrate interfaces and bulk: geometric and atomistic perspectives
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - 45-minute invited lecture covering both experimental (Servio) and computational (Rey) lab research; invited by course instructor Dr. Linda Reven (Chemistry Department)
- Canadian Chemical Engineering Conference -- October 05 to October 07, 2025 -- Montréal, Canada
  - Multiscale Characterisation of sII Gas Hydrate Interfacial Structure and Organisation
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Abstract](https://www.xcdsystem.com/cic/program/0CzMEbA/index.cfm?pgid=3111&sid=30508&abid=117304)
  - **Prize: Graduate Research Enhancement and Travel Award**
- Centre for Research in Molecular Modeling Annual Symposium -- May 06, 2025 -- Concordia University, Montréal, Canada
  - Multiscale Characterisation Gas Hydrates Under Pressure
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey

## 2024

- Materials Research Society Fall Meeting & Exhibit -- December 01 to December 06, 2024 -- Boston, United States
  - Characterizing, Classifying and Manipulating Gas Hydrate Crystaline Interfaces and Associated Liquid-Like Layers to Understand Their Nucleation and Growth
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/2024-fall-meeting)
- Chemical Engineering Research Day -- November 28, 2024 -- McGill University, Montréal Canada
  - Characterizing, Classifying, and Manipulating Gas Hydrate Crystalline Interfaces and Associated Phases & Layers to Understand Nucleation and Growth
  - **Samuel Mathews**, Alejandro Rey, Phillip Servio
- Canadian Chemical Engineering Conference -- October 06 to October 09, 2024 -- Toronto, Canada
  - Molecular Modeling and Characterisation of Processes and Dynamics of Gas Hydrates in the Presence of Applied Electric Fields and Backbone Instabilities
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Abstract](https://www.xcdsystem.com/cic/program/guRM5nD/index.cfm?pgid=3018&sid=28670&abid=108732)
- CHEM 634: Seminar in Advanced Materials Invited Speaker -- September 25, 2024 -- McGill University, Montréal Canada
  - Multiscale Modeling of Gas Hydrates and their Interfaces
  - **Samuel Mathews**, Alejandro Rey, Phillip Servio
  - 45-minute invited lecture covering both experimental and computational lab research; invited by Dr. Linda Reven (Chemistry Department)
- 16th World Congress on Computational Mechanics and 4th Pan American Congress on Computational Mechanics -- July 21 to July 26, 2024 -- Vancouver, Canada
  - Modeling the Effect of Backbone Instabilities and Guest Occupancies on Interfacial and Structural Processes and Dynamics of sII Gas Hydrate Systems Using Molecular Dynamics
  - **Samuel Mathews**, Alejandro Rey, Phillip Servio
  - [Home Page](https://web.archive.org/web/20250207184246/https://www.wccm2024.org/)
  - **Prize: Canadian Association for Computational Science and Engineering (CACSE) Travel Award**
  - **Prize: Graduate Research Enhancement and Travel Award**
- 16th World Congress on Computational Mechanics and 4th Pan American Congress on Computational Mechanics -- July 21 to July 26, 2024 -- Vancouver, Canada
  - Geometric Modeling of Gas Hydrate Structural Properties and Guest-Host Interactions
  - **Samuel Mathews**, Zijun Xu, Phillip Servio, Alejandro Rey
  - [Home Page](https://web.archive.org/web/20250207184246/https://www.wccm2024.org/)
  - **Prize: Canadian Association for Computational Science and Engineering (CACSE) Travel Award**
  - **Prize: Graduate Research Enhancement and Travel Award**
- Mathematics of Multiscale and Multiphysics Phenomena in Materials Science (24w5159) -- June 16 to June 21, 2024 -- Banff International Research Station for Mathematical Innovation and Discovery, Banff, Canada
  - Molecular Modeling of sII Gas Hydrate Interfacial Structures and Processes
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - **Invited poster**
  - [Home Page](https://www.birs.ca/workshops/2024/24w5159/report24w5159.pdf)
- Centre for Research in Molecular Modeling Annual Symposium -- May 27, 2024 -- Concordia University, Montréal, Canada
  - Interfacial Properties and Processes of Natural Gas Hydrates for Energy Applications
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.concordia.ca/cuevents/artsci/molecular-modeling/2024/05/27/cermm-symposium-2024.html?c=/research/molecular-modeling/news-events/events)
  - **Prize: Presentation Excellence Award**
- Quebec Centre for Advanced Materials Annual Symposium -- May 22 to May 23, 2024 -- Université de Laval, Quebec City, Canada
  - Propriétés et Processus Interfaciaux des Hydrates de Gaz pour des Applications Énergétiques
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://cqmf-qcam.ca/meeting2024?lang=en)
  - **Prize: Best Use of Language - Oral Session**

## 2023

- Materials Research Society Fall Meeting & Exhibit -- November 26 to December 01, 2023 -- Boston, United States
  - Modeling of Interfacial Growth and Structural Processes and Dynamics of sII Gas Hydrate Systems using Molecular Dynamics and Geometric Techniques
  - **Samuel Mathews**, André Guerra, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/2023-mrs-fall-meeting)
- Canadian Chemical Engineering Conference -- October 29 to November 01, 2023 -- Calgary, Canada
  - Molecular Modeling and Characterization of Interfacial Processes, Structures, and Dynamics of sII Gas Hydrate Systems for Engineering Applications
  - **Samuel Mathews**, André Guerra, Phillip Servio, Alejandro Rey
  - [Listing](https://www.xcdsystem.com/cic/program/33B3EXI/index.cfm?pgid=2)
- 11th World Congress of Chemical Engineering -- June 04 to June 08, 2023 -- Buenos Aires, Argentina
  - Gas Hydrate Thermal and Interfacial Properties and Processes in Gas Capture and Storage for Energy Applications
  - **Samuel Mathews**, André Guerra, Alejandro Rey, Phillip Servio
  - [Home Page](https://www.wcce11.org/)
  - **Prize: Graduate Research Enhancement and Travel Award**
- Chemical Engineering Research Day -- March 17, 2023 -- Université de Montréal, Montréal Canada
  - Modeling of Interfacial Processes of Gas Hydrate Systems for Energy and Engineering Applications
  - **Samuel Mathews**, Alejandro Rey, Phillip Servio
- American Physical Society March Meeting -- March 05 to March 10, 2023 -- Las Vegas, United States
  - Modeling of Interfacial Processes of Gas Hydrate Systems for Engineering Applications at Extreme Conditions
  - **Samuel Mathews**, André Guerra, Phillip Servio, Alejandro Rey
  - [Abstract](https://meetings.aps.org/Meeting/MAR23/Session/PP02.3)
- American Physical Society March Meeting -- March 05 to March 10, 2023 -- Las Vegas, United States
  - Equilibrium molecular dynamics of methane hydrate systems at pre-nucleation conditions to predict system transport properties
  - André Guerra, **Samuel Mathews**, Phillip Servio, Alejandro Rey, Milan Marić
  - [Abstract](https://meetings.aps.org/Meeting/MAR23/Session/CCC01.10)

## 2022

- Materials Research Society Fall Meeting -- November 27 to December 02, 2022 -- Boston, United States
  - Molecular Modeling of Interfacial Structure, Kinetics and Processes of sII Gas Hydrate Systems for Engineering Applications
  - **Samuel Mathews**, André Guerra, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/2022-mrs-fall-meeting)
  - **Prize: Graduate Research Enhancement and Travel Award**
- Materials Research Society Fall Meeting -- November 27 to December 02, 2022 -- Boston, United States
  - Molecular Dynamics Estimations of Transport Properties of Pure Water and Methane Hydrate Systems at Pre-Nucleation Conditions
  - André Guerra, **Samuel Mathews**, Alejandro Rey, Milan Marić, Phillip Servio
  - [Listing](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/2022-mrs-fall-meeting)
- Canadian Chemical Engineering Conference -- October 23 to October 26, 2022 -- Vancouver, Canada
  - All-atom molecular dynamics predictions of transport properties of methane hydrate systems at pre-nucleation conditions using the TIP4P/Ice water OPLS potential
  - André Guerra, **Samuel Mathews**, Milan Marić, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.xcdsystem.com/cic/program/5iXyWiQ/index.cfm?pgid=2778&sid=25672&abid=94832)
- McGill-ETH Zurich Synergia Symposium -- August 05, 2022 -- McGill University, Montréal, Canada
  - Molecular Dynamics-based transport and interfacial properties with applications to rheology and crystallization  of water-based solutions
  - **Samuel Mathews**, André Guerra

## 2021

- Materials Research Society Fall Meeting -- November 29 to December 02, 2021 -- Boston, United States
  - Gas Hydrate Thermal and Interfacial Properties for Natural Gas Capture and Storage via Novel Atomistic-Molecular Dynamics Simulations
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/2021-mrs-fall-meeting)
- Canadian Chemical Engineering Conference: Molecules to Enterprise -- October 24 to October 27, 2021 -- Virtual
  - Gas Hydrate Thermal and Interfacial Properties via Molecular and Atomic Modeling Techniques
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
- Quebec Centre for Advanced Materials Annual Symposium -- May 27 to May 28, 2021 -- Virtual
  - Thermal Properties of Structure I Hydrates Using Density Functional Theory and Phonon Calculations
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://cqmf-qcam.ca/meeting2021?lang=en)

## 2020

- International Conference on Gas Hydrates 10 (Canceled due to COVID-19) -- June 21 to June 26, 2020 -- Singapore
  - Thermal Properties of sI Hydrates Using Density Functional Theory
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://web.archive.org/web/20200301230348/https://icgh10.com/)
- Centre for Research in Molecular Modeling Annual Symposium -- February 07, 2020 -- Concordia University, Montréal, Canada
  - Thermal Properties of sI Hydrates Using Density Functional Theory
  - **Samuel Mathews**, Phillip Servio, Alejandro Rey
  - [Home Page](https://www.concordia.ca/cuevents/artsci/molecular-modeling/2020/02/07/2020-cermm-annual-symposium.html?c=/research/molecular-modeling/news-events/events)

## 2019

- Chemical Engineering Research Day -- November 19, 2019 -- McGill University, Montréal Canada
  - Thermal Properties of sI Hydrates Using Density Functional Theory
  - **Samuel Mathews**, Alejandro Rey, Phillip Servio
  - **Prize: Outstanding Presentation Award (Masters)**
