# Hello 👋, I'm Salamot

I'm a Data Science student at the University of Texas at Dallas (B.S., expected Spring 2027) and a current AI/ML Fellow with Break Through Tech at Cornell Tech. I work across the full machine learning lifecycle, from framing a business problem and auditing a dataset for bias, through modeling, to communicating results to technical and non-technical audiences alike.

## What I'm doing now

- Completing the Break Through Tech AI/ML Fellowship, a year-long, industry-sponsored applied ML program with mentorship from practicing data scientists and engineers
- Building a chatbot for UT Dallas students with the Artificial Intelligence Society (AskTemoc), contributing to system design, database integration, and iterative development within a cross-functional team

## Skills

- **Languages and tools:** Python, R, SQL (PostgreSQL), Microsoft Excel, Power BI, HTML, CSS (Tailwind CSS)
- **Libraries:** NumPy, pandas, scikit-learn, Keras, Tidyverse
- **Machine learning:** regression, classification, decision trees and ensemble methods, feature selection and regularization, clustering and dimensionality reduction

## Featured projects

### [AI Anime Watch Planner](https://github.com/Sal-Fakoya/ai-anime-watch-planner) (Solo Project)
[Demo video](#) — the app requires Databricks workspace login, so a walkthrough video is linked here instead of a live link

An agentic recommendation system for group anime watch-planning, built end-to-end on Databricks: a Spark pipeline ingests and cleans data from the AniList API into a Postgres-backed Lakebase store, a Vector Search index enables semantic retrieval over synopses and tags, and a LinUCB contextual bandit re-ranks recommendations from a group's accumulated ratings. A LangGraph agent with five tools (semantic search, structured filtering, comparison, watchlist management, and rating logging) handles multi-turn conversations with persistent memory, deployed as a Databricks App with a chat interface. Debugged and resolved a full production deployment chain, including service-principal authentication for Vector Search, Lakebase secret management, and schema migrations for a live, evolving dataset.

### [Income Classification: A Comparative Study of Predictive Models](https://github.com/Sal-Fakoya/Income-Classification-A-Comparative-Study-of-Predictive-Models) (Solo Project)
[Live presentation](https://sal-fakoya.github.io/Income-Classification-A-Comparative-Study-of-Predictive-Models/)

Benchmarked Logistic Regression, Decision Tree, KNN, and a neural network on 32,561 census records to test whether model complexity pays off for income based credit risk estimation. Corrected a 76/24 class imbalance and recommended Logistic Regression (90.5% AUC) over the neural network, since the neural network's edge in accuracy came at the cost of interpretability that a regulated credit context actually requires. Shipped as an interactive presentation with separate business and technical narratives.

### [Coarse and Fine Grained Dog Breed Discovery](https://github.com/Sal-Fakoya/Dog-Breed-Discovery-Research-Project-CS-4375-Machine-Learning) (Group Project)
[Live presentation](https://sal-fakoya.github.io/Dog-Breed-Discovery-Research-Project-CS-4375-Machine-Learning/)

Benchmarked ResNet-18, VGG-16, ViT-B/16, and ViT-L/16 as frozen feature extractors across four datasets to test whether pretrained models can recover dog breed structure with zero label supervision. Vision Transformers reached a 50% improvement in Adjusted Rand Index over the strongest CNN baseline, isolating global average pooling as the real limitation of the convolutional models. Background removal and lighting degradation experiments across 18+ comparisons further showed that segmentation preprocessing consistently hurt clustering quality, despite the common assumption that it would help.

### [Credit Card Balance Prediction](https://github.com/Sal-Fakoya/credit-MLR) (Solo Project)

Predicted credit card balances with 95% R-squared using regression on demographic and financial data, optimized through feature engineering, outlier removal, and multi-model comparison with 10-fold cross validation, and packaged as a reproducible R Markdown pipeline with visual diagnostics.

### SQL Playground (Solo Project)

A cross-database web application compatible with SQLite and MySQL, with query validation and error handling built in (dynamic alerts, input validation).

## A bit more about me

I'm a highly curious, knowledge-driven person outside of the classroom too. Right now I'm into Re:Zero, and being this deep into anime has me wanting to eventually build my own recommendation system, one that can hold its own against Netflix, Crunchyroll, or Amazon Prime. I've also spent time in customer facing and hands-on roles outside of data science, as a cashier and as a design intern, which taught me a lot about working with people under different paces and pressures.

## Connect

- [LinkedIn](https://www.linkedin.com/in/salamot-fakoya-650325224/)
- [Email](mailto:salamot.fakoya@utdallas.edu)
