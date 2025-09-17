# Deep Learning – RNNs, LSTMs, Attention, and Sequence Models

Implementations and analyses of recurrent and attention-based architectures in PyTorch, applied to tasks such as sentiment analysis, sequence-to-sequence modeling, and attention visualization.

---

## 📂 Repository Structure
```
├── Deep-Learning-RNNs-LSTMs-Attention-and-Sequence-Models.ipynb   # Jupyter Notebook with code & experiments
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```
## 📖 Contents
## 1. RNN and LSTM Computations
- Step-by-step manual calculations of hidden states.
- Exploration of vanishing gradients and memory retention.
- Conceptual interpretation of hidden state dynamics.

## 2. Architecture Analysis
- Comparison of RNN, LSTM, GRU, Bi-RNN, and Transformer models.
- Key mathematical operations and computational complexity.
- Strengths and weaknesses in capturing long-range dependencies.

## 3. PyTorch Implementations
- Custom RNN and LSTM cells from scratch.
- Scaled dot-product self-attention module.
- Sequence-to-sequence (Seq2Seq) model with attention.
- Extensions: bidirectional layers, GRUs, masking, and multi-head attention.

## 4. Applications
- Sentiment Analysis: Bidirectional LSTM on IMDB dataset.
- Text Generation: GRU-based sequence modeling.
- Attention Visualization: Heatmap of self-attention weights on a sentence.

## ⚙️ Requirements
To run the notebook, install the following dependencies:

```
pip install -r requirements.txt
```
(Alternatively, install manually:)
```
pip install torch torchvision matplotlib numpy
```
## 🚀 How to Run

Clone this repository:
```
git clone https://github.com/<your-username>/deep-sequence-models.git
cd deep-sequence-models
```
Open the Jupyter Notebook:
```
jupyter notebook deeplearning-assignment-2.ipynb
```
Run the cells step by step to reproduce the results.

## 📊 Highlights

- Manual derivations of RNN and LSTM state updates.
- Implementations of sequence modeling components from scratch.
- Real-world application: IMDB sentiment classification with BiLSTM.
- Visual demonstration of self-attention capturing long-range dependencies.

## ✨ Acknowledgments

- This project was developed during my MSc Digital Business Engineering program.
- Code and explanations were developed independently with references to online resources and textbooks.
- Some parts were refined with the help of ChatGPT for clarity and readability, always critically evaluated and adapted to maintain originality.
