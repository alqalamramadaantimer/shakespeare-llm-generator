# shakespeare-llm-generator
Mini GPT model trained on Shakespeare poetry using LSTM in PyTorch


# 🧠 Shakespeare-Style Text Generator using LSTM

This project demonstrates how to build and train a mini Large Language Model (LLM) using an LSTM architecture in PyTorch. The model is trained on Shakespeare's poetry and generates new, Shakespeare-style text. It also includes a readability checker to ensure the generated output is understandable English.

---

## 📌 Project Overview

- 🔍 **Topic**: Generative AI – Large Language Models (LLMs)
- 🧱 **Model**: LSTM-based mini GPT (trained from scratch)
- 🗃️ **Dataset**: `shakespeare_poetry.txt` – A custom file containing Shakespearean poems
- 🧠 **Goal**: Generate original poetic text in Shakespeare's style with fluent English output

---

## ⚙️ Technologies Used

- Python 3.10+
- PyTorch
- NumPy
- textstat (for readability scoring)
- Google Colab (for training & testing)

---

## 🚀 How to Run the Project

1. Clone this repository or open the code in Google Colab.
2. Upload your `shakespeare_poetry.txt` file to `/content/` in Colab.
3. Run all code cells step by step:
   - Train the model
   - Generate poetry
   - Check for English fluency using Flesch score
4. Try changing the `start_text` in the generation function!

---

## 🧪 Sample Output

Love is compare,
Stain to all nymphs, more lovely than a man,
More white and red than her cheeks;
And in some perfumes is theer she walks the star to the sun with purple-coloought ‘gins to woo hily har



> 📊 Readability Score: 69.63 (✅ readable)

---

## ✅ Features

- LSTM-based character-level text generation
- Custom dataset (Shakespeare poetry)
- English fluency checking using readability scores
- Fully trainable and modifiable in Colab

---

## 📂 File Structure

shakespeare-llm-generator/
├── main.ipynb <- Complete model and training code
├── shakespeare_poetry.txt <- Training dataset (you upload)
├── README.md <- This file


---

## 📈 Results & Evaluation

- Model trained on ~1000 steps using a small dataset
- Successfully generates poetic text with understandable structure
- Readability score ensures usable output (above 60 = good)

---

## 🧠 Future Improvements

- Switch from LSTM to Transformer (for more modern architecture)
- Add rhyme/verse structure detection
- Expand dataset (full Shakespeare works)

---

## 👨‍🎓 Project By

- Abdiwali bashir ahmed
- Course: Generative AI Final Project  
- Instructor: Prof. Dr. Murat Şimşek 
- OSTIM Technical University – 2025

---


