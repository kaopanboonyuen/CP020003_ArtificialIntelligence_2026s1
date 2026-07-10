<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=CP020003%20%E2%80%94%20Artificial%20Intelligence&fontSize=32&fontColor=ffffff&fontAlignY=40&desc=Khon%20Kaen%20University%20%C2%B7%202026%20Semester%201&descSize=16&descAlignY=62&animation=fadeIn" width="100%"/>

<br/>

<!-- BADGES -->
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=for-the-badge&logo=apache)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Colab](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com)
[![PyTorch](https://img.shields.io/badge/PyTorch-Enabled-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Ready-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![GitHub Stars](https://img.shields.io/github/stars/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1?style=for-the-badge&logo=github&color=FFD700)](https://github.com/kaopanboonyuen/CP020003_ArtificialIntelligence_2026s1)

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