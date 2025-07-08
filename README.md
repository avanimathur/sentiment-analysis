# sentiment-analysis

### Multi-Model Architecture -

- BERT/RoBERTa Integration: Uses emotion-english-distilroberta-base for state-of-the-art accuracy
- TextBlob Analysis: Provides sentiment polarity and subjectivity scores
- VADER Sentiment: Specialized for social media and informal text
- Ensemble Method: Combines all models with weighted predictions (BERT: 60%, others: 20% each)

### Advanced Text Preprocessing

- URL removal and sanitization
- User mention and hashtag cleaning
- Special character handling with emoticon preservation
- Whitespace normalization
- Lowercase conversion

### Evaluation & Metrics Features

1. Comprehensive Performance Metrics

- Accuracy Score: Overall classification accuracy
- Precision: Weighted average across all emotions
- Recall: Weighted average recall scores
- F1-Score: Harmonic mean of precision and recall
- Per-Class Metrics: Individual performance for each emotion

2. Visual Analytics

- Confusion Matrix Heatmap: Shows prediction vs actual emotions
- Performance Bar Charts: Visual representation of all metrics
- Detailed Classification Reports: Per-emotion precision, recall, F1

### Technical Features

1. GPU/CPU Optimization

- Automatic device detection (CUDA/CPU)
- Efficient batch processing
- Memory-optimized operations

2. Dataset Management

- Automatic Download: No manual dataset setup required
- Professional Dataset: Uses Hugging Face's emotion dataset (20K+ samples)
- 6 Emotion Categories: anger, fear, joy, love, sadness, surprise
- Pre-split Data: Train/validation/test splits included
