## Artificial Intelligence
- **AI Agent**: an AI system that plans and takes multi-step actions with tools to complete a goal
    - **Agentic Browser**: a web browser with a built-in AI agent that can navigate and act on pages for you
    - **AI Coding Agent**: an AI agent that plans, writes, tests, and submits code changes with limited supervision
    - **MCP (Model Context Protocol)**: an open standard for connecting AI models to external tools and data sources
    - **Multi-Agent Orchestration**: coordinating several specialized AI agents that divide and hand off work        
- **AI Alignment**: making AI systems behave according to human intentions and values
- **AI Coding Assistant**: an editor plugin that suggests and completes code using AI
- **AI Research Assistant**: an AI tool that searches, reads, and summarizes sources to answer questions
- **AI Tutor**: an AI tool that adapts explanations and practice to help a learner understand material
- **Computer Vision**: teaching computers to interpret and understand images and video
    - **NeRF (Neural Radiance Fields)**: neural networks that reconstruct 3D scenes from a set of 2D images
    - **OCR (Optical Character Recognition)**: converting images of text into machine-readable text
- **Deepfake**: synthetic media that swaps or fabricates a person's face or voice using AI
- **Generative AI**: AI that creates new text, images, audio, video, or code from prompts
    - **AI Image Generation**: creating or editing images from text prompts
        - **Diffusion Model**: a generative model that creates images by learning to reverse a gradual noising process
    - **AI Music Generation**: creating songs, vocals, or background music from prompts
    - **AI Video Generation**: creating video clips or films from text, image, or video prompts
    - **AI Voice Generation**: synthesizing lifelike speech or cloning voices from text
- **LLM (Large Language Model)**: a neural network trained on huge text corpora to understand and generate language
    - **AI Chatbot**: a conversational interface for chatting with an LLM
    - **Fine-Tuning**: further training a pretrained model on task-specific data
        - **LoRA (Low-Rank Adaptation)**: a parameter-efficient fine-tuning method that trains small low-rank matrices
    - **Inference**: running a trained model to generate predictions or outputs
        - **Local LLM Inference**: running a language model on your own hardware instead of through a hosted API
    - **LLM Evaluation**: measuring model quality, accuracy, latency, and safety with repeatable tests
    - **LLM Framework**: a library for building apps that chain LLM calls, tools, and data sources
    - **Open-Weight Model**: a model whose trained weights are publicly released for anyone to run or fine-tune
    - **Pretraining**: training a model from scratch on a large unlabeled corpus
- **Model Hub**: a platform for sharing and downloading pretrained models, datasets, and demos
- **NLP (Natural Language Processing)**: teaching computers to understand, process, and generate human language
- **Prompt Engineering**: designing and refining model inputs to get accurate, useful outputs
- **RAG (Retrieval-Augmented Generation)**: improving LLM answers by retrieving relevant documents and adding them to the prompt
    - **Vector Embedding**: a numeric vector that represents the meaning of text, images, or other data

## Big Data
- **Data Lakehouse**: combines a data lake's cheap, flexible storage with a warehouse's structured querying
- **Data Warehouse**: a central repository optimized for analytical queries over large structured datasets
- **Distributed Computing**: splitting data storage and processing across a cluster of machines
    - **MapReduce**: a programming model that processes large datasets in parallel map and reduce steps
- **Distributed Key-Value Store**: a database spread across machines that stores data as sorted key-value pairs
- **Full-Text Search**: indexing text so documents can be searched by words and ranked by relevance

## Business Analytics
- **BI (Business Intelligence)**: turning business data into dashboards and reports that inform decisions
- **Business Model Canvas**: a one-page template for mapping a business's value proposition, customers, channels, and costs
- **Market Research**: gathering and analyzing information about markets, competitors, and customers
- **Spreadsheet**: a grid-based app for organizing, calculating, and charting data

## Data Analytics
- **Observability**: monitoring systems through metrics, logs, and traces to understand their health and performance
- **Web Analytics**: measuring and reporting website traffic, user behavior, and marketing performance
    - **Tracking Pixel**: a snippet on a website that reports visitor actions to an ad platform to measure and optimize ads

## Data Science
- **Computational Notebook**: an interactive document that mixes live code, output, charts, and notes
- **Data App**: an interactive web app that lets users explore data or models
- **Data Cleaning**: fixing incorrect, corrupted, duplicate, or incomplete data
- **Data Mining**: extracting and discovering patterns in large datasets
- **Data Preprocessing**: transforming raw data into a clean, consistent format for analysis or modeling
- **Data Visualization**: representing data graphically with charts, plots, and interactive dashboards
- **Regex (Regular Expression)**: a pattern language for searching, matching, and extracting text
- **Statistical Computing**: using programming languages and software to perform statistical analysis
- **Web Scraping**: automatically extracting data from websites

