[![](https://img.shields.io/badge/Visit-our%20project%20page-ff69b4)](https://school.brainhackmtl.org/project/template)

# How well can autism be predicted from fMRI data?

By Andréanne Proulx

![Brainhacking](https://cdn2.researchfeatures.com/wp-content/uploads/2016/06/Decoding_language_brain.jpg)

*Source: https://researchfeatures.com/2016/06/20/decoding-language-brain/

### Background

I am a Master's student in Psychology currently enrolled at the University of Montreal. My main focus is in genomic imagery which consists of relating information about genetics to fonctional and structural brain phenotypes. More specifically, I have been interested in functional connectivity measures in the resting-state in carrier populations. 

## Project definition 

This project's main objective will be to learn how to use machine learning and visualisation tools available in Python. As for the scientific purpose, it will be to evaluate the performance of different linear and non-linear classification algorithms (SVM, decision tree, random forest, etc.) at a task which consists of predicting autism diagnosis from the functional connectivity profile observed in subjects. I will also try out cross validation and different hyperparameters in order to maximise the classification performance.    

![chart (2)](https://user-images.githubusercontent.com/65092948/82572545-7f161a80-9b52-11ea-9380-640eca9851bd.jpg)

https://hal.inria.fr/hal-01824205v3/document

A second objective for this project will be to integrate as much of the tools (Github notably) we were introduced to in the previous week allowing therefore science to be as reproducible as possible. 

### Tools 

This project will rely on the following tools: 
 * Jupyter Notebook 
 * Libraries: Scikit-learn, Nilearn, Seaborn, matplotlib, Pyplot
 * Github 

### Data 
For the purpose of this project, I will be using an the preprocessed open source database ABIDE (see Preprocessed Connectomes Project), available through Nilearn. This data contains structural, functional and phenotypic data of 539 individuals with autism and 573 typical controls.  

### Deliverables
 - A jupyter notebook containing the code and all visualisation graphs
 - Requirements.txt
 - Readme file 
 - Python script
 - Presentation slides
 - Interactive plot (Week 3)
 
### Tools I will learn during this project
 - Matplotlib & Plotly: Explore different ways of exploring and plotting the data
 - Nilearn: Visualize fMRI data in the form of static and interactive images (matrix, brain plotting, etc.)
 - Sklearn: Dimensionality reduction, test-train split, try out different estimator to fit the data, cross-validation methods, evaluate performance
 - Github

## Open to colabs?
Part of the ABIDE TEAM. See team repo: https://github.com/orgs/brainhack-school2020/teams/abide-team

### Deliverable week 3
link: [Age distribution](https://anproulx.github.io/publication_website/)
link: [Influence of hyperparameter values gamma and C for SVM estimator](https://anproulx.github.io/cross_validation_plots/)

### Results
![chart (2)](https://app.diagrams.net/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.drawio#R7Vxbd5s4EP41Pmf3wTncjR9bnLRnk6Y5Sbd7edkjQMa0GHmF4kt%2BfUcgbAGKS5PYpiXuQ9AgCc18n0fDaNyB6c3X7yhazD6QECcDQwvXA3MyMAzd0cbwh0s2hcQytEIQ0TgUnXaCu%2FgBC2HZ7T4OcVbpyAhJWLyoCgOSpjhgFRmilKyq3aYkqT51gSLcENwFKGlK%2F4pDNiukrjHayd%2FjOJqVT9YdofAclZ2FJtkMhWQliczzgelRQlhxNV97OOHGK%2B1SjLt45O52YRSnrM2A8Hq9ub4cBSPXv1otsxB%2FeG8PdTHNEiX3QuPzjMWweEIzbsI05MalJMuG0CcOEYtJyrUJCAVcCs3YpjRXtornCUqh9XbG5gkIdbjMGKJMYAurhHuExg8kZajsEfBGnGL6abPgvRjFfI4oQRkHkI9p6luuHVOG15JI6P8OkzlmdANdxF1LQCG4OBbN1Q7YUcm7mQSqVY5DgkzRduadveFCmFxt%2Fs9%2FfL70%2FnU3%2F32dPlgfP15eEXQ7NBvWb1gUh8BH0SSUzUhEUpSc76SFdd9wrkOXlOTGx2lYk1Byn4Y4FMaEIRFmNzChR9KMUbA9VxajjK1wxvis5J4GuNEj5WuAe9xgAhK%2BwuoXNJ98j9p2E8s97GzCSXECPFxWn6oCRwy9IXzxWxroRpUHhlPDt9Q9H1WDeLuMp6Nu9RN1p9%2Bo2wrUnYQbPYyXcBnxSwf2FQ8MZZf34FHS7QZPVrOY4bsFCnh7BVtw1fGCx45SuA7A4piCgPvKGHa3N%2BLGPA7DnE7c4V7A5hinkRjLJR%2FIcieYxknikYTQ%2FNFmiLA7DXImUvIVS3ecwMX%2BdLvchn9%2BBgfENDUoTU3hyVWO%2FFB%2B3Glgy8MAz8iB7BBkNnZDSwWZa%2Fim4xwSMt3sGGajfnrh8Wm9sOmc1gu7%2FUS9DGv7Cvu4AbvNd9pR1xz0KffU0fcdtHtMB11yVgYNvr6e1TXQTrirmp0DTRXm9sHBjp4J6DMdrO3WHKx9XAerN0PgfuDu9hz3Zhhtgwvw3K456RPurLbWsVcfvRkFwzZleOOugXbCndXpGmhGMxzqhYct1exK3tA0jutht8ccfcPd7DnuRtNJQ9uzO%2Bakp1PsBMqdNRyNfU07pJOuQ%2BSc2ke3ONA7KVRT4xGoHN%2Bxj5v%2FPTlWLd5YSttfIR8nNySL89Nvc%2BITxshcAQ4jNTizGcoPtOfriBdInPkoi4OzBWIAbnoB8NzmVQs5UqUHD2MU3eJljhOG%2BSb2tgOHraxD0M6MilyGM%2F8cNjyqoGkooqOtA5XhrOf9Xg7OFomHVzgffUWpH44eEM8%2FM0w%2F%2Bl%2B4oQwt4VAUQ6%2FiFCMKsrvPnogRwJ%2Fd5gUykqr7WTCW1BS0eYbvbeFiU7yS4qzJYAQgOf%2Ff80W%2F3YVlW9HAfCPdT3wijd51MrxdQ4rc1LPksZt67DbCazVyNFFsGTb%2Fp3xvzj98BEmZJC8%2Bv4jvgaZE1730neAgzoriqE%2B8eumJDDa1Vwb%2F8gw%2BprtVULhlcVozS3SL0hA2SkO74NV%2F7KSx7Sttj05bq%2BZ5FQWUunbMoM9snus2OCnnRmq4CyLAjZKIT8yU4HXM%2Fs5jONMcifY%2F0B5qZ5prCsFkLfWebKTGDaYxGIR%2FJaRS1x9PmZg%2FdhgBZspTGN%2BNql88t2LVKnGPfGhh%2F%2BQptS3dJKrpe1n2VEbZP5aEa8GogqMvX2BiVxnVsr4EwEIbqduCd8j2EFftAS8e6%2B7u6w4XxfNfltzNHFQn84anPJGzGsWIjY1MlYsyD7WP2c1c1Hma4bnPgxMNnjEjYQM7MAqrZScqlhQOSDa7ELWHVcWPqkc7XIxcK23RFQlDSwFSPU3%2FckW%2BqgM4qYJbwqaM7DhEQ2FtCP%2B0L%2FcZi6cbOWgsC7uLibIFSpUz%2BSj4GuWWHwYFmHw%2BGvm%2FGZo14DqDUprB8x%2FltW3%2F3nyQrg3z30DtysuLR1aXUa8675iWvMKgvDY1hZYJRks8BLIPYcf8%2BXSV9dOc7bVuj%2Ffpyp8C31b481Sl%2BQvFsw1ROAWtpXoVVS0lYfksixppFYsHaXX9%2FXKXQ9tWhtSStzRUGYWDuUujxc%2Bc%2BpGQ%2F04JZ%2B1dSPlWfdyjlBY%2FjTgdci8B25FzLd0hwGPJ68vr68FTj1zkF7rXhHX3M3%2FdYaMiNQ2i3U%2Fii1fi3X8sYJ5%2FAw%3D%3D)

##### Other projects
## Conclusion and acknowledgement

