---
layout: default
title: Research
---
<a href="{{site.baseurl}}/index">Home</a> | 
<a href="{{site.baseurl}}/profile">Profile</a> | 
<a href="{{site.baseurl}}/publications">Publications</a> | 
<a href="{{site.baseurl}}/research">Research</a> | 
<a href="{{site.baseurl}}/teaching">Teaching</a>

## Research

<!-- <sub>[Research Supervision](#research-supervision)</sub> -->

I investigate and innovate in the areas of artificial intelligence (neural networks) and data science. Through my research, I try to answer the following questions:

1. How to design fast, robust, optimal, efficient learning systems? This includes research in the area of lightweight, explainable and inferable neural networks and learning systems and adversarially robust and secure networks.
1. How to effectively solve challenging interdisciplinary problems? For example, image data (e.g., medical imaging), environment data (e.g. hydrology), climate data (e.g., chaotic systems).
1. How do biological neurons behave, and how to inform the design of biologically plausible neural networks?

I like to work with academics, industry, and students on research contributing to these questions. Do read examples of my work towards answering these questions and do get in touch at v.k.ojha[at]reading.ac.uk.

### Grants
1. **EPSRC (UK)** Doctoral Training Program projects from the University of Reading (£120K): a) Artificial intelligence-enabled smart eco assisted living space (PI) and b) Combining machine learning and data assimilation to estimate model errors (Co-I). 
1. **Innovate UK** projects (£230K): a) a project with Optimal Monitoring on natural language processing for customer feedback and response systems (advisor) b) a project with CrowdCharge on time-series forecasting for electric vehicle charging preferences (advisor).

### Current Research
I recently worked on an algorithm called a **backpropagation neural tree**. I propose a _stochastic computational dendritic tree_ that takes random repeated inputs through its leaves and imposes dendritic nonlinearities through its internal connections as a biological dendritic tree would. This neural tree's neurons plausibly are close to the biological behaviour of neurons, dendrites. This research is inspired by _neuroscience_ aspects to inform this new neural network algorithms design. The image below shows the computation of this neural tree algorithm and other computational models of the literature.

![](/imgs/tree_bio.svg)

**Figure.** Biologically plausible neural computation of dendritic trees. The red circle represents a neuron (soma), black lines are dendrites, and the numbers indicate inputs. Left is a biological neuron model ( <a href="https://www.karger.com/Article/Abstract/86707" target="_blank">Travis et al., 2005</a>), the middle is a single neuron dendritic tree (<a href="https://direct.mit.edu/neco/article-abstract/33/6/1554/100576/Might-a-Single-Neuron-Solve-Interesting-Machine?redirectedFrom=fulltext" target="_blank">Jones and Kording, 2021</a>), right is the proposed backpropagation Neural Tree. 

This work is currently under review in _Neural Networks_ Elsevier (check out preprint <a href="https://github.com/vojha-code/BNeuralT/blob/master/BNeuralT.pdf" target="_blank">PDF</a> and <a href="https://github.com/vojha-code/BNeuralT" target="_blank">Code</a>). Also, check previous related work on trees (<a a href="https://arxiv.org/abs/1705.05592" target="_blank">neural tree</a> and <a a href="https://arxiv.org/abs/1705.05769" target="_blank">fuzzy tree</a>). Students interested in the topics of **neural networks** and **deep learning** network architecture analysis (e.g., using adversarial robustness), and exploring neuroscience, information-theoretic or complex network literature for PhD research are welcomed!

I like to work on **interdisciplinary research** and **data science** projects. In my recent work in collaboration with the meteorology department, we forecast real flood events of the rivers Severn and Avon, UK. We investigate how Transfer Learning and Semantic Segmentation can be applied to a time series of images (see Fig below) to predict flood events. Our to-date results have successfully demonstrated use to Transfer Learning with an accuracy above 91% for these flood events (check out our paper). 

![](/imgs/water_segmentation_work.png)

**Figure** time-series of river camera images. Water (blue) and non-water pixel predictions.

