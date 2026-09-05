# Assignment 1 – GPT-2 Text Generation and Bias Analysis

## 📌 Overview

This assignment explores **Generative AI using the GPT-2 language model**. The project demonstrates how GPT-2 can generate text from prompts and investigates how different prompts and temperature settings influence generated outputs.

The assignment was implemented using **Python and Google Colab** with the Hugging Face Transformers library.

## 🎯 Objectives

* Load and use the GPT-2 language model for text generation.
* Create prompts related to different professions.
* Generate multiple outputs for each profession.
* Analyze possible patterns and biases in the generated text.
* Examine gender-related word patterns in generated outputs.
* Compare text generation at different temperature values.
* Save generated results in CSV format.

## 🛠️ Tools & Technologies

* Python
* Google Colab
* PyTorch
* Hugging Face Transformers
* GPT-2
* Pandas

## 🤖 Model Used

**GPT-2**

Model: `openai-community/gpt2`

The GPT-2 model is loaded using the Hugging Face Transformers library and used to generate text based on user-defined prompts.

## 📋 Tasks Performed

### Task 1 – GPT-2 Setup

The required Python libraries were installed and imported. The GPT-2 tokenizer and language model were loaded successfully.

### Task 2 – Text Generation

A text generation function was created using GPT-2 with parameters such as:

* Maximum new tokens: 50
* Temperature
* Top-K sampling
* Top-P sampling
* Repetition penalty

### Task 3 – Profession-Based Prompts

Prompts were created for the following professions:

* Doctor
* Nurse
* Business Executive
* Scientist
* Police Officer
* Criminal

Five outputs were generated for each profession.

### Task 4 – Bias Analysis

The generated outputs were collected into a Pandas DataFrame.

The analysis considers patterns related to:

* Gender
* Age
* Clothing
* Professional appearance
* Language and tone

Gender-related words such as `he`, `she`, `man`, `woman`, `father`, and `mother` were also considered for basic word-count analysis.

### Task 5 – Custom Prompt Generation

A custom story prompt was created:

> "When Maya opened the old wooden box, she discovered a small device that could predict events twenty-four hours before they happened."

The prompt was generated using different temperature values:

* 0.5
* 0.9
* 1.2

The outputs were compared to observe how temperature affects text generation.

### Task 6 – High Temperature Experiment

An additional generation experiment was performed using a temperature of **2.0** to observe highly varied text generation.

## 📊 Results

The generated outputs were stored in a Pandas DataFrame and exported as:

`GPT2_Bias_Results.csv`

The experiments demonstrate that changing the temperature can affect the creativity and variability of GPT-2's generated text.

## 📂 Files

```text
Assignment-1/
│
├── genai_assigment_1.ipynb
├── GPT2_Bias_Results.csv
└── README.md
```

## 🎓 Learning Outcomes

After completing this assignment, I learned:

* How to use a pre-trained Generative AI model.
* How GPT-2 generates text from prompts.
* How to work with Hugging Face Transformers.
* How sampling parameters affect generated text.
* How to organize generated outputs using Pandas.
* How to explore potential patterns and biases in AI-generated content.
* How to save and present Generative AI experiment results.

## ✅ Conclusion

This assignment provided practical experience with **Generative AI and language models** using GPT-2. The experiments showed how prompts, sampling parameters, and temperature influence generated text. The profession-based generation also provided an opportunity to examine patterns and potential biases in AI-generated content.

## 👨‍💻 Author

**[Your Name]**

Generative AI / Artificial Intelligence Student
