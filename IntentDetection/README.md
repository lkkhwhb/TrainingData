# Intent Detection Data

**Author:** Bhargav Barman  
**Contact:** lkkhwhb@gmail.com  
**GitHub:** [lkkhwhb](https://github.com/lkkhwhb)  

---

## Overview
The *Intent Detection Data* repository provides a curated collection of natural language utterances labeled with intent categories.  
This dataset is designed to support training and evaluation of neural network models for intent recognition tasks, making it useful for research, experimentation, and educational purposes.  

> **Note:** This dataset is **intended for very small-scale NLP tasks only**. It is not suitable for production-grade conversational systems or large-scale language modeling.  

---

## Dataset Summary
- **Total Examples:** 5,992
- **Training Examples:** 5,402  
- **Validation Examples:** 590
- **Number of Classes:** 10  
- **Duplicates:** None  
- **Data Cleaned & Verified:** Yes  
- **Language:** English (ENG)  
- **Intended Use:** Small/basic intent detection models  

---

## File Structure
- **Training Data:** `./Tdata.json`  
- **Validation Data:** `./Vdata.json`  

Both files are in JSON format and contain text samples with corresponding intent labels.  

---

## Class Distribution

### Training Set
| Intent Category         | Count |
|--------------------------|-------|
| Greetings               | 550   |
| Proposal                | 475   |
| Insult                  | 533   |
| Question                | 540   |
| Order                   | 519   |
| Request                 | 456   |
| Farewell                | 499   |
| Apology                 | 541   |
| Negation / Disagreement | 573   |
| Confusion / Uncertainty | 716   |

### Validation Set
Uniform distribution across classes:  
59 examples per intent category.  

---

## Usage Guidelines
1. Clone the repository:  
   ```bash
   git clone https://github.com/lkkhwhb/TrainingData.git
   ```

2. Load the dataset files (`Tdata.json`, `Vdata.json`) into your pipeline.
3. Apply preprocessing (e.g., tokenization, embeddings) according to your model’s requirements.
4. Train and validate your intent detection model using the provided splits.

---

## Recommended Applications

* Intent recognition in small dialogue systems
* Benchmarking lightweight NLP models
* Educational use in ML/NLP courses
* Rapid prototyping of chatbots and assistants

---

## License & Disclaimer

This dataset is released under the **MIT License**.
It is provided **“as is” without warranty of any kind**, and is intended only for **research, learning, and small-scale experimentation**.

By using this dataset, you agree that it is **not designed for high-stakes or production-grade NLP applications**.

---

## Citation

If you use this dataset, please cite it as:

```
Barman, B. (2025). Intent Detection Data: A Clean and Structured Dataset for Training Neural Networks in Natural Language Intent Classification. GitHub. https://github.com/lkkhwhb
```
