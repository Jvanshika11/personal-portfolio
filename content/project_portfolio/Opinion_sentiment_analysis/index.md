---
title: 'Opinion Sentiment Analysis using BERT'
date: 2023-02-14
tags: [
    "Natural Language Processing",
    "Deep Learning",
    "Machine Learning",
    "Hugging Face"
]
image: 'cover.png'
github: 'https://github.com/Jvanshika11/Opinion-Sentiment-Analysis'
draft: false
---

Developed a sophisticated multi-class sentiment analysis system using BERT, achieving 80.69% accuracy on aspect-based opinion classification. The project successfully addressed class imbalance challenges through weighted loss functions and optimised model architecture, demonstrating robust performance in categorising opinions as positive, negative, or neutral.

<!--more-->

## Overview
The project tackles the complex challenge of aspect-based sentiment analysis through implementation of advanced transformer architectures. Using a dataset of 1,503 training samples and 376 development samples, the system analyses sentence-aspect-category triplets to determine sentiment polarity. The research particularly focused on addressing significant class imbalance issues, with neutral sentiments comprising only 4% of the dataset, through innovative weighting strategies and architectural optimisations.

## Technologies
- **Development Environment**: Python 3.9
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Deep Learning Framework**: PyTorch, PyTorch Lightning
- **NLP Libraries**: Transformers, NLTK, Stanza
- **Pre-trained Models**: BERT (bert-base-uncased)
- **Dataset Management**: Hugging Face Datasets
- **GPU Acceleration**: CUDA
- **Tokenisation**: SentencePiece
- **Performance Monitoring**: TensorBoard

## Implementation Details

### 1. Model Architecture
- Implemented BERT-based classifier with custom layers
- Developed weighted cross-entropy loss for class imbalance
- Created dropout layers for regularisation
- Implemented softmax-based classification head
- Optimised model for multi-class prediction

### 2. Data Processing
- Created efficient data loading pipeline
- Implemented aspect-category concatenation with [SEP] tokens
- Developed tokenisation framework for input processing
- Created balanced batch sampling strategy
- Implemented dynamic padding for efficiency

### 3. Training Framework
- Implemented AdamW optimiser with learning rate 5e-5
- Developed epoch-based training schedule
- Created comprehensive evaluation pipeline
- Implemented GPU acceleration support
- Developed model checkpointing system

### 4. Performance Optimisation
- Implemented class weighting (1:3:20 ratio)
- Created efficient batch processing system
- Developed early stopping mechanism
- Implemented learning rate scheduling
- Created robust evaluation metrics

### Analysis Features
- Multi-class sentiment distribution analysis
- Model performance tracking
- Class-wise accuracy assessment
- Training convergence monitoring
- Aspect category impact analysis
- Prediction confidence scoring
- Error pattern investigation
- Performance visualisation
- Cross-validation results
- Resource utilisation monitoring

## Key Results
- Achieved 80.69% accuracy on development dataset
- Successfully handled severe class imbalance
- Optimised training time to 9 minutes with GPU
- Processed 1,503 training samples effectively
- Implemented robust 3-class classification
- Established balanced performance metrics
- Demonstrated aspect-based analysis capability
- Achieved consistent cross-run performance

## Skills Gained
- Advanced NLP model implementation
- Deep learning architecture design
- Class imbalance handling techniques
- GPU computing optimisation
- Machine learning pipeline development
- Model evaluation and metrics analysis
- Transfer learning implementation
- Performance optimisation strategies
- Multi-class classification techniques

## Impact
The system provides robust sentiment analysis capabilities for aspect-based opinion mining, particularly valuable for customer feedback analysis and market research. The methodology demonstrates effective handling of class imbalance in natural language processing tasks, offering insights for similar multi-class classification challenges. The project's approach to combining aspect categories with textual content provides a foundation for more nuanced sentiment analysis applications.