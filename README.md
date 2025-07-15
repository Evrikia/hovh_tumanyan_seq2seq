
# 📝 Seq2Seq Dataset: Hovhannes Tumanyan's Poems

This dataset contains sentence pairs extracted from the poetic works of **Hovhannes Tumanyan**, one of the most celebrated Armenian poets. It is formatted for training **sequence-to-sequence (Seq2Seq)** models for tasks such as:

* Text generation
* Dialogue modeling
* Style imitation

## 📂 Dataset Structure

The dataset is provided as a `.csv` file with two columns:

| input\_sentence | target\_sentence |
| --------------- | ---------------- |
| Line 1 of poem  | Line 2 of poem   |
| Line 2 of poem  | Line 3 of poem   |
| ...             | ...              |

Each row represents a sentence pair where the **input** is a line from a Tumanyan poem and the **target** is the **next consecutive line**. This format is ideal for training models to learn the flow, rhythm, and style of Tumanyan’s poetic language.


## 🧠 Use Cases

* **Train a chatbot** that speaks in Tumanyan’s style.
* **Generate poetry** line-by-line.
* **Fine-tune transformer models** (e.g., GPT, T5, BART) on Armenian poetic structure.
* Build educational tools for **Armenian language learning**.

## 📜 Source

All poems are in the public domain and attributed to **Hovhannes Tumanyan (1869–1923)**. Texts were cleaned and segmented line by line to maintain poetic continuity.

## 💡 Recommended Preprocessing

* Normalize punctuation (e.g., Armenian vs. Latin commas).
* Tokenize properly if training tokenizer-based models (e.g., HuggingFace tokenizers).
* Optionally, remove very short lines to avoid low-content samples.

## 📘 License

**MIT**
---
