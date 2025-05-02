# Rubric Generator using Fine-Tuned ML Model

This repository contains a machine learning model designed to **generate grading rubrics** based on a given question and a sample answer. The model has been fine-tuned on custom data and implemented in a Jupyter Notebook.

## 📁 Repository Structure

- `rubric_generator.ipynb`: Jupyter notebook containing the code to load and use the fine-tuned model to generate rubrics.
- `converted_finetune_rubric_data.txt`: Text file containing the data used to fine-tune the model. This file follows the format required for supervised fine-tuning (e.g., question-answer pairs with associated rubric).

## 🧠 Model Functionality

The model takes two inputs:
1. **Question** – The original question or prompt for which a rubric is needed.
2. **Sample Answer** – A sample response to the question.

Based on this input, it outputs a **detailed rubric** that can be used for evaluation or instructional purposes.

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- OpenAI or HuggingFace-compatible ML libraries (e.g., `transformers`, `openai`, etc.)
- `pandas`, `json`, or any required dependencies (see the notebook for details)

### Running the Notebook

1. Clone the repository:

```bash
git clone https://github.com/yourusername/rubric-generator.git
cd rubric-generator
````

2. Open the notebook:

```bash
jupyter notebook rubric_generator.ipynb
```

3. Run the cells to load the model and generate a rubric based on your input.

## 📊 Fine-Tuning Data

The file `converted_finetune_rubric_data.txt` contains the dataset used for fine-tuning the model. This data includes:

* Structured examples of questions,
* Sample answers,
* Corresponding rubrics.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Author**: Mrigank Singh
**Contact**: Mriganksingh005@gmail.com
