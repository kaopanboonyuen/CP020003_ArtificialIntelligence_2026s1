<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=CP020003%20%E2%80%94%20Artificial%20Intelligence&fontSize=32&fontColor=ffffff&fontAlignY=40&desc=Khon%20Kaen%20University%20%C2%B7%202026%20Semester%201&descSize=16&descAlignY=62&animation=fadeIn" width="100%"/>

<br/>

<!-- BADGES -->
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=for-the-badge&logo=apache)](LICENSE)
<!-- [![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Colab](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com)
[![PyTorch](https://img.shields.io/badge/PyTorch-Enabled-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Ready-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![GitHub Stars](https://img.shields.io/github/stars/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1?style=for-the-badge&logo=github&color=FFD700)](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1) -->

<br/>

```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║    🤖  CP020003 · Artificial Intelligence · 2026 S1                      ║
║    🏫  Khon Kaen University                                              ║
║    🌱  Teerapong Panboonyuen (P'Kao)                                     ║
║    📧  teerapong.pa@chula.ac.th                                          ║
║                                                                          ║
║    "From data to intelligence — one model at a time."                    ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## 🌱 About the Instructor

<table>
<tr>
<td width="80">
<img src="https://avatars.githubusercontent.com/kaopanboonyuen" width="72" style="border-radius:50%"/>
</td>
<td>

**Teerapong Panboonyuen (P'Kao)**<br/>
Senior AI Research Scientist · MARSAIL Lab<br/>
Postdoctoral Fellow · Chulalongkorn University

📧 [teerapong.pa@chula.ac.th](mailto:teerapong.pa@chula.ac.th) &nbsp;|&nbsp; 🌐 [GitHub](https://github.com/kaopanboonyuen) &nbsp;|&nbsp; 📦 [Course Repo](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1)

</td>
</tr>
</table>

---

## 🧭 Course Overview

> 🌍 **Open for the world** — this repository is free and public. If you couldn't afford a university AI course, this is for you too.

This course introduces modern **Artificial Intelligence** using real-world datasets, industry-grade tools, and hands-on labs every single week. Students build from the ground up — from Python fundamentals to deep learning, computer vision, LLMs, and AI agents.

| 🎯 Final Outcome | 🛠️ Tools | 📦 Framework |
|:---|:---|:---|
| Build a complete AI solution — from raw data to a live demo | Python · Colab · Git | scikit-learn · PyTorch · HuggingFace |

---

## 🔁 Pre-Course: Python & Pandas Recap

> 📚 **Recommended before Week 1** — review Python, NumPy, and Pandas essentials used throughout the course.

| Resource | Link |
|:---|:---|
| 🐍 Python Recap Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Python101_Recap_Complete_Panboonyuen.ipynb) |

> *Covers*: Python syntax · NumPy arrays · Pandas DataFrames · data exploration · basic plotting

---

## 🗓️ Weekly Schedule

### 📅 Week 1 — Introduction to AI + Heart Attack Dataset

> 🎯 **Goal**: Understand the AI landscape, refresh Python & Pandas fundamentals, and perform your first real-world data analysis on a medical dataset.

#### 🛠️ Lab Activity: Heart Attack Dataset

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_1_intro_ai.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_1_intro_ai.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week1_InClass.ipynb) |
| 📄 Lab Instructions | [AI-Homework-Assignment-Week-1.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-1.pdf) |
| 📂 Dataset | [heart_kku_version.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/heart_kku_version.csv) |

> 💡 *Task*: Load the Heart Disease dataset with `pandas`. Explore distributions, handle missing values, engineer features, and answer analytical questions using real patient data.

<details>
<summary>📖 Dataset Dictionary — Heart Disease (KKU Version)</summary>

| Column | Description |
|:---|:---|
| `age` | Age of the patient |
| `sex` | Sex (1 = male, 0 = female) |
| `cp` | Chest pain type (0–3) |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true) |
| `restecg` | Resting ECG results (0, 1, 2) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = yes) |
| `oldpeak` | ST depression (exercise vs rest) |
| `slope` | Slope of peak exercise ST segment |
| `ca` | Number of major vessels (0–3, fluoroscopy) |
| `thal` | Thalassemia (0 = normal, 1 = fixed, 2 = reversable) |
| `target` | Heart disease (1 = yes, 0 = no) |

</details>

---

### 📅 Week 2 — Feature Engineering + Spotify Dataset

> 🎯 **Goal**: Learn how to transform raw data into meaningful features using real-world datasets. Explore traditional feature engineering, AI-assisted feature engineering, and prepare for modern Machine Learning and AI Hackathons.

#### 🛠️ In-Class Lab: Spotify Music Dataset

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_2_feature_engineering_spotify.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_2_feature_engineering_spotify.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week2_InClass.ipynb) |
| 📂 Dataset | [spotify-kku-dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/spotify-kku-dataset.csv) |

> 💡 **Lab Topics**
>
> - Load and inspect a real-world Spotify dataset using **Pandas**
> - Perform data cleaning and exploratory data analysis (EDA)
> - Create new features from existing attributes
> - Understand the difference between **raw features** and **engineered features**
> - Practice categorical, numerical, ranking, aggregation, and domain-specific feature engineering
> - Prepare datasets for Machine Learning models

<details>
<summary>📖 Dataset Dictionary — Spotify Music Dataset</summary>

| Column | Description |
|:---|:---|
| `track_id` | Unique Spotify track identifier |
| `artists` | Artist(s) performing the song |
| `album_name` | Album name |
| `track_name` | Song title |
| `popularity` | Spotify popularity score (0–100) |
| `duration_ms` | Song duration in milliseconds |
| `explicit` | Whether the song contains explicit lyrics |
| `danceability` | How suitable the song is for dancing (0–1) |
| `energy` | Perceived intensity and activity level (0–1) |
| `key` | Estimated musical key (0–11) |
| `loudness` | Average loudness (dB) |
| `mode` | Musical mode (1 = Major, 0 = Minor) |
| `speechiness` | Presence of spoken words (0–1) |
| `acousticness` | Confidence that the track is acoustic (0–1) |
| `instrumentalness` | Probability that the track contains no vocals (0–1) |
| `liveness` | Probability that the recording is performed live (0–1) |
| `valence` | Musical positiveness or happiness (0–1) |
| `tempo` | Estimated tempo (beats per minute) |
| `time_signature` | Number of beats per measure |
| `track_genre` | Music genre (e.g., Pop, Rock, Jazz, Hip-Hop) |

</details>

---

### 📝 Homework Assignment — Netflix Dataset

> 🎯 **Goal**: Apply feature engineering techniques independently on a real-world streaming platform dataset and prepare features suitable for Machine Learning applications.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-2.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-2.pdf) |
| 📂 Dataset | [netflix-kku-dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/netflix-kku-dataset.csv) |

> 💡 **Homework Tasks**
>
> - Explore and understand the Netflix dataset
> - Clean missing and inconsistent data
> - Engineer meaningful features from raw metadata
> - Create numerical, categorical, and text-based features
> - Visualize important insights
> - Explain how your engineered features could improve Machine Learning performance
> - Think like a Data Scientist: *Which features would you create if you were building Netflix's recommendation system?*

---

### 📅 Week 3 — Supervised Learning + Spotify & Netflix Datasets

> 🎯 **Goal**: Learn the full supervised learning workflow — from encoding and splitting data, to training classical ML models and a first deep learning model, to properly evaluating and comparing results.

#### 🛠️ In-Class Lab: Supervised Learning on the Spotify Dataset

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_3_supervised_learning.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_3_supervised_learning.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week3_InClass.ipynb) |
| 📂 Dataset | [spotify-kku-dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/spotify-kku-dataset.csv) *(same dataset as Week 2 — see data dictionary there)* |

> 💡 **Lab Topics**
>
> - Recap: feature engineering, plus a modern AI-powered feature using **Hugging Face zero-shot classification**
> - Convert strings to vectors: **One-Hot Encoding** vs **Label/Ordinal Encoding**, and when to use each
> - Perform a proper **stratified train/test split**
> - Train and compare classical ML models: **Decision Tree, Random Forest, XGBoost, Logistic Regression, SVM**
> - Get an intro to **Deep Learning**: what convolution is, and how a CNN learns features automatically
> - Compare **manual feature engineering (ML)** vs **automatic feature learning (DL)**
> - Evaluate models with **Accuracy, Precision, Recall, F1, ROC-AUC**, and the **Confusion Matrix** (TP/FP/FN/TN)
> - Discuss real-world trade-offs: when a **False Positive** matters more than a **False Negative** (and vice versa)
> - Perform **error analysis** to understand *why* a model makes mistakes

---

### 📝 Homework Assignment — Netflix Dataset

> 🎯 **Goal**: Build a complete, end-to-end supervised learning pipeline independently — choose a target variable, engineer and encode features, train multiple models, and evaluate them like a real Data Scientist would.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-3.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-3.pdf) |
| 📂 Dataset | [netflix-kku-dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/netflix-kku-dataset.csv) *(same dataset as Week 2 — see data dictionary there)* |

> 💡 **Homework Tasks**
>
> - Choose a target variable (e.g. predict `type`: Movie vs TV Show) and justify your choice
> - Engineer and encode features, choosing One-Hot vs Label encoding appropriately
> - Perform a stratified train/test split
> - Train and compare **at least 5 models** — a mix of classical ML and deep learning
> - Evaluate with Accuracy, Precision, Recall, F1, ROC-AUC, and a Confusion Matrix
> - Discuss which error (False Positive vs False Negative) matters more for your problem, and why
> - Perform error analysis on misclassified examples
> - **Bonus**: use an ML model or DL architecture we didn't cover in class, or bring in NLP on the `description` column

---

### 📅 Week 4 — DNA Classification + Supervised Learning

> 🎯 **Goal**: Learn how AI classifies biological DNA sequences using feature engineering, classical Machine Learning, and Deep Learning.

#### 🛠️ In-Class Lab: DNA Classification

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_4_dna_classification.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_4_dna_classification.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week4_InClass.ipynb) |
| 📄 Lab Instructions | [AI-Homework-Assignment-Week-4.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-4.pdf) |
| 📂 Dataset | [dna-synthetic.zip](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/dna-synthetic.zip) |

> 💡 **Lab Topics**
>
> - Explore DNA sequence data using Pandas
> - Engineer biological features (GC Content, nucleotide counts, k-mers)
> - Train Decision Tree, Random Forest, and XGBoost
> - Build CNN, LSTM, and GRU models with PyTorch
> - Compare classical ML vs Deep Learning
> - Evaluate using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix

<details>
<summary>🧬 Dataset Dictionary — DNA Classification</summary>

| Column | Description |
|:---|:---|
| `Sequence` | DNA sequence |
| `GC_Content` | GC percentage |
| `AT_Content` | AT percentage |
| `Sequence_Length` | DNA length |
| `Num_A`, `Num_T`, `Num_C`, `Num_G` | Nucleotide counts |
| `kmer_3_freq` | 3-mer frequency feature |
| `Mutation_Flag` | Mutation indicator |
| `Class_Label` | Human / Bacteria / Virus / Plant |
| `Disease_Risk` | Low / Medium / High |

</details>

---

### 📝 Homework Assignment — DNA Methylation Prediction

> 🎯 **Goal**: Apply the complete supervised learning workflow to a real DNA methylation dataset and predict methylation levels from genomic sequences.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-4.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-4.pdf) |
| 📂 Dataset | [dna-methylation.zip](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/dna-methylation.zip) |

> 💡 **Homework Tasks**
>
> - Perform EDA and data cleaning
> - Engineer biological sequence features
> - Encode genomic annotations
> - Train at least **5 ML/DL models**
> - Evaluate with Accuracy, Precision, Recall, F1, and Confusion Matrix
> - Perform error analysis and discuss biological significance
> - **Bonus:** Try LightGBM/CatBoost or predict continuous Beta values

<details>
<summary>🧬 Dataset Dictionary — DNA Methylation</summary>

| Column | Description |
|:---|:---|
| `Id` | CpG probe ID |
| `CHR` | Chromosome |
| `MAPINFO` | Genomic position |
| `UCSC_RefGene_Group` | Gene annotation |
| `Relation_to_UCSC_CpG_Island` | CpG island relation |
| `Regulatory_Feature_Group` | Regulatory annotation |
| `Forward_Sequence` | Local DNA sequence |
| `seq` | Long DNA sequence |
| `Beta` | DNA methylation level (target) |

</details>

---

### 📅 Week 5 — Unsupervised Learning + Retail Customer Segmentation

> 🎯 **Goal**: Learn the full unsupervised learning workflow — from EDA and RFM-style feature engineering, to scaling, PCA, and the Curse of Dimensionality, to clustering with K-Means and DBSCAN, to validating results and translating cluster numbers into profit-driving business personas.

#### 🛠️ In-Class Lab: Unsupervised Learning on the Retail Sales Dataset

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_5_unsupervised_learning.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_5_unsupervised_learning.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week5_InClass.ipynb) |
| 📂 Dataset | [retail_sales_dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/retail_sales_dataset.csv) *(1,000 retail transactions across Beauty, Clothing & Electronics)* |

> 💡 **Lab Topics**
>
> - Why **Unsupervised Learning** is the right tool when there's no ground-truth label — and how it differs from Weeks 1–4
> - Perform proper **EDA** on transactional retail data and spot trends before modeling anything
> - Engineer customer-level behavioral features (an **RFM-style feature set**: Recency, Frequency, Monetary) from raw transactions
> - Explain **why Feature Scaling (StandardScaler)** is not optional for distance-based clustering
> - Explain and **measure the Curse of Dimensionality** — why distance stops being meaningful in high dimensions
> - Use **PCA** both to fight the curse of dimensionality and to visualize clusters in 2D
> - Choose the right **K** using the Elbow Method, Silhouette Score, Davies–Bouldin Index, and Calinski–Harabasz Index
> - Understand **K-Means** at the algorithm level — including **Random Init vs. K-Means++**
> - Understand **DBSCAN** at the algorithm level — including `eps` and `min_samples`, and *why* it can succeed exactly where K-Means fails
> - Know **when** to reach for K-Means, DBSCAN, or a **deep-learning-based** clustering approach (autoencoder + clustering)
> - Meet two more essential unsupervised tools: **Hierarchical Clustering** and **Gaussian Mixture Models**
> - Most importantly: turn cluster numbers into **business personas** and concrete, profit-driving **actions** (with a full win-back campaign revenue estimate)

---

### 📝 Homework Assignment — Retail Insights Dataset (True RFM)

> 🎯 **Goal**: Apply the full unsupervised learning workflow independently on a real, order-level dataset with genuine repeat customers — build a true RFM feature set, choose and justify one clustering approach, validate it, and translate every cluster into a numbers-backed business persona and profit-maximizing action.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-5.docx](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-5.docx) |
| 📂 Dataset | [retail_insights_dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/retail_insights_dataset.csv) *(5,000 order-line records, 789 unique customers — see data dictionary below)* |

> 💡 **Homework Tasks**
>
> - Clean the currency columns, parse dates, handle the 2 missing values, and explore Order Total, Customer Type, Product Category, and Order Priority
> - Aggregate order-lines to the **customer level** and build a **true RFM feature set** (Recency, Frequency, Monetary) — real repeat customers finally make this possible
> - Add **at least 2 more behavioral features** of your own choosing (e.g. avg. discount %, avg. profit margin, dominant category, % Critical/High-priority orders)
> - Apply **StandardScaler** and explain in your own words why scaling isn't optional for K-Means/DBSCAN
> - Apply **PCA**, report explained variance, and visualize a 2D projection before and after clustering
> - Choose **ONE** clustering approach — K-Means, DBSCAN, or a deep-learning-based approach — and **justify the choice** using the Decision Guide criteria from class
> - Select K with at least 2 of the 4 metrics (or tune `eps`/`min_samples` with a k-distance plot if using DBSCAN)
> - Validate with **Silhouette Score** at minimum (Davies-Bouldin / Calinski-Harabasz / noise % where relevant)
> - **Business Interpretation (heaviest-weighted step)** — profile every cluster with real numbers and give each one a clear, memorable persona name
> - Recommend **at least one concrete, profit-maximizing action per cluster**, with a quantified, clearly-labeled revenue estimate — exactly like the in-class win-back campaign
> - Conclude: which cluster is most valuable, which is most at-risk of churning, and which one you'd target first with a limited budget
> - **Bonus**: try an algorithm not covered hands-on in class (Spectral Clustering, HDBSCAN, Mean Shift, GMM), compare two approaches side by side, build a loyalty/churn-risk score, quantify what-if profit for 2+ clusters, or build the autoencoder + clustering pipeline as an alternative model

<details>
<summary>🛍️ Dataset Dictionary — Retail Insights (Homework)</summary>

| Column | Description |
|:---|:---|
| `Order No` | Unique order-line identifier, e.g. `4293-1` |
| `Order Date` | Date the order was placed (`DD-MM-YYYY`) |
| `Customer Name` | Customer who placed the order — repeats across rows (789 unique customers / 5,000 order lines) |
| `Address` / `City` / `State` | Delivery location — Sydney, NSW or Melbourne, VIC |
| `Customer Type` | Consumer / Corporate / Home Office / Small Business |
| `Account Manager` | Staff member managing the account |
| `Order Priority` | Critical / High / Medium / Low / Not Specified |
| `Product Name` / `Product Category` / `Product Container` | What was purchased — category is Office Supplies, Technology, or Furniture |
| `Ship Mode` / `Ship Date` | How and when the order shipped |
| `Cost Price` / `Retail Price` / `Profit Margin` | Unit-level currency strings (e.g. `"$156.50"`) — strip `$` and commas before converting to float |
| `Order Quantity` | Units in this order line |
| `Sub Total` / `Discount %` / `Discount $` / `Order Total` / `Shipping Cost` / `Total` | Full pricing breakdown, also stored as currency/percent strings — `Order Total`/`Total` is the natural Monetary feature |

> ⚠️ **Grading emphasis**: most marks are earned in the *business interpretation* steps — a clear, numbers-backed persona and action per cluster beats a technically perfect pipeline with generic descriptions. The clearest, best-explained submission earns **+1% extra credit**.

</details>

---

## 📚 References & Credits

| Resource | Link |
|:---------|:-----|
| 🤗 Hugging Face | [huggingface.co/learn](https://huggingface.co/learn) |
| 🔗 LangChain Docs | [docs.langchain.com](https://docs.langchain.com/) |
| 👁️ CS231n — Stanford Vision | [cs231n.stanford.edu](http://cs231n.stanford.edu/) |
| 📖 Deep Learning with Python | [Manning](https://www.manning.com/books/deep-learning-with-python) |
| 🔬 Google Colab | [colab.research.google.com](https://colab.research.google.com) |
| 💬 Anthropic Claude | [anthropic.com](https://www.anthropic.com) |
| 🧠 OpenAI ChatGPT | [chat.openai.com](https://chat.openai.com) |
| 🔥 PyTorch | [pytorch.org](https://pytorch.org) |
| 📊 Kaggle | [kaggle.com](https://www.kaggle.com) |
| 🌐 CS224N — Stanford NLP | [web.stanford.edu/class/cs224n](https://web.stanford.edu/class/cs224n/) |

---

## 🙌 Acknowledgements

This course is inspired by **CS231n**, the **Hugging Face** open-source community, **PyTorch** team, **Kaggle** community notebooks, and every student who believes that AI education should be accessible to all.

<div align="center">

---

```
╔════════════════════════════════════════════════════════════╗
║                                                            ║
║   Made for everyone, everywhere — not just for one place   ║
║                                                            ║
║   For the builders of intelligence, the learners of data,  ║
║   and those shaping the future of AI systems.              ║
║                                                            ║
║   From curiosity to creation — one model at a time.        ║
║                                                            ║
╚════════════════════════════════════════════════════════════╝
```

[![Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square)](LICENSE)
[![KKU](https://img.shields.io/badge/University-Khon%20Kaen%20University-darkgreen?style=flat-square)](https://kku.ac.th)
[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square)](https://github.com/kaopanboonyuen)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

</div>