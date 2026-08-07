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
> - Explore and preprocess a real-world Spotify dataset, perform EDA, engineer meaningful features across different types, understand raw vs. engineered features, and prepare data for Machine Learning models.

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
> - Explore and clean the Netflix dataset, engineer meaningful numerical, categorical, and text features, visualize key insights, and explain how feature engineering can improve ML performance while thinking like a data scientist building a recommendation system.

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
> - Review feature engineering and explore AI-powered features with zero-shot classification, covering encoding methods, stratified data splitting, classical ML and deep learning models, feature engineering vs automatic feature learning, model evaluation with key metrics, and error analysis with real-world trade-offs.

---

### 📝 Homework Assignment — Netflix Dataset

> 🎯 **Goal**: Build a complete, end-to-end supervised learning pipeline independently — choose a target variable, engineer and encode features, train multiple models, and evaluate them like a real Data Scientist would.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-3.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-3.pdf) |
| 📂 Dataset | [netflix-kku-dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/netflix-kku-dataset.csv) *(same dataset as Week 2 — see data dictionary there)* |

> 💡 **Homework Tasks**
>
> - Define and justify a prediction target, engineer and encode features, train and compare multiple ML and deep learning models, evaluate performance with classification metrics, analyze errors and their real-world impact, and explore advanced approaches such as new models or NLP-based features.

---

### 📅 Week 4 — DNA Classification + Supervised Learning

> 🎯 **Goal**: Learn how AI classifies biological DNA sequences using feature engineering, classical Machine Learning, and Deep Learning.

#### 🛠️ In-Class Lab: DNA Classification

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_4_dna_classification.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_4_dna_classification.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week4_InClass.ipynb) |
| 📂 Dataset | [dna-synthetic.zip](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/dna-synthetic.zip) |

> 💡 **Lab Topics**
>
> - Explore and engineer DNA sequence features, train classical ML and deep learning models (Decision Tree, Random Forest, XGBoost, CNN, LSTM, and GRU), compare approaches, and evaluate performance using key classification metrics.

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
> - Perform biological data preprocessing, feature engineering, ML/DL modeling, evaluation, and biological interpretation, with bonus exploration of advanced models or continuous Beta prediction.

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
| 📂 Dataset | [retail_sales_dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/retail_sales_dataset.csv) |

> 💡 **Lab Topics**
>
> - Use unsupervised learning to cluster customers and transform data into meaningful business strategies.

---

### 📅 Week 6 — Recommender Systems: From "People Also Bought" to Deep Learning

> 🎯 **Goal**: Build a full family of recommenders — popularity-based, user- and item-based collaborative filtering, matrix factorization (SVD), content-based filtering, and Neural Collaborative Filtering — while learning sparsity, cold-start handling, leakage-safe train/test splitting, and how to turn Precision@K/Recall@K/Coverage into a production deployment decision.

#### 🛠️ In-Class Lab: Recommender Systems on the Book-Crossing Dataset

| Resource | Link |
|:---|:---|
| 🧠 Lecture Slide | [lecture_6_recommender_systems.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/slides/lecture_6_recommender_systems.pdf) |
| 🧪 Colab Notebook | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/code/Week6_InClass.ipynb) |
| 📂 Dataset | [Book-Crossing (Books.csv + Ratings.csv)](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/book-crossing.zip) |

> 💡 **Lab Topics**
>
> - The recommender systems "family tree" (popularity → content-based → collaborative filtering → matrix factorization → deep learning) and when each fits
> - EDA on rating distributions & matrix sparsity; leakage-safe train/test splitting *before* building any similarity matrix
> - Popularity-based (Bayesian-average), User-based CF, Item-based CF, SVD matrix factorization, Content-based filtering, and Neural Collaborative Filtering (NCF)
> - Evaluation beyond RMSE — Precision@K, Recall@K, Coverage — and translating cluster/segment results into a business action + revenue estimate

