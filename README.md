# Dialect-Conversion-from-UK-to-US

## 1. Install dependencies using `pip install torch transformers pandas scikit-learn`.
2. Ensure the dataset is available at the specified path.
3. Run the notebook sequentially to train the model and perform inference.

### Dependencies and Installation
- Python 3.8+
- PyTorch
- Transformers (Hugging Face)
- Pandas
- scikit-learn

### Known Limitations and Potential Improvements
- The model may require fine-tuning on a larger dataset for better accuracy.
- Beam search parameters can be adjusted to improve text fluency.
- Limited training data may result in suboptimal translations.

### Handling Time Constraints
- Reduce the number of epochs for faster training.
- Use a smaller dataset subset for quick testing.
"""
print(README)

Why are we Using T5 Transformer?

I am using T5 because it is designed to handle tasks like text translation and text transformation. It works by treating everything as a text-to-text problem. In your case, you are turning UK English into US English, and T5 is good for this because:

    1.  It can easily handle tasks like translation (in your case, dialect conversion).
    2. It has been trained on lots of data and can generalize to different language tasks.
    3. The model works by taking an input text (UK English) and producing an output text (US English) using its encoder-decoder architecture.

In short, T5 is a good fit because it’s flexible, powerful, and trained for tasks like the one you're working on.