## Machine Learning
- **AutoML (Automated Machine Learning)**: automating model selection, feature engineering, and hyperparameter tuning
- **Deep Learning**: machine learning with multi-layer neural networks that learn features directly from data
    - **Neural Network**: layers of connected nodes, loosely inspired by the brain, that learn patterns from data
        - **Backpropagation**: computing error gradients layer by layer to update a neural network's weights
        - **CNN (Convolutional Neural Network)**: a neural network that uses convolution filters to learn spatial patterns in images
        - **RNN (Recurrent Neural Network)**: a neural network with loops that processes sequences like text or time series
        - **Transformer**: a neural network architecture built on self-attention that underpins modern LLMs
- **Ensemble Learning**: combining multiple models to get better predictions than any single one
    - **Bagging**: trains models on random subsets of the data and averages their predictions
        - **Random Forest**: an ensemble of decision trees trained with bagging on random subsets of features
    - **Boosting**: trains models sequentially, with each one correcting the errors of the last
        - **AdaBoost**: a boosting method that reweights misclassified examples so later models focus on them
        - **Gradient Boosting**: a boosting method that fits each new tree to the remaining errors of the ensemble
- **Evolutionary Computation**: optimization methods inspired by natural selection and evolution
    - **Genetic Algorithm**: evolves candidate solutions through selection, crossover, and mutation
- **Gradient Descent**: an optimization method that iteratively adjusts parameters in the direction that reduces error
- **ML Framework**: a library for building, training, and running machine learning models
- **ML Platform**: a managed cloud service for building, training, and deploying ML models
- **MLOps (Machine Learning Operations)**: practices for tracking, deploying, and monitoring machine learning models
    - **Experiment Tracking**: logging the parameters, metrics, and artifacts of training runs so they can be compared
- **Preprocessing Pipeline**: chaining data transformations so they are applied consistently in training and inference
- **Regularization**: penalizing model complexity to reduce overfitting
    - **L1 Regularization (Lasso)**: adds the absolute value of weights as a penalty, which can shrink some weights to zero
    - **L2 Regularization (Ridge)**: adds the squared value of weights as a penalty, which keeps all weights small
- **Reinforcement Learning**: training an agent to take actions that maximize rewards through trial and error
    - **AlphaZero**: DeepMind's self-play algorithm that mastered chess, shogi, and Go using tree search and neural networks
- **Supervised Learning**: training models on labeled data to predict outputs from inputs
    - **Decision Tree**: a model that predicts by splitting data on feature values in a tree of if-then rules
    - **KNN (K-Nearest Neighbors)**: predicts from the labels of the closest data points
    - **Linear Regression**: fits a straight line or plane that predicts a numeric value from input features
        - **Multiple Linear Regression**: linear regression with more than one input feature
        - **Polynomial Regression**: regression that fits curved relationships using polynomial features
    - **Logistic Regression**: predicts the probability of a class using a logistic (sigmoid) function
    - **Naive Bayes Classifier**: a probabilistic classifier that applies Bayes' theorem assuming independent features
    - **SVM (Support Vector Machine)**: finds the boundary that separates classes with the widest margin
- **Unsupervised Learning**: finding patterns and structure in unlabeled data
    - **Apriori**: an algorithm that finds frequent itemsets and association rules, as in market basket analysis
    - **Clustering**: grouping similar data points together without predefined labels
        - **Hierarchical Clustering**: builds a tree of nested clusters by repeatedly merging or splitting groups
        - **K-Means**: partitions data into k clusters by assigning points to the nearest cluster center
    - **PCA (Principal Component Analysis)**: reduces data dimensions by projecting onto the directions of greatest variance

## Mathematics
- **Calculus**: the mathematics of continuous change through derivatives and integrals
    - **Differential Calculus**: studies rates of change and slopes of curves through derivatives
    - **Integral Calculus**: studies accumulation, areas, and volumes through integrals
    - **Multivariable Calculus**: extends calculus to functions of several variables, essential for gradients in ML
- **Combinatorics**: the mathematics of counting, arranging, and combining objects
- **Differential Equations**: equations relating functions to their derivatives, used to model change over time
- **Discrete Mathematics**: the study of countable structures such as logic, sets, graphs, and integers
- **Graph Theory**: the study of networks of nodes connected by edges
- **Higher Mathematics**: advanced, proof-based mathematics beyond calculus
- **Linear Algebra**: the mathematics of vectors, matrices, and linear transformations
- **Linear Optimization**: finding the best outcome of a linear objective subject to linear constraints
- **Numerical Analysis**: algorithms for approximating mathematical solutions on computers
- **Probability**: the mathematics of uncertainty and how likely events are
- **Real Analysis**: the rigorous study of real numbers, limits, continuity, and convergence
- **Statistics**: collecting, analyzing, and interpreting data to draw conclusions
    - **Bayesian Statistics**: updating the probability of a hypothesis as new evidence arrives
    - **Multivariate Analysis**: analyzing several variables at once to understand how they relate
    - **Statistical Inference**: drawing conclusions about a population from a sample
    - **Time Series Analysis**: analyzing data points ordered in time to find trends and forecast values
