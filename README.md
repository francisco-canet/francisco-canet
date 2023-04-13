### Hi there 🙋

I’m an engineer and biomedical researcher. My research was focused on studying cellular mechanisms (such as mitochondrial function and oxidative stress) implicated in the development of diabetes and its related cardiovascular complications. During this period, I learned many important lessons for becoming a data scientist.
- 🔭 I’m currently searching for job opportunities
- 📫 How to reach me: [e-mail](francisco.canet.1994@gmail.com) and [Linkedin](https://www.linkedin.com/in/francisco-canet/)  
---
### 🧰 Languages and Tools:

<img align="left" alt="Python" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />

<img align="left" alt="Pandas" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" />

<img align="left" alt="Numpy" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" />

<img align="left" alt="R" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" />

<img align="left" alt="PostgreSQL" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" />

<img align="left" alt="MySQL" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-plain-wordmark.svg" />

<img align="left" alt="scikit learn" width="50px" style="padding-right:10px;" src="https://raw.githubusercontent.com/scikit-learn/scikit-learn/00032b09c7feea08edd4486c522c2d962f9d52ec/doc/logos/scikit-learn-logo-without-subtitle.svg" /> 

<img align="left" alt="Flask" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original-wordmark.svg" />


<img align="left" alt="vscode" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original-wordmark.svg" />

<br />
<br/>

#

---
### 💼 My Projects

#### 1. Biomarkers to predict the development of type 2 diabetes.
This project was part of my PhD thesis, check the published research [here](https://pubmed.ncbi.nlm.nih.gov/36501195/) <br/>

Diabetes involves many metabolic alterations beyond high glucose levels. It could be helpful for physicians to know which patients are more likely to develop diabetes. With this in mind, we examined the metabolic profile of patients at increased risk of developing type 2 diabetes; this profile consisted of measurements of 250 metabolite concentrations and 780 gene expressions.
Because insulin resistance appears years before developing diabetes, first we divided the patients into tertiles based on their insulin resistance levels, with those in the lowest tertile exhibiting less resistance and those in the highest tertile having greater resistance. 
<br/>

We found that the patients in the highest tertile had a higher serum monounsaturated fatty acid ratio to total fatty acids and higher Glycoprotein acetyl (an inflammation marker), but less glycine (an amino acid) and acetate (a short-chain fatty acid), compared to those patients with less insulin resistance.
<br/>
<div align="center">
    <img src="Salmon\fatty.jpg" alt="fatty acids baseline"  width="500" height="600">
    <img src="Salmon\amino acids.jpg" alt="amino acids baseline"  width="400" height="600">
</div><br/>

Another interesting finding was that the leukocytes from patients in the highest tertile had higher expression of the gene CPT1A, which codes for a protein involved in fatty acid metabolism.
<br/>
<div align="center">
    <img src="Salmon\genes.jpg" alt="genes"  width="550" height="500">
</div><br/>

Finally, we wondered if any of these biomarkers could be altered by supplementation with salmon protein, because clinical studies have shown that eating fish has positive effects on preventing diabetes. Only the acetate concentration was increased in the patients with less insulin resistance, but not in patients in the highest tertile, suggesting that not all patients could benefit equally from nutritional interventions. <br/>
<div align="center">
    <img src="Salmon\amino acids2.jpg" alt="amino acids intervention"  width="450" height="650">
</div> <br/>
<br/>

---

#### 2.	Machine learning to predict the quality of white wine 

**CONTEXT**
<br/>
Wine industry has grown in the last decades. To continue this growth, the wine industry has invested in modern technology for making and selling wine. Wine certification and quality assessment are important in this context. Quality assessment is part of the certification process and can be used to improve the winemaking process, by identifying the most crucial factors in making a good wine, and to stratify wines into premium brands, useful for pricing.
<br/>

During certification, physicochemical variables are measured, and sensory tests are carried out. In the laboratory, routine physicochemical variables such as density, alcohol, pH, sulfur content. are measured, on the other hand, sensory tests are carried out by expert tasters. It is important to note that taste is the least understood human sense, so wine classification can be a challenging task.
<br/>

Data source [here](http://www3.dsi.uminho.pt/pcortez/wine/)

**OBJECTIVE**
<br/>
To facilitate the wine classification process, I trained a machine learning (ML) model to predict wine quality based on different physicochemical variables.
<br/>

**EXPLORATORY DATA ANALYSIS**
<br/>
The quality of wines ranges in a score from 4–8. This was an imbalanced classification task because there were more normal (6 and 7) wines than poor (4) and excellent ones (8). Originally, there were eleven physicochemical variables. <br/>
<div align="center">
    <img src="Wine\histogram.png" alt="histogram quality wine"  width="600" height="500">
</div><br/>

**MODEL TRAINING AND TESTING**
<br/>
The F1-score was used for tuning the ML model. The best model in cross validation was Random Forest. Below, you can see the confusion of how the wines in the test set were classified by this Random Forest algorithm.
<br/>

We see that most wines were classified correctly, or one category above or below, but not more. Thus, this ML model could aid wine tasters in assessing wine quality.
*Note: the confusion matrix is normalized by the ground true values, so it gives an idea of the precision of the classification in each quality category.
<br/>
<div align="center">
    <img src="Wine\matrix.png" alt="confusion matrix"  width="500" height="500">
</div>

**Note: the confusion matrix is normalized by the ground true values, so it gives an idea of the precision of the classification in each quality category.*

**FEATURE IMPORTANCE**
<br/>
The most important feature in wine quality was alcohol content, followed by the ratio of free sulfur to total sulfur and volatile acidity. 
<br/>

Winemakers could manipulate or modulate these variables to some degree to produce better wine. For example, alcohol content could be influenced by grape variety and temperature during fermentation.
<br/>
<div align="center">
    <img src="Wine\features.png" alt="feature importance"  width="700" height="500">
</div>

Check my complete code [here](https://github.com/francisco-canet/wine-ml)
<br/>

---
<details>
    <summary><h3> 🏄 My data science journey</h4></summary>
    <p> While I was working on my PhD research, I really enjoyed analyzing the data from my experiments, understanding the math behind the statistical test I was using, trying to see patterns, making hypotheses, and finally telling an interesting data-based story.
    I started to teach myself R with the idea of analyzing my data faster and making my work more efficient. In the meantime, I had the opportunity to work on a bioinformatics project where I met people enthusiastic about coding and statistics, which inspired me.
    At this point, I was very curious about machine learning and all the potential of these informatic tools in solving real-world problems, so I decided to enroll in a Data Science Bootcamp.
    That’s how I started my path into data science, and I’m happy to have made that decision.</p>
    </details>