# Last-FM Data Mining

## Project Overview
This project analyzes music listening behavior using the Last.fm dataset. The goal is to understand whether patterns in listening data are driven by popularity bias or reflect meaningful user behavior.

We apply multiple data mining techniques to uncover relationships between artists and explore how users transition between them.

👉 The main deliverable is: **main_notebook.ipynb**

🎥 Project Video: [https://youtu.be/TshxJtPsyu8]

---

## Research Questions

- Do highly popular artists dominate frequent itemsets, and how does this affect pattern diversity?
- Can association rules be used to generate meaningful music recommendations?
- How do sequential patterns differ from frequent itemsets in capturing user listening behavior?

---

## Techniques Used

### Course Techniques
- Frequent Itemset Mining (FP-Growth)
- Association Rule Mining

### Beyond-Course Technique
- Sequential Pattern Mining (PrefixSpan)

---

## Dataset

- **Name:** Last.fm HetRec 2011 Dataset  
- **Source:** https://files.grouplens.org/datasets/hetrec2011/  
- **Files Used:**
  - `user_artists.dat`
  - `artists.dat`

### Preprocessing
- Grouped data by user to create transaction baskets
- Converted data to one-hot encoding for FP-Growth
- Created user-level sequences for sequential pattern mining
- Sampled subset for computational feasibility

---

## How to Reproduce

This project was developed using Jupyter Notebook.

### Steps:
1. Download dataset from the link above  
2. Place data files in `data/` folder  
4. Run the notebook:
     main_notebook.ipynb
---

## Key Dependencies

- Python 3.12.13 
- pandas  
- mlxtend  
- prefixspan  
- matplotlib  

(Full environment available in `requirements.txt`)

---

## Repository Structure

Last-FM-Data-Mining/
│
├── main_notebook.ipynb # Final curated notebook (START HERE)
├── checkpoints/
│ ├── checkpoint_1.ipynb
│ └── checkpoint_2.ipynb
├── data/ # Datasets
├── requirements.txt
└── README.md

---

## Results Summary

- Frequent itemsets are dominated by popular artists → strong popularity bias  
- Association rules show meaningful relationships (high lift), not just popularity  
- Sequential patterns reveal structured listening behavior and order of consumption  

Example:
Duran Duran → New Order → Depeche Mode

👉 Key Insight:  
User listening behavior is structured and sequential, not random.  
This has strong implications for improving recommendation systems.

---

## Author
Immanuel Oji