Other interdisciplinary research titles in the areas of applied **Evolutionary Computation** and **Optimisation** I am working on are:
1. A multiobjective evolutionary algorithm application for the prediction of the best strain of genes and production of chemicals.  <br>
**Output Due:** Potential output is Amaradio MN, **Ojha V**, Jansen G, Pappalardo X, Costanza J, <a href="https://orcid.org/0000-0002-0650-3157" target="_blank">Nicosia G</a>, (2022) Microbial Cell Factories Engineering for the Growth-coupled Overproduction of Sustainable Chemicals, _Biotechnology and Bioengineering_.
1. An application of derivative-free optimisations algorithms for the optimisation of  Space Trus Structures (Civil Engineering). <br>
**Output Due:** **Ojha V**, <a href="https://www.imperial.ac.uk/people/b.panto" target="_blank">Panto B</a>, Nicosia G (2022) Incremental hypersphere algorithm for buckling analysis of space truss structures, _Engineering Applications of Artificial Intelligence_.

### Research Supervision Projects
#### Current Postdoc
Remy Vandaele (2020–), Machine learning for high-impact weather and flood prediction (co-supervision
with <a href="http://www.met.reading.ac.uk/~sws01sld/" target="_blank">Prof Sarh Dance</a> of Mathematics Department), UoR, UK. (current output: a <a href="https://centaur.reading.ac.uk/93823/" target="_blank">paper</a> and a <a href="https://hess.copernicus.org/articles/25/4435/2021/" target="_blank">journal</a>)

**Project**: _We investigate how Transfer Learning and Semantic Segmentation can be applied to predict flood events. We use the river Camra Images of FasonDigital Watercams as our data source and the past flood events of the UK as case studies. Our to-date results have successfully demonstrated use to Transfer Learning with an accuracy above 91%  for the flood event on the rivers Severn and Avon, UK. Currently, we are trying to investigate a large volume of data by combining river gauge data time-series with image data time-series and offering an automated flood monitoring system_. 

#### Current PhD Student Projects
Chandresh Parvin (2019–2022), Signal Processing for the Robustness Analysis of Deep Neural Networks, UoR (current output: <a href="https://centaur.reading.ac.uk/99457/" target="_blank">paper</a>)

**Questions**: _We investigate methodologies to expose the weaknesses of deep neural networks against adversarial attacks. We aim to answer what and why adversaries target some features from a learned representation instead of others. We aim to evaluate the structural robustness of deep neural networks with respect to a clean dataset and the dataset applied to a single-step adversarial perturbation in the input space with respect to increasing generalization loss. Moreover, we aim to apply signal processing techniques to perturb neural synapses globally and locally to analyze how the network response varies for the perturbed and unperturbed inputs_. A near submission output:

**Output Due:** Pravin C, Ojha V, (2022) Exposing the weaknesses of deep neural networks against adversarial attacks.

Daniel Ayers (2019–2022) Using supervised learning to estimate local instabilities in chaotic systems: computation of local Lyapunov exponents, UoR (co-supervision with <a href="https://scholar.google.com/citations?user=hiMvzDYAAAAJ&hl=en" target="_blank">Prof Alberto Carrassi</a>, current output: a <a href="https://events.ecmwf.int/event/172/contributions/1739/attachments/865/1538/Machine-Learning-WS_Ayers.pdf" target="_blank">poster</a>)

**Questions**: _In dynamical systems such as those to predict the weather, prediction errors grow faster in some situations than in others. Knowledge about the growth of prediction errors at the current time could enable strategies to quantify or mitigate error growth. The theory of Lyapunov exponents measures the rate at which very small prediction errors grow. Calculating Lyapunov exponents exactly requires the tangent linear model and orthogonalization algorithms. These are computationally expensive. We investigate whether supervised machine learning can provide a cheaper alternative. Specifically, we test the ability of popular supervised learning methods to predict the local Lyapunov exponents in two low-dimensional chaotic dynamical systems. We find that the predictions are accurate in certain cases, and we suggest how this difference in performance might be explained_. 

**Output Due:** Ayers D, Lau J, Amezcua J, Carrassi A, Ojha V, (2022) Supervised learning to estimate local dynamical instabilities in chaotic systems: computation of local Lyapunov exponents, _Quarterly Journal of the Royal Meteorological Society_.


