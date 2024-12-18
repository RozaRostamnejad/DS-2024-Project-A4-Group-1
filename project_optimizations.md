PROJECT OPTIMIZATIONS AND FUTURE DIRECTIONS

This document outlines key optimization opportunities and future directions identified during and after the development of this project. These reflections are informed by feedback from our more experienced peers during the poster presentation, ongoing self-assessment, and critical analysis of our project workflow! 

---

*1. DATA BALANCING STRATEGY*

**Current Approach:** We used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the classes in our dataset.  
**Optimization Opportunity:** Considering feedback from more experienced students in the poster session, we recognize that an alternative approach, such as **undersampling**, could have been explored. Undersampling may reduce computational load and avoid potential pitfalls of generating synthetic samples that might distort the natural class distributions.

---

*2. MODEL TUNING*

**Current Approach:** We applied and tuned **Random Forest** and **Gradient Boosting** classifiers to achieve optimal predictive performance.  
**Optimization Opportunity:** We acknowledge that additional hyperparameter tuning, especially for the **Gradient Boosting model**, could enhance model performance. Future efforts would focus on fine-tuning hyperparameters such as learning rate, depth, and number of estimators.

---

*3. ASSOCIATION RULE MINING*

**Current Approach:** We aimed to apply **Apriori** for pattern mining and association discovery. However, challenges in implementation and time constraints hindered its successful completion.  
**Optimization Opportunity:** We aim to resolve these technical challenges in future iterations, as we believe **Apriori-based association rules** could yield valuable insights and improve the interpretability of our model's decision-making process.

---

*ACKNOWLEDGEMENTS*

These reflections were shaped by insights gained from neighboring poster presenters with more experience in data science. Their constructive feedback provided valuable perspectives, reinforcing the potential for improvement in our project approach.
