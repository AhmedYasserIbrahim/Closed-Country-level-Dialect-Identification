# Arabic Dialect Identification – MARBERT (18 Classes)

## 📌 Overview  
This project tackles the challenge of **Arabic dialect identification** on social media (specifically Twitter). Arabic is highly diverse, with many country-level dialects that differ significantly from Modern Standard Arabic (MSA). Correctly classifying dialects is an important step for **NLP applications such as sentiment analysis, machine translation, and conversational agents**.  

We developed and fine-tuned a **MARBERT transformer model** to classify **18 different Arabic dialects** from short tweets.  

---

## 🎯 Objectives  
- Build a robust NLP system that can distinguish between 18 country-level Arabic dialects.  
- Benchmark the model against a shared-task leaderboard to evaluate its global performance.  
- Contribute to advancing Arabic NLP research in under-resourced languages and dialects.  

---

## ⚙️ Methodology  
- **Model Backbone:** Fine-tuned **MARBERT**, a transformer pretrained on billions of Arabic tweets.  
- **Data:** Tweets annotated with 18 dialect labels (e.g., Egyptian, Gulf, Levantine, Sudanese, etc.).  
- **Approach:**  
  - Preprocessing tweets (cleaning, normalization).  
  - Applying automation and prompt-engineering strategies for better coverage.  
  - Fine-tuning MARBERT on the classification task.  
- **Evaluation Metrics:** Macro F1, Accuracy, Precision, Recall.  

---

## 📊 Results  
Our model achieved:  

- **F1 Score:** 0.842  
- **Accuracy:** 0.841  
- **Precision:** 0.845  
- **Recall:** 0.840  

This placed us **4th on the official shared-task leaderboard**, demonstrating competitive performance globally despite a later submission.  

---

## 🔑 Key Insights  
- Arabic dialects are often highly similar, making the classification task challenging.  
- The strongest confusions were between **neighboring dialects** (e.g., Levant vs. Gulf).  
- Using MARBERT significantly outperformed traditional models for dialect detection.  
- The system can be extended to downstream applications like **opinion mining** or **content moderation**.  

---

## 🏆 Recognition  
- Ranked **Top-4 worldwide** on the shared task leaderboard.  
- Open-sourced code and methodology to encourage reproducibility and further research in **Arabic NLP**.  
