# 📝 Customer Review Summarization and Analysis

## 📌 Project Overview

This project develops an **abstractive text summarization model** to condense **Amazon Fine Food Reviews** into concise summaries. Instead of extracting sentences, the model generates new phrases that capture the meaning of the original review, helping users quickly understand customer opinions.

The project demonstrates a full pipeline from **data preprocessing** to **model training and evaluation**, showcasing how unstructured customer feedback can be systematically analyzed.

---

## 📂 Repository Contents

* `Data_Pre_Processing.ipynb` → Cleans and tokenizes raw reviews, builds vocabulary, integrates GloVe embeddings
* `Summarization.ipynb` → Defines and trains the Seq2Seq model with attention, evaluates results, generates summaries
* `POSTER.pptx` → Presentation summarizing the workflow, methodology, and findings

---

## 🔄 Workflow

1. **Data Preprocessing**

   * Cleaned and tokenized Amazon Fine Food Reviews dataset
   * Built vocabulary and mapped words to **GloVe embeddings**
   * Batched and organized data for efficient training

2. **Model Architecture**

   * **Sequence-to-Sequence (Seq2Seq)** with bi-directional **LSTM encoder**
   * **LSTM decoder** with **local attention** for contextual abstraction

3. **Training & Optimization**

   * **Adam optimizer** with gradient clipping
   * **Dropout** for regularization
   * **Early stopping** to avoid overfitting
   * **Cross-entropy loss with L2 regularization**

4. **Evaluation**

   * Metrics: loss, accuracy, validation performance
   * Model checkpointing for best-performing runs

---

## 📊 Example

* **Input Review**:

  > “The pasta sauce tasted fresh but was far too salty. Delivery was quick, and packaging was good. Not sure I would repurchase.”

* **Generated Summary**:

  > “Fresh taste but too salty. Quick delivery and good packaging.”

---

## 📈 Applications

* Summarizing large volumes of **customer reviews**
* Extracting **product feedback** efficiently
* Enabling quick scanning of sentiment and recurring issues

---

## 🛠️ Tools & Libraries

* **Python**
* **TensorFlow / Keras**
* **NLTK / spaCy**
* **GloVe embeddings**

---

## 👥 Team

Developed by:

* Brinda Kumar
* Kishan Terdal

Under the guidance of **Prof. Lu Xiao**

---

