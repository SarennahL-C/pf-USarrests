# US Arrests — Principal Component Analysis and Unsupervised Clustering

This project applies **Principal Component Analysis (PCA)** and **unsupervised clustering techniques** to explore patterns in violent crime statistics across the United States. Using arrest data for assault, murder, and rape alongside urban population levels, the analysis investigates underlying structure within the dataset and how states group based on crime-related characteristics.

The project emphasises **careful preprocessing, interpretability, and disciplined analytical reasoning**, reflecting a professional approach to unsupervised machine learning.

![The left shows a black and white images of a man holding his hands together. He is wearing handcuffs and has a sorrowful posture. On the right is a map showing the American States. Some of the states are coloured red, some blue and others white.](handcuffs-and-state-clsuters.jpg)

Criminal in handcuffs image from www.rawpixel.com. Map created with www.mapchart.net. 

---

### What’s in this repository

- **Jupyter Notebook:** full PCA and clustering analysis (`unsupervised_task.ipynb`)  
- **Images:** biplots, clustering visualisations, reviewer feedback  
- **Source data:** US Arrests dataset (`UsArrests.csv`)  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

### Project Context

This capstone task focused on exploring relationships between different categories of violent crime across U.S. states in 1973. The dataset contains arrest rates per 100,000 residents for murder, assault, and rape, alongside the percentage of the population living in urban areas. The objective was to reduce dimensionality, identify dominant sources of variation, and examine whether meaningful groupings of states could be identified using unsupervised learning techniques.

---

### Approach Overview

- Data exploration and preprocessing  
- Feature scaling and preparation for PCA  
- Correlation analysis and interpretation  
- Principal Component Analysis and component selection  
- Biplot visualisation and interpretation  
- Application of two clustering techniques  
- Comparative analysis of cluster structure  

---

### Key Insights / Findings

- PCA successfully transformed correlated crime variables into independent components.  
- The first principal components captured the dominant variation in violent crime rates across states.  
- Biplot visualisation revealed clear directional relationships between crime types and component loadings.  
- Clustering methods identified groups of states with similar crime profiles, though boundaries were not absolute.  
- Results reinforced that unsupervised learning reveals structural similarity, not categorical truth.  

---

### Endorsement

Reviewer feedback highlighted the **high quality and professionalism of the submission**, with particular praise for:

- A **comprehensive and well-structured analytical process**  
- Strong **preprocessing and data cleaning foundations**  
- **Modular, readable code** supported by clear documentation  
- Informative interpretations that provided context for the reader  

Overall feedback described the work as **outstanding**, concluding: *“Well done, Sarennah! You nailed this task!”*

---

### Skills Demonstrated

**Analysis**
- Exploratory data analysis  
- Correlation analysis and interpretation  

**Modelling**
- Principal Component Analysis (PCA)  
- Unsupervised clustering techniques  

**Evaluation**
- Component selection and justification  
- Cluster interpretation and comparison  

**Tools**
- Python  
- pandas  
- scikit-learn  
- matplotlib / seaborn  
- Jupyter Notebook  

---

### Requirements

Install the required Python dependencies with `requirements.txt`

---

### Why this project belongs in my portfolio
This project demonstrates my ability to apply unsupervised machine learning techniques thoughtfully and interpret results with appropriate caution. Rather than seeking a single “correct” outcome, the analysis focuses on understanding structure, variance, and similarity within complex data. 

