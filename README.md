# Comment Toxicity Classifier: Deep Learning NLP Model

A multi-label deep learning model that detects and classifies toxic comments across six categories using bidirectional LSTM networks. Built on the Jigsaw Toxic Comment Classification dataset with a production-ready Gradio interface.

## 🎯 Project Overview

This system identifies harmful online content with high precision:
- **Dataset**: Jigsaw Toxic Comment Classification Challenge (160K+ labeled comments)
- **Algorithm**: Bidirectional LSTM with embedding layers
- **Classification**: 6 toxicity types (toxic, severe toxic, obscene, threat, insult, identity hate)
- **Performance**: ~81% precision, ~68% recall
- **Deployment**: Gradio web interface for real-time predictions

## ✨ Key Features

- **Multi-Label Classification**: Detects multiple toxicity types per comment simultaneously
- **Deep Contextual Understanding**: Bidirectional LSTM captures meaning in both directions
- **Real-Time Predictions**: Gradio UI for instant toxicity scoring on custom input
- **Production Metrics**: Precision, recall, and categorical accuracy tracked per batch
- **Interactive Demo**: Users can test any comment and receive detailed toxicity breakdown

## 📊 Example

![Screenshot (11)](https://github.com/ankushmehta123/comment-toxicity-model/assets/32393931/085b80a2-9c1b-4fe6-9679-edaf3ad6ca70)

## 🛠️ Tech Stack

- **TensorFlow / Keras** – Deep learning framework
- **LSTM & Embedding Layers** – NLP sequence modeling
- **Gradio** – Interactive web UI
- **Pandas & NumPy** – Data processing
- **Python 3.x**

## 📈 Model Architecture

1. **TextVectorization Layer**: Tokenizes comments into integer sequences
2. **Embedding Layer**: Converts tokens to dense vector representations
3. **Bidirectional LSTM**: Captures contextual patterns in both directions
4. **Dense Layers**: Feature extraction and non-linear transformations
5. **Sigmoid Output**: 6 units for multi-label binary classification

## 📊 Dataset

- **Source**: [Jigsaw Toxic Comment Classification Challenge (Kaggle)](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)
- **Size**: 160K+ labeled comments
- **Labels**: 6 binary toxicity categories
- **Challenge**: Imbalanced labels, nuanced toxicity definitions

## 💡 Skills Demonstrated

✓ NLP text preprocessing & vectorization  
✓ Deep learning architecture design (LSTM, bidirectional networks)  
✓ Multi-label classification  
✓ TensorFlow/Keras model building & training  
✓ Model evaluation (precision, recall, accuracy)  
✓ Gradio deployment for interactive predictions  
✓ End-to-end ML pipeline  

## 🚀 How to Use

1. Enter a comment in the Gradio interface
2. Click "Predict" to analyze toxicity
3. View real-time predictions for all 6 toxicity categories

## 📝 Model Performance

- **Precision**: ~81% (reliable positive predictions)
- **Recall**: ~68% (catches majority of toxic comments)
- **Note**: Performance improves with additional training epochs and fine-tuning

---

**Note**: This project demonstrates production-ready deep learning deployment with real-time inference capability. Ideal for content moderation, social platform safety, and online community management.
