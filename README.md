# Ants_temperature_adaptation_dissertation   
### Author: Andrew D. Nguyen    
### website: https://adnguyen.github.io/    
### email: anbe642@gmail.com   
Date started: 20160322   
Last date modified: 20160408    

------

# Table of contents
1. [Sharing my dissertation](#id-section1)
2. [Dissertation Questions](#id-section2)
3. [Repository Layout](#id-section3)

 

------
<div id='id-section1'/>
## Sharing my dissertation projects     
My goal is to make my research reproducible and open to anybody who wants to expand or double check my data analyses. I'm trying to model the way I layout each project following this paper: http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424

Basically, anybody should be able to download any one of my projects(or whole dissertation repository), understand the files and recover similar/identical results.     

------

<div id='id-section2'/>  
## Dissertation Questions/projects
1. What is the evolutionary history of critical stress proteins in ants? This is already [published](http://bmcevolbiol.biomedcentral.com/articles/10.1186/s12862-015-0573-0)    

2. To what extent are common woodland ants locally adapted to their environment? And how does the stress response follow these patterns of adaptive variation?    

3. How do other stressors that accompany climate change influence the thermal physiology of these ants?    

**Additional questions/projects**   

* Do common woodland ants at the northern range limits face thermal constraints?   

* Are ants stressed under experimental warming?   

** These will be shared as separate repositories. ** 

------

<div id='id-section3'/>  
##Repository layout 
* The main folder has the readME, license, and the overall protocols for most of these projects.    
* Question 2 and 3 are layed out in /Dissertation_Projects/2014_xanbe-common-garden_gxp_evolution/   
 
  1. **2016_Comparative_HSs_CTmax_geneexpression_manuscript/** : folder for manuscript
  2. **Data/** : All of the raw data generated and includes manipulated or manually parsed data. 
    * **Phylogenetics/** : phylogenetic trees from raxml and beast analyses
    * **Raw/** : All qpcr data
    * **sequencing/** : sequenced amplicons from qpcr reactions
  3. Results/ : Has preliminary results so far; pdf output of scripts
  4. **Scripts_Analyses/** : I use [R](https://www.r-project.org/) and [Rstudio](https://www.rstudio.com/) for data analysis and data visualization and convert ([knit](http://yihui.name/knitr/)) these analyses into pdfs(see results). 
