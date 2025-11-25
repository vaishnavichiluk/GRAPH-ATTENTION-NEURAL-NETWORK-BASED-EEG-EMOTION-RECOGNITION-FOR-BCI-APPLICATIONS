🌐 Graph Attention Neural Network (GAT)–Based EEG Emotion Recognition
For Brain–Computer Interface (BCI) Applications

This project explores how brain activity can be used to understand human emotions. Using EEG (electroencephalogram) signals and Graph Attention Neural Networks (GAT), the model learns how different brain-signal channels interact with each other and uses those relationships to classify emotional states.

The goal is to build an efficient and intelligent emotion-recognition system that can support real-world Brain–Computer Interface (BCI) applications such as mental-health monitoring, adaptive interfaces, neuro-feedback systems, and more.

🔍 Project Overview

Traditional deep learning models often treat EEG channels independently, missing the meaningful relationships between electrodes.
This project solves that by:

Representing EEG electrodes as nodes in a graph

Connecting them using spatial and functional relationships

Using Graph Attention Networks (GAT) to learn which channels matter most

Classifying emotional states more accurately using learned attention weights

This graph-based approach helps the model understand brain activity in a more natural and structured way.

🧠 Key Features

Converts raw EEG data into a graph structure

Applies GAT layers to capture inter-channel relationships

Performs multi-class emotion classification

Includes data preprocessing, graph construction, feature extraction, and model training

Visualizes EEG signals and performance metrics

🛠️ Technologies Used:

Programming	Python (Jupyter Notebook)
Deep Learning	PyTorch
EEG Processing	MNE
Data Handling	NumPy, Pandas
Visualization	Matplotlib

🚀 How It Works

Load EEG data (raw or preprocessed)

Build graph representation

Each electrode → node

Connectivity → edges

Extract features from each EEG channel

Pass graph into GAT model, where attention scores identify important connections

Predict emotional state (e.g., happy, calm, stressed)

Evaluate accuracy using validation metrics

📊 Results

The GAT-based approach showed improved performance compared to simple CNN/RNN methods, especially in capturing spatial dependencies between EEG electrodes.

(You can replace this with your actual accuracy/F1 score later.)

💡 Inspiration

This project was inspired by the growing intersection of neuroscience, deep learning, and affective computing. Understanding emotions from EEG signals has promising applications in mental health, virtual reality, adaptive learning, gaming, and neuro-interface systems.

🤝 Contributions

Feel free to open an issue or submit a pull request if you'd like to contribute or improve the model.
