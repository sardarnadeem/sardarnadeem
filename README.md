# Hi, I'm Nadeem 👋

I am an Artificial Intelligence and Data Science graduate based in London.  
I am interested in Machine Learning, Deep Learning, Generative AI, RAG, Agentic AI, MCP, Surrogate Models, Computer Vision, NLP, and real-world AI applications.

## About Me

- 🎓 Artificial Intelligence and Data Science graduate
- 💻 Interested in building practical AI and data science projects
- 🤖 Exploring Generative AI, RAG, Agentic AI, MCP, NLP, and Computer Vision
- 📊 Enjoy working with real-world datasets and solving practical problems

## Skills and Interests

- Python
- Machine Learning
- Deep Learning
- Data Science
- SQL
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- PyTorch
- Computer Vision
- Natural Language Processing
- Generative AI
- Retrieval-Augmented Generation
- Agentic AI
- Model Context Protocol
- AI Surrogate Modelling
- Physics-based Machine Learning

## Projects

### 1. Second-Hand Car Price Prediction and Pattern Analysis

A machine learning project based on around 55,000 UK second-hand car sales records.  
The aim was to predict car prices and discover useful patterns in the UK used car market.

**Key Features:**
- Predicted car prices using supervised machine learning models
- Compared Linear Regression, Random Forest, and Artificial Neural Network models
- Used clustering to discover natural car groups based on age, mileage, and other features

**Technologies Used:** Python, Pandas, NumPy, Scikit-learn, Machine Learning, ANN, Random Forest, K-Means, Agglomerative Clustering

### 2. Handwritten Digit Recognition using CNN

A deep learning project using the MNIST dataset to classify handwritten digits from 0 to 9.  
The project used a Convolutional Neural Network to learn image features and classify unseen digit images.

**Key Features:**
- Used the MNIST dataset with 70,000 grayscale images
- Normalised pixel values between 0 and 1
- Reshaped images into 28 × 28 × 1 format for CNN input
- Applied dropout and early stopping to reduce overfitting
- Used data augmentation such as rotation, shift, and zoom

**Model Architecture:**
- Conv2D layer with 32 filters
- MaxPooling2D
- Conv2D layer with 64 filters
- MaxPooling2D
- Dropout
- Dense layer with 128 units
- Softmax output layer for 10 digit classes

**Results:**
- Achieved over 90% accuracy
- Improved generalisation using dropout and early stopping

**Technologies Used:** Python, TensorFlow, Keras, CNN, Deep Learning, Image Classification, MNIST

### 3. Road Accident Data Analysis using SQL

A data analysis project using a UK road accident database.  
The aim was to explore accident, casualty, vehicle, and location data using SQL queries.

**Key Features:**
- Connected to a SQLite accident database
- Explored database tables and schemas
- Used SQL queries to extract useful road safety insights
- Joined multiple tables including Accident, Casualty, Vehicle, and LSOA
- Filtered accident records for Kingston upon Hull

**Technologies Used:** SQL, SQLite, Python, Pandas, Data Analysis, Database Joins

### 4. Road Accident Pattern Mining and Forecasting

A data mining and forecasting project focused on UK road accident patterns.  
The project used Apriori association rule mining and SARIMA time series forecasting.

**Key Features:**
- Analysed accident severity patterns using association rules
- Converted accident features into categorical labels
- Used one-hot encoding to create transactions
- Applied Apriori algorithm with support threshold of 0.01
- Generated rules using lift score
- Forecasted future accident trends using SARIMA

**Technologies Used:** Python, Pandas, Apriori, Association Rule Mining, SARIMA, Time Series Forecasting, Data Mining

### 5. Named Entity Recognition using BiLSTM and BERT

An NLP project focused on Named Entity Recognition.  
The goal was to identify entities such as people, locations, and organisations from text.

**Key Features:**
- Used the PAN-X dataset from the XTREME benchmark
- Predicted entity labels such as PER, LOC, and ORG
- Compared BiLSTM and BERT-based models
- Used BIO tagging for entity labels
- Applied tokenisation, padding, label encoding, and dropout
- Used class weights and O-token dropout to handle imbalance

**Models Used:**
- BiLSTM with embedding layer and softmax output
- BERT using bert-base-cased with a linear classifier

**Results:**
- BiLSTM achieved around 80% Micro F1 Score
- BERT achieved around 90% Micro F1 Score

**Technologies Used:** Python, NLP, BERT, BiLSTM, Transformers, PyTorch, Named Entity Recognition, Tokenisation, Deep Learning

### 6. Long-Term Multi-Person Action Recognition and Tracking

A computer vision project focused on detecting, tracking, and recognising actions of multiple people in video.  
The goal was to maintain person identities across frames and predict human actions over time.

**Key Features:**
- Used a pre-trained action recognition model instead of training from scratch
- Used ResNet-101 backbone with SlowFast-style architecture
- Processed short video clips of 64 frames
- Used YOLOv3 for person detection
- Used tracking methods to assign IDs to people across frames
- Added an IdentityBank module to improve long-term identity tracking

**Main Components:**
- Person detection using YOLOv3
- Tracking using motion and appearance matching
- Kalman Filter for motion prediction
- ReID features for appearance comparison
- Hungarian Matching for person assignment
- IdentityBank for storing and matching global person IDs
- Action recognition using ResNet-101 and AIA module

**Goal:**
To recognise human actions while keeping the same identity for each person across video frames, even during occlusion or re-entry.

**Technologies Used:** Python, Computer Vision, YOLOv3, DeepSORT-style Tracking, ResNet-101, SlowFast, AIA, Action Recognition, Identity Tracking, Deep Learning

### 7. Wing Aerodynamics Surrogate Model

A physics-based machine learning project focused on predicting aerodynamic behaviour from 3D wing geometry data.  
The model uses mesh-based wing data from STL files to predict lift coefficient and drag coefficient more efficiently than traditional simulation methods.

**Key Features:**
- Used 3D wing geometry data from STL mesh files
- Built graph-based input features from vertices, faces, and edges
- Predicted lift coefficient and drag coefficient
- Applied machine learning as a faster alternative to traditional simulation

**Technologies Used:** Python, PyTorch, DGL, MeshGraphNet, STL files, Machine Learning, Deep Learning, Surrogate Modelling, Physics-based AI

## Future Projects

I am currently exploring projects related to:

- Generative AI applications
- RAG-based chatbots
- Agentic AI systems
- MCP-based AI tools
- NLP applications
- Computer Vision
- AI for engineering and science
- Physics-based surrogate modelling

## Connect With Me

- GitHub: https://github.com/sardarnadeem
- LinkedIn: www.linkedin.com/in/nadeem-rehman-b21604108