---

### 📝 Homework Assignment — E-Commerce Implicit Recommenders (No Ready-Made Rating Matrix)

> 🎯 **Goal**: Unlike class, this week there's **no shared rating table** — just a customer profile table and a product catalog table. Design your own implicit customer–product interaction signal from `Browsing_History`/`Purchase_History`, then build and rigorously compare **≥ 2 techniques** (Popularity, CF, SVD, Content-Based, or Deep Learning) on the same held-out split, handle cold start, and back a deployment recommendation with real Precision@K/Recall@K/Coverage numbers.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-6.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-6.pdf) |
| 📂 Dataset | [e-commerce.zip](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/e-commerce.zip) |

> 💡 **Homework Tasks**
>
> - Parse list-formatted `Browsing_History`/`Purchase_History` columns and build a weighted implicit Customer × Product interaction matrix (purchase = 1.0, browse-only = 0.3)
> - Pick and justify ≥ 2 techniques, train/test on the same leakage-safe split, and generate top-N recommendations for one customer per `Customer_Segment`
> - Evaluate & compare techniques side-by-side (Precision@K / Recall@K / Coverage, or RMSE), handle cold-start users/products explicitly, and quantify business impact per segment

<details>
<summary>🛒 Dataset Dictionary — E-Commerce (Homework)</summary>

| Column | Description |
|:---|:---|
| `Customer_ID` | Unique customer identifier, e.g. `C1000` (10,000 customers) |
| `Age` / `Gender` / `Location` | Demographics — Location is one of 5 Indian cities |
| `Browsing_History` | Python-list string of browsed categories, e.g. `"['Books','Fashion']"` — weak implicit signal |
| `Purchase_History` | Python-list string of purchased items — the strongest implicit signal, treat like last week's explicit ratings |
| `Customer_Segment` | New Visitor / Occasional Shopper / Frequent Buyer — used for cold-start framing |
| `Avg_Order_Value` / `Holiday` / `Season` | Spend and context fields |
| `Product_ID` | Unique product identifier, e.g. `P2000` (10,000 products) |
| `Category` / `Subcategory` | Category is one of 6 values (Fashion, Beauty, Electronics, Books, Home Decor, Fitness) — shared vocabulary with customer history, which links the two tables |
| `Price` / `Brand` | List price and one of 4 brand codes |
| `Product_Rating` / `Average_Rating_of_Similar_Products` | Roughly 1–5 scale ratings |
| `Customer_Review_Sentiment_Score` | 0–1 sentiment score from review text |
| `Similar_Product_List` | Python-list string of related products — ready-made item–item signal |
| `Probability_of_Recommendation` | 0–1 pseudo-label, usable as a regression target for a ranking model |

> ⚠️ **Grading emphasis**: getting one recommender running is not enough. Most marks come from Steps 6–9 — a rigorous, honest head-to-head comparison on held-out data and a clear, numbers-backed deployment recommendation per customer segment beats five techniques bolted on with only a vague sentence of comparison.

</details>

---

### 📝 Homework Assignment — Retail Insights Dataset (True RFM)

> 🎯 **Goal**: Apply the full unsupervised learning workflow independently on a real, order-level dataset with genuine repeat customers — build a true RFM feature set, choose and justify one clustering approach, validate it, and translate every cluster into a numbers-backed business persona and profit-maximizing action.

| Resource | Link |
|:---|:---|
| 📄 Assignment | [AI-Homework-Assignment-Week-5.pdf](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/assignments/AI-Homework-Assignment-Week-5.pdf) |
| 📂 Dataset | [retail_insights_dataset.csv](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1/blob/main/dataset/retail_insights_dataset.csv) |

> 💡 **Homework Tasks**
>
> - Clean retail data, build RFM and behavioral features, apply clustering with proper evaluation, interpret customer personas, and recommend data-driven business strategies with measurable impact.

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