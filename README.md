
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Medium Length Professional CV
% LaTeX Template
% Version 2.0 (8/5/13)
%
% This template has been downloaded from:
% http://www.LaTeXTemplates.com
%
% Original author:
% Trey Hunner (http://www.treyhunner.com/)
%
% Important note:
% This template requires the resume.cls file to be in the same directory as the
% .tex file. The resume.cls file provides the resume style used for structuring the
% document.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%	PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------------------------------------------------

\documentclass{resume} % Use the custom resume.cls style

\usepackage{hyperref}
\hypersetup{ 
     colorlinks=true, 
     linkcolor=blue, 
     filecolor=blue, 
     citecolor = black,       
     urlcolor=blue, 
     } 
\usepackage[left=0.4 in,top=0.4in,right=0.4 in,bottom=0.4in]{geometry} % Document margins
\newcommand{\tab}[1]{\hspace{.2667\textwidth}\rlap{#1}} 
\newcommand{\itab}[1]{\hspace{0em}\rlap{#1}}
\newcommand{\tinybullet}{\raisebox{0.25ex}{\tiny$\bullet$} }
\name{Anushka Agrawal}
\address{848-248-1489 \\ anushkaagrawal@uchicago.edu}  % Your phone number and email

\begin{document}

\begin{rSection}{Education}

{\bf The University of Chicago} \hfill {Chicago, IL | June 2026}
\\ 
 B.S. in Computer Science; B.S. in Biological Sciences (Computational Biology track) \\
 GPA: 3.7/4.0 \\
 Honors: Quad Undergraduate Research Scholar 2023-2024; Metcalf Fellowship Awardee 2024-2025

{\bf The Pingry School} \hfill {Basking Ridge, NJ | May 2021}

\end{rSection}

\begin{rSection}{SKILLS}

\begin{tabular}{ @{} >{\bfseries}l @{\hspace{6ex}} l }
Programming Languages & Python, JavaScript, R, C/C++, SQL, Shell/Bash, MATLAB\\ 
Frameworks \& Tools & PyTorch, TensorFlow, React, Node.js, Scikit-learn, NumPy, Pandas \\  
Cloud \& Infrastructure & AWS (EC2, S3), Git, Linux, HPC, Conda, SnakeMake, Hugging Face \\

\end{tabular}

\end{rSection}

\begin{rSection}{EXPERIENCE} \itemsep -3pt  

{\bf AI/ML Intern | Chan Zuckerberg Biohub Chicago} \hfill {June 2025 – present} \\
\tinybullet Led deployment of Virtual CRISPR software, a machine learning tool that predicts CRISPR screen outcomes \\
\tinybullet Built Python pipelines for handling 100+ GB of single-cell sequencing data \\
\tinybullet Optimized data processing workflows, reducing runtime through parallelization and caching

{\bf Computational Drug Discovery Intern | Opal Therapeutics} \hfill {January 2025 – June 2025} \\
\tinybullet Developed a full-stack Python-based platform to predict novel therapeutic targets for gynecological diseases \\
\tinybullet Integrated 200+ complex biological datasets to create a unified analysis framework, employing advanced data wrangling and cross-validation methods in AWS

{\bf Bioinformatics Intern | New York Genome Center} \hfill {June 2024 – August 2024} \\
\tinybullet Engineered scalable pipelines for processing terabyte-scale genomic datasets, optimizing workflows for chromatin accessibility analysis \\
\tinybullet Implemented automated monitoring and error handling for pipeline reliability \\
\tinybullet Optimized database queries and data structures, improving query performance by 30\%

{\bf Quantitative Microscopy Researcher, Munro Lab | UChicago} \hfill {September 2023 – June 2024} \\
\tinybullet Employed quantitative spinning disk microscopy to mathematically model cytoskeletal dynamics in \textit{C. elegans}
\tinybullet Presented findings at the 2024 Quad Undergraduate Research Symposium



\end{rSection} 


%----------------------------------------------------------------------------------------
\begin{rSection}{Projects} \itemsep -1pt {}   
{\bf Predictive Statistical Modeling using Cardiovascular Data} \hfill {March 2024} \\
\tinybullet Built and evaluated GLMs to examine cardiovascular outcomes after kidney transplantation \href{https://drive.google.com/file/d/1Oxth4qUK7QPnecBtO_GYiDahaZozJRW4/view?usp=sharing}{(unpublished report)}

{\bf Structural Analysis of Metastatic Cancer Factor} \hfill {September 2023 – June 2024} \\
\tinybullet \href{https://faseb.onlinelibrary.wiley.com/doi/10.1096/fasebj.2019.33.1_supplement.lb256}{"Chromosomal Instability Promotes cGAS-Mediated Cytosolic DNA Response in Metastatic Cancer", \textit{The FASEB Journal}}

\end{rSection}

\begin{rSection}{Leadership} \itemsep -1pt {}   
{\bf President, Women's Club Ice Hockey | UChicago} \hfill {June 2023 -- present} \\
\tinybullet Organize recruiting events, transportation, and ice time, and oversee recruitment of 40+ new members \\
\tinybullet Introduced a Diversity and Inclusion initiative and raised \$2k to eliminate the financial barrier of hockey gear costs

\end{rSection}

\end{document}
