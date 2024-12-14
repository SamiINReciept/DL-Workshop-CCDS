# Deep Learning Workshop Repository

Welcome to the repository for the **2-Day Deep Learning Workshop** that I recently completed. This repository contains the resources, code, and materials provided during the workshop, along with some of my own modifications and additions. 🎉📚✨

---

## Repository Structure 🎯📁🔍

### **1. Day-wise Workshop Folders**
Each day’s folder contains Colab notebook files with different deep learning tasks: 🧠📓💻

#### **Day 1**

- **Image Classification with CNN:** Implementation of Convolutional Neural Networks for image classification.
- **Image Classification with VGG16:** Transfer learning using the pre-trained VGG16 model for image classification.
- **Emotion Recognition with LSTM:** Implementation of LSTM networks for emotion recognition tasks using: 1-hot encoding

#### **Day 2**

- **Emotion Recognition with LSTM:** Implementation of LSTM networks for emotion recognition tasks using: Word2Vec embedding
- **Fine-tuning BERT for Emotion Recognition:** Code to fine-tune a BERT model for emotion recognition tasks.

---

### **2. Materials Folder**

This folder includes: 📄📂✨

- **Workshop Slides**: All the slides presented during the workshop.
- **Workshop Contents List**: A comprehensive list of the topics covered during the two days.

---

### **3. Modified Codes Folder**

This folder contains: 🛠️🖋️🚀

- My custom modifications to the provided codes, reflecting improvements, enhancements, or experiments I conducted based on workshop learnings.

---

### **4. To-Do Requirements Files**

Two separate files detailing requirements for: 📝✔️📌

1. **Task-Specific Adjustments**:
   - Freezing convolutional layers and ensuring non-trainable parameters are properly handled.
   - Adding precision and recall calculations alongside F1 scores.
   - Including train loss in plots when using Weights and Biases (WandB).

2. **BERT Fine-Tuning**:
   - Identifying the most attentive tokens for each class in the test dataset by leveraging BERT's attention scores.
   - Aggregating and ranking token attention scores to determine their importance for specific classes.
   - Implementing a new method in the `BERT_FineTuning` class to extract and process attention-based insights for tokens.

---

### **5. Python Lightning Command Line Instruction File**

A file with command-line instructions for running PyTorch Lightning tasks effectively. ⚡🐍💻

---

## How to Use This Repository 🧑‍💻🛠️📖

1. Clone the repository:

   ```bash
   git clone https://github.com/SamiINReciept/deep-learning-workshop.git
   ```

2. Navigate to the specific folders to explore notebooks, materials, or modified codes.

---

## Key Learnings from the Workshop 🌟📚💡

- Advanced techniques for image classification using CNNs and pre-trained models.
- Emotion recognition with LSTM networks leveraging various embedding techniques.
- Fine-tuning transformer-based models like BERT for NLP tasks.
- Practical implementation of PyTorch Lightning for streamlined deep learning experiments.

---

## Acknowledgments 🤝🎓👏

Special thanks to the workshop organizers at [CCDS.AI](https://ccds.ai/) for their detailed explanations and valuable insights into deep learning concepts.

---

## Contributions and Feedback 🌟💻✨

Feel free to explore, use, and modify the resources in this repository. Contributions, suggestions, and feedback are always welcome! Your input helps improve and expand this repository further.

---

## License 📜🔓💡

This repository is licensed under the [MIT License](LICENSE).

