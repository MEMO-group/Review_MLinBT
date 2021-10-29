# Tutorial
This repository contains the accompanying tutorial to "Improving the performance of machine learning models for biotechnology: The quest for deus ex machina". You find all info in the jupyter notebook "Tutorial" in this repository.
 <br /> <br />
<h2>Technical Prerequisites</h2>

This tutorial is built in <a href="https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/">Jupyter notebook</a> with code written in <a href="https://docs.python.org/3/">Python 3</a>. It is made available publically through GitHub.

If you wish to run or modify code cells yourself:
1. Install Python and Jupyter notebook or use <a href="https://mybinder.org/">Binder</a> online (changes are not saved in this case). To run files locally, download this tutorial and open it via Jupyter Notebook (for example via Anaconda).
2. To run a code cell (blocks preceded by ```[ ]:```), select it and press ```Ctrl + Enter```. In Jupyter notebooks, cells have to be run sequentially to store variables correctly. 
3. Comments in code cells are preceded by # and are not interpreted as code.  
 <br /> <br />
You might need to install the following packages:
* numpy 1.19.2
* pandas 1.1.3
* matplotlib 3.3.2
* scipy 1.5.2
* sklearn 0.23.2  
<br /> <br />
<h2>Recommended Literature</h2>

The review offers a section on basic terminology relevant to the issues discussed below. For a deeper introduction, we particularly highlight the following reviews:

<b>Lawson <i>et al</i>, 2020</b>: <a href="https://doi.org/10.1016/j.ymben.2020.10.005">Machine learning for metabolic engineering: A review</a><br>
<small>Excellent introduction to machine learning, introducting important terminology such as the concepts of over-/underfitting, cross-validation and model complexity. Figure 10 depicts a useful guide for different scikit-learn packages. Section 2.4 describes practical considerations for successful implementation of machine learning, which are particularly useful to beginners. Table 1 lists studies that have used machine learning, including their input dataset size. The review has a focus on machine learning in metabolic engineering.</small>


<b>Walsh <i>et al</i>, 2021</b>: <a href="https://doi.org/10.1038/s41592-021-01205-4">DOME: recommendations for supervised machine learning validation in biology</a><br>
<small>DOME attempts to set a standard for reporting supervised machine learning studies in biotechnology to make assessment and reproducibility easier. It introduces key terms for datasets and optimization and evaluation metrics. Such reporting standards are very much in the spirit of the presented review as well.</small>


<hr style="border:1px solid #e8e8e8"> </hr>

Other sources in alphabetical order:

<b>Camacho <i>et al</i>, 2018</b>: <a href="https://doi.org/10.1016/j.cell.2018.05.015">Next-Generation Machine Learning for Biological Networks</a><br>
<small>Introduction to model categories used for biological problems with a focus on neural networks and different fields that particularly profited from applying machine learning models: Disease biology, drug discovery, microbiome research, synthetic biology.</small>


<b>Cuperlovic-Culf <i>et al</i>, 2018</b>: <a href="https://doi.org/10.3390/metabo8010004">Machine Learning Methods for Analysis of Metabolic Data and Metabolic Pathway Modeling</a><br>
<small>Table 1 shows an overview of algorithm groups with a short description and applications listed for each. The review itself focuses on machine learning on metabolic data and pathway modeling.</small>


<b>Kim <i>et al</i>, 2020</b>: <a href="https://doi.org/10.1016/j.copbio.2019.08.010">Machine learning applications in systems metabolic engineering</a><br>
<small>Table 1 shows an overview of algorithm tasks with a short description and applications listed for each. Figure 1 depicts a graphical overview of different machine learning algorithms being employed each step of the workflow for industrial strain development. This review discusses machine learining in the context of systems biology.</small>


<b>Presnell & Alper <i>et al</i>, 2019</b>: <a href="https://doi.org/10.1002/biot.201800416">Systems Metabolic Engineering Meets Machine Learning: A New Era for Data-Driven Metabolic Engineering</a><br>
<small>This review focuses on data-driven research in systems biology and metbaolic research. Table 1 lists data repositories where Omic dataset scan be found and table 2 discusses various algorithms, their pros and cons and relevant articles. The review discusses subsections of the field where studies applied data-driven models.</small>


<b>Reel <i>et al</i>, 2021</b>: <a href="https://www.sciencedirect.com/science/article/pii/S0734975021000458">Using machine learning approaches for multi-omics data analysis: A review</a><br>
<small>This review discusses the use of machine learning models in the context of multi-omic datasets. It provides an overview of high-throughput techniques in omics and also introduces standard machine learning terminology. Several challenges that come with omic datasets such as class imbalances, outliers and small dataset sizes are briefly discussed. The review also provides an overview on different multi-omic integration methods that were carried out using difernt learning algorithms.</small>


<b>Volk <i>et al</i>, 2020</b>: <a href="https://doi.org/10.1021/acssynbio.0c00129">Biosystems Design by Machine Learning</a><br>
<small>This review defines terminology such as variables, loss function, hyperparameters. It also briefly introduces some of the most known algorithms (such as random forest or neural network). Applications in synthetic biology are described for all relevant levels: DNA, protein engineering (detailed description in table 2), pathway, genome and process (detailed descriptoin in table 3) level.</small>


<b>Zou <i>et al</i>, 2020</b>: <a href="https://doi.org/10.1038/s41588-018-0295-5">A primer on deep learning in genomics</a><br>
<small>This review focuses on applying deep learning to problems in genomics and explains neural network-relevant terminology. Tips for usage and interpretation are discussed and further elaborated in an interactive online tutorial. Box 3 lists resourches such as cloud platforms and software libraries that are useful for deep learning. Applications in the field of genomics are reviewed.</small>
 <br /> <br />
<h2>The authors</h2>
Authors of paper: Friederike Mey, Jim Clauwaert, Kirsten Van Huffel, Willem Waegeman, Marjan De Mey <br />
Authors of tutorial: Friederike Mey, Jim Clauwaert and cited sources <br />
Contact: <a href="mailto:marjan.demey@ugent.be">Marjan De Mey</a>
