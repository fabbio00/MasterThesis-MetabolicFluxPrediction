# MasterThesis-MetabolicFluxPrediction
This repository contains a public overview of my MSc thesis, which focuses on predicting metabolic fluxes using Graph Neural Networks (GNNs).

The goal of this work was to develop a graph-based deep learning approach to estimate reaction fluxes in genome-scale metabolic models. We designed and trained a GNN model that incorporates stoichiometric information, gene expression data, and network topology.

![model](model_architecture.png)

## 📜 Abstract

*Metabolic flux estimation is a fundamental challenge in computational biology, as intracellular fluxes cannot be directly measured and must instead be inferred through computational models. Traditional methods, such as Flux Balance Analysis (FBA), provide constraint-based approaches for estimating metabolic fluxes but rely on strong assumptions, including predefined objective functions and steady-state conditions. These constraints may not fully capture the dynamic and heterogeneous nature of cellular metabolism. Recent advances in deep learning, particularly Graph Neural Networks (GNNs), offer promising tools for modeling complex biological systems with structured data.*

*This thesis explores the application of GNNs for metabolic state inference by integrating omics data with metabolic network topology. After reviewing existing deep learning-based approaches for metabolic flux prediction, key limitations related to flexibility, scalability, and the integration of heterogeneous biological data are identified. To address these challenges, a novel computational framework is proposed, designed to learn directly from gene expression profiles and network connectivity. The proposed method is evaluated against existing approaches by assessing its ability to distinguish metabolic variations between healthy and tumor tissues, its correlation with gene expression patterns, and its adherence to fundamental metabolic principles.*

*Experimental results demonstrate that the GNN-based approach effectively captures biologically meaningful metabolic differences while overcoming key limitations of constraint-based models. This work highlights the potential of geometric deep learning in metabolic modeling, presenting a scalable and flexible alternative to classical methods. In conclusion, the text delineates future research directions, with the objective of expanding the present approach, thereby laying the groundwork for the study of deep learning models for metabolic systems.*

**Keywords:** *Computational Biology*, *Flux Balance Analysis (FBA)*, *Omics Data Integration*, *Deep Learning for Fluxomics*, *Graph Neural Networks (GNNs)*

## 📂 Files

- `Thesis_summary.pdf`: A more detailed overview
- `Thesis_presentation.pdf`: Thesis defense slides with results images

## 🚧 Note

This repository contains only public content. The full code and implementation remain private for now due to possible future publications and ongoing work.

## 🧑‍💻 Author

Fabio Marini [@fabbio00](https://github.com/fabbio00)

## 📅 Date

Thesis defended in March 2025 at Università degli Studi di Milano Bicocca
