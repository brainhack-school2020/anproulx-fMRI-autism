[![](https://img.shields.io/badge/Visit-our%20project%20page-ff69b4)](https://school.brainhackmtl.org/project/template)

# How well can autism be predicted from fMRI data?

By Andréanne Proulx

![Brainhacking](https://cdn2.researchfeatures.com/wp-content/uploads/2016/06/Decoding_language_brain.jpg)

*Source: https://researchfeatures.com/2016/06/20/decoding-language-brain/

### Background

I am a Master's student in Psychology currently enrolled at the University of Montreal. My main focus is in genomic imagery which consists of investigating the effect of genetic mutations on fonctional and structural brain phenotypes. More specifically, I have been interested in resing-state functional connectivity measures in carrier populations. 

![Me](21.png)

### Project definition 

This project's main objective will be to learn machine learning and visualisation tools available in Python. As for the scientific purpose, it will be to evaluate the performance of different linear and non-linear classification algorithms (SVM, decision tree, random forest, etc.) at a task which consists of predicting autism diagnosis from the functional connectivity data. I will also try out cross validation and different hyperparameters in order to maximise the classification performance. A second objective for this project will be to integrate as much of the tools (Github notably) we were introduced to in the previous week allowing therefore science to be as reproducible as possible. 

![Data preparation](42.png)
![Machine learning](44.png)
![Machine learning](46.png)

### Tools 

This project will rely on the following tools: 
 * Jupyter Notebook 
 * Libraries: Scikit-learn, Nilearn, Seaborn, Matplotlib, Pyplot
 * Github 

### Data 

For the purpose of this project, I will be using an the preprocessed open source database ABIDE (see Preprocessed Connectomes Project), available through Nilearn. This data contains structural, functional and phenotypic data of 539 individuals with autism and 573 typical controls.  

### Deliverables

 - A jupyter notebook containing the code and all visualization graphs
 - Requirements.txt
 - Readme file 
 - Python script
 - Presentation slides
 - Interactive plot (Week 3)
 
### Tools I will learn during this project

 - Python librairies: Nilearn (specialized library for neuroimaging), Matplotlib (static plotting),  Plotly (interactive plotting), Sklearn (Machine learning)
 -Jupyter Notebook
 - Git & Github : Track files and building a repository
 
### Tools I ended up learning during this project
- Python librairies: Nilearn, Matplotlib,  Plotly, Sklearn (dimensionality reduction, test-train split, gridsearch, cross-validation methods, evaluate performance)
- Jupyter Notebook
- Github: Push, pull, fork, merge, pull requests, issues, etc. Also learned team management and organization.
- Git: Track Jupyter Notebook
- Venv: Make requirement.txt file

## Collabs
Part of the ABIDE TEAM. See team repo: https://github.com/orgs/brainhack-school2020/teams/abide-team

### Results
![Results](result_cv.png)

### Deliverable week 3
 - link: [Age distribution](https://anproulx.github.io/publication_website/)
 - link: [Influence of hyperparameter values gamma and C for SVM estimator](https://anproulx.github.io/cross_validation_plots/)
 
### Resources
1. Choosing appropriate estimators with scikit-learn https://scikit-learn.org/stable/tutorial/machine_learning_map/
2. Benchmarking functional connectome-based predictive models for resting-state fMRI (for classification estimator inspiration) https://hal.inria.fr/hal-01824205
3. Getting the data using nilearn fetch https://nilearn.github.io/modules/generated/nilearn.datasets.fetch_abide_pcp.html
4. Python Data Science Handbook GitHub and website https://github.com/jakevdp/PythonDataScienceHandbook

## Conclusion and acknowledgement
A special thank you to all the 2020 BrainHack School Organizers for making this event an amazing learning experience!

Pierre Bellec (Mentor)
Désirée Lussier-Lévesque (Mentor)
Alexa Pichet-Binette (Mentor)
Sebastian Urchs (Mentor)
Jean-Baptiste Poline
Tristan Glatard
Benjamin de Leener
Elizabeth DuPre
Ross Markello
Peer Herholz
Samuel Guay
Valerie Hayot-Sasson
Karim Jerbi
Greg Kiar
Jake Vogel
Agâh Karakuzu


