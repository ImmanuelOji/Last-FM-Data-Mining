# Last-FM Data Mining

## Project Overview
This project analyzes music listening behavior using the Last.fm dataset. The goal is to understand whether patterns in listening behavior are driven by popularity or reflect meaningful user behavior.

We apply multiple data mining techniques to uncover patterns in how users listen to music.

---

## Techniques Used

### Course Techniques
- Frequent Itemset Mining (FP-Growth)
- Association Rule Mining

### Beyond-Course Technique
- Sequential Pattern Mining (PrefixSpan)

---

## Key Questions

- Do highly popular artists dominate frequent itemsets?
- Can association rules generate meaningful music recommendations?
- Do sequential patterns reveal behavior not captured by itemsets?

---

## Key Findings

- Frequent itemsets are dominated by popular artists (popularity bias)
- Association rules show strong relationships (high lift), not just popularity
- Sequential patterns reveal structured listening behavior (order matters)

Example:
Duran Duran → New Order → Depeche Mode

---

## Dataset
- Last.fm HetRec 2011 Dataset
- User listening data with artist interactions

---

## How to Run  
1. Run the Jupyter notebook

---

## Why This Matters

Understanding listening sequences enables better recommendation systems by moving beyond popularity-based suggestions toward behavior-driven personalization.

---

## Author
Immanuel Oji
