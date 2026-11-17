# XAI Project (2026/27) - P7: Attention and Input Attribution

This repository contains the code, data, and deliverables for our Explainable AI (XAI) project, carried out as part of the University of Padua course.

## 👥 Team

* **Arthur Louette** (Team Referee)
* **Aleš Manuel Papáček**

## 📌 Project Description

The **P7 (Attention and Input Attribution)** project explores the mechanistic interpretability of models based on the Transformer architecture. The objective is to investigate whether attention weights identify the same evidence (tokens) as input attribution methods.

We compare head-averaged attention, attention rollout, and Integrated Gradients. Our evaluation relies on perturbing specific tokens and performing targeted attention head ablation to measure the actual changes in the model's predictions.

## 📂 Repository Structure

* `data/`: Contains the public dataset used for training and evaluation.
* `notebooks/`: Contains the Jupyter Notebook files detailing our experiments and visualizations.
* `report/`: Contains the LaTeX source code and PDF version of our final report (limited to 5 pages).
* `presentation/`: Contains the slides for our 15–20-minute oral presentation.
* `requirements.txt`: Lists the Python dependencies required to run the code.

## 🚀 How to Reproduce the Experiments

To ensure the reproducibility of our experiments, please follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Arthvrr/Explainable-AI-Project.git
   cd repository-name
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv xai-env
   source xai-env/bin/activate  # On Mac/Linux
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebook:** Open the notebook files using Jupyter or VS Code and execute the cells sequentially. The pre-trained model will be automatically downloaded from Hugging Face during the first execution.

## 🤖 Use of Artificial Intelligence Tools

In accordance with the project guidelines, the use of AI tools (LLMs) was permitted and is documented here. Coding assistants (e.g., Gemini, Claude) were used throughout this project to:

- Speed up the implementation of standard Python functions (data processing and pandas manipulation).
- Generate the basic structure of Matplotlib/Seaborn visualizations.

All experimental decisions, the selection of standard evaluation metrics, and the critical analysis of the results are strictly the result of our own human contribution. Every AI-generated component was manually reviewed and validated.

## ⚖️ Assessment and Deliverables

This project was designed to meet the course assessment criteria:

- **Understanding:** Clear explanations of the XAI concepts and methods used.
- **Experimental Quality:** Justification of the implementation, evaluation metrics, and interpretation of the results.
- **Communication:** Concise presentation and critical discussion of the limitations of our explanations.