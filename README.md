#  Applying NLP for topic modelling & customer sentiment analysis

The aim of this project was to process and analyse the customer reviews of a Multinational Gym provider using NLP and LLM-based pipelines to pinpoint key areas for improvements, propose actionable solutions for addressing the prevalent problems and improve customer satisfaction.


## 🔹 Data

Over 20,000 customer reviews collected annually from Google Reviews and Trustpilot.


## 🔹 Methodology

* Performed the necessary text preprocessing and EDA, identified and visualised the most frequently used words in the reviews.

* Applied **BERTopic** for topic modelling, keeping track of gym locations, to locate common topics and words in the negative reviews.

* Aggregated the datasets on locations and extracted the top 30 venues with the most negative reviews.

* Used the built-in visualisation functions in BERTopic to cluster and visually represent the topics and words in these reviews, thereby identifying specific themes.

* Performed **emotion analysis** to determine the emotions associated with the reviews.

* Filtered the angry reviews and applied BERTopic to discover prevalent topics and words in these negative reviews.

* Summarised the outputs into actionable insights.

* Leveraged the multi-purpose capability of **Microsoft's Phi-4-mini-instruct model** <https://huggingface.co/microsoft/Phi-4-mini-instruct> to compare and interpret the identified dominant topics.

* Utilised the created pipeline with additional prompting to generate additional improvement suggestions, based on the main topics identified from the negative reviews.

* Conducted a comparative analysis between BERTopic and **Gensim’s LDA model** to validate topic coherence and ensure methodological robustness.


## 🔹 Tools
- Python, NumPy, Pandas
- Matplotlib, Seaborn, Scikit-learn
- NLTK, WordCloud
- BERTopic, Bert-based-uncased-emotion, Phi-4
- PyTorch & HuggingFace tools: transformers, datasets, evaluate
- Gensim & pyLDavis


## 🔹 Results and Findings

* Key negative themes: poor equipment maintenance, hygiene, unhelpful staff, and contract cancellation issues making up over 65% of negative feedback.

* Emotion analysis revealed anger and frustration dominating negative reviews, particularly in large urban gyms.

* Actionable improvements included:
  * Enhance staff and customer support training
  * Devise flexible membership policies
  * Improve equipment upgrade schedules
  * Redesign schedule of offered classes for improved engagement and attendance

---
 <img width="1142" height="646" alt="image" src="https://github.com/user-attachments/assets/c99de6c5-f17e-4e27-a805-6cfa8df371e7" />

