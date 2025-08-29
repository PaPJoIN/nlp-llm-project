#  Applying NLP for topic modelling & customer sentiment analysis

Case Context: The aim of this project was to process and analyse the customer reviews of a Multinational Gym provider using NLP and LLM pipelines to pinpoint key areas of improvements, propose actionable solutions for addressing the prevalent problems and improve customer satisfaction.


## 🔹 Data

Yearly customer reviews extracted from Google and Trustpilot.


## 🔹 Tools and Methodology

* Performed the necessary text preprocessing and EDA, identified and visualised the most frequently used words in the reviews.

* Applied **BERTopic** for topic modelling, keeping track of gym locations, to locate common topics and words in the negative reviews.

* Aggregated the datasets on locations and extracted the top 30 venues with the most negative reviews.

* Used the built-in visualisation functions in BERTopic to cluster and visually represent the topics and words in these reviews, thereby identifying specific themes.

* Performed **emotion analysis** to determine the emotions associated with the reviews.

* Filtered the angry reviews and applied BERTopic to discover prevalent topics and words being discussed in these negative reviews.

* Summarised the outputs into actionable insights.

* Leveraged the multi-purpose capability of **Microsoft's Phi-4-mini-instruct model** <https://huggingface.co/microsoft/Phi-4-mini-instruct> to compare the identified top topics.

* Utilised additional prompting to generate further improvement suggestions for the client, based on the top topics identified from the negative reviews.

* Conducted a comparison of BERTopic with **Gensim’s LDA model** to validate the results and ensure robustness.


## 🔹 Tools Used
- Python, NumPy, Pandas
- Matplotlib, Seaborn, Scikit-learn
- NLTK, WordCloud
- BERTopic, Bert-based-uncased-emotion, Phi-4
- PyTorch & HuggingFace tools: transformers, datasets, evaluate
- Gensim & pyLDavis


## 🔹 Results and Findings

* Key negative themes: poor equipment maintenance, hygiene, unhelpful staff, and contract cancellation issues making up over 65% of complaints.

* Emotion analysis revealed anger and frustration dominating negative reviews, particularly in large urban gyms.

* Suggested improvements: better customer support training, flexible membership policies, and equipment upgrade schedules.
