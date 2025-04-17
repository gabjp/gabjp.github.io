# Undergraduate Thesis - MAC0499 - IME/USP

## Introduction  
Geometric Deep Learning (GDL) is a subfield of machine learning focused on designing neural network architectures that respect the inherent symmetries and invariances of the data. Traditionally, the development of neural network architectures has leaned more toward an empirical craft, driven by trial and error. GDL aims to provide a mathematical framework that connects architectural design to the underlying mathematical structures of the data domain, guided by inductive biases embedded in the architectures.

## Objective
- **Theoretical Component (Monograph):** To introduce, explain, and illustrate the core concepts of GDL in a clear and accessible way, simplifying and summarizing the foundational work presented in [1].  
- **Experimental Component (Optional):** To identify a suitable application domain and conduct computational experiments that demonstrate the principles of GDL in practice.

## Primary Resources
- [1] Bronstein et al., *Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges*, [arXiv:2104.13478](https://arxiv.org/pdf/2104.13478)  
- [2] Geometric Deep Learning Lecture Series: [geometricdeeplearning.com/lectures](https://geometricdeeplearning.com/lectures)

---

## Project Plan  

### Monograph – Theoretical Component

#### 1. Introduction  (May - June)
- **Historical Context:**  
  - Overview of key neural network architectures that have shaped the field of deep learning.  
  - The design of these architectures has traditionally been empirical, relying on extensive trial and error.  
  - **Motivation:** The process of creating deep learning models often lacks a unifying theoretical foundation, leading to inefficient experimentation.  
- **Content:**
  - Universal approximation, inductive biases and the curse of dimensionality.     
  - **Problem Statement:** Approximating arbitrary functions in high-dimensional spaces is data-intensive.    
  - **Proposed Solution:** Leverage geometric structures and patterns present in the data domain.  


#### 2. Preliminary Concepts  (July - August)
- **Geometric Priors:**  
  - **Symmetries:** Transformations that preserve specific properties (e.g., groups, invariance, equivariance).  
  - **Scale Separation:** Techniques for reducing data dimensionality.  
  - These priors serve as tools to combat the curse of dimensionality.  
- **“GDL Blueprint”:** General strategy for incorporating geometric priors into learning architectures.

#### 3. Domains of GDL (September - October)
- Grids  
- Groups  
- Graphs  
- Geodesics  
- Gauges

#### 4. GDL Models  (November - December)
Explore well-known architectures within the GDL framework. For each model, describe its structure, explain how it incorporates geometric priors, and demonstrate how it fits into the broader GDL paradigm.

- **Main Candidates:**  
  - Convolutional Neural Networks (CNNs)  
  - Graph Neural Networks (GNNs)  
  - Transformers  

Include practical examples and applications where these models are used.

---

### Experimental Component (Optional)  
Select a real-world problem or domain and design experiments that showcase how GDL principles can be applied. Potential areas include:  
- Chemistry  
- Biology  
- Combinatorial Optimization  
- Others...
