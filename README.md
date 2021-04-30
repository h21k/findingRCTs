# findingRCTs
Repository for the article: "Finding randomized trials in health research databases: evaluation of transformer models" submitted to [Journal of the American Medical Informatics Association](https://academic.oup.com/jamia) and available at y.

## Authors

[Frank Soboczenski](https://h21k.github.io/) School of Population Health and Life Sciences, King's College London, London, UK<br>
[Byron C Wallace](http://www.byronwallace.com/) College of Computer and Information Science, Northeastern University, Boston, USA<br>
[Anna Noel-Storr](https://www.rdm.ox.ac.uk/people/anna-noel-storr) Cochrane Dementia Group, University of Oxford, Oxford, UK<br>
[James Thomas](https://iris.ucl.ac.uk/iris/browse/profile?upi=JTHOA32) Institute of Education, University College London, London, UK<br>
[Iain J Marshall](https://kclpure.kcl.ac.uk/portal/iain.marshall.html) School of Population Health and Life Sciences, King's College London, London, UK<br>

## Structure of the repository

Data:<br> 

+ one
+ `TimeAnalysis2_1.xlsx` (main data file)<br>
+ `UXData1.xlsx` (aux data file - mainly including qualitative answers)<br>

Fine-Tuned Models:<br> 

Available via hugginface model repo - links to be updated soon
+ link insert<br>
+ link insert<br>
              
Jupyter Notebook: Analysis.ipynb<br>

+ BERT based Jupyter Notebooks

Structure:<br>  
1. `Main Analysis` (distribution of the data, Wilcoxon significance tests, boxplots, scatterplots)<br>
2. `Descriptives` (mean, sd etc of timing data)<br>
3. `Tukey Ladder of Powers` (data transformation and plots)<br>
4. `Linear Mixed Effects Model Analysis` (primary and auxiluiary model analysis)<br>
5. `Reviewer Judgments & Annoations Analysis` (descriptives, self-reported characteristics, agreement data, annotation data)<br>
6. `Questionnaire Analysis` (likert scale analysis, System Usability Score (SUS) evaluation)<br>

The System used and evaluated in this study can be found here: [RobotReviewer User Study](https://github.com/h21k/robotreviewer3/tree/ux)

