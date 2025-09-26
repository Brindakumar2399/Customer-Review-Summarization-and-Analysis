# 📝 Customer Review Analysis & Summarization

## 📌 Project Overview

This project analyzes **Amazon Fine Food Reviews** to extract insights about customer sentiment, product experience, and recurring themes. Using **abstractive summarization**, the project condenses long reviews into short, meaningful summaries, making it easier to understand large volumes of unstructured feedback.

The workflow combines **data preprocessing, exploratory analysis, and automated summarization** to demonstrate how raw customer feedback can be turned into structured insights.

---

## 📂 Repository Contents

* `Data_Pre_Processing.ipynb` → Prepares the dataset (cleaning, tokenization, embedding integration)
* `Summarization.ipynb` → Generates summaries, evaluates results, and provides examples
* `POSTER.pptx` → Visual summary of the project workflow and key findings

---

## 🔄 Data Analysis Workflow

1. **Data Preprocessing**

   * Cleaned text (removal of stopwords, special characters, duplicates)
   * Tokenization and vocabulary creation
   * Integration of **GloVe word embeddings** for semantic representation

2. **Exploratory Review Analysis**

   * Word frequency and sentiment distribution
   * Identification of recurring product themes (e.g., taste, delivery, packaging)
   * Length and structure of reviews

3. **Summarization**

   * Applied a **sequence-to-sequence model with attention** to generate summaries
   * Compared model summaries with original reviews to evaluate effectiveness

4. **Evaluation**

   * Measured conciseness (summary length vs. original)
   * Tracked coverage of key themes (e.g., product quality, service)
   * Reported performance metrics (loss, accuracy, ROUGE scores)

---

## 📊 Example

* **Input Review**:

  > “The pasta sauce tasted fresh but was far too salty. Delivery was quick, and packaging was good. Not sure I would repurchase.”

* **Generated Summary**:

  > “Fresh taste but too salty. Quick delivery and good packaging.”

---

## 📈 Key Performance Indicators (KPIs)

* **Data KPIs**

  * Total reviews analyzed
  * Vocabulary size and coverage
  * Distribution of sentiment (positive vs. negative reviews)

* **Summarization KPIs**

  * Average review length vs. average summary length
  * ROUGE-1, ROUGE-2, ROUGE-L scores (summary overlap with references)
  * Perplexity (model predictive quality)

* **Insight KPIs**

  * % of reviews mentioning delivery, packaging, or taste
  * Frequency of positive vs. negative product attributes
  * Time saved by auto-summarization (scaling manual review effort)

---

## 📈 Applications

* **Customer Feedback Analysis** → Quickly identify what customers like/dislike
* **Product Improvement** → Spot recurring issues across thousands of reviews
* **Business Intelligence** → Condense feedback for reporting & decision-making
* **Sentiment Tracking** → Monitor changes in satisfaction over time

---

## 🛠️ Tools & Libraries

* **Python** → For analysis and modeling
* **Pandas / NumPy** → data wrangling, cleaning, and transformation
* **Matplotlib** → exploratory data analysis and visualization
* **NLTK / spaCy** → natural language processing for text cleaning, tokenization, and sentiment cues
* **GloVe embeddings** → pre-trained word embeddings for semantic representation
* **TensorFlow / Keras** → sequence-to-sequence model with attention for summarization