Rhian Taylor (2020–2023) Sensitivity Analysis of Deep Neural Networks, UoR, UK. (current output: <a href="https://centaur.reading.ac.uk/100199/" target="_blank">paper</a>)

**Questions**: _We investigate novel approaches to ranking and understanding the influence of deep learning (DL) hyper-parameters through the application of sensitivity analysis (SA). We investigate how shallow and deeper models are susceptible to hyper-parameters affecting their convergence profiles. We try to understand how the stochasticity of the learning process of deeper models showed sensitivity to hyper-parameters and how hyperparameters influence the convergence speed. Additionally, we try to understand how the complexity of the dataset can affect the margin of separation between the sensitivity measures of the most and the least influential parameters_.

#### Selected Master and Bachelor Student Projects
##### Selected Master Student Projects
1. Jaikumar P (2020) Transfer learning for segmentation of waste bottles using Mask R-CNN (<a href="https://centaur.reading.ac.uk/98569/" target="_blank">Conference Paper</a>)
1. Desai SV (2021) Study of diffusion of nano-particles in polymer and ferrofluids using ML, (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/PG/2021_Shreya_Desai_MSc.pdf" target="_blank">Thesis</a>)
1. Lau J (2021) Computing of local Lyapunov exponents using machine learning, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/PG/2021_Jack_Lau_MSc.pdf" target="_blank">Thesis</a>)
1. Ashokan V (2021)Variational Autoencoders and GANs for addressing imbalance image data, (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/PG/2021_Vijayakumar_Asokan_Msc.pdf" target="_blank">Thesis</a>)
1. Peschiutta P (2020) Machine Learning modelling of die filling for pharmaceutical powders, (external co-supervision with <a href="https://www.surrey.ac.uk/people/charley-wu" target="_blank">Prof C Wu</a>), University of Padua, Padua, Italy (<a href="http://tesi.cab.unipd.it/64688/1/Peschiutta_Stefano_1190561.pdf" target="_blank">Thesis</a>)
1. Heidi S (2018)Non-spatial and spatial statistics for analysing human’s perception of the built environment, ETH Zurich (<a href="https://www.research-collection.ethz.ch/handle/20.500.11850/290292" target="_blank">Thesis</a>)
1. Charlotte S (2017) People’s perception of urban and architectural features, ETH Zurich (<a href="https://www.research-collection.ethz.ch/handle/20.500.11850/266634" target="_blank">Thesis</a>)
1. Victor S (2018) Convolutional neural network based visual feature extraction for evaluation of the
urban environment, ETH Zurich, Zurich (<a href="https://www.research-collection.ethz.ch/handle/20.500.11850/293677" target="_blank">Thesis</a>)

##### Selected Bachelor Student Projects
1. Ward B (2020) Classification of musical preference in generation Z through signal processing, UoR, UK (<a href="https://centaur.reading.ac.uk/98568/" target="_blank">Conference Paper</a>)
1. Shergill JS (2020) Machine learning for speech (English language accent) classification, UoR (<a href="https://centaur.reading.ac.uk/97785/" target="_blank">Confernce Paper</a>)
1. Young R (2021) Using DL and box speed calibration for predicting rowing boat speed, UoR (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2020_21_Rob_Young.pdf" target="_blank">Report</a>)
1. Taemur A (2021) Audio classification using machine learning techniques, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2020_21_Adam_Taemur.pdf" target="_blank">Report</a>)
1. Neele M (2021) Using neural networks for time-series analysis of UK river flow data, UoR, UK(<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2020_21_Michale_Neel.pdf" target="_blank">Report</a>)
1. Mehring C (2021) Fake news detection with neural networks, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2020_21_Conor_Mehrin.pdf" target="_blank">Report</a>)
1. Doidge KB (2021) A study into the effectiveness of recurrent neural networks for trading, (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2020_21_Kyle_Doidge.pdf" target="_blank">Report</a>)
1. Rickard J (2020) An analysis of NLP techniques applied to generating tweets, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2019_20_Joe_Richard.pdf" target="_blank">Report</a>)
1. Ford J (2020) Reading bus time prediction - A data science approach, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2019_20_Jade_Ford.pdf" target="_blank">Report</a>)
1. Braund T (2019) Analysing and presenting the general public opinions of feature films through data mining from social media feeds and a chatbot, UoR, UK (<a href="https://github.com/ojhavk/ojhavk.github.io/blob/main/data/Student_Projects/UG/2018_19_Thomas_Braund.pdf" target="_blank">Report</a>)

### Code Repository at GitHub (<a href="https://github.com/vojha-code/" target="_blank">github.com/vojha-code</a>) 
1. Backpropagation Neural Tree (BNeuralT) (<a href="https://github.com/vojha-code/BNeuralT" target="_blank">Code</a>)
1. Neural-Tree-Software (<a href="https://github.com/vojha-code/Neural-Tree-Software" target="_blank">Code</a>)
1. Neural-Network-Predictor Software(<a href="https://github.com/vojha-code/Neural-Network-Predictor" target="_blank">Code</a>)
1. Conjugate-Gradient-Neural-Network (<a href="https://github.com/vojha-code/Conjugate-Gradient-Neural-Network" target="_blank">Code</a>)
1. Complex-Valued-Neural-Network (<a href="https://github.com/vojha-code/Complex-Valued-Neural-Network" target="_blank">Code</a>)
1. Multiple-Linear-Regression (<a href="https://github.com/vojha-code/Multiple-Linear-Regression" target="_blank">Code</a>)
1. Hierarchical-Fuzzy-Tree (<a href="https://github.com/vojha-code/Hierarchical-Fuzzy-Tree" target="_blank">Code</a>)
1. K-Nearest-Neighbor (<a href="https://github.com/vojha-code/K-Nearest-Neighbor" target="_blank">Code</a>)
1. Support-Vector-Machine (<a href="https://github.com/vojha-code/Support-Vector-Machine" target="_blank">Code</a>)
1. Self-Organizing-Map (<a href="https://github.com/vojha-code/Self-Organizing-Map" target="_blank">Code</a>)
1. Anomaly-Detection (<a href="https://github.com/vojha-code/Anomaly-Detection" target="_blank">Code</a>)
1. Humans Perception Through Physiological Response <a href="https://github.com/vojha-code/ESUM-project" target="_blank">Code</a>)

1. Sensitivity Analysis of Evolutionary Algorithms <a href="https://github.com/vojha-code/SAofEAs" target="_blank">Code</a>)
1. Meta-heuristic-Optimizer Software(<a href="https://github.com/vojha-code/Meta-heuristic-Optimizer" target="_blank">Code</a>)
1. Multilevel-Coordinate-Search (<a href="https://github.com/vojha-code/Multilevel-Coordinate-Search" target="_blank">Code</a>)
1. Evolutionary-Computation (<a href="https://github.com/vojha-code/Evolutionary-Computation" target="_blank">Code</a>)
1. Evolutionary-Ensemble (<a href="https://github.com/vojha-code/Evolutionary-Ensemble" target="_blank">Code</a>)

1. Algorithm-Complexity (<a href="https://github.com/vojha-code/Algorithm-Complexity" target="_blank">Code</a>)
1. Curse-of-Dimensionality (<a href="https://github.com/vojha-code/Curse-of-Dimensionality" target="_blank">Code</a>)
1. Principal-Component-Analysis (<a href="https://github.com/vojha-code/Principal-Component-Analysis" target="_blank">Code</a>)
1. Kolmogorov-Smirnov-Test (<a href="https://github.com/vojha-code/Kolmogorov-Smirnov-Test" target="_blank">Code</a>)
1. Block-Truncation-Coding (<a href="https://github.com/vojha-code/Block-Truncation-Coding" target="_blank">Code</a>)
1. Python-MATLAB-Communication (<a href="https://github.com/vojha-code/Python-MATLAB-Communication" target="_blank">Code</a>)
1. Cython-Project-Hierarchy (<a href="https://github.com/vojha-code/Cython-Project-Hierarchy" target="_blank">Code</a>)
