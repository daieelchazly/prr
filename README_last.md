# Deep Learning Intrusion Detection System (DL-IDS)

This project implements a Deep Learning-based Intrusion Detection System (IDS) using the NSL-KDD dataset. The system is capable of:
- Preprocessing and training on the NSL-KDD dataset
- Evaluating model performance
- Capturing live network packets using Scapy
- Classifying packets as normal or attack
- Logging malicious activity
- Defending the model using adversarial robustness techniques from the Adversarial Robustness Toolbox (ART)

## 📁 Project Structure

DL-IDS/
├── dataset/
│ └── NSL-KDD.zip # NSL-KDD dataset zip file
├── model/
│ └── model.pth # Trained PyTorch model (saved automatically)
├── logs/
│ └── live_log.txt # Log of live-detected malicious packets
├── intrusion_detection.py # Main code to preprocess, train, evaluate, and run live IDS
├── requirements.txt # List of required packages
└── README.md # Project documentation (this file)


##  Project Structure

The project contains a main Jupyter Notebook:

last-try: Includes the full implementation of the GPT-2 model, training it on the TinyStories dataset, and generating tex

---

## Features

- Custom tokenizer for text processing
-architecture implemented 
- Supports TinyStories dataset or similar text data
- Training loop with loss reporting
- Text generation using temperature scaling

---

### . Load the dataset

Place the file roneneldan/TinyStories" in the appropriate path as referenced in the notebook.

---
 ### . Generate Text

After training, you can generate new text samples by setting a prompt and temperature value.
---
##  Model Details


- **Embedding Layer**: Represents tokens and their positions
- **Transformer Blocks**: Includes multi-head self-attention and feedforward layers
- **Output**: Predicts the next token

---

## Example Output
--- Story ---
once upon a time, was a little girl named Lily. She loved to play outside in the sky. One day, she found a rock on the ground. It was very weird and wanted to see what it was over. She wanted to do with it, but she started to pull it.

Lily was sad as she was inside and had taken it. She asked her mom what she was wrong and told her that she could do. She was a funny trophy she could not find it.
---
